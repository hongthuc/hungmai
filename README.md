<html lang="vi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no">
    <title>CÔNG TY TNHH TMDV&XD HƯNG MAI - Gạch Men, TBVS, Sơn Nước & Thi Công Công Trình Đà Nẵng</title>
    <meta name="description" content="CÔNG TY TNHH TMDV&XD HƯNG MAI (hungmai.com) chuyên phân phối Gạch men, Thiết bị vệ sinh (TBVS), Sơn nước chính hãng, Vật liệu xây dựng và Thi công công trình trọn gói tại 36 Đàm Văn Lễ, Phường Hòa Khánh, TP Đà Nẵng. Hotline: 0904.524.442.">
    
    <!-- Open Graph Thumbnail là Logo công ty khi gửi link trang web -->
    <meta property="og:type" content="website">
    <meta property="og:url" content="https://hungmai.com/">
    <meta property="og:site_name" content="hungmai.com - CÔNG TY TNHH TMDV&XD HƯNG MAI">
    <meta property="og:title" content="CÔNG TY TNHH TMDV&XD HƯNG MAI | Gạch Men - TBVS - Sơn Nước - Thi Công Công Trình">
    <meta property="og:description" content="Tổng kho Gạch Men, Thiết Bị Vệ Sinh, Sơn Nước, VLXD & Thi Công Công Trình tại 36 Đàm Văn Lễ, P. Hòa Khánh, TP Đà Nẵng. ĐT: 0904.524.442">
    <meta property="og:image" content="https://drive.google.com/thumbnail?id=1IoXlEyTKTbZIOdhCTDhomRntEqO0MXe7&sz=w1200">
    <meta property="og:image:alt" content="Logo Công Ty TNHH TMDV&XD Hưng Mai - hungmai.com">

    <!-- Google Fonts: Inter & Montserrat chuẩn Flatsome -->
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700;800&display=swap" rel="stylesheet">
    
    <!-- Font Awesome Icons -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.1/css/all.min.css">
    
    <!-- Tailwind CSS -->
    <script src="https://cdn.tailwindcss.com"></script>
    <script>
        tailwind.config = {
            theme: {
                extend: {
                    fontFamily: {
                        sans: ['Inter', 'sans-serif'],
                    },
                    colors: {
                        brand: {
                            navy: '#0d3b7a',      /* Màu xanh đậm chủ đạo theo logo */
                            blue: '#1554ad',      /* Màu xanh trung tâm */
                            light: '#eef5ff',     /* Nền xanh nhạt */
                            orange: '#d9480f',    /* Màu cam đỏ điểm nhấn theo logo & Flatsome */
                            gold: '#f59e0b',
                            sale: '#d26e4b'       /* Màu badge giảm giá chuẩn Flatsome */
                        }
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
            font-family: 'Inter', sans-serif;
            background-color: #f6f7f9;
            color: #222;
            scroll-behavior: smooth;
        }

        /* Chiều ngang giao diện trên máy tính bằng 95% kích thước màn hình máy tính */
        .flatsome-container {
            width: 100%;
            padding-left: 10px;
            padding-right: 10px;
            margin-left: auto;
            margin-right: auto;
        }
        @media (min-width: 1024px) {
            .flatsome-container {
                width: 95%;
                max-width: 95%;
                padding-left: 0;
                padding-right: 0;
            }
        }

        /* Danh mục trên máy tính: viết liền trên 1 hàng chữ nhỏ gọn, không xuống dòng trong từng tên danh mục */
        .desktop-cat-link {
            white-space: nowrap;
            display: inline-flex;
            align-items: center;
            font-size: 12.5px;
            font-weight: 600;
            padding: 7px 10px;
            border-radius: 4px;
            transition: all 0.2s ease;
            line-height: 1.2;
        }
        .desktop-cat-link:hover, .desktop-cat-link.active {
            background-color: #d9480f;
            color: #ffffff;
        }

        /* Tên sản phẩm hiển thị đầy đủ, không bị cắt chữ hoặc tràn ra ngoài */
        .product-title-full {
            white-space: normal;
            word-break: break-word;
            overflow-wrap: anywhere;
            line-height: 1.38;
        }

        /* Badge % giảm giá chuẩn Flatsome góc trên bên trái */
        .flatsome-onsale {
            position: absolute;
            top: 8px;
            left: 8px;
            z-index: 10;
            background-color: #d26e4b;
            color: #ffffff;
            font-weight: 700;
            font-size: 11px;
            width: 38px;
            height: 38px;
            border-radius: 9999px;
            display: flex;
            align-items: center;
            justify-content: center;
            box-shadow: 0 2px 5px rgba(0,0,0,0.2);
            pointer-events: none;
        }

        /* Tiêu đề danh mục trang chủ nhỏ gọn kiểu Flatsome */
        .flatsome-section-title {
            display: flex;
            align-items: center;
            justify-content: space-between;
            border-bottom: 2px solid #0d3b7a;
            margin-bottom: 14px;
            background: #ffffff;
            border-radius: 6px 6px 0 0;
            padding: 8px 12px;
        }
        .flatsome-section-heading {
            font-size: 14px;
            font-weight: 800;
            text-transform: uppercase;
            color: #0d3b7a;
            letter-spacing: 0.2px;
            display: flex;
            align-items: center;
            gap: 8px;
        }
        @media (min-width: 768px) {
            .flatsome-section-heading {
                font-size: 15.5px;
            }
        }

        /* Hiệu ứng nút liên hệ nổi rung nhẹ */
        @keyframes pulse-ring {
            0% { transform: scale(0.95); box-shadow: 0 0 0 0 rgba(217, 72, 15, 0.6); }
            70% { transform: scale(1); box-shadow: 0 0 0 10px rgba(217, 72, 15, 0); }
            100% { transform: scale(0.95); box-shadow: 0 0 0 0 rgba(217, 72, 15, 0); }
        }
        .floating-pulse {
            animation: pulse-ring 2s infinite;
        }

        /* Ẩn thanh cuộn ngang cho danh mục trên mobile */
        .no-scrollbar::-webkit-scrollbar {
            display: none;
        }
        .no-scrollbar {
            -ms-overflow-style: none;
            scrollbar-width: none;
        }
    </style>
</head>
<body>

    <!-- ================================================================= -->
    <!-- 1. TOP BAR (Đơn giản, không có tùy chọn UX Builder)               -->
    <!-- ================================================================= -->
    <div class="bg-brand-navy text-white text-[11.5px] py-1.5 border-b border-blue-900">
        <div class="flatsome-container flex flex-wrap items-center justify-between gap-2">
            <div class="flex items-center gap-2 truncate">
                <span class="font-semibold text-amber-300">hungmai.com</span>
                <span class="hidden sm:inline text-blue-200">|</span>
                <span class="truncate">CÔNG TY TNHH TMDV&XD HƯNG MAI - Gạch Men, TBVS, Sơn Nước & Thi Công</span>
            </div>
            <div class="hidden md:flex items-center gap-4 text-blue-100 whitespace-nowrap">
                <span><i class="fa-solid fa-location-dot text-amber-400 mr-1"></i>36 Đàm Văn Lễ, P. Hòa Khánh, TP Đà Nẵng</span>
                <span><i class="fa-solid fa-phone-volume text-amber-400 mr-1"></i>0904.524.442</span>
            </div>
        </div>
    </div>

    <!-- ================================================================= -->
    <!-- 2. HEADER (Logo chỉnh gọn nhỏ lại, KHÔNG để nút gọi ngay)          -->
    <!-- ================================================================= -->
    <header class="bg-white sticky top-0 z-40 shadow-sm border-b border-gray-200">
        <div class="flatsome-container py-2.5 flex items-center justify-between gap-2 sm:gap-4">
            
            <!-- Nút mở menu trên điện thoại -->
            <button onclick="toggleMobileDrawer()" aria-label="Mở danh mục" class="lg:hidden p-2 rounded bg-gray-100 text-brand-navy hover:bg-gray-200 shrink-0">
                <i class="fa-solid fa-bars text-base"></i>
            </button>

            <!-- Logo Công Ty TNHH TMDV&XD Hưng Mai (Thiết kế chuyên nghiệp, nhỏ gọn) -->
            <a href="#top" class="flex items-center gap-2 shrink-0 group">
                <svg class="w-9 h-9 sm:w-10 sm:h-10 shrink-0 rounded-md shadow-xs" viewBox="0 0 100 100" fill="none" xmlns="http://www.w3.org/2000/svg">
                    <rect width="100" height="100" rx="14" fill="#0d3b7a"/>
                    <!-- Biểu tượng Mái Nhà & Công Trình -->
                    <path d="M16 44L50 16L84 44V52L50 24L16 52V44Z" fill="#d9480f"/>
                    <!-- Chữ HM cách điệu -->
                    <path d="M25 48H35V64H45V48H55V82H45V72H35V82H25V48Z" fill="#ffffff"/>
                    <path d="M59 48H67L73 62L79 48H87V82H79V63L73 76L67 63V82H59V48Z" fill="#fbbf24"/>
                </svg>
                <div class="leading-tight">
                    <div class="text-[13px] sm:text-[15px] font-extrabold text-brand-navy tracking-tight">HƯNG MAI</div>
                    <div class="text-[9.5px] sm:text-[10.5px] font-semibold text-brand-orange uppercase">TMDV & Xây Dựng</div>
                    <div class="text-[9px] text-gray-500 hidden sm:block">hungmai.com</div>
                </div>
            </a>

            <!-- Ô tìm kiếm sản phẩm giữa Header -->
            <div class="flex-1 max-w-xl mx-1 sm:mx-3">
                <form onsubmit="handleSearch(event)" class="relative flex items-center w-full">
                    <input 
                        id="searchInput"
                        type="text" 
                        placeholder="Tìm gạch men, TBVS, sơn Jotun, Dulux, xi măng..." 
                        class="w-full text-xs sm:text-sm py-2 pl-3 pr-9 rounded border border-gray-300 focus:outline-none focus:border-brand-navy bg-gray-50"
                    >
                    <button type="submit" aria-label="Tìm kiếm" class="absolute right-0 top-0 bottom-0 px-3 text-white bg-brand-navy hover:bg-brand-orange rounded-r transition-colors">
                        <i class="fa-solid fa-magnifying-glass text-xs"></i>
                    </button>
                </form>
            </div>

            <!-- Liên kết nhanh gọn (Không để nút gọi ngay để tránh tràn viền) -->
            <div class="hidden xl:flex items-center gap-4 text-xs text-gray-700 shrink-0">
                <a href="#form-bao-gia" class="flex items-center gap-1.5 hover:text-brand-orange font-semibold">
                    <i class="fa-solid fa-file-invoice-dollar text-brand-orange text-sm"></i>
                    <span>Nhận Báo Giá</span>
                </a>
                <a href="#ban-do-cua-hang" class="flex items-center gap-1.5 hover:text-brand-orange font-semibold">
                    <i class="fa-solid fa-map-location-dot text-brand-navy text-sm"></i>
                    <span>36 Đàm Văn Lễ</span>
                </a>
            </div>
        </div>

        <!-- ================================================================= -->
        <!-- 3. THANH DANH MỤC TRÊN MÁY TÍNH & ĐIỆN THOẠI                      -->
        <!-- Trên máy tính: chữ nhỏ gọn, viết liền 1 hàng, nằm trên 1 hàng     -->
        <!-- hoặc tự xuống hàng 2 nguyên cụm, không bao giờ gãy chữ            -->
        <!-- ================================================================= -->
        <nav class="bg-brand-navy text-white border-t border-blue-800">
            <div class="flatsome-container py-1">
                <!-- Giao diện danh mục trên Máy Tính -->
                <div class="hidden lg:flex lg:flex-wrap items-center justify-start gap-x-1 gap-y-1">
                    <a href="#top" onclick="filterByCategory('ALL')" class="desktop-cat-link active" data-cat-btn="ALL">
                        <i class="fa-solid fa-house mr-1 text-[11px]"></i>TRANG CHỦ
                    </a>
                    <a href="#cua-hang-hung-mai" class="desktop-cat-link">
                        GIỚI THIỆU
                    </a>
                    <a href="#khu-vuc-san-pham" onclick="filterByCategory('GACH_MEN')" class="desktop-cat-link" data-cat-btn="GACH_MEN">
                        GẠCH MEN & ỐP LÁT
                    </a>
                    <a href="#khu-vuc-san-pham" onclick="filterByCategory('TBVS')" class="desktop-cat-link" data-cat-btn="TBVS">
                        THIẾT BỊ VỆ SINH
                    </a>
                    <a href="#khu-vuc-san-pham" onclick="filterByCategory('SON_NUOC')" class="desktop-cat-link" data-cat-btn="SON_NUOC">
                        SƠN NƯỚC (JOTUN - DULUX - MAXILITE)
                    </a>
                    <a href="#khu-vuc-san-pham" onclick="filterByCategory('CHONG_THAM')" class="desktop-cat-link" data-cat-btn="CHONG_THAM">
                        SƠN CHỐNG THẤM
                    </a>
                    <a href="#khu-vuc-san-pham" onclick="filterByCategory('VLXD')" class="desktop-cat-link" data-cat-btn="VLXD">
                        VẬT LIỆU XÂY DỰNG
                    </a>
                    <a href="#khu-vuc-san-pham" onclick="filterByCategory('VAT_TU_PHU')" class="desktop-cat-link" data-cat-btn="VAT_TU_PHU">
                        VẬT TƯ PHỤ
                    </a>
                    <a href="#dich-vu-thi-cong" class="desktop-cat-link">
                        THI CÔNG CÔNG TRÌNH
                    </a>
                    <a href="#doi-tac" class="desktop-cat-link">
                        ĐỐI TÁC
                    </a>
                    <a href="#bai-viet-trang-chu" class="desktop-cat-link">
                        TIN TỨC
                    </a>
                    <a href="#form-bao-gia" class="desktop-cat-link">
                        BÁO GIÁ & LIÊN HỆ
                    </a>
                </div>

                <!-- Giao diện danh mục nhanh trên Điện Thoại (Vuốt ngang mượt mà, không gãy chữ) -->
                <div class="flex lg:hidden items-center gap-1.5 overflow-x-auto no-scrollbar py-1">
                    <button onclick="filterByCategory('ALL')" class="whitespace-nowrap text-[11.5px] font-semibold px-2.5 py-1 rounded bg-brand-orange text-white shrink-0">
                        Tất cả
                    </button>
                    <button onclick="filterByCategory('GACH_MEN')" class="whitespace-nowrap text-[11.5px] font-semibold px-2.5 py-1 rounded bg-blue-900/80 hover:bg-brand-orange text-white shrink-0">
                        Gạch Men
                    </button>
                    <button onclick="filterByCategory('TBVS')" class="whitespace-nowrap text-[11.5px] font-semibold px-2.5 py-1 rounded bg-blue-900/80 hover:bg-brand-orange text-white shrink-0">
                        Thiết Bị Vệ Sinh
                    </button>
                    <button onclick="filterByCategory('SON_NUOC')" class="whitespace-nowrap text-[11.5px] font-semibold px-2.5 py-1 rounded bg-blue-900/80 hover:bg-brand-orange text-white shrink-0">
                        Sơn Nước
                    </button>
                    <button onclick="filterByCategory('CHONG_THAM')" class="whitespace-nowrap text-[11.5px] font-semibold px-2.5 py-1 rounded bg-blue-900/80 hover:bg-brand-orange text-white shrink-0">
                        Chống Thấm
                    </button>
                    <button onclick="filterByCategory('VLXD')" class="whitespace-nowrap text-[11.5px] font-semibold px-2.5 py-1 rounded bg-blue-900/80 hover:bg-brand-orange text-white shrink-0">
                        VLXD
                    </button>
                    <button onclick="filterByCategory('VAT_TU_PHU')" class="whitespace-nowrap text-[11.5px] font-semibold px-2.5 py-1 rounded bg-blue-900/80 hover:bg-brand-orange text-white shrink-0">
                        Vật Tư Phụ
                    </button>
                    <a href="#dich-vu-thi-cong" class="whitespace-nowrap text-[11.5px] font-semibold px-2.5 py-1 rounded bg-blue-900/80 hover:bg-brand-orange text-white shrink-0">
                        Thi Công
                    </a>
                    <a href="#form-bao-gia" class="whitespace-nowrap text-[11.5px] font-semibold px-2.5 py-1 rounded bg-blue-900/80 hover:bg-brand-orange text-white shrink-0">
                        Báo Giá
                    </a>
                </div>
            </div>
        </nav>
    </header>

    <!-- Menu Drawer trên Điện thoại -->
    <div id="mobileDrawer" class="fixed inset-0 z-50 hidden">
        <div onclick="toggleMobileDrawer()" class="fixed inset-0 bg-black/60"></div>
        <div class="relative w-72 max-w-[82vw] bg-white h-full shadow-2xl flex flex-col z-10 overflow-y-auto">
            <div class="p-3.5 bg-brand-navy text-white flex items-center justify-between">
                <span class="font-bold text-xs uppercase tracking-wider">DANH MỤC HƯNG MAI</span>
                <button onclick="toggleMobileDrawer()" class="w-7 h-7 rounded bg-white/10 flex items-center justify-center">
                    <i class="fa-solid fa-xmark"></i>
                </button>
            </div>
            <div class="divide-y divide-gray-100 text-xs font-semibold text-gray-800">
                <a href="#khu-vuc-san-pham" onclick="filterByCategory('ALL'); toggleMobileDrawer();" class="block px-4 py-3 hover:bg-gray-50">Tất Cả Sản Phẩm</a>
                <a href="#khu-vuc-san-pham" onclick="filterByCategory('GACH_MEN'); toggleMobileDrawer();" class="block px-4 py-3 hover:bg-gray-50">1. Gạch Men & Đá Ốp Lát</a>
                <a href="#khu-vuc-san-pham" onclick="filterByCategory('TBVS'); toggleMobileDrawer();" class="block px-4 py-3 hover:bg-gray-50">2. Thiết Bị Vệ Sinh (TBVS)</a>
                <a href="#khu-vuc-san-pham" onclick="filterByCategory('SON_NUOC'); toggleMobileDrawer();" class="block px-4 py-3 hover:bg-gray-50">3. Sơn Nước (Jotun, Dulux, Maxilite)</a>
                <a href="#khu-vuc-san-pham" onclick="filterByCategory('CHONG_THAM'); toggleMobileDrawer();" class="block px-4 py-3 hover:bg-gray-50">4. Sơn Chống Thấm & Hóa Chất</a>
                <a href="#khu-vuc-san-pham" onclick="filterByCategory('VLXD'); toggleMobileDrawer();" class="block px-4 py-3 hover:bg-gray-50">5. Vật Liệu Xây Dựng (Xi Măng, Cát, Đá, Thép)</a>
                <a href="#khu-vuc-san-pham" onclick="filterByCategory('VAT_TU_PHU'); toggleMobileDrawer();" class="block px-4 py-3 hover:bg-gray-50">6. Vật Tư Phụ Xây Dựng</a>
                <a href="#dich-vu-thi-cong" onclick="toggleMobileDrawer();" class="block px-4 py-3 hover:bg-gray-50">7. Dịch Vụ Thi Công Công Trình</a>
                <a href="#doi-tac" onclick="toggleMobileDrawer();" class="block px-4 py-3 hover:bg-gray-50">8. Đối Tác Thương Hiệu</a>
                <a href="#bai-viet-trang-chu" onclick="toggleMobileDrawer();" class="block px-4 py-3 hover:bg-gray-50">9. Tin Tức & Kinh Nghiệm</a>
                <a href="#form-bao-gia" onclick="toggleMobileDrawer();" class="block px-4 py-3 hover:bg-gray-50 text-brand-orange">10. Yêu Cầu Báo Giá</a>
            </div>
            <div class="p-4 mt-auto bg-gray-50 border-t border-gray-200 text-xs space-y-1.5">
                <div class="font-bold text-brand-navy">CÔNG TY TNHH TMDV&XD HƯNG MAI</div>
                <div class="text-gray-600">ĐC: 36 Đàm Văn Lễ, P. Hòa Khánh, TP Đà Nẵng</div>
                <div class="font-bold text-brand-orange">SĐT/Zalo: 0904.524.442</div>
            </div>
        </div>
    </div>

    <!-- ================================================================= -->
    <!-- 4. HAI BANNER TỰ TRƯỢT CHUYÊN NGHIỆP KÍCH THƯỚC BẰNG NHAU        -->
    <!-- Chữ & hình nằm gọn bên trong, cách xa viền, không mất chữ         -->
    <!-- ================================================================= -->
    <section id="top" class="py-3">
        <div class="flatsome-container">
            <div class="relative w-full h-[250px] sm:h-[310px] md:h-[360px] rounded-lg overflow-hidden shadow-md bg-brand-navy">
                
                <!-- SLIDE 1: Gạch Men - TBVS - Sơn Nước Chính Hãng -->
                <div id="banner-slide-0" class="banner-slide absolute inset-0 w-full h-full transition-opacity duration-700 opacity-100 z-10 bg-gradient-to-r from-[#0a2e63] via-[#12458f] to-[#0d3b7a] flex items-center">
                    <!-- Khoảng đệm rộng (px-7 sm:px-14 md:px-20) đảm bảo chữ cách xa viền banner -->
                    <div class="w-full h-full px-7 sm:px-14 md:px-20 py-5 flex flex-col md:flex-row items-center justify-between gap-4">
                        <div class="w-full md:w-3/5 text-white space-y-1.5 sm:space-y-2.5 text-center md:text-left">
                            <div class="inline-block bg-brand-orange text-white text-[10px] sm:text-xs font-bold px-2.5 py-0.5 rounded uppercase tracking-wider">
                                hungmai.com - Tổng Kho Phân Phối Chính Hãng
                            </div>
                            <h1 class="text-sm sm:text-xl md:text-2xl lg:text-3xl font-extrabold leading-snug text-white">
                                CÔNG TY TNHH TMDV&XD HƯNG MAI
                            </h1>
                            <p class="text-[11px] sm:text-xs md:text-sm text-blue-100 leading-relaxed">
                                Chuyên Gạch Men Ốp Lát, Thiết Bị Vệ Sinh Cao Cấp, Sơn Nước (Jotun, Dulux, Maxilite) & Vật Liệu Xây Dựng.
                            </p>
                            <div class="pt-1 flex flex-wrap items-center justify-center md:justify-start gap-2 text-[11px] sm:text-xs">
                                <span class="bg-white/15 px-2.5 py-1 rounded text-amber-300 font-semibold">
                                    <i class="fa-solid fa-location-dot mr-1"></i>36 Đàm Văn Lễ, P. Hòa Khánh, Đà Nẵng
                                </span>
                                <span class="bg-amber-400 text-brand-navy px-2.5 py-1 rounded font-extrabold">
                                    <i class="fa-solid fa-phone mr-1"></i>0904.524.442
                                </span>
                            </div>
                        </div>
                        <!-- Khung ảnh thực tế nằm gọn bên trong banner -->
                        <div class="hidden md:flex md:w-2/5 justify-center items-center">
                            <div class="grid grid-cols-2 gap-2.5 p-2.5 bg-white/10 rounded-lg border border-white/20 max-w-[300px]">
                                <img src="https://drive.google.com/thumbnail?id=1IoXlEyTKTbZIOdhCTDhomRntEqO0MXe7&sz=w500" alt="Showroom Hưng Mai" class="w-32 h-24 object-cover rounded bg-white" onerror="this.src='https://placehold.co/300x220/0d3b7a/ffffff?text=HUNG+MAI'">
                                <img src="https://drive.google.com/thumbnail?id=1P2fePSvPXm6YIcNDixVa0YwFWshcHFDY&sz=w500" alt="Gạch men Hưng Mai" class="w-32 h-24 object-cover rounded bg-white" onerror="this.src='https://placehold.co/300x220/1554ad/ffffff?text=GACH+MEN'">
                                <img src="https://drive.google.com/thumbnail?id=171kMlCqYFeFpvYcgH1wQbaIMszY0Ns3O&sz=w500" alt="TBVS Hưng Mai" class="w-32 h-24 object-cover rounded bg-white" onerror="this.src='https://placehold.co/300x220/d9480f/ffffff?text=TBVS'">
                                <img src="https://drive.google.com/thumbnail?id=1X-ECML9CKN4ycBfVFu4pC0wnqzTS12CP&sz=w500" alt="Sơn nước Hưng Mai" class="w-32 h-24 object-cover rounded bg-white" onerror="this.src='https://placehold.co/300x220/0d3b7a/fbbf24?text=SON+NUOC'">
                            </div>
                        </div>
                    </div>
                </div>

                <!-- SLIDE 2: Thi Công Công Trình & Cung Ứng VLXD Trọn Gói (Kích thước bằng hệt Slide 1) -->
                <div id="banner-slide-1" class="banner-slide absolute inset-0 w-full h-full transition-opacity duration-700 opacity-0 z-0 bg-gradient-to-r from-[#14335c] via-[#0d3b7a] to-[#1e4e8c] flex items-center">
                    <div class="w-full h-full px-7 sm:px-14 md:px-20 py-5 flex flex-col md:flex-row items-center justify-between gap-4">
                        <div class="w-full md:w-3/5 text-white space-y-1.5 sm:space-y-2.5 text-center md:text-left">
                            <div class="inline-block bg-amber-400 text-brand-navy text-[10px] sm:text-xs font-extrabold px-2.5 py-0.5 rounded uppercase tracking-wider">
                                Giải Pháp Xây Dựng & Hoàn Thiện Toàn Diện
                            </div>
                            <h2 class="text-sm sm:text-xl md:text-2xl lg:text-3xl font-extrabold leading-snug text-white">
                                THI CÔNG CÔNG TRÌNH & BÁO GIÁ VLXD SỈ LẺ
                            </h2>
                            <p class="text-[11px] sm:text-xs md:text-sm text-blue-100 leading-relaxed">
                                Nhận thi công ốp lát gạch men, lắp đặt thiết bị vệ sinh, sơn nước, chống thấm và xây dựng nhà ở dân dụng uy tín tại Đà Nẵng.
                            </p>
                            <div class="pt-1 flex flex-wrap items-center justify-center md:justify-start gap-2 text-[11px] sm:text-xs">
                                <span class="bg-white/15 px-2.5 py-1 rounded text-white font-semibold">
                                    <i class="fa-solid fa-check-circle text-amber-300 mr-1"></i>Chiết khấu cao cho thầu thợ
                                </span>
                                <span class="bg-brand-orange text-white px-2.5 py-1 rounded font-extrabold">
                                    <i class="fa-solid fa-headset mr-1"></i>Tư vấn: 0904.524.442
                                </span>
                            </div>
                        </div>
                        <div class="hidden md:flex md:w-2/5 justify-center items-center">
                            <div class="grid grid-cols-2 gap-2.5 p-2.5 bg-white/10 rounded-lg border border-white/20 max-w-[300px]">
                                <img src="https://drive.google.com/thumbnail?id=11z7ir7cmqEcdrYuAThZvpOhgUVFsLUnP&sz=w500" alt="Sản phẩm thực tế" class="w-32 h-24 object-cover rounded bg-white" onerror="this.src='https://placehold.co/300x220/0d3b7a/ffffff?text=OP+LAT'">
                                <img src="https://drive.google.com/thumbnail?id=1NwR4v0eypEtIwPi6NJVJCKoNCFFQ8G54&sz=w500" alt="Sản phẩm thực tế" class="w-32 h-24 object-cover rounded bg-white" onerror="this.src='https://placehold.co/300x220/1554ad/ffffff?text=THI+CONG'">
                                <img src="https://drive.google.com/thumbnail?id=1ciwHcFfmGbsIyjTsi9KlyIsx6EXBNJTN&sz=w500" alt="Sản phẩm thực tế" class="w-32 h-24 object-cover rounded bg-white" onerror="this.src='https://placehold.co/300x220/d9480f/ffffff?text=CHONG+THAM'">
                                <img src="https://drive.google.com/thumbnail?id=1WLKyUBxRc63xFN9GBUhFcqE0xPo0sQKh&sz=w500" alt="Sản phẩm thực tế" class="w-32 h-24 object-cover rounded bg-white" onerror="this.src='https://placehold.co/300x220/0d3b7a/fbbf24?text=VLXD'">
                            </div>
                        </div>
                    </div>
                </div>

                <!-- Nút điều hướng trái/phải nằm sát mép ngoài vùng chữ -->
                <button onclick="changeSlide(-1)" aria-label="Slide trước" class="absolute left-1.5 top-1/2 -translate-y-1/2 z-20 w-7 h-7 sm:w-8 sm:h-8 rounded-full bg-black/35 hover:bg-black/60 text-white flex items-center justify-center">
                    <i class="fa-solid fa-chevron-left text-xs"></i>
                </button>
                <button onclick="changeSlide(1)" aria-label="Slide kế tiếp" class="absolute right-1.5 top-1/2 -translate-y-1/2 z-20 w-7 h-7 sm:w-8 sm:h-8 rounded-full bg-black/35 hover:bg-black/60 text-white flex items-center justify-center">
                    <i class="fa-solid fa-chevron-right text-xs"></i>
                </button>

                <!-- Dấu chấm chuyển Slide -->
                <div class="absolute bottom-2 left-1/2 -translate-x-1/2 z-20 flex items-center gap-2">
                    <button onclick="goToSlide(0)" id="dot-0" class="w-6 h-2 rounded-full bg-amber-400 transition-all"></button>
                    <button onclick="goToSlide(1)" id="dot-1" class="w-2.5 h-2 rounded-full bg-white/60 transition-all"></button>
                </div>
            </div>
        </div>
    </section>

    <!-- ================================================================= -->
    <!-- 5. DANH MỤC SẢN PHẨM TRANG CHỦ (Chữ nhỏ gọn, chuẩn UX Builder)    -->
    <!-- ================================================================= -->
    <section class="py-3">
        <div class="flatsome-container">
            <div class="flatsome-section-title">
                <h2 class="flatsome-section-heading">
                    <i class="fa-solid fa-layer-group text-brand-orange"></i>
                    <span>DANH MỤC SẢN PHẨM & DỊCH VỤ</span>
                </h2>
                <span class="text-[11px] text-gray-500 hidden sm:inline">Chọn danh mục để lọc nhanh</span>
            </div>

            <div class="grid grid-cols-2 sm:grid-cols-4 lg:grid-cols-7 gap-2 sm:gap-2.5">
                <button onclick="filterByCategory('GACH_MEN')" class="bg-white p-2.5 rounded border border-gray-200 hover:border-brand-navy shadow-2xs flex flex-col items-center text-center transition">
                    <div class="w-9 h-9 rounded-full bg-blue-50 text-brand-navy flex items-center justify-center mb-1.5">
                        <i class="fa-solid fa-border-all text-sm"></i>
                    </div>
                    <span class="text-xs font-bold text-gray-800 leading-tight">Gạch Men & Ốp Lát</span>
                    <span class="text-[10px] text-gray-500 mt-0.5">60x60, 80x80, 30x60</span>
                </button>

                <button onclick="filterByCategory('TBVS')" class="bg-white p-2.5 rounded border border-gray-200 hover:border-brand-navy shadow-2xs flex flex-col items-center text-center transition">
                    <div class="w-9 h-9 rounded-full bg-orange-50 text-brand-orange flex items-center justify-center mb-1.5">
                        <i class="fa-solid fa-shower text-sm"></i>
                    </div>
                    <span class="text-xs font-bold text-gray-800 leading-tight">Thiết Bị Vệ Sinh</span>
                    <span class="text-[10px] text-gray-500 mt-0.5">Bồn cầu, Sen cây, Tủ chậu</span>
                </button>

                <button onclick="filterByCategory('SON_NUOC')" class="bg-white p-2.5 rounded border border-gray-200 hover:border-brand-navy shadow-2xs flex flex-col items-center text-center transition">
                    <div class="w-9 h-9 rounded-full bg-blue-50 text-brand-navy flex items-center justify-center mb-1.5">
                        <i class="fa-solid fa-fill-drip text-sm"></i>
                    </div>
                    <span class="text-xs font-bold text-gray-800 leading-tight">Sơn Nước Chính Hãng</span>
                    <span class="text-[10px] text-gray-500 mt-0.5">Jotun, Dulux, Maxilite</span>
                </button>

                <button onclick="filterByCategory('CHONG_THAM')" class="bg-white p-2.5 rounded border border-gray-200 hover:border-brand-navy shadow-2xs flex flex-col items-center text-center transition">
                    <div class="w-9 h-9 rounded-full bg-orange-50 text-brand-orange flex items-center justify-center mb-1.5">
                        <i class="fa-solid fa-shield-halved text-sm"></i>
                    </div>
                    <span class="text-xs font-bold text-gray-800 leading-tight">Sơn Chống Thấm</span>
                    <span class="text-[10px] text-gray-500 mt-0.5">Sika, CT-11A, BestSeal</span>
                </button>

                <button onclick="filterByCategory('VLXD')" class="bg-white p-2.5 rounded border border-gray-200 hover:border-brand-navy shadow-2xs flex flex-col items-center text-center transition">
                    <div class="w-9 h-9 rounded-full bg-blue-50 text-brand-navy flex items-center justify-center mb-1.5">
                        <i class="fa-solid fa-trowel-bricks text-sm"></i>
                    </div>
                    <span class="text-xs font-bold text-gray-800 leading-tight">Vật Liệu Xây Dựng</span>
                    <span class="text-[10px] text-gray-500 mt-0.5">Xi măng, Cát, Đá, Thép</span>
                </button>

                <button onclick="filterByCategory('VAT_TU_PHU')" class="bg-white p-2.5 rounded border border-gray-200 hover:border-brand-navy shadow-2xs flex flex-col items-center text-center transition">
                    <div class="w-9 h-9 rounded-full bg-orange-50 text-brand-orange flex items-center justify-center mb-1.5">
                        <i class="fa-solid fa-paint-roller text-sm"></i>
                    </div>
                    <span class="text-xs font-bold text-gray-800 leading-tight">Vật Tư Phụ</span>
                    <span class="text-[10px] text-gray-500 mt-0.5">Keo dán gạch, Cọ lăn, Bay</span>
                </button>

                <a href="#dich-vu-thi-cong" class="col-span-2 sm:col-span-2 lg:col-span-1 bg-white p-2.5 rounded border border-gray-200 hover:border-brand-navy shadow-2xs flex flex-col items-center text-center transition">
                    <div class="w-9 h-9 rounded-full bg-blue-50 text-brand-navy flex items-center justify-center mb-1.5">
                        <i class="fa-solid fa-helmet-safety text-sm"></i>
                    </div>
                    <span class="text-xs font-bold text-gray-800 leading-tight">Thi Công Công Trình</span>
                    <span class="text-[10px] text-gray-500 mt-0.5">Ốp lát, Sơn, Xây dựng</span>
                </a>
            </div>
        </div>
    </section>

    <!-- ================================================================= -->
    <!-- 6. DANH SÁCH SẢN PHẨM THEO TỪNG DANH MỤC (Giống web mẫu)          -->
    <!-- - Điện thoại chia 2 cột (grid-cols-2)                             -->
    <!-- - Tên sản phẩm hiển thị đầy đủ, không thiếu chữ                   -->
    <!-- - Chỉ hiển thị % giảm giá góc trên bên trái chuẩn Flatsome        -->
    <!-- ================================================================= -->
    <main id="khu-vuc-san-pham" class="py-2 space-y-6">
        <div class="flatsome-container space-y-6" id="productSectionsContainer">
            <!-- Được render tự động bằng JavaScript từ dữ liệu thực tế -->
        </div>
    </main>

    <!-- ================================================================= -->
    <!-- 7. DỊCH VỤ THI CÔNG CÔNG TRÌNH & HÌNH ẢNH CỬA HÀNG THỰC TẾ       -->
    <!-- ================================================================= -->
    <section id="cua-hang-hung-mai" class="py-4">
        <div class="flatsome-container">
            <div class="flatsome-section-title">
                <h2 class="flatsome-section-heading">
                    <i class="fa-solid fa-store text-brand-orange"></i>
                    <span>SHOWROOM CỬA HÀNG & DỊCH VỤ THI CÔNG HƯNG MAI</span>
                </h2>
                <span class="text-xs font-semibold text-brand-navy">36 Đàm Văn Lễ, TP Đà Nẵng</span>
            </div>

            <div id="dich-vu-thi-cong" class="bg-white rounded-lg border border-gray-200 p-4 sm:p-5 grid grid-cols-1 lg:grid-cols-12 gap-5 items-center">
                <!-- Ảnh thực tế cửa hàng từ Google Drive -->
                <div class="lg:col-span-5">
                    <div class="rounded-lg overflow-hidden border border-gray-200 bg-gray-100">
                        <img 
                            src="https://drive.google.com/thumbnail?id=1IoXlEyTKTbZIOdhCTDhomRntEqO0MXe7&sz=w1000" 
                            alt="Showroom Cửa hàng Công ty TNHH TMDV&XD Hưng Mai - 36 Đàm Văn Lễ" 
                            class="w-full h-60 sm:h-72 object-cover"
                            onerror="this.onerror=null; this.src='https://lh3.googleusercontent.com/d/1IoXlEyTKTbZIOdhCTDhomRntEqO0MXe7';"
                        >
                        <div class="p-2.5 bg-brand-navy text-white text-xs text-center font-medium">
                            Hình ảnh thực tế Cửa hàng Hưng Mai - 36 Đàm Văn Lễ, Phường Hòa Khánh, TP Đà Nẵng
                        </div>
                    </div>
                </div>

                <!-- Nội dung năng lực cung ứng & thi công -->
                <div class="lg:col-span-7 space-y-3">
                    <h3 class="text-base sm:text-lg font-extrabold text-brand-navy">
                        CÔNG TY TNHH TMDV&XD HƯNG MAI – ĐỐI TÁC TIN CẬY CHO MỌI CÔNG TRÌNH
                    </h3>
                    <p class="text-xs sm:text-sm text-gray-700 leading-relaxed">
                        Tọa lạc tại <strong>36 Đàm Văn Lễ, Phường Hòa Khánh, TP Đà Nẵng</strong>, <strong>Hưng Mai (hungmai.com)</strong> là đơn vị chuyên phân phối sỉ & lẻ gạch men ốp lát, thiết bị vệ sinh phòng tắm, sơn nước chính hãng (Jotun, Dulux, Maxilite, Sika) cùng vật liệu xây dựng và nhận thi công hoàn thiện công trình trọn gói.
                    </p>
                    <div class="grid grid-cols-1 sm:grid-cols-2 gap-2.5 pt-1">
                        <div class="p-3 rounded bg-gray-50 border border-gray-200">
                            <div class="font-bold text-xs sm:text-sm text-brand-navy mb-1">
                                <i class="fa-solid fa-check text-brand-orange mr-1.5"></i>Thi Công Ốp Lát & Lắp Đặt TBVS
                            </div>
                            <p class="text-xs text-gray-600">Đội ngũ thợ lành nghề thi công ốp lát gạch nền, gạch tường, đá cầu thang và lắp đặt trọn bộ thiết bị vệ sinh chuẩn kỹ thuật.</p>
                        </div>
                        <div class="p-3 rounded bg-gray-50 border border-gray-200">
                            <div class="font-bold text-xs sm:text-sm text-brand-navy mb-1">
                                <i class="fa-solid fa-check text-brand-orange mr-1.5"></i>Thi Công Sơn Nước & Chống Thấm
                            </div>
                            <p class="text-xs text-gray-600">Tư vấn phối màu sơn 3D, thi công bả matit, sơn nội ngoại thất Jotun/Dulux và xử lý chống thấm sàn mái, tường đứng triệt để.</p>
                        </div>
                        <div class="p-3 rounded bg-gray-50 border border-gray-200">
                            <div class="font-bold text-xs sm:text-sm text-brand-navy mb-1">
                                <i class="fa-solid fa-check text-brand-orange mr-1.5"></i>Xây Dựng & Cải Tạo Nhà Trọn Gói
                            </div>
                            <p class="text-xs text-gray-600">Nhận xây mới, sửa chữa, cải tạo nhà phố, biệt thự, văn phòng, nhà xưởng tại Đà Nẵng với cam kết đúng tiến độ.</p>
                        </div>
                        <div class="p-3 rounded bg-gray-50 border border-gray-200">
                            <div class="font-bold text-xs sm:text-sm text-brand-navy mb-1">
                                <i class="fa-solid fa-check text-brand-orange mr-1.5"></i>Giao Hàng Tận Chân Công Trình
                            </div>
                            <p class="text-xs text-gray-600">Vận chuyển nhanh chóng tận nơi tại Hòa Khánh, Liên Chiểu và toàn TP Đà Nẵng, chiết khấu cao cho nhà thầu.</p>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- ================================================================= -->
    <!-- 8. FORM YÊU CẦU BÁO GIÁ + FACEBOOK + GOOGLE MAP NGOÀI TRANG CHỦ    -->
    <!-- ================================================================= -->
    <section id="form-bao-gia" class="py-4">
        <div class="flatsome-container">
            <div class="flatsome-section-title">
                <h2 class="flatsome-section-heading">
                    <i class="fa-solid fa-paper-plane text-brand-orange"></i>
                    <span>YÊU CẦU BÁO GIÁ & KẾT NỐI TRỰC TIẾP TRANG CHỦ</span>
                </h2>
                <span class="text-xs text-gray-500">Hỗ trợ nhanh qua Hotline/Zalo: 0904.524.442</span>
            </div>

            <div class="grid grid-cols-1 lg:grid-cols-12 gap-4">
                
                <!-- CỘT 1: FORM YÊU CẦU VÀ BÁO GIÁ TRANG CHỦ (5 cột) -->
                <div class="lg:col-span-5 bg-white rounded-lg border border-gray-200 p-4 shadow-2xs">
                    <h3 class="text-sm sm:text-base font-extrabold text-brand-navy uppercase mb-1">
                        ĐĂNG KÝ NHẬN BÁO GIÁ SỈ & LẺ
                    </h3>
                    <p class="text-xs text-gray-600 mb-3">
                        Để lại thông tin, Hưng Mai sẽ gửi bảng báo giá chiết khấu tốt nhất qua Zalo hoặc gọi lại ngay.
                    </p>
                    <form onsubmit="submitQuoteForm(event)" class="space-y-2.5 text-xs sm:text-sm">
                        <div>
                            <label class="block font-semibold text-gray-700 mb-1">Họ và tên khách hàng *</label>
                            <input id="qName" type="text" required placeholder="Nhập họ và tên của bạn" class="w-full px-3 py-2 rounded border border-gray-300 focus:outline-none focus:border-brand-navy">
                        </div>
                        <div>
                            <label class="block font-semibold text-gray-700 mb-1">Số điện thoại / Zalo *</label>
                            <input id="qPhone" type="tel" required placeholder="Ví dụ: 0904524442" class="w-full px-3 py-2 rounded border border-gray-300 focus:outline-none focus:border-brand-navy">
                        </div>
                        <div>
                            <label class="block font-semibold text-gray-700 mb-1">Danh mục cần báo giá</label>
                            <select id="qCategory" class="w-full px-3 py-2 rounded border border-gray-300 focus:outline-none focus:border-brand-navy bg-white">
                                <option value="Gạch men & Đá ốp lát">Gạch men & Đá ốp lát</option>
                                <option value="Thiết bị vệ sinh (TBVS)">Thiết bị vệ sinh (TBVS)</option>
                                <option value="Sơn nước Jotun / Dulux / Maxilite">Sơn nước Jotun / Dulux / Maxilite</option>
                                <option value="Sơn chống thấm & Hóa chất">Sơn chống thấm & Hóa chất</option>
                                <option value="Vật liệu xây dựng & Vật tư phụ">Vật liệu xây dựng & Vật tư phụ</option>
                                <option value="Thi công công trình trọn gói">Thi công công trình trọn gói</option>
                            </select>
                        </div>
                        <div>
                            <label class="block font-semibold text-gray-700 mb-1">Nội dung / Địa chỉ công trình</label>
                            <textarea id="qNote" rows="3" placeholder="Nhập mã sản phẩm, số lượng hoặc địa chỉ công trình tại Đà Nẵng..." class="w-full px-3 py-2 rounded border border-gray-300 focus:outline-none focus:border-brand-navy"></textarea>
                        </div>
                        <button type="submit" class="w-full py-2.5 px-4 rounded bg-brand-orange hover:bg-brand-navy text-white font-bold uppercase tracking-wide transition">
                            <i class="fa-solid fa-paper-plane mr-1.5"></i>GỬI YÊU CẦU BÁO GIÁ NGAY
                        </button>
                        <div id="quoteSuccessMsg" class="hidden p-2.5 rounded bg-green-50 border border-green-300 text-green-800 text-xs font-medium"></div>
                    </form>
                </div>

                <!-- CỘT 2: FACEBOOK CHÍNH THỨC NGOÀI TRANG CHỦ (3 cột) -->
                <div class="lg:col-span-3 bg-white rounded-lg border border-gray-200 p-4 shadow-2xs flex flex-col justify-between">
                    <div>
                        <h3 class="text-sm sm:text-base font-extrabold text-brand-navy uppercase mb-1 flex items-center gap-1.5">
                            <i class="fa-brands fa-facebook text-[#1877F2] text-lg"></i>
                            <span>FACEBOOK HƯNG MAI</span>
                        </h3>
                        <p class="text-xs text-gray-600 mb-3">
                            Kết nối trực tiếp qua Facebook để xem hình ảnh hàng về và công trình thực tế mỗi ngày.
                        </p>

                        <!-- Thẻ hiển thị Facebook ngoài trang chủ -->
                        <div class="rounded-lg overflow-hidden border border-gray-200 bg-gray-50">
                            <div class="h-24 bg-gradient-to-r from-brand-navy to-brand-blue relative p-3 flex items-end">
                                <img src="https://drive.google.com/thumbnail?id=1IoXlEyTKTbZIOdhCTDhomRntEqO0MXe7&sz=w500" alt="Facebook Hưng Mai" class="w-14 h-14 rounded-full border-2 border-white object-cover bg-white shadow">
                                <div class="ml-2.5 text-white">
                                    <div class="font-bold text-xs sm:text-sm leading-tight">Hưng Ngô (Hưng Mai)</div>
                                    <div class="text-[11px] text-blue-100">Gạch Men - TBVS - Sơn Nước</div>
                                </div>
                            </div>
                            <div class="p-3 space-y-2 text-xs text-gray-700">
                                <div class="flex items-center gap-2">
                                    <i class="fa-solid fa-building text-brand-navy"></i>
                                    <span>CÔNG TY TNHH TMDV&XD HƯNG MAI</span>
                                </div>
                                <div class="flex items-center gap-2">
                                    <i class="fa-solid fa-location-dot text-brand-orange"></i>
                                    <span>36 Đàm Văn Lễ, P. Hòa Khánh, Đà Nẵng</span>
                                </div>
                                <div class="flex items-center gap-2">
                                    <i class="fa-solid fa-phone text-green-600"></i>
                                    <span class="font-bold">0904.524.442</span>
                                </div>
                                <div class="text-[11px] text-blue-700 break-all bg-blue-50 p-1.5 rounded">
                                    facebook.com/hung.ngo.450108
                                </div>
                            </div>
                        </div>
                    </div>

                    <a href="https://www.facebook.com/hung.ngo.450108" target="_blank" rel="noopener noreferrer" class="mt-3 w-full py-2.5 px-3 rounded bg-[#1877F2] hover:bg-blue-700 text-white font-bold text-xs sm:text-sm text-center flex items-center justify-center gap-2 transition">
                        <i class="fa-brands fa-facebook-messenger"></i>
                        <span>MỞ FACEBOOK TRỰC TIẾP</span>
                    </a>
                </div>

                <!-- CỘT 3: GOOGLE MAP NGOÀI TRANG CHỦ (4 cột) -->
                <div id="ban-do-cua-hang" class="lg:col-span-4 bg-white rounded-lg border border-gray-200 p-4 shadow-2xs flex flex-col justify-between">
                    <div>
                        <h3 class="text-sm sm:text-base font-extrabold text-brand-navy uppercase mb-1 flex items-center gap-1.5">
                            <i class="fa-solid fa-map-location-dot text-brand-orange text-lg"></i>
                            <span>BẢN ĐỒ GOOGLE MAPS</span>
                        </h3>
                        <p class="text-xs text-gray-600 mb-2">
                            <strong>Địa chỉ:</strong> 36 Đàm Văn Lễ, Phường Hòa Khánh, TP Đà Nẵng
                        </p>
                        <!-- Nhúng trực tiếp Google Maps ra ngoài trang chủ -->
                        <div class="w-full h-56 sm:h-60 rounded-lg overflow-hidden border border-gray-300 bg-gray-100">
                            <iframe 
                                title="Bản đồ 36 Đàm Văn Lễ, Phường Hòa Khánh, TP Đà Nẵng"
                                src="https://www.google.com/maps?q=36+%C4%90%C3%A0m+V%C4%83n+L%E1%BB%85,+H%C3%B2a+Kh%C3%A1nh,+%C4%90%C3%A0+N%E1%BA%B5ng&output=embed"
                                class="w-full h-full border-0" 
                                allowfullscreen="" 
                                loading="lazy" 
                                referrerpolicy="no-referrer-when-downgrade">
                            </iframe>
                        </div>
                    </div>
                    <a href="https://www.google.com/maps/place//data=!4m2!3m1!19sChIJI4BlPRcZQjERE3VMCuWbDes" target="_blank" rel="noopener noreferrer" class="mt-3 w-full py-2.5 px-3 rounded bg-brand-navy hover:bg-brand-orange text-white font-bold text-xs sm:text-sm text-center flex items-center justify-center gap-2 transition">
                        <i class="fa-solid fa-diamond-turn-right"></i>
                        <span>CHỈ ĐƯỜNG TRÊN GOOGLE MAPS</span>
                    </a>
                </div>

            </div>
        </div>
    </section>

    <!-- ================================================================= -->
    <!-- 9. DANH MỤC CÁC BÀI VIẾT TRANG CHỦ (TIN TỨC & KINH NGHIỆM)        -->
    <!-- ================================================================= -->
    <section id="bai-viet-trang-chu" class="py-4">
        <div class="flatsome-container">
            <div class="flatsome-section-title">
                <h2 class="flatsome-section-heading">
                    <i class="fa-solid fa-newspaper text-brand-orange"></i>
                    <span>DANH MỤC BÀI VIẾT & KINH NGHIỆM XÂY DỰNG</span>
                </h2>
                <span class="text-xs text-gray-500">Cập nhật kiến thức VLXD & thi công</span>
            </div>

            <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-4 gap-3.5">
                <!-- Bài viết 1 -->
                <article class="bg-white rounded-lg border border-gray-200 overflow-hidden shadow-2xs flex flex-col">
                    <img src="https://drive.google.com/thumbnail?id=1P2fePSvPXm6YIcNDixVa0YwFWshcHFDY&sz=w600" alt="Kinh nghiệm chọn gạch men" class="w-full h-40 object-cover bg-gray-100" onerror="this.src='https://placehold.co/600x400/0d3b7a/ffffff?text=GACH+MEN+DA+NANG'">
                    <div class="p-3.5 flex-1 flex flex-col justify-between">
                        <div>
                            <div class="text-[11px] font-semibold text-brand-orange uppercase mb-1">Tư vấn Gạch Men</div>
                            <h3 class="text-xs sm:text-sm font-bold text-gray-900 leading-snug mb-1.5">
                                Kinh nghiệm chọn gạch lát nền 60x60, 80x80 và gạch ốp tường bền đẹp cho nhà phố Đà Nẵng
                            </h3>
                            <p class="text-xs text-gray-600 leading-relaxed">
                                Hướng dẫn cách chọn chất liệu gạch Porcelain, Granite chống trầy xước, chống thấm hút nước phù hợp từng không gian phòng khách, phòng bếp...
                            </p>
                        </div>
                        <a href="#form-bao-gia" class="mt-3 inline-block text-xs font-bold text-brand-navy hover:text-brand-orange">
                            Nhận tư vấn mẫu gạch <i class="fa-solid fa-arrow-right ml-1"></i>
                        </a>
                    </div>
                </article>

                <!-- Bài viết 2 -->
                <article class="bg-white rounded-lg border border-gray-200 overflow-hidden shadow-2xs flex flex-col">
                    <img src="https://drive.google.com/thumbnail?id=171kMlCqYFeFpvYcgH1wQbaIMszY0Ns3O&sz=w600" alt="Combo thiết bị vệ sinh" class="w-full h-40 object-cover bg-gray-100" onerror="this.src='https://placehold.co/600x400/1554ad/ffffff?text=THIET+BI+VE+SINH'">
                    <div class="p-3.5 flex-1 flex flex-col justify-between">
                        <div>
                            <div class="text-[11px] font-semibold text-brand-orange uppercase mb-1">Thiết Bị Vệ Sinh</div>
                            <h3 class="text-xs sm:text-sm font-bold text-gray-900 leading-snug mb-1.5">
                                Trọn bộ Thiết Bị Vệ Sinh phòng tắm gồm những gì? Báo giá ưu đãi tại Hưng Mai
                            </h3>
                            <p class="text-xs text-gray-600 leading-relaxed">
                                Giải pháp đồng bộ bồn cầu 1 khối men Nano kháng khuẩn, sen cây tắm nóng lạnh Inox 304 và bộ tủ chậu Lavabo hiện đại, tiết kiệm chi phí...
                            </p>
                        </div>
                        <a href="#form-bao-gia" class="mt-3 inline-block text-xs font-bold text-brand-navy hover:text-brand-orange">
                            Xem báo giá combo TBVS <i class="fa-solid fa-arrow-right ml-1"></i>
                        </a>
                    </div>
                </article>

                <!-- Bài viết 3 -->
                <article class="bg-white rounded-lg border border-gray-200 overflow-hidden shadow-2xs flex flex-col">
                    <img src="https://drive.google.com/thumbnail?id=1X-ECML9CKN4ycBfVFu4pC0wnqzTS12CP&sz=w600" alt="Sơn nước và chống thấm" class="w-full h-40 object-cover bg-gray-100" onerror="this.src='https://placehold.co/600x400/d9480f/ffffff?text=SON+CHONG+THAM'">
                    <div class="p-3.5 flex-1 flex flex-col justify-between">
                        <div>
                            <div class="text-[11px] font-semibold text-brand-orange uppercase mb-1">Sơn Nước & Chống Thấm</div>
                            <h3 class="text-xs sm:text-sm font-bold text-gray-900 leading-snug mb-1.5">
                                Quy trình thi công sơn Jotun, Dulux và chống thấm Sika bền màu trước khí hậu miền Trung
                            </h3>
                            <p class="text-xs text-gray-600 leading-relaxed">
                                Bí quyết xử lý bề mặt tường, chọn bột trét, sơn lót kháng kiềm và sơn phủ chống bám bẩn giúp bảo vệ ngôi nhà lên đến 10 năm...
                            </p>
                        </div>
                        <a href="#form-bao-gia" class="mt-3 inline-block text-xs font-bold text-brand-navy hover:text-brand-orange">
                            Tư vấn quy trình sơn <i class="fa-solid fa-arrow-right ml-1"></i>
                        </a>
                    </div>
                </article>

                <!-- Bài viết 4 -->
                <article class="bg-white rounded-lg border border-gray-200 overflow-hidden shadow-2xs flex flex-col">
                    <img src="https://drive.google.com/thumbnail?id=1IoXlEyTKTbZIOdhCTDhomRntEqO0MXe7&sz=w600" alt="Báo giá vật liệu xây dựng Đà Nẵng" class="w-full h-40 object-cover bg-gray-100" onerror="this.src='https://placehold.co/600x400/0d3b7a/fbbf24?text=VLXD+HUNG+MAI'">
                    <div class="p-3.5 flex-1 flex flex-col justify-between">
                        <div>
                            <div class="text-[11px] font-semibold text-brand-orange uppercase mb-1">Vật Liệu Xây Dựng</div>
                            <h3 class="text-xs sm:text-sm font-bold text-gray-900 leading-snug mb-1.5">
                                Hưng Mai – Địa chỉ cung cấp VLXD, gạch men, TBVS và thi công uy tín tại Hòa Khánh, Đà Nẵng
                            </h3>
                            <p class="text-xs text-gray-600 leading-relaxed">
                                Cam kết sản phẩm chính hãng 100%, báo giá minh bạch, hỗ trợ vận chuyển nhanh chóng tận công trình tại 36 Đàm Văn Lễ, Đà Nẵng...
                            </p>
                        </div>
                        <a href="#form-bao-gia" class="mt-3 inline-block text-xs font-bold text-brand-navy hover:text-brand-orange">
                            Liên hệ đặt hàng ngay <i class="fa-solid fa-arrow-right ml-1"></i>
                        </a>
                    </div>
                </article>
            </div>
        </div>
    </section>

    <!-- ================================================================= -->
    <!-- 10. DANH MỤC CÁC ĐỐI TÁC THƯƠNG HIỆU                              -->
    <!-- ================================================================= -->
    <section id="doi-tac" class="py-4">
        <div class="flatsome-container">
            <div class="flatsome-section-title">
                <h2 class="flatsome-section-heading">
                    <i class="fa-solid fa-handshake text-brand-orange"></i>
                    <span>ĐỐI TÁC & THƯƠNG HIỆU PHÂN PHỐI CHÍNH HÃNG</span>
                </h2>
                <span class="text-xs text-gray-500">Hợp tác cùng các thương hiệu hàng đầu</span>
            </div>

            <div class="grid grid-cols-2 sm:grid-cols-3 md:grid-cols-6 gap-2.5">
                <div class="bg-white border border-gray-200 rounded p-3 text-center flex flex-col items-center justify-center h-20">
                    <span class="font-extrabold text-sm sm:text-base text-brand-navy tracking-wider">JOTUN</span>
                    <span class="text-[10px] text-gray-500">Sơn Nước Chính Hãng</span>
                </div>
                <div class="bg-white border border-gray-200 rounded p-3 text-center flex flex-col items-center justify-center h-20">
                    <span class="font-extrabold text-sm sm:text-base text-blue-700 tracking-wider">DULUX - MAXILITE</span>
                    <span class="text-[10px] text-gray-500">Sơn Nội Ngoại Thất</span>
                </div>
                <div class="bg-white border border-gray-200 rounded p-3 text-center flex flex-col items-center justify-center h-20">
                    <span class="font-extrabold text-sm sm:text-base text-red-600 tracking-wider">SIKA</span>
                    <span class="text-[10px] text-gray-500">Hóa Chất Chống Thấm</span>
                </div>
                <div class="bg-white border border-gray-200 rounded p-3 text-center flex flex-col items-center justify-center h-20">
                    <span class="font-extrabold text-sm sm:text-base text-brand-navy tracking-wider">VIGLACERA - PRIME</span>
                    <span class="text-[10px] text-gray-500">Gạch Men Cao Cấp</span>
                </div>
                <div class="bg-white border border-gray-200 rounded p-3 text-center flex flex-col items-center justify-center h-20">
                    <span class="font-extrabold text-sm sm:text-base text-blue-800 tracking-wider">INAX - TOTO</span>
                    <span class="text-[10px] text-gray-500">Thiết Bị Vệ Sinh</span>
                </div>
                <div class="bg-white border border-gray-200 rounded p-3 text-center flex flex-col items-center justify-center h-20">
                    <span class="font-extrabold text-sm sm:text-base text-amber-700 tracking-wider">ĐỒNG LÂM - HÒA PHÁT</span>
                    <span class="text-[10px] text-gray-500">Xi Măng & Sắt Thép</span>
                </div>
            </div>
        </div>
    </section>

    <!-- ================================================================= -->
    <!-- 11. FOOTER CHUẨN MẪU FLATSOME                                     -->
    <!-- ================================================================= -->
    <footer class="bg-brand-navy text-white mt-6 border-t-4 border-brand-orange">
        <div class="flatsome-container py-8 grid grid-cols-1 md:grid-cols-2 lg:grid-cols-4 gap-6 text-xs sm:text-sm">
            
            <!-- Thông tin công ty -->
            <div class="space-y-2.5">
                <div class="flex items-center gap-2.5">
                    <svg class="w-9 h-9 shrink-0 rounded bg-white p-0.5" viewBox="0 0 100 100" fill="none" xmlns="http://www.w3.org/2000/svg">
                        <rect width="100" height="100" rx="14" fill="#0d3b7a"/>
                        <path d="M16 44L50 16L84 44V52L50 24L16 52V44Z" fill="#d9480f"/>
                        <path d="M25 48H35V64H45V48H55V82H45V72H35V82H25V48Z" fill="#ffffff"/>
                        <path d="M59 48H67L73 62L79 48H87V82H79V63L73 76L67 63V82H59V48Z" fill="#fbbf24"/>
                    </svg>
                    <div>
                        <div class="font-extrabold text-white text-sm">CÔNG TY TNHH TMDV&XD HƯNG MAI</div>
                        <div class="text-amber-300 text-xs font-semibold">Website: hungmai.com</div>
                    </div>
                </div>
                <p class="text-blue-100 text-xs leading-relaxed">
                    Chuyên phân phối Gạch men, Thiết bị vệ sinh, Sơn nước, Chống thấm, Vật liệu xây dựng và Thi công công trình uy tín tại Đà Nẵng.
                </p>
                <div class="space-y-1 text-xs text-blue-100">
                    <div><i class="fa-solid fa-location-dot text-amber-400 mr-1.5"></i><strong>Địa chỉ:</strong> 36 Đàm Văn Lễ, Phường Hòa Khánh, TP Đà Nẵng</div>
                    <div><i class="fa-solid fa-phone text-amber-400 mr-1.5"></i><strong>Hotline/Zalo:</strong> 0904.524.442</div>
                    <div><i class="fa-brands fa-facebook text-amber-400 mr-1.5"></i><strong>Facebook:</strong> fb.com/hung.ngo.450108</div>
                </div>
            </div>

            <!-- Danh mục sản phẩm -->
            <div>
                <h4 class="font-extrabold text-sm uppercase text-amber-300 mb-3 border-b border-blue-800 pb-1.5">DANH MỤC SẢN PHẨM</h4>
                <ul class="space-y-2 text-xs text-blue-100">
                    <li><a href="#khu-vuc-san-pham" onclick="filterByCategory('GACH_MEN')" class="hover:text-white"><i class="fa-solid fa-angle-right mr-1.5 text-amber-400"></i>Gạch Men & Đá Ốp Lát</a></li>
                    <li><a href="#khu-vuc-san-pham" onclick="filterByCategory('TBVS')" class="hover:text-white"><i class="fa-solid fa-angle-right mr-1.5 text-amber-400"></i>Thiết Bị Vệ Sinh Phòng Tắm</a></li>
                    <li><a href="#khu-vuc-san-pham" onclick="filterByCategory('SON_NUOC')" class="hover:text-white"><i class="fa-solid fa-angle-right mr-1.5 text-amber-400"></i>Sơn Nước Jotun - Dulux - Maxilite</a></li>
                    <li><a href="#khu-vuc-san-pham" onclick="filterByCategory('CHONG_THAM')" class="hover:text-white"><i class="fa-solid fa-angle-right mr-1.5 text-amber-400"></i>Sơn Chống Thấm Sika - CT11A</a></li>
                    <li><a href="#khu-vuc-san-pham" onclick="filterByCategory('VLXD')" class="hover:text-white"><i class="fa-solid fa-angle-right mr-1.5 text-amber-400"></i>Vật Liệu Xây Dựng (Xi măng, Cát, Đá, Thép)</a></li>
                    <li><a href="#khu-vuc-san-pham" onclick="filterByCategory('VAT_TU_PHU')" class="hover:text-white"><i class="fa-solid fa-angle-right mr-1.5 text-amber-400"></i>Vật Tư Phụ Xây Dựng</a></li>
                </ul>
            </div>

            <!-- Dịch vụ & Hỗ trợ -->
            <div>
                <h4 class="font-extrabold text-sm uppercase text-amber-300 mb-3 border-b border-blue-800 pb-1.5">DỊCH VỤ & HỖ TRỢ</h4>
                <ul class="space-y-2 text-xs text-blue-100">
                    <li><a href="#dich-vu-thi-cong" class="hover:text-white"><i class="fa-solid fa-angle-right mr-1.5 text-amber-400"></i>Thi Công Ốp Lát Gạch Men</a></li>
                    <li><a href="#dich-vu-thi-cong" class="hover:text-white"><i class="fa-solid fa-angle-right mr-1.5 text-amber-400"></i>Thi Công Sơn Nước & Chống Thấm</a></li>
                    <li><a href="#dich-vu-thi-cong" class="hover:text-white"><i class="fa-solid fa-angle-right mr-1.5 text-amber-400"></i>Lắp Đặt Thiết Bị Vệ Sinh Trọn Gói</a></li>
                    <li><a href="#dich-vu-thi-cong" class="hover:text-white"><i class="fa-solid fa-angle-right mr-1.5 text-amber-400"></i>Xây Dựng & Cải Tạo Công Trình</a></li>
                    <li><a href="#form-bao-gia" class="hover:text-white"><i class="fa-solid fa-angle-right mr-1.5 text-amber-400"></i>Yêu Cầu Báo Giá Sỉ & Lẻ</a></li>
                    <li><a href="#ban-do-cua-hang" class="hover:text-white"><i class="fa-solid fa-angle-right mr-1.5 text-amber-400"></i>Chỉ Đường Đến 36 Đàm Văn Lễ</a></li>
                </ul>
            </div>

            <!-- Thống kê truy cập giống web mẫu -->
            <div>
                <h4 class="font-extrabold text-sm uppercase text-amber-300 mb-3 border-b border-blue-800 pb-1.5">THỐNG KÊ & KẾT NỐI</h4>
                <div class="bg-blue-950/70 p-3 rounded border border-blue-800 space-y-1.5 text-xs text-blue-100">
                    <div class="flex justify-between"><span>Đang trực tuyến:</span><span class="font-bold text-amber-300">12</span></div>
                    <div class="flex justify-between"><span>Hôm nay:</span><span class="font-bold text-white">148</span></div>
                    <div class="flex justify-between"><span>Tháng này:</span><span class="font-bold text-white">4.620</span></div>
                    <div class="flex justify-between"><span>Tổng truy cập:</span><span class="font-bold text-amber-400">186.450</span></div>
                </div>
                <div class="mt-3 flex items-center gap-2">
                    <a href="tel:0904524442" class="flex-1 py-2 px-2.5 rounded bg-brand-orange text-white text-center font-bold text-xs">
                        <i class="fa-solid fa-phone mr-1"></i>0904.524.442
                    </a>
                    <a href="https://www.facebook.com/hung.ngo.450108" target="_blank" rel="noopener noreferrer" class="py-2 px-3 rounded bg-[#1877F2] text-white font-bold text-xs">
                        <i class="fa-brands fa-facebook-f"></i>
                    </a>
                </div>
            </div>
        </div>

        <div class="bg-[#082754] py-3 text-center text-xs text-blue-200 border-t border-blue-900">
            <div class="flatsome-container">
                Copyright © 2026 <strong>CÔNG TY TNHH TMDV&XD HƯNG MAI (hungmai.com)</strong> - 36 Đàm Văn Lễ, P. Hòa Khánh, TP Đà Nẵng.
            </div>
        </div>
    </footer>

    <!-- ================================================================= -->
    <!-- 12. NÚT LIÊN HỆ NỔI BẬT (ZALO, FACEBOOK, HOTLINE)                 -->
    <!-- Tương thích hoàn hảo trên cả máy tính và điện thoại               -->
    <!-- ================================================================= -->
    <div class="fixed right-2.5 bottom-4 z-50 flex flex-col items-end gap-2.5">
        
        <!-- Nút Facebook nổi -->
        <a href="https://www.facebook.com/hung.ngo.450108" target="_blank" rel="noopener noreferrer" title="Chat Facebook Hưng Mai" class="flex items-center gap-2 bg-[#1877F2] hover:bg-blue-700 text-white rounded-full p-2.5 sm:px-3.5 sm:py-2 shadow-lg transition">
            <i class="fa-brands fa-facebook-messenger text-lg sm:text-base"></i>
            <span class="hidden sm:inline text-xs font-bold">Facebook</span>
        </a>

        <!-- Nút Zalo nổi -->
        <a href="https://zalo.me/0904524442" target="_blank" rel="noopener noreferrer" title="Chat Zalo 0904.524.442" class="flex items-center gap-2 bg-[#0068ff] hover:bg-blue-600 text-white rounded-full p-2.5 sm:px-3.5 sm:py-2 shadow-lg transition">
            <span class="font-extrabold text-xs sm:text-xs bg-white text-[#0068ff] px-1.5 py-0.5 rounded-full leading-none">Zalo</span>
            <span class="hidden sm:inline text-xs font-bold">0904.524.442</span>
        </a>

        <!-- Nút Hotline nổi có hiệu ứng rung -->
        <a href="tel:0904524442" title="Gọi ngay 0904.524.442" class="floating-pulse flex items-center gap-2 bg-brand-orange hover:bg-red-700 text-white rounded-full p-3 sm:px-4 sm:py-2.5 shadow-xl transition">
            <i class="fa-solid fa-phone-volume text-base"></i>
            <span class="text-xs font-extrabold">0904.524.442</span>
        </a>
    </div>

    <!-- ================================================================= -->
    <!-- JAVASCRIPT: DỮ LIỆU SẢN PHẨM THỰC TẾ TỪ GOOGLE DRIVE & WEB MẪU    -->
    <!-- ================================================================= -->
    <script>
        // Hàm tạo link ảnh Google Drive ổn định
        function driveImg(id) {
            return `https://drive.google.com/thumbnail?id=${id}&sz=w800`;
        }

        // Danh mục & toàn bộ 19 ảnh thực tế Google Drive + danh mục sản phẩm từ trang mẫu vatlieuxaydungdanang.com
        const PRODUCT_SECTIONS = [
            {
                id: 'GACH_MEN',
                title: 'GẠCH MEN & ĐÁ ỐP LÁT',
                icon: 'fa-border-all',
                products: [
                    {
                        name: 'Gạch Lát Nền Vân Đá Marble Bóng Kiếng 60x60 Cao Cấp HM-G01',
                        driveId: '1P2fePSvPXm6YIcNDixVa0YwFWshcHFDY',
                        oldPrice: '215.000 ₫/m²',
                        price: '165.000 ₫/m²',
                        discount: '-23%'
                    },
                    {
                        name: 'Gạch Lát Nền Khổ Lớn 80x80 Vân Đá Tự Nhiên Chống Trầy HM-G02',
                        driveId: '11z7ir7cmqEcdrYuAThZvpOhgUVFsLUnP',
                        oldPrice: '285.000 ₫/m²',
                        price: '219.000 ₫/m²',
                        discount: '-23%'
                    },
                    {
                        name: 'Gạch Ốp Tường Phòng Khách & Phòng Tắm 30x60 Men Bóng HM-G03',
                        driveId: '1KTDzdSGqiXWuLZDkPoDD7oZZVL-5F3Rr',
                        oldPrice: '195.000 ₫/m²',
                        price: '148.000 ₫/m²',
                        discount: '-24%'
                    },
                    {
                        name: 'Gạch Lát Nền Vân Mây Sang Trọng Xương Đá Porcelain HM-G04',
                        driveId: '1X31hmhpLVVORV-tmMSZYzBO-qtpyusry',
                        oldPrice: '240.000 ₫/m²',
                        price: '179.000 ₫/m²',
                        discount: '-25%'
                    },
                    {
                        name: 'Gạch Vân Gỗ Lát Phòng Ngủ & Mặt Tiền Chống Thấm HM-G05',
                        driveId: '171kMlCqYFeFpvYcgH1wQbaIMszY0Ns3O',
                        oldPrice: '230.000 ₫/m²',
                        price: '172.000 ₫/m²',
                        discount: '-25%'
                    },
                    {
                        name: 'Gạch Trang Trí & Ốp Mặt Tiền Hiện Đại Bền Màu HM-G06',
                        driveId: '1t8U7WQsmDbGWzmSelkxzjVv8M0BvIxAg',
                        oldPrice: '260.000 ₫/m²',
                        price: '195.000 ₫/m²',
                        discount: '-25%'
                    },
                    {
                        name: 'Gạch Sân Vườn Chống Trơn Trượt Chịu Lực Cao HM-G07',
                        driveId: '1uqL6ACCB5ne0G1BYkXCurdnrsf1m2lr4',
                        oldPrice: '175.000 ₫/m²',
                        price: '135.000 ₫/m²',
                        discount: '-23%'
                    }
                ]
            },
            {
                id: 'TBVS',
                title: 'THIẾT BỊ VỆ SINH (TBVS)',
                icon: 'fa-shower',
                products: [
                    {
                        name: 'Bồn Cầu Nguyên Khối Men Tuyết Nano Kháng Khuẩn Xả Xoáy HM-VS01',
                        driveId: '1NwR4v0eypEtIwPi6NJVJCKoNCFFQ8G54',
                        oldPrice: '3.650.000 ₫',
                        price: '2.550.000 ₫',
                        discount: '-30%'
                    },
                    {
                        name: 'Bộ Tủ Chậu Lavabo Kèm Gương Phòng Tắm Chống Nước HM-VS02',
                        driveId: '19jauCH_X7lcc0KNlu2OJ75CRiw3ArT7r',
                        oldPrice: '4.200.000 ₫',
                        price: '2.950.000 ₫',
                        discount: '-30%'
                    },
                    {
                        name: 'Sen Cây Tắm Đứng Nóng Lạnh Inox 304 Cao Cấp HM-VS03',
                        driveId: '1_HXfxWiPLtWiayxMPjgFCsl1WS1wGb7h',
                        oldPrice: '2.450.000 ₫',
                        price: '1.690.000 ₫',
                        discount: '-31%'
                    },
                    {
                        name: 'Chậu Rửa Lavabo Đặt Bàn Tráng Men Cao Cấp Chống Bám Bẩn HM-VS04',
                        driveId: '1ciwHcFfmGbsIyjTsi9KlyIsx6EXBNJTN',
                        oldPrice: '1.250.000 ₫',
                        price: '890.000 ₫',
                        discount: '-29%'
                    },
                    {
                        name: 'Vòi Lavabo Nóng Lạnh & Bộ Phụ Kiện Phòng Tắm Đồng Bộ HM-VS05',
                        driveId: '1vHG-pgeryaSItJoQ5ciiCGSWA7SJSU8c',
                        oldPrice: '980.000 ₫',
                        price: '680.000 ₫',
                        discount: '-31%'
                    },
                    {
                        name: 'Chậu Rửa Chén Bát Inox 304 Đúc Nguyên Khối Kèm Vòi HM-VS06',
                        driveId: '1X-ECML9CKN4ycBfVFu4pC0wnqzTS12CP',
                        oldPrice: '2.600.000 ₫',
                        price: '1.850.000 ₫',
                        discount: '-29%'
                    }
                ]
            },
            {
                id: 'SON_NUOC',
                title: 'SƠN NƯỚC (JOTUN - DULUX - MAXILITE)',
                icon: 'fa-fill-drip',
                products: [
                    {
                        name: 'Sơn Nội Thất Jotun Majestic Đẹp Hoàn Hảo Bóng Chính Hãng',
                        driveId: '1CGBZ4cuB7DMWadnoktlMoji6MB3dioC-',
                        oldPrice: '2.223.000 ₫',
                        price: '1.450.000 ₫',
                        discount: '-35%'
                    },
                    {
                        name: 'Sơn Ngoại Thất Jotun Jotashield Bền Màu Toàn Diện',
                        driveId: '17YrxXteZmzhvVRYgfaklNGC2hKjN09N8',
                        oldPrice: '3.546.000 ₫',
                        price: '2.305.000 ₫',
                        discount: '-35%'
                    },
                    {
                        name: 'Sơn Nội Thất Jotun Essence Che Phủ Tối Đa (Bề Mặt Mờ)',
                        driveId: '19k5uWHn_xeas2_BMP_JgBDwwu-IysSRP',
                        oldPrice: '1.803.000 ₫',
                        price: '1.170.000 ₫',
                        discount: '-35%'
                    },
                    {
                        name: 'Bột Trét Tường Jotun Ngoại Thất & Nội Thất Chính Hãng',
                        driveId: '1oah4j6YAPIsJacMYQFJ0JGVemrMwqCgf',
                        oldPrice: '515.000 ₫',
                        price: '361.000 ₫',
                        discount: '-30%'
                    },
                    {
                        name: 'Sơn Ngoại Thất Dulux Weathershield BJ8 & Sơn Lót Chống Kiềm A936',
                        driveId: '15IWAPhzVLsyUO5TDRoWXxvncrHoFcH1_',
                        oldPrice: '3.450.000 ₫',
                        price: '2.415.000 ₫',
                        discount: '-30%'
                    },
                    {
                        name: 'Sơn Nội Ngoại Thất Maxilite Total & Maxilite Tough 28C Chính Hãng',
                        driveId: '1WLKyUBxRc63xFN9GBUhFcqE0xPo0sQKh',
                        oldPrice: '1.420.000 ₫',
                        price: '995.000 ₫',
                        discount: '-30%'
                    }
                ]
            },
            {
                id: 'CHONG_THAM',
                title: 'SƠN CHỐNG THẤM & HÓA CHẤT XÂY DỰNG',
                icon: 'fa-shield-halved',
                products: [
                    {
                        name: 'Chống Thấm Đàn Hồi Sikalastic-110 & SikaTop-107 Seal VN',
                        driveId: '1CGBZ4cuB7DMWadnoktlMoji6MB3dioC-',
                        oldPrice: '1.350.000 ₫',
                        price: '980.000 ₫',
                        discount: '-27%'
                    },
                    {
                        name: 'Sơn Chống Thấm Pha Xi Măng CT-11A Đa Năng Chính Hãng',
                        driveId: '17YrxXteZmzhvVRYgfaklNGC2hKjN09N8',
                        oldPrice: '2.100.000 ₫',
                        price: '1.550.000 ₫',
                        discount: '-26%'
                    },
                    {
                        name: 'Chống Thấm Hai Thành Phần Smartflex Komix & BestSeal AC408',
                        driveId: '19k5uWHn_xeas2_BMP_JgBDwwu-IysSRP',
                        oldPrice: '1.650.000 ₫',
                        price: '1.220.000 ₫',
                        discount: '-26%'
                    },
                    {
                        name: 'Sơn Lót Chống Thấm Ngược & Phụ Gia Chống Thấm Sika Latex TH',
                        driveId: '1oah4j6YAPIsJacMYQFJ0JGVemrMwqCgf',
                        oldPrice: '890.000 ₫',
                        price: '650.000 ₫',
                        discount: '-27%'
                    }
                ]
            },
            {
                id: 'VLXD',
                title: 'VẬT LIỆU XÂY DỰNG (XI MĂNG - CÁT - ĐÁ - GẠCH - THÉP)',
                icon: 'fa-trowel-bricks',
                products: [
                    {
                        name: 'Xi Măng Đồng Lâm PCB40, Kim Đỉnh PCB40 & Sông Gianh',
                        driveId: '1IoXlEyTKTbZIOdhCTDhomRntEqO0MXe7',
                        oldPrice: '98.000 ₫/bao',
                        price: '86.000 ₫/bao',
                        discount: '-12%'
                    },
                    {
                        name: 'Thép Cuộn D6, D8 & Thép Cây Hòa Phát - Việt Mỹ Chính Hãng',
                        driveId: '1WLKyUBxRc63xFN9GBUhFcqE0xPo0sQKh',
                        oldPrice: '',
                        price: 'Liên hệ: 0904.524.442',
                        discount: '-15%'
                    },
                    {
                        name: 'Gạch Xây 6 Lỗ & Gạch Thẻ Điện Ngọc - Đại Hưng Chất Lượng Cao',
                        driveId: '1uqL6ACCB5ne0G1BYkXCurdnrsf1m2lr4',
                        oldPrice: '',
                        price: 'Liên hệ: 0904.524.442',
                        discount: '-15%'
                    },
                    {
                        name: 'Đá Xây Dựng 1x2, 2x4, 4x6 & Cát Xây, Cát Tô, Cát Đúc Đà Nẵng',
                        driveId: '1t8U7WQsmDbGWzmSelkxzjVv8M0BvIxAg',
                        oldPrice: '',
                        price: 'Liên hệ: 0904.524.442',
                        discount: '-10%'
                    }
                ]
            },
            {
                id: 'VAT_TU_PHU',
                title: 'VẬT TƯ PHỤ XÂY DỰNG & ỐP LÁT',
                icon: 'fa-paint-roller',
                products: [
                    {
                        name: 'Keo Dán Gạch & Keo Chà Ron Chống Thấm Cao Cấp Đủ Màu',
                        driveId: '15IWAPhzVLsyUO5TDRoWXxvncrHoFcH1_',
                        oldPrice: '245.000 ₫/bao',
                        price: '185.000 ₫/bao',
                        discount: '-24%'
                    },
                    {
                        name: 'Cọ Lăn Sơn Nước Đông Nam Á 15cm - 23cm & Cọ Quét Sơn',
                        driveId: '1X-ECML9CKN4ycBfVFu4pC0wnqzTS12CP',
                        oldPrice: '35.000 ₫',
                        price: '25.000 ₫',
                        discount: '-28%'
                    },
                    {
                        name: 'Bay Thép Xây Dựng, Bàn Chà Nhám, Dao Trét Nhựa & Sủi Sơn',
                        driveId: '1vHG-pgeryaSItJoQ5ciiCGSWA7SJSU8c',
                        oldPrice: '32.000 ₫',
                        price: '25.000 ₫',
                        discount: '-22%'
                    },
                    {
                        name: 'Giấy Nhám Vải, Nhám Máy 100-240 & Ke Cân Bằng Gạch Ốp Lát',
                        driveId: '1ciwHcFfmGbsIyjTsi9KlyIsx6EXBNJTN',
                        oldPrice: '90.000 ₫/bịch',
                        price: '65.000 ₫/bịch',
                        discount: '-28%'
                    }
                ]
            }
        ];

        let currentCategory = 'ALL';
        let currentSearch = '';

        function renderProductSections() {
            const container = document.getElementById('productSectionsContainer');
            let html = '';

            const filteredSections = PRODUCT_SECTIONS.filter(sec => {
                return currentCategory === 'ALL' || sec.id === currentCategory;
            });

            filteredSections.forEach(section => {
                const matchedProducts = section.products.filter(p => {
                    if (!currentSearch) return true;
                    return p.name.toLowerCase().includes(currentSearch.toLowerCase());
                });

                if (matchedProducts.length === 0) return;

                html += `
                <section class="w-full">
                    <div class="flatsome-section-title">
                        <h2 class="flatsome-section-heading">
                            <i class="fa-solid ${section.icon} text-brand-orange"></i>
                            <span>${section.title}</span>
                        </h2>
                        <a href="#form-bao-gia" class="text-xs font-bold text-brand-orange hover:underline whitespace-nowrap">
                            Nhận báo giá sỉ <i class="fa-solid fa-angle-right ml-0.5"></i>
                        </a>
                    </div>

                    <!-- Sản phẩm chia thành 2 cột trên điện thoại (grid-cols-2), 4-5 cột trên máy tính -->
                    <div class="grid grid-cols-2 sm:grid-cols-3 md:grid-cols-4 lg:grid-cols-5 gap-2.5 sm:gap-3.5">
                        ${matchedProducts.map(prod => `
                            <div class="bg-white rounded-md border border-gray-200 hover:border-brand-navy overflow-hidden shadow-2xs flex flex-col justify-between transition">
                                <div>
                                    <!-- Khung ảnh sản phẩm thực tế + % giảm giá góc trên bên trái chuẩn Flatsome -->
                                    <div class="relative w-full aspect-square bg-gray-100 overflow-hidden border-b border-gray-100">
                                        ${prod.discount ? `<div class="flatsome-onsale">${prod.discount}</div>` : ''}
                                        <img 
                                            src="${driveImg(prod.driveId)}" 
                                            alt="${prod.name}" 
                                            loading="lazy"
                                            class="w-full h-full object-cover hover:scale-105 transition-transform duration-300"
                                            onerror="this.onerror=null; this.src='https://lh3.googleusercontent.com/d/${prod.driveId}';"
                                        >
                                    </div>

                                    <!-- Tên sản phẩm đầy đủ, không bị cắt chữ hoặc tràn ra ngoài -->
                                    <div class="p-2.5 sm:p-3">
                                        <h3 class="product-title-full text-xs sm:text-[13.5px] font-semibold text-gray-800 mb-1.5">
                                            ${prod.name}
                                        </h3>
                                        <div class="flex flex-wrap items-baseline gap-1.5">
                                            ${prod.oldPrice ? `<del class="text-[11px] text-gray-400">${prod.oldPrice}</del>` : ''}
                                            <ins class="no-underline text-xs sm:text-sm font-extrabold text-brand-orange">${prod.price}</ins>
                                        </div>
                                    </div>
                                </div>

                                <!-- Nút đặt mua / liên hệ báo giá -->
                                <div class="px-2.5 pb-2.5 sm:px-3 sm:pb-3 pt-1">
                                    <a href="#form-bao-gia" onclick="prefillProduct('${prod.name.replace(/'/g, "\\'")}')" class="block w-full py-1.5 px-2 rounded bg-brand-navy hover:bg-brand-orange text-white text-center text-[11px] sm:text-xs font-bold transition">
                                        Liên hệ: 0904.524.442
                                    </a>
                                </div>
                            </div>
                        `).join('')}
                    </div>
                </section>
                `;
            });

            if (!html) {
                html = `
                <div class="bg-white rounded-lg p-8 text-center border border-gray-200">
                    <p class="text-sm text-gray-700 font-semibold mb-2">Không tìm thấy sản phẩm phù hợp với từ khóa "${currentSearch}".</p>
                    <button onclick="resetFilter()" class="px-4 py-2 rounded bg-brand-navy text-white text-xs font-bold">Xem tất cả sản phẩm</button>
                </div>`;
            }

            container.innerHTML = html;
        }

        function filterByCategory(catId) {
            currentCategory = catId;
            currentSearch = '';
            const searchInput = document.getElementById('searchInput');
            if (searchInput) searchInput.value = '';

            document.querySelectorAll('[data-cat-btn]').forEach(btn => {
                if (btn.getAttribute('data-cat-btn') === catId) {
                    btn.classList.add('active');
                } else {
                    btn.classList.remove('active');
                }
            });

            renderProductSections();
        }

        function handleSearch(e) {
            e.preventDefault();
            const val = document.getElementById('searchInput').value.trim();
            currentSearch = val;
            currentCategory = 'ALL';
            renderProductSections();
            document.getElementById('khu-vuc-san-pham').scrollIntoView({ behavior: 'smooth' });
        }

        function resetFilter() {
            currentCategory = 'ALL';
            currentSearch = '';
            document.getElementById('searchInput').value = '';
            renderProductSections();
        }

        function prefillProduct(productName) {
            const noteEl = document.getElementById('qNote');
            if (noteEl) {
                noteEl.value = `Tôi cần tư vấn & báo giá sản phẩm: ${productName}`;
            }
        }

        // Quản lý Drawer trên Mobile
        function toggleMobileDrawer() {
            const drawer = document.getElementById('mobileDrawer');
            drawer.classList.toggle('hidden');
        }

        // Quản lý 2 Banner tự trượt chuyên nghiệp
        let activeSlide = 0;
        const totalSlides = 2;
        let slideTimer = null;

        function showSlide(index) {
            activeSlide = (index + totalSlides) % totalSlides;
            for (let i = 0; i < totalSlides; i++) {
                const slide = document.getElementById(`banner-slide-${i}`);
                const dot = document.getElementById(`dot-${i}`);
                if (i === activeSlide) {
                    slide.classList.remove('opacity-0', 'z-0');
                    slide.classList.add('opacity-100', 'z-10');
                    dot.className = 'w-6 h-2 rounded-full bg-amber-400 transition-all';
                } else {
                    slide.classList.remove('opacity-100', 'z-10');
                    slide.classList.add('opacity-0', 'z-0');
                    dot.className = 'w-2.5 h-2 rounded-full bg-white/60 transition-all';
                }
            }
        }

        function changeSlide(step) {
            showSlide(activeSlide + step);
            restartSlideTimer();
        }

        function goToSlide(index) {
            showSlide(index);
            restartSlideTimer();
        }

        function restartSlideTimer() {
            if (slideTimer) clearInterval(slideTimer);
            slideTimer = setInterval(() => {
                showSlide(activeSlide + 1);
            }, 5000);
        }

        // Xử lý gửi Form Yêu Cầu Báo Giá
        function submitQuoteForm(e) {
            e.preventDefault();
            const name = document.getElementById('qName').value.trim();
            const phone = document.getElementById('qPhone').value.trim();
            const category = document.getElementById('qCategory').value;
            const note = document.getElementById('qNote').value.trim();
            const msgBox = document.getElementById('quoteSuccessMsg');

            msgBox.classList.remove('hidden');
            msgBox.innerHTML = `<i class="fa-solid fa-circle-check mr-1"></i>Cảm ơn <strong>${name}</strong> (${phone})! Yêu cầu báo giá <strong>${category}</strong> đã được ghi nhận. Bộ phận kinh doanh Hưng Mai sẽ liên hệ ngay qua SĐT/Zalo <strong>0904.524.442</strong>.`;
            e.target.reset();
        }

        window.onload = function() {
            renderProductSections();
            restartSlideTimer();
        };
    </script>
</body>
</html>
