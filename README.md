<html lang="vi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Le Perfum Élite | Nước Hoa Cao Cấp Chính Hãng</title>
    <meta name="description" content="Le Perfum Élite - Nhà phân phối nước hoa cao cấp thương hiệu Le Perfum. Sang trọng, quyến rũ và độc bản.">
    <link href="https://fonts.googleapis.com/css2?family=Playfair+Display:wght@400;700&family=Cormorant+Garamond:wght@300;400;500&family=Roboto:wght@300;400&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <style>
        :root {
            --gold: #d4af37;
            --black: #000000;
            --white: #ffffff;
            --gray: #f5f5f5;
        }
        * { margin: 0; padding: 0; box-sizing: border-box; }
        body {
            font-family: 'Roboto', sans-serif;
            background-color: var(--black);
            color: var(--white);
            line-height: 1.6;
            overflow-x: hidden;
        }
        h1, h2, h3, h4 { font-family: 'Playfair Display', serif; }
        
        /* Header */
        header {
            position: fixed;
            top: 0;
            width: 100%;
            background: rgba(0,0,0,0.9);
            z-index: 1000;
            padding: 20px 5%;
            display: flex;
            justify-content: space-between;
            align-items: center;
            backdrop-filter: blur(10px);
        }
        .logo {
            font-family: 'Playfair Display', serif;
            font-size: 28px;
            font-weight: 700;
            color: var(--gold);
            letter-spacing: 3px;
        }
        nav ul {
            list-style: none;
            display: flex;
            gap: 40px;
        }
        nav a {
            color: var(--white);
            text-decoration: none;
            font-weight: 300;
            letter-spacing: 1px;
            transition: 0.3s;
        }
        nav a:hover { color: var(--gold); }
        
        /* Hero Section */
        .hero {
            height: 100vh;
            background: linear-gradient(rgba(0,0,0,0.6), rgba(0,0,0,0.6)), url('https://images.unsplash.com/photo-1541643600923-9bd822a90470?w=1920&q=80') center/cover no-repeat;
            display: flex;
            align-items: center;
            justify-content: center;
            text-align: center;
        }
        .hero-content h1 {
            font-size: 80px;
            font-weight: 400;
            letter-spacing: 8px;
            margin-bottom: 20px;
        }
        .hero-content p {
            font-family: 'Cormorant Garamond', serif;
            font-size: 24px;
            margin-bottom: 40px;
            opacity: 0.9;
        }
        .btn {
            padding: 15px 40px;
            background: transparent;
            border: 1px solid var(--gold);
            color: var(--gold);
            font-size: 14px;
            letter-spacing: 3px;
            cursor: pointer;
            transition: 0.4s;
        }
        .btn:hover {
            background: var(--gold);
            color: var(--black);
        }

        /* Collections */
        .section-title {
            text-align: center;
            padding: 100px 0 60px;
            font-size: 48px;
            letter-spacing: 5px;
        }
        .products {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 40px;
            padding: 0 5%;
            margin-bottom: 100px;
        }
        .product-card {
            background: rgba(255,255,255,0.05);
            overflow: hidden;
            transition: 0.5s;
        }
        .product-card:hover {
            transform: translateY(-20px);
            box-shadow: 0 20px 40px rgba(212,175,55,0.2);
        }
        .product-card img {
            width: 100%;
            height: 400px;
            object-fit: cover;
        }
        .product-info {
            padding: 30px;
            text-align: center;
        }
        .product-info h3 {
            font-size: 24px;
            margin-bottom: 10px;
        }
        .price {
            color: var(--gold);
            font-size: 20px;
            font-weight: 300;
        }

        /* Footer */
        footer {
            background: #111;
            padding: 80px 5% 40px;
            text-align: center;
        }
        .footer-logo {
            font-size: 36px;
            color: var(--gold);
            margin-bottom: 30px;
        }
        .contact-info {
            margin: 40px 0;
            font-size: 16px;
        }
        .contact-info p {
            margin: 10px 0;
        }
        .social-icons a {
            color: var(--white);
            font-size: 20px;
            margin: 0 15px;
            transition: 0.3s;
        }
        .social-icons a:hover { color: var(--gold); }

        @media (max-width: 768px) {
            .hero-content h1 { font-size: 50px; }
            nav ul { gap: 20px; font-size: 14px; }
        }
    </style>
</head>
<body>

    <!-- Header -->
    <header>
        <div class="logo">LE PERFUM ÉLITE</div>
        <nav>
            <ul>
                <li><a href="#">TRANG CHỦ</a></li>
                <li><a href="#">BỘ SƯU TẬP</a></li>
                <li><a href="#">NAM</a></li>
                <li><a href="#">NỮ</a></li>
                <li><a href="#">VỀ CHÚNG TÔI</a></li>
                <li><a href="#">LIÊN HỆ</a></li>
            </ul>
        </nav>
    </header>

    <!-- Hero -->
    <section class="hero">
        <div class="hero-content">
            <h1>LE PERFUM</h1>
            <p>Nghệ thuật của mùi hương đích thực</p>
            <button class="btn">KHÁM PHÁ BỘ SƯU TẬP</button>
        </div>
    </section>
    <!-- Featured Collection -->
<h2 class="section-title">BỘ SƯU TẬP NỔI BẬT</h2>
    <div class="products">
        <div class="product-card">
            <img src="https://images.unsplash.com/photo-1594035910387-fea47794261f?w=800&q=80" alt="Le Perfum Oud Imperial">
            <div class="product-info">
                <h3>Oud Impérial</h3>
                <p>Nồng nàn – Quyền lực – Đẳng cấp</p>
                <div class="price">8.900.000 ₫</div>
            </div>
        </div>
        <div class="product-card">
            <img src="https://images.unsplash.com/photo-1622473596860-0dax7e8e8a41?w=800&q=80" alt="Le Perfum Rose de Nuit">
            <div class="product-info">
                <h3>Rose de Nuit</h3>
                <p>Quyến rũ – Bí ẩn – Sang trọng</p>
                <div class="price">7.200.000 ₫</div>
            </div>
        </div>
        <div class="product-card">
            <img src="https://images.unsplash.com/photo-1604212678438-1d381f85d1d1?w=800&q=80" alt="Le Perfum Ambre Secret">
            <div class="product-info">
                <h3>Ambre Secret</h3>
                <p>Ấm áp – Gợi cảm – Vĩnh cửu</p>
                <div class="price">9.500.000 ₫</div>
            </div>
        </div>
    </div>

    <!-- Footer -->
    <footer>
        <div class="footer-logo">LE PERFUM ÉLITE</div>
        <div class="contact-info">
            <p><i class="fas fa-envelope"></i> Email: tdao22537@gmail.com</p>
            <p><i class="fas fa-phone"></i> Hotline: 0981 506 320</p>
            <p><i class="fas fa-map-marker-alt"></i> Hà Nội | TP. Hồ Chí Minh | Toàn quốc</p>
        </div>
        <div class="social-icons">
            <a href="#"><i class="fab fa-facebook"></i></a>
            <a href="#"><i class="fab fa-instagram"></i></a>
            <a href="#"><i class="fab fa-tiktok"></i></a>
        </div>
        <p style="margin-top: 40px; font-size: 12px; opacity: 0.6;">© 2025 Le Perfum Élite. Tất cả quyền được bảo lưu.</p>
    </footer>

</body>
</html>
