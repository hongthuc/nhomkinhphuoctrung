<html lang="vi">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=5.0" />
  <title>Nhôm Kính Phước Trung Đà Nẵng | Cửa Nhôm Xingfa &amp; Kính Cường Lực Chính Hãng</title>
  <meta name="description" content="Nhôm Kính Phước Trung (nhomkinhphuoctrung.com) - Chuyên thi công cửa nhôm Xingfa, cửa kính cường lực, cửa nhựa lõi thép, cầu thang kính, kính ốp bếp, phòng tắm kính tại Tp. Đà Nẵng. Hotline: 0905.192.439." />

  <!-- Meta Thumbnail Logo khi chia sẻ đường link trang web lên Zalo, Facebook -->
  <meta property="og:type" content="website" />
  <meta property="og:site_name" content="Nhôm Kính Phước Trung" />
  <meta property="og:title" content="Nhôm Kính Phước Trung Đà Nẵng - Cửa Nhôm Xingfa &amp; Kính Cường Lực" />
  <meta property="og:description" content="Thi công cửa nhôm Xingfa nhập khẩu, cửa kính cường lực, cầu thang kính, kính ốp bếp, phòng tắm kính uy tín tại TP. Đà Nẵng. Hotline: 0905.192.439." />
  <meta property="og:url" content="https://nhomkinhphuoctrung.com" />
  <meta property="og:image" content="https://nhomkinhphuoctrung.com/wp-content/uploads/logo-nhom-kinh-phuoc-trung.png" />
  <meta property="og:image:alt" content="Logo Nhôm Kính Phước Trung Đà Nẵng" />
  <meta name="twitter:card" content="summary_large_image" />
  <meta name="twitter:title" content="Nhôm Kính Phước Trung Đà Nẵng" />
  <meta name="twitter:description" content="Cửa Nhôm Xingfa &amp; Kính Cường Lực Chính Hãng tại TP. Đà Nẵng - 0905.192.439" />
  <meta name="twitter:image" content="https://nhomkinhphuoctrung.com/wp-content/uploads/logo-nhom-kinh-phuoc-trung.png" />

  <!-- Favicon SVG Logo Phước Trung -->
  <link rel="icon" type="image/svg+xml" href="data:image/svg+xml,%3Csvg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 64 64'%3E%3Crect width='64' height='64' rx='12' fill='%230B3C5D'/%3E%3Cpath d='M14 14h16v36H14z' fill='none' stroke='%23FFFFFF' stroke-width='4'/%3E%3Cpath d='M34 14h16v22H34z' fill='%23E67E22'/%3E%3Cpath d='M34 40h16v10H34z' fill='%2338BDF8'/%3E%3C/svg%3E" />

  <!-- Google Fonts: Inter -->
  <link rel="preconnect" href="https://fonts.googleapis.com" />
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin />
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700;800&display=swap" rel="stylesheet" />

  <!-- Font Awesome Icons -->
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.2/css/all.min.css" />

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
              dark: '#082B44',      /* Xanh Navy đậm theo Logo */
              primary: '#0B3C5D',   /* Xanh dương kiến trúc chủ đạo */
              medium: '#155E8A',    /* Xanh thép phụ trợ */
              light: '#EBF4FA',     /* Nền xanh nhạt nhẹ mắt */
              accent: '#E67E22',    /* Cam đồng điểm nhấn theo Logo */
              accentDark: '#C96814' /* Cam đậm khi hover */
            }
          }
        }
      }
    };
  </script>

  <style>
    /* Thiết lập chống tràn viền tuyệt đối và mượt mà trên mọi thiết bị */
    *, *::before, *::after {
      box-sizing: border-box;
    }
    html, body {
      margin: 0;
      padding: 0;
      width: 100%;
      max-width: 100%;
      overflow-x: hidden;
      font-family: 'Inter', sans-serif;
      color: #1F2937;
      background-color: #FFFFFF;
      scroll-behavior: smooth;
    }

    /* Chiều ngang giao diện trên máy tính bằng đúng 95% kích thước màn hình */
    .container-95 {
      width: 100%;
      padding-left: 12px;
      padding-right: 12px;
      margin-left: auto;
      margin-right: auto;
    }
    @media (min-width: 768px) {
      .container-95 {
        width: 95%;
        max-width: 95vw;
        padding-left: 0;
        padding-right: 0;
      }
    }

    /* Tiêu đề Section chuẩn phong cách Flatsome (gạch ngang 2 bên / gạch chân) */
    .flatsome-heading {
      position: relative;
      display: flex;
      align-items: center;
      justify-content: center;
      gap: 12px;
      margin-bottom: 1.5rem;
    }
    .flatsome-heading::before,
    .flatsome-heading::after {
      content: "";
      flex: 1;
      height: 1.5px;
      background-color: #D1DCE5;
      max-width: 180px;
    }

    /* Dropdown Menu chuẩn Flatsome */
    .nav-dropdown {
      opacity: 0;
      visibility: hidden;
      transform: translateY(8px);
      transition: all 0.2s ease;
    }
    .nav-item:hover .nav-dropdown,
    .nav-item:focus-within .nav-dropdown {
      opacity: 1;
      visibility: visible;
      transform: translateY(0);
    }

    /* Hiệu ứng mượt cho Banner tự trượt kích thước bằng nhau */
    .banner-grid-stack {
      display: grid;
      grid-template-columns: 1fr;
    }
    .banner-slide {
      grid-area: 1 / 1 / 2 / 2;
      transition: opacity 0.65s ease, visibility 0.65s ease;
      opacity: 0;
      visibility: hidden;
      pointer-events: none;
    }
    .banner-slide.active {
      opacity: 1;
      visibility: visible;
      pointer-events: auto;
      z-index: 10;
    }

    /* Hiệu ứng rung nhẹ cho nút Hotline nổi */
    @keyframes pulseRing {
      0% { transform: scale(0.95); box-shadow: 0 0 0 0 rgba(230, 126, 34, 0.65); }
      70% { transform: scale(1); box-shadow: 0 0 0 12px rgba(230, 126, 34, 0); }
      100% { transform: scale(0.95); box-shadow: 0 0 0 0 rgba(230, 126, 34, 0); }
    }
    .hotline-pulse {
      animation: pulseRing 2s infinite;
    }

    /* Tối ưu ảnh không bị méo */
    .img-cover {
      width: 100%;
      height: 100%;
      object-fit: cover;
      display: block;
    }
  </style>
