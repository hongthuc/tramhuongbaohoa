<html lang="vi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no">
    <title>Trầm Hương Bảo Hòa - Tinh Hoa Trầm Hương Thiên Nhiên Nông Sơn, Đà Nẵng | tramhuongbaohoa.com</title>
    <meta name="description" content="Trầm Hương Bảo Hòa (tramhuongbaohoa.com) chuyên sản xuất và cung cấp Chuỗi trầm hương 108 hạt, Vòng tay phong thủy, Nhang trầm, Giác xông, Trầm cảnh tự nhiên 100% tại Thị trấn Trung Phước, Nông Sơn, Đà Nẵng.">
    
    <!-- Open Graph Thumbnail là Logo trang web khi gửi link chia sẻ -->
    <meta property="og:type" content="website">
    <meta property="og:url" content="https://tramhuongbaohoa.com/">
    <meta property="og:title" content="Trầm Hương Bảo Hòa - Trầm Hương Thiên Nhiên Uy Tín Đà Nẵng">
    <meta property="og:description" content="Chuyên sỉ & lẻ Chuỗi hạt trầm hương, Vòng tay trầm hương, Nhang trầm sạch, Trầm miếng giác xông, Tượng trầm cảnh thiên nhiên nguyên chất.">
    <meta property="og:image" content="https://drive.google.com/thumbnail?id=15pD64oSReDKPkfb20w4Wpw5Xts8aqP81&sz=w1000">
    <meta name="twitter:card" content="summary_large_image">
    <meta name="twitter:image" content="https://drive.google.com/thumbnail?id=15pD64oSReDKPkfb20w4Wpw5Xts8aqP81&sz=w1000">
    <link rel="icon" href="https://drive.google.com/thumbnail?id=15pD64oSReDKPkfb20w4Wpw5Xts8aqP81&sz=w200" type="image/png">

    <!-- Tailwind CSS -->
    <script src="https://cdn.tailwindcss.com"></script>
    <!-- Font Awesome Icons -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.1/css/all.min.css">
    <!-- Google Fonts: Inter & Playfair Display -->
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700&family=Playfair+Display:wght@600;700&display=swap" rel="stylesheet">

    <script>
        tailwind.config = {
            theme: {
                extend: {
                    colors: {
                        tram: {
                            50: '#fdfaf5',
                            100: '#f7efe2',
                            200: '#eedcc0',
                            300: '#dec093',
                            400: '#cca064',
                            500: '#b8833d',
                            600: '#996629',
                            700: '#6e4519',
                            800: '#4a2c0f',
                            900: '#2e1a07',
                        },
                        gold: {
                            DEFAULT: '#d4af37',
                            light: '#f3e5ab',
                            dark: '#aa820a'
                        }
                    },
                    fontFamily: {
                        sans: ['Inter', 'sans-serif'],
                        serif: ['Playfair Display', 'serif'],
                    }
                }
            }
        }
    </script>

    <style>
        /* Chống tràn viền và chống lệch phải tuyệt đối trên mọi thiết bị */
        *, *::before, *::after {
            box-sizing: border-box;
        }
        html, body {
            width: 100%;
            max-width: 100vw;
            overflow-x: hidden;
            margin: 0;
            padding: 0;
            background-color: #fdfaf5;
            color: #2e1a07;
            scroll-behavior: smooth;
        }

        /* Khung giao diện chuẩn 95% chiều ngang màn hình máy tính */
        .flatsome-container {
            width: 95%;
            max-width: 95%;
            margin-left: auto;
            margin-right: auto;
        }
        @media (max-width: 767px) {
            .flatsome-container {
                width: 94%;
                max-width: 94%;
            }
        }

        /* Tiêu đề Section chuẩn Flatsome UX Builder */
        .section-title-container {
            margin-bottom: 1.25rem;
        }
        .section-title-normal {
            display: flex;
            align-items: center;
            justify-content: space-between;
            border-bottom: 2px solid #eedcc0;
            padding-bottom: 0.5rem;
        }
        .section-title-main {
            font-weight: 700;
            text-transform: uppercase;
            color: #4a2c0f;
            border-bottom: 3px solid #996629;
            margin-bottom: -0.6rem;
            padding-bottom: 0.5rem;
            display: inline-block;
        }
        .section-title-center {
            display: flex;
            align-items: center;
            justify-content: center;
            text-align: center;
            margin-bottom: 1.25rem;
        }
        .section-title-center b {
            flex: 1;
            height: 2px;
            background-color: #dec093;
        }
        .section-title-center span {
            padding: 0 1rem;
            font-weight: 700;
            text-transform: uppercase;
            color: #4a2c0f;
        }

        /* Nhãn giảm giá góc trên bên trái chuẩn Flatsome */
        .badge-container {
            position: absolute;
            top: 8px;
            left: 8px;
            z-index: 10;
            pointer-events: none;
        }
        .onsale-badge {
            background-color: #b91c1c;
            color: #ffffff;
            font-weight: 700;
            font-size: 11px;
            width: 38px;
            height: 38px;
            border-radius: 9999px;
            display: flex;
            align-items: center;
            justify-content: center;
            box-shadow: 0 2px 5px rgba(0,0,0,0.25);
        }

        /* Tối ưu tên danh mục trên máy tính: viết liền trên 1 hàng, không xuống dòng từng mục */
        .cat-nav-item {
            white-space: nowrap;
            display: inline-flex;
            align-items: center;
            transition: all 0.2s ease;
        }

        /* Hiệu ứng nút liên hệ nổi */
        @keyframes pulse-ring {
            0% { transform: scale(0.95); box-shadow: 0 0 0 0 rgba(184, 131, 61, 0.7); }
            70% { transform: scale(1); box-shadow: 0 0 0 10px rgba(184, 131, 61, 0); }
            100% { transform: scale(0.95); box-shadow: 0 0 0 0 rgba(184, 131, 61, 0); }
        }
        .contact-pulse {
            animation: pulse-ring 2s infinite;
        }
    </style>
