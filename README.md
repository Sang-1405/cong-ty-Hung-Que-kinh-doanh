<!doctype html>
<html lang="vi">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>Công Ty Hưng Quế kinh doanh</title>
  <style>
    :root{
      --primary:#2196f3;         /* Màu xanh biển chủ đạo */
      --accent:#1565c0;          /* Màu xanh biển đậm */
      --bg:#e3f2fd;              /* Nền xanh nhạt */
      --card:#fff;
      --muted:#5c7fa3;           /* Xanh xám nhẹ */
      --dark:#0d2240;            /* Xanh đậm thay cho đen */
      --radius:12px;
      --max-width:1200px;
    }
    *{box-sizing:border-box}
    body{font-family:Arial, Helvetica, sans-serif;background:var(--bg);color:var(--dark);line-height:1.5;margin:0}
    a{color:var(--accent)}
    header.site-header{display:flex;align-items:center;justify-content:space-between;padding:10px 16px;background:var(--card);border-bottom:1px solid #cce1ff;position:sticky;top:0;z-index:60}
    .brand{font-weight:700;color:var(--primary);font-size:20px}
    .main-nav{display:flex;gap:10px;align-items:center}
    .nav-link{padding:8px 10px;border-radius:8px;color:var(--dark);text-decoration:none}
    .nav-link:hover,.nav-link.active{background:#e3f2fd;color:var(--accent)}
    .header-contact{font-size:14px;color:var(--muted);display:flex;align-items:center;gap:8px}
    .header-contact a{color:var(--accent);font-weight:600;text-decoration:none}
    .mobile-toggle{display:none;background:transparent;border:0;font-size:20px;padding:6px;cursor:pointer;color:var(--accent)}
    .container{max-width:var(--max-width);margin:0 auto;padding:18px}
    .hero{display:grid;grid-template-columns:1fr 1fr;gap:20px;align-items:center;padding:24px;background:var(--card);border-radius:12px;box-shadow:0 6px 24px rgba(33,150,243,0.09)}
    .hero h1{margin:0 0 12px;font-size:28px;color:var(--primary)}
    .hero p{color:var(--muted)}
    .hero img{width:100%;border-radius:10px;display:block;box-shadow:0 4px 16px rgba(33,150,243,0.08)}
    .section{margin-top:22px}
    .cards{display:grid;grid-template-columns:repeat(auto-fit,minmax(220px,1fr));gap:16px}
    .card{background:var(--card);padding:14px;border-radius:12px;border:1px solid #cce1ff;box-shadow:0 6px 18px rgba(33,150,243,0.05)}
    .card img{width:100%;height:140px;object-fit:cover;border-radius:8px;margin-bottom:10px}
    h2{margin-bottom:12px;color:var(--primary)}
    .video-wrapper{position:relative;padding-top:56.25%;margin-top:12px;border-radius:8px;overflow:hidden}
    .video-wrapper iframe{position:absolute;left:0;top:0;width:100%;height:100%;border:0}
    .btn{display:inline-block;padding:10px 14px;border-radius:8px;border:1px solid var(--accent);background:#fff;color:var(--accent);text-decoration:none;cursor:pointer;transition:all 0.15s}
    .btn.primary{background:var(--primary);color:#fff;border-color:var(--primary)}
    .btn:hover{background:var(--accent);color:#fff}
    footer.site-footer{background:var(--card);border-top:1px solid #cce1ff;padding:18px 16px;margin-top:28px;text-align:center;color:var(--muted)}
    .lightbox{display:none;position:fixed;inset:0;background:rgba(33,150,243,0.85);align-items:center;justify-content:center;z-index:120}
    .lightbox-inner{background:#fff;padding:18px;border-radius:10px;max-width:95vw;max-height:92vh;overflow:auto;text-align:center}
    .lightbox-inner img{max-width:90vw;max-height:68vh;border-radius:8px;display:block;margin:0 auto 12px}
    .muted{color:var(--muted)}
    form input, form textarea {width:100%;padding:8px;border-radius:6px;border:1px solid #cce1ff}
    .sep{color:#cce1ff;margin:0 6px}
    .small{font-size:0.9em;color:var(--muted)}
    @media(max-width:900px){
      .hero{grid-template-columns:1fr}
      .main-nav{display:none}
      .mobile-toggle{display:inline-block}
      header.site-header{flex-wrap:wrap;gap:8px}
    }
    .mobile-nav-open .main-nav{display:flex;position:absolute;left:16px;right:16px;top:64px;background:var(--card);padding:8px;border-radius:8px;box-shadow:0 10px 30px rgba(33,150,243,0.14);flex-direction:column}
  </style>
</head>
<body>
  <header class="site-header">
    <div class="brand">Công Ty Hưng Quế kinh doanh</div>

    <nav class="main-nav" aria-label="main navigation">
      <a class="nav-link active" href="#home">Trang chủ</a>
      <a class="nav-link" href="#gioi-thieu">Giới thiệu</a>
      <a class="nav-link" href="#dich-vu">Dịch vụ</a>
      <a class="nav-link" href="#san-pham">Sản phẩm</a>
      <a class="nav-link" href="#lien-he">Liên hệ</a>
    </nav>

    <div class="header-contact" aria-label="Thông tin liên hệ">
      <span class="small">Điện thoại:</span>
      <a href="tel:0914414368">0914414368</a>
      <span class="sep">|</span>
      <span class="small">Hotline:</span>
      <a href="tel:0944215456">0944215456</a>
    </div>

    <button class="mobile-toggle" aria-label="Mở menu">☰</button>
  </header>

  <main class="container">
    <!-- HOME / HERO -->
    <section id="home" class="hero" aria-labelledby="home-title">
      <div>
        <h1 id="home-title">Giải pháp vật liệu & thiết bị cho mọi công trình</h1>
        <p>Hưng Quế cung cấp vật liệu xây dựng, nội thất, thiết bị điện nước. Đồng hành cùng bạn xây dựng những công trình bền vững.</p>
        <p>
          <a class="btn primary" href="#san-pham">Xem sản phẩm</a>
          <a class="btn" href="#lien-he">Liên hệ ngay</a>
        </p>
      </div>
      <div>
        <img src="https://files.oaiusercontent.com/file-7c6b7b7f-fbfb-4c7b-9c25-8613de8b8bb2/IMG_20231001_155658.jpg" alt="Showroom Hưng Quế">
      </div>
    </section>

    <!-- GIỚI THIỆU -->
    <section id="gioi-thieu" class="section" aria-labelledby="gioi-title">
      <h2 id="gioi-title">Giới thiệu công ty Hưng Quế</h2>
      <p>Hưng Quế là đơn vị phân phối vật liệu xây dựng, nội thất và thiết bị điện nước. Chúng tôi cung cấp giải pháp toàn diện cho nhà thầu, chủ đầu tư và hộ gia đình.</p>

      <!-- Ảnh mặt tiền công ty (ảnh số 10) -->
      <img 
        src="https://files.oaiusercontent.com/file-7c6b7b7f-fbfb-4c7b-9c25-8613de8b8bb2/IMG_20231001_155658.jpg"
        alt="Mặt tiền Công ty Hưng Quế"
        style="width:100%;max-width:700px;display:block;margin:18px auto 8px auto;border-radius:12px;box-shadow:0 4px 18px rgba(33,150,243,0.10)"
      >

      <div class="video-wrapper" aria-hidden="false">
        <iframe
          src="https://www.youtube.com/embed/NqTrCk04Qok"
          title="Giới thiệu Hưng Quế"
          frameborder="0"
          allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
          allowfullscreen
          loading="lazy"></iframe>
      </div>
    </section>

    <!-- DỊCH VỤ -->
    <section id="dich-vu" class="section">
      <h2>Dịch vụ</h2>
      <div class="cards">
        <div class="card"><h3>Tư vấn vật liệu</h3><p class="small">Gợi ý vật liệu theo ngân sách.</p></div>
        <div class="card"><h3>Cung ứng & vận chuyển</h3><p class="small">Giao hàng nhanh.</p></div>
        <div class="card"><h3>Lắp đặt</h3><p class="small">Lắp đặt điện nước, bảo hành.</p></div>
      </div>
    </section>

    <!-- SẢN PHẨM -->
    <section id="san-pham" class="section" aria-labelledby="sanpham-title">
      <h2 id="sanpham-title">Sản phẩm tiêu biểu</h2>

      <!-- Products grid -->
      <div class="cards" id="productsGrid">
        <!-- Existing original items (0..3) -->
        <article class="card">
          <img src="https://files.oaiusercontent.com/file-90cfdb4d-924a-4a14-99b6-7c4c690e5f95/IMG_20231001_155708.jpg" alt="Tranh kính & gạch lát sàn">
          <h4>Tranh kính nghệ thuật & Gạch lát sàn</h4>
          <p class="small">Trưng bày tranh kính nghệ thuật và các mẫu gạch lát sàn cao cấp.</p>
          <div style="margin-top:10px">
            <button class="btn" data-idx="0">Xem ảnh</button>
            <a class="btn" href="#lien-he">Mua hàng</a>
          </div>
        </article>

        <article class="card">
          <img src="https://files.oaiusercontent.com/file-2b90f7b8-3b37-425d-bcf0-3b2d9b3aa31e/IMG_20231001_155730.jpg" alt="Thiết bị chiếu sáng">
          <h4>Thiết bị chiếu sáng</h4>
          <p class="small">Đèn trang trí, đèn trần, đèn thả, đèn bàn và các thiết bị chiếu sáng.</p>
          <div style="margin-top:10px">
            <button class="btn" data-idx="1">Xem ảnh</button>
            <a class="btn" href="#lien-he">Mua hàng</a>
          </div>
        </article>

        <article class="card">
          <img src="https://files.oaiusercontent.com/file-9e7c2a4a-7c41-48f7-8b42-6b5e6ee9e09f/IMG_20231001_155735.jpg" alt="Thiết bị vệ sinh">
          <h4>Thiết bị vệ sinh & điện nước</h4>
          <p class="small">Vòi nước, máy nước nóng, bồn rửa, thiết bị điện nước và phụ kiện.</p>
          <div style="margin-top:10px">
            <button class="btn" data-idx="2">Xem ảnh</button>
            <a class="btn" href="#lien-he">Mua hàng</a>
          </div>
        </article>

        <article class="card">
          <img src="https://files.oaiusercontent.com/file-7c6b7b7f-fbfb-4c7b-9c25-8613de8b8bb2/IMG_20231001_155658.jpg" alt="Mặt tiền showroom">
          <h4>Mặt tiền showroom</h4>
          <p class="small">Hình ảnh mặt tiền cửa hàng Hưng Quế - uy tín và chuyên nghiệp.</p>
          <div style="margin-top:10px">
            <button class="btn" data-idx="3">Xem ảnh</button>
            <a class="btn" href="#lien-he">Liên hệ</a>
          </div>
        </article>

        <!-- NEW: user images (16..19) added as products (indices 4..7) -->
        <article class="card">
          <!-- Save the provided first image as images/product-16.jpg (see notes below) -->
          <img src="images/product-16.jpg" alt="Ảnh cửa hàng - khu thiết bị">
          <h4>Khu thiết bị & phụ kiện</h4>
          <p class="small">Kho trưng bày các thiết bị, phụ kiện và vật tư.</p>
          <div style="margin-top:10px">
            <button class="btn" data-idx="4">Xem ảnh</button>
            <a class="btn" href="#lien-he">Mua hàng</a>
          </div>
        </article>

        <article class="card">
          <img src="images/product-17.jpg" alt="Ảnh showroom thiết bị">
          <h4>Showroom thiết bị</h4>
          <p class="small">Không gian trưng bày thiết bị điện nước, vòi, phụ kiện.</p>
          <div style="margin-top:10px">
            <button class="btn" data-idx="5">Xem ảnh</button>
            <a class="btn" href="#lien-he">Mua hàng</a>
          </div>
        </article>

        <article class="card">
          <img src="images/product-18.jpg" alt="Khu mẫu gạch & tranh kính">
          <h4>Khu mẫu gạch & tranh kính</h4>
          <p class="small">Mẫu tranh kính, gạch ốp lát và sàn minh họa.</p>
          <div style="margin-top:10px">
            <button class="btn" data-idx="6">Xem ảnh</button>
            <a class="btn" href="#lien-he">Mua hàng</a>
          </div>
        </article>

        <article class="card">
          <img src="images/product-19.jpg" alt="Thiết bị vệ sinh trưng bày">
          <h4>Thiết bị vệ sinh trưng bày</h4>
          <p class="small">Bồn cầu, lavabo và các phụ kiện trưng bày.</p>
          <div style="margin-top:10px">
            <button class="btn" data-idx="7">Xem ảnh</button>
            <a class="btn" href="#lien-he">Mua hàng</a>
          </div>
        </article>

      </div>
    </section>

    <!-- LIÊN HỆ -->
    <section id="lien-he" class="section" aria-labelledby="lien-title">
      <h2 id="lien-title">Liên hệ</h2>
      <div style="display:grid;grid-template-columns:1fr 320px;gap:20px">
        <div>
          <form id="contactForm">
            <label>Họ tên<br><input name="name" type="text" required></label><br><br>
            <label>Điện thoại<br><input name="phone" type="tel" required></label><br><br>
            <label>Email<br><input name="email" type="email"></label><br><br>
            <label>Nội dung<br><textarea name="message" rows="5" required></textarea></label><br><br>
            <button class="btn primary" type="submit">Gửi liên hệ</button>
          </form>
        </div>
        <aside style="background:var(--card);padding:14px;border-radius:10px;border:1px solid #cce1ff">
          <p><strong>Địa chỉ:</strong> Yên Sơn, Thanh Hóa</p>
          <p><strong>Điện thoại:</strong> <a href="tel:0914414368">0914414368</a></p>
          <p><strong>Hotline:</strong> <a href="tel:0944215456">0944215456</a></p>
          <p><strong>Email:</strong> <a href="mailto:info@hungque.vn">info@hungque.vn</a></p>
        </aside>
      </div>
    </section>
  </main>

  <footer class="site-footer">
    <div class="container">
      <p>© 2025 Công Ty Hưng Quế kinh doanh – Vật liệu xây dựng, nội thất, thiết bị điện nước.</p>
      <p class="small">Điện thoại: <a href="tel:0914414368">0914414368</a> • Hotline: <a href="tel:0944215456">0944215456</a></p>
    </div>
  </footer>

  <!-- Lightbox / modal (dùng chung cho tất cả sản phẩm) -->
  <div id="lightbox" class="lightbox" role="dialog" aria-hidden="true" style="display:none;align-items:center;justify-content:center">
    <div class="lightbox-inner" role="document">
      <button id="closeLightbox" class="btn" style="float:right">× Đóng</button>
      <img id="lightboxImg" src="" alt="Ảnh sản phẩm">
      <div class="caption" id="lightboxCaption"></div>
      <div style="margin-top:12px"><a id="lightboxContact" class="btn primary" href="#lien-he">Liên hệ mua</a></div>
    </div>
  </div>

  <!-- Cookie banner -->
  <div id="cookieBanner" class="cookie-banner" style="position:fixed;bottom:16px;left:16px;right:16px;background:var(--accent);color:#fff;padding:12px;border-radius:12px;display:flex;justify-content:space-between;align-items:center;z-index:140">
    <span>Trang web sử dụng cookies để cải thiện trải nghiệm.</span>
    <div><button id="acceptCookies" class="btn">Đồng ý</button></div>
  </div>

  <script>
    (function(){
      // Cookie banner
      var cookieBanner = document.getElementById('cookieBanner');
      var accept = document.getElementById('acceptCookies');
      if(localStorage.getItem('hq_cookies')==='1') cookieBanner.style.display='none';
      if(accept) accept.addEventListener('click', function(){ localStorage.setItem('hq_cookies','1'); cookieBanner.style.display='none'; });

      // Images array used by lightbox. Indices must match buttons' data-idx.
      var images = [
        {src:"https://files.oaiusercontent.com/file-90cfdb4d-924a-4a14-99b6-7c4c690e5f95/IMG_20231001_155708.jpg", caption:"Tranh kính nghệ thuật & Gạch lát sàn"},
        {src:"https://files.oaiusercontent.com/file-2b90f7b8-3b37-425d-bcf0-3b2d9b3aa31e/IMG_20231001_155730.jpg", caption:"Thiết bị chiếu sáng"},
        {src:"https://files.oaiusercontent.com/file-9e7c2a4a-7c41-48f7-8b42-6b5e6ee9e09f/IMG_20231001_155735.jpg", caption:"Thiết bị vệ sinh & điện nước"},
        {src:"https://files.oaiusercontent.com/file-7c6b7b7f-fbfb-4c7b-9c25-8613de8b8bb2/IMG_20231001_155658.jpg", caption:"Mặt tiền showroom Hưng Quế"},
        // New images added for the products you provided:
        {src:"images/product-16.jpg", caption:"Khu thiết bị & phụ kiện (ảnh 16)"},
        {src:"images/product-17.jpg", caption:"Showroom thiết bị (ảnh 17)"},
        {src:"images/product-18.jpg", caption:"Khu mẫu gạch & tranh kính (ảnh 18)"},
        {src:"images/product-19.jpg", caption:"Thiết bị vệ sinh trưng bày (ảnh 19)"}
      ];

      // Lightbox handlers
      var productButtons = document.querySelectorAll('button[data-idx]');
      var lightbox = document.getElementById('lightbox');
      var lightboxImg = document.getElementById('lightboxImg');
      var lightboxCaption = document.getElementById('lightboxCaption');
      var lightboxContact = document.getElementById('lightboxContact');

      productButtons.forEach(function(btn){
        btn.addEventListener('click', function(){
          var idx = parseInt(this.getAttribute('data-idx'),10) || 0;
          var img = images[idx] || images[0];
          lightboxImg.src = img.src;
          lightboxCaption.textContent = img.caption;
          lightboxContact.href = "#lien-he";
          lightbox.style.display = 'flex';
          lightbox.setAttribute('aria-hidden','false');
          document.body.style.overflow = 'hidden';
        });
      });

      var closeLightbox = document.getElementById('closeLightbox');
      if(closeLightbox) closeLightbox.addEventListener('click', function(){ lightbox.style.display='none'; lightbox.setAttribute('aria-hidden','true'); document.body.style.overflow=''; });
      if(lightbox) lightbox.addEventListener('click', function(e){ if(e.target===lightbox){ lightbox.style.display='none'; lightbox.setAttribute('aria-hidden','true'); document.body.style.overflow=''; } });

      // Contact form simple handler
      var form = document.getElementById('contactForm');
      if(form) form.addEventListener('submit', function(e){ e.preventDefault(); alert('Cảm ơn bạn! Thông tin đã được gửi.'); form.reset(); });

      // Smooth scroll anchors
      document.querySelectorAll('a[href^="#"]').forEach(function(a){
        a.addEventListener('click', function(e){
          var href = this.getAttribute('href');
          if(href.length>1){ e.preventDefault(); var el = document.querySelector(href); if(el){ el.scrollIntoView({behavior:'smooth',block:'start'}); history.replaceState(null,null,href); } }
        });
      });
    })();
  </script>
</body>
</html>