</head>
<body class="bg-white text-gray-800 antialiased">

  <!-- ===================================================================== -->
  <!-- FLATSOME TOP BAR (Thông tin nhanh, không hiển thị thanh UX Builder)   -->
  <!-- ===================================================================== -->
  <div class="bg-brand-dark text-white text-[11px] sm:text-xs py-2 border-b border-white/10">
    <div class="container-95 flex flex-wrap items-center justify-between gap-2">
      <div class="flex items-center gap-3 sm:gap-5 flex-wrap">
        <span class="inline-flex items-center gap-1.5">
          <i class="fa-solid fa-location-dot text-brand-accent"></i>
          <span>Tp. Đà Nẵng</span>
        </span>
        <span class="hidden sm:inline-flex items-center gap-1.5">
          <i class="fa-regular fa-clock text-brand-accent"></i>
          <span>Tư vấn &amp; Khảo sát 24/7</span>
        </span>
      </div>
      <div class="flex items-center gap-3 sm:gap-5">
        <a href="tel:0905192439" class="inline-flex items-center gap-1.5 font-semibold hover:text-brand-accent transition-colors">
          <i class="fa-solid fa-phone-volume text-brand-accent"></i>
          <span>0905.192.439</span>
        </a>
        <span class="hidden md:inline-flex items-center gap-1.5 text-white/85">
          <i class="fa-solid fa-globe text-brand-accent"></i>
          <span>nhomkinhphuoctrung.com</span>
        </span>
      </div>
    </div>
  </div>

  <!-- ===================================================================== -->
  <!-- FLATSOME HEADER (Logo gọn nhỏ + Menu 1 hàng chuẩn desktop, không nút gọi ngay) -->
  <!-- ===================================================================== -->
  <header id="site-header" class="sticky top-0 z-40 bg-white/95 backdrop-blur-md shadow-sm border-b border-gray-200">
    <div class="container-95 py-2.5 flex items-center justify-between gap-3">

      <!-- Logo chuyên nghiệp chỉnh gọn nhỏ -->
      <a href="#trang-chu" class="flex items-center gap-2 shrink-0 group focus:outline-none" aria-label="Nhôm Kính Phước Trung">
        <svg class="w-9 h-9 sm:w-10 sm:h-10 shrink-0" viewBox="0 0 64 64" fill="none" xmlns="http://www.w3.org/2000/svg">
          <rect width="64" height="64" rx="12" fill="#0B3C5D" />
          <!-- Khung cửa nhôm kiến trúc cách điệu chữ P-T -->
          <rect x="11" y="11" width="19" height="42" rx="2.5" stroke="#FFFFFF" stroke-width="3.5" />
          <line x1="20.5" y1="11" x2="20.5" y2="53" stroke="#38BDF8" stroke-width="2" stroke-opacity="0.7" />
          <rect x="34" y="11" width="19" height="24" rx="2.5" fill="#E67E22" />
          <path d="M38 19L49 19M43.5 19L43.5 30" stroke="#FFFFFF" stroke-width="3" stroke-linecap="round" />
          <rect x="34" y="39" width="19" height="14" rx="2.5" fill="#155E8A" stroke="#7DD3FC" stroke-width="2" />
        </svg>
        <div class="leading-tight">
          <div class="text-[13px] sm:text-[15px] font-extrabold tracking-tight text-brand-primary group-hover:text-brand-medium transition-colors whitespace-nowrap">
            NHÔM KÍNH <span class="text-brand-accent">PHƯỚC TRUNG</span>
          </div>
          <div class="text-[9px] sm:text-[10px] font-medium tracking-wider text-gray-500 uppercase whitespace-nowrap">
            nhomkinhphuoctrung.com
          </div>
        </div>
      </a>

      <!-- Menu trên máy tính: chữ nhỏ gọn, viết liền không xuống dòng tên danh mục -->
      <nav aria-label="Danh mục chính" class="hidden lg:flex items-center flex-wrap justify-end gap-x-0.5 xl:gap-x-1.5 gap-y-1">
        <a href="#trang-chu" class="whitespace-nowrap px-2 xl:px-2.5 py-2 text-[11.5px] xl:text-[12.5px] font-semibold uppercase tracking-tight text-brand-primary hover:text-brand-accent transition-colors rounded-md">
          Trang chủ
        </a>
        <a href="#gioi-thieu" class="whitespace-nowrap px-2 xl:px-2.5 py-2 text-[11.5px] xl:text-[12.5px] font-semibold uppercase tracking-tight text-gray-700 hover:text-brand-accent transition-colors rounded-md">
          Giới thiệu
        </a>

        <!-- Dropdown: Cửa nhôm xingfa -->
        <div class="relative nav-item">
          <a href="#san-pham-xingfa" class="whitespace-nowrap inline-flex items-center gap-1 px-2 xl:px-2.5 py-2 text-[11.5px] xl:text-[12.5px] font-semibold uppercase tracking-tight text-gray-700 hover:text-brand-accent transition-colors rounded-md">
            <span>Cửa nhôm xingfa</span>
            <i class="fa-solid fa-chevron-down text-[9px]"></i>
          </a>
          <div class="nav-dropdown absolute left-0 top-full pt-1 w-56 z-50">
            <ul class="bg-white rounded-lg shadow-xl border border-gray-100 py-1.5 text-[12.5px] font-medium text-gray-700">
              <li><a href="#san-pham-xingfa" onclick="filterProducts('1-canh')" class="block px-4 py-2 hover:bg-brand-light hover:text-brand-primary transition-colors">Cửa nhôm xingfa 1 cánh</a></li>
              <li><a href="#san-pham-xingfa" onclick="filterProducts('2-canh')" class="block px-4 py-2 hover:bg-brand-light hover:text-brand-primary transition-colors">Cửa nhôm xingfa 2 cánh</a></li>
              <li><a href="#san-pham-xingfa" onclick="filterProducts('3-canh')" class="block px-4 py-2 hover:bg-brand-light hover:text-brand-primary transition-colors">Cửa nhôm xingfa 3 cánh</a></li>
              <li><a href="#san-pham-xingfa" onclick="filterProducts('4-canh')" class="block px-4 py-2 hover:bg-brand-light hover:text-brand-primary transition-colors">Cửa nhôm xingfa 4 cánh</a></li>
              <li><a href="#san-pham-xingfa" onclick="filterProducts('5-canh')" class="block px-4 py-2 hover:bg-brand-light hover:text-brand-primary transition-colors">Cửa nhôm xingfa 5 cánh</a></li>
            </ul>
          </div>
        </div>

        <a href="#danh-muc-san-pham" class="whitespace-nowrap px-2 xl:px-2.5 py-2 text-[11.5px] xl:text-[12.5px] font-semibold uppercase tracking-tight text-gray-700 hover:text-brand-accent transition-colors rounded-md">
          Cửa kính cường lực
        </a>

        <!-- Dropdown: Sản phẩm -->
        <div class="relative nav-item">
          <a href="#danh-muc-san-pham" class="whitespace-nowrap inline-flex items-center gap-1 px-2 xl:px-2.5 py-2 text-[11.5px] xl:text-[12.5px] font-semibold uppercase tracking-tight text-gray-700 hover:text-brand-accent transition-colors rounded-md">
            <span>Sản phẩm</span>
            <i class="fa-solid fa-chevron-down text-[9px]"></i>
          </a>
          <div class="nav-dropdown absolute left-0 top-full pt-1 w-52 z-50">
            <ul class="bg-white rounded-lg shadow-xl border border-gray-100 py-1.5 text-[12.5px] font-medium text-gray-700">
              <li><a href="#san-pham-xingfa" class="block px-4 py-2 hover:bg-brand-light hover:text-brand-primary transition-colors">Cửa nhôm xingfa</a></li>
              <li><a href="#danh-muc-san-pham" class="block px-4 py-2 hover:bg-brand-light hover:text-brand-primary transition-colors">Cửa nhựa lõi thép</a></li>
              <li><a href="#danh-muc-san-pham" class="block px-4 py-2 hover:bg-brand-light hover:text-brand-primary transition-colors">Cửa kính tự động</a></li>
              <li><a href="#danh-muc-san-pham" class="block px-4 py-2 hover:bg-brand-light hover:text-brand-primary transition-colors">Cầu thang kính</a></li>
              <li><a href="#danh-muc-san-pham" class="block px-4 py-2 hover:bg-brand-light hover:text-brand-primary transition-colors">Kính ốp bếp</a></li>
              <li><a href="#danh-muc-san-pham" class="block px-4 py-2 hover:bg-brand-light hover:text-brand-primary transition-colors">Phòng tắm kính</a></li>
            </ul>
          </div>
        </div>

        <a href="#cong-trinh" class="whitespace-nowrap px-2 xl:px-2.5 py-2 text-[11.5px] xl:text-[12.5px] font-semibold uppercase tracking-tight text-gray-700 hover:text-brand-accent transition-colors rounded-md">
          Công trình
        </a>
        <a href="#bao-gia" class="whitespace-nowrap px-2 xl:px-2.5 py-2 text-[11.5px] xl:text-[12.5px] font-semibold uppercase tracking-tight text-gray-700 hover:text-brand-accent transition-colors rounded-md">
          Báo giá
        </a>
        <a href="#tin-tuc" class="whitespace-nowrap px-2 xl:px-2.5 py-2 text-[11.5px] xl:text-[12.5px] font-semibold uppercase tracking-tight text-gray-700 hover:text-brand-accent transition-colors rounded-md">
          Tin tức
        </a>
        <a href="#lien-he" class="whitespace-nowrap px-2 xl:px-2.5 py-2 text-[11.5px] xl:text-[12.5px] font-semibold uppercase tracking-tight text-gray-700 hover:text-brand-accent transition-colors rounded-md">
          Liên hệ
        </a>
      </nav>

      <!-- Nút mở menu trên điện thoại & máy tính bảng -->
      <button id="mobile-menu-btn" type="button" onclick="toggleMobileMenu()" aria-label="Mở danh mục" class="lg:hidden inline-flex items-center justify-center w-10 h-10 rounded-lg border border-gray-200 text-brand-primary hover:bg-brand-light transition-colors">
        <i class="fa-solid fa-bars text-lg"></i>
      </button>
    </div>

    <!-- Menu Drawer trên điện thoại (đẹp, gọn, có danh mục con thả xuống) -->
    <div id="mobile-menu" class="hidden lg:hidden bg-white border-t border-gray-200 shadow-lg max-h-[80vh] overflow-y-auto">
      <div class="container-95 py-3 flex flex-col divide-y divide-gray-100 text-[13.5px] font-semibold text-gray-800">
        <a href="#trang-chu" onclick="closeMobileMenu()" class="py-2.5 px-2 text-brand-primary">Trang chủ</a>
        <a href="#gioi-thieu" onclick="closeMobileMenu()" class="py-2.5 px-2 hover:text-brand-accent">Giới thiệu</a>

        <!-- Accordion: Cửa nhôm xingfa -->
        <div class="py-1">
          <button type="button" onclick="toggleSubmenu('mob-sub-xingfa', this)" class="w-full flex items-center justify-between py-2 px-2 text-left hover:text-brand-accent">
            <span>Cửa nhôm xingfa</span>
            <i class="fa-solid fa-chevron-down text-xs transition-transform"></i>
          </button>
          <div id="mob-sub-xingfa" class="hidden pl-5 pb-2 space-y-1.5 text-[13px] font-medium text-gray-600">
            <a href="#san-pham-xingfa" onclick="filterProducts('1-canh'); closeMobileMenu();" class="block py-1 hover:text-brand-primary">+ Cửa nhôm xingfa 1 cánh</a>
            <a href="#san-pham-xingfa" onclick="filterProducts('2-canh'); closeMobileMenu();" class="block py-1 hover:text-brand-primary">+ Cửa nhôm xingfa 2 cánh</a>
            <a href="#san-pham-xingfa" onclick="filterProducts('3-canh'); closeMobileMenu();" class="block py-1 hover:text-brand-primary">+ Cửa nhôm xingfa 3 cánh</a>
            <a href="#san-pham-xingfa" onclick="filterProducts('4-canh'); closeMobileMenu();" class="block py-1 hover:text-brand-primary">+ Cửa nhôm xingfa 4 cánh</a>
            <a href="#san-pham-xingfa" onclick="filterProducts('5-canh'); closeMobileMenu();" class="block py-1 hover:text-brand-primary">+ Cửa nhôm xingfa 5 cánh</a>
          </div>
        </div>

        <a href="#danh-muc-san-pham" onclick="closeMobileMenu()" class="py-2.5 px-2 hover:text-brand-accent">Cửa kính cường lực</a>

        <!-- Accordion: Sản phẩm -->
        <div class="py-1">
          <button type="button" onclick="toggleSubmenu('mob-sub-sp', this)" class="w-full flex items-center justify-between py-2 px-2 text-left hover:text-brand-accent">
            <span>Sản phẩm</span>
            <i class="fa-solid fa-chevron-down text-xs transition-transform"></i>
          </button>
          <div id="mob-sub-sp" class="hidden pl-5 pb-2 space-y-1.5 text-[13px] font-medium text-gray-600">
            <a href="#san-pham-xingfa" onclick="closeMobileMenu()" class="block py-1 hover:text-brand-primary">+ Cửa nhôm xingfa</a>
            <a href="#danh-muc-san-pham" onclick="closeMobileMenu()" class="block py-1 hover:text-brand-primary">+ Cửa nhựa lõi thép</a>
            <a href="#danh-muc-san-pham" onclick="closeMobileMenu()" class="block py-1 hover:text-brand-primary">+ Cửa kính tự động</a>
            <a href="#danh-muc-san-pham" onclick="closeMobileMenu()" class="block py-1 hover:text-brand-primary">+ Cầu thang kính</a>
            <a href="#danh-muc-san-pham" onclick="closeMobileMenu()" class="block py-1 hover:text-brand-primary">+ Kính ốp bếp</a>
            <a href="#danh-muc-san-pham" onclick="closeMobileMenu()" class="block py-1 hover:text-brand-primary">+ Phòng tắm kính</a>
          </div>
        </div>

        <a href="#cong-trinh" onclick="closeMobileMenu()" class="py-2.5 px-2 hover:text-brand-accent">Công trình</a>
        <a href="#bao-gia" onclick="closeMobileMenu()" class="py-2.5 px-2 hover:text-brand-accent">Báo giá</a>
        <a href="#tin-tuc" onclick="closeMobileMenu()" class="py-2.5 px-2 hover:text-brand-accent">Tin tức</a>
        <a href="#lien-he" onclick="closeMobileMenu()" class="py-2.5 px-2 hover:text-brand-accent">Liên hệ</a>
      </div>
    </div>
  </header>

  <main id="trang-chu" class="w-full overflow-x-hidden">

    <!-- ===================================================================== -->
    <!-- FLATSOME SECTION 1: 2 BANNER TỰ TRƯỢT KÍCH THƯỚC BẰNG NHAU            -->
    <!-- Thiết kế an toàn: chữ cách xa viền, không mất chữ trên mobile/desktop -->
    <!-- ===================================================================== -->
    <section class="pt-3 pb-4 sm:pt-4 sm:pb-6 bg-gray-50">
      <div class="container-95">
        <div id="hero-slider" class="relative rounded-2xl overflow-hidden shadow-md bg-brand-primary">

          <div class="banner-grid-stack">
            <!-- BANNER 1 -->
            <div class="banner-slide active bg-gradient-to-br from-brand-dark via-brand-primary to-brand-medium text-white">
              <div class="w-full h-full px-8 sm:px-14 md:px-20 py-9 sm:py-12 md:py-16 grid grid-cols-1 md:grid-cols-12 gap-6 md:gap-8 items-center">
                <!-- Nội dung chữ nằm gọn bên trong, cách xa viền -->
                <div class="md:col-span-7 space-y-3 sm:space-y-4">
                  <p class="text-[11px] sm:text-xs font-semibold uppercase tracking-widest text-sky-300">
                    NHÔM KÍNH PHƯỚC TRUNG • TP. ĐÀ NẴNG
                  </p>
                  <h1 class="text-xl sm:text-3xl lg:text-4xl font-extrabold leading-tight text-white">
                    CỬA NHÔM XINGFA NHẬP KHẨU &amp; KÍNH CƯỜNG LỰC CAO CẤP
                  </h1>
                  <p class="text-xs sm:text-sm md:text-base text-white/90 leading-relaxed max-w-xl">
                    Chuyên sản xuất, thi công trọn gói cửa nhôm Xingfa tem đỏ Quảng Đông, cửa kính cường lực, cầu thang kính, phòng tắm kính chuẩn kỹ thuật – thẩm mỹ bền đẹp theo thời gian.
                  </p>
                  <div class="pt-2 flex flex-wrap items-center gap-3">
                    <a href="#bao-gia-form" class="inline-flex items-center gap-2 px-5 py-2.5 rounded-lg bg-brand-accent hover:bg-brand-accentDark text-white text-xs sm:text-sm font-bold shadow transition-colors">
                      <i class="fa-solid fa-file-invoice-dollar"></i>
                      <span>Nhận báo giá ngay</span>
                    </a>
                    <a href="#san-pham-xingfa" class="inline-flex items-center gap-2 px-5 py-2.5 rounded-lg bg-white/15 hover:bg-white/25 text-white border border-white/30 text-xs sm:text-sm font-semibold transition-colors">
                      <span>Xem mẫu cửa</span>
                    </a>
                  </div>
                </div>
                <!-- Hình ảnh minh họa nằm gọn trong khung banner -->
                <div class="md:col-span-5 flex justify-center">
                  <div class="w-full max-w-[360px] aspect-[16/10] rounded-xl overflow-hidden border-2 border-white/25 shadow-lg bg-brand-dark">
                    <img
                      data-drive-id="1lxzMKWX3e_HJn7UELFZDOURuxh-NYZg-"
                      alt="Cửa đi quay mở 4 cánh nhôm Xingfa Phước Trung"
                      class="img-cover"
                    />
                  </div>
                </div>
              </div>
            </div>

            <!-- BANNER 2 -->
            <div class="banner-slide bg-gradient-to-br from-[#0A304A] via-[#0F4970] to-[#1A6596] text-white">
              <div class="w-full h-full px-8 sm:px-14 md:px-20 py-9 sm:py-12 md:py-16 grid grid-cols-1 md:grid-cols-12 gap-6 md:gap-8 items-center">
                <!-- Nội dung chữ nằm gọn bên trong, cách xa viền -->
                <div class="md:col-span-7 space-y-3 sm:space-y-4">
                  <p class="text-[11px] sm:text-xs font-semibold uppercase tracking-widest text-amber-300">
                    ƯU ĐÃI THI CÔNG TRỌN GÓI TẠI ĐÀ NẴNG
                  </p>
                  <h2 class="text-xl sm:text-3xl lg:text-4xl font-extrabold leading-tight text-white">
                    GIẢM GIÁ ĐẾN 20% CHI PHÍ LẮP ĐẶT CÔNG TRÌNH MỚI
                  </h2>
                  <p class="text-xs sm:text-sm md:text-base text-white/90 leading-relaxed max-w-xl">
                    Đo đạc khảo sát tận nơi miễn phí tại Đà Nẵng. Phụ kiện Kinlong đồng bộ chính hãng, bảo hành dài hạn, đội ngũ kỹ thuật tay nghề cao bàn giao đúng tiến độ.
                  </p>
                  <div class="pt-2 flex flex-wrap items-center gap-3">
                    <a href="tel:0905192439" class="inline-flex items-center gap-2 px-5 py-2.5 rounded-lg bg-brand-accent hover:bg-brand-accentDark text-white text-xs sm:text-sm font-bold shadow transition-colors">
                      <i class="fa-solid fa-phone"></i>
                      <span>Tư vấn: 0905.192.439</span>
                    </a>
                    <a href="#cong-trinh" class="inline-flex items-center gap-2 px-5 py-2.5 rounded-lg bg-white/15 hover:bg-white/25 text-white border border-white/30 text-xs sm:text-sm font-semibold transition-colors">
                      <span>Xem dự án thực tế</span>
                    </a>
                  </div>
                </div>
                <!-- Hình ảnh công trình thực tế nằm gọn trong banner -->
                <div class="md:col-span-5 flex justify-center">
                  <div class="w-full max-w-[360px] aspect-[16/10] rounded-xl overflow-hidden border-2 border-white/25 shadow-lg bg-brand-dark">
                    <img
                      data-drive-id="1MmAfsyp3s3YCaEMymrkk8TZbD38jCsAQ"
                      alt="Dự án thi công Nhôm Kính Phước Trung Đà Nẵng"
                      class="img-cover"
                    />
                  </div>
                </div>
              </div>
            </div>
          </div>

          <!-- Nút điều hướng đặt sát mép ngoài an toàn, không đè chữ -->
          <button type="button" onclick="prevSlide()" aria-label="Banner trước" class="absolute left-2 sm:left-3 top-1/2 -translate-y-1/2 z-20 w-7 h-7 sm:w-9 sm:h-9 rounded-full bg-black/30 hover:bg-brand-accent text-white flex items-center justify-center transition-colors">
            <i class="fa-solid fa-chevron-left text-xs sm:text-sm"></i>
          </button>
          <button type="button" onclick="nextSlide()" aria-label="Banner tiếp theo" class="absolute right-2 sm:right-3 top-1/2 -translate-y-1/2 z-20 w-7 h-7 sm:w-9 sm:h-9 rounded-full bg-black/30 hover:bg-brand-accent text-white flex items-center justify-center transition-colors">
            <i class="fa-solid fa-chevron-right text-xs sm:text-sm"></i>
          </button>

          <!-- Chấm chỉ báo Slide -->
          <div class="absolute bottom-3 left-1/2 -translate-x-1/2 z-20 flex items-center gap-2">
            <button type="button" onclick="goToSlide(0)" class="slider-dot w-6 h-2 rounded-full bg-brand-accent transition-all" aria-label="Slide 1"></button>
            <button type="button" onclick="goToSlide(1)" class="slider-dot w-2 h-2 rounded-full bg-white/50 hover:bg-white transition-all" aria-label="Slide 2"></button>
          </div>
        </div>
      </div>
    </section>

    <!-- ===================================================================== -->
    <!-- FLATSOME SECTION 2: GIỚI THIỆU NHÔM KÍNH PHƯỚC TRUNG & CAM KẾT        -->
    <!-- ===================================================================== -->
    <section id="gioi-thieu" class="py-8 sm:py-10 bg-white">
      <div class="container-95">
        <div class="grid grid-cols-1 lg:grid-cols-12 gap-6 items-center">
          <div class="lg:col-span-7 space-y-3">
            <h2 class="text-lg sm:text-2xl font-extrabold text-brand-primary uppercase">
              NHÔM KÍNH PHƯỚC TRUNG – CỬA ĐẸP CHO MỌI CÔNG TRÌNH ĐÀ NẴNG
            </h2>
            <p class="text-sm text-gray-600 leading-relaxed">
              <strong>Nhôm Kính Phước Trung</strong> là đơn vị uy tín chuyên tư vấn, thiết kế, gia công và lắp đặt trọn gói các hạng mục nhôm kính tại <strong>TP. Đà Nẵng</strong> và khu vực miền Trung. Các dòng sản phẩm chủ lực bao gồm: Cửa nhôm Xingfa nhập khẩu tem đỏ, Cửa kính cường lực, Cửa nhựa lõi thép, Cửa kính tự động, Cầu thang kính, Kính ốp bếp và Phòng tắm kính.
            </p>
            <p class="text-sm text-gray-600 leading-relaxed">
              Với phương châm <em>“Chất lượng tạo niềm tin – Thẩm mỹ bền vững”</em>, Phước Trung cam kết vật tư chính hãng, giá xuất xưởng minh bạch, thi công tỉ mỉ và chế độ bảo hành chu đáo cho nhà phố, biệt thự, khách sạn và resort.
            </p>
          </div>

          <!-- Thống kê 4 ô chuẩn Flatsome -->
          <div class="lg:col-span-5 grid grid-cols-2 gap-3">
            <div class="p-4 rounded-xl bg-brand-light border border-brand-primary/10 text-center">
              <div class="text-2xl sm:text-3xl font-extrabold text-brand-primary">150+</div>
              <div class="text-xs font-medium text-gray-600 mt-1">Dự án hoàn thành</div>
            </div>
            <div class="p-4 rounded-xl bg-brand-light border border-brand-primary/10 text-center">
              <div class="text-2xl sm:text-3xl font-extrabold text-brand-accent">50+</div>
              <div class="text-xs font-medium text-gray-600 mt-1">Thợ kỹ thuật lành nghề</div>
            </div>
            <div class="p-4 rounded-xl bg-brand-light border border-brand-primary/10 text-center">
              <div class="text-2xl sm:text-3xl font-extrabold text-brand-primary">100+</div>
              <div class="text-xs font-medium text-gray-600 mt-1">Mẫu cửa chất lượng</div>
            </div>
            <div class="p-4 rounded-xl bg-brand-light border border-brand-primary/10 text-center">
              <div class="text-2xl sm:text-3xl font-extrabold text-brand-accent">100%</div>
              <div class="text-xs font-medium text-gray-600 mt-1">Khách hàng hài lòng</div>
            </div>
          </div>
        </div>
      </div>
    </section>

    <!-- ===================================================================== -->
    <!-- FLATSOME SECTION 3: DANH MỤC SẢN PHẨM NỔI BẬT (Chữ nhỏ gọn, dễ nhìn)   -->
    <!-- ===================================================================== -->
    <section id="danh-muc-san-pham" class="py-8 sm:py-10 bg-gray-50 border-y border-gray-100">
      <div class="container-95">
        <div class="flatsome-heading">
          <h2 class="text-base sm:text-xl font-extrabold text-brand-primary uppercase text-center tracking-tight">
            DANH MỤC SẢN PHẨM NỔI BẬT
          </h2>
        </div>

        <!-- 2 cột trên mobile, 3 cột tablet, 6 cột desktop -->
        <div class="grid grid-cols-2 sm:grid-cols-3 lg:grid-cols-6 gap-3 sm:gap-4" id="category-grid">
          <!-- Danh mục được render từ JS với đúng link ảnh Drive -->
        </div>
      </div>
    </section>

    <!-- ===================================================================== -->
    <!-- FLATSOME SECTION 4: SẢN PHẨM CỬA NHÔM XINGFA                          -->
    <!-- 2 cột trên điện thoại, giá & giảm giá % góc trên bên trái, không mất chữ -->
    <!-- ===================================================================== -->
    <section id="san-pham-xingfa" class="py-8 sm:py-12 bg-white">
      <div class="container-95">
        <div class="flatsome-heading">
          <h2 class="text-base sm:text-xl font-extrabold text-brand-primary uppercase text-center tracking-tight">
            SẢN PHẨM CỬA NHÔM XINGFA ĐÀ NẴNG
          </h2>
        </div>

        <!-- Bộ lọc nhanh đơn giản (chuẩn UX Builder Tabs) -->
        <div class="flex flex-wrap items-center justify-center gap-2 mb-6">
          <button type="button" onclick="filterProducts('all')" data-filter="all" class="filter-btn px-3.5 py-1.5 rounded-lg text-xs font-semibold bg-brand-primary text-white transition-colors">
            Tất cả mẫu cửa
          </button>
          <button type="button" onclick="filterProducts('1-canh')" data-filter="1-canh" class="filter-btn px-3.5 py-1.5 rounded-lg text-xs font-semibold bg-gray-100 text-gray-700 hover:bg-brand-light hover:text-brand-primary transition-colors">
            Xingfa 1 cánh
          </button>
          <button type="button" onclick="filterProducts('2-canh')" data-filter="2-canh" class="filter-btn px-3.5 py-1.5 rounded-lg text-xs font-semibold bg-gray-100 text-gray-700 hover:bg-brand-light hover:text-brand-primary transition-colors">
            Xingfa 2 cánh
          </button>
          <button type="button" onclick="filterProducts('3-canh')" data-filter="3-canh" class="filter-btn px-3.5 py-1.5 rounded-lg text-xs font-semibold bg-gray-100 text-gray-700 hover:bg-brand-light hover:text-brand-primary transition-colors">
            Xingfa 3 cánh
          </button>
          <button type="button" onclick="filterProducts('4-canh')" data-filter="4-canh" class="filter-btn px-3.5 py-1.5 rounded-lg text-xs font-semibold bg-gray-100 text-gray-700 hover:bg-brand-light hover:text-brand-primary transition-colors">
            Xingfa 4 cánh
          </button>
          <button type="button" onclick="filterProducts('5-canh')" data-filter="5-canh" class="filter-btn px-3.5 py-1.5 rounded-lg text-xs font-semibold bg-gray-100 text-gray-700 hover:bg-brand-light hover:text-brand-primary transition-colors">
            Xếp trượt / 5 cánh
          </button>
        </div>

        <!-- Lưới sản phẩm: Đúng 2 cột trên điện thoại, 3 cột trên máy tính -->
        <div id="product-grid" class="grid grid-cols-2 md:grid-cols-3 gap-3 sm:gap-5">
          <!-- Sản phẩm render động từ mảng chuẩn xác -->
        </div>
      </div>
    </section>

    <!-- ===================================================================== -->
    <!-- FLATSOME SECTION 5: BẢNG BÁO GIÁ THAM KHẢO NHÔM XINGFA ĐÀ NẴNG         -->
    <!-- ===================================================================== -->
    <section id="bao-gia" class="py-8 sm:py-10 bg-brand-light/60 border-y border-gray-200/70">
      <div class="container-95">
        <div class="flatsome-heading">
          <h2 class="text-base sm:text-xl font-extrabold text-brand-primary uppercase text-center tracking-tight">
            BẢNG BÁO GIÁ CỬA NHÔM XINGFA ĐÀ NẴNG THAM KHẢO
          </h2>
        </div>

        <div class="bg-white rounded-xl shadow-sm border border-gray-200 overflow-hidden">
          <div class="overflow-x-auto">
            <table class="w-full text-left border-collapse text-xs sm:text-sm">
              <thead>
                <tr class="bg-brand-primary text-white">
                  <th class="py-3 px-3 sm:px-4 font-bold">STT</th>
                  <th class="py-3 px-3 sm:px-4 font-bold">Hạng mục cửa nhôm Xingfa hệ 55 / 93</th>
                  <th class="py-3 px-3 sm:px-4 font-bold">Đơn giá (VNĐ/m²)</th>
                  <th class="py-3 px-3 sm:px-4 font-bold hidden sm:table-cell">Ghi chú kỹ thuật</th>
                </tr>
              </thead>
              <tbody class="divide-y divide-gray-100">
                <tr class="hover:bg-gray-50">
                  <td class="py-2.5 px-3 sm:px-4 font-semibold text-gray-500">01</td>
                  <td class="py-2.5 px-3 sm:px-4 font-semibold text-gray-800">Cửa sổ mở hất / mở quay nhôm Xingfa hệ 55</td>
                  <td class="py-2.5 px-3 sm:px-4 font-bold text-brand-accent">1.650.000 ₫</td>
                  <td class="py-2.5 px-3 sm:px-4 text-gray-600 hidden sm:table-cell">Nhôm dày 1.4mm, kính cường lực 8mm</td>
                </tr>
                <tr class="hover:bg-gray-50">
                  <td class="py-2.5 px-3 sm:px-4 font-semibold text-gray-500">02</td>
                  <td class="py-2.5 px-3 sm:px-4 font-semibold text-gray-800">Cửa đi mở quay 1 cánh nhôm Xingfa</td>
                  <td class="py-2.5 px-3 sm:px-4 font-bold text-brand-accent">1.790.000 ₫</td>
                  <td class="py-2.5 px-3 sm:px-4 text-gray-600 hidden sm:table-cell">Nhôm hệ 55 dày 2.0mm, phụ kiện Kinlong</td>
                </tr>
                <tr class="hover:bg-gray-50">
                  <td class="py-2.5 px-3 sm:px-4 font-semibold text-gray-500">03</td>
                  <td class="py-2.5 px-3 sm:px-4 font-semibold text-gray-800">Cửa đi mở quay 2 cánh nhôm Xingfa</td>
                  <td class="py-2.5 px-3 sm:px-4 font-bold text-brand-accent">1.850.000 ₫</td>
                  <td class="py-2.5 px-3 sm:px-4 text-gray-600 hidden sm:table-cell">Nhôm hệ 55 dày 2.0mm, gioăng EPDM kín khít</td>
                </tr>
                <tr class="hover:bg-gray-50">
                  <td class="py-2.5 px-3 sm:px-4 font-semibold text-gray-500">04</td>
                  <td class="py-2.5 px-3 sm:px-4 font-semibold text-gray-800">Cửa đi mở quay 3 cánh / 4 cánh nhôm Xingfa</td>
                  <td class="py-2.5 px-3 sm:px-4 font-bold text-brand-accent">1.890.000 ₫</td>
                  <td class="py-2.5 px-3 sm:px-4 text-gray-600 hidden sm:table-cell">Chống chịu gió bão tốt, bản lề 3D/4D</td>
                </tr>
                <tr class="hover:bg-gray-50">
                  <td class="py-2.5 px-3 sm:px-4 font-semibold text-gray-500">05</td>
                  <td class="py-2.5 px-3 sm:px-4 font-semibold text-gray-800">Cửa đi xếp trượt nhôm Xingfa (4 – 5 – 6 cánh)</td>
                  <td class="py-2.5 px-3 sm:px-4 font-bold text-brand-accent">1.950.000 ₫</td>
                  <td class="py-2.5 px-3 sm:px-4 text-gray-600 hidden sm:table-cell">Hệ 63 chuyên dụng, mở rộng tối đa không gian</td>
                </tr>
              </tbody>
            </table>
          </div>
          <div class="px-4 py-3 bg-gray-50 border-t border-gray-100 flex flex-wrap items-center justify-between gap-2 text-xs text-gray-600">
            <span>* Giá trên mang tính tham khảo và đã bao gồm công lắp đặt hoàn thiện tại nội thành TP. Đà Nẵng.</span>
            <a href="#bao-gia-form" class="font-bold text-brand-primary hover:text-brand-accent underline">Gửi kích thước nhận báo giá chi tiết &rarr;</a>
          </div>
        </div>
      </div>
    </section>

    <!-- ===================================================================== -->
    <!-- FLATSOME SECTION 6: CÁC DỰ ÁN TIÊU BIỂU TẠI ĐÀ NẴNG                    -->
    <!-- ===================================================================== -->
    <section id="cong-trinh" class="py-8 sm:py-12 bg-white">
      <div class="container-95">
        <div class="flatsome-heading">
          <h2 class="text-base sm:text-xl font-extrabold text-brand-primary uppercase text-center tracking-tight">
            CÁC DỰ ÁN TIÊU BIỂU TẠI ĐÀ NẴNG
          </h2>
        </div>

        <div id="project-grid" class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-3 gap-4 sm:gap-5">
          <!-- 6 Dự án thực tế render từ JS với link Drive chính xác -->
        </div>
      </div>
    </section>

    <!-- ===================================================================== -->
    <!-- FLATSOME SECTION 7: DANH MỤC CÁC BÀI VIẾT & TIN TỨC TRANG CHỦ          -->
    <!-- ===================================================================== -->
    <section id="tin-tuc" class="py-8 sm:py-12 bg-gray-50 border-y border-gray-100">
      <div class="container-95">
        <div class="flatsome-heading">
          <h2 class="text-base sm:text-xl font-extrabold text-brand-primary uppercase text-center tracking-tight">
            TIN TỨC &amp; KINH NGHIỆM NHÔM KÍNH
          </h2>
        </div>

        <!-- Danh mục chủ đề bài viết gọn đẹp -->
        <div class="flex flex-wrap items-center justify-center gap-2 mb-6">
          <button type="button" onclick="filterPosts('all')" data-post-cat="all" class="post-cat-btn px-3 py-1.5 rounded-lg text-xs font-semibold bg-brand-primary text-white transition-colors">
            Tất cả bài viết
          </button>
          <button type="button" onclick="filterPosts('tu-van')" data-post-cat="tu-van" class="post-cat-btn px-3 py-1.5 rounded-lg text-xs font-semibold bg-white border border-gray-200 text-gray-700 hover:border-brand-primary hover:text-brand-primary transition-colors">
            Tư vấn chọn cửa
          </button>
          <button type="button" onclick="filterPosts('ky-thuat')" data-post-cat="ky-thuat" class="post-cat-btn px-3 py-1.5 rounded-lg text-xs font-semibold bg-white border border-gray-200 text-gray-700 hover:border-brand-primary hover:text-brand-primary transition-colors">
            Kỹ thuật nhôm Xingfa
          </button>
          <button type="button" onclick="filterPosts('kinh-noi-that')" data-post-cat="kinh-noi-that" class="post-cat-btn px-3 py-1.5 rounded-lg text-xs font-semibold bg-white border border-gray-200 text-gray-700 hover:border-brand-primary hover:text-brand-primary transition-colors">
            Kính nội thất &amp; Bếp
          </button>
        </div>

        <div id="blog-grid" class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-3 gap-4 sm:gap-5">
          <!-- Bài viết render từ JS -->
        </div>
      </div>
    </section>

    <!-- ===================================================================== -->
    <!-- FLATSOME SECTION 8: FORM YÊU CẦU BÁO GIÁ + GOOGLE MAP + FANPAGE       -->
    <!-- Đưa đầy đủ Form, Google Map Đà Nẵng và Fanpage ra ngoài trang chủ     -->
    <!-- ===================================================================== -->
    <section id="bao-gia-form" class="py-8 sm:py-12 bg-white">
      <div class="container-95">
        <div class="flatsome-heading">
          <h2 class="text-base sm:text-xl font-extrabold text-brand-primary uppercase text-center tracking-tight">
            YÊU CẦU BÁO GIÁ – BẢN ĐỒ &amp; KẾT NỐI FANPAGE
          </h2>
        </div>

        <div class="grid grid-cols-1 lg:grid-cols-12 gap-5 items-stretch">

          <!-- Cột 1: Form yêu cầu và báo giá -->
          <div class="lg:col-span-5 bg-brand-light/70 rounded-2xl p-5 sm:p-6 border border-brand-primary/15 flex flex-col justify-between">
            <div>
              <h3 class="text-base sm:text-lg font-extrabold text-brand-primary uppercase mb-1">
                Đăng ký nhận tư vấn &amp; báo giá
              </h3>
              <p class="text-xs sm:text-sm text-gray-600 mb-4">
                Để lại thông tin công trình, kỹ thuật viên Nhôm Kính Phước Trung sẽ liên hệ đo đạc và gửi bảng giá tốt nhất trong 15 phút.
              </p>

              <form id="quote-form" onsubmit="handleQuoteSubmit(event)" class="space-y-3">
                <div>
                  <label for="q-name" class="block text-xs font-semibold text-gray-700 mb-1">Họ và tên *</label>
                  <input id="q-name" type="text" required placeholder="Nhập họ tên của bạn" class="w-full px-3.5 py-2.5 rounded-lg border border-gray-300 bg-white text-sm focus:outline-none focus:border-brand-primary" />
                </div>
                <div class="grid grid-cols-1 sm:grid-cols-2 gap-3">
                  <div>
                    <label for="q-phone" class="block text-xs font-semibold text-gray-700 mb-1">Số điện thoại / Zalo *</label>
                    <input id="q-phone" type="tel" required placeholder="0905.xxx.xxx" class="w-full px-3.5 py-2.5 rounded-lg border border-gray-300 bg-white text-sm focus:outline-none focus:border-brand-primary" />
                  </div>
                  <div>
                    <label for="q-service" class="block text-xs font-semibold text-gray-700 mb-1">Hạng mục quan tâm</label>
                    <select id="q-service" class="w-full px-3 py-2.5 rounded-lg border border-gray-300 bg-white text-sm focus:outline-none focus:border-brand-primary">
                      <option value="Cửa nhôm Xingfa">Cửa nhôm Xingfa</option>
                      <option value="Cửa kính cường lực">Cửa kính cường lực</option>
                      <option value="Cửa nhựa lõi thép">Cửa nhựa lõi thép</option>
                      <option value="Cửa kính tự động">Cửa kính tự động</option>
                      <option value="Cầu thang kính">Cầu thang kính</option>
                      <option value="Kính ốp bếp">Kính ốp bếp</option>
                      <option value="Phòng tắm kính">Phòng tắm kính</option>
                    </select>
                  </div>
                </div>
                <div>
                  <label for="q-note" class="block text-xs font-semibold text-gray-700 mb-1">Kích thước dự kiến / Địa chỉ thi công</label>
                  <textarea id="q-note" rows="3" placeholder="Ví dụ: Lắp 1 bộ cửa đi 4 cánh nhôm Xingfa tại quận Hải Châu, Đà Nẵng..." class="w-full px-3.5 py-2 rounded-lg border border-gray-300 bg-white text-sm focus:outline-none focus:border-brand-primary"></textarea>
                </div>
                <button type="submit" class="w-full py-3 rounded-lg bg-brand-accent hover:bg-brand-accentDark text-white font-bold text-sm shadow transition-colors flex items-center justify-center gap-2">
                  <i class="fa-solid fa-paper-plane"></i>
                  <span>GỬI YÊU CẦU BÁO GIÁ MIỄN PHÍ</span>
                </button>
              </form>
            </div>
          </div>

          <!-- Cột 2: Bản đồ Google Map TP. Đà Nẵng ra ngoài trang chủ -->
          <div class="lg:col-span-4 bg-white rounded-2xl border border-gray-200 overflow-hidden shadow-sm flex flex-col">
            <div class="px-4 py-3 bg-brand-primary text-white flex items-center justify-between">
              <div class="flex items-center gap-2 text-xs sm:text-sm font-bold">
                <i class="fa-solid fa-map-location-dot text-brand-accent"></i>
                <span>Bản đồ chỉ đường – Tp. Đà Nẵng</span>
              </div>
              <a href="https://maps.google.com/?q=Da+Nang,Vietnam" target="_blank" rel="noopener noreferrer" class="text-[11px] text-sky-200 hover:text-white underline">
                Mở bản đồ lớn
              </a>
            </div>
            <div class="flex-1 min-h-[270px] w-full bg-gray-100 relative">
              <iframe
                title="Bản đồ Nhôm Kính Phước Trung TP. Đà Nẵng"
                src="https://www.google.com/maps?q=Da+Nang,+Vietnam&output=embed"
                class="w-full h-full min-h-[270px] border-0"
                loading="lazy"
                referrerpolicy="no-referrer-when-downgrade"
              ></iframe>
            </div>
            <div class="px-4 py-2.5 bg-gray-50 border-t border-gray-100 text-xs text-gray-600 flex items-center justify-between gap-2">
              <span><i class="fa-solid fa-location-dot text-brand-accent mr-1"></i>Tp. Đà Nẵng</span>
              <a href="tel:0905192439" class="font-bold text-brand-primary">0905.192.439</a>
            </div>
          </div>

          <!-- Cột 3: Fanpage Facebook ra ngoài trang chủ -->
          <div class="lg:col-span-3 bg-white rounded-2xl border border-gray-200 overflow-hidden shadow-sm flex flex-col">
            <div class="px-4 py-3 bg-[#1877F2] text-white flex items-center gap-2 text-xs sm:text-sm font-bold">
              <i class="fa-brands fa-facebook text-base"></i>
              <span>Fanpage Facebook</span>
            </div>

            <!-- Giao diện thẻ Fanpage trực quan, gọn đẹp, luôn hiển thị ổn định -->
            <div class="p-4 flex-1 flex flex-col justify-between bg-gradient-to-b from-blue-50/60 to-white">
              <div>
                <!-- Ảnh bìa Fanpage -->
                <div class="relative rounded-xl overflow-hidden h-28 bg-brand-primary mb-3">
                  <img
                    data-drive-id="1wH-JJ2rOYRmDGsNapl3bIBjfiG3Qm6zZ"
                    alt="Fanpage Nhôm Kính Phước Trung Đà Nẵng"
                    class="img-cover opacity-80"
                  />
                  <div class="absolute inset-0 bg-gradient-to-t from-black/75 via-black/25 to-transparent p-3 flex items-end gap-2.5">
                    <div class="w-11 h-11 rounded-lg bg-brand-primary border-2 border-white flex items-center justify-center shrink-0 shadow">
                      <span class="text-white font-extrabold text-sm">PT</span>
                    </div>
                    <div class="text-white leading-tight min-w-0">
                      <div class="font-bold text-xs sm:text-sm truncate">Nhôm Kính Phước Trung</div>
                      <div class="text-[11px] text-white/85">TP. Đà Nẵng • 4.9 ★</div>
                    </div>
                  </div>
                </div>

                <p class="text-xs text-gray-600 leading-relaxed mb-3">
                  Theo dõi Fanpage chính thức của <strong>Nhôm Kính Phước Trung</strong> để xem cập nhật công trình mới nhất mỗi ngày và nhận ưu đãi thi công tại Đà Nẵng.
                </p>

                <div class="flex items-center gap-2 text-[11px] text-gray-500 mb-4">
                  <span class="inline-flex items-center gap-1 bg-gray-100 px-2 py-1 rounded-md">
                    <i class="fa-solid fa-thumbs-up text-[#1877F2]"></i> 3.8K lượt thích
                  </span>
                  <span class="inline-flex items-center gap-1 bg-gray-100 px-2 py-1 rounded-md">
                    <i class="fa-solid fa-message text-brand-primary"></i> Phản hồi nhanh
                  </span>
                </div>
              </div>

              <div class="grid grid-cols-2 gap-2">
                <a href="https://www.facebook.com/" target="_blank" rel="noopener noreferrer" class="py-2 px-3 rounded-lg bg-[#1877F2] hover:bg-blue-700 text-white text-xs font-bold text-center transition-colors">
                  <i class="fa-brands fa-facebook-f mr-1"></i>Thích Trang
                </a>
                <a href="https://zalo.me/0905192439" target="_blank" rel="noopener noreferrer" class="py-2 px-3 rounded-lg bg-brand-primary hover:bg-brand-dark text-white text-xs font-bold text-center transition-colors">
                  <i class="fa-solid fa-comments mr-1"></i>Nhắn tin
                </a>
              </div>
            </div>
          </div>

        </div>
      </div>
    </section>

    <!-- ===================================================================== -->
    <!-- FLATSOME SECTION 9: ĐỐI TÁC CỦA CHÚNG TÔI (6 Logo từ Google Drive)     -->
    <!-- ===================================================================== -->
    <section class="py-8 sm:py-10 bg-gray-50 border-t border-gray-100">
      <div class="container-95">
        <div class="flatsome-heading">
          <h2 class="text-base sm:text-xl font-extrabold text-brand-primary uppercase text-center tracking-tight">
            ĐỐI TÁC CUNG CẤP VẬT TƯ CHÍNH HÃNG
          </h2>
        </div>

        <div id="partner-grid" class="grid grid-cols-2 sm:grid-cols-3 lg:grid-cols-6 gap-3 sm:gap-4 items-center">
          <!-- 6 Logo đối tác từ link Drive -->
        </div>
      </div>
    </section>

  </main>

  <!-- ===================================================================== -->
  <!-- FLATSOME FOOTER (Bố cục 4 cột đơn giản, rõ ràng)                      -->
  <!-- ===================================================================== -->
  <footer id="lien-he" class="bg-brand-dark text-gray-300 pt-10 pb-6 border-t-4 border-brand-accent">
    <div class="container-95">
      <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-4 gap-7 pb-8 border-b border-white/10">

        <!-- Cột 1: Thông tin liên hệ -->
        <div class="space-y-3">
          <div class="flex items-center gap-2">
            <svg class="w-9 h-9 shrink-0" viewBox="0 0 64 64" fill="none" xmlns="http://www.w3.org/2000/svg">
              <rect width="64" height="64" rx="12" fill="#0B3C5D" stroke="#38BDF8" stroke-opacity="0.35" stroke-width="2" />
              <rect x="11" y="11" width="19" height="42" rx="2.5" stroke="#FFFFFF" stroke-width="3.5" />
              <rect x="34" y="11" width="19" height="24" rx="2.5" fill="#E67E22" />
              <rect x="34" y="39" width="19" height="14" rx="2.5" fill="#155E8A" />
            </svg>
            <div>
              <div class="text-sm font-extrabold text-white">NHÔM KÍNH <span class="text-brand-accent">PHƯỚC TRUNG</span></div>
              <div class="text-[11px] text-sky-200">Uy tín – Chất lượng – Bền vững</div>
            </div>
          </div>
          <ul class="space-y-2 text-xs sm:text-sm">
            <li class="flex items-start gap-2">
              <i class="fa-solid fa-location-dot text-brand-accent mt-1"></i>
              <span>Địa chỉ: Tp. Đà Nẵng</span>
            </li>
            <li class="flex items-center gap-2">
              <i class="fa-solid fa-phone text-brand-accent"></i>
              <a href="tel:0905192439" class="font-bold text-white hover:text-brand-accent">Hotline: 0905.192.439</a>
            </li>
            <li class="flex items-center gap-2">
              <i class="fa-solid fa-globe text-brand-accent"></i>
              <a href="https://nhomkinhphuoctrung.com" class="hover:text-white">Website: nhomkinhphuoctrung.com</a>
            </li>
          </ul>
        </div>

        <!-- Cột 2: Cửa nhôm Xingfa -->
        <div>
          <h4 class="text-sm font-bold text-white uppercase tracking-wide mb-3 pb-1.5 border-b border-brand-accent/60 inline-block">
            Cửa Nhôm Xingfa
          </h4>
          <ul class="space-y-2 text-xs sm:text-sm">
            <li><a href="#san-pham-xingfa" onclick="filterProducts('1-canh')" class="hover:text-brand-accent transition-colors">Cửa nhôm xingfa 1 cánh</a></li>
            <li><a href="#san-pham-xingfa" onclick="filterProducts('2-canh')" class="hover:text-brand-accent transition-colors">Cửa nhôm xingfa 2 cánh</a></li>
            <li><a href="#san-pham-xingfa" onclick="filterProducts('3-canh')" class="hover:text-brand-accent transition-colors">Cửa nhôm xingfa 3 cánh</a></li>
            <li><a href="#san-pham-xingfa" onclick="filterProducts('4-canh')" class="hover:text-brand-accent transition-colors">Cửa nhôm xingfa 4 cánh</a></li>
            <li><a href="#san-pham-xingfa" onclick="filterProducts('5-canh')" class="hover:text-brand-accent transition-colors">Cửa nhôm xingfa 5 cánh / Xếp trượt</a></li>
          </ul>
        </div>

        <!-- Cột 3: Danh mục sản phẩm -->
        <div>
          <h4 class="text-sm font-bold text-white uppercase tracking-wide mb-3 pb-1.5 border-b border-brand-accent/60 inline-block">
            Danh Mục Sản Phẩm
          </h4>
          <ul class="space-y-2 text-xs sm:text-sm">
            <li><a href="#danh-muc-san-pham" class="hover:text-brand-accent transition-colors">Cửa kính cường lực</a></li>
            <li><a href="#danh-muc-san-pham" class="hover:text-brand-accent transition-colors">Cửa nhựa lõi thép</a></li>
            <li><a href="#danh-muc-san-pham" class="hover:text-brand-accent transition-colors">Cửa kính tự động</a></li>
            <li><a href="#danh-muc-san-pham" class="hover:text-brand-accent transition-colors">Cầu thang kính</a></li>
            <li><a href="#danh-muc-san-pham" class="hover:text-brand-accent transition-colors">Kính ốp bếp &amp; Phòng tắm kính</a></li>
          </ul>
        </div>

        <!-- Cột 4: Hỗ trợ khách hàng -->
        <div>
          <h4 class="text-sm font-bold text-white uppercase tracking-wide mb-3 pb-1.5 border-b border-brand-accent/60 inline-block">
            Hỗ Trợ Nhanh
          </h4>
          <ul class="space-y-2 text-xs sm:text-sm mb-4">
            <li><a href="#cong-trinh" class="hover:text-brand-accent transition-colors">Công trình thực tế tại Đà Nẵng</a></li>
            <li><a href="#bao-gia" class="hover:text-brand-accent transition-colors">Bảng báo giá nhôm kính mới nhất</a></li>
            <li><a href="#tin-tuc" class="hover:text-brand-accent transition-colors">Tin tức &amp; Tư vấn kỹ thuật</a></li>
            <li><a href="#bao-gia-form" class="hover:text-brand-accent transition-colors">Đăng ký khảo sát đo đạc miễn phí</a></li>
          </ul>
        </div>
      </div>

      <div class="pt-5 flex flex-col sm:flex-row items-center justify-between gap-2 text-xs text-gray-400">
        <p>© 2026 Bản quyền thuộc về <strong class="text-white">Nhôm Kính Phước Trung</strong> – nhomkinhphuoctrung.com</p>
        <p>Thiết kế chuẩn Flatsome UX Builder • TP. Đà Nẵng</p>
      </div>
    </div>
  </footer>

  <!-- ===================================================================== -->
  <!-- CÁC NÚT LIÊN HỆ NỔI BẬT: ZALO, FACEBOOK, HOTLINE                      -->
  <!-- Tương thích mượt mà cả máy tính và điện thoại, không che nội dung     -->
  <!-- ===================================================================== -->
  <div class="fixed right-3 bottom-4 sm:right-5 sm:bottom-6 z-50 flex flex-col items-end gap-2.5">
    <!-- Zalo -->
    <a href="https://zalo.me/0905192439" target="_blank" rel="noopener noreferrer" aria-label="Chat Zalo Nhôm Kính Phước Trung" class="group flex items-center gap-2 bg-[#0068FF] hover:bg-blue-700 text-white rounded-full shadow-lg pl-3 pr-3 sm:pl-3.5 sm:pr-4 py-2 transition-all">
      <span class="font-extrabold text-[11px] bg-white text-[#0068FF] w-7 h-7 rounded-full flex items-center justify-center shrink-0">Zalo</span>
      <span class="hidden sm:inline text-xs font-bold whitespace-nowrap">Chat Zalo</span>
    </a>

    <!-- Facebook -->
    <a href="https://www.facebook.com/" target="_blank" rel="noopener noreferrer" aria-label="Facebook Nhôm Kính Phước Trung" class="group flex items-center gap-2 bg-[#1877F2] hover:bg-blue-800 text-white rounded-full shadow-lg pl-3 pr-3 sm:pl-3.5 sm:pr-4 py-2 transition-all">
      <span class="w-7 h-7 rounded-full bg-white text-[#1877F2] flex items-center justify-center shrink-0">
        <i class="fa-brands fa-facebook-f text-sm"></i>
      </span>
      <span class="hidden sm:inline text-xs font-bold whitespace-nowrap">Facebook</span>
    </a>

    <!-- Hotline nổi bật -->
    <a href="tel:0905192439" aria-label="Gọi Hotline 0905.192.439" class="hotline-pulse flex items-center gap-2 bg-brand-accent hover:bg-brand-accentDark text-white rounded-full shadow-xl pl-3 pr-3.5 sm:pl-3.5 sm:pr-4 py-2 transition-all">
      <span class="w-7 h-7 rounded-full bg-white text-brand-accent flex items-center justify-center shrink-0">
        <i class="fa-solid fa-phone-volume text-sm"></i>
      </span>
      <span class="text-xs font-extrabold whitespace-nowrap">0905.192.439</span>
    </a>
  </div>

  <!-- ===================================================================== -->
  <!-- MODAL XEM CHI TIẾT SẢN PHẨM / BÀI VIẾT & THÔNG BÁO (Thay thế alert()) -->
  <!-- ===================================================================== -->
  <div id="detail-modal" class="hidden fixed inset-0 z-50 bg-black/60 backdrop-blur-xs flex items-center justify-center p-4" onclick="closeDetailModal(event)">
    <div class="bg-white rounded-2xl max-w-lg w-full max-h-[88vh] overflow-y-auto shadow-2xl border border-gray-200" onclick="event.stopPropagation()">
      <div class="flex items-center justify-between px-5 py-3.5 border-b border-gray-100 sticky top-0 bg-white z-10">
        <h3 id="modal-title" class="text-sm sm:text-base font-extrabold text-brand-primary pr-4">Chi tiết</h3>
        <button type="button" onclick="hideDetailModal()" class="w-8 h-8 rounded-full bg-gray-100 hover:bg-gray-200 text-gray-600 flex items-center justify-center shrink-0">
          <i class="fa-solid fa-xmark"></i>
        </button>
      </div>
      <div id="modal-body" class="p-5 space-y-4 text-sm text-gray-700"></div>
    </div>
  </div>

  <!-- Toast thông báo gửi form thành công -->
  <div id="toast-box" class="hidden fixed top-20 right-4 z-50 max-w-sm bg-brand-primary text-white px-4 py-3 rounded-xl shadow-xl border-l-4 border-brand-accent text-xs sm:text-sm font-medium flex items-center gap-3">
    <i class="fa-solid fa-circle-check text-brand-accent text-lg shrink-0"></i>
    <span id="toast-message">Yêu cầu báo giá của bạn đã được gửi thành công!</span>
  </div>

  <!-- ===================================================================== -->
  <!-- JAVASCRIPT: DỮ LIỆU THỰC TẾ, XỬ LÝ ẢNH GOOGLE DRIVE, SLIDER & LỌC     -->
  <!-- ===================================================================== -->
  <script>
    /**
     * Hàm tạo đường dẫn ảnh Google Drive tối ưu với cơ chế tự dự phòng 3 tầng:
     * 1. lh3.googleusercontent.com/d/{id}=w1000 (nhanh & ổn định nhất)
     * 2. drive.google.com/thumbnail?id={id}&sz=w1000 (dự phòng 1)
     * 3. placehold.co (dự phòng cuối cùng tránh vỡ khung hình)
     */
    function getDriveUrl(id) {
      return `https://lh3.googleusercontent.com/d/${id}=w1000`;
    }

    function handleImgFallback(img, id, label) {
      const step = parseInt(img.dataset.step || '0', 10);
      if (step === 0) {
        img.dataset.step = '1';
        img.src = `https://drive.google.com/thumbnail?id=${id}&sz=w1000`;
      } else if (step === 1) {
        img.dataset.step = '2';
        const safeText = encodeURIComponent(label || 'Nhôm Kính Phước Trung');
        img.src = `https://placehold.co/600x450/0B3C5D/FFFFFF?text=${safeText}`;
      }
    }

    // Khởi tạo tất cả các thẻ img có thuộc tính data-drive-id
    function initDriveImages() {
      document.querySelectorAll('img[data-drive-id]').forEach((img) => {
        const id = img.getAttribute('data-drive-id');
        const label = img.getAttribute('alt') || 'Phước Trung';
        img.src = getDriveUrl(id);
        img.onerror = function () {
          handleImgFallback(this, id, label);
        };
      });
    }

    // =========================================================================
    // 1. DỮ LIỆU DANH MỤC SẢN PHẨM (Đúng theo web mẫu & link Drive của bạn)
    // =========================================================================
    const categories = [
      { name: 'Cửa nhôm Xingfa', id: '1zRlHJBAneXS7EQ1jdT__hVRCTf2mzOiX', target: '#san-pham-xingfa' },
      { name: 'Cửa nhựa lõi thép', id: '1jiHBW-2MoWUHjQUicSe-rO6NlmfNuZNA', target: '#bao-gia-form' },
      { name: 'Cửa kính tự động', id: '1PIFP1UCQs_FIaKCgGwcJWt-5wTnST9iJ', target: '#bao-gia-form' },
      { name: 'Cầu thang kính', id: '1FnuITlKMjk-xTxkIV96ABv43S1PG--Ul', target: '#bao-gia-form' },
      { name: 'Kính ốp bếp', id: '1ilanOshTrs9llnMXWl5iZ8DtgptJ0hCb', target: '#bao-gia-form' },
      { name: 'Phòng tắm kính', id: '1MhCILHQ5goD1cAPTt1hZsY_ajeOMs-qH', target: '#bao-gia-form' }
    ];

    function renderCategories() {
      const container = document.getElementById('category-grid');
      container.innerHTML = categories.map((cat) => `
        <a href="${cat.target}" class="group bg-white rounded-xl overflow-hidden border border-gray-200 hover:border-brand-primary shadow-xs hover:shadow-md transition-all flex flex-col">
          <div class="aspect-[4/3] w-full overflow-hidden bg-gray-100">
            <img
              data-drive-id="${cat.id}"
              alt="${cat.name}"
              class="img-cover group-hover:scale-105 transition-transform duration-300"
            />
          </div>
          <div class="p-2.5 text-center bg-white">
            <h3 class="text-[11.5px] sm:text-xs font-bold text-brand-primary group-hover:text-brand-accent uppercase leading-snug">
              ${cat.name}
            </h3>
          </div>
        </a>
      `).join('');
    }

    // =========================================================================
    // 2. DỮ LIỆU SẢN PHẨM CỬA NHÔM XINGFA (Có giá, giảm giá % góc trên trái)
    // =========================================================================
    const products = [
      {
        id: 'sp-1',
        name: 'Cửa đi quay mở 1 cánh nhôm Xingfa',
        category: '1-canh',
        driveId: '1-0eBWGjPwzQ-C9c1Wjws9wt0gbsulkPm',
        oldPrice: '2.100.000 ₫',
        salePrice: '1.785.000 ₫',
        discount: '-15%',
        specs: 'Thanh nhôm Xingfa hệ 55 dày 2.0mm nhập khẩu Quảng Đông tem đỏ, kính cường lực 8mm – 10mm, phụ kiện Kinlong đồng bộ chính hãng.'
      },
      {
        id: 'sp-2',
        name: 'Cửa đi quay mở 2 cánh nhôm Xingfa',
        category: '2-canh',
        driveId: '1h2r2rbPrEL7dgLE-MiE5lBBuE8gFNehb',
        oldPrice: '2.150.000 ₫',
        salePrice: '1.850.000 ₫',
        discount: '-14%',
        specs: 'Thiết kế mở quay 2 cánh cân đối, cách âm cách nhiệt vượt trội nhờ hệ gioăng EPDM kép và keo Silicone chống thấm tuyệt đối.'
      },
      {
        id: 'sp-3',
        name: 'Cửa đi quay mở 3 cánh nhôm Xingfa',
        category: '3-canh',
        driveId: '17Qi2D8ntACnVrTeRPZ2V7rC0FmI8ecaR',
        oldPrice: '2.200.000 ₫',
        salePrice: '1.890.000 ₫',
        discount: '-14%',
        specs: 'Giải pháp tối ưu cho mặt tiền có độ rộng vừa phải. Sơn tĩnh điện cao cấp chống muối biển phù hợp khí hậu TP. Đà Nẵng.'
      },
      {
        id: 'sp-4',
        name: 'Cửa đi quay mở 4 cánh nhôm Xingfa',
        category: '4-canh',
        driveId: '1lxzMKWX3e_HJn7UELFZDOURuxh-NYZg-',
        oldPrice: '2.250.000 ₫',
        salePrice: '1.890.000 ₫',
        discount: '-16%',
        specs: 'Mẫu cửa chính sang trọng cho nhà phố, biệt thự. Kết cấu khoang rỗng tăng cứng giúp cửa vận hành nhẹ nhàng, chịu lực gió mạnh.'
      },
      {
        id: 'sp-5',
        name: 'Cửa Nhôm Xingfa Cửa Đi Xếp Trượt',
        category: '5-canh',
        driveId: '1lJpUJBpR_cJp8mIaZ4FnRTynQ_-paNwZ',
        oldPrice: '2.350.000 ₫',
        salePrice: '1.950.000 ₫',
        discount: '-17%',
        specs: 'Cửa xếp trượt nhôm Xingfa hệ 63 (từ 4 – 5 – 6 cánh) giúp mở rộng đến 90% diện tích ô cửa, cực kỳ thoáng đãng cho sân vườn & resort.'
      },
      {
        id: 'sp-6',
        name: 'Cửa sổ mở hất 2 cánh nhôm Xingfa',
        category: '2-canh',
        driveId: '11fS_oEeJtnDICQZ77fJlYl6GhHf-GOhA',
        oldPrice: '1.950.000 ₫',
        salePrice: '1.650.000 ₫',
        discount: '-15%',
        specs: 'Góc mở tối đa 45 độ kèm thanh định vị chống va đập gió bão, tránh hắt mưa hiệu quả cho phòng ngủ và nhà cao tầng.'
      }
    ];

    function renderProducts(filter = 'all') {
      const grid = document.getElementById('product-grid');
      const filtered = filter === 'all' ? products : products.filter((p) => p.category === filter);

      grid.innerHTML = filtered.map((p) => `
        <article class="group bg-white rounded-xl border border-gray-200 hover:border-brand-primary shadow-xs hover:shadow-lg transition-all overflow-hidden flex flex-col">
          <!-- Khung ảnh sản phẩm + Badge giảm giá % góc trên bên trái -->
          <div class="relative aspect-[4/3] w-full overflow-hidden bg-gray-100">
            <span class="absolute top-2 left-2 z-10 px-2 py-0.5 sm:px-2.5 sm:py-1 rounded-md bg-brand-accent text-white text-[11px] sm:text-xs font-extrabold shadow">
              ${p.discount}
            </span>
            <img
              data-drive-id="${p.driveId}"
              alt="${p.name}"
              class="img-cover group-hover:scale-105 transition-transform duration-300"
            />
          </div>

          <!-- Nội dung sản phẩm: Tên đầy đủ không bị cắt/thiếu chữ trên 2 cột mobile -->
          <div class="p-2.5 sm:p-4 flex-1 flex flex-col justify-between gap-2">
            <div>
              <h3 class="text-[12.5px] sm:text-sm font-bold text-gray-800 group-hover:text-brand-primary leading-snug break-words">
                ${p.name}
              </h3>
              <div class="mt-2 flex flex-wrap items-baseline gap-x-2 gap-y-0.5">
                <span class="text-sm sm:text-base font-extrabold text-brand-accent">${p.salePrice}</span>
                <span class="text-[11px] sm:text-xs text-gray-400 line-through">${p.oldPrice}</span>
              </div>
            </div>

            <div class="pt-1 flex flex-col sm:flex-row gap-1.5 sm:gap-2">
              <button type="button" onclick="openProductModal('${p.id}')" class="w-full py-2 px-2 rounded-lg bg-brand-light hover:bg-brand-primary text-brand-primary hover:text-white text-[11.5px] sm:text-xs font-bold transition-colors">
                Xem chi tiết
              </button>
              <a href="#bao-gia-form" onclick="selectQuoteService('${p.name}')" class="w-full py-2 px-2 rounded-lg bg-brand-primary hover:bg-brand-accent text-white text-[11.5px] sm:text-xs font-bold text-center transition-colors">
                Báo giá
              </a>
            </div>
          </div>
        </article>
      `).join('');

      initDriveImages();
    }

    function filterProducts(cat) {
      renderProducts(cat);
      document.querySelectorAll('.filter-btn').forEach((btn) => {
        if (btn.dataset.filter === cat) {
          btn.className = 'filter-btn px-3.5 py-1.5 rounded-lg text-xs font-semibold bg-brand-primary text-white transition-colors';
        } else {
          btn.className = 'filter-btn px-3.5 py-1.5 rounded-lg text-xs font-semibold bg-gray-100 text-gray-700 hover:bg-brand-light hover:text-brand-primary transition-colors';
        }
      });
    }

    // =========================================================================
    // 3. DỮ LIỆU 6 DỰ ÁN TIÊU BIỂU TẠI ĐÀ NẴNG (Đúng tên & link Drive)
    // =========================================================================
    const projects = [
      {
        title: 'DỰ ÁN KHÁCH SẠN RUBY LIGHT',
        location: 'TP. Đà Nẵng',
        driveId: '1wH-JJ2rOYRmDGsNapl3bIBjfiG3Qm6zZ'
      },
      {
        title: 'DỰ ÁN RESORT MỸ SƠN 4 SAO “MY SON HERITAGE RESORT & SPA”',
        location: 'Đà Nẵng – Quảng Nam',
        driveId: '1MmAfsyp3s3YCaEMymrkk8TZbD38jCsAQ'
      },
      {
        title: 'THI CÔNG DỰ ÁN KHÁCH SẠN GODEN LINE',
        location: 'TP. Đà Nẵng',
        driveId: '1YeuDLiSXUK_Epupq9QiGzM90_EGW3Kfy'
      },
      {
        title: 'THI CÔNG DỰ ÁN KHÁCH SẠN JOLIA',
        location: 'TP. Đà Nẵng',
        driveId: '1WRgx-EUIrn8IKFZdpmdv6Z2Xyb7L8_64'
      },
      {
        title: 'THI CÔNG DỰ ÁN KHÁCH SẠN SOHO',
        location: 'TP. Đà Nẵng',
        driveId: '1-C5bdt4K-PpLX_KqSN6QAR5ULo1WnNzt'
      },
      {
        title: 'THI CÔNG DỰ ÁN RAON ĐÀ NẴNG BEACH HOTEL',
        location: 'Biển Mỹ Khê, Đà Nẵng',
        driveId: '1za_IJpAm850uulT6IuhBsk1THb3LuPuc'
      }
    ];

    function renderProjects() {
      const grid = document.getElementById('project-grid');
      grid.innerHTML = projects.map((proj) => `
        <div class="group bg-white rounded-xl overflow-hidden border border-gray-200 hover:border-brand-primary shadow-xs hover:shadow-md transition-all flex flex-col">
          <div class="aspect-[16/10] w-full overflow-hidden bg-gray-100">
            <img
              data-drive-id="${proj.driveId}"
              alt="${proj.title}"
              class="img-cover group-hover:scale-105 transition-transform duration-300"
            />
          </div>
          <div class="p-3.5 flex-1 flex flex-col justify-between">
            <h3 class="text-xs sm:text-[13.5px] font-bold text-brand-primary group-hover:text-brand-accent leading-snug uppercase">
              ${proj.title}
            </h3>
            <p class="mt-1.5 text-[11.5px] text-gray-500 flex items-center gap-1.5">
              <i class="fa-solid fa-location-dot text-brand-accent"></i>
              <span>${proj.location}</span>
            </p>
          </div>
        </div>
      `).join('');
    }

    // =========================================================================
    // 4. DỮ LIỆU DANH MỤC BÀI VIẾT TRANG CHỦ
    // =========================================================================
    const blogPosts = [
      {
        id: 'post-1',
        category: 'tu-van',
        catLabel: 'Tư vấn chọn cửa',
        title: 'Cửa nhôm Xingfa có phù hợp với khí hậu biển Đà Nẵng không?',
        excerpt: 'Nhờ lớp sơn tĩnh điện công nghệ cao và cấu trúc thanh nhôm khoang rỗng chịu lực, cửa nhôm Xingfa chống ăn mòn muối biển và gió bão rất hiệu quả.',
        content: 'Tại khu vực ven biển như TP. Đà Nẵng, hơi muối và gió bão là yếu tố ảnh hưởng lớn đến tuổi thọ cửa. Cửa nhôm Xingfa nhập khẩu tem đỏ sử dụng công nghệ sơn tĩnh điện ngoài trời cao cấp giúp chống oxy hóa, kết hợp gioăng EPDM kín khít giúp ngăn nước mưa tuyệt đối và cách âm cực tốt.',
        driveId: '1zRlHJBAneXS7EQ1jdT__hVRCTf2mzOiX',
        date: '20/11/2026'
      },
      {
        id: 'post-2',
        category: 'ky-thuat',
        catLabel: 'Kỹ thuật nhôm Xingfa',
        title: 'Cách phân biệt nhôm Xingfa nhập khẩu Quảng Đông tem đỏ chính hãng',
        excerpt: 'Hướng dẫn kiểm tra mã QR, độ dày thanh nhôm hệ 55 (1.4mm – 2.0mm) và phụ kiện Kinlong đồng bộ để chọn đúng sản phẩm chất lượng.',
        content: 'Thanh nhôm Xingfa chính hãng có bề mặt ánh kim mịn, mặt cắt bên trong ánh đồng do công nghệ mạ crom chống ăn mòn, tem đỏ sắc nét có mã QR kiểm tra xuất xứ. Khi gia công tại Phước Trung, góc cửa luôn được ép góc bằng máy thủy lực ke góc dày tạo độ khít tuyệt đối.',
        driveId: '1lxzMKWX3e_HJn7UELFZDOURuxh-NYZg-',
        date: '15/11/2026'
      },
      {
        id: 'post-3',
        category: 'kinh-noi-that',
        catLabel: 'Kính nội thất & Bếp',
        title: 'Kinh nghiệm chọn kính ốp bếp và phòng tắm kính cường lực bền đẹp',
        excerpt: 'Lựa chọn độ dày kính 8mm – 10mm tôi nhiệt chuẩn an toàn, phụ kiện inox 304 chống gỉ giúp không gian bếp và nhà tắm luôn sáng bóng.',
        content: 'Đối với kính ốp bếp cường lực, độ dày 8mm sơn màu chịu nhiệt giúp dễ lau chùi dầu mỡ và tạo chiều sâu cho căn bếp. Với phòng tắm kính đứng, nên sử dụng kính cường lực 10mm kết hợp kẹp, bản lề và ray trượt Inox 304 chính hãng để đảm bảo an toàn và không hoen gỉ trong môi trường ẩm ướt.',
        driveId: '1ilanOshTrs9llnMXWl5iZ8DtgptJ0hCb',
        date: '08/11/2026'
      }
    ];

    function renderPosts(cat = 'all') {
      const grid = document.getElementById('blog-grid');
      const list = cat === 'all' ? blogPosts : blogPosts.filter((b) => b.category === cat);

      grid.innerHTML = list.map((post) => `
        <article class="bg-white rounded-xl overflow-hidden border border-gray-200 hover:border-brand-primary shadow-xs hover:shadow-md transition-all flex flex-col">
          <div class="aspect-[16/9] w-full overflow-hidden bg-gray-100">
            <img
              data-drive-id="${post.driveId}"
              alt="${post.title}"
              class="img-cover hover:scale-105 transition-transform duration-300"
            />
          </div>
          <div class="p-4 flex-1 flex flex-col justify-between space-y-3">
            <div>
              <div class="flex items-center justify-between text-[11px] text-gray-500 mb-1.5">
                <span class="font-semibold text-brand-accent">${post.catLabel}</span>
                <span><i class="fa-regular fa-calendar mr-1"></i>${post.date}</span>
              </div>
              <h3 class="text-sm font-bold text-gray-800 hover:text-brand-primary leading-snug mb-1.5 cursor-pointer" onclick="openPostModal('${post.id}')">
                ${post.title}
              </h3>
              <p class="text-xs text-gray-600 leading-relaxed">
                ${post.excerpt}
              </p>
            </div>
            <div>
              <button type="button" onclick="openPostModal('${post.id}')" class="text-xs font-bold text-brand-primary hover:text-brand-accent inline-flex items-center gap-1 transition-colors">
                <span>Đọc chi tiết</span>
                <i class="fa-solid fa-arrow-right text-[10px]"></i>
              </button>
            </div>
          </div>
        </article>
      `).join('');

      initDriveImages();
    }

    function filterPosts(cat) {
      renderPosts(cat);
      document.querySelectorAll('.post-cat-btn').forEach((btn) => {
        if (btn.dataset.postCat === cat) {
          btn.className = 'post-cat-btn px-3 py-1.5 rounded-lg text-xs font-semibold bg-brand-primary text-white transition-colors';
        } else {
          btn.className = 'post-cat-btn px-3 py-1.5 rounded-lg text-xs font-semibold bg-white border border-gray-200 text-gray-700 hover:border-brand-primary hover:text-brand-primary transition-colors';
        }
      });
    }

    // =========================================================================
    // 5. DỮ LIỆU 6 LOGO ĐỐI TÁC TỪ GOOGLE DRIVE
    // =========================================================================
    const partners = [
      { name: 'Đối tác 1', driveId: '13il4TeS8ZnrK0CD4VDPMdNX3EKxY8AFk' },
      { name: 'Đối tác 2', driveId: '1QRcPtjWfg5PEQXw6UMg6ZylQhg8BpzUq' },
      { name: 'Đối tác 3', driveId: '1-Ka-zScPzx653Tg2oWE9-qmFtTdn3Svn' },
      { name: 'Đối tác 4', driveId: '1Oy52Wdfy5x6DKF1lyfYxpZTD5fvGH5vT' },
      { name: 'Đối tác 5', driveId: '1SDcarhnX0yypmqdbawICjYBRtFnKngn-' },
      { name: 'Đối tác 6', driveId: '1Ua4C1iiZqrjkWx-3h2quvqM0w_Xj33fg' }
    ];

    function renderPartners() {
      const grid = document.getElementById('partner-grid');
      grid.innerHTML = partners.map((pt) => `
        <div class="bg-white rounded-xl border border-gray-200 p-3 h-20 flex items-center justify-center hover:shadow-sm transition-shadow">
          <img
            data-drive-id="${pt.driveId}"
            alt="${pt.name}"
            class="max-h-14 max-w-full object-contain"
          />
        </div>
      `).join('');
    }

    // =========================================================================
    // 6. LOGIC SLIDER 2 BANNER TỰ TRƯỢT
    // =========================================================================
    let currentSlide = 0;
    let slideInterval = null;

    function showSlide(index) {
      const slides = document.querySelectorAll('.banner-slide');
      const dots = document.querySelectorAll('.slider-dot');
      if (!slides.length) return;

      currentSlide = (index + slides.length) % slides.length;
      slides.forEach((s, i) => {
        s.classList.toggle('active', i === currentSlide);
      });
      dots.forEach((d, i) => {
        if (i === currentSlide) {
          d.className = 'slider-dot w-6 h-2 rounded-full bg-brand-accent transition-all';
        } else {
          d.className = 'slider-dot w-2 h-2 rounded-full bg-white/50 hover:bg-white transition-all';
        }
      });
    }

    function nextSlide() {
      showSlide(currentSlide + 1);
      resetSlideTimer();
    }

    function prevSlide() {
      showSlide(currentSlide - 1);
      resetSlideTimer();
    }

    function goToSlide(idx) {
      showSlide(idx);
      resetSlideTimer();
    }

    function resetSlideTimer() {
      if (slideInterval) clearInterval(slideInterval);
      slideInterval = setInterval(() => showSlide(currentSlide + 1), 5000);
    }

    // =========================================================================
    // 7. MENU MOBILE, MODAL CHI TIẾT & FORM BÁO GIÁ
    // =========================================================================
    function toggleMobileMenu() {
      const menu = document.getElementById('mobile-menu');
      menu.classList.toggle('hidden');
    }

    function closeMobileMenu() {
      document.getElementById('mobile-menu').classList.add('hidden');
    }

    function toggleSubmenu(id, btn) {
      const el = document.getElementById(id);
      const icon = btn.querySelector('i');
      el.classList.toggle('hidden');
      icon.classList.toggle('rotate-180');
    }

    function openProductModal(id) {
      const p = products.find((item) => item.id === id);
      if (!p) return;

      document.getElementById('modal-title').textContent = p.name;
      document.getElementById('modal-body').innerHTML = `
        <div class="relative rounded-xl overflow-hidden aspect-[4/3] bg-gray-100">
          <span class="absolute top-2.5 left-2.5 px-2.5 py-1 rounded-md bg-brand-accent text-white text-xs font-extrabold">${p.discount}</span>
          <img data-drive-id="${p.driveId}" alt="${p.name}" class="img-cover" />
        </div>
        <div class="flex items-baseline gap-3">
          <span class="text-xl font-extrabold text-brand-accent">${p.salePrice} / m²</span>
          <span class="text-sm text-gray-400 line-through">${p.oldPrice}</span>
        </div>
        <p class="leading-relaxed text-gray-600">${p.specs}</p>
        <div class="bg-brand-light rounded-xl p-3 text-xs text-brand-primary space-y-1">
          <div><strong>• Bảo hành:</strong> Chính hãng dài hạn, bảo trì nhanh tại Đà Nẵng.</div>
          <div><strong>• Ưu đãi:</strong> Miễn phí khảo sát đo đạc &amp; vận chuyển nội thành.</div>
        </div>
        <div class="grid grid-cols-2 gap-2.5 pt-1">
          <a href="tel:0905192439" class="py-2.5 rounded-lg bg-brand-accent hover:bg-brand-accentDark text-white font-bold text-center text-xs sm:text-sm">
            Gọi 0905.192.439
          </a>
          <a href="#bao-gia-form" onclick="hideDetailModal(); selectQuoteService('${p.name}')" class="py-2.5 rounded-lg bg-brand-primary hover:bg-brand-dark text-white font-bold text-center text-xs sm:text-sm">
            Nhận báo giá
          </a>
        </div>
      `;
      document.getElementById('detail-modal').classList.remove('hidden');
      initDriveImages();
    }

    function openPostModal(id) {
      const post = blogPosts.find((item) => item.id === id);
      if (!post) return;

      document.getElementById('modal-title').textContent = post.title;
      document.getElementById('modal-body').innerHTML = `
        <div class="rounded-xl overflow-hidden aspect-[16/9] bg-gray-100">
          <img data-drive-id="${post.driveId}" alt="${post.title}" class="img-cover" />
        </div>
        <div class="text-xs text-gray-500 flex items-center gap-3">
          <span class="font-bold text-brand-accent">${post.catLabel}</span>
          <span>Ngày đăng: ${post.date}</span>
        </div>
        <p class="leading-relaxed text-gray-700">${post.content}</p>
        <div class="pt-2">
          <a href="#bao-gia-form" onclick="hideDetailModal()" class="inline-flex items-center gap-2 px-4 py-2.5 rounded-lg bg-brand-primary text-white text-xs font-bold hover:bg-brand-accent transition-colors">
            Liên hệ tư vấn kỹ thuật miễn phí
          </a>
        </div>
      `;
      document.getElementById('detail-modal').classList.remove('hidden');
      initDriveImages();
    }

    function hideDetailModal() {
      document.getElementById('detail-modal').classList.add('hidden');
    }

    function closeDetailModal(e) {
      if (e.target.id === 'detail-modal') hideDetailModal();
    }

    function selectQuoteService(text) {
      const noteEl = document.getElementById('q-note');
      if (noteEl) {
        noteEl.value = `Tôi cần tư vấn và báo giá mẫu: ${text}.`;
      }
    }

    function showToast(msg) {
      const toast = document.getElementById('toast-box');
      document.getElementById('toast-message').textContent = msg;
      toast.classList.remove('hidden');
      setTimeout(() => {
        toast.classList.add('hidden');
      }, 4000);
    }

    function handleQuoteSubmit(event) {
      event.preventDefault();
      const name = document.getElementById('q-name').value.trim();
      const phone = document.getElementById('q-phone').value.trim();
      if (!name || !phone) return;

      showToast(`Cảm ơn ${name}! Phước Trung sẽ liên hệ số ${phone} để báo giá sớm nhất.`);
      event.target.reset();
    }

    // Khởi chạy khi tải xong trang
    window.addEventListener('DOMContentLoaded', () => {
      renderCategories();
      renderProducts('all');
      renderProjects();
      renderPosts('all');
      renderPartners();
      initDriveImages();
      resetSlideTimer();

      // Hỗ trợ vuốt cảm ứng trên điện thoại cho Banner
      const sliderEl = document.getElementById('hero-slider');
      let touchStartX = 0;
      sliderEl.addEventListener('touchstart', (e) => {
        touchStartX = e.changedTouches[0].screenX;
      }, { passive: true });
      sliderEl.addEventListener('touchend', (e) => {
        const diff = e.changedTouches[0].screenX - touchStartX;
        if (Math.abs(diff) > 45) {
          if (diff < 0) nextSlide();
          else prevSlide();
        }
      }, { passive: true });
    });
  </script>
</body>
</html>