</head>
<body class="font-sans antialiased">

    <!-- ================= TOP BAR (Đơn giản, chuẩn Flatsome, không có thanh UX Builder) ================= -->
    <div class="bg-tram-900 text-tram-100 text-xs py-1.5 border-b border-tram-700">
        <div class="flatsome-container flex flex-wrap items-center justify-between gap-2">
            <div class="flex items-center gap-3 truncate">
                <span><i class="fa-solid fa-location-dot text-gold mr-1"></i>Thị trấn Trung Phước, Nông Sơn, Đà Nẵng</span>
                <span class="hidden md:inline text-tram-400">|</span>
                <span class="hidden md:inline"><i class="fa-solid fa-globe text-gold mr-1"></i>tramhuongbaohoa.com</span>
            </div>
            <div class="flex items-center gap-4 ml-auto">
                <a href="#bao-gia" class="hover:text-gold transition">Chính sách đại lý</a>
                <span class="text-tram-500">|</span>
                <a href="#lien-he" class="hover:text-gold transition">Hướng dẫn đặt hàng</a>
                <span class="text-tram-500">|</span>
                <a href="https://www.facebook.com/hoai.bao.201781" target="_blank" rel="noopener noreferrer" class="hover:text-gold transition flex items-center gap-1">
                    <i class="fa-brands fa-facebook"></i> Facebook
                </a>
            </div>
        </div>
    </div>

    <!-- ================= HEADER (Logo chỉnh gọn nhỏ lại, không để nút gọi ngay để tránh tràn viền) ================= -->
    <header class="bg-white shadow-sm sticky top-0 z-40 border-b border-tram-200">
        <div class="flatsome-container py-2.5 flex items-center justify-between gap-3">
            
            <!-- Nút Menu Điện Thoại -->
            <button id="mobile-menu-btn" onclick="toggleMobileMenu()" class="lg:hidden p-2 rounded-lg text-tram-800 hover:bg-tram-100 focus:outline-none" aria-label="Mở danh mục">
                <i class="fa-solid fa-bars text-xl"></i>
            </button>

            <!-- Logo Trầm Hương Bảo Hòa (Đã thu gọn nhỏ nhắn, tinh tế) -->
            <a href="#" class="flex items-center gap-2.5 shrink-0">
                <img 
                    src="https://drive.google.com/thumbnail?id=15pD64oSReDKPkfb20w4Wpw5Xts8aqP81&sz=w400" 
                    onerror="this.onerror=null; this.src='https://lh3.googleusercontent.com/d/15pD64oSReDKPkfb20w4Wpw5Xts8aqP81';"
                    alt="Logo Trầm Hương Bảo Hòa" 
                    class="h-9 sm:h-11 w-auto object-contain rounded border border-tram-200 p-0.5 bg-white"
                >
                <div class="leading-tight">
                    <span class="block font-serif font-bold text-sm sm:text-base md:text-lg text-tram-800 tracking-tight">TRẦM HƯƠNG BẢO HÒA</span>
                    <span class="block text-[10px] sm:text-xs text-tram-600 font-medium">tramhuongbaohoa.com</span>
                </div>
            </a>

            <!-- Ô tìm kiếm sản phẩm chuẩn Flatsome -->
            <div class="hidden md:flex flex-1 max-w-xl mx-4">
                <div class="flex w-full border border-tram-300 rounded-full overflow-hidden bg-tram-50 focus-within:border-tram-600">
                    <select id="category-QuickFilter" onchange="filterBySelect(this.value)" class="bg-tram-100 text-tram-800 text-xs px-3 py-2 border-r border-tram-300 focus:outline-none cursor-pointer">
                        <option value="all">Tất cả danh mục</option>
                        <option value="chuoi-tram">Chuỗi trầm hương</option>
                        <option value="vong-tay">Vòng tay phong thủy</option>
                        <option value="nhang-tram">Nhang trầm - Thác lư xông</option>
                        <option value="tram-mieng">Trầm hương miếng - Giác xông</option>
                        <option value="tuong-tram">Tranh - Tượng trầm cảnh</option>
                        <option value="mat-tuong">Mặt tượng đeo cổ</option>
                        <option value="tram-chim">Trầm chìm VIP cao cấp</option>
                    </select>
                    <input 
                        type="text" 
                        id="search-input" 
                        oninput="searchProducts(this.value)"
                        placeholder="Tìm vòng trầm 108 hạt, nhang trầm, giác xông, tượng trầm..." 
                        class="w-full px-3.5 py-2 text-xs bg-transparent focus:outline-none text-tram-900"
                    >
                    <button onclick="searchProducts(document.getElementById('search-input').value)" class="bg-tram-700 hover:bg-tram-800 text-white px-4 text-xs font-medium transition">
                        <i class="fa-solid fa-magnifying-glass"></i>
                    </button>
                </div>
            </div>

            <!-- Liên kết điều hướng nhanh & Giỏ hàng (Không để nút Gọi ngay trên Header) -->
            <div class="flex items-center gap-2 sm:gap-4 shrink-0">
                <nav class="hidden xl:flex items-center gap-4 text-xs font-semibold text-tram-800 uppercase">
                    <a href="#trang-chu" class="text-tram-600 hover:text-tram-900">Trang chủ</a>
                    <a href="#gioi-thieu" class="hover:text-tram-600">Giới thiệu</a>
                    <a href="#san-pham" class="hover:text-tram-600">Sản phẩm</a>
                    <a href="#kien-thuc" class="hover:text-tram-600">Kiến thức</a>
                    <a href="#doi-tac" class="hover:text-tram-600">Đối tác</a>
                    <a href="#lien-he" class="hover:text-tram-600">Liên hệ</a>
                </nav>

                <button onclick="openQuoteModal('Giỏ hàng / Tư vấn đơn hàng')" class="relative inline-flex items-center gap-1.5 px-3 py-1.5 rounded-full bg-tram-100 hover:bg-tram-200 text-tram-800 text-xs font-semibold border border-tram-300 transition">
                    <i class="fa-solid fa-bag-shopping text-tram-700"></i>
                    <span class="hidden sm:inline">Giỏ hàng</span>
                    <span id="cart-count" class="bg-tram-700 text-white text-[10px] w-4 h-4 rounded-full inline-flex items-center justify-center">0</span>
                </button>
            </div>
        </div>

        <!-- Ô tìm kiếm hiển thị gọn trên Điện Thoại -->
        <div class="md:hidden flatsome-container pb-2">
            <div class="flex w-full border border-tram-300 rounded-full overflow-hidden bg-tram-50">
                <input 
                    type="text" 
                    oninput="searchProducts(this.value)"
                    placeholder="Tìm sản phẩm Trầm Hương Bảo Hòa..." 
                    class="w-full px-3.5 py-1.5 text-xs bg-transparent focus:outline-none"
                >
                <button class="bg-tram-700 text-white px-3.5 text-xs">
                    <i class="fa-solid fa-magnifying-glass"></i>
                </button>
            </div>
        </div>

        <!-- THANH DANH MỤC SẢN PHẨM TRÊN MÁY TÍNH (Viết liền trên 1 hàng, chữ nhỏ gọn, tự xuống hàng 2 nguyên cụm nếu màn nhỏ, tuyệt đối không gãy chữ) -->
        <div class="hidden lg:block bg-tram-800 text-white border-t border-tram-700">
            <div class="flatsome-container py-1.5">
                <div class="flex flex-wrap items-center justify-center gap-x-3 gap-y-1 text-[11.5px] font-medium">
                    <button onclick="filterCategory('all')" class="cat-nav-item px-2.5 py-1 rounded bg-gold text-tram-900 font-bold hover:bg-gold-light">
                        <i class="fa-solid fa-table-cells-large mr-1.5"></i>Tất cả sản phẩm
                    </button>
                    <button onclick="filterCategory('chuoi-tram')" class="cat-nav-item px-2 py-1 rounded hover:bg-tram-700 hover:text-gold-light">
                        Chuỗi trầm hương 108 hạt
                    </button>
                    <button onclick="filterCategory('vong-tay')" class="cat-nav-item px-2 py-1 rounded hover:bg-tram-700 hover:text-gold-light">
                        Vòng tay phong thủy
                    </button>
                    <button onclick="filterCategory('boc-vang')" class="cat-nav-item px-2 py-1 rounded hover:bg-tram-700 hover:text-gold-light">
                        Vòng trầm hương bọc vàng
                    </button>
                    <button onclick="filterCategory('mat-tuong')" class="cat-nav-item px-2 py-1 rounded hover:bg-tram-700 hover:text-gold-light">
                        Mặt tượng đeo cổ
                    </button>
                    <button onclick="filterCategory('nhang-tram')" class="cat-nav-item px-2 py-1 rounded hover:bg-tram-700 hover:text-gold-light">
                        Nhang trầm – Thác lư xông
                    </button>
                    <button onclick="filterCategory('tram-mieng')" class="cat-nav-item px-2 py-1 rounded hover:bg-tram-700 hover:text-gold-light">
                        Trầm hương miếng – Giác xông
                    </button>
                    <button onclick="filterCategory('tuong-tram')" class="cat-nav-item px-2 py-1 rounded hover:bg-tram-700 hover:text-gold-light">
                        Tranh – Tượng trầm cảnh
                    </button>
                    <button onclick="filterCategory('tram-chim')" class="cat-nav-item px-2 py-1 rounded hover:bg-tram-700 hover:text-gold-light">
                        Trầm chìm VIP cao cấp
                    </button>
                    <button onclick="filterCategory('vong-be')" class="cat-nav-item px-2 py-1 rounded hover:bg-tram-700 hover:text-gold-light">
                        Vòng đeo cổ & Vòng cho bé
                    </button>
                    <button onclick="filterCategory('qua-tang')" class="cat-nav-item px-2 py-1 rounded hover:bg-tram-700 hover:text-gold-light">
                        Set quà tặng & Tinh dầu
                    </button>
                </div>
            </div>
        </div>
    </header>

    <!-- ================= MENU TRƯỢT TRÊN ĐIỆN THOẠI ================= -->
    <div id="mobile-drawer" class="fixed inset-0 z-50 hidden">
        <div onclick="toggleMobileMenu()" class="fixed inset-0 bg-black/60 backdrop-blur-xs"></div>
        <div class="relative w-72 max-w-[82vw] bg-white h-full shadow-2xl flex flex-col z-10 overflow-y-auto">
            <div class="p-3.5 bg-tram-800 text-white flex items-center justify-between">
                <div class="flex items-center gap-2">
                    <img src="https://drive.google.com/thumbnail?id=15pD64oSReDKPkfb20w4Wpw5Xts8aqP81&sz=w200" alt="Logo" class="h-8 w-8 rounded object-contain bg-white p-0.5">
                    <span class="font-bold text-xs uppercase tracking-wider">Danh Mục Bảo Hòa</span>
                </div>
                <button onclick="toggleMobileMenu()" class="text-white hover:text-gold p-1">
                    <i class="fa-solid fa-xmark text-lg"></i>
                </button>
            </div>
            <div class="p-3 divide-y divide-tram-100 text-xs font-medium text-tram-900">
                <button onclick="filterCategory('all'); toggleMobileMenu();" class="w-full text-left py-2.5 px-2 hover:bg-tram-50 rounded font-bold text-tram-700">
                    <i class="fa-solid fa-Layer-group mr-2"></i>Tất cả sản phẩm
                </button>
                <button onclick="filterCategory('chuoi-tram'); toggleMobileMenu();" class="w-full text-left py-2.5 px-2 hover:bg-tram-50 rounded">
                    Chuỗi trầm hương (108 hạt, 216 hạt)
                </button>
                <button onclick="filterCategory('vong-tay'); toggleMobileMenu();" class="w-full text-left py-2.5 px-2 hover:bg-tram-50 rounded">
                    Vòng tay phong thủy (Nam / Nữ)
                </button>
                <button onclick="filterCategory('boc-vang'); toggleMobileMenu();" class="w-full text-left py-2.5 px-2 hover:bg-tram-50 rounded">
                    Vòng trầm hương bọc vàng
                </button>
                <button onclick="filterCategory('mat-tuong'); toggleMobileMenu();" class="w-full text-left py-2.5 px-2 hover:bg-tram-50 rounded">
                    Mặt tượng đeo cổ
                </button>
                <button onclick="filterCategory('nhang-tram'); toggleMobileMenu();" class="w-full text-left py-2.5 px-2 hover:bg-tram-50 rounded">
                    Nhang trầm – Thác lư xông
                </button>
                <button onclick="filterCategory('tram-mieng'); toggleMobileMenu();" class="w-full text-left py-2.5 px-2 hover:bg-tram-50 rounded">
                    Trầm hương miếng – Giác xông
                </button>
                <button onclick="filterCategory('tuong-tram'); toggleMobileMenu();" class="w-full text-left py-2.5 px-2 hover:bg-tram-50 rounded">
                    Tranh – Tượng trầm cảnh
                </button>
                <button onclick="filterCategory('tram-chim'); toggleMobileMenu();" class="w-full text-left py-2.5 px-2 hover:bg-tram-50 rounded">
                    Trầm chìm VIP cao cấp
                </button>
                <button onclick="filterCategory('vong-be'); toggleMobileMenu();" class="w-full text-left py-2.5 px-2 hover:bg-tram-50 rounded">
                    Vòng đeo cổ & Vòng cho bé
                </button>
                <button onclick="filterCategory('qua-tang'); toggleMobileMenu();" class="w-full text-left py-2.5 px-2 hover:bg-tram-50 rounded">
                    Set quà tặng & Tinh dầu trầm
                </button>
                <div class="pt-3 mt-2 space-y-2">
                    <a href="#bao-gia" onclick="toggleMobileMenu()" class="block py-2 px-3 bg-tram-100 rounded text-center font-semibold text-tram-800">Nhận Báo Giá Sỉ & Lẻ</a>
                    <a href="https://www.facebook.com/hoai.bao.201781" target="_blank" rel="noopener noreferrer" class="block py-2 px-3 bg-blue-600 text-white rounded text-center font-semibold">
                        <i class="fa-brands fa-facebook mr-1"></i>Facebook Bảo Hòa
                    </a>
                </div>
            </div>
        </div>
    </div>

    <!-- ================= 2 ẢNH BANNER TỰ TRƯỢT CHUYÊN NGHIỆP KÍCH THƯỚC BẰNG NHAU ================= -->
    <!-- Hình ảnh và chữ nằm gọn hoàn toàn bên trong, chữ cách xa viền ảnh, không bị thiếu chữ trên cả ĐT và Máy tính -->
    <section id="trang-chu" class="py-3 sm:py-4">
        <div class="flatsome-container">
            <div class="relative rounded-xl overflow-hidden shadow-md border border-tram-200 bg-tram-900">
                
                <!-- Khung cố định chiều cao đồng nhất cho cả 2 Slide -->
                <div id="banner-slider" class="relative w-full h-[270px] sm:h-[330px] md:h-[390px] lg:h-[420px]">
                    
                    <!-- SLIDE 1 -->
                    <div class="banner-slide absolute inset-0 w-full h-full transition-opacity duration-700 opacity-100 z-10 flex items-center"
                         style="background: radial-gradient(circle at 75% 50%, #6e4519 0%, #3a200a 55%, #231204 100%);">
                        <!-- Khoảng đệm an toàn cách xa viền (px-9 sm:px-14 md:px-20) để không bao giờ mất chữ -->
                        <div class="w-full h-full px-9 sm:px-14 md:px-20 py-5 sm:py-8 grid grid-cols-12 items-center gap-3 sm:gap-6">
                            
                            <!-- Khối chữ Slide 1 -->
                            <div class="col-span-7 sm:col-span-7 text-left space-y-1.5 sm:space-y-3">
                                <p class="text-gold-light text-[10px] sm:text-xs md:text-sm font-semibold uppercase tracking-wider">
                                    Tinh Hoa Trầm Hương Xứ Quảng
                                </p>
                                <h1 class="font-serif font-bold text-white text-sm sm:text-xl md:text-3xl lg:text-4xl leading-snug">
                                    TRẦM HƯƠNG BẢO HÒA
                                </h1>
                                <p class="text-tram-100 text-[11px] sm:text-xs md:text-sm leading-relaxed">
                                    Chuyên chế tác Chuỗi Trầm Hương 108 Hạt, Vòng Tay Phong Thủy, Nhang Nụ Trầm & Giác Xông Tự Nhiên 100%.
                                </p>
                                <div class="pt-1 sm:pt-2 flex flex-wrap items-center gap-2 text-[10px] sm:text-xs text-gold-light">
                                    <span><i class="fa-solid fa-location-dot mr-1"></i>Trung Phước, Nông Sơn, Đà Nẵng</span>
                                    <span class="hidden sm:inline">|</span>
                                    <span><i class="fa-solid fa-phone mr-1"></i>0868 222 097 - 0972 511 539</span>
                                </div>
                                <div class="pt-1.5 sm:pt-2">
                                    <a href="#san-pham" class="inline-block bg-gold hover:bg-gold-light text-tram-900 font-bold text-[11px] sm:text-xs md:text-sm px-3.5 sm:px-5 py-1.5 sm:py-2.5 rounded-full shadow transition">
                                        Khám Phá Sản Phẩm
                                    </a>
                                </div>
                            </div>

                            <!-- Khối ảnh thực tế nằm gọn trong Banner 1 -->
                            <div class="col-span-5 sm:col-span-5 flex items-center justify-center h-full">
                                <div class="relative w-28 h-28 sm:w-44 sm:h-44 md:w-56 md:h-56 lg:w-64 lg:h-64 rounded-2xl overflow-hidden border-2 border-gold/60 shadow-2xl bg-tram-800 p-1">
                                    <img 
                                        src="https://drive.google.com/thumbnail?id=1_W7t5anuhxUJ8TJYl0g-n36PxkDUMU-C&sz=w800" 
                                        onerror="this.onerror=null; this.src='https://lh3.googleusercontent.com/d/1_W7t5anuhxUJ8TJYl0g-n36PxkDUMU-C';"
                                        alt="Sản phẩm Trầm Hương Bảo Hòa" 
                                        class="w-full h-full object-cover rounded-xl"
                                    >
                                </div>
                            </div>

                        </div>
                    </div>

                    <!-- SLIDE 2 (Kích thước bằng hệt Slide 1) -->
                    <div class="banner-slide absolute inset-0 w-full h-full transition-opacity duration-700 opacity-0 z-0 flex items-center"
                         style="background: radial-gradient(circle at 25% 50%, #5c3814 0%, #331c08 60%, #1d0f03 100%);">
                        <!-- Khoảng đệm an toàn cách xa viền (px-9 sm:px-14 md:px-20) -->
                        <div class="w-full h-full px-9 sm:px-14 md:px-20 py-5 sm:py-8 grid grid-cols-12 items-center gap-3 sm:gap-6">
                            
                            <!-- Khối chữ Slide 2 -->
                            <div class="col-span-7 sm:col-span-7 text-left space-y-1.5 sm:space-y-3">
                                <p class="text-gold-light text-[10px] sm:text-xs md:text-sm font-semibold uppercase tracking-wider">
                                    Cam Kết Trầm Thật Tự Nhiên 100%
                                </p>
                                <h2 class="font-serif font-bold text-white text-sm sm:text-xl md:text-3xl lg:text-4xl leading-snug">
                                    VẬT PHẨM PHONG THỦY & TRẦM CẢNH VIP
                                </h2>
                                <p class="text-tram-100 text-[11px] sm:text-xs md:text-sm leading-relaxed">
                                    Tuyển chọn từ vùng trầm Nông Sơn danh tiếng: Hương thơm ngọt sâu, vân dầu tự nhiên, chiêu tài đón lộc bình an.
                                </p>
                                <div class="pt-1 sm:pt-2 flex flex-wrap items-center gap-2 text-[10px] sm:text-xs text-gold-light">
                                    <span><i class="fa-solid fa-globe mr-1"></i>tramhuongbaohoa.com</span>
                                    <span class="hidden sm:inline">|</span>
                                    <span><i class="fa-solid fa-truck-fast mr-1"></i>Giao hàng toàn quốc</span>
                                </div>
                                <div class="pt-1.5 sm:pt-2">
                                    <a href="#bao-gia" class="inline-block bg-gold hover:bg-gold-light text-tram-900 font-bold text-[11px] sm:text-xs md:text-sm px-3.5 sm:px-5 py-1.5 sm:py-2.5 rounded-full shadow transition">
                                        Nhận Báo Giá Ngay
                                    </a>
                                </div>
                            </div>

                            <!-- Khối ảnh thực tế nằm gọn trong Banner 2 -->
                            <div class="col-span-5 sm:col-span-5 flex items-center justify-center h-full">
                                <div class="relative w-28 h-28 sm:w-44 sm:h-44 md:w-56 md:h-56 lg:w-64 lg:h-64 rounded-2xl overflow-hidden border-2 border-gold/60 shadow-2xl bg-tram-800 p-1">
                                    <img 
                                        src="https://drive.google.com/thumbnail?id=1hiUWJ0LqaFjQckI9NR0bO7S05EeuQKyy&sz=w800" 
                                        onerror="this.onerror=null; this.src='https://lh3.googleusercontent.com/d/1hiUWJ0LqaFjQckI9NR0bO7S05EeuQKyy';"
                                        alt="Trầm Cảnh & Vòng Trầm Bảo Hòa" 
                                        class="w-full h-full object-cover rounded-xl"
                                    >
                                </div>
                            </div>

                        </div>
                    </div>

                </div>

                <!-- Nút điều hướng trái/phải đặt sát mép ngoài vùng đệm chữ -->
                <button onclick="prevBanner()" class="absolute left-1.5 sm:left-3 top-1/2 -translate-y-1/2 z-20 w-7 h-7 sm:w-9 sm:h-9 rounded-full bg-black/40 hover:bg-gold text-white hover:text-tram-900 flex items-center justify-center transition" aria-label="Slide trước">
                    <i class="fa-solid fa-chevron-left text-xs sm:text-sm"></i>
                </button>
                <button onclick="nextBanner()" class="absolute right-1.5 sm:right-3 top-1/2 -translate-y-1/2 z-20 w-7 h-7 sm:w-9 sm:h-9 rounded-full bg-black/40 hover:bg-gold text-white hover:text-tram-900 flex items-center justify-center transition" aria-label="Slide kế tiếp">
                    <i class="fa-solid fa-chevron-right text-xs sm:text-sm"></i>
                </button>

                <!-- Chấm chỉ báo Slide -->
                <div class="absolute bottom-2.5 left-1/2 -translate-x-1/2 z-20 flex items-center gap-2">
                    <button onclick="goToBanner(0)" id="dot-0" class="w-6 h-2 rounded-full bg-gold transition-all"></button>
                    <button onclick="goToBanner(1)" id="dot-1" class="w-2 h-2 rounded-full bg-white/50 transition-all"></button>
                </div>
            </div>
        </div>
    </section>

    <!-- ================= DANH MỤC SẢN PHẨM TRANG CHỦ (Tối ưu nhỏ gọn, không gãy chữ trên máy tính & điện thoại) ================= -->
    <section class="py-4">
        <div class="flatsome-container">
            <div class="section-title-center">
                <b></b>
                <span class="text-sm sm:text-base md:text-lg">DANH MỤC SẢN PHẨM</span>
                <b></b>
            </div>

            <!-- Chia 2 cột trên ĐT, 5 cột trên Máy tính, chữ danh mục nhỏ gọn trên 1 hàng -->
            <div class="grid grid-cols-2 sm:grid-cols-3 md:grid-cols-5 gap-2.5 sm:gap-3">
                
                <div onclick="filterCategory('chuoi-tram')" class="cursor-pointer group bg-white rounded-xl border border-tram-200 p-2 sm:p-2.5 flex items-center gap-2.5 hover:border-tram-600 hover:shadow-md transition">
                    <img src="https://drive.google.com/thumbnail?id=1_W7t5anuhxUJ8TJYl0g-n36PxkDUMU-C&sz=w300" onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/1_W7t5anuhxUJ8TJYl0g-n36PxkDUMU-C';" alt="Chuỗi trầm hương" class="w-11 h-11 sm:w-12 sm:h-12 rounded-lg object-cover shrink-0 border border-tram-100">
                    <div class="min-w-0 flex-1">
                        <h3 class="text-[11px] sm:text-xs font-bold text-tram-900 group-hover:text-tram-600 whitespace-nowrap overflow-hidden text-ellipsis">Chuỗi trầm 108 hạt</h3>
                        <p class="text-[10px] text-tram-500 whitespace-nowrap">Chuỗi hạt tự nhiên</p>
                    </div>
                </div>

                <div onclick="filterCategory('vong-tay')" class="cursor-pointer group bg-white rounded-xl border border-tram-200 p-2 sm:p-2.5 flex items-center gap-2.5 hover:border-tram-600 hover:shadow-md transition">
                    <img src="https://drive.google.com/thumbnail?id=1hiUWJ0LqaFjQckI9NR0bO7S05EeuQKyy&sz=w300" onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/1hiUWJ0LqaFjQckI9NR0bO7S05EeuQKyy';" alt="Vòng tay phong thủy" class="w-11 h-11 sm:w-12 sm:h-12 rounded-lg object-cover shrink-0 border border-tram-100">
                    <div class="min-w-0 flex-1">
                        <h3 class="text-[11px] sm:text-xs font-bold text-tram-900 group-hover:text-tram-600 whitespace-nowrap overflow-hidden text-ellipsis">Vòng tay phong thủy</h3>
                        <p class="text-[10px] text-tram-500 whitespace-nowrap">Vòng đơn nam & nữ</p>
                    </div>
                </div>

                <div onclick="filterCategory('boc-vang')" class="cursor-pointer group bg-white rounded-xl border border-tram-200 p-2 sm:p-2.5 flex items-center gap-2.5 hover:border-tram-600 hover:shadow-md transition">
                    <img src="https://drive.google.com/thumbnail?id=17n-iriQsii3d4wMGDPs9CA44NN3eUKls&sz=w300" onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/17n-iriQsii3d4wMGDPs9CA44NN3eUKls';" alt="Vòng trầm bọc vàng" class="w-11 h-11 sm:w-12 sm:h-12 rounded-lg object-cover shrink-0 border border-tram-100">
                    <div class="min-w-0 flex-1">
                        <h3 class="text-[11px] sm:text-xs font-bold text-tram-900 group-hover:text-tram-600 whitespace-nowrap overflow-hidden text-ellipsis">Vòng trầm bọc vàng</h3>
                        <p class="text-[10px] text-tram-500 whitespace-nowrap">Mix charm cao cấp</p>
                    </div>
                </div>

                <div onclick="filterCategory('mat-tuong')" class="cursor-pointer group bg-white rounded-xl border border-tram-200 p-2 sm:p-2.5 flex items-center gap-2.5 hover:border-tram-600 hover:shadow-md transition">
                    <img src="https://drive.google.com/thumbnail?id=10CbxE5yeYbCjRdkio9yFOEGxfxbp-tEc&sz=w300" onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/10CbxE5yeYbCjRdkio9yFOEGxfxbp-tEc';" alt="Mặt tượng đeo cổ" class="w-11 h-11 sm:w-12 sm:h-12 rounded-lg object-cover shrink-0 border border-tram-100">
                    <div class="min-w-0 flex-1">
                        <h3 class="text-[11px] sm:text-xs font-bold text-tram-900 group-hover:text-tram-600 whitespace-nowrap overflow-hidden text-ellipsis">Mặt tượng đeo cổ</h3>
                        <p class="text-[10px] text-tram-500 whitespace-nowrap">Chế tác thủ công</p>
                    </div>
                </div>

                <div onclick="filterCategory('nhang-tram')" class="cursor-pointer group bg-white rounded-xl border border-tram-200 p-2 sm:p-2.5 flex items-center gap-2.5 hover:border-tram-600 hover:shadow-md transition">
                    <img src="https://drive.google.com/thumbnail?id=1zJlqndUtnVNwAI6cgXCbnKH5kPUp8AmP&sz=w300" onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/1zJlqndUtnVNwAI6cgXCbnKH5kPUp8AmP';" alt="Nhang trầm thác khói" class="w-11 h-11 sm:w-12 sm:h-12 rounded-lg object-cover shrink-0 border border-tram-100">
                    <div class="min-w-0 flex-1">
                        <h3 class="text-[11px] sm:text-xs font-bold text-tram-900 group-hover:text-tram-600 whitespace-nowrap overflow-hidden text-ellipsis">Nhang trầm – Lư xông</h3>
                        <p class="text-[10px] text-tram-500 whitespace-nowrap">Nụ trầm & không tăm</p>
                    </div>
                </div>

                <div onclick="filterCategory('tram-mieng')" class="cursor-pointer group bg-white rounded-xl border border-tram-200 p-2 sm:p-2.5 flex items-center gap-2.5 hover:border-tram-600 hover:shadow-md transition">
                    <img src="https://drive.google.com/thumbnail?id=1_mg1eE_U5G1r7fr-8mSr9nCWHU4PTh7K&sz=w300" onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/1_mg1eE_U5G1r7fr-8mSr9nCWHU4PTh7K';" alt="Trầm hương miếng giác xông" class="w-11 h-11 sm:w-12 sm:h-12 rounded-lg object-cover shrink-0 border border-tram-100">
                    <div class="min-w-0 flex-1">
                        <h3 class="text-[11px] sm:text-xs font-bold text-tram-900 group-hover:text-tram-600 whitespace-nowrap overflow-hidden text-ellipsis">Trầm miếng – Giác xông</h3>
                        <p class="text-[10px] text-tram-500 whitespace-nowrap">Xông nhà tẩy uế</p>
                    </div>
                </div>

                <div onclick="filterCategory('tuong-tram')" class="cursor-pointer group bg-white rounded-xl border border-tram-200 p-2 sm:p-2.5 flex items-center gap-2.5 hover:border-tram-600 hover:shadow-md transition">
                    <img src="https://drive.google.com/thumbnail?id=1jher5yKrewFqQXyc8d3D616lg19ZeJwO&sz=w300" onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/1jher5yKrewFqQXyc8d3D616lg19ZeJwO';" alt="Tranh tượng trầm cảnh" class="w-11 h-11 sm:w-12 sm:h-12 rounded-lg object-cover shrink-0 border border-tram-100">
                    <div class="min-w-0 flex-1">
                        <h3 class="text-[11px] sm:text-xs font-bold text-tram-900 group-hover:text-tram-600 whitespace-nowrap overflow-hidden text-ellipsis">Tranh – Tượng trầm cảnh</h3>
                        <p class="text-[10px] text-tram-500 whitespace-nowrap">Trưng bày phong thủy</p>
                    </div>
                </div>

                <div onclick="filterCategory('tram-chim')" class="cursor-pointer group bg-white rounded-xl border border-tram-200 p-2 sm:p-2.5 flex items-center gap-2.5 hover:border-tram-600 hover:shadow-md transition">
                    <img src="https://drive.google.com/thumbnail?id=1beSkJ1QeBzyps9m-B7e9bWbYgZnj2YYb&sz=w300" onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/1beSkJ1QeBzyps9m-B7e9bWbYgZnj2YYb';" alt="Trầm chìm VIP cao cấp" class="w-11 h-11 sm:w-12 sm:h-12 rounded-lg object-cover shrink-0 border border-tram-100">
                    <div class="min-w-0 flex-1">
                        <h3 class="text-[11px] sm:text-xs font-bold text-tram-900 group-hover:text-tram-600 whitespace-nowrap overflow-hidden text-ellipsis">Trầm chìm VIP cao cấp</h3>
                        <p class="text-[10px] text-tram-500 whitespace-nowrap">Già dầu thượng hạng</p>
                    </div>
                </div>

                <div onclick="filterCategory('vong-be')" class="cursor-pointer group bg-white rounded-xl border border-tram-200 p-2 sm:p-2.5 flex items-center gap-2.5 hover:border-tram-600 hover:shadow-md transition">
                    <img src="https://drive.google.com/thumbnail?id=1ke_GgfB6dmB8t1A5pz_L0WKwSOKspf0S&sz=w300" onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/1ke_GgfB6dmB8t1A5pz_L0WKwSOKspf0S';" alt="Vòng đeo cổ và cho bé" class="w-11 h-11 sm:w-12 sm:h-12 rounded-lg object-cover shrink-0 border border-tram-100">
                    <div class="min-w-0 flex-1">
                        <h3 class="text-[11px] sm:text-xs font-bold text-tram-900 group-hover:text-tram-600 whitespace-nowrap overflow-hidden text-ellipsis">Vòng cổ & Vòng cho bé</h3>
                        <p class="text-[10px] text-tram-500 whitespace-nowrap">Bình an hộ mệnh</p>
                    </div>
                </div>

                <div onclick="filterCategory('qua-tang')" class="cursor-pointer group bg-white rounded-xl border border-tram-200 p-2 sm:p-2.5 flex items-center gap-2.5 hover:border-tram-600 hover:shadow-md transition">
                    <img src="https://drive.google.com/thumbnail?id=1_W7t5anuhxUJ8TJYl0g-n36PxkDUMU-C&sz=w300" onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/1_W7t5anuhxUJ8TJYl0g-n36PxkDUMU-C';" alt="Set quà tặng trầm hương" class="w-11 h-11 sm:w-12 sm:h-12 rounded-lg object-cover shrink-0 border border-tram-100">
                    <div class="min-w-0 flex-1">
                        <h3 class="text-[11px] sm:text-xs font-bold text-tram-900 group-hover:text-tram-600 whitespace-nowrap overflow-hidden text-ellipsis">Set quà tặng & Tinh dầu</h3>
                        <p class="text-[10px] text-tram-500 whitespace-nowrap">Quà biếu sang trọng</p>
                    </div>
                </div>

            </div>
        </div>
    </section>

    <!-- ================= SẢN PHẨM TRẦM HƯƠNG THỰC TẾ (Chia 2 cột trên ĐT, đầy đủ tên không bị cắt chữ, có % giảm giá góc trái trên) ================= -->
    <section id="san-pham" class="py-5">
        <div class="flatsome-container">
            
            <!-- Phần 1: Sản phẩm nổi bật & bán chạy (9 ảnh thực tế từ Google Drive) -->
            <div class="section-title-container">
                <div class="section-title-normal">
                    <h2 class="section-title-main text-sm sm:text-base md:text-lg">SẢN PHẨM TRẦM HƯƠNG BÁN CHẠY</h2>
                    <button onclick="filterCategory('all')" class="text-xs font-semibold text-tram-700 hover:text-tram-900 whitespace-nowrap">
                        Xem tất cả <i class="fa-solid fa-angle-right ml-1"></i>
                    </button>
                </div>
            </div>

            <!-- Lưới sản phẩm: 2 cột trên Điện Thoại (grid-cols-2), 3 cột trên Tablet, 4-5 cột trên Máy Tính -->
            <div id="product-grid" class="grid grid-cols-2 sm:grid-cols-3 lg:grid-cols-4 xl:grid-cols-5 gap-2.5 sm:gap-4">
                <!-- Đổ dữ liệu bằng JavaScript từ danh sách 9 ảnh thực tế Google Drive -->
            </div>

        </div>
    </section>

    <!-- ================= CHUYÊN MỤC 2: VÒNG TAY PHONG THỦY & CHUỖI TRẦM 108 HẠT ================= -->
    <section class="py-4">
        <div class="flatsome-container">
            <div class="section-title-container">
                <div class="section-title-normal">
                    <h2 class="section-title-main text-sm sm:text-base md:text-lg">VÒNG TAY PHONG THỦY & CHUỖI TRẦM 108 HẠT</h2>
                    <div class="hidden md:flex items-center gap-2 text-xs">
                        <button onclick="filterCategory('chuoi-tram')" class="cat-nav-item px-2 py-0.5 rounded bg-tram-100 hover:bg-tram-200 text-tram-800">Chuỗi 108 hạt</button>
                        <button onclick="filterCategory('vong-tay')" class="cat-nav-item px-2 py-0.5 rounded bg-tram-100 hover:bg-tram-200 text-tram-800">Vòng trầm đơn nam</button>
                        <button onclick="filterCategory('vong-tay')" class="cat-nav-item px-2 py-0.5 rounded bg-tram-100 hover:bg-tram-200 text-tram-800">Vòng trầm đơn nữ</button>
                        <button onclick="filterCategory('boc-vang')" class="cat-nav-item px-2 py-0.5 rounded bg-tram-100 hover:bg-tram-200 text-tram-800">Vòng bọc vàng</button>
                    </div>
                </div>
            </div>

            <div id="bracelet-grid" class="grid grid-cols-2 sm:grid-cols-3 lg:grid-cols-4 xl:grid-cols-5 gap-2.5 sm:gap-4">
                <!-- Đổ dữ liệu bằng JS -->
            </div>
        </div>
    </section>

    <!-- ================= CHUYÊN MỤC 3: NHANG TRẦM - GIÁC XÔNG - VẬT PHẨM PHONG THỦY ================= -->
    <section class="py-4">
        <div class="flatsome-container">
            <div class="section-title-container">
                <div class="section-title-normal">
                    <h2 class="section-title-main text-sm sm:text-base md:text-lg">VẬT PHẨM PHONG THỦY – NHANG TRẦM – TRẦM CẢNH</h2>
                    <div class="hidden md:flex items-center gap-2 text-xs">
                        <button onclick="filterCategory('nhang-tram')" class="cat-nav-item px-2 py-0.5 rounded bg-tram-100 hover:bg-tram-200 text-tram-800">Nhang trầm – Lư xông</button>
                        <button onclick="filterCategory('tram-mieng')" class="cat-nav-item px-2 py-0.5 rounded bg-tram-100 hover:bg-tram-200 text-tram-800">Trầm miếng – Giác xông</button>
                        <button onclick="filterCategory('tuong-tram')" class="cat-nav-item px-2 py-0.5 rounded bg-tram-100 hover:bg-tram-200 text-tram-800">Tranh – Tượng trầm cảnh</button>
                    </div>
                </div>
            </div>

            <div id="incense-grid" class="grid grid-cols-2 sm:grid-cols-3 lg:grid-cols-4 xl:grid-cols-5 gap-2.5 sm:gap-4">
                <!-- Đổ dữ liệu bằng JS -->
            </div>
        </div>
    </section>

    <!-- ================= GIỚI THIỆU VỀ TRẦM HƯƠNG BẢO HÒA (Chuẩn bố cục web mẫu tramhuongdanang.vn) ================= -->
    <section id="gioi-thieu" class="py-6 bg-white border-y border-tram-200 my-4">
        <div class="flatsome-container">
            <div class="section-title-center">
                <b></b>
                <span class="text-sm sm:text-base md:text-lg">TRẦM HƯƠNG BẢO HÒA – UY TÍN TẠI NÔNG SƠN, ĐÀ NẴNG</span>
                <b></b>
            </div>

            <div class="grid grid-cols-1 lg:grid-cols-12 gap-6 items-center">
                <div class="lg:col-span-7 space-y-3 text-xs sm:text-sm text-tram-800 leading-relaxed">
                    <h3 class="text-base sm:text-lg font-serif font-bold text-tram-900">
                        Tinh hoa Trầm Hương Thiên Nhiên từ vùng đất Trung Phước, Nông Sơn
                    </h3>
                    <p>
                        <strong>Trầm Hương Bảo Hòa (<a href="https://tramhuongbaohoa.com" class="text-tram-600 underline">tramhuongbaohoa.com</a>)</strong> tự hào là đơn vị trực tiếp chế tác và phân phối các dòng sản phẩm trầm hương tự nhiên 100% tại <strong>Thị trấn Trung Phước, Nông Sơn, Đà Nẵng</strong> — cái nôi của nghề trầm hương truyền thống danh tiếng xứ Quảng.
                    </p>
                    <p>
                        Cây Dó Bầu qua hàng chục năm tích tụ linh khí đất trời vùng núi Nông Sơn tạo nên những thớ trầm giàu dầu, hương thơm ngọt thanh tao nhã, giúp thư giãn tinh thần, thanh lọc không gian và thu hút tài lộc, vượng khí cho gia chủ.
                    </p>

                    <div class="grid grid-cols-1 sm:grid-cols-2 gap-3 pt-2">
                        <div class="p-3 rounded-xl bg-tram-50 border border-tram-200">
                            <h4 class="font-bold text-tram-900 text-xs sm:text-sm mb-1"><i class="fa-solid fa-circle-check text-tram-600 mr-1.5"></i>100% Trầm Hương Tự Nhiên</h4>
                            <p class="text-xs text-tram-700">Cam kết trầm thật nguyên chất từ cây Dó Bầu, không tẩm hóa chất hay hương liệu nhân tạo.</p>
                        </div>
                        <div class="p-3 rounded-xl bg-tram-50 border border-tram-200">
                            <h4 class="font-bold text-tram-900 text-xs sm:text-sm mb-1"><i class="fa-solid fa-gem text-tram-600 mr-1.5"></i>Chế Tác Tinh Xảo Đa Dạng</h4>
                            <p class="text-xs text-tram-700">Đầy đủ chuỗi hạt 108 hạt, vòng tay nam nữ, tượng Phật trầm hương, giác xông, nhang trầm sạch.</p>
                        </div>
                        <div class="p-3 rounded-xl bg-tram-50 border border-tram-200">
                            <h4 class="font-bold text-tram-900 text-xs sm:text-sm mb-1"><i class="fa-solid fa-shield-heart text-tram-600 mr-1.5"></i>An Toàn Cho Sức Khỏe</h4>
                            <p class="text-xs text-tram-700">Hương thơm dịu ngọt tự nhiên giúp giảm căng thẳng, an thần, ngủ ngon và tịnh tâm.</p>
                        </div>
                        <div class="p-3 rounded-xl bg-tram-50 border border-tram-200">
                            <h4 class="font-bold text-tram-900 text-xs sm:text-sm mb-1"><i class="fa-solid fa-headset text-tram-600 mr-1.5"></i>Giá Gốc Xưởng & Bảo Hành Uy Tín</h4>
                            <p class="text-xs text-tram-700">Sản xuất trực tiếp tại Nông Sơn không qua trung gian, tư vấn hợp mệnh phong thủy tận tâm.</p>
                        </div>
                    </div>
                </div>

                <!-- Khung hình ảnh thực tế xưởng & sản phẩm Trầm Hương Bảo Hòa -->
                <div class="lg:col-span-5 grid grid-cols-2 gap-2.5">
                    <img src="https://drive.google.com/thumbnail?id=17n-iriQsii3d4wMGDPs9CA44NN3eUKls&sz=w600" onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/17n-iriQsii3d4wMGDPs9CA44NN3eUKls';" alt="Trầm Hương Bảo Hòa 1" class="w-full h-36 sm:h-44 object-cover rounded-xl border border-tram-200 shadow-xs">
                    <img src="https://drive.google.com/thumbnail?id=10CbxE5yeYbCjRdkio9yFOEGxfxbp-tEc&sz=w600" onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/10CbxE5yeYbCjRdkio9yFOEGxfxbp-tEc';" alt="Trầm Hương Bảo Hòa 2" class="w-full h-36 sm:h-44 object-cover rounded-xl border border-tram-200 shadow-xs">
                    <img src="https://drive.google.com/thumbnail?id=1zJlqndUtnVNwAI6cgXCbnKH5kPUp8AmP&sz=w600" onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/1zJlqndUtnVNwAI6cgXCbnKH5kPUp8AmP';" alt="Trầm Hương Bảo Hòa 3" class="w-full h-36 sm:h-44 object-cover rounded-xl border border-tram-200 shadow-xs">
                    <img src="https://drive.google.com/thumbnail?id=1_mg1eE_U5G1r7fr-8mSr9nCWHU4PTh7K&sz=w600" onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/1_mg1eE_U5G1r7fr-8mSr9nCWHU4PTh7K';" alt="Trầm Hương Bảo Hòa 4" class="w-full h-36 sm:h-44 object-cover rounded-xl border border-tram-200 shadow-xs">
                </div>
            </div>
        </div>
    </section>

    <!-- ================= FORM YÊU CẦU TƯ VẤN & BÁO GIÁ + FACEBOOK RA NGOÀI TRANG CHỦ ================= -->
    <section id="bao-gia" class="py-6">
        <div class="flatsome-container">
            <div class="grid grid-cols-1 lg:grid-cols-12 gap-6">
                
                <!-- Cột Trái (7 cột): Form Yêu Cầu & Báo Giá Trang Chủ -->
                <div class="lg:col-span-7 bg-white rounded-2xl shadow-sm border border-tram-200 p-4 sm:p-6">
                    <div class="section-title-normal mb-4">
                        <h2 class="section-title-main text-sm sm:text-base md:text-lg">
                            <i class="fa-solid fa-file-signature text-tram-600 mr-1.5"></i>ĐĂNG KÝ TƯ VẤN & NHẬN BÁO GIÁ TRẦM HƯƠNG
                        </h2>
                    </div>
                    <p class="text-xs text-tram-700 mb-4">
                        Quý khách cần tư vấn chọn vòng trầm hợp mệnh, đặt làm quà biếu hoặc nhận bảng báo giá sỉ đại lý của <strong>Trầm Hương Bảo Hòa</strong>, vui lòng để lại thông tin bên dưới:
                    </p>

                    <form id="homepage-quote-form" onsubmit="submitQuoteForm(event)" class="space-y-3">
                        <div class="grid grid-cols-1 sm:grid-cols-2 gap-3">
                            <div>
                                <label class="block text-xs font-semibold text-tram-800 mb-1">Họ và tên quý khách *</label>
                                <input type="text" id="q-name" required placeholder="Nhập họ và tên..." class="w-full px-3 py-2 text-xs rounded-lg border border-tram-300 bg-tram-50 focus:outline-none focus:border-tram-700">
                            </div>
                            <div>
                                <label class="block text-xs font-semibold text-tram-800 mb-1">Số điện thoại / Zalo *</label>
                                <input type="tel" id="q-phone" required placeholder="Ví dụ: 0868 222 097" class="w-full px-3 py-2 text-xs rounded-lg border border-tram-300 bg-tram-50 focus:outline-none focus:border-tram-700">
                            </div>
                        </div>

                        <div class="grid grid-cols-1 sm:grid-cols-2 gap-3">
                            <div>
                                <label class="block text-xs font-semibold text-tram-800 mb-1">Danh mục sản phẩm quan tâm</label>
                                <select id="q-category" class="w-full px-3 py-2 text-xs rounded-lg border border-tram-300 bg-tram-50 focus:outline-none focus:border-tram-700">
                                    <option value="Chuỗi trầm hương 108 hạt">Chuỗi trầm hương 108 hạt</option>
                                    <option value="Vòng tay trầm hương Nam / Nữ">Vòng tay trầm hương Nam / Nữ</option>
                                    <option value="Vòng trầm hương bọc vàng">Vòng trầm hương bọc vàng</option>
                                    <option value="Nhang trầm - Nụ trầm - Thác khói">Nhang trầm - Nụ trầm - Thác khói</option>
                                    <option value="Trầm miếng - Giác xông nhà">Trầm miếng - Giác xông nhà</option>
                                    <option value="Tranh - Tượng trầm cảnh phong thủy">Tranh - Tượng trầm cảnh phong thủy</option>
                                    <option value="Trầm chìm VIP cao cấp">Trầm chìm VIP cao cấp</option>
                                    <option value="Đăng ký đại lý / Báo giá sỉ">Đăng ký đại lý / Báo giá sỉ</option>
                                </select>
                            </div>
                            <div>
                                <label class="block text-xs font-semibold text-tram-800 mb-1">Hình thức mua hàng</label>
                                <select id="q-type" class="w-full px-3 py-2 text-xs rounded-lg border border-tram-300 bg-tram-50 focus:outline-none focus:border-tram-700">
                                    <option value="Mua lẻ sử dụng / Làm quà tặng">Mua lẻ sử dụng / Làm quà tặng</option>
                                    <option value="Mua sỉ / Hợp tác đại lý">Mua sỉ / Hợp tác đại lý</option>
                                    <option value="Đặt chế tác theo yêu cầu">Đặt chế tác theo yêu cầu riêng</option>
                                </select>
                            </div>
                        </div>

                        <div>
                            <label class="block text-xs font-semibold text-tram-800 mb-1">Nội dung yêu cầu chi tiết</label>
                            <textarea id="q-note" rows="3" placeholder="Nhập kích thước hạt (8mm, 10mm, 12mm...), mệnh ngũ hành hoặc số lượng cần báo giá..." class="w-full px-3 py-2 text-xs rounded-lg border border-tram-300 bg-tram-50 focus:outline-none focus:border-tram-700"></textarea>
                        </div>

                        <div class="flex flex-wrap items-center justify-between gap-3 pt-1">
                            <button type="submit" class="bg-tram-800 hover:bg-tram-900 text-gold-light font-bold text-xs sm:text-sm px-6 py-2.5 rounded-lg shadow transition cursor-pointer">
                                <i class="fa-solid fa-paper-plane mr-1.5"></i>GỬI YÊU CẦU BÁO GIÁ
                            </button>
                            <div class="text-xs text-tram-700">
                                Hoặc liên hệ trực tiếp: <strong class="text-tram-900">0868 222 097 - 0972 511 539</strong>
                            </div>
                        </div>
                    </form>

                    <!-- Thông báo gửi thành công -->
                    <div id="quote-success-msg" class="hidden mt-3 p-3 rounded-lg bg-green-50 border border-green-300 text-green-800 text-xs">
                        <i class="fa-solid fa-circle-check mr-1"></i>
                        Đã ghi nhận yêu cầu báo giá của quý khách! Trầm Hương Bảo Hòa sẽ liên hệ qua số điện thoại/Zalo trong thời gian sớm nhất.
                    </div>
                </div>

                <!-- Cột Phải (5 cột): Đưa Facebook https://www.facebook.com/hoai.bao.201781 ra ngoài trang chủ -->
                <div class="lg:col-span-5 bg-white rounded-2xl shadow-sm border border-tram-200 p-4 sm:p-6 flex flex-col justify-between">
                    <div>
                        <div class="section-title-normal mb-4">
                            <h2 class="section-title-main text-sm sm:text-base md:text-lg">
                                <i class="fa-brands fa-facebook text-blue-600 mr-1.5"></i>KẾT NỐI FACEBOOK TRẦM HƯƠNG BẢO HÒA
                            </h2>
                        </div>

                        <!-- Khung hiển thị trang Facebook nổi bật ngoài trang chủ -->
                        <div class="rounded-xl overflow-hidden border border-tram-200 bg-tram-50">
                            <div class="h-28 bg-gradient-to-r from-tram-900 via-tram-700 to-tram-800 relative flex items-center px-4">
                                <div class="flex items-center gap-3">
                                    <img 
                                        src="https://drive.google.com/thumbnail?id=15pD64oSReDKPkfb20w4Wpw5Xts8aqP81&sz=w300" 
                                        onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/15pD64oSReDKPkfb20w4Wpw5Xts8aqP81';"
                                        alt="Trầm Hương Bảo Hòa Facebook" 
                                        class="w-16 h-16 rounded-full border-2 border-gold bg-white object-contain p-1 shadow-md shrink-0"
                                    >
                                    <div class="text-white">
                                        <h3 class="font-bold text-sm sm:text-base flex items-center gap-1.5">
                                            Trầm Hương Bảo Hòa <i class="fa-solid fa-circle-check text-blue-400 text-xs"></i>
                                        </h3>
                                        <p class="text-[11px] text-gold-light">Lê Hoài Bảo • Nông Sơn, Đà Nẵng</p>
                                        <p class="text-[11px] text-tram-200 truncate max-w-[210px] sm:max-w-xs">facebook.com/hoai.bao.201781</p>
                                    </div>
                                </div>
                            </div>

                            <div class="p-4 space-y-3 text-xs text-tram-800">
                                <p class="leading-relaxed">
                                    Cập nhật video test trầm thực tế, hình ảnh vòng trầm hương tự nhiên, phôi trầm cảnh Nông Sơn mới nhất mỗi ngày trên Facebook chính thức.
                                </p>
                                <div class="grid grid-cols-3 gap-2">
                                    <img src="https://drive.google.com/thumbnail?id=1jher5yKrewFqQXyc8d3D616lg19ZeJwO&sz=w300" onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/1jher5yKrewFqQXyc8d3D616lg19ZeJwO';" alt="Ảnh FB 1" class="w-full h-16 object-cover rounded border border-tram-200">
                                    <img src="https://drive.google.com/thumbnail?id=1beSkJ1QeBzyps9m-B7e9bWbYgZnj2YYb&sz=w300" onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/1beSkJ1QeBzyps9m-B7e9bWbYgZnj2YYb';" alt="Ảnh FB 2" class="w-full h-16 object-cover rounded border border-tram-200">
                                    <img src="https://drive.google.com/thumbnail?id=1ke_GgfB6dmB8t1A5pz_L0WKwSOKspf0S&sz=w300" onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/1ke_GgfB6dmB8t1A5pz_L0WKwSOKspf0S';" alt="Ảnh FB 3" class="w-full h-16 object-cover rounded border border-tram-200">
                                </div>
                                <div class="pt-1 flex flex-wrap gap-2">
                                    <a href="https://www.facebook.com/hoai.bao.201781" target="_blank" rel="noopener noreferrer" class="flex-1 text-center bg-blue-600 hover:bg-blue-700 text-white font-bold py-2.5 px-4 rounded-lg transition">
                                        <i class="fa-brands fa-facebook mr-1.5"></i>Truy Cập Facebook Ngay
                                    </a>
                                    <a href="https://zalo.me/0868222097" target="_blank" rel="noopener noreferrer" class="text-center bg-tram-700 hover:bg-tram-800 text-white font-bold py-2.5 px-4 rounded-lg transition">
                                        Chat Zalo
                                    </a>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>

            </div>
        </div>
    </section>

    <!-- ================= DANH MỤC CÁC BÀI VIẾT & KIẾN THỨC PHONG THỦY TRANG CHỦ ================= -->
    <section id="kien-thuc" class="py-5">
        <div class="flatsome-container">
            <div class="section-title-container">
                <div class="section-title-normal">
                    <h2 class="section-title-main text-sm sm:text-base md:text-lg">KIẾN THỨC PHONG THỦY & TIN TỨC TRẦM HƯƠNG</h2>
                    <span class="text-xs text-tram-600">Cẩm nang chơi trầm</span>
                </div>
            </div>

            <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-4 gap-4">
                
                <!-- Bài viết 1 -->
                <article class="bg-white rounded-xl overflow-hidden border border-tram-200 shadow-xs hover:shadow-md transition flex flex-col">
                    <div class="h-40 overflow-hidden bg-tram-100">
                        <img src="https://drive.google.com/thumbnail?id=1beSkJ1QeBzyps9m-B7e9bWbYgZnj2YYb&sz=w600" onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/1beSkJ1QeBzyps9m-B7e9bWbYgZnj2YYb';" alt="Trầm hương chìm nước là gì" class="w-full h-full object-cover hover:scale-105 transition duration-500">
                    </div>
                    <div class="p-3.5 flex-1 flex flex-col justify-between">
                        <div>
                            <span class="text-[10px] text-tram-500 font-medium">Kiến thức trầm hương • 12/03/2026</span>
                            <h3 class="font-bold text-xs sm:text-sm text-tram-900 mt-1 mb-1.5 leading-snug">
                                Trầm Hương Chìm Nước Là Gì? Vì Sao Giá Trị Cao Hơn Các Loại Trầm Khác?
                            </h3>
                            <p class="text-xs text-tram-700 leading-relaxed">
                                Tìm hiểu nguyên nhân tích tụ lượng tinh dầu lớn trong thớ gỗ Dó Bầu giúp khối trầm chìm hoàn toàn dưới nước và giá trị sưu tầm cao.
                            </p>
                        </div>
                        <button onclick="openArticleModal(0)" class="mt-3 text-left text-xs font-semibold text-tram-700 hover:text-tram-900">
                            Đọc chi tiết <i class="fa-solid fa-arrow-right ml-1"></i>
                        </button>
                    </div>
                </article>

                <!-- Bài viết 2 -->
                <article class="bg-white rounded-xl overflow-hidden border border-tram-200 shadow-xs hover:shadow-md transition flex flex-col">
                    <div class="h-40 overflow-hidden bg-tram-100">
                        <img src="https://drive.google.com/thumbnail?id=1_W7t5anuhxUJ8TJYl0g-n36PxkDUMU-C&sz=w600" onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/1_W7t5anuhxUJ8TJYl0g-n36PxkDUMU-C';" alt="Cách phân biệt trầm hương thật giả" class="w-full h-full object-cover hover:scale-105 transition duration-500">
                    </div>
                    <div class="p-3.5 flex-1 flex flex-col justify-between">
                        <div>
                            <span class="text-[10px] text-tram-500 font-medium">Kinh nghiệm chọn trầm • 25/02/2026</span>
                            <h3 class="font-bold text-xs sm:text-sm text-tram-900 mt-1 mb-1.5 leading-snug">
                                Cách Phân Biệt Trầm Hương Tự Nhiên Thật Và Giả Chuẩn Xác Nhất
                            </h3>
                            <p class="text-xs text-tram-700 leading-relaxed">
                                Hướng dẫn quan sát vân dầu tự nhiên, cảm nhận mùi hương dịu ngọt khi ma sát hoặc đốt nhẹ để nhận biết trầm hương Nông Sơn chuẩn.
                            </p>
                        </div>
                        <button onclick="openArticleModal(1)" class="mt-3 text-left text-xs font-semibold text-tram-700 hover:text-tram-900">
                            Đọc chi tiết <i class="fa-solid fa-arrow-right ml-1"></i>
                        </button>
                    </div>
                </article>

                <!-- Bài viết 3 -->
                <article class="bg-white rounded-xl overflow-hidden border border-tram-200 shadow-xs hover:shadow-md transition flex flex-col">
                    <div class="h-40 overflow-hidden bg-tram-100">
                        <img src="https://drive.google.com/thumbnail?id=1hiUWJ0LqaFjQckI9NR0bO7S05EeuQKyy&sz=w600" onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/1hiUWJ0LqaFjQckI9NR0bO7S05EeuQKyy';" alt="Ý nghĩa đeo vòng tay trầm hương 108 hạt" class="w-full h-full object-cover hover:scale-105 transition duration-500">
                    </div>
                    <div class="p-3.5 flex-1 flex flex-col justify-between">
                        <div>
                            <span class="text-[10px] text-tram-500 font-medium">Kiến thức phong thủy • 10/02/2026</span>
                            <h3 class="font-bold text-xs sm:text-sm text-tram-900 mt-1 mb-1.5 leading-snug">
                                Đeo Vòng Tay Trầm Hương 108 Hạt Có Tác Dụng Gì Trong Phong Thủy?
                            </h3>
                            <p class="text-xs text-tram-700 leading-relaxed">
                                Chuỗi 108 hạt tượng trưng cho việc đoạn trừ 108 phiền não, mang lại sự bình an, minh mẫn và thu hút năng lượng tích cực mỗi ngày.
                            </p>
                        </div>
                        <button onclick="openArticleModal(2)" class="mt-3 text-left text-xs font-semibold text-tram-700 hover:text-tram-900">
                            Đọc chi tiết <i class="fa-solid fa-arrow-right ml-1"></i>
                        </button>
                    </div>
                </article>

                <!-- Bài viết 4 -->
                <article class="bg-white rounded-xl overflow-hidden border border-tram-200 shadow-xs hover:shadow-md transition flex flex-col">
                    <div class="h-40 overflow-hidden bg-tram-100">
                        <img src="https://drive.google.com/thumbnail?id=1_mg1eE_U5G1r7fr-8mSr9nCWHU4PTh7K&sz=w600" onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/1_mg1eE_U5G1r7fr-8mSr9nCWHU4PTh7K';" alt="Trầm hương xông nhà có tác dụng gì" class="w-full h-full object-cover hover:scale-105 transition duration-500">
                    </div>
                    <div class="p-3.5 flex-1 flex flex-col justify-between">
                        <div>
                            <span class="text-[10px] text-tram-500 font-medium">Văn hóa thưởng trầm • 02/02/2026</span>
                            <h3 class="font-bold text-xs sm:text-sm text-tram-900 mt-1 mb-1.5 leading-snug">
                                Trầm Hương Xông Nhà Có Tác Dụng Gì? Hướng Dẫn Xông Trầm Đúng Cách
                            </h3>
                            <p class="text-xs text-tram-700 leading-relaxed">
                                Xông trầm hương miếng và nụ trầm khi tân gia, khai trương hay dịp lễ Tết giúp thanh lọc không khí, xua tà khí và đón vượng khí.
                            </p>
                        </div>
                        <button onclick="openArticleModal(3)" class="mt-3 text-left text-xs font-semibold text-tram-700 hover:text-tram-900">
                            Đọc chi tiết <i class="fa-solid fa-arrow-right ml-1"></i>
                        </button>
                    </div>
                </article>

            </div>
        </div>
    </section>

    <!-- ================= DANH MỤC CÁC ĐỐI TÁC TRANG CHỦ ================= -->
    <section id="doi-tac" class="py-5 bg-white border-t border-tram-200">
        <div class="flatsome-container">
            <div class="section-title-center">
                <b></b>
                <span class="text-sm sm:text-base md:text-lg">DANH MỤC ĐỐI TÁC & KHÁCH HÀNG TIÊU BIỂU</span>
                <b></b>
            </div>

            <div class="grid grid-cols-2 sm:grid-cols-3 lg:grid-cols-6 gap-3">
                <div class="p-3 rounded-xl bg-tram-50 border border-tram-200 text-center flex flex-col items-center justify-center">
                    <i class="fa-solid fa-award text-2xl text-tram-700 mb-1.5"></i>
                    <h4 class="font-bold text-xs text-tram-900">Hội Trầm Hương Xứ Quảng</h4>
                    <p class="text-[11px] text-tram-600">Đối tác làng nghề</p>
                </div>
                <div class="p-3 rounded-xl bg-tram-50 border border-tram-200 text-center flex flex-col items-center justify-center">
                    <i class="fa-solid fa-yin-yang text-2xl text-tram-700 mb-1.5"></i>
                    <h4 class="font-bold text-xs text-tram-900">Phong Thủy Tâm An</h4>
                    <p class="text-[11px] text-tram-600">Đại lý phân phối</p>
                </div>
                <div class="p-3 rounded-xl bg-tram-50 border border-tram-200 text-center flex flex-col items-center justify-center">
                    <i class="fa-solid fa-gift text-2xl text-tram-700 mb-1.5"></i>
                    <h4 class="font-bold text-xs text-tram-900">Quà Tặng Doanh Nghiệp ĐN</h4>
                    <p class="text-[11px] text-tram-600">Đối tác quà biếu VIP</p>
                </div>
                <div class="p-3 rounded-xl bg-tram-50 border border-tram-200 text-center flex flex-col items-center justify-center">
                    <i class="fa-solid fa-spa text-2xl text-tram-700 mb-1.5"></i>
                    <h4 class="font-bold text-xs text-tram-900">Thiền & Trà Đạo Việt</h4>
                    <p class="text-[11px] text-tram-600">Đối tác thưởng trầm</p>
                </div>
                <div class="p-3 rounded-xl bg-tram-50 border border-tram-200 text-center flex flex-col items-center justify-center">
                    <i class="fa-solid fa-gem text-2xl text-tram-700 mb-1.5"></i>
                    <h4 class="font-bold text-xs text-tram-900">Trang Sức Phong Thủy Bảo Ngọc</h4>
                    <p class="text-[11px] text-tram-600">Đối tác chế tác charm</p>
                </div>
                <div class="p-3 rounded-xl bg-tram-50 border border-tram-200 text-center flex flex-col items-center justify-center">
                    <i class="fa-solid fa-plane-departure text-2xl text-tram-700 mb-1.5"></i>
                    <h4 class="font-bold text-xs text-tram-900">Trầm Hương Xuất Khẩu Á Châu</h4>
                    <p class="text-[11px] text-tram-600">Đối tác thương mại</p>
                </div>
            </div>
        </div>
    </section>

    <!-- ================= BẢN ĐỒ GOOGLE MAPS NGOÀI TRANG CHỦ & THÔNG TIN LIÊN HỆ ================= -->
    <section id="lien-he" class="py-6 bg-tram-100/60 border-t border-tram-200">
        <div class="flatsome-container">
            <div class="section-title-center">
                <b></b>
                <span class="text-sm sm:text-base md:text-lg">BẢN ĐỒ ĐỊA CHỈ TRẦM HƯƠNG BẢO HÒA</span>
                <b></b>
            </div>

            <div class="grid grid-cols-1 lg:grid-cols-12 gap-5 items-stretch">
                
                <!-- Thông tin địa chỉ & Hotline -->
                <div class="lg:col-span-5 bg-white p-4 sm:p-5 rounded-2xl border border-tram-200 shadow-xs flex flex-col justify-between space-y-4">
                    <div class="space-y-3">
                        <div class="flex items-center gap-3">
                            <img src="https://drive.google.com/thumbnail?id=15pD64oSReDKPkfb20w4Wpw5Xts8aqP81&sz=w200" onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/15pD64oSReDKPkfb20w4Wpw5Xts8aqP81';" alt="Logo" class="w-12 h-12 rounded-lg object-contain border border-tram-200 p-0.5 bg-white">
                            <div>
                                <h3 class="font-serif font-bold text-sm sm:text-base text-tram-900">CÔNG TY TNHH MTV TRẦM HƯƠNG BẢO HÒA</h3>
                                <p class="text-xs text-tram-600">Website: tramhuongbaohoa.com</p>
                            </div>
                        </div>

                        <div class="space-y-2.5 text-xs sm:text-sm text-tram-800 pt-2 border-t border-tram-100">
                            <p class="flex items-start gap-2.5">
                                <i class="fa-solid fa-location-dot text-tram-700 mt-1 shrink-0"></i>
                                <span><strong>Địa chỉ:</strong> Thị trấn Trung Phước, Nông Sơn, Đà Nẵng</span>
                            </p>
                            <p class="flex items-start gap-2.5">
                                <i class="fa-solid fa-phone-volume text-tram-700 mt-1 shrink-0"></i>
                                <span>
                                    <strong>Hotline / Zalo:</strong> 
                                    <a href="tel:0868222097" class="text-tram-700 font-bold hover:underline">0868 222 097</a> - 
                                    <a href="tel:0972511539" class="text-tram-700 font-bold hover:underline">0972 511 539</a>
                                </span>
                            </p>
                            <p class="flex items-start gap-2.5">
                                <i class="fa-brands fa-facebook text-blue-600 mt-1 shrink-0"></i>
                                <span>
                                    <strong>Facebook:</strong> 
                                    <a href="https://www.facebook.com/hoai.bao.201781" target="_blank" rel="noopener noreferrer" class="text-blue-600 hover:underline break-all">
                                        https://www.facebook.com/hoai.bao.201781
                                    </a>
                                </span>
                            </p>
                            <p class="flex items-start gap-2.5">
                                <i class="fa-solid fa-clock text-tram-700 mt-1 shrink-0"></i>
                                <span><strong>Giờ mở cửa:</strong> 07:30 – 21:30 (Tất cả các ngày trong tuần)</span>
                            </p>
                        </div>
                    </div>

                    <div class="pt-2 flex flex-wrap gap-2">
                        <a href="https://www.google.com/maps/place//data=!4m2!3m1!19sChIJT8xRRHj_aTERiWyV2tuKHtA" target="_blank" rel="noopener noreferrer" class="flex-1 text-center bg-tram-800 hover:bg-tram-900 text-gold-light text-xs font-bold py-2.5 px-4 rounded-lg transition">
                            <i class="fa-solid fa-map-location-dot mr-1.5"></i>Mở Google Maps Chỉ Đường
                        </a>
                    </div>
                </div>

                <!-- Bản đồ Google Map hiển thị trực tiếp ngoài trang chủ -->
                <div class="lg:col-span-7 bg-white p-2 rounded-2xl border border-tram-200 shadow-xs min-h-[280px] sm:min-h-[320px] flex flex-col">
                    <iframe 
                        title="Bản đồ Trầm Hương Bảo Hòa - Thị trấn Trung Phước, Nông Sơn, Đà Nẵng"
                        src="https://maps.google.com/maps?q=Trung%20Ph%C6%B0%E1%BB%9Bc,%20N%C3%B4ng%20S%C6%A1n&t=&z=14&ie=UTF8&iwloc=&output=embed" 
                        class="w-full h-full min-h-[270px] sm:min-h-[310px] rounded-xl border-0" 
                        allowfullscreen="" 
                        loading="lazy" 
                        referrerpolicy="no-referrer-when-downgrade">
                    </iframe>
                </div>

            </div>
        </div>
    </section>

    <!-- ================= FOOTER CHUẨN FLATSOME ================= -->
    <footer class="bg-tram-900 text-tram-100 pt-8 pb-20 md:pb-8 border-t-4 border-gold">
        <div class="flatsome-container">
            <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-4 gap-6 pb-6 border-b border-tram-700 text-xs">
                
                <!-- Cột 1: Thông tin thương hiệu -->
                <div class="space-y-2.5">
                    <div class="flex items-center gap-2.5">
                        <img src="https://drive.google.com/thumbnail?id=15pD64oSReDKPkfb20w4Wpw5Xts8aqP81&sz=w200" onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/15pD64oSReDKPkfb20w4Wpw5Xts8aqP81';" alt="Logo" class="h-10 w-10 rounded bg-white p-0.5 object-contain">
                        <div>
                            <h4 class="font-serif font-bold text-sm text-gold-light">TRẦM HƯƠNG BẢO HÒA</h4>
                            <p class="text-[11px] text-tram-300">tramhuongbaohoa.com</p>
                        </div>
                    </div>
                    <p class="text-tram-200 leading-relaxed">
                        Chuyên sản xuất và cung cấp sản phẩm trầm hương thiên nhiên: Chuỗi hạt 108 hạt, vòng tay phong thủy, nhang trầm, giác xông, tượng trầm cảnh và quà tặng cao cấp.
                    </p>
                    <p class="text-gold-light font-medium">
                        <i class="fa-solid fa-location-dot mr-1"></i>Thị trấn Trung Phước, Nông Sơn, Đà Nẵng
                    </p>
                    <p class="text-gold-light font-medium">
                        <i class="fa-solid fa-phone mr-1"></i>0868 222 097 - 0972 511 539
                    </p>
                </div>

                <!-- Cột 2: Danh mục sản phẩm -->
                <div class="space-y-2">
                    <h4 class="font-bold text-sm text-gold-light uppercase">Danh Mục Sản Phẩm</h4>
                    <ul class="space-y-1.5 text-tram-200">
                        <li><a href="#san-pham" onclick="filterCategory('chuoi-tram')" class="hover:text-gold">Chuỗi trầm hương 108 hạt</a></li>
                        <li><a href="#san-pham" onclick="filterCategory('vong-tay')" class="hover:text-gold">Vòng tay trầm hương phong thủy</a></li>
                        <li><a href="#san-pham" onclick="filterCategory('boc-vang')" class="hover:text-gold">Vòng trầm hương bọc vàng</a></li>
                        <li><a href="#san-pham" onclick="filterCategory('nhang-tram')" class="hover:text-gold">Nhang trầm – Thác lư xông</a></li>
                        <li><a href="#san-pham" onclick="filterCategory('tram-mieng')" class="hover:text-gold">Trầm hương miếng – Giác xông</a></li>
                        <li><a href="#san-pham" onclick="filterCategory('tuong-tram')" class="hover:text-gold">Tranh – Tượng trầm cảnh</a></li>
                        <li><a href="#san-pham" onclick="filterCategory('tram-chim')" class="hover:text-gold">Trầm chìm VIP cao cấp</a></li>
                    </ul>
                </div>

                <!-- Cột 3: Chính sách khách hàng -->
                <div class="space-y-2">
                    <h4 class="font-bold text-sm text-gold-light uppercase">Chính Sách & Hỗ Trợ</h4>
                    <ul class="space-y-1.5 text-tram-200">
                        <li><a href="#bao-gia" class="hover:text-gold">Hướng dẫn đặt hàng & thanh toán</a></li>
                        <li><a href="#bao-gia" class="hover:text-gold">Chính sách bảo hành đánh bóng hạt</a></li>
                        <li><a href="#bao-gia" class="hover:text-gold">Chính sách kiểm hàng & đổi trả</a></li>
                        <li><a href="#bao-gia" class="hover:text-gold">Chính sách đại lý & sỉ toàn quốc</a></li>
                        <li><a href="#bao-gia" class="hover:text-gold">Cam kết trầm hương tự nhiên 100%</a></li>
                    </ul>
                </div>

                <!-- Cột 4: Kết nối mạng xã hội -->
                <div class="space-y-2.5">
                    <h4 class="font-bold text-sm text-gold-light uppercase">Kết Nối Với Bảo Hòa</h4>
                    <p class="text-tram-200">Theo dõi Facebook chính thức để xem video sản phẩm thực tế mới nhất:</p>
                    <a href="https://www.facebook.com/hoai.bao.201781" target="_blank" rel="noopener noreferrer" class="inline-flex items-center gap-2 bg-blue-600 hover:bg-blue-700 text-white font-semibold px-3.5 py-2 rounded-lg transition">
                        <i class="fa-brands fa-facebook text-base"></i> Facebook Trầm Hương Bảo Hòa
                    </a>
                    <div class="pt-1">
                        <a href="https://zalo.me/0868222097" target="_blank" rel="noopener noreferrer" class="inline-flex items-center gap-2 bg-tram-700 hover:bg-tram-600 text-white font-semibold px-3.5 py-2 rounded-lg transition">
                            <i class="fa-solid fa-comment-dots text-base"></i> Zalo: 0868 222 097
                        </a>
                    </div>
                </div>

            </div>

            <div class="pt-4 text-center text-[11px] text-tram-300 flex flex-col sm:flex-row items-center justify-between gap-2">
                <p>Copyright 2026 © <strong>tramhuongbaohoa.com</strong> - Công Ty TNHH MTV Trầm Hương Bảo Hòa</p>
                <p>Địa chỉ: Thị trấn Trung Phước, Nông Sơn, Đà Nẵng | ĐT: 0868 222 097 - 0972 511 539</p>
            </div>
        </div>
    </footer>

    <!-- ================= CÁC NÚT LIÊN HỆ NỔI BẬT (ZALO, FACEBOOK, HOTLINE) TƯƠNG THÍCH MÁY TÍNH & ĐIỆN THOẠI ================= -->
    <div class="fixed left-3 bottom-4 z-40 flex flex-col gap-2.5">
        <!-- Nút Zalo nổi bật -->
        <a href="https://zalo.me/0868222097" target="_blank" rel="noopener noreferrer" class="contact-pulse flex items-center gap-2 bg-blue-600 hover:bg-blue-700 text-white px-3 py-2 rounded-full shadow-lg border border-white/30 transition">
            <span class="w-6 h-6 rounded-full bg-white text-blue-600 font-extrabold text-[11px] flex items-center justify-center shrink-0">Zalo</span>
            <span class="text-xs font-bold hidden sm:inline">Chat Zalo: 0868 222 097</span>
        </a>

        <!-- Nút Facebook nổi bật -->
        <a href="https://www.facebook.com/hoai.bao.201781" target="_blank" rel="noopener noreferrer" class="flex items-center gap-2 bg-[#1877F2] hover:bg-blue-800 text-white px-3 py-2 rounded-full shadow-lg border border-white/30 transition">
            <i class="fa-brands fa-facebook-f w-6 h-6 rounded-full bg-white text-[#1877F2] flex items-center justify-center text-xs shrink-0"></i>
            <span class="text-xs font-bold hidden sm:inline">Facebook Bảo Hòa</span>
        </a>

        <!-- Nút Hotline 1 -->
        <a href="tel:0868222097" class="contact-pulse flex items-center gap-2 bg-red-700 hover:bg-red-800 text-white px-3 py-2 rounded-full shadow-lg border border-white/30 transition">
            <i class="fa-solid fa-phone-volume w-6 h-6 rounded-full bg-white text-red-700 flex items-center justify-center text-xs shrink-0"></i>
            <span class="text-xs font-bold">0868 222 097</span>
        </a>

        <!-- Nút Hotline 2 -->
        <a href="tel:0972511539" class="flex items-center gap-2 bg-tram-800 hover:bg-tram-900 text-gold-light px-3 py-1.5 rounded-full shadow-lg border border-gold/40 transition">
            <i class="fa-solid fa-phone w-5 h-5 rounded-full bg-gold text-tram-900 flex items-center justify-center text-[10px] shrink-0"></i>
            <span class="text-xs font-bold">0972 511 539</span>
        </a>
    </div>

    <!-- ================= MODAL ĐẶT HÀNG / NHẬN BÁO GIÁ NHANH ================= -->
    <div id="order-modal" class="fixed inset-0 z-50 hidden flex items-center justify-center p-3">
        <div onclick="closeQuoteModal()" class="fixed inset-0 bg-black/60 backdrop-blur-xs"></div>
        <div class="relative bg-white rounded-2xl max-w-md w-full p-5 shadow-2xl border border-tram-200 z-10">
            <div class="flex items-center justify-between pb-3 border-b border-tram-100">
                <h3 class="font-serif font-bold text-sm sm:text-base text-tram-900">ĐẶT MUA & NHẬN TƯ VẤN NHANH</h3>
                <button onclick="closeQuoteModal()" class="text-tram-500 hover:text-tram-900 p-1">
                    <i class="fa-solid fa-xmark text-lg"></i>
                </button>
            </div>
            <form onsubmit="handleQuickOrder(event)" class="space-y-3 pt-3 text-xs">
                <div>
                    <label class="font-semibold text-tram-800 block mb-1">Sản phẩm đã chọn:</label>
                    <input type="text" id="modal-product-name" readonly class="w-full px-3 py-2 rounded-lg bg-tram-100 text-tram-900 font-bold border border-tram-200">
                </div>
                <div>
                    <label class="font-semibold text-tram-800 block mb-1">Họ và tên của bạn *</label>
                    <input type="text" required placeholder="Nhập họ và tên..." class="w-full px-3 py-2 rounded-lg border border-tram-300 focus:outline-none focus:border-tram-700">
                </div>
                <div>
                    <label class="font-semibold text-tram-800 block mb-1">Số điện thoại liên hệ *</label>
                    <input type="tel" required placeholder="Nhập số điện thoại / Zalo..." class="w-full px-3 py-2 rounded-lg border border-tram-300 focus:outline-none focus:border-tram-700">
                </div>
                <div>
                    <label class="font-semibold text-tram-800 block mb-1">Địa chỉ nhận hàng / Ghi chú</label>
                    <textarea rows="2" placeholder="Nhập địa chỉ hoặc yêu cầu tư vấn size hạt..." class="w-full px-3 py-2 rounded-lg border border-tram-300 focus:outline-none focus:border-tram-700"></textarea>
                </div>
                <button type="submit" class="w-full bg-tram-800 hover:bg-tram-900 text-gold-light font-bold py-2.5 rounded-lg transition cursor-pointer">
                    XÁC NHẬN ĐẶT HÀNG & TƯ VẤN
                </button>
            </form>
            <div id="modal-order-success" class="hidden mt-3 p-2.5 bg-green-50 border border-green-300 text-green-800 rounded-lg text-xs text-center">
                Đặt hàng thành công! Trầm Hương Bảo Hòa sẽ gọi xác nhận ngay.
            </div>
        </div>
    </div>

    <!-- ================= MODAL ĐỌC BÀI VIẾT KIẾN THỨC ================= -->
    <div id="article-modal" class="fixed inset-0 z-50 hidden flex items-center justify-center p-3">
        <div onclick="closeArticleModal()" class="fixed inset-0 bg-black/60 backdrop-blur-xs"></div>
        <div class="relative bg-white rounded-2xl max-w-lg w-full p-5 shadow-2xl border border-tram-200 z-10 max-h-[85vh] overflow-y-auto">
            <div class="flex items-center justify-between pb-3 border-b border-tram-100">
                <h3 id="article-modal-title" class="font-serif font-bold text-sm sm:text-base text-tram-900 pr-4"></h3>
                <button onclick="closeArticleModal()" class="text-tram-500 hover:text-tram-900 p-1">
                    <i class="fa-solid fa-xmark text-lg"></i>
                </button>
            </div>
            <div id="article-modal-body" class="py-3 text-xs sm:text-sm text-tram-800 leading-relaxed space-y-2.5"></div>
        </div>
    </div>

    <!-- ================= JAVASCRIPT XỬ LÝ DỮ LIỆU SẢN PHẨM & TƯƠNG TÁC ================= -->
    <script>
        // Danh sách 9 sản phẩm thực tế sử dụng trực tiếp 9 file ảnh Google Drive của khách hàng
        // Tên sản phẩm và phân loại chuẩn theo mẫu tramhuongdanang.vn
        const realProducts = [
            {
                id: 1,
                driveId: '1_W7t5anuhxUJ8TJYl0g-n36PxkDUMU-C',
                name: 'CHUỖI TRẦM HƯƠNG TỰ NHIÊN 108 HẠT 8MM VÂN DẦU ĐẸP',
                category: 'chuoi-tram',
                categoryLabel: 'Chuỗi trầm hương 108 hạt',
                oldPrice: '2.200.000₫',
                price: '1.850.000₫',
                discount: '-16%',
                section: 'both-bracelet'
            },
            {
                id: 2,
                driveId: '1hiUWJ0LqaFjQckI9NR0bO7S05EeuQKyy',
                name: 'VÒNG TAY TRẦM HƯƠNG TỐC KIẾN TỰ NHIÊN NAM NỮ',
                category: 'vong-tay',
                categoryLabel: 'Vòng tay phong thủy',
                oldPrice: '1.500.000₫',
                price: '1.200.000₫',
                discount: '-20%',
                section: 'both-bracelet'
            },
            {
                id: 3,
                driveId: '17n-iriQsii3d4wMGDPs9CA44NN3eUKls',
                name: 'VÒNG TRẦM HƯƠNG BỌC VÀNG MIX CHARM PHONG THỦY',
                category: 'boc-vang',
                categoryLabel: 'Vòng trầm hương bọc vàng',
                oldPrice: '6.800.000₫',
                price: '6.000.000₫',
                discount: '-12%',
                section: 'both-bracelet'
            },
            {
                id: 4,
                driveId: '10CbxE5yeYbCjRdkio9yFOEGxfxbp-tEc',
                name: 'MẶT TƯỢNG PHẬT TRẦM HƯƠNG ĐEO CỔ CHẾ TÁC THỦ CÔNG',
                category: 'mat-tuong',
                categoryLabel: 'Mặt tượng đeo cổ',
                oldPrice: '1.200.000₫',
                price: '900.000₫',
                discount: '-25%',
                section: 'both-incense'
            },
            {
                id: 5,
                driveId: '1zJlqndUtnVNwAI6cgXCbnKH5kPUp8AmP',
                name: 'NHANG NỤ TRẦM HƯƠNG NGUYÊN CHẤT & THÁC KHÓI LƯ XÔNG',
                category: 'nhang-tram',
                categoryLabel: 'Nhang trầm – Thác lư xông',
                oldPrice: '450.000₫',
                price: '350.000₫',
                discount: '-22%',
                section: 'both-incense'
            },
            {
                id: 6,
                driveId: '1_mg1eE_U5G1r7fr-8mSr9nCWHU4PTh7K',
                name: 'TRẦM HƯƠNG MIẾNG GIÁC XÔNG NHÀ TỰ NHIÊN NÔNG SƠN',
                category: 'tram-mieng',
                categoryLabel: 'Trầm hương miếng – Giác xông',
                oldPrice: '1.100.000₫',
                price: '850.000₫',
                discount: '-23%',
                section: 'both-incense'
            },
            {
                id: 7,
                driveId: '1jher5yKrewFqQXyc8d3D616lg19ZeJwO',
                name: 'TƯỢNG TRẦM CẢNH PHONG THỦY TRƯNG BÀY BÀN LÀM VIỆC',
                category: 'tuong-tram',
                categoryLabel: 'Tranh – Tượng trầm cảnh',
                oldPrice: '4.500.000₫',
                price: '3.800.000₫',
                discount: '-15%',
                section: 'both-incense'
            },
            {
                id: 8,
                driveId: '1beSkJ1QeBzyps9m-B7e9bWbYgZnj2YYb',
                name: 'VÒNG TRẦM HƯƠNG VIP GIÀ DẦU BANH ĐỎ CAO CẤP',
                category: 'tram-chim',
                categoryLabel: 'Trầm chìm VIP cao cấp',
                oldPrice: '18.000.000₫',
                price: '16.000.000₫',
                discount: '-11%',
                section: 'both-bracelet'
            },
            {
                id: 9,
                driveId: '1ke_GgfB6dmB8t1A5pz_L0WKwSOKspf0S',
                name: 'VÒNG TRẦM HƯƠNG Đốt Trúc & VÒNG TRẦM BÌNH AN CHO BÉ',
                category: 'vong-be',
                categoryLabel: 'Vòng đeo cổ & Vòng cho bé',
                oldPrice: '650.000₫',
                price: '520.000₫',
                discount: '-20%',
                section: 'both-bracelet'
            },
            {
                id: 10,
                driveId: '1_W7t5anuhxUJ8TJYl0g-n36PxkDUMU-C',
                name: 'SET QUÀ TẶNG TRẦM HƯƠNG BẢO HÒA THƯỢNG HẠNG',
                category: 'qua-tang',
                categoryLabel: 'Set quà tặng & Tinh dầu',
                oldPrice: '2.500.000₫',
                price: '1.950.000₫',
                discount: '-22%',
                section: 'both-incense'
            }
        ];

        // Hàm tạo thẻ sản phẩm chuẩn Flatsome (Giá giảm giá & % giảm giá góc trên bên trái, tên đầy đủ không bị cắt chữ)
        function createProductCard(item) {
            const imgPrimary = `https://drive.google.com/thumbnail?id=${item.driveId}&sz=w700`;
            const imgFallback = `https://lh3.googleusercontent.com/d/${item.driveId}`;
            return `
                <div class="product-small box bg-white rounded-xl border border-tram-200 overflow-hidden shadow-xs hover:shadow-md transition flex flex-col justify-between">
                    <div class="box-image relative aspect-square w-full overflow-hidden bg-tram-50">
                        <!-- % Giảm giá góc trên bên trái giống Flatsome -->
                        <div class="badge-container">
                            <div class="onsale-badge">${item.discount}</div>
                        </div>
                        <img 
                            src="${imgPrimary}" 
                            onerror="this.onerror=null; this.src='${imgFallback}';"
                            alt="${item.name}" 
                            class="w-full h-full object-cover hover:scale-105 transition duration-500"
                        >
                    </div>
                    <div class="box-text p-2.5 sm:p-3 flex-1 flex flex-col justify-between text-center">
                        <div>
                            <p class="text-[10px] text-tram-500 uppercase tracking-wide mb-1">${item.categoryLabel}</p>
                            <!-- Tên sản phẩm hiển thị đầy đủ, không bị tràn ra ngoài hoặc thiếu chữ -->
                            <h3 class="font-bold text-xs sm:text-sm text-tram-900 leading-snug break-words mb-2">
                                ${item.name}
                            </h3>
                        </div>
                        <div>
                            <div class="price-wrapper flex flex-wrap items-center justify-center gap-1.5 mb-2.5">
                                <del class="text-[11px] text-gray-400">${item.oldPrice}</del>
                                <span class="text-xs sm:text-sm font-extrabold text-red-700">${item.price}</span>
                            </div>
                            <button onclick="openQuoteModal('${item.name}')" class="w-full py-1.5 px-2 rounded-lg bg-tram-800 hover:bg-tram-900 text-gold-light font-semibold text-[11px] sm:text-xs transition cursor-pointer">
                                Đặt mua / Tư vấn
                            </button>
                        </div>
                    </div>
                </div>
            `;
        }

        function renderAllGrids(list) {
            const mainGrid = document.getElementById('product-grid');
            const braceletGrid = document.getElementById('bracelet-grid');
            const incenseGrid = document.getElementById('incense-grid');

            mainGrid.innerHTML = list.map(createProductCard).join('');
            braceletGrid.innerHTML = realProducts.filter(p => p.section === 'both-bracelet').map(createProductCard).join('');
            incenseGrid.innerHTML = realProducts.filter(p => p.section === 'both-incense').map(createProductCard).join('');
        }

        function filterCategory(cat) {
            if (cat === 'all') {
                renderAllGrids(realProducts);
            } else {
                const filtered = realProducts.filter(p => p.category === cat);
                document.getElementById('product-grid').innerHTML = (filtered.length ? filtered : realProducts).map(createProductCard).join('');
            }
            document.getElementById('san-pham').scrollIntoView({ behavior: 'smooth' });
        }

        function filterBySelect(cat) {
            filterCategory(cat);
        }

        function searchProducts(keyword) {
            const kw = keyword.trim().toLowerCase();
            if (!kw) {
                renderAllGrids(realProducts);
                return;
            }
            const matched = realProducts.filter(p => 
                p.name.toLowerCase().includes(kw) || 
                p.categoryLabel.toLowerCase().includes(kw)
            );
            document.getElementById('product-grid').innerHTML = matched.length 
                ? matched.map(createProductCard).join('') 
                : `<div class="col-span-full text-center py-8 text-xs text-tram-700">Không tìm thấy sản phẩm phù hợp. Quý khách vui lòng gọi <strong>0868 222 097</strong> để được tư vấn trực tiếp.</div>`;
        }

        // ================= SLIDER 2 BANNER TỰ TRƯỢT =================
        let currentSlide = 0;
        const slides = document.querySelectorAll('.banner-slide');

        function showSlide(index) {
            currentSlide = (index + slides.length) % slides.length;
            slides.forEach((slide, i) => {
                if (i === currentSlide) {
                    slide.classList.remove('opacity-0', 'z-0');
                    slide.classList.add('opacity-100', 'z-10');
                } else {
                    slide.classList.remove('opacity-100', 'z-10');
                    slide.classList.add('opacity-0', 'z-0');
                }
            });
            const dot0 = document.getElementById('dot-0');
            const dot1 = document.getElementById('dot-1');
            if (currentSlide === 0) {
                dot0.className = 'w-6 h-2 rounded-full bg-gold transition-all';
                dot1.className = 'w-2 h-2 rounded-full bg-white/50 transition-all';
            } else {
                dot1.className = 'w-6 h-2 rounded-full bg-gold transition-all';
                dot0.className = 'w-2 h-2 rounded-full bg-white/50 transition-all';
            }
        }

        function nextBanner() { showSlide(currentSlide + 1); }
        function prevBanner() { showSlide(currentSlide - 1); }
        function goToBanner(idx) { showSlide(idx); }

        setInterval(nextBanner, 5000);

        // ================= MENU ĐIỆN THOẠI & MODAL =================
        function toggleMobileMenu() {
            const drawer = document.getElementById('mobile-drawer');
            drawer.classList.toggle('hidden');
        }

        let cartItems = 0;
        function openQuoteModal(productName) {
            document.getElementById('modal-product-name').value = productName;
            document.getElementById('modal-order-success').classList.add('hidden');
            document.getElementById('order-modal').classList.remove('hidden');
        }

        function closeQuoteModal() {
            document.getElementById('order-modal').classList.add('hidden');
        }

        function handleQuickOrder(e) {
            e.preventDefault();
            cartItems++;
            document.getElementById('cart-count').textContent = cartItems;
            document.getElementById('modal-order-success').classList.remove('hidden');
            setTimeout(() => {
                closeQuoteModal();
            }, 1800);
        }

        function submitQuoteForm(e) {
            e.preventDefault();
            document.getElementById('quote-success-msg').classList.remove('hidden');
            e.target.reset();
        }

        // ================= DỮ LIỆU BÀI VIẾT KIẾN THỨC =================
        const articlesData = [
            {
                title: 'Trầm Hương Chìm Nước Là Gì? Vì Sao Giá Trị Cao Hơn Các Loại Trầm Khác?',
                content: `
                    <p><strong>Trầm hương chìm nước</strong> là dòng trầm hương quý hiếm có mật độ tinh dầu tích tụ cực cao trong từng thớ gỗ Dó Bầu, khiến khối lượng riêng của trầm nặng hơn nước và chìm hoàn toàn khi thả vào nước.</p>
                    <p>Tại vùng núi <strong>Trung Phước, Nông Sơn, Đà Nẵng</strong>, quá trình tạo trầm tự nhiên diễn ra qua hàng chục năm dưới điều kiện thổ nhưỡng đặc biệt, mang lại mùi hương ngọt sâu, thanh khiết và giá trị phong thủy, sưu tầm bậc nhất.</p>
                `
            },
            {
                title: 'Cách Phân Biệt Trầm Hương Tự Nhiên Thật Và Giả Chuẩn Xác Nhất',
                content: `
                    <p>Để nhận biết <strong>Trầm Hương Tự Nhiên</strong> chuẩn xác, quý khách có thể dựa vào 3 yếu tố cốt lõi:</p>
                    <p>1. <strong>Vân dầu tự nhiên:</strong> Hạt trầm thật có các đường vân dầu xen kẽ thớ gỗ tự nhiên, không bóng loáng màu sơn hóa học.</p>
                    <p>2. <strong>Mùi hương:</strong> Trầm tự nhiên có hương thơm dịu nhẹ, ngọt thanh, càng đeo gặp thân nhiệt càng tỏa hương ấm áp, không nồng gắt mùi hương liệu.</p>
                `
            },
            {
                title: 'Đeo Vòng Tay Trầm Hương 108 Hạt Có Tác Dụng Gì Trong Phong Thủy?',
                content: `
                    <p><strong>Chuỗi vòng trầm hương 108 hạt</strong> vừa là trang sức sang trọng vừa mang ý nghĩa tâm linh sâu sắc, biểu trưng cho sự cầu chứng 108 pháp Tam Muội để đoạn trừ 108 phiền não trong cuộc sống.</p>
                    <p>Hương thơm dịu ngọt từ vòng trầm giúp người đeo an thần, giảm căng thẳng, giữ tâm trí sáng suốt và thu hút tài lộc, may mắn.</p>
                `
            },
            {
                title: 'Trầm Hương Xông Nhà Có Tác Dụng Gì? Hướng Dẫn Xông Trầm Đúng Cách',
                content: `
                    <p>Sử dụng <strong>Trầm hương miếng, giác xông hoặc nụ trầm hương</strong> để xông nhà giúp thanh lọc không khí, khử mùi ẩm mốc, xua đuổi uế khí và mang lại nguồn năng lượng dương ấm áp cho gia đình và cửa hàng kinh doanh.</p>
                `
            }
        ];

        function openArticleModal(idx) {
            const item = articlesData[idx];
            document.getElementById('article-modal-title').textContent = item.title;
            document.getElementById('article-modal-body').innerHTML = item.content;
            document.getElementById('article-modal').classList.remove('hidden');
        }

        function closeArticleModal() {
            document.getElementById('article-modal').classList.add('hidden');
        }

        // Khởi chạy hiển thị sản phẩm khi tải trang
        window.onload = function() {
            renderAllGrids(realProducts);
        };
    </script>
</body>
</html>
