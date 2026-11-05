<html lang="vi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no">
    <title>Đồ Gỗ Mỹ Nghệ Bảo Lâm - Xưởng Sản Xuất Nội Thất Gỗ Tự Nhiên Cao Cấp | baolam.net</title>
    <meta name="description" content="Đồ Gỗ Mỹ Nghệ Bảo Lâm (baolam.net) - Chuyên sản xuất và cung cấp nội thất gỗ tự nhiên cao cấp: Bàn ghế phòng khách, Hoàng Gia, Rồng Đỉnh, Bàn ghế ăn, Giường tủ, Đồ thờ tại 94 Nam Cao, Hòa Khánh, TP Đà Nẵng. Hotline: 0905.265.586">

    <!-- Open Graph / Thumbnail là ảnh Logo trang web khi chia sẻ link -->
    <meta property="og:type" content="website">
    <meta property="og:url" content="https://baolam.net/">
    <meta property="og:title" content="Đồ Gỗ Mỹ Nghệ Bảo Lâm - Tinh Hoa Gỗ Việt | baolam.net">
    <meta property="og:description" content="Xưởng sản xuất đồ gỗ mỹ nghệ cao cấp tại 94 Nam Cao, Phường Hòa Khánh, TP Đà Nẵng. Hotline/Zalo: 0905.265.586">
    <meta property="og:image" content="https://lh3.googleusercontent.com/d/1egxad2JO9d8csN2hRnKiu-wtocfV1Paj=w1000">
    <meta name="twitter:card" content="summary_large_image">
    <meta name="twitter:image" content="https://lh3.googleusercontent.com/d/1egxad2JO9d8csN2hRnKiu-wtocfV1Paj=w1000">
    <link rel="icon" href="https://lh3.googleusercontent.com/d/1egxad2JO9d8csN2hRnKiu-wtocfV1Paj=w200">

    <!-- Google Fonts: Inter & Playfair Display -->
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700;800&family=Playfair+Display:wght@600;700;800&display=swap" rel="stylesheet">

    <!-- Font Awesome Icons -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.1/css/all.min.css">

    <!-- Tailwind CSS -->
    <script src="https://cdn.tailwindcss.com"></script>
    <script>
        tailwind.config = {
            theme: {
                extend: {
                    colors: {
                        wood: {
                            50: '#fdfaf6',
                            100: '#f9f1e7',
                            200: '#f1dec8',
                            300: '#e5c39d',
                            400: '#d59f6b',
                            500: '#b87438',
                            600: '#965423',
                            700: '#783b16',
                            800: '#5e2c10',
                            900: '#421d09',
                        },
                        gold: {
                            400: '#facc15',
                            500: '#eab308',
                            600: '#ca8a04',
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
        /* Khóa tràn viền ngang tuyệt đối & căn giữa chuẩn Flatsome 1500px */
        *, *::before, *::after {
            box-sizing: border-box;
        }
        html, body {
            width: 100%;
            max-width: 100vw;
            overflow-x: hidden;
            margin: 0;
            padding: 0;
            background-color: #faf7f2;
            color: #271c15;
            scroll-behavior: smooth;
        }

        /* Container chuẩn 1500px trên máy tính theo yêu cầu */
        .flatsome-container {
            width: 100%;
            max-width: 1500px;
            margin-left: auto;
            margin-right: auto;
            padding-left: 12px;
            padding-right: 12px;
        }
        @media (min-width: 1024px) {
            .flatsome-container {
                padding-left: 20px;
                padding-right: 20px;
            }
        }

        /* Badge % giảm giá chuẩn Flatsome góc trên bên trái */
        .flatsome-sale-badge {
            position: absolute;
            top: 10px;
            left: 10px;
            z-index: 10;
            width: 44px;
            height: 44px;
            border-radius: 9999px;
            background: linear-gradient(135deg, #c81e1e 0%, #991b1b 100%);
            color: #ffffff;
            font-weight: 700;
            font-size: 13px;
            display: flex;
            align-items: center;
            justify-content: center;
            box-shadow: 0 3px 8px rgba(0, 0, 0, 0.25);
            border: 1.5px solid #fde047;
            pointer-events: none;
        }
        @media (max-width: 640px) {
            .flatsome-sale-badge {
                width: 36px;
                height: 36px;
                font-size: 11px;
                top: 6px;
                left: 6px;
            }
        }

        /* Tiêu đề Section chuẩn Flatsome (dogophamgia.com) */
        .flatsome-section-header {
            display: flex;
            flex-wrap: wrap;
            align-items: center;
            justify-content: space-between;
            border-bottom: 2px solid #783b16;
            margin-bottom: 18px;
            background: #ffffff;
            border-radius: 8px 8px 0 0;
        }
        .flatsome-section-title {
            background: linear-gradient(90deg, #5e2c10 0%, #783b16 100%);
            color: #fef08a;
            padding: 10px 20px;
            font-weight: 700;
            font-size: 15px;
            text-transform: uppercase;
            letter-spacing: 0.5px;
            border-radius: 8px 18px 0 0;
            display: inline-flex;
            align-items: center;
            gap: 8px;
            white-space: nowrap;
        }

        /* Danh mục không bao giờ bị xuống dòng giữa chừng chữ */
        .nav-cat-item {
            white-space: nowrap;
            display: inline-flex;
            align-items: center;
            transition: all 0.2s ease;
        }

        /* Card sản phẩm chuẩn UX Builder Flatsome */
        .product-small.box {
            background: #ffffff;
            border: 1px solid #e7dccb;
            border-radius: 10px;
            overflow: hidden;
            transition: transform 0.25s ease, box-shadow 0.25s ease;
            display: flex;
            flex-direction: column;
            height: 100%;
        }
        .product-small.box:hover {
            transform: translateY(-3px);
            box-shadow: 0 10px 24px -6px rgba(94, 44, 16, 0.18);
            border-color: #b87438;
        }

        /* Đảm bảo tên sản phẩm hiển thị đầy đủ 100%, không bị cắt chữ hay tràn ra ngoài */
        .product-title-full {
            white-space: normal;
            word-wrap: break-word;
            overflow-wrap: break-word;
            line-height: 1.4;
            color: #271c15;
            font-weight: 600;
        }

        /* Hiệu ứng sóng cho nút liên hệ nổi */
        @keyframes pulse-ring {
            0% { transform: scale(0.95); box-shadow: 0 0 0 0 rgba(202, 138, 4, 0.7); }
            70% { transform: scale(1); box-shadow: 0 0 0 10px rgba(202, 138, 4, 0); }
            100% { transform: scale(0.95); box-shadow: 0 0 0 0 rgba(202, 138, 4, 0); }
        }
        .floating-btn-pulse {
            animation: pulse-ring 2s infinite;
        }
    </style>
</head>
<body class="font-sans antialiased selection:bg-wood-700 selection:text-white">

    <!-- ==========================================
         TOP BAR (THÔNG TIN XƯỞNG BẢO LÂM - CHUẨN FLATSOME)
         ========================================== -->
    <div class="bg-wood-900 text-amber-100 text-xs py-2 border-b border-wood-700">
        <div class="flatsome-container flex flex-wrap items-center justify-between gap-2">
            <div class="flex items-center gap-4 flex-wrap">
                <span class="inline-flex items-center gap-1.5 font-medium">
                    <i class="fa-solid fa-award text-gold-400"></i>
                    <strong>ĐỒ GỖ MỸ NGHỆ BẢO LÂM</strong> - Website chính thức: <strong class="text-gold-400">baolam.net</strong>
                </span>
                <span class="hidden md:inline-flex items-center gap-1.5 text-amber-200/90">
                    <i class="fa-solid fa-location-dot text-gold-400"></i>
                    94 Nam Cao, Phường Hòa Khánh, TP Đà Nẵng
                </span>
            </div>
            <div class="flex items-center gap-4 text-xs">
                <a href="#bang-bao-gia" class="hover:text-gold-400 transition whitespace-nowrap">
                    <i class="fa-solid fa-file-invoice-dollar mr-1 text-gold-400"></i>Yêu cầu báo giá
                </a>
                <span class="text-wood-600">|</span>
                <a href="#ban-do-trang-chu" class="hover:text-gold-400 transition whitespace-nowrap">
                    <i class="fa-solid fa-map-location-dot mr-1 text-gold-400"></i>Chỉ đường Showroom
                </a>
            </div>
        </div>
    </div>

    <!-- ==========================================
         HEADER CHÍNH (LOGO GỌN NHỎ - KHÔNG ĐỂ NÚT GỌI NGAY ĐỂ TRÁNH TRÀN VIỀN)
         ========================================== -->
    <header id="header" class="bg-white sticky top-0 z-40 shadow-sm border-b border-stone-200">
        <div class="flatsome-container py-2.5">
            <div class="flex items-center justify-between gap-3">
                
                <!-- Nút mở Menu trên Điện thoại -->
                <button id="mobileMenuBtn" onclick="toggleMobileMenu()" aria-label="Mở danh mục" class="lg:hidden p-2 rounded-lg text-wood-800 hover:bg-wood-50 border border-stone-200 flex-shrink-0">
                    <i class="fa-solid fa-bars text-lg"></i>
                </button>

                <!-- Logo Bảo Lâm đã chỉnh gọn nhỏ lại theo đúng yêu cầu -->
                <a href="#" class="flex items-center gap-2.5 flex-shrink-0 group">
                    <div class="w-10 h-10 sm:w-12 sm:h-12 rounded-lg overflow-hidden border border-amber-700/30 bg-wood-50 flex items-center justify-center p-0.5 shadow-sm flex-shrink-0">
                        <img src="https://lh3.googleusercontent.com/d/1egxad2JO9d8csN2hRnKiu-wtocfV1Paj=w400" 
                             onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1egxad2JO9d8csN2hRnKiu-wtocfV1Paj&sz=w400';"
                             alt="Logo Đồ Gỗ Mỹ Nghệ Bảo Lâm" 
                             class="w-full h-full object-contain rounded">
                    </div>
                    <div class="leading-tight">
                        <span class="block font-serif font-bold text-sm sm:text-lg text-wood-800 tracking-tight group-hover:text-wood-600 transition">
                            ĐỒ GỖ BẢO LÂM
                        </span>
                        <span class="block text-[10px] sm:text-xs text-stone-500 font-medium">
                            baolam.net • Mỹ Nghệ Cao Cấp
                        </span>
                    </div>
                </a>

                <!-- Thanh tìm kiếm sản phẩm (Máy tính) -->
                <div class="hidden md:flex flex-1 max-w-xl mx-4">
                    <div class="relative w-full flex items-center">
                        <input id="desktopSearchInput" type="text" oninput="filterProductsBySearch(this.value)"
                               placeholder="Tìm bàn ghế Hoàng Gia, Rồng Đỉnh, kệ tivi, bàn ăn, sập thờ..." 
                               class="w-full pl-4 pr-11 py-2 text-xs sm:text-sm bg-stone-50 border border-stone-300 rounded-full focus:outline-none focus:border-wood-700 focus:bg-white transition">
                        <button onclick="filterProductsBySearch(document.getElementById('desktopSearchInput').value)" class="absolute right-1.5 w-8 h-8 rounded-full bg-wood-800 text-gold-400 flex items-center justify-center hover:bg-wood-700 transition">
                            <i class="fa-solid fa-magnifying-glass text-xs"></i>
                        </button>
                    </div>
                </div>

                <!-- Cam kết chất lượng & Giỏ hàng (Không để nút gọi ngay trên header tránh tràn viền) -->
                <div class="flex items-center gap-2 sm:gap-4 flex-shrink-0">
                    <div class="hidden xl:flex items-center gap-2 text-xs text-stone-600 bg-wood-50 px-3 py-1.5 rounded-lg border border-wood-200">
                        <i class="fa-solid fa-shield-halved text-wood-700 text-sm"></i>
                        <div>
                            <div class="font-semibold text-wood-900">Gỗ Tự Nhiên 100%</div>
                            <div class="text-[11px] text-stone-500">Bảo hành dài hạn tại xưởng</div>
                        </div>
                    </div>

                    <a href="#bang-bao-gia" class="inline-flex items-center gap-1.5 px-3 py-2 rounded-lg bg-wood-50 hover:bg-wood-100 text-wood-800 border border-wood-300 text-xs font-semibold transition whitespace-nowrap">
                        <i class="fa-solid fa-pen-to-square text-wood-700"></i>
                        <span class="hidden sm:inline">Đặt Hàng Theo Yêu Cầu</span>
                        <span class="sm:hidden">Báo Giá</span>
                    </a>
                </div>
            </div>

            <!-- Thanh tìm kiếm gọn trên Điện thoại -->
            <div class="mt-2 md:hidden">
                <div class="relative w-full flex items-center">
                    <input id="mobileSearchInput" type="text" oninput="filterProductsBySearch(this.value)"
                           placeholder="Tìm kiếm sản phẩm đồ gỗ Bảo Lâm..." 
                           class="w-full pl-3.5 pr-9 py-1.5 text-xs bg-stone-50 border border-stone-300 rounded-full focus:outline-none focus:border-wood-700">
                    <i class="fa-solid fa-magnifying-glass text-xs text-stone-400 absolute right-3"></i>
                </div>
            </div>
        </div>

        <!-- ==========================================
             THANH DANH MỤC TRÊN MÁY TÍNH (CHỮ NHỎ GỌN, VIẾT LIỀN TRÊN 1 HÀNG HOẶC XUỐNG HÀNG 2, KHÔNG BỊ GÃY DÒNG TÊN DANH MỤC)
             ========================================== -->
        <nav class="hidden lg:block bg-wood-800 text-white border-t border-wood-700">
            <div class="flatsome-container">
                <ul class="flex flex-wrap items-center justify-center gap-x-1 gap-y-1 py-1.5 text-[12.5px] font-semibold">
                    <li>
                        <a href="#" onclick="filterCategory('all'); return false;" class="nav-cat-item px-2.5 py-1.5 rounded bg-gold-500 text-wood-900 font-bold hover:bg-gold-400">
                            <i class="fa-solid fa-house mr-1.5 text-[11px]"></i>Trang chủ
                        </a>
                    </li>
                    <li class="relative group">
                        <a href="#sec-phong-khach" onclick="filterCategory('phong-khach')" class="nav-cat-item px-2.5 py-1.5 rounded hover:bg-wood-700 hover:text-gold-400">
                            Nội thất phòng khách <i class="fa-solid fa-chevron-down ml-1 text-[9px] opacity-80"></i>
                        </a>
                        <div class="absolute left-0 top-full hidden group-hover:block bg-white text-stone-800 shadow-xl rounded-b-lg border border-stone-200 py-1.5 min-w-[210px] z-50">
                            <a href="#sec-phong-khach" onclick="filterCategory('phong-khach')" class="block px-3.5 py-1.5 text-xs hover:bg-wood-50 hover:text-wood-800 whitespace-nowrap">Bàn ghế phòng khách</a>
                            <a href="#sec-phong-khach" onclick="filterCategory('phong-khach')" class="block px-3.5 py-1.5 text-xs hover:bg-wood-50 hover:text-wood-800 whitespace-nowrap">Sofa phòng khách</a>
                            <a href="#sec-phong-khach" onclick="filterCategory('ke-tivi')" class="block px-3.5 py-1.5 text-xs hover:bg-wood-50 hover:text-wood-800 whitespace-nowrap">Kệ Tivi gỗ tự nhiên</a>
                            <a href="#sec-phong-khach" onclick="filterCategory('phong-khach')" class="block px-3.5 py-1.5 text-xs hover:bg-wood-50 hover:text-wood-800 whitespace-nowrap">Đồng hồ cây</a>
                            <a href="#sec-phong-khach" onclick="filterCategory('phong-khach')" class="block px-3.5 py-1.5 text-xs hover:bg-wood-50 hover:text-wood-800 whitespace-nowrap">Chiếu ngựa - Phản gỗ</a>
                        </div>
                    </li>
                    <li>
                        <a href="#sec-phong-khach" onclick="filterCategory('hoang-gia')" class="nav-cat-item px-2.5 py-1.5 rounded hover:bg-wood-700 hover:text-gold-400">
                            Bàn ghế Hoàng Gia
                        </a>
                    </li>
                    <li>
                        <a href="#sec-phong-khach" onclick="filterCategory('rong-dinh')" class="nav-cat-item px-2.5 py-1.5 rounded hover:bg-wood-700 hover:text-gold-400">
                            Bàn ghế Rồng Đỉnh
                        </a>
                    </li>
                    <li>
                        <a href="#sec-phong-khach" onclick="filterCategory('tan-thuy-hoang')" class="nav-cat-item px-2.5 py-1.5 rounded hover:bg-wood-700 hover:text-gold-400">
                            Bàn ghế Tần Thủy Hoàng
                        </a>
                    </li>
                    <li>
                        <a href="#sec-phong-khach" onclick="filterCategory('au-a')" class="nav-cat-item px-2.5 py-1.5 rounded hover:bg-wood-700 hover:text-gold-400">
                            Bàn ghế Âu Á
                        </a>
                    </li>
                    <li>
                        <a href="#sec-phong-khach" onclick="filterCategory('minh-quoc')" class="nav-cat-item px-2.5 py-1.5 rounded hover:bg-wood-700 hover:text-gold-400">
                            Bàn ghế Minh Quốc
                        </a>
                    </li>
                    <li class="relative group">
                        <a href="#sec-phong-bep" onclick="filterCategory('phong-bep')" class="nav-cat-item px-2.5 py-1.5 rounded hover:bg-wood-700 hover:text-gold-400">
                            Nội thất phòng bếp <i class="fa-solid fa-chevron-down ml-1 text-[9px] opacity-80"></i>
                        </a>
                        <div class="absolute left-0 top-full hidden group-hover:block bg-white text-stone-800 shadow-xl rounded-b-lg border border-stone-200 py-1.5 min-w-[190px] z-50">
                            <a href="#sec-phong-bep" onclick="filterCategory('phong-bep')" class="block px-3.5 py-1.5 text-xs hover:bg-wood-50 hover:text-wood-800 whitespace-nowrap">Bàn ghế ăn gỗ tự nhiên</a>
                            <a href="#sec-phong-bep" onclick="filterCategory('phong-bep')" class="block px-3.5 py-1.5 text-xs hover:bg-wood-50 hover:text-wood-800 whitespace-nowrap">Bàn ăn nguyên khối</a>
                            <a href="#sec-phong-bep" onclick="filterCategory('phong-bep')" class="block px-3.5 py-1.5 text-xs hover:bg-wood-50 hover:text-wood-800 whitespace-nowrap">Tủ rượu gỗ quý</a>
                        </div>
                    </li>
                    <li class="relative group">
                        <a href="#sec-phong-ngu" onclick="filterCategory('phong-ngu')" class="nav-cat-item px-2.5 py-1.5 rounded hover:bg-wood-700 hover:text-gold-400">
                            Nội thất phòng ngủ <i class="fa-solid fa-chevron-down ml-1 text-[9px] opacity-80"></i>
                        </a>
                        <div class="absolute left-0 top-full hidden group-hover:block bg-white text-stone-800 shadow-xl rounded-b-lg border border-stone-200 py-1.5 min-w-[190px] z-50">
                            <a href="#sec-phong-ngu" onclick="filterCategory('phong-ngu')" class="block px-3.5 py-1.5 text-xs hover:bg-wood-50 hover:text-wood-800 whitespace-nowrap">Giường ngủ gỗ tự nhiên</a>
                            <a href="#sec-phong-ngu" onclick="filterCategory('phong-ngu')" class="block px-3.5 py-1.5 text-xs hover:bg-wood-50 hover:text-wood-800 whitespace-nowrap">Tủ quần áo gỗ</a>
                            <a href="#sec-phong-ngu" onclick="filterCategory('phong-ngu')" class="block px-3.5 py-1.5 text-xs hover:bg-wood-50 hover:text-wood-800 whitespace-nowrap">Bàn trang điểm</a>
                        </div>
                    </li>
                    <li class="relative group">
                        <a href="#sec-phong-tho" onclick="filterCategory('phong-tho')" class="nav-cat-item px-2.5 py-1.5 rounded hover:bg-wood-700 hover:text-gold-400">
                            Nội thất phòng thờ <i class="fa-solid fa-chevron-down ml-1 text-[9px] opacity-80"></i>
                        </a>
                        <div class="absolute left-0 top-full hidden group-hover:block bg-white text-stone-800 shadow-xl rounded-b-lg border border-stone-200 py-1.5 min-w-[190px] z-50">
                            <a href="#sec-phong-tho" onclick="filterCategory('phong-tho')" class="block px-3.5 py-1.5 text-xs hover:bg-wood-50 hover:text-wood-800 whitespace-nowrap">Sập thờ - Án gian</a>
                            <a href="#sec-phong-tho" onclick="filterCategory('phong-tho')" class="block px-3.5 py-1.5 text-xs hover:bg-wood-50 hover:text-wood-800 whitespace-nowrap">Tủ thờ gia tiên</a>
                            <a href="#sec-phong-tho" onclick="filterCategory('phong-tho')" class="block px-3.5 py-1.5 text-xs hover:bg-wood-50 hover:text-wood-800 whitespace-nowrap">Hoành phi câu đối</a>
                            <a href="#sec-phong-tho" onclick="filterCategory('phong-tho')" class="block px-3.5 py-1.5 text-xs hover:bg-wood-50 hover:text-wood-800 whitespace-nowrap">Lục bình gỗ phong thủy</a>
                        </div>
                    </li>
                    <li>
                        <a href="#sec-doi-tac" class="nav-cat-item px-2.5 py-1.5 rounded hover:bg-wood-700 hover:text-gold-400">
                            Đối tác
                        </a>
                    </li>
                    <li>
                        <a href="#sec-tin-tuc" class="nav-cat-item px-2.5 py-1.5 rounded hover:bg-wood-700 hover:text-gold-400">
                            Tin tức
                        </a>
                    </li>
                    <li>
                        <a href="#bang-bao-gia" class="nav-cat-item px-2.5 py-1.5 rounded hover:bg-wood-700 hover:text-gold-400">
                            Báo giá & Liên hệ
                        </a>
                    </li>
                </ul>
            </div>
        </nav>

        <!-- Menu Danh mục trượt ngang nhanh trên Điện thoại (Chữ nhỏ gọn, không gãy chữ) -->
        <div class="lg:hidden bg-wood-800 text-white border-t border-wood-700 overflow-x-auto no-scrollbar">
            <div class="flex items-center gap-1.5 px-2.5 py-1.5 text-[11.5px] font-medium">
                <a href="#danh-muc-trang-chu" onclick="filterCategory('all')" class="nav-cat-item px-2.5 py-1 rounded bg-gold-500 text-wood-900 font-bold">Tất cả</a>
                <a href="#sec-phong-khach" onclick="filterCategory('phong-khach')" class="nav-cat-item px-2.5 py-1 rounded bg-wood-700/80 hover:bg-wood-600">Nội thất phòng khách</a>
                <a href="#sec-phong-khach" onclick="filterCategory('hoang-gia')" class="nav-cat-item px-2.5 py-1 rounded bg-wood-700/80 hover:bg-wood-600">Bàn ghế Hoàng Gia</a>
                <a href="#sec-phong-khach" onclick="filterCategory('rong-dinh')" class="nav-cat-item px-2.5 py-1 rounded bg-wood-700/80 hover:bg-wood-600">Bàn ghế Rồng Đỉnh</a>
                <a href="#sec-phong-bep" onclick="filterCategory('phong-bep')" class="nav-cat-item px-2.5 py-1 rounded bg-wood-700/80 hover:bg-wood-600">Nội thất phòng bếp</a>
                <a href="#sec-phong-ngu" onclick="filterCategory('phong-ngu')" class="nav-cat-item px-2.5 py-1 rounded bg-wood-700/80 hover:bg-wood-600">Nội thất phòng ngủ</a>
                <a href="#sec-phong-tho" onclick="filterCategory('phong-tho')" class="nav-cat-item px-2.5 py-1 rounded bg-wood-700/80 hover:bg-wood-600">Nội thất phòng thờ</a>
                <a href="#sec-doi-tac" class="nav-cat-item px-2.5 py-1 rounded bg-wood-700/80 hover:bg-wood-600">Đối tác</a>
                <a href="#sec-tin-tuc" class="nav-cat-item px-2.5 py-1 rounded bg-wood-700/80 hover:bg-wood-600">Tin tức</a>
            </div>
        </div>
    </header>

    <!-- ==========================================
         DRAWER MENU ĐIỆN THOẠI (OFF-CANVAS FLATSOME)
         ========================================== -->
    <div id="mobileMenuOverlay" onclick="toggleMobileMenu()" class="fixed inset-0 bg-black/60 z-50 hidden"></div>
    <aside id="mobileMenuDrawer" class="fixed top-0 left-0 bottom-0 w-72 max-w-[85vw] bg-white z-50 transform -translate-x-full transition-transform duration-300 flex flex-col shadow-2xl">
        <div class="p-3.5 bg-wood-900 text-white flex items-center justify-between">
            <div class="flex items-center gap-2">
                <img src="https://lh3.googleusercontent.com/d/1egxad2JO9d8csN2hRnKiu-wtocfV1Paj=w200" 
                     onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1egxad2JO9d8csN2hRnKiu-wtocfV1Paj&sz=w200';"
                     alt="Logo Bảo Lâm" class="w-8 h-8 rounded bg-white p-0.5 object-contain">
                <span class="font-serif font-bold text-sm text-gold-400">ĐỒ GỖ BẢO LÂM</span>
            </div>
            <button onclick="toggleMobileMenu()" class="w-7 h-7 rounded bg-wood-800 text-white flex items-center justify-center">
                <i class="fa-solid fa-xmark"></i>
            </button>
        </div>
        <div class="p-3 overflow-y-auto flex-1 divide-y divide-stone-100 text-xs font-semibold text-stone-700">
            <a href="#" onclick="filterCategory('all'); toggleMobileMenu();" class="block py-2.5 text-wood-800"><i class="fa-solid fa-house w-5 text-wood-600"></i> Trang chủ baolam.net</a>
            <a href="#sec-phong-khach" onclick="filterCategory('phong-khach'); toggleMobileMenu();" class="block py-2.5"><i class="fa-solid fa-couch w-5 text-wood-600"></i> Nội thất phòng khách</a>
            <a href="#sec-phong-khach" onclick="filterCategory('hoang-gia'); toggleMobileMenu();" class="block py-2.5 pl-4 text-stone-600">• Bàn ghế Hoàng Gia</a>
            <a href="#sec-phong-khach" onclick="filterCategory('rong-dinh'); toggleMobileMenu();" class="block py-2.5 pl-4 text-stone-600">• Bàn ghế Rồng Đỉnh</a>
            <a href="#sec-phong-khach" onclick="filterCategory('tan-thuy-hoang'); toggleMobileMenu();" class="block py-2.5 pl-4 text-stone-600">• Bàn ghế Tần Thủy Hoàng</a>
            <a href="#sec-phong-khach" onclick="filterCategory('au-a'); toggleMobileMenu();" class="block py-2.5 pl-4 text-stone-600">• Bàn ghế Âu Á - Minh Quốc</a>
            <a href="#sec-phong-khach" onclick="filterCategory('ke-tivi'); toggleMobileMenu();" class="block py-2.5 pl-4 text-stone-600">• Kệ Tivi & Đồng hồ cây</a>
            <a href="#sec-phong-bep" onclick="filterCategory('phong-bep'); toggleMobileMenu();" class="block py-2.5"><i class="fa-solid fa-utensils w-5 text-wood-600"></i> Nội thất phòng bếp (Bàn ăn, Tủ rượu)</a>
            <a href="#sec-phong-ngu" onclick="filterCategory('phong-ngu'); toggleMobileMenu();" class="block py-2.5"><i class="fa-solid fa-bed w-5 text-wood-600"></i> Nội thất phòng ngủ (Giường, Tủ áo)</a>
            <a href="#sec-phong-tho" onclick="filterCategory('phong-tho'); toggleMobileMenu();" class="block py-2.5"><i class="fa-solid fa-place-of-worship w-5 text-wood-600"></i> Nội thất phòng thờ (Sập thờ, Án gian)</a>
            <a href="#sec-doi-tac" onclick="toggleMobileMenu();" class="block py-2.5"><i class="fa-solid fa-handshake w-5 text-wood-600"></i> Đối tác đồng hành</a>
            <a href="#sec-tin-tuc" onclick="toggleMobileMenu();" class="block py-2.5"><i class="fa-solid fa-newspaper w-5 text-wood-600"></i> Tin tức & Kinh nghiệm đồ gỗ</a>
            <a href="#bang-bao-gia" onclick="toggleMobileMenu();" class="block py-2.5"><i class="fa-solid fa-envelope-open-text w-5 text-wood-600"></i> Yêu cầu báo giá tại xưởng</a>
            <a href="#ban-do-trang-chu" onclick="toggleMobileMenu();" class="block py-2.5"><i class="fa-solid fa-location-dot w-5 text-wood-600"></i> Bản đồ & Fanpage Bảo Lâm</a>
        </div>
        <div class="p-3 bg-stone-50 border-t border-stone-200 text-[11px] text-stone-600">
            <p class="font-bold text-wood-800">ĐỒ GỖ MỸ NGHỆ BẢO LÂM</p>
            <p class="mt-0.5">Đ/c: 94 Nam Cao, P. Hòa Khánh, TP Đà Nẵng</p>
            <p class="mt-0.5 font-bold text-red-700">Hotline/Zalo: 0905.265.586</p>
        </div>
    </aside>

    <!-- ==========================================
         2 BANNER TỰ TRƯỢT CHUYÊN NGHIỆP KÍCH THƯỚC BẰNG NHAU
         - Thiết kế Banner Máy Tính riêng (hidden md:block)
         - Thiết kế Banner Điện Thoại riêng (block md:hidden) chữ nhỏ gọn nằm hết trong ảnh, không tràn viền
         ========================================== -->
    <section class="py-3">
        <div class="flatsome-container">
            <div class="relative rounded-xl overflow-hidden shadow-md border border-wood-200 bg-wood-900">

                <!-- ====== BANNER DÀNH RIÊNG CHO MÁY TÍNH (2 SLIDE KÍCH THƯỚC BẰNG NHAU 420PX) ====== -->
                <div class="hidden md:block relative w-full h-[420px]">
                    <!-- Desktop Slide 1 -->
                    <div id="desktop-slide-0" class="banner-slide-desktop absolute inset-0 w-full h-full transition-opacity duration-700 opacity-100 z-10">
                        <div class="grid grid-cols-12 h-full bg-gradient-to-r from-[#3b1808] via-[#59260e] to-[#2e1205]">
                            <!-- Khung chữ bên trái: Căn lề an toàn, chữ vừa vặn nằm gọn 100% trong ảnh -->
                            <div class="col-span-7 flex flex-col justify-center px-10 lg:px-14 py-6 text-white z-10">
                                <div class="inline-flex items-center gap-2 px-3 py-1 rounded-full bg-gold-500/20 border border-gold-400/50 text-gold-400 text-xs font-semibold w-fit mb-3">
                                    <i class="fa-solid fa-crown"></i> XƯỞNG ĐỒ GỖ MỸ NGHỆ BẢO LÂM - BAOLAM.NET
                                </div>
                                <h1 class="font-serif font-bold text-2xl lg:text-3xl text-amber-100 leading-snug">
                                    TINH HOA ĐỒ GỖ MỸ NGHỆ CAO CẤP <br>
                                    <span class="text-gold-400">CHẾ TÁC THỦ CÔNG ĐẲNG CẤP</span>
                                </h1>
                                <p class="mt-3 text-xs lg:text-sm text-amber-100/90 leading-relaxed max-w-xl">
                                    Chuyên sản xuất Bàn ghế Hoàng Gia, Rồng Đỉnh, Minh Quốc, Bàn ăn nguyên khối, Giường tủ & Nội thất phòng thờ từ gỗ Hương Đá, Gõ Đỏ, Cẩm Lai tự nhiên 100%. Nhận đặt hàng theo kích thước yêu cầu.
                                </p>
                                <div class="mt-4 grid grid-cols-2 gap-2 text-xs text-amber-200 max-w-lg">
                                    <div class="flex items-center gap-1.5"><i class="fa-solid fa-circle-check text-gold-400"></i> Giá gốc tận xưởng không qua trung gian</div>
                                    <div class="flex items-center gap-1.5"><i class="fa-solid fa-circle-check text-gold-400"></i> Kiểm tra mộc trước khi sơn PU</div>
                                    <div class="flex items-center gap-1.5"><i class="fa-solid fa-location-dot text-gold-400"></i> 94 Nam Cao, P. Hòa Khánh, Đà Nẵng</div>
                                    <div class="flex items-center gap-1.5"><i class="fa-solid fa-phone-volume text-gold-400"></i> Hotline/Zalo: <strong>0905.265.586</strong></div>
                                </div>
                                <div class="mt-5 flex items-center gap-3">
                                    <a href="#sec-phong-khach" class="px-5 py-2.5 rounded-lg bg-gold-500 hover:bg-gold-400 text-wood-900 font-bold text-xs uppercase tracking-wider transition shadow">
                                        Xem Sản Phẩm Thực Tế
                                    </a>
                                    <a href="#bang-bao-gia" class="px-5 py-2.5 rounded-lg bg-white/10 hover:bg-white/20 text-white border border-amber-200/40 font-semibold text-xs uppercase tracking-wider transition">
                                        Nhận Báo Giá Tại Xưởng
                                    </a>
                                </div>
                            </div>
                            <!-- Khung ảnh thực tế bên phải -->
                            <div class="col-span-5 relative h-full p-5 flex items-center justify-center">
                                <div class="w-full h-full rounded-xl overflow-hidden border-2 border-gold-400/50 shadow-2xl relative">
                                    <img src="https://lh3.googleusercontent.com/d/17I0CSHLS9vjV-PtPdYwwU96vkDGzLJky=w1000" 
                                         onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=17I0CSHLS9vjV-PtPdYwwU96vkDGzLJky&sz=w1000';"
                                         alt="Sản phẩm thực tế Đồ Gỗ Bảo Lâm" class="w-full h-full object-cover">
                                    <div class="absolute bottom-2 right-2 bg-wood-900/85 text-gold-400 text-[11px] font-semibold px-3 py-1 rounded border border-gold-400/40">
                                        Ảnh thực tế tại Đồ Gỗ Bảo Lâm
                                    </div>
                                </div>
                            </div>
                        </div>
                    </div>

                    <!-- Desktop Slide 2 -->
                    <div id="desktop-slide-1" class="banner-slide-desktop absolute inset-0 w-full h-full transition-opacity duration-700 opacity-0 z-0">
                        <div class="grid grid-cols-12 h-full bg-gradient-to-r from-[#2c140a] via-[#4f220e] to-[#291106]">
                            <!-- Khung chữ bên trái: Căn lề an toàn, chữ nhỏ gọn nằm hết trong ảnh -->
                            <div class="col-span-7 flex flex-col justify-center px-10 lg:px-14 py-6 text-white z-10">
                                <div class="inline-flex items-center gap-2 px-3 py-1 rounded-full bg-gold-500/20 border border-gold-400/50 text-gold-400 text-xs font-semibold w-fit mb-3">
                                    <i class="fa-solid fa-gem"></i> ĐO VẼ & THI CÔNG NỘI THẤT THEO YÊU CẦU
                                </div>
                                <h2 class="font-serif font-bold text-2xl lg:text-3xl text-amber-100 leading-snug">
                                    NỘI THẤT PHÒNG KHÁCH - PHÒNG BẾP <br>
                                    <span class="text-gold-400">PHÒNG NGỦ & ĐỒ THỜ GIA TIÊN</span>
                                </h2>
                                <p class="mt-3 text-xs lg:text-sm text-amber-100/90 leading-relaxed max-w-xl">
                                    Quý khách có mẫu sẵn chỉ cần gửi hình ảnh và kích thước, xưởng Đồ Gỗ Mỹ Nghệ Bảo Lâm cam kết chế tác chuẩn mẫu 99%, hoàn thiện tỉ mỉ từng đường nét đục chạm thủ công.
                                </p>
                                <div class="mt-4 grid grid-cols-2 gap-2 text-xs text-amber-200 max-w-lg">
                                    <div class="flex items-center gap-1.5"><i class="fa-solid fa-truck-fast text-gold-400"></i> Giao hàng & lắp đặt tận nhà toàn quốc</div>
                                    <div class="flex items-center gap-1.5"><i class="fa-solid fa-medal text-gold-400"></i> Cam kết gỗ chuẩn nhóm 1 không rác</div>
                                    <div class="flex items-center gap-1.5"><i class="fa-solid fa-location-dot text-gold-400"></i> 94 Nam Cao, P. Hòa Khánh, Đà Nẵng</div>
                                    <div class="flex items-center gap-1.5"><i class="fa-solid fa-phone-volume text-gold-400"></i> Tư vấn 24/7: <strong>0905.265.586</strong></div>
                                </div>
                                <div class="mt-5 flex items-center gap-3">
                                    <a href="#bang-bao-gia" class="px-5 py-2.5 rounded-lg bg-gold-500 hover:bg-gold-400 text-wood-900 font-bold text-xs uppercase tracking-wider transition shadow">
                                        Gửi Mẫu & Nhận Báo Giá
                                    </a>
                                    <a href="#ban-do-trang-chu" class="px-5 py-2.5 rounded-lg bg-white/10 hover:bg-white/20 text-white border border-amber-200/40 font-semibold text-xs uppercase tracking-wider transition">
                                        Xem Bản Đồ Showroom
                                    </a>
                                </div>
                            </div>
                            <!-- Khung ảnh thực tế bên phải -->
                            <div class="col-span-5 relative h-full p-5 flex items-center justify-center">
                                <div class="w-full h-full rounded-xl overflow-hidden border-2 border-gold-400/50 shadow-2xl relative">
                                    <img src="https://lh3.googleusercontent.com/d/1kEWYtsSAdsLcPGfML3QcyiLzEoCwGvLJ=w1000" 
                                         onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1kEWYtsSAdsLcPGfML3QcyiLzEoCwGvLJ&sz=w1000';"
                                         alt="Tuyệt tác Đồ Gỗ Bảo Lâm" class="w-full h-full object-cover">
                                    <div class="absolute bottom-2 right-2 bg-wood-900/85 text-gold-400 text-[11px] font-semibold px-3 py-1 rounded border border-gold-400/40">
                                        Chế tác tinh xảo - baolam.net
                                    </div>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>

                <!-- ====== BANNER THIẾT KẾ MỚI RIÊNG CHO ĐIỆN THOẠI (2 SLIDE KÍCH THƯỚC BẰNG NHAU 350PX, CHỮ NHỎ NẰM HẾT TRONG ẢNH, KHÔNG TRÀN VIỀN) ====== -->
                <div class="block md:hidden relative w-full h-[350px]">
                    <!-- Mobile Slide 1 -->
                    <div id="mobile-slide-0" class="banner-slide-mobile absolute inset-0 w-full h-full transition-opacity duration-700 opacity-100 z-10 bg-gradient-to-b from-[#421d09] via-[#5e2c10] to-[#2e1205] p-3.5 flex flex-col justify-between">
                        <div class="flex items-center gap-2.5 bg-black/25 p-2 rounded-lg border border-gold-400/30">
                            <img src="https://lh3.googleusercontent.com/d/17I0CSHLS9vjV-PtPdYwwU96vkDGzLJky=w500" 
                                 onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=17I0CSHLS9vjV-PtPdYwwU96vkDGzLJky&sz=w500';"
                                 alt="Đồ Gỗ Bảo Lâm" class="w-20 h-20 rounded-md object-cover border border-gold-400 flex-shrink-0">
                            <div class="min-w-0 flex-1">
                                <span class="inline-block text-[10px] font-bold text-gold-400 uppercase tracking-wide">baolam.net • Đà Nẵng</span>
                                <h2 class="font-serif font-bold text-[13px] text-white leading-snug mt-0.5">
                                    ĐỒ GỖ MỸ NGHỆ BẢO LÂM
                                </h2>
                                <p class="text-[11px] text-amber-100/90 leading-tight mt-1">
                                    Chuyên Bàn ghế phòng khách, Bàn ăn, Giường tủ, Đồ thờ gỗ quý tự nhiên 100%.
                                </p>
                            </div>
                        </div>

                        <div class="bg-white/10 rounded-lg p-2.5 border border-white/15 text-[11px] text-amber-100 space-y-1">
                            <div class="flex items-center gap-1.5">
                                <i class="fa-solid fa-check text-gold-400 text-[10px]"></i>
                                <span>Đục chạm thủ công tinh xảo - Giá gốc tận xưởng</span>
                            </div>
                            <div class="flex items-center gap-1.5">
                                <i class="fa-solid fa-location-dot text-gold-400 text-[10px]"></i>
                                <span>Đ/c: 94 Nam Cao, P. Hòa Khánh, TP Đà Nẵng</span>
                            </div>
                            <div class="flex items-center gap-1.5">
                                <i class="fa-solid fa-phone text-gold-400 text-[10px]"></i>
                                <span>Hotline/Zalo: <strong class="text-gold-400">0905.265.586</strong></span>
                            </div>
                        </div>

                        <div class="grid grid-cols-2 gap-2">
                            <a href="#sec-phong-khach" class="py-2 px-2 rounded-lg bg-gold-500 text-wood-900 font-bold text-[11px] text-center">
                                Xem Sản Phẩm
                            </a>
                            <a href="#bang-bao-gia" class="py-2 px-2 rounded-lg bg-white/15 text-white border border-gold-400/40 font-semibold text-[11px] text-center">
                                Nhận Báo Giá
                            </a>
                        </div>
                    </div>

                    <!-- Mobile Slide 2 -->
                    <div id="mobile-slide-1" class="banner-slide-mobile absolute inset-0 w-full h-full transition-opacity duration-700 opacity-0 z-0 bg-gradient-to-b from-[#2e1205] via-[#54240c] to-[#381707] p-3.5 flex flex-col justify-between">
                        <div class="flex items-center gap-2.5 bg-black/25 p-2 rounded-lg border border-gold-400/30">
                            <img src="https://lh3.googleusercontent.com/d/1kEWYtsSAdsLcPGfML3QcyiLzEoCwGvLJ=w500" 
                                 onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1kEWYtsSAdsLcPGfML3QcyiLzEoCwGvLJ&sz=w500';"
                                 alt="Xưởng Gỗ Bảo Lâm" class="w-20 h-20 rounded-md object-cover border border-gold-400 flex-shrink-0">
                            <div class="min-w-0 flex-1">
                                <span class="inline-block text-[10px] font-bold text-gold-400 uppercase tracking-wide">Đặt Hàng Theo Yêu Cầu</span>
                                <h2 class="font-serif font-bold text-[13px] text-white leading-snug mt-0.5">
                                    CHẾ TÁC CHUẨN MẪU 99%
                                </h2>
                                <p class="text-[11px] text-amber-100/90 leading-tight mt-1">
                                    Nhận đo vẽ, thiết kế nội thất phòng khách, phòng bếp, phòng ngủ, phòng thờ.
                                </p>
                            </div>
                        </div>

                        <div class="bg-white/10 rounded-lg p-2.5 border border-white/15 text-[11px] text-amber-100 space-y-1">
                            <div class="flex items-center gap-1.5">
                                <i class="fa-solid fa-shield-halved text-gold-400 text-[10px]"></i>
                                <span>Bảo hành dài hạn - Vận chuyển lắp đặt tận nơi</span>
                            </div>
                            <div class="flex items-center gap-1.5">
                                <i class="fa-solid fa-location-dot text-gold-400 text-[10px]"></i>
                                <span>Showroom: 94 Nam Cao, Hòa Khánh, Đà Nẵng</span>
                            </div>
                            <div class="flex items-center gap-1.5">
                                <i class="fa-solid fa-phone text-gold-400 text-[10px]"></i>
                                <span>Tư vấn miễn phí: <strong class="text-gold-400">0905.265.586</strong></span>
                            </div>
                        </div>

                        <div class="grid grid-cols-2 gap-2">
                            <a href="#bang-bao-gia" class="py-2 px-2 rounded-lg bg-gold-500 text-wood-900 font-bold text-[11px] text-center">
                                Đặt Đóng Theo Mẫu
                            </a>
                            <a href="#ban-do-trang-chu" class="py-2 px-2 rounded-lg bg-white/15 text-white border border-gold-400/40 font-semibold text-[11px] text-center">
                                Xem Bản Đồ
                            </a>
                        </div>
                    </div>
                </div>

                <!-- Nút điều khiển Banner trái/phải & chấm tròn -->
                <button onclick="prevBannerSlide()" aria-label="Slide trước" class="absolute left-2 top-1/2 -translate-y-1/2 z-20 w-8 h-8 rounded-full bg-black/40 hover:bg-black/70 text-white flex items-center justify-center transition">
                    <i class="fa-solid fa-chevron-left text-xs"></i>
                </button>
                <button onclick="nextBannerSlide()" aria-label="Slide tiếp" class="absolute right-2 top-1/2 -translate-y-1/2 z-20 w-8 h-8 rounded-full bg-black/40 hover:bg-black/70 text-white flex items-center justify-center transition">
                    <i class="fa-solid fa-chevron-right text-xs"></i>
                </button>
                <div class="absolute bottom-2 left-1/2 -translate-x-1/2 z-20 flex items-center gap-2">
                    <button id="banner-dot-0" onclick="goToBannerSlide(0)" class="w-6 h-2 rounded-full bg-gold-400 transition-all"></button>
                    <button id="banner-dot-1" onclick="goToBannerSlide(1)" class="w-2 h-2 rounded-full bg-white/50 transition-all"></button>
                </div>

            </div>
        </div>
    </section>

    <!-- ==========================================
         GIỚI THIỆU NGẮN XƯỞNG ĐỒ GỖ MỸ NGHỆ BẢO LÂM (GIỐNG MẪU DOGOPHAMGIA.COM)
         ========================================== -->
    <section class="py-4">
        <div class="flatsome-container">
            <div class="bg-white rounded-xl p-4 sm:p-6 border border-stone-200 shadow-sm text-center">
                <h2 class="font-serif font-bold text-lg sm:text-2xl text-wood-800 uppercase tracking-wide">
                    ĐỒ GỖ MỸ NGHỆ BẢO LÂM - XƯỞNG SẢN XUẤT NỘI THẤT GỖ TỰ NHIÊN UY TÍN
                </h2>
                <div class="w-24 h-1 bg-gold-500 mx-auto my-2.5 rounded-full"></div>
                <p class="text-xs sm:text-sm text-stone-600 max-w-4xl mx-auto leading-relaxed">
                    Xưởng <strong>Đồ Gỗ Mỹ Nghệ Bảo Lâm (baolam.net)</strong> tại <strong>94 Nam Cao, Phường Hòa Khánh, TP Đà Nẵng</strong> chuyên sản xuất và phân phối các sản phẩm đồ gỗ nội thất đo vẽ theo yêu cầu của khách hàng. Bao gồm bàn ghế gỗ phòng khách (Hoàng Gia, Rồng Đỉnh, Tần Thủy Hoàng, Âu Á, Minh Quốc), sofa gỗ cao cấp, bàn ghế ăn nguyên khối, kệ tivi, sập thờ, án gian, lục bình phong thủy, giường ngủ, tủ quần áo, bàn trang điểm… Quý khách có mẫu sẵn chỉ cần gửi hình ảnh và kích thước qua Zalo <strong>0905.265.586</strong> là xưởng có thể chế tác chuẩn 99% theo mẫu.
                </p>
            </div>
        </div>
    </section>

    <!-- ==========================================
         DANH MỤC SẢN PHẨM TRANG CHỦ (CHỮ NHỎ GỌN, KHÔNG XUỐNG DÒNG TÊN DANH MỤC, CHUẨN DOGOPHAMGIA.COM)
         ========================================== -->
    <section id="danh-muc-trang-chu" class="py-3">
        <div class="flatsome-container">
            <div class="bg-white rounded-xl p-4 border border-stone-200 shadow-sm">
                <div class="flex items-center justify-between mb-3 pb-2 border-b border-stone-200">
                    <h2 class="font-bold text-sm sm:text-base text-wood-800 uppercase flex items-center gap-2">
                        <i class="fa-solid fa-layer-group text-wood-600"></i>
                        Danh Mục Sản Phẩm Chủ Lực
                    </h2>
                    <button onclick="filterCategory('all')" class="text-xs font-semibold text-wood-700 hover:text-wood-900 whitespace-nowrap">
                        Xem tất cả (13 sản phẩm thực tế) <i class="fa-solid fa-arrow-right ml-1"></i>
                    </button>
                </div>

                <!-- Grid danh mục chữ nhỏ gọn, tên danh mục không bị gãy dòng -->
                <div class="grid grid-cols-2 sm:grid-cols-3 md:grid-cols-4 lg:grid-cols-6 gap-2.5">
                    <a href="#sec-phong-khach" onclick="filterCategory('hoang-gia')" class="group flex items-center gap-2.5 p-2 rounded-lg border border-stone-200 hover:border-wood-600 hover:bg-wood-50 transition">
                        <img src="https://lh3.googleusercontent.com/d/17I0CSHLS9vjV-PtPdYwwU96vkDGzLJky=w200" 
                             onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=17I0CSHLS9vjV-PtPdYwwU96vkDGzLJky&sz=w200';"
                             alt="Bàn ghế Hoàng Gia" class="w-10 h-10 rounded object-cover flex-shrink-0 border border-stone-200">
                        <div class="min-w-0">
                            <div class="text-[11.5px] font-bold text-wood-900 group-hover:text-wood-700 whitespace-nowrap">Bàn ghế Hoàng Gia</div>
                            <div class="text-[10px] text-stone-500 whitespace-nowrap">Phòng khách VIP</div>
                        </div>
                    </a>

                    <a href="#sec-phong-khach" onclick="filterCategory('rong-dinh')" class="group flex items-center gap-2.5 p-2 rounded-lg border border-stone-200 hover:border-wood-600 hover:bg-wood-50 transition">
                        <img src="https://lh3.googleusercontent.com/d/1kEWYtsSAdsLcPGfML3QcyiLzEoCwGvLJ=w200" 
                             onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1kEWYtsSAdsLcPGfML3QcyiLzEoCwGvLJ&sz=w200';"
                             alt="Bàn ghế Rồng Đỉnh" class="w-10 h-10 rounded object-cover flex-shrink-0 border border-stone-200">
                        <div class="min-w-0">
                            <div class="text-[11.5px] font-bold text-wood-900 group-hover:text-wood-700 whitespace-nowrap">Bàn ghế Rồng Đỉnh</div>
                            <div class="text-[10px] text-stone-500 whitespace-nowrap">Đục tay mỹ nghệ</div>
                        </div>
                    </a>

                    <a href="#sec-phong-khach" onclick="filterCategory('tan-thuy-hoang')" class="group flex items-center gap-2.5 p-2 rounded-lg border border-stone-200 hover:border-wood-600 hover:bg-wood-50 transition">
                        <img src="https://lh3.googleusercontent.com/d/1eLxbKDSKrHUYROvydx0ZhQpYT16dL9Hp=w200" 
                             onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1eLxbKDSKrHUYROvydx0ZhQpYT16dL9Hp&sz=w200';"
                             alt="Tần Thủy Hoàng" class="w-10 h-10 rounded object-cover flex-shrink-0 border border-stone-200">
                        <div class="min-w-0">
                            <div class="text-[11.5px] font-bold text-wood-900 group-hover:text-wood-700 whitespace-nowrap">Tần Thủy Hoàng</div>
                            <div class="text-[10px] text-stone-500 whitespace-nowrap">Dáng cột cong</div>
                        </div>
                    </a>

                    <a href="#sec-phong-khach" onclick="filterCategory('au-a')" class="group flex items-center gap-2.5 p-2 rounded-lg border border-stone-200 hover:border-wood-600 hover:bg-wood-50 transition">
                        <img src="https://lh3.googleusercontent.com/d/1i4EcMyV9pbK2Z_w0gLyAGLWDDgKyvJzj=w200" 
                             onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1i4EcMyV9pbK2Z_w0gLyAGLWDDgKyvJzj&sz=w200';"
                             alt="Bàn ghế Âu Á" class="w-10 h-10 rounded object-cover flex-shrink-0 border border-stone-200">
                        <div class="min-w-0">
                            <div class="text-[11.5px] font-bold text-wood-900 group-hover:text-wood-700 whitespace-nowrap">Bàn ghế Âu Á</div>
                            <div class="text-[10px] text-stone-500 whitespace-nowrap">Hiện đại sang trọng</div>
                        </div>
                    </a>

                    <a href="#sec-phong-khach" onclick="filterCategory('minh-quoc')" class="group flex items-center gap-2.5 p-2 rounded-lg border border-stone-200 hover:border-wood-600 hover:bg-wood-50 transition">
                        <img src="https://lh3.googleusercontent.com/d/1cAaStBVcvuIMuNGEwGTyO5BBzLdbhXWO=w200" 
                             onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1cAaStBVcvuIMuNGEwGTyO5BBzLdbhXWO&sz=w200';"
                             alt="Bàn ghế Minh Quốc" class="w-10 h-10 rounded object-cover flex-shrink-0 border border-stone-200">
                        <div class="min-w-0">
                            <div class="text-[11.5px] font-bold text-wood-900 group-hover:text-wood-700 whitespace-nowrap">Bàn ghế Minh Quốc</div>
                            <div class="text-[10px] text-stone-500 whitespace-nowrap">Truyền thống bền đẹp</div>
                        </div>
                    </a>

                    <a href="#sec-phong-khach" onclick="filterCategory('ke-tivi')" class="group flex items-center gap-2.5 p-2 rounded-lg border border-stone-200 hover:border-wood-600 hover:bg-wood-50 transition">
                        <img src="https://lh3.googleusercontent.com/d/1iTUWrN3NI6RfUX7MaGEV9k_t9mG868EE=w200" 
                             onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1iTUWrN3NI6RfUX7MaGEV9k_t9mG868EE&sz=w200';"
                             alt="Kệ Tivi Gỗ" class="w-10 h-10 rounded object-cover flex-shrink-0 border border-stone-200">
                        <div class="min-w-0">
                            <div class="text-[11.5px] font-bold text-wood-900 group-hover:text-wood-700 whitespace-nowrap">Kệ Tivi - Đồng hồ</div>
                            <div class="text-[10px] text-stone-500 whitespace-nowrap">Nguyên khối & Mõ lồi</div>
                        </div>
                    </a>

                    <a href="#sec-phong-bep" onclick="filterCategory('phong-bep')" class="group flex items-center gap-2.5 p-2 rounded-lg border border-stone-200 hover:border-wood-600 hover:bg-wood-50 transition">
                        <img src="https://lh3.googleusercontent.com/d/1qp0LECZZldxrDlEizT-PnmEoe-pIsKql=w200" 
                             onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1qp0LECZZldxrDlEizT-PnmEoe-pIsKql&sz=w200';"
                             alt="Bàn ghế ăn" class="w-10 h-10 rounded object-cover flex-shrink-0 border border-stone-200">
                        <div class="min-w-0">
                            <div class="text-[11.5px] font-bold text-wood-900 group-hover:text-wood-700 whitespace-nowrap">Bàn ghế ăn gỗ</div>
                            <div class="text-[10px] text-stone-500 whitespace-nowrap">6 ghế - 8 ghế - 10 ghế</div>
                        </div>
                    </a>

                    <a href="#sec-phong-bep" onclick="filterCategory('phong-bep')" class="group flex items-center gap-2.5 p-2 rounded-lg border border-stone-200 hover:border-wood-600 hover:bg-wood-50 transition">
                        <img src="https://lh3.googleusercontent.com/d/1HiwnZSN-MQLSaZ22EPwDTUc7CCokytAE=w200" 
                             onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1HiwnZSN-MQLSaZ22EPwDTUc7CCokytAE&sz=w200';"
                             alt="Tủ rượu gỗ" class="w-10 h-10 rounded object-cover flex-shrink-0 border border-stone-200">
                        <div class="min-w-0">
                            <div class="text-[11.5px] font-bold text-wood-900 group-hover:text-wood-700 whitespace-nowrap">Tủ rượu - Quầy bar</div>
                            <div class="text-[10px] text-stone-500 whitespace-nowrap">Nội thất phòng bếp</div>
                        </div>
                    </a>

                    <a href="#sec-phong-ngu" onclick="filterCategory('phong-ngu')" class="group flex items-center gap-2.5 p-2 rounded-lg border border-stone-200 hover:border-wood-600 hover:bg-wood-50 transition">
                        <img src="https://lh3.googleusercontent.com/d/1dA75Boh5gUl0uPANMVOIKmMOJqBYShtz=w200" 
                             onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1dA75Boh5gUl0uPANMVOIKmMOJqBYShtz&sz=w200';"
                             alt="Giường ngủ" class="w-10 h-10 rounded object-cover flex-shrink-0 border border-stone-200">
                        <div class="min-w-0">
                            <div class="text-[11.5px] font-bold text-wood-900 group-hover:text-wood-700 whitespace-nowrap">Giường ngủ gỗ quý</div>
                            <div class="text-[10px] text-stone-500 whitespace-nowrap">Hoàng Gia & Chân quỳ</div>
                        </div>
                    </a>

                    <a href="#sec-phong-ngu" onclick="filterCategory('phong-ngu')" class="group flex items-center gap-2.5 p-2 rounded-lg border border-stone-200 hover:border-wood-600 hover:bg-wood-50 transition">
                        <img src="https://lh3.googleusercontent.com/d/1M6D1QTHl9T1lLy-xLZlNDdRMMq4lBmw7=w200" 
                             onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1M6D1QTHl9T1lLy-xLZlNDdRMMq4lBmw7&sz=w200';"
                             alt="Tủ quần áo" class="w-10 h-10 rounded object-cover flex-shrink-0 border border-stone-200">
                        <div class="min-w-0">
                            <div class="text-[11.5px] font-bold text-wood-900 group-hover:text-wood-700 whitespace-nowrap">Tủ quần áo - Bàn phấn</div>
                            <div class="text-[10px] text-stone-500 whitespace-nowrap">Combo phòng ngủ</div>
                        </div>
                    </a>

                    <a href="#sec-phong-tho" onclick="filterCategory('phong-tho')" class="group flex items-center gap-2.5 p-2 rounded-lg border border-stone-200 hover:border-wood-600 hover:bg-wood-50 transition">
                        <img src="https://lh3.googleusercontent.com/d/1rJLV7jlxhSbUksXvNV3IJv9e1zziYoVw=w200" 
                             onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1rJLV7jlxhSbUksXvNV3IJv9e1zziYoVw&sz=w200';"
                             alt="Sập thờ Án gian" class="w-10 h-10 rounded object-cover flex-shrink-0 border border-stone-200">
                        <div class="min-w-0">
                            <div class="text-[11.5px] font-bold text-wood-900 group-hover:text-wood-700 whitespace-nowrap">Sập thờ - Án gian</div>
                            <div class="text-[10px] text-stone-500 whitespace-nowrap">Nội thất phòng thờ</div>
                        </div>
                    </a>

                    <a href="#sec-phong-tho" onclick="filterCategory('phong-tho')" class="group flex items-center gap-2.5 p-2 rounded-lg border border-stone-200 hover:border-wood-600 hover:bg-wood-50 transition">
                        <img src="https://lh3.googleusercontent.com/d/1kx82MVqz_XcghMo0pK67_kb5BVmt_Er1=w200" 
                             onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1kx82MVqz_XcghMo0pK67_kb5BVmt_Er1&sz=w200';"
                             alt="Lục bình phong thủy" class="w-10 h-10 rounded object-cover flex-shrink-0 border border-stone-200">
                        <div class="min-w-0">
                            <div class="text-[11.5px] font-bold text-wood-900 group-hover:text-wood-700 whitespace-nowrap">Lục bình - Tượng gỗ</div>
                            <div class="text-[10px] text-stone-500 whitespace-nowrap">Mỹ nghệ phong thủy</div>
                        </div>
                    </a>
                </div>
            </div>
        </div>
    </section>

    <!-- Thông báo trạng thái lọc danh mục / tìm kiếm (ẩn mặc định) -->
    <div id="filterStatusBanner" class="flatsome-container hidden my-2">
        <div class="bg-amber-50 border border-amber-300 rounded-lg px-4 py-2.5 flex items-center justify-between text-xs sm:text-sm">
            <span id="filterStatusText" class="font-semibold text-wood-800">Đang hiển thị sản phẩm theo bộ lọc</span>
            <button onclick="filterCategory('all')" class="px-3 py-1 rounded bg-wood-800 text-white text-xs font-semibold hover:bg-wood-700">
                Hiển thị tất cả
            </button>
        </div>
    </div>

    <!-- ==========================================
         SECTION 1: NỘI THẤT PHÒNG KHÁCH (7 ẢNH SẢN PHẨM THỰC TẾ)
         - Điện thoại chia 2 cột (grid-cols-2)
         - Tên sản phẩm hiển thị đầy đủ không tràn/không cắt chữ
         - Chỉ có vòng tròn % giảm giá góc trên bên trái chuẩn Flatsome, không để nhãn dán khác
         ========================================== -->
    <section id="sec-phong-khach" class="py-4 product-section">
        <div class="flatsome-container">
            <div class="flatsome-section-header">
                <div class="flatsome-section-title">
                    <i class="fa-solid fa-couch"></i>
                    <span>NỘI THẤT PHÒNG KHÁCH</span>
                </div>
                <div class="flex items-center gap-1.5 px-3 py-1.5 overflow-x-auto text-xs font-medium text-stone-700">
                    <button onclick="filterCategory('hoang-gia')" class="nav-cat-item px-2.5 py-1 rounded hover:bg-wood-50 hover:text-wood-800">Bàn ghế Hoàng Gia</button>
                    <button onclick="filterCategory('rong-dinh')" class="nav-cat-item px-2.5 py-1 rounded hover:bg-wood-50 hover:text-wood-800">Bàn ghế Rồng Đỉnh</button>
                    <button onclick="filterCategory('tan-thuy-hoang')" class="nav-cat-item px-2.5 py-1 rounded hover:bg-wood-50 hover:text-wood-800">Bàn ghế Tần Thủy Hoàng</button>
                    <button onclick="filterCategory('au-a')" class="nav-cat-item px-2.5 py-1 rounded hover:bg-wood-50 hover:text-wood-800">Bàn ghế Âu Á</button>
                    <button onclick="filterCategory('minh-quoc')" class="nav-cat-item px-2.5 py-1 rounded hover:bg-wood-50 hover:text-wood-800">Bàn ghế Minh Quốc</button>
                    <button onclick="filterCategory('ke-tivi')" class="nav-cat-item px-2.5 py-1 rounded hover:bg-wood-50 hover:text-wood-800">Kệ Tivi & Đồng hồ</button>
                    <button onclick="filterCategory('all')" class="nav-cat-item px-2.5 py-1 rounded text-wood-700 font-bold hover:underline">Xem tất cả</button>
                </div>
            </div>

            <!-- Grid sản phẩm: 2 cột trên điện thoại, 4 cột trên máy tính -->
            <div id="grid-phong-khach" class="grid grid-cols-2 md:grid-cols-3 lg:grid-cols-4 gap-3 sm:gap-5"></div>
        </div>
    </section>

    <!-- ==========================================
         SECTION 2: NỘI THẤT PHÒNG BẾP (BÀN GHẾ ĂN & TỦ RƯỢU THỰC TẾ)
         ========================================== -->
    <section id="sec-phong-bep" class="py-4 product-section">
        <div class="flatsome-container">
            <div class="flatsome-section-header">
                <div class="flatsome-section-title">
                    <i class="fa-solid fa-utensils"></i>
                    <span>NỘI THẤT PHÒNG BẾP</span>
                </div>
                <div class="flex items-center gap-1.5 px-3 py-1.5 overflow-x-auto text-xs font-medium text-stone-700">
                    <button onclick="filterCategory('phong-bep')" class="nav-cat-item px-2.5 py-1 rounded hover:bg-wood-50 hover:text-wood-800">Bàn ghế ăn nguyên khối</button>
                    <button onclick="filterCategory('phong-bep')" class="nav-cat-item px-2.5 py-1 rounded hover:bg-wood-50 hover:text-wood-800">Bàn ăn Hoàng Gia 8 ghế</button>
                    <button onclick="filterCategory('phong-bep')" class="nav-cat-item px-2.5 py-1 rounded hover:bg-wood-50 hover:text-wood-800">Tủ rượu gỗ tự nhiên</button>
                    <button onclick="filterCategory('all')" class="nav-cat-item px-2.5 py-1 rounded text-wood-700 font-bold hover:underline">Xem tất cả</button>
                </div>
            </div>

            <div id="grid-phong-bep" class="grid grid-cols-2 md:grid-cols-3 lg:grid-cols-4 gap-3 sm:gap-5"></div>
        </div>
    </section>

    <!-- ==========================================
         SECTION 3: NỘI THẤT PHÒNG NGỦ (GIƯỜNG NGỦ, TỦ QUẦN ÁO, BÀN TRANG ĐIỂM)
         ========================================== -->
    <section id="sec-phong-ngu" class="py-4 product-section">
        <div class="flatsome-container">
            <div class="flatsome-section-header">
                <div class="flatsome-section-title">
                    <i class="fa-solid fa-bed"></i>
                    <span>NỘI THẤT PHÒNG NGỦ</span>
                </div>
                <div class="flex items-center gap-1.5 px-3 py-1.5 overflow-x-auto text-xs font-medium text-stone-700">
                    <button onclick="filterCategory('phong-ngu')" class="nav-cat-item px-2.5 py-1 rounded hover:bg-wood-50 hover:text-wood-800">Giường ngủ Hoàng Gia</button>
                    <button onclick="filterCategory('phong-ngu')" class="nav-cat-item px-2.5 py-1 rounded hover:bg-wood-50 hover:text-wood-800">Tủ quần áo gỗ Hương</button>
                    <button onclick="filterCategory('phong-ngu')" class="nav-cat-item px-2.5 py-1 rounded hover:bg-wood-50 hover:text-wood-800">Bàn trang điểm</button>
                    <button onclick="filterCategory('all')" class="nav-cat-item px-2.5 py-1 rounded text-wood-700 font-bold hover:underline">Xem tất cả</button>
                </div>
            </div>

            <div id="grid-phong-ngu" class="grid grid-cols-2 md:grid-cols-3 lg:grid-cols-4 gap-3 sm:gap-5"></div>
        </div>
    </section>

    <!-- ==========================================
         SECTION 4: NỘI THẤT PHÒNG THỜ & ĐỒ GỖ MỸ NGHỆ (SẬP THỜ, ÁN GIAN, LỤC BÌNH)
         ========================================== -->
    <section id="sec-phong-tho" class="py-4 product-section">
        <div class="flatsome-container">
            <div class="flatsome-section-header">
                <div class="flatsome-section-title">
                    <i class="fa-solid fa-place-of-worship"></i>
                    <span>NỘI THẤT PHÒNG THỜ & ĐỒ THỜ</span>
                </div>
                <div class="flex items-center gap-1.5 px-3 py-1.5 overflow-x-auto text-xs font-medium text-stone-700">
                    <button onclick="filterCategory('phong-tho')" class="nav-cat-item px-2.5 py-1 rounded hover:bg-wood-50 hover:text-wood-800">Án gian thờ</button>
                    <button onclick="filterCategory('phong-tho')" class="nav-cat-item px-2.5 py-1 rounded hover:bg-wood-50 hover:text-wood-800">Sập thờ Tứ Linh</button>
                    <button onclick="filterCategory('phong-tho')" class="nav-cat-item px-2.5 py-1 rounded hover:bg-wood-50 hover:text-wood-800">Hoành phi câu đối</button>
                    <button onclick="filterCategory('phong-tho')" class="nav-cat-item px-2.5 py-1 rounded hover:bg-wood-50 hover:text-wood-800">Lục bình gỗ quý</button>
                    <button onclick="filterCategory('all')" class="nav-cat-item px-2.5 py-1 rounded text-wood-700 font-bold hover:underline">Xem tất cả</button>
                </div>
            </div>

            <div id="grid-phong-tho" class="grid grid-cols-2 md:grid-cols-3 lg:grid-cols-4 gap-3 sm:gap-5"></div>
        </div>
    </section>

    <!-- ==========================================
         CAM KẾT VÀNG CỦA XƯỞNG ĐỒ GỖ MỸ NGHỆ BẢO LÂM (GIỐNG MẪU DOGOPHAMGIA.COM)
         ========================================== -->
    <section class="py-5">
        <div class="flatsome-container">
            <div class="bg-gradient-to-r from-wood-900 via-wood-800 to-wood-900 rounded-xl p-5 sm:p-7 text-white shadow-md border border-wood-700">
                <div class="text-center mb-5">
                    <h2 class="font-serif font-bold text-lg sm:text-2xl text-gold-400 uppercase">
                        ĐỒ GỖ MỸ NGHỆ BẢO LÂM - CAM KẾT CHẤT LƯỢNG TẬN XƯỞNG
                    </h2>
                    <p class="text-xs sm:text-sm text-amber-100/90 mt-1">
                        Uy tín tạo dựng thương hiệu Đồ Gỗ Bảo Lâm tại Đà Nẵng & Khu vực Miền Trung - Tây Nguyên
                    </p>
                </div>
                <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-3 gap-4 text-xs sm:text-sm">
                    <div class="bg-white/10 rounded-lg p-4 border border-white/15 flex items-start gap-3">
                        <i class="fa-solid fa-hammer text-gold-400 text-xl mt-0.5"></i>
                        <div>
                            <h3 class="font-bold text-amber-200">Sản xuất & phân phối trực tiếp</h3>
                            <p class="text-amber-100/85 mt-1 leading-relaxed">Nhận đặt hàng theo yêu cầu riêng của quý khách, giá gốc tại xưởng không qua trung gian.</p>
                        </div>
                    </div>
                    <div class="bg-white/10 rounded-lg p-4 border border-white/15 flex items-start gap-3">
                        <i class="fa-solid fa-hand-sparkles text-gold-400 text-xl mt-0.5"></i>
                        <div>
                            <h3 class="font-bold text-amber-200">Hàng thủ công mỹ nghệ đục tay</h3>
                            <p class="text-amber-100/85 mt-1 leading-relaxed">Hoàn thiện kỹ lưỡng đến từng chi tiết nhỏ nhất bởi đội ngũ nghệ nhân lành nghề lâu năm.</p>
                        </div>
                    </div>
                    <div class="bg-white/10 rounded-lg p-4 border border-white/15 flex items-start gap-3">
                        <i class="fa-solid fa-truck-ramp-box text-gold-400 text-xl mt-0.5"></i>
                        <div>
                            <h3 class="font-bold text-amber-200">Kiểm tra hàng trước, thanh toán sau</h3>
                            <p class="text-amber-100/85 mt-1 leading-relaxed">Vận chuyển an toàn tận nhà quý khách, nghiệm thu đúng chủng loại gỗ mới thanh toán.</p>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- ==========================================
         FORM YÊU CẦU VÀ BÁO GIÁ TRANG CHỦ
         ========================================== -->
    <section id="bang-bao-gia" class="py-5">
        <div class="flatsome-container">
            <div class="bg-white rounded-xl border-2 border-wood-600 shadow-md overflow-hidden">
                <div class="grid grid-cols-1 lg:grid-cols-12">
                    <!-- Cột thông tin tư vấn đặt hàng -->
                    <div class="lg:col-span-5 bg-wood-800 text-white p-5 sm:p-7 flex flex-col justify-between">
                        <div>
                            <span class="inline-block px-3 py-1 rounded bg-gold-500 text-wood-900 font-bold text-xs uppercase">
                                Tư Vấn & Báo Giá Nhanh
                            </span>
                            <h2 class="font-serif font-bold text-xl sm:text-2xl text-gold-400 mt-3 leading-snug">
                                ĐĂNG KÝ YÊU CẦU TƯ VẤN & NHẬN BÁO GIÁ TẠI XƯỞNG
                            </h2>
                            <p class="text-xs sm:text-sm text-amber-100/90 mt-2.5 leading-relaxed">
                                Quý khách cần tư vấn kích thước phong thủy Lỗ Ban, chất liệu gỗ Hương Đá, Gõ Đỏ, Cẩm Lai, Gụ Lào hoặc đặt đóng theo mẫu riêng? Hãy để lại thông tin, Kỹ thuật trưởng của <strong>Đồ Gỗ Bảo Lâm</strong> sẽ liên hệ báo giá chi tiết trong 5 phút!
                            </p>
                            <ul class="mt-4 space-y-2.5 text-xs sm:text-sm text-amber-100">
                                <li class="flex items-center gap-2.5">
                                    <i class="fa-solid fa-phone-volume text-gold-400 w-4"></i>
                                    <span>Hotline/Zalo: <strong class="text-gold-400 text-base">0905.265.586</strong></span>
                                </li>
                                <li class="flex items-center gap-2.5">
                                    <i class="fa-solid fa-location-dot text-gold-400 w-4"></i>
                                    <span>Địa chỉ: <strong>94 Nam Cao, Phường Hòa Khánh, TP Đà Nẵng</strong></span>
                                </li>
                                <li class="flex items-center gap-2.5">
                                    <i class="fa-solid fa-globe text-gold-400 w-4"></i>
                                    <span>Website chính thức: <strong>baolam.net</strong></span>
                                </li>
                            </ul>
                        </div>
                        <div class="mt-6 pt-4 border-t border-wood-700 flex items-center gap-3">
                            <img src="https://lh3.googleusercontent.com/d/1egxad2JO9d8csN2hRnKiu-wtocfV1Paj=w200" 
                                 onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1egxad2JO9d8csN2hRnKiu-wtocfV1Paj&sz=w200';"
                                 alt="Logo Bảo Lâm" class="w-11 h-11 rounded bg-white p-1 object-contain">
                            <div class="text-xs text-amber-200">
                                <div class="font-bold text-white">CÔNG TY CỔ PHẦN BẢO LÂM</div>
                                <div>Khảo sát & đo đạc miễn phí tận nhà tại Đà Nẵng</div>
                            </div>
                        </div>
                    </div>

                    <!-- Cột Form nhập yêu cầu báo giá -->
                    <div class="lg:col-span-7 p-5 sm:p-7 bg-white">
                        <form id="quoteRequestForm" onsubmit="handleQuoteSubmit(event)" class="space-y-4">
                            <div class="grid grid-cols-1 sm:grid-cols-2 gap-4">
                                <div>
                                    <label class="block text-xs font-bold text-stone-700 mb-1">Họ và tên Quý khách *</label>
                                    <input id="quoteName" type="text" required placeholder="Nhập họ và tên..." 
                                           class="w-full px-3.5 py-2.5 text-xs sm:text-sm rounded-lg border border-stone-300 focus:outline-none focus:border-wood-700 bg-stone-50 focus:bg-white">
                                </div>
                                <div>
                                    <label class="block text-xs font-bold text-stone-700 mb-1">Số điện thoại / Zalo *</label>
                                    <input id="quotePhone" type="tel" required placeholder="Ví dụ: 0905265586" 
                                           class="w-full px-3.5 py-2.5 text-xs sm:text-sm rounded-lg border border-stone-300 focus:outline-none focus:border-wood-700 bg-stone-50 focus:bg-white">
                                </div>
                            </div>

                            <div class="grid grid-cols-1 sm:grid-cols-2 gap-4">
                                <div>
                                    <label class="block text-xs font-bold text-stone-700 mb-1">Danh mục sản phẩm quan tâm *</label>
                                    <select id="quoteCategory" class="w-full px-3.5 py-2.5 text-xs sm:text-sm rounded-lg border border-stone-300 focus:outline-none focus:border-wood-700 bg-stone-50 focus:bg-white">
                                        <option value="Bàn ghế Phòng Khách (Hoàng Gia, Rồng Đỉnh, Minh Quốc...)">Bàn ghế Phòng Khách (Hoàng Gia, Rồng Đỉnh, Minh Quốc...)</option>
                                        <option value="Sofa Gỗ Tự Nhiên Nguyên Khối">Sofa Gỗ Tự Nhiên Nguyên Khối</option>
                                        <option value="Kệ Tivi - Đồng Hồ Cây - Chiếu Ngựa">Kệ Tivi - Đồng Hồ Cây - Chiếu Ngựa</option>
                                        <option value="Nội thất Phòng Bếp (Bàn ghế ăn, Tủ rượu)">Nội thất Phòng Bếp (Bàn ghế ăn, Tủ rượu)</option>
                                        <option value="Nội thất Phòng Ngủ (Giường ngủ, Tủ quần áo)">Nội thất Phòng Ngủ (Giường ngủ, Tủ quần áo)</option>
                                        <option value="Nội thất Phòng Thờ (Sập thờ, Án gian, Lục bình)">Nội thất Phòng Thờ (Sập thờ, Án gian, Lục bình)</option>
                                        <option value="Đặt đóng theo kích thước & bản vẽ riêng">Đặt đóng theo kích thước & bản vẽ riêng</option>
                                    </select>
                                </div>
                                <div>
                                    <label class="block text-xs font-bold text-stone-700 mb-1">Chất liệu gỗ yêu thích</label>
                                    <select id="quoteMaterial" class="w-full px-3.5 py-2.5 text-xs sm:text-sm rounded-lg border border-stone-300 focus:outline-none focus:border-wood-700 bg-stone-50 focus:bg-white">
                                        <option value="Gỗ Hương Đá Nam Phi">Gỗ Hương Đá Cao Cấp</option>
                                        <option value="Gỗ Gõ Đỏ">Gỗ Gõ Đỏ Tự Nhiên</option>
                                        <option value="Gỗ Cẩm Lai / Gỗ Gụ">Gỗ Cẩm Vàng / Cẩm Lai / Gỗ Gụ</option>
                                        <option value="Gỗ Mun Hoa">Gỗ Mun Hoa Quý Hiếm</option>
                                        <option value="Cần xưởng tư vấn loại gỗ phù hợp">Cần xưởng tư vấn loại gỗ phù hợp ngân sách</option>
                                    </select>
                                </div>
                            </div>

                            <div>
                                <label class="block text-xs font-bold text-stone-700 mb-1">Yêu cầu chi tiết (Kích thước phòng, mẫu sản phẩm, địa chỉ giao hàng...)</label>
                                <textarea id="quoteNote" rows="3" placeholder="Nhập yêu cầu cụ thể hoặc tên sản phẩm Quý khách muốn báo giá..." 
                                          class="w-full px-3.5 py-2.5 text-xs sm:text-sm rounded-lg border border-stone-300 focus:outline-none focus:border-wood-700 bg-stone-50 focus:bg-white"></textarea>
                            </div>

                            <div class="flex flex-wrap items-center justify-between gap-3 pt-1">
                                <button type="submit" class="px-6 py-3 rounded-lg bg-wood-800 hover:bg-wood-700 text-gold-400 font-bold text-xs sm:text-sm uppercase tracking-wider shadow transition flex items-center gap-2">
                                    <i class="fa-solid fa-paper-plane"></i>
                                    Gửi Yêu Cầu Báo Giá Ngay
                                </button>
                                <a href="https://zalo.me/0905265586" target="_blank" rel="noopener noreferrer" class="px-4 py-2.5 rounded-lg bg-blue-600 hover:bg-blue-700 text-white font-semibold text-xs flex items-center gap-1.5 transition">
                                    <i class="fa-solid fa-comment-dots"></i> Chat Zalo: 0905.265.586
                                </a>
                            </div>

                            <!-- Hộp thông báo gửi thành công (không dùng alert) -->
                            <div id="quoteSuccessBox" class="hidden p-3.5 rounded-lg bg-emerald-50 border border-emerald-300 text-emerald-900 text-xs sm:text-sm"></div>
                        </form>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- ==========================================
         DANH MỤC CÁC BÀI VIẾT TRANG CHỦ (TIN TỨC & KINH NGHIỆM ĐỒ GỖ)
         ========================================== -->
    <section id="sec-tin-tuc" class="py-4">
        <div class="flatsome-container">
            <div class="flatsome-section-header">
                <div class="flatsome-section-title">
                    <i class="fa-solid fa-newspaper"></i>
                    <span>DANH MỤC BÀI VIẾT & KINH NGHIỆM ĐỒ GỖ</span>
                </div>
                <div class="px-3 py-1.5 text-xs font-semibold text-wood-700">
                    Cẩm nang chọn nội thất gỗ quý • baolam.net
                </div>
            </div>

            <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-4 gap-4">
                <!-- Bài viết 1 -->
                <article class="bg-white rounded-xl border border-stone-200 overflow-hidden shadow-sm hover:shadow-md transition flex flex-col">
                    <div class="h-44 overflow-hidden relative">
                        <img src="https://lh3.googleusercontent.com/d/17I0CSHLS9vjV-PtPdYwwU96vkDGzLJky=w600" 
                             onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=17I0CSHLS9vjV-PtPdYwwU96vkDGzLJky&sz=w600';"
                             alt="Cách nhận biết gỗ Hương Đá và gỗ Gõ Đỏ" class="w-full h-full object-cover hover:scale-105 transition duration-500">
                    </div>
                    <div class="p-4 flex-1 flex flex-col justify-between">
                        <div>
                            <span class="text-[11px] font-semibold text-wood-600 uppercase">Kiến thức gỗ quý</span>
                            <h3 class="font-bold text-sm text-stone-900 mt-1 leading-snug hover:text-wood-700">
                                Cách phân biệt gỗ Hương Đá và gỗ Gõ Đỏ chuẩn xác nhất khi mua bàn ghế phòng khách
                            </h3>
                            <p class="text-xs text-stone-600 mt-2 leading-relaxed">
                                Gỗ Hương Đá và Gõ Đỏ đều thuộc nhóm gỗ quý nhóm 1 với vân gỗ sắc nét, độ cứng cao, chống mối mọt tuyệt đối và lên màu cực sang trọng...
                            </p>
                        </div>
                        <a href="#bang-bao-gia" class="mt-3 inline-flex items-center text-xs font-bold text-wood-700 hover:text-wood-900">
                            Tư vấn chi tiết <i class="fa-solid fa-angle-right ml-1"></i>
                        </a>
                    </div>
                </article>

                <!-- Bài viết 2 -->
                <article class="bg-white rounded-xl border border-stone-200 overflow-hidden shadow-sm hover:shadow-md transition flex flex-col">
                    <div class="h-44 overflow-hidden relative">
                        <img src="https://lh3.googleusercontent.com/d/1kEWYtsSAdsLcPGfML3QcyiLzEoCwGvLJ=w600" 
                             onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1kEWYtsSAdsLcPGfML3QcyiLzEoCwGvLJ&sz=w600';"
                             alt="Kinh nghiệm chọn bàn ghế Hoàng Gia và Rồng Đỉnh" class="w-full h-full object-cover hover:scale-105 transition duration-500">
                    </div>
                    <div class="p-4 flex-1 flex flex-col justify-between">
                        <div>
                            <span class="text-[11px] font-semibold text-wood-600 uppercase">Tư vấn phòng khách</span>
                            <h3 class="font-bold text-sm text-stone-900 mt-1 leading-snug hover:text-wood-700">
                                Kinh nghiệm chọn bộ bàn ghế Hoàng Gia & Rồng Đỉnh hợp diện tích biệt thự, nhà phố
                            </h3>
                            <p class="text-xs text-stone-600 mt-2 leading-relaxed">
                                Hướng dẫn cách đo diện tích phòng khách để chọn bộ bàn ghế 6 món, 10 món hoặc 12 món vừa bề thế vừa hài hòa phong thủy gia chủ...
                            </p>
                        </div>
                        <a href="#bang-bao-gia" class="mt-3 inline-flex items-center text-xs font-bold text-wood-700 hover:text-wood-900">
                            Tư vấn chi tiết <i class="fa-solid fa-angle-right ml-1"></i>
                        </a>
                    </div>
                </article>

                <!-- Bài viết 3 -->
                <article class="bg-white rounded-xl border border-stone-200 overflow-hidden shadow-sm hover:shadow-md transition flex flex-col">
                    <div class="h-44 overflow-hidden relative">
                        <img src="https://lh3.googleusercontent.com/d/1qp0LECZZldxrDlEizT-PnmEoe-pIsKql=w600" 
                             onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1qp0LECZZldxrDlEizT-PnmEoe-pIsKql&sz=w600';"
                             alt="Bàn ăn nguyên khối gỗ tự nhiên" class="w-full h-full object-cover hover:scale-105 transition duration-500">
                    </div>
                    <div class="p-4 flex-1 flex flex-col justify-between">
                        <div>
                            <span class="text-[11px] font-semibold text-wood-600 uppercase">Nội thất phòng bếp</span>
                            <h3 class="font-bold text-sm text-stone-900 mt-1 leading-snug hover:text-wood-700">
                                Xu hướng chọn bàn ăn gỗ tự nhiên & tủ rượu sang trọng cho không gian bếp ấm cúng
                            </h3>
                            <p class="text-xs text-stone-600 mt-2 leading-relaxed">
                                Bộ bàn ghế ăn gỗ tự nhiên kết hợp ghế chạm hoa hồng tinh xảo không chỉ bền bỉ hàng chục năm mà còn nâng tầm không gian phòng bếp...
                            </p>
                        </div>
                        <a href="#bang-bao-gia" class="mt-3 inline-flex items-center text-xs font-bold text-wood-700 hover:text-wood-900">
                            Tư vấn chi tiết <i class="fa-solid fa-angle-right ml-1"></i>
                        </a>
                    </div>
                </article>

                <!-- Bài viết 4 -->
                <article class="bg-white rounded-xl border border-stone-200 overflow-hidden shadow-sm hover:shadow-md transition flex flex-col">
                    <div class="h-44 overflow-hidden relative">
                        <img src="https://lh3.googleusercontent.com/d/1rJLV7jlxhSbUksXvNV3IJv9e1zziYoVw=w600" 
                             onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1rJLV7jlxhSbUksXvNV3IJv9e1zziYoVw&sz=w600';"
                             alt="Kích thước Lỗ Ban bàn thờ gia tiên" class="w-full h-full object-cover hover:scale-105 transition duration-500">
                    </div>
                    <div class="p-4 flex-1 flex flex-col justify-between">
                        <div>
                            <span class="text-[11px] font-semibold text-wood-600 uppercase">Phong thủy phòng thờ</span>
                            <h3 class="font-bold text-sm text-stone-900 mt-1 leading-snug hover:text-wood-700">
                                Chuẩn kích thước thước Lỗ Ban 38.8cm khi đóng Sập thờ, Án gian & Lục bình gỗ
                            </h3>
                            <p class="text-xs text-stone-600 mt-2 leading-relaxed">
                                Tìm hiểu các cung số đẹp Tài Vượng, Phú Quý, Tiến Bảo khi chế tác nội thất phòng thờ gia tiên tại Xưởng Đồ Gỗ Mỹ Nghệ Bảo Lâm...
                            </p>
                        </div>
                        <a href="#bang-bao-gia" class="mt-3 inline-flex items-center text-xs font-bold text-wood-700 hover:text-wood-900">
                            Tư vấn chi tiết <i class="fa-solid fa-angle-right ml-1"></i>
                        </a>
                    </div>
                </article>
            </div>
        </div>
    </section>

    <!-- ==========================================
         DANH MỤC CÁC ĐỐI TÁC ĐỒNG HÀNH
         ========================================== -->
    <section id="sec-doi-tac" class="py-4">
        <div class="flatsome-container">
            <div class="flatsome-section-header">
                <div class="flatsome-section-title">
                    <i class="fa-solid fa-handshake"></i>
                    <span>DANH MỤC CÁC ĐỐI TÁC CHIẾN LƯỢC</span>
                </div>
                <div class="px-3 py-1.5 text-xs font-semibold text-stone-600">
                    Đối tác cung ứng, thiết kế thi công & thanh toán liên kết
                </div>
            </div>

            <div class="grid grid-cols-2 sm:grid-cols-3 lg:grid-cols-6 gap-3">
                <div class="bg-white p-3.5 rounded-xl border border-stone-200 text-center shadow-sm hover:border-wood-600 transition">
                    <div class="w-10 h-10 mx-auto rounded-full bg-wood-50 text-wood-700 flex items-center justify-center text-lg">
                        <i class="fa-solid fa-tree"></i>
                    </div>
                    <h3 class="font-bold text-xs text-wood-900 mt-2">Hiệp Hội Gỗ & Lâm Sản</h3>
                    <p class="text-[11px] text-stone-500 mt-0.5">Nguồn gỗ nhập khẩu chính ngạch</p>
                </div>

                <div class="bg-white p-3.5 rounded-xl border border-stone-200 text-center shadow-sm hover:border-wood-600 transition">
                    <div class="w-10 h-10 mx-auto rounded-full bg-wood-50 text-wood-700 flex items-center justify-center text-lg">
                        <i class="fa-solid fa-building-columns"></i>
                    </div>
                    <h3 class="font-bold text-xs text-wood-900 mt-2">Vietcombank & BIDV</h3>
                    <p class="text-[11px] text-stone-500 mt-0.5">Đối tác thanh toán & trả góp</p>
                </div>

                <div class="bg-white p-3.5 rounded-xl border border-stone-200 text-center shadow-sm hover:border-wood-600 transition">
                    <div class="w-10 h-10 mx-auto rounded-full bg-wood-50 text-wood-700 flex items-center justify-center text-lg">
                        <i class="fa-solid fa-compass-drafting"></i>
                    </div>
                    <h3 class="font-bold text-xs text-wood-900 mt-2">Kiến Trúc Biệt Thự Miền Trung</h3>
                    <p class="text-[11px] text-stone-500 mt-0.5">Đối tác thiết kế nội thất gỗ</p>
                </div>

                <div class="bg-white p-3.5 rounded-xl border border-stone-200 text-center shadow-sm hover:border-wood-600 transition">
                    <div class="w-10 h-10 mx-auto rounded-full bg-wood-50 text-wood-700 flex items-center justify-center text-lg">
                        <i class="fa-solid fa-fill-drip"></i>
                    </div>
                    <h3 class="font-bold text-xs text-wood-900 mt-2">Sơn PU Oseven Cao Cấp</h3>
                    <p class="text-[11px] text-stone-500 mt-0.5">Bảo vệ bề mặt gỗ bền màu</p>
                </div>

                <div class="bg-white p-3.5 rounded-xl border border-stone-200 text-center shadow-sm hover:border-wood-600 transition">
                    <div class="w-10 h-10 mx-auto rounded-full bg-wood-50 text-wood-700 flex items-center justify-center text-lg">
                        <i class="fa-solid fa-hotel"></i>
                    </div>
                    <h3 class="font-bold text-xs text-wood-900 mt-2">Resort & Khách Sạn Đà Nẵng</h3>
                    <p class="text-[11px] text-stone-500 mt-0.5">Đối tác cung cấp nội thất dự án</p>
                </div>

                <div class="bg-white p-3.5 rounded-xl border border-stone-200 text-center shadow-sm hover:border-wood-600 transition">
                    <div class="w-10 h-10 mx-auto rounded-full bg-wood-50 text-wood-700 flex items-center justify-center text-lg">
                        <i class="fa-solid fa-truck-moving"></i>
                    </div>
                    <h3 class="font-bold text-xs text-wood-900 mt-2">Vận Tải Bắc Trung Nam</h3>
                    <p class="text-[11px] text-stone-500 mt-0.5">Giao lắp đặt an toàn tận nhà</p>
                </div>
            </div>
        </div>
    </section>

    <!-- ==========================================
         ĐƯA FANPAGE FACEBOOK & ẢNH BẢN ĐỒ GOOGLE MAP RA NGOÀI TRANG CHỦ
         - Địa chỉ: 94 Nam Cao, Phường Hòa Khánh, TP Đà Nẵng
         - Link Map: https://maps.app.goo.gl/7N4b845T2fxhusUz6
         - Link Fanpage: https://www.facebook.com/profile.php?id=100062969002550
         ========================================== -->
    <section id="ban-do-trang-chu" class="py-5">
        <div class="flatsome-container">
            <div class="flatsome-section-header">
                <div class="flatsome-section-title">
                    <i class="fa-solid fa-map-location-dot"></i>
                    <span>FANPAGE CHÍNH THỨC & BẢN ĐỒ GOOGLE MAPS TRANG CHỦ</span>
                </div>
                <div class="px-3 py-1.5 text-xs font-semibold text-wood-800">
                    94 Nam Cao, Phường Hòa Khánh, TP Đà Nẵng
                </div>
            </div>

            <div class="grid grid-cols-1 lg:grid-cols-12 gap-5">
                
                <!-- Cột 1: Đưa Fanpage Đồ Gỗ Mỹ Nghệ Bảo Lâm ra ngoài trang chủ -->
                <div class="lg:col-span-5 bg-white rounded-xl border border-stone-200 p-4 shadow-sm flex flex-col justify-between">
                    <div>
                        <div class="flex items-center justify-between mb-3">
                            <h3 class="font-bold text-sm sm:text-base text-wood-900 flex items-center gap-2">
                                <i class="fa-brands fa-facebook text-blue-600 text-lg"></i>
                                Fanpage Đồ Gỗ Mỹ Nghệ Bảo Lâm
                            </h3>
                            <a href="https://www.facebook.com/profile.php?id=100062969002550" target="_blank" rel="noopener noreferrer" class="text-xs font-semibold text-blue-600 hover:underline">
                                Mở Facebook <i class="fa-solid fa-arrow-up-right-from-square ml-0.5"></i>
                            </a>
                        </div>

                        <!-- Khung giao diện Fanpage trực quan trên trang chủ -->
                        <div class="rounded-xl overflow-hidden border border-stone-200 bg-stone-50">
                            <div class="relative h-40 bg-wood-900">
                                <img src="https://lh3.googleusercontent.com/d/1eLxbKDSKrHUYROvydx0ZhQpYT16dL9Hp=w800" 
                                     onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1eLxbKDSKrHUYROvydx0ZhQpYT16dL9Hp&sz=w800';"
                                     alt="Ảnh bìa Fanpage Đồ Gỗ Mỹ Nghệ Bảo Lâm" class="w-full h-full object-cover opacity-80">
                                <div class="absolute inset-0 bg-gradient-to-t from-black/80 via-black/30 to-transparent"></div>
                                <div class="absolute bottom-3 left-3 right-3 flex items-end gap-3">
                                    <img src="https://lh3.googleusercontent.com/d/1egxad2JO9d8csN2hRnKiu-wtocfV1Paj=w200" 
                                         onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1egxad2JO9d8csN2hRnKiu-wtocfV1Paj&sz=w200';"
                                         alt="Logo Bảo Lâm" class="w-14 h-14 rounded-lg border-2 border-white bg-white p-0.5 object-contain shadow-md flex-shrink-0">
                                    <div class="text-white min-w-0">
                                        <a href="https://www.facebook.com/profile.php?id=100062969002550" target="_blank" rel="noopener noreferrer" class="font-bold text-sm sm:text-base hover:underline block truncate">
                                            Đồ Gỗ Mỹ Nghệ Bảo Lâm <i class="fa-solid fa-circle-check text-blue-400 text-xs"></i>
                                        </a>
                                        <p class="text-[11px] text-stone-200">Xưởng sản xuất nội thất gỗ tự nhiên • Đà Nẵng</p>
                                    </div>
                                </div>
                            </div>

                            <div class="p-3.5 space-y-2.5 text-xs text-stone-700">
                                <p class="leading-relaxed">
                                    Cập nhật hình ảnh bàn giao thực tế hàng ngày tại Fanpage chính thức của <strong>Đồ Gỗ Mỹ Nghệ Bảo Lâm</strong>.
                                </p>
                                <div class="flex flex-wrap gap-2 pt-1">
                                    <a href="https://www.facebook.com/profile.php?id=100062969002550" target="_blank" rel="noopener noreferrer"
                                       class="flex-1 py-2 px-3 rounded-lg bg-blue-600 hover:bg-blue-700 text-white font-bold text-center transition">
                                        <i class="fa-brands fa-facebook-f mr-1"></i> Theo Dõi Fanpage
                                    </a>
                                    <a href="https://www.facebook.com/profile.php?id=100062969002550" target="_blank" rel="noopener noreferrer"
                                       class="flex-1 py-2 px-3 rounded-lg bg-stone-200 hover:bg-stone-300 text-stone-800 font-bold text-center transition">
                                        <i class="fa-brands fa-facebook-messenger mr-1 text-blue-600"></i> Nhắn Tin Tư Vấn
                                    </a>
                                </div>
                            </div>
                        </div>
                    </div>

                    <div class="mt-3 p-3 rounded-lg bg-wood-50 border border-wood-200 text-xs text-stone-700">
                        <div class="font-bold text-wood-800"><i class="fa-solid fa-clock mr-1"></i> Giờ mở cửa Showroom & Xưởng:</div>
                        <div class="mt-0.5">7h30 - 21h00 (Tất cả các ngày trong tuần, kể cả Thứ 7 & Chủ Nhật)</div>
                    </div>
                </div>

                <!-- Cột 2: Đưa Ảnh Google Map & Bản đồ trực tiếp ra ngoài trang chủ -->
                <div class="lg:col-span-7 bg-white rounded-xl border border-stone-200 p-4 shadow-sm flex flex-col justify-between">
                    <div>
                        <div class="flex flex-wrap items-center justify-between gap-2 mb-3">
                            <div>
                                <h3 class="font-bold text-sm sm:text-base text-wood-900 flex items-center gap-2">
                                    <i class="fa-solid fa-location-dot text-red-600 text-lg"></i>
                                    Bản Đồ Google Maps: 94 Nam Cao, Phường Hòa Khánh, TP Đà Nẵng
                                </h3>
                            </div>
                            <a href="https://maps.app.goo.gl/7N4b845T2fxhusUz6" target="_blank" rel="noopener noreferrer"
                               class="px-3 py-1.5 rounded-lg bg-red-600 hover:bg-red-700 text-white text-xs font-bold flex items-center gap-1.5 shadow-sm transition">
                                <i class="fa-solid fa-diamond-turn-right"></i> Mở Google Maps Chỉ Đường
                            </a>
                        </div>

                        <!-- Khung Bản đồ Google Map thực tế kết hợp thẻ vị trí trực quan -->
                        <div class="relative rounded-xl overflow-hidden border border-stone-300 h-72 sm:h-80 bg-stone-100">
                            <iframe 
                                title="Bản đồ Đồ Gỗ Mỹ Nghệ Bảo Lâm 94 Nam Cao Đà Nẵng"
                                src="https://maps.google.com/maps?q=94%20Nam%20Cao,%20H%C3%B2a%20Kh%C3%A1nh,%20Li%C3%AAn%20Chi%E1%BB%83u,%20%C4%90%C3%A0%20N%E1%BA%B5ng&t=&z=16&ie=UTF8&iwloc=&output=embed"
                                class="w-full h-full border-0"
                                loading="lazy"
                                referrerpolicy="no-referrer-when-downgrade">
                            </iframe>

                            <!-- Thẻ nổi ghim địa chỉ & mở trực tiếp link https://maps.app.goo.gl/7N4b845T2fxhusUz6 -->
                            <div class="absolute bottom-3 left-3 right-3 sm:right-auto bg-white/95 backdrop-blur-sm p-3 rounded-lg shadow-lg border border-stone-200 max-w-md">
                                <div class="flex items-start gap-2.5">
                                    <div class="w-9 h-9 rounded-lg bg-red-600 text-white flex items-center justify-center flex-shrink-0 mt-0.5">
                                        <i class="fa-solid fa-map-pin"></i>
                                    </div>
                                    <div class="text-xs">
                                        <div class="font-bold text-wood-900">ĐỒ GỖ MỸ NGHỆ BẢO LÂM (baolam.net)</div>
                                        <div class="text-stone-600 mt-0.5">94 Nam Cao, Phường Hòa Khánh, TP Đà Nẵng</div>
                                        <div class="mt-1.5 flex items-center gap-3">
                                            <a href="https://maps.app.goo.gl/7N4b845T2fxhusUz6" target="_blank" rel="noopener noreferrer" class="font-bold text-blue-600 hover:underline">
                                                Xem trên Google Maps <i class="fa-solid fa-arrow-up-right-from-square text-[10px]"></i>
                                            </a>
                                            <span class="text-stone-300">|</span>
                                            <a href="tel:0905265586" class="font-bold text-red-600 hover:underline">
                                                SĐT: 0905.265.586
                                            </a>
                                        </div>
                                    </div>
                                </div>
                            </div>
                        </div>
                    </div>

                    <div class="mt-3 flex flex-wrap items-center justify-between gap-2 text-xs text-stone-600 pt-2 border-t border-stone-100">
                        <span><i class="fa-solid fa-square-parking text-wood-700 mr-1"></i> Có chỗ đậu xe ô tô rộng rãi tại Showroom 94 Nam Cao</span>
                        <a href="https://maps.app.goo.gl/7N4b845T2fxhusUz6" target="_blank" rel="noopener noreferrer" class="font-semibold text-wood-800 hover:underline">
                            Link bản đồ: https://maps.app.goo.gl/7N4b845T2fxhusUz6
                        </a>
                    </div>
                </div>

            </div>
        </div>
    </section>

    <!-- ==========================================
         FOOTER CHUẨN FLATSOME & DOGOPHAMGIA.COM
         ========================================== -->
    <footer class="bg-wood-900 text-amber-100/90 pt-10 pb-20 lg:pb-8 border-t-4 border-gold-500 mt-6">
        <div class="flatsome-container">
            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-4 gap-7 pb-8 border-b border-wood-700 text-xs sm:text-sm">
                
                <!-- Cột 1: Thông tin công ty -->
                <div>
                    <div class="flex items-center gap-2.5 mb-3">
                        <img src="https://lh3.googleusercontent.com/d/1egxad2JO9d8csN2hRnKiu-wtocfV1Paj=w200" 
                             onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1egxad2JO9d8csN2hRnKiu-wtocfV1Paj&sz=w200';"
                             alt="Logo Đồ Gỗ Bảo Lâm" class="w-11 h-11 rounded-lg bg-white p-0.5 object-contain">
                        <div>
                            <h3 class="font-serif font-bold text-base text-gold-400">ĐỒ GỖ MỸ NGHỆ BẢO LÂM</h3>
                            <p class="text-[11px] text-amber-200">Website: baolam.net</p>
                        </div>
                    </div>
                    <p class="text-xs leading-relaxed text-amber-100/80 mb-3">
                        CÔNG TY CỔ PHẦN BẢO LÂM - Đơn vị uy tín hàng đầu chuyên sản xuất và cung cấp đồ gỗ mỹ nghệ nội thất phòng khách, phòng bếp, phòng ngủ, phòng thờ cao cấp tại TP Đà Nẵng và toàn quốc.
                    </p>
                    <ul class="space-y-1.5 text-xs">
                        <li><i class="fa-solid fa-location-dot text-gold-400 w-4"></i> <strong>Địa chỉ:</strong> 94 Nam Cao, Phường Hòa Khánh, TP Đà Nẵng</li>
                        <li><i class="fa-solid fa-phone text-gold-400 w-4"></i> <strong>Điện thoại / Zalo:</strong> <a href="tel:0905265586" class="text-gold-400 font-bold">0905.265.586</a></li>
                        <li><i class="fa-solid fa-globe text-gold-400 w-4"></i> <strong>Website:</strong> <a href="https://baolam.net" class="hover:underline">baolam.net</a></li>
                        <li><i class="fa-brands fa-facebook text-gold-400 w-4"></i> <strong>Fanpage:</strong> <a href="https://www.facebook.com/profile.php?id=100062969002550" target="_blank" rel="noopener noreferrer" class="hover:underline">Đồ Gỗ Mỹ Nghệ Bảo Lâm</a></li>
                    </ul>
                </div>

                <!-- Cột 2: Danh mục sản phẩm (Giống web mẫu dogophamgia.com) -->
                <div>
                    <h4 class="font-bold text-sm text-gold-400 uppercase mb-3 pb-1.5 border-b border-wood-700">
                        Danh Mục Sản Phẩm
                    </h4>
                    <ul class="grid grid-cols-2 gap-2 text-xs">
                        <li><a href="#sec-phong-khach" onclick="filterCategory('phong-khach')" class="hover:text-gold-400">• Bàn ghế phòng khách</a></li>
                        <li><a href="#sec-phong-khach" onclick="filterCategory('hoang-gia')" class="hover:text-gold-400">• Mẫu Hoàng Gia</a></li>
                        <li><a href="#sec-phong-khach" onclick="filterCategory('rong-dinh')" class="hover:text-gold-400">• Mẫu Rồng Đỉnh</a></li>
                        <li><a href="#sec-phong-khach" onclick="filterCategory('tan-thuy-hoang')" class="hover:text-gold-400">• Mẫu Tần Thủy Hoàng</a></li>
                        <li><a href="#sec-phong-khach" onclick="filterCategory('au-a')" class="hover:text-gold-400">• Mẫu Âu Á</a></li>
                        <li><a href="#sec-phong-khach" onclick="filterCategory('minh-quoc')" class="hover:text-gold-400">• Mẫu Minh Quốc</a></li>
                        <li><a href="#sec-phong-khach" onclick="filterCategory('ke-tivi')" class="hover:text-gold-400">• Kệ Tivi gỗ</a></li>
                        <li><a href="#sec-phong-khach" onclick="filterCategory('phong-khach')" class="hover:text-gold-400">• Sofa gỗ tự nhiên</a></li>
                        <li><a href="#sec-phong-bep" onclick="filterCategory('phong-bep')" class="hover:text-gold-400">• Bàn ghế ăn</a></li>
                        <li><a href="#sec-phong-bep" onclick="filterCategory('phong-bep')" class="hover:text-gold-400">• Tủ rượu gỗ</a></li>
                        <li><a href="#sec-phong-ngu" onclick="filterCategory('phong-ngu')" class="hover:text-gold-400">• Giường ngủ - Tủ áo</a></li>
                        <li><a href="#sec-phong-tho" onclick="filterCategory('phong-tho')" class="hover:text-gold-400">• Đồ thờ - Lục bình</a></li>
                    </ul>
                </div>

                <!-- Cột 3: Chính sách khách hàng -->
                <div>
                    <h4 class="font-bold text-sm text-gold-400 uppercase mb-3 pb-1.5 border-b border-wood-700">
                        Chính Sách & Hỗ Trợ
                    </h4>
                    <ul class="space-y-2 text-xs">
                        <li><a href="#bang-bao-gia" class="hover:text-gold-400"><i class="fa-solid fa-angle-right mr-1.5 text-gold-400"></i>Giới thiệu Xưởng Đồ Gỗ Bảo Lâm</a></li>
                        <li><a href="#bang-bao-gia" class="hover:text-gold-400"><i class="fa-solid fa-angle-right mr-1.5 text-gold-400"></i>Chính sách đặt hàng theo yêu cầu</a></li>
                        <li><a href="#bang-bao-gia" class="hover:text-gold-400"><i class="fa-solid fa-angle-right mr-1.5 text-gold-400"></i>Chính sách vận chuyển & lắp đặt tận nhà</a></li>
                        <li><a href="#bang-bao-gia" class="hover:text-gold-400"><i class="fa-solid fa-angle-right mr-1.5 text-gold-400"></i>Chính sách bảo hành & bảo trì dài hạn</a></li>
                        <li><a href="#bang-bao-gia" class="hover:text-gold-400"><i class="fa-solid fa-angle-right mr-1.5 text-gold-400"></i>Quy trình kiểm tra mộc tại xưởng</a></li>
                        <li><a href="https://maps.app.goo.gl/7N4b845T2fxhusUz6" target="_blank" rel="noopener noreferrer" class="hover:text-gold-400"><i class="fa-solid fa-angle-right mr-1.5 text-gold-400"></i>Chỉ đường tới 94 Nam Cao, Đà Nẵng</a></li>
                    </ul>
                </div>

                <!-- Cột 4: Liên hệ nhanh -->
                <div>
                    <h4 class="font-bold text-sm text-gold-400 uppercase mb-3 pb-1.5 border-b border-wood-700">
                        Liên Hệ Đặt Hàng
                    </h4>
                    <div class="bg-wood-800 p-3.5 rounded-xl border border-wood-700 space-y-2 text-xs">
                        <div class="text-amber-200 font-semibold">Hotline / Zalo Tư Vấn 24/7:</div>
                        <a href="tel:0905265586" class="block text-xl font-extrabold text-gold-400 hover:underline">
                            0905.265.586
                        </a>
                        <p class="text-[11px] text-amber-100/80">
                            Quý khách kết bạn Zalo <strong>0905.265.586</strong> để nhận video quay thực tế từng sản phẩm tại xưởng Bảo Lâm.
                        </p>
                        <div class="pt-2 flex gap-2">
                            <a href="https://zalo.me/0905265586" target="_blank" rel="noopener noreferrer" class="flex-1 py-2 rounded bg-blue-600 hover:bg-blue-500 text-white font-bold text-center">
                                Chat Zalo
                            </a>
                            <a href="https://www.facebook.com/profile.php?id=100062969002550" target="_blank" rel="noopener noreferrer" class="flex-1 py-2 rounded bg-indigo-600 hover:bg-indigo-500 text-white font-bold text-center">
                                Fanpage FB
                            </a>
                        </div>
                    </div>
                </div>
            </div>

            <div class="pt-5 flex flex-wrap items-center justify-between gap-2 text-xs text-amber-200/70">
                <div>Copyright 2026 © <strong>baolam.net</strong> - Đồ Gỗ Mỹ Nghệ Bảo Lâm (94 Nam Cao, P. Hòa Khánh, TP Đà Nẵng)</div>
                <div>Giao diện chuẩn UX Builder Flatsome • Tối ưu máy tính (1500px) & Điện thoại</div>
            </div>
        </div>
    </footer>

    <!-- ==========================================
         CÁC NÚT LIÊN HỆ NỔI BẬT (ZALO, FACEBOOK, HOTLINE)
         - Thiết kế gọn đẹp, không gây tràn viền
         ========================================== -->
    <div class="fixed bottom-4 left-3 z-40 flex flex-col gap-2.5">
        <!-- Nút Facebook Fanpage nổi bật -->
        <a href="https://www.facebook.com/profile.php?id=100062969002550" target="_blank" rel="noopener noreferrer"
           class="flex items-center gap-2 bg-[#1877F2] hover:bg-blue-700 text-white px-3 py-2 rounded-full shadow-lg border border-white/30 transition transform hover:scale-105">
            <span class="w-7 h-7 rounded-full bg-white text-[#1877F2] flex items-center justify-center font-bold text-sm flex-shrink-0">
                <i class="fa-brands fa-facebook-f"></i>
            </span>
            <span class="text-xs font-bold pr-1 whitespace-nowrap">Fanpage Bảo Lâm</span>
        </a>

        <!-- Nút Chat Zalo nổi bật -->
        <a href="https://zalo.me/0905265586" target="_blank" rel="noopener noreferrer"
           class="flex items-center gap-2 bg-[#0068FF] hover:bg-blue-600 text-white px-3 py-2 rounded-full shadow-lg border border-white/30 transition transform hover:scale-105">
            <span class="w-7 h-7 rounded-full bg-white text-[#0068FF] flex items-center justify-center font-extrabold text-[10px] flex-shrink-0">
                Zalo
            </span>
            <span class="text-xs font-bold pr-1 whitespace-nowrap">Chat Zalo</span>
        </a>

        <!-- Nút Hotline nổi bật -->
        <a href="tel:0905265586"
           class="floating-btn-pulse flex items-center gap-2 bg-red-700 hover:bg-red-800 text-white px-3 py-2 rounded-full shadow-xl border border-gold-400 transition transform hover:scale-105">
            <span class="w-7 h-7 rounded-full bg-gold-400 text-red-900 flex items-center justify-center font-bold text-xs flex-shrink-0">
                <i class="fa-solid fa-phone-volume"></i>
            </span>
            <span class="text-xs font-extrabold pr-1 whitespace-nowrap">0905.265.586</span>
        </a>
    </div>

    <!-- ==========================================
         MODAL XEM CHI TIẾT SẢN PHẨM & ĐẶT HÀNG NHANH
         ========================================== -->
    <div id="productDetailModal" class="fixed inset-0 bg-black/70 z-50 hidden items-center justify-center p-3">
        <div class="bg-white rounded-xl max-w-3xl w-full overflow-hidden shadow-2xl border border-stone-200 max-h-[90vh] flex flex-col">
            <div class="px-4 py-3 bg-wood-900 text-white flex items-center justify-between">
                <h3 id="modalProductTitle" class="font-bold text-sm sm:text-base text-gold-400 pr-4">Chi tiết sản phẩm</h3>
                <button onclick="closeProductModal()" class="w-8 h-8 rounded-full bg-wood-800 text-white flex items-center justify-center hover:bg-red-600 transition flex-shrink-0">
                    <i class="fa-solid fa-xmark"></i>
                </button>
            </div>
            <div class="p-4 sm:p-6 overflow-y-auto grid grid-cols-1 md:grid-cols-2 gap-5">
                <div class="relative rounded-xl overflow-hidden border border-stone-200 bg-stone-100 aspect-square">
                    <span id="modalProductDiscount" class="flatsome-sale-badge">-10%</span>
                    <img id="modalProductImg" src="" alt="Ảnh thực tế sản phẩm" class="w-full h-full object-cover">
                </div>
                <div class="flex flex-col justify-between text-xs sm:text-sm">
                    <div>
                        <span id="modalProductCat" class="inline-block px-2.5 py-0.5 rounded bg-wood-100 text-wood-800 font-semibold text-xs">Danh mục</span>
                        <h4 id="modalProductName" class="font-bold text-base sm:text-lg text-stone-900 mt-2 leading-snug"></h4>
                        <div class="mt-3 flex items-baseline gap-2.5">
                            <span id="modalProductSalePrice" class="text-lg sm:text-xl font-extrabold text-red-700"></span>
                            <span id="modalProductOldPrice" class="text-xs sm:text-sm text-stone-400 line-through"></span>
                        </div>
                        <div class="mt-3 p-3 rounded-lg bg-stone-50 border border-stone-200 space-y-1.5 text-xs text-stone-700">
                            <div><i class="fa-solid fa-check text-wood-700 mr-1.5"></i> <strong>Đơn vị sản xuất:</strong> Xưởng Đồ Gỗ Mỹ Nghệ Bảo Lâm (baolam.net)</div>
                            <div><i class="fa-solid fa-check text-wood-700 mr-1.5"></i> <strong>Chất liệu:</strong> Gỗ tự nhiên tuyển chọn 100%, sấy khô chống cong vênh</div>
                            <div><i class="fa-solid fa-check text-wood-700 mr-1.5"></i> <strong>Showroom:</strong> 94 Nam Cao, Phường Hòa Khánh, TP Đà Nẵng</div>
                            <div><i class="fa-solid fa-check text-wood-700 mr-1.5"></i> <strong>Bảo hành:</strong> Bảo hành kỹ thuật dài hạn, giao lắp đặt tận nơi</div>
                        </div>
                    </div>
                    <div class="mt-5 grid grid-cols-2 gap-2.5">
                        <a href="tel:0905265586" class="py-2.5 px-3 rounded-lg bg-red-700 hover:bg-red-800 text-white font-bold text-xs text-center flex items-center justify-center gap-1.5">
                            <i class="fa-solid fa-phone"></i> Gọi 0905.265.586
                        </a>
                        <button onclick="selectProductForQuote()" class="py-2.5 px-3 rounded-lg bg-wood-800 hover:bg-wood-700 text-gold-400 font-bold text-xs text-center flex items-center justify-center gap-1.5">
                            <i class="fa-solid fa-file-signature"></i> Đặt Báo Giá Mẫu Này
                        </button>
                    </div>
                </div>
            </div>
        </div>
    </div>

    <!-- ==========================================
         JAVASCRIPT QUẢN LÝ 13 SẢN PHẨM THỰC TẾ, SLIDER BANNER, BỘ LỌC & BÁO GIÁ
         ========================================== -->
    <script>
        /* Danh sách toàn bộ 13 ảnh sản phẩm thực tế từ Google Drive của Đồ Gỗ Mỹ Nghệ Bảo Lâm
           được phân bổ chuẩn xác vào các danh mục giống dogophamgia.com */
        const BAOLAM_PRODUCTS = [
            // --- NỘI THẤT PHÒNG KHÁCH (7 Sản phẩm thực tế) ---
            {
                id: 1,
                driveId: '17I0CSHLS9vjV-PtPdYwwU96vkDGzLJky',
                name: 'Bộ Bàn Ghế Hoàng Gia Nguyên Khối Gỗ Hương Đá Chạm Thủ Công',
                section: 'phong-khach',
                subCat: 'hoang-gia',
                catLabel: 'Bàn ghế Hoàng Gia',
                oldPrice: '98,000,000 ₫',
                salePrice: '86,000,000 ₫',
                discount: '-12%'
            },
            {
                id: 2,
                driveId: '1kEWYtsSAdsLcPGfML3QcyiLzEoCwGvLJ',
                name: 'Bộ Bàn Ghế Rồng Đỉnh Nghê Bảo Đỉnh 12 Món Gỗ Quý Đục Tay',
                section: 'phong-khach',
                subCat: 'rong-dinh',
                catLabel: 'Bàn ghế Rồng Đỉnh',
                oldPrice: '145,000,000 ₫',
                salePrice: '130,000,000 ₫',
                discount: '-10%'
            },
            {
                id: 3,
                driveId: '1eLxbKDSKrHUYROvydx0ZhQpYT16dL9Hp',
                name: 'Bộ Bàn Ghế Tần Thủy Hoàng Cột 12 Chân 14 Gỗ Hương Đá Chọn Vân',
                section: 'phong-khach',
                subCat: 'tan-thuy-hoang',
                catLabel: 'Bàn ghế Tần Thủy Hoàng',
                oldPrice: '52,000,000 ₫',
                salePrice: '46,500,000 ₫',
                discount: '-11%'
            },
            {
                id: 4,
                driveId: '1i4EcMyV9pbK2Z_w0gLyAGLWDDgKyvJzj',
                name: 'Bộ Bàn Ghế Âu Á Hộp Chương Cuốn Thư Gỗ Gõ Đỏ Tự Nhiên',
                section: 'phong-khach',
                subCat: 'au-a',
                catLabel: 'Bàn ghế Âu Á',
                oldPrice: '42,000,000 ₫',
                salePrice: '37,800,000 ₫',
                discount: '-10%'
            },
            {
                id: 5,
                driveId: '1cAaStBVcvuIMuNGEwGTyO5BBzLdbhXWO',
                name: 'Bộ Bàn Ghế Minh Quốc Đào Chim Tay 12 Gỗ Hương Đá Dáng Đẹp',
                section: 'phong-khach',
                subCat: 'minh-quoc',
                catLabel: 'Bàn ghế Minh Quốc',
                oldPrice: '45,000,000 ₫',
                salePrice: '39,500,000 ₫',
                discount: '-12%'
            },
            {
                id: 6,
                driveId: '1iTUWrN3NI6RfUX7MaGEV9k_t9mG868EE',
                name: 'Kệ Tivi Nguyên Khối Lồi Giữa 2m4 Gỗ Hương Đá Chạm Hoa Lá Tây',
                section: 'phong-khach',
                subCat: 'ke-tivi',
                catLabel: 'Kệ Tivi Phòng Khách',
                oldPrice: '22,000,000 ₫',
                salePrice: '19,000,000 ₫',
                discount: '-14%'
            },
            {
                id: 7,
                driveId: '1qbaUkVv7h4uJMzhN0Ut7CLAWkGge8pzO',
                name: 'Sofa Gỗ Tự Nhiên Chân Thuyền Kèm Đệm Da Phòng Khách Hiện Đại',
                section: 'phong-khach',
                subCat: 'phong-khach',
                catLabel: 'Sofa Phòng Khách',
                oldPrice: '48,000,000 ₫',
                salePrice: '42,000,000 ₫',
                discount: '-13%'
            },

            // --- NỘI THẤT PHÒNG BẾP (2 Sản phẩm thực tế) ---
            {
                id: 8,
                driveId: '1qp0LECZZldxrDlEizT-PnmEoe-pIsKql',
                name: 'Bộ Bàn Ăn Nguyên Khối Gỗ Gõ Đỏ 8 Ghế Hoàng Gia Chạm Hoa Hồng',
                section: 'phong-bep',
                subCat: 'phong-bep',
                catLabel: 'Bàn ghế ăn',
                oldPrice: '62,000,000 ₫',
                salePrice: '55,000,000 ₫',
                discount: '-11%'
            },
            {
                id: 9,
                driveId: '1HiwnZSN-MQLSaZ22EPwDTUc7CCokytAE',
                name: 'Tủ Rượu Góc & Bàn Ghế Phòng Ăn Gỗ Tự Nhiên Cao Cấp Bảo Lâm',
                section: 'phong-bep',
                subCat: 'phong-bep',
                catLabel: 'Nội thất phòng bếp',
                oldPrice: '28,000,000 ₫',
                salePrice: '24,500,000 ₫',
                discount: '-13%'
            },

            // --- NỘI THẤT PHÒNG NGỦ (2 Sản phẩm thực tế) ---
            {
                id: 10,
                driveId: '1dA75Boh5gUl0uPANMVOIKmMOJqBYShtz',
                name: 'Giường Ngủ Hoàng Gia Chân Quỳ Gỗ Gõ Đỏ Chạm Hoa Hồng Sang Trọng',
                section: 'phong-ngu',
                subCat: 'phong-ngu',
                catLabel: 'Giường ngủ gỗ',
                oldPrice: '32,000,000 ₫',
                salePrice: '28,000,000 ₫',
                discount: '-13%'
            },
            {
                id: 11,
                driveId: '1M6D1QTHl9T1lLy-xLZlNDdRMMq4lBmw7',
                name: 'Tủ Quần Áo 4 Cánh & Bàn Trang Điểm Gỗ Hương Đá Tự Nhiên',
                section: 'phong-ngu',
                subCat: 'phong-ngu',
                catLabel: 'Tủ quần áo & Bàn phấn',
                oldPrice: '44,000,000 ₫',
                salePrice: '39,000,000 ₫',
                discount: '-11%'
            },

            // --- NỘI THẤT PHÒNG THỜ & ĐỒ THỜ (2 Sản phẩm thực tế) ---
            {
                id: 12,
                driveId: '1rJLV7jlxhSbUksXvNV3IJv9e1zziYoVw',
                name: 'Bộ Sập Thờ Tứ Linh & Án Gian Gia Tiên Gỗ Hương Đá Chuẩn Lỗ Ban',
                section: 'phong-tho',
                subCat: 'phong-tho',
                catLabel: 'Sập thờ - Án gian',
                oldPrice: '38,000,000 ₫',
                salePrice: '33,500,000 ₫',
                discount: '-12%'
            },
            {
                id: 13,
                driveId: '1kx82MVqz_XcghMo0pK67_kb5BVmt_Er1',
                name: 'Đôi Lục Bình Phong Thủy & Tủ Thờ Gỗ Cẩm Vàng Nguyên Khối',
                section: 'phong-tho',
                subCat: 'phong-tho',
                catLabel: 'Đồ thờ & Lục bình gỗ',
                oldPrice: '30,000,000 ₫',
                salePrice: '26,500,000 ₫',
                discount: '-12%'
            }
        ];

        let currentSelectedProduct = null;

        /* Hàm tạo thẻ sản phẩm chuẩn UX Builder Flatsome:
           - Chỉ để duy nhất badge % giảm giá góc trên bên trái
           - Không để bất kỳ nhãn dán phụ nào khác
           - Tên sản phẩm hiển thị đầy đủ 100%, không bị cắt chữ hay tràn ra ngoài */
        function createProductCardHTML(item) {
            const imgPrimary = `https://lh3.googleusercontent.com/d/${item.driveId}=w800`;
            const imgFallback = `https://drive.google.com/thumbnail?id=${item.driveId}&sz=w800`;
            return `
                <div class="product-small box" data-id="${item.id}">
                    <div class="box-image relative aspect-square w-full overflow-hidden bg-stone-100 cursor-pointer" onclick="openProductModal(${item.id})">
                        <span class="flatsome-sale-badge">${item.discount}</span>
                        <img src="${imgPrimary}"
                             onerror="this.onerror=null;this.src='${imgFallback}';"
                             alt="${item.name}"
                             loading="lazy"
                             class="w-full h-full object-cover hover:scale-105 transition duration-500">
                    </div>
                    <div class="box-text p-2.5 sm:p-3.5 flex-1 flex flex-col justify-between">
                        <div>
                            <div class="text-[10px] sm:text-[11px] text-stone-500 font-medium mb-1">${item.catLabel}</div>
                            <h3 class="product-title-full text-xs sm:text-sm cursor-pointer hover:text-wood-700 transition" onclick="openProductModal(${item.id})">
                                ${item.name}
                            </h3>
                        </div>
                        <div class="mt-2.5 pt-2 border-t border-stone-100">
                            <div class="flex flex-wrap items-baseline gap-x-2 gap-y-0.5">
                                <span class="text-xs sm:text-sm font-extrabold text-red-700">${item.salePrice}</span>
                                <span class="text-[10px] sm:text-xs text-stone-400 line-through">${item.oldPrice}</span>
                            </div>
                            <button onclick="openProductModal(${item.id})" class="mt-2 w-full py-1.5 px-2 rounded bg-wood-50 hover:bg-wood-800 text-wood-800 hover:text-gold-400 border border-wood-200 font-semibold text-[11px] sm:text-xs transition">
                                Xem Chi Tiết & Báo Giá
                            </button>
                        </div>
                    </div>
                </div>
            `;
        }

        /* Render toàn bộ sản phẩm vào 4 khu vực danh mục trên trang chủ */
        function renderAllProducts(filterKey = 'all', searchKeyword = '') {
            const kw = searchKeyword.trim().toLowerCase();

            const matchFilter = (item) => {
                const matchesCat = (filterKey === 'all') || (item.section === filterKey) || (item.subCat === filterKey);
                const matchesSearch = !kw || item.name.toLowerCase().includes(kw) || item.catLabel.toLowerCase().includes(kw);
                return matchesCat && matchesSearch;
            };

            const pkItems = BAOLAM_PRODUCTS.filter(p => p.section === 'phong-khach' && matchFilter(p));
            const pbItems = BAOLAM_PRODUCTS.filter(p => p.section === 'phong-bep' && matchFilter(p));
            const pnItems = BAOLAM_PRODUCTS.filter(p => p.section === 'phong-ngu' && matchFilter(p));
            const ptItems = BAOLAM_PRODUCTS.filter(p => p.section === 'phong-tho' && matchFilter(p));

            document.getElementById('grid-phong-khach').innerHTML = pkItems.map(createProductCardHTML).join('');
            document.getElementById('grid-phong-bep').innerHTML = pbItems.map(createProductCardHTML).join('');
            document.getElementById('grid-phong-ngu').innerHTML = pnItems.map(createProductCardHTML).join('');
            document.getElementById('grid-phong-tho').innerHTML = ptItems.map(createProductCardHTML).join('');

            // Ẩn/hiện từng section nếu đang lọc chuyên biệt
            document.getElementById('sec-phong-khach').style.display = pkItems.length ? 'block' : 'none';
            document.getElementById('sec-phong-bep').style.display = pbItems.length ? 'block' : 'none';
            document.getElementById('sec-phong-ngu').style.display = pnItems.length ? 'block' : 'none';
            document.getElementById('sec-phong-tho').style.display = ptItems.length ? 'block' : 'none';
        }

        function filterCategory(catKey) {
            const statusBanner = document.getElementById('filterStatusBanner');
            const statusText = document.getElementById('filterStatusText');
            if (catKey === 'all') {
                statusBanner.classList.add('hidden');
            } else {
                statusBanner.classList.remove('hidden');
                statusText.textContent = 'Đang lọc sản phẩm theo danh mục đã chọn';
            }
            renderAllProducts(catKey, '');
        }

        function filterProductsBySearch(keyword) {
            const statusBanner = document.getElementById('filterStatusBanner');
            const statusText = document.getElementById('filterStatusText');
            if (!keyword.trim()) {
                statusBanner.classList.add('hidden');
            } else {
                statusBanner.classList.remove('hidden');
                statusText.textContent = `Kết quả tìm kiếm cho từ khóa: "${keyword}"`;
            }
            renderAllProducts('all', keyword);
        }

        /* Mở Modal xem ảnh lớn & đặt báo giá */
        function openProductModal(productId) {
            const item = BAOLAM_PRODUCTS.find(p => p.id === productId);
            if (!item) return;
            currentSelectedProduct = item;

            document.getElementById('modalProductTitle').textContent = item.catLabel + ' - Đồ Gỗ Bảo Lâm';
            document.getElementById('modalProductCat').textContent = item.catLabel;
            document.getElementById('modalProductName').textContent = item.name;
            document.getElementById('modalProductSalePrice').textContent = item.salePrice;
            document.getElementById('modalProductOldPrice').textContent = item.oldPrice;
            document.getElementById('modalProductDiscount').textContent = item.discount;

            const imgEl = document.getElementById('modalProductImg');
            imgEl.src = `https://lh3.googleusercontent.com/d/${item.driveId}=w1000`;
            imgEl.onerror = function() {
                this.onerror = null;
                this.src = `https://drive.google.com/thumbnail?id=${item.driveId}&sz=w1000`;
            };

            const modal = document.getElementById('productDetailModal');
            modal.classList.remove('hidden');
            modal.classList.add('flex');
        }

        function closeProductModal() {
            const modal = document.getElementById('productDetailModal');
            modal.classList.add('hidden');
            modal.classList.remove('flex');
        }

        function selectProductForQuote() {
            closeProductModal();
            if (currentSelectedProduct) {
                const noteEl = document.getElementById('quoteNote');
                noteEl.value = `Tôi muốn nhận tư vấn & báo giá mẫu: ${currentSelectedProduct.name} (Giá niêm yết: ${currentSelectedProduct.salePrice})`;
            }
            document.getElementById('bang-bao-gia').scrollIntoView({ behavior: 'smooth' });
        }

        /* Xử lý Form Yêu cầu & Báo giá trên trang chủ */
        function handleQuoteSubmit(e) {
            e.preventDefault();
            const name = document.getElementById('quoteName').value.trim();
            const phone = document.getElementById('quotePhone').value.trim();
            const category = document.getElementById('quoteCategory').value;
            const material = document.getElementById('quoteMaterial').value;
            const box = document.getElementById('quoteSuccessBox');

            box.classList.remove('hidden');
            box.innerHTML = `
                <div class="font-bold text-emerald-800"><i class="fa-solid fa-circle-check mr-1"></i> Đã tiếp nhận yêu cầu báo giá của Quý khách ${name}!</div>
                <div class="mt-1">Số điện thoại: <strong>${phone}</strong> • Hạng mục: <strong>${category} (${material})</strong>.</div>
                <div class="mt-1">Xưởng Đồ Gỗ Mỹ Nghệ Bảo Lâm (Hotline/Zalo: <strong>0905.265.586</strong>) sẽ liên hệ tư vấn báo giá ngay cho Quý khách.</div>
            `;
            document.getElementById('quoteRequestForm').reset();
        }

        /* Menu Điện thoại */
        function toggleMobileMenu() {
            const overlay = document.getElementById('mobileMenuOverlay');
            const drawer = document.getElementById('mobileMenuDrawer');
            const isHidden = overlay.classList.contains('hidden');
            if (isHidden) {
                overlay.classList.remove('hidden');
                drawer.classList.remove('-translate-x-full');
            } else {
                overlay.classList.add('hidden');
                drawer.classList.add('-translate-x-full');
            }
        }

        /* Bộ điều khiển 2 Banner Tự Trượt (đồng bộ cả Desktop & Mobile) */
        let currentBannerIndex = 0;
        const totalBannerSlides = 2;
        let bannerInterval = null;

        function goToBannerSlide(index) {
            currentBannerIndex = (index + totalBannerSlides) % totalBannerSlides;
            for (let i = 0; i < totalBannerSlides; i++) {
                const dSlide = document.getElementById(`desktop-slide-${i}`);
                const mSlide = document.getElementById(`mobile-slide-${i}`);
                const dot = document.getElementById(`banner-dot-${i}`);

                if (i === currentBannerIndex) {
                    if (dSlide) { dSlide.classList.remove('opacity-0', 'z-0'); dSlide.classList.add('opacity-100', 'z-10'); }
                    if (mSlide) { mSlide.classList.remove('opacity-0', 'z-0'); mSlide.classList.add('opacity-100', 'z-10'); }
                    if (dot) { dot.classList.remove('w-2', 'bg-white/50'); dot.classList.add('w-6', 'bg-gold-400'); }
                } else {
                    if (dSlide) { dSlide.classList.remove('opacity-100', 'z-10'); dSlide.classList.add('opacity-0', 'z-0'); }
                    if (mSlide) { mSlide.classList.remove('opacity-100', 'z-10'); mSlide.classList.add('opacity-0', 'z-0'); }
                    if (dot) { dot.classList.remove('w-6', 'bg-gold-400'); dot.classList.add('w-2', 'bg-white/50'); }
                }
            }
        }

        function nextBannerSlide() {
            goToBannerSlide(currentBannerIndex + 1);
            resetBannerTimer();
        }

        function prevBannerSlide() {
            goToBannerSlide(currentBannerIndex - 1);
            resetBannerTimer();
        }

        function resetBannerTimer() {
            if (bannerInterval) clearInterval(bannerInterval);
            bannerInterval = setInterval(() => {
                goToBannerSlide(currentBannerIndex + 1);
            }, 5500);
        }

        window.onload = function() {
            renderAllProducts('all', '');
            resetBannerTimer();
        };
    </script>
</body>
</html>
