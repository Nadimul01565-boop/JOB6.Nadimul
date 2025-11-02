<!doctype html>
<html lang="en">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<title>Bangladesh Cricket Board (BCB) - Demo</title>

<!-- Bootstrap 5 CSS -->
<link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/css/bootstrap.min.css" rel="stylesheet">

<!-- Swiper CSS for slider -->
<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/swiper@9/swiper-bundle.min.css"/>

<!-- Icons -->
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.0/css/all.min.css"/>

<style>
:root{
  --primary-grad: linear-gradient(90deg,#00aaff,#00dd88);
  --card-shadow: 0 6px 18px rgba(0,0,0,0.08);
  --accent: #007bff;
}
body{font-family:'Segoe UI',Roboto,Arial,sans-serif;background:#fff;color:#222;}
/* Header */
.topbar{
  background: var(--primary-grad);
  color: white;
  padding: 18px 0;
  box-shadow: 0 3px 10px rgba(0,0,0,0.08);
}
.brand-logo {
  width:72px;height:72px;border-radius:50%;
  display:flex;align-items:center;justify-content:center;
  font-weight:700;color:white;font-size:20px;
  background: linear-gradient(180deg,#004b7a,#0088cc);
  box-shadow: 0 6px 18px rgba(0,0,0,0.18);
}
.site-title {font-size:28px;font-weight:700;margin-bottom:0;}
.site-sub {font-size:14px;opacity:0.95;}
.navbar {background:#111827;}
.navbar .nav-link{color:#e6eef6;}
.navbar .nav-link:hover{color:white;}
.swiper-wrapper .slide {
  height:520px;
  background-position:center;
  background-size:cover;
}
@media (max-width:768px){
  .swiper-wrapper .slide{height:300px;}
}
.hero-overlay {
  position:absolute;
  inset:0;
  pointer-events:none;
  background:linear-gradient(180deg,rgba(0,0,0,0.15),rgba(0,0,0,0.15));
}
.anthem-card {box-shadow:var(--card-shadow);border-radius:12px;}
.welcome h2 {color:#0b7a4b;font-weight:700;}
.person-card {
  border-radius:10px;box-shadow:var(--card-shadow);
  overflow:hidden;text-align:center;
  transition:transform .25s ease,box-shadow .25s ease;
  background:#fff;
}
.person-card:hover{transform:translateY(-6px);box-shadow:0 12px 30px rgba(0,0,0,0.12);}
.person-card .role {background:#0b7aef;color:white;padding:10px 0;font-weight:700;}
.person-card .role.vice {background:#6c757d;}
.person-card img {
  width:120px;height:120px;object-fit:cover;
  border-radius:50%;margin-top:16px;
}
footer {background:#061428;color:#cfeaf3;padding:28px 0;}
footer a {color:#aee6ff;text-decoration:none;}
.social-icons a {font-size:18px;margin-right:10px;color:#fff;opacity:.9;}
</style>
</head>

<body>

<!-- Top header -->
<header class="topbar">
  <div class="container d-flex align-items-center gap-3">
    <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQ1mngKu6NqDVjLJzLjdxpklzKXFgSmkt3Nyg&s" alt="BCB Logo" width="72" height="72" class="rounded-circle border border-light">
    <div>
      <p class="mb-0 site-title">Bangladesh Cricket Board (BCB)</p>
      <small class="site-sub">Location: Mirpur, Dhaka</small>
    </div>
    <div class="ms-auto text-end d-none d-md-block">
      <div><strong>Hotline:</strong> 01887396300</div>
      <small>Official site demo</small>
    </div>
  </div>
</header>

<!-- Navbar -->
<nav class="navbar navbar-expand-lg navbar-dark">
  <div class="container">
    <a class="navbar-brand text-white d-lg-none" href="#">BCB</a>
    <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navMenu">
      <span class="navbar-toggler-icon"></span>
    </button>
    <div id="navMenu" class="collapse navbar-collapse">
      <ul class="navbar-nav me-auto mb-2 mb-lg-0">
        <li class="nav-item"><a class="nav-link active" href="#">Home</a></li>
        <li class="nav-item"><a class="nav-link" href="/about.page.html">About</a></li>
        <li class="nav-item"><a class="nav-link" href="#teams">Teams</a></li>
        <li class="nav-item"><a class="nav-link" href="/gallery.page.html">Gallery</a></li>
        <li class="nav-item"><a class="nav-link" href="/Contact.page.Html">Contact</a></li>
      </ul>
      <form class="d-flex" role="search">
        <input class="form-control me-2" type="search" placeholder="Search">
        <button class="btn btn-outline-light" type="submit">Search</button>
      </form>
    </div>
  </div>
</nav>

<!-- HERO SLIDER -->
<section class="hero">
  <div class="swiper mySwiper">
    <div class="swiper-wrapper">

      <!-- Sher-e-Bangla -->
      <div class="swiper-slide slide" style="background-image:url('https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRXgwJzLh24LZoXwGNoLVuDK-EB0tzLKxxxwA&s');">
        <div class="container h-100 d-flex align-items-end">
          <div class="p-4 text-white" style="max-width:720px;">
            <h1 class="display-5">Sher-e-Bangla National Cricket Stadium</h1>
            <p>Mirpur, Dhaka — The home of Bangladesh cricket.</p>
          </div>
        </div>
      </div>

      <!-- Zahur Ahmed Chowdhury -->
      <div class="swiper-slide slide" style="background-image:url('https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQ8teMbBhjVgGDwUV_vqN6-ERk5adm6r7mgJM-X4nZSJg6Jbn2XhA5ZxD92or1EbdAHPHI&usqp=CAU');">
        <div class="container h-100 d-flex align-items-end">
          <div class="p-4 text-white" style="max-width:720px;">
            <h1 class="display-5">Zahur Ahmed Chowdhury Stadium</h1>
            <p>Chittagong — Famous for thrilling matches.</p>
          </div>
        </div>
      </div>

      <!-- Sylhet -->
      <div class="swiper-slide slide" style="background-image:url('https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSBYj4y5WtVHGFVXt0A_VwoonOvJ0ybEETiDg&s');">
        <div class="container h-100 d-flex align-items-end">
          <div class="p-4 text-white" style="max-width:720px;">
            <h1 class="display-5">Sylhet International Cricket Stadium</h1>
            <p>Sylhet — Scenic and modern venue.</p>
          </div>
        </div>
      </div>

      <!-- Bangladesh National Stadium -->
      <div class="swiper-slide slide" style="background-image:url('https://bashat.com.bd/wp-content/uploads/2025/03/1-20-Copy.jpg');">
        <div class="container h-100 d-flex align-items-end">
          <div class="p-4 text-white" style="max-width:720px;">
            <h1 class="display-5">Bangladesh National Stadium (Gulistan)</h1>
            <p>Historic grounds in Dhaka city center.</p>
          </div>
        </div>
      </div>

    </div>
    <div class="swiper-button-next"></div>
    <div class="swiper-button-prev"></div>
    <div class="swiper-pagination"></div>
  </div>
  <div class="hero-overlay"></div>
</section>

<!-- Main content -->
<main class="py-5">
  <div class="container">
    <div class="row g-4">
      <div class="col-lg-8">
        <div class="card anthem-card mb-4 p-3">
          <div class="d-flex align-items-center gap-3">
            <div style="font-size:28px;"><i class="fa-solid fa-music"></i></div>
            <div>
              <h5 class="mb-1">National Anthem of Bangladesh</h5>
              <small class="text-muted">Play / Pause the anthem</small>
            </div>
          </div>
          <hr>
          <div class="p-2">
            <audio controls style="width:100%;">
              <source src="assets/anthem.mp3" type="audio/mpeg">
              Your browser does not support the audio element.
            </audio>
          </div>
        </div>

        <section id="about" class="welcome mb-4">
          <h2 class="mb-3"><i class="fa-solid fa-book-open me-2" style="color:#0b7a4b"></i> Welcome to Bangladesh Cricket Board</h2>
          <p>
            Bangladesh Cricket Board (BCB) is the national governing body for cricket in Bangladesh.
            Headquartered in Mirpur, Dhaka, BCB organizes and oversees the development of cricket at all levels,
            including national teams, domestic leagues, coaching, and grassroots programs.
          </p>
        </section>
        <!-- 📰 Latest News Section -->
<section id="news" class="py-5" style="background: linear-gradient(135deg, #c8e6c9, #e3f2fd);">
  <div class="container">
    <h2 class="text-success mb-4 text-center">
      <i class="bi bi-newspaper"></i> Latest News
    </h2>

    <div class="card shadow-lg border-0" style="border-radius: 15px;">
      <div class="card-body" style="background: #ffffff; border-radius: 15px;">
        <ul class="list-unstyled mb-0">
          <li class="mb-3">
            <a href="#" class="fw-semibold" 
               style="color: #007bff; text-decoration: none; font-size: 1.05rem;">
              🏏 Bangladesh to Host Tri-Nation Series 2025 – Fixtures Announced!
            </a>
          </li>
          <li class="mb-3">
            <a href="#" class="fw-semibold" 
               style="color: #007bff; text-decoration: none; font-size: 1.05rem;">
              🌟 Shakib Al Hasan Returns to the Squad for Home Series
            </a>
          </li>
          <li class="mb-3">
            <a href="#" class="fw-semibold" 
               style="color: #007bff; text-decoration: none; font-size: 1.05rem;">
              🚨 BPL 2025 Schedule Published – Exciting Matches Ahead!
            </a>
          </li>
          <li class="mb-3">
            <a href="#" class="fw-semibold" 
               style="color: #007bff; text-decoration: none; font-size: 1.05rem;">
              🧢 Under-19 Team Qualifies for ICC Youth World Cup
            </a>
          </li>
          <li>
            <a href="#" class="fw-semibold" 
               style="color: #007bff; text-decoration: none; font-size: 1.05rem;">
              🎯 BCB Launches New Cricket Training Academy in Sylhet
            </a>
          </li>
        </ul>
      </div>
    </div>
  </div>

  <style>
    #news a:hover {
      color: #0044cc !important;
      text-decoration: underline !important;
      transition: 0.2s ease-in-out;
    }
  </style>
</section>


        <section id="gallery" class="mb-4">
          <div class="row g-2">
            <div class="col-md-12


             col-md-3"><!-- 🌟 President & Vice President Messages Section -->
<section class="message-section">
  <h2 class="section-title">President & Vice President Messages</h2>

  <!-- 🟢 President Message -->
  <div class="message-card">
    <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQFf9tOZ_XCb-zNazXsoglZRGi-mMMyoYnflQ&s" alt="President" class="profile-img">
    <div class="message-content">
      <h3>Aminul Islam Bulbul</h3>
      <p>
        As the <strong>President of Bangladesh Cricket Board</strong>, I reaffirm our commitment to cricket development
        at all levels. Our vision is to nurture young talent, ensure professional excellence, and make Bangladesh
        a global cricketing force. Together, we aim to raise the spirit of our nation through dedication and teamwork.
      </p>
    </div>
  </div>

  <!-- 🔵 Vice President Message -->
  <div class="message-card">
    <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcT1ZzQBtVWuq7gb-3RzDL2hKFSbw73HbiNhAi5EBKdkF83AThdkamsEymtxpfqTQN1HRCY&usqp=CAU" alt="Vice President" class="profile-img">
    <div class="message-content">
      <h3>Faruque Ahmed</h3>
      <p>
        As <strong>Vice President</strong>, I proudly support our initiatives to promote and develop cricket nationwide.
        Our mission is to inspire the next generation, build strong leadership, and strengthen Bangladesh’s presence
        in world cricket with unity, passion, and excellence.
      </p>
    </div>
  </div>
</section>

<!-- 🌈 CSS Styling -->
<style>
.message-section {
  background: linear-gradient(135deg, #004aad, #00b4db);
  padding: 60px 30px;
  color: white;
  font-family: "Poppins", sans-serif;
  border-radius: 20px;
  box-shadow: 0px 10px 40px rgba(0, 0, 0, 0.3);
  margin-top: 40px;
  animation: fadeIn 1.2s ease-in-out;
}

.section-title {
  text-align: center;
  font-size: 2.5em;
  font-weight: 700;
  margin-bottom: 30px;
  text-transform: uppercase;
  letter-spacing: 2px;
  background: linear-gradient(90deg, #ffdd00, #ff6a00);
  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent;
}

.message-card {
  display: flex;
  align-items: flex-start;
  background: rgba(255, 255, 255, 0.15);
  border: 2px solid rgba(255, 255, 255, 0.2);
  border-radius: 16px;
  padding: 20px;
  margin: 20px 0;
  backdrop-filter: blur(10px);
  transition: transform 0.3s ease, box-shadow 0.3s ease;
}

.message-card:hover {
  transform: translateY(-8px);
  box-shadow: 0px 15px 40px rgba(0, 0, 0, 0.4);
}

.profile-img {
  width: 150px;
  height: 150px;
  border-radius: 15px;
  object-fit: cover;
  border: 3px solid #ffdd00;
  box-shadow: 0px 0px 20px rgba(255, 255, 255, 0.4);
  margin-right: 20px;
}

.message-content h3 {
  font-size: 1.6em;
  color: #ffeb3b;
  margin-bottom: 10px;
}

.message-content p {
  font-size: 1.05em;
  line-height: 1.7em;
  color: #f5f5f5;
  text-align: justify;
}

@keyframes fadeIn {
  from { opacity: 0; transform: translateY(20px); }
  to { opacity: 1; transform: translateY(0); }
}
</style>


            <div class="col-6 col-md-3">
          </div>
        </section>
      </div>

      <div class="col-lg-4">
        <div class="person-card mb-4 p-3">
          <div class="role">BCB President</div>
          <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQFf9tOZ_XCb-zNazXsoglZRGi-mMMyoYnflQ&s" alt="Aminul Islam ">
          <div class="py-3">
            <h6 class="mb-0">Aminul Islam Bulbul</h6>
            <small class="text-muted d-block mb-2">BCB President</small>
            <a href="#" class="btn btn-outline-primary btn-sm">Details</a>
          </div>
        </div>

        <div class="person-card mb-4 p-3">
          <div class="role vice">BCB Vice-President</div>
          <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcT1ZzQBtVWuq7gb-3RzDL2hKFSbw73HbiNhAi5EBKdkF83AThdkamsEymtxpfqTQN1HRCY&usqp=CAU" alt=" Faruq Ahmed">
          <div class="py-3">
            <h6 class="mb-0">Faruque Ahmed</h6>
            <small class="text-muted d-block mb-2">BCB Vice President</small>
            <a href="#" class="btn btn-outline-primary btn-sm">Details</a>
          </div>
        </div>

        <div class="card p-0 mb-4">
          <div class="p-3" style="background: linear-gradient(90deg,#00c6ff,#00dd88); color:white;">
            <h6 class="mb-0">Google Map</h6>
          </div>
          <div style="height:260px;">
            <iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3650.9535573891456!2d90.3661696149811!3d23.80931828457594!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x3755c7c5c5f4f3b1%3A0x7ff5c54f1f0a7b5b!2sSher-e-Bangla%20National%20Cricket%20Stadium%2C%20Mirpur!5e0!3m2!1sen!2sbd!4v1697710000000!5m2!1sen!2sbd"
            width="100%" height="100%" style="border:0;" allowfullscreen="" loading="lazy"></iframe>
          </div>
        </div>
      </div>
    </div>
  </div>
</main>

<footer id="contact">
  <div class="container">
    <div class="row align-items-center">
      <div class="col-md-6">
        <h5>Bangladesh Cricket Board</h5>
        <p>Mirpur, Dhaka — Hotline <strong>01887396300</strong></p>
        <div class="social-icons">
          <a href="#"><i class="fa-brands fa-facebook"></i></a>
          <a href="#"><i class="fa-brands fa-youtube"></i></a>
          <a href="#"><i class="fa-brands fa-twitter"></i></a>
        </div>
      </div>
      <div class="col-md-6 text-md-end mt-3 mt-md-0">
        <small>© <span id="year"></span> Bangladesh Cricket Board. All rights reserved.</small>
      </div>
    </div>
  </div>
</footer>

<!-- JS: Bootstrap + Swiper -->
<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/js/bootstrap.bundle.min.js"></script>
<script src="https://cdn.jsdelivr.net/npm/swiper@9/swiper-bundle.min.js"></script>
<script>
const swiper = new Swiper('.mySwiper', {
  loop: true,
  autoplay: { delay: 4500, disableOnInteraction: false },
  pagination: { el: '.swiper-pagination', clickable: true },
  navigation: { nextEl: '.swiper-button-next', prevEl: '.swiper-button-prev' },
});
document.getElementById('year').textContent = new Date().getFullYear();
</script>

</body>
</html> 
<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width,initial-scale=1">
  <title>About — History of Cricket in Bangladesh</title>
  <style>
    :root{
      --accent:#00bfa6;
      --accent2:#0078ff;
      --bg:#0f1724;
      --muted:#cbd5e1;
      font-family:'Poppins', system-ui, -apple-system, 'Segoe UI', Roboto, sans-serif;
    }
    *{box-sizing:border-box;transition:all .3s ease}
    body{
      margin:0;
      background:radial-gradient(circle at top left, #08142b, #0f1724 70%);
      color:#f8fafc;
      line-height:1.6;
      overflow-x:hidden;
    }
    .container{
      max-width:1100px;
      margin:50px auto;
      padding:30px;
      background:rgba(255,255,255,0.05);
      border-radius:20px;
      backdrop-filter:blur(20px);
      box-shadow:0 0 40px rgba(0,0,0,0.4);
    }
    header{
      display:flex;
      align-items:center;
      gap:18px;
      background:linear-gradient(135deg,#00bfa6,#0078ff);
      padding:18px 22px;
      border-radius:14px;
      color:#fff;
      box-shadow:0 6px 20px rgba(0,0,0,0.3);
    }
    .logo{
      width:70px;height:70px;
      border-radius:12px;
      background:#fff;
      color:#0078ff;
      font-weight:800;
      font-size:22px;
      display:flex;align-items:center;justify-content:center;
    }
    h1{margin:0;font-size:28px;letter-spacing:.5px;}
    p.lead{color:#e2e8f0;margin:6px 0 0;font-size:15px;}

    .timeline{
      background:rgba(255,255,255,0.03);
      border-radius:16px;
      padding:28px;
      margin-top:30px;
      box-shadow:inset 0 0 30px rgba(0,255,255,0.05);
    }

    .era{
      margin-bottom:40px;
      padding:20px;
      background:linear-gradient(135deg,rgba(0,184,255,0.1),rgba(0,255,204,0.08));
      border-radius:16px;
      box-shadow:0 0 20px rgba(0,0,0,0.3);
    }

    .era h2{
      font-size:22px;
      color:#00f5d4;
      text-transform:uppercase;
      letter-spacing:1px;
      border-left:5px solid #00bfa6;
      padding-left:10px;
      margin-bottom:20px;
    }

    .grid{
      display:grid;
      grid-template-columns:1fr 250px;
      gap:22px;
    }

    .card{
      background:rgba(255,255,255,0.05);
      border-radius:14px;
      padding:16px;
      box-shadow:0 4px 20px rgba(0,0,0,0.3);
      border:1px solid rgba(255,255,255,0.1);
    }

    .event{
      display:flex;
      gap:14px;
      padding:14px 0;
      border-bottom:1px solid rgba(255,255,255,0.08);
    }
    .event:last-child{border-bottom:0}
    .eyebrow{
      font-weight:700;
      color:#00eaff;
      width:86px;
      flex-shrink:0;
      font-size:16px;
    }
    .desc{
      color:#e2e8f0;
      font-size:15px;
    }
    .desc strong{
      color:#fff;
      font-weight:700;
      display:block;
      margin-bottom:4px;
    }

    .thumb, .thumb-small{
      width:100%;
      height:130px;
      object-fit:cover;
      border-radius:10px;
      border:2px solid rgba(255,255,255,0.1);
      box-shadow:0 4px 10px rgba(0,0,0,0.4);
      cursor:pointer;
      transition:transform .3s ease, box-shadow .3s ease;
    }
    .thumb:hover, .thumb-small:hover{
      transform:scale(1.05);
      box-shadow:0 6px 20px rgba(0,255,255,0.4);
    }

    .aside{
      display:flex;
      flex-direction:column;
      gap:14px;
    }

    .tag{
      display:inline-block;
      background:linear-gradient(90deg,#00bfa6,#0078ff);
      color:#fff;
      padding:6px 12px;
      border-radius:999px;
      font-size:13px;
      font-weight:600;
    }

    footer{
      text-align:center;
      color:#a7b1c1;
      font-size:14px;
      margin-top:30px;
      padding-top:20px;
      border-top:1px solid rgba(255,255,255,0.1);
    }

    /* ✨ Modal for image preview */
    .modal{
      position:fixed;inset:0;
      display:none;
      align-items:center;
      justify-content:center;
      background:rgba(0,0,0,0.8);
      z-index:1000;
      animation:fadeIn .4s ease;
    }
    .modal img{
      max-width:90%;
      max-height:85%;
      border-radius:14px;
      box-shadow:0 0 40px rgba(0,255,255,0.3);
    }
    .close{
      position:absolute;
      right:30px;top:20px;
      color:#fff;
      font-size:32px;
      cursor:pointer;
      font-weight:600;
    }

    @media (max-width:820px){
      .grid{grid-template-columns:1fr}
      header{flex-direction:column;text-align:center}
    }

    @keyframes fadeIn{
      from{opacity:0;transform:scale(.95);}
      to{opacity:1;transform:scale(1);}
    }
  </style>
</head>
<body>
  <div class="container">
    <header>
      <div class="logo">BC</div>
      <div>
        <h1>History of Cricket in Bangladesh</h1>
        <p class="lead">From the British era to modern-day masters — a concise timeline of key moments that shaped cricket in Bangladesh.</p>
      </div>
    </header>

    <main class="timeline">

      <section class="era">
        <h2>British Era (1792 - 1947)</h2>
        <div class="grid">
          <div class="card">
            <div class="event">
              <div class="eyebrow">1792</div>
              <div class="desc">
                <strong>Sub-Continental Cricket in British Era</strong>
                <div style="color:#a0aec0;font-size:14px;margin-top:6px">Cricket flourished in Bengal during the British era. Centering Calcutta, cricket gained popularity among the general mass and evolved over the years in West Bengal and present Bangladesh.</div>
              </div>
            </div>

            <div class="event">
              <div class="eyebrow">1941</div>
              <div class="desc">
                <strong>Governor's XI plays at Dacca Stadium</strong>
                <div style="color:#a0aec0;font-size:14px;margin-top:6px">The earliest notable match in Dhaka was in February 1941 when a Bengal Governor's XI played the Bengal Gymkhana at the Dacca Stadium (now Bangabandhu National Stadium).</div>
              </div>
            </div>
          </div>

          <aside class="aside">
            <img src="https://www.tigercricket.com.bd/images/2022/03/1.jpeg" alt="1792 Sub-Continental Cricket" class="thumb-small" loading="lazy" onclick="openModal(this.src,'Sub-Continental Cricket (1792)')">
            <img src="https://www.tigercricket.com.bd/images/2022/03/2.png" alt="1941 Governor's XI at Dacca Stadium" class="thumb-small" loading="lazy" onclick="openModal(this.src,'Governor\'s XI at Dacca Stadium (1941)')">
            <div style="font-size:13px;color:#a7b1c1"><span class="tag">British Era</span> Key early matches and venues that seeded cricket across Bengal.</div>
          </aside>
        </div>
      </section>

      <section class="era">
        <h2>East Pakistan Era (1947 - 1971)</h2>
        <div class="grid">
          <div class="card">
            <div class="event">
              <div class="eyebrow">1950</div>
              <div class="desc">
                <strong>The First Test in Bangladesh</strong>
                <div style="color:#a0aec0;font-size:14px;margin-top:6px">After 1947 partition, regional East Pakistani teams took part in Pakistan domestic cricket. Dhaka hosted several Tests between 1955 and 1969, starting with Pakistan vs India in January 1955 at the newly built Dacca Stadium (capacity ~15,000).</div>
              </div>
            </div>

            <div class="event">
              <div class="eyebrow">1960</div>
              <div class="desc">
                <strong>Dacca Stadium becomes a regular venue</strong>
                <div style="color:#a0aec0;font-size:14px;margin-top:6px">Matches involving Pakistan, New Zealand, West Indies, Australia and England visited Dhaka between the late 1950s and 1969, establishing the stadium as a regular Test venue.</div>
              </div>
            </div>

          </div>

          <aside class="aside">
            <img src="https://www.tigercricket.com.bd/images/2022/03/3.jpeg" alt="1950 First Test" class="thumb-small" loading="lazy" onclick="openModal(this.src,'First Test (1950)')">
            <img src="https://www.tigercricket.com.bd/images/2022/03/4.jpeg" alt="1960 Dacca Stadium" class="thumb-small" loading="lazy" onclick="openModal(this.src,'Dacca Stadium (1960)')">
            <div style="font-size:13px;color:#a7b1c1"><span class="tag">East Pakistan Era</span> Dhaka hosted international sides and became a recognized cricket venue.</div>
          </aside>
        </div>
      </section>

      <section class="era">
        <h2>Bangladesh Era (1971 - Present)</h2>
        <div class="grid">
          <div class="card">
            <div class="event">
              <div class="eyebrow">1972</div>
              <div class="desc">
                <strong>The Establishment</strong>
                <div style="color:#a0aec0;font-size:14px;margin-top:6px">The Bangladesh Cricket Control Board (BCCB) is established and domestic leagues start in Dhaka and Chittagong despite early post-war challenges.</div>
              </div>
            </div>

            <div class="event">
              <div class="eyebrow">1974</div>
              <div class="desc">
                <strong>First Steps in Domestic Cricket</strong>
                <div style="color:#a0aec0;font-size:14px;margin-top:6px">National tournaments and district leagues (1st & 2nd divisions) begin, alongside youth, university, college and school competitions that grew the grassroots game.</div>
              </div>
            </div>

            <div class="event">
              <div class="eyebrow">1976</div>
              <div class="desc">
                <strong>MCC tours Bangladesh</strong>
                <div style="color:#a0aec0;font-size:14px;margin-top:6px">The MCC toured in December 1976; enthusiasm soared as tens of thousands attended representative matches. BCCB drafted its first constitution and pushed for ICC membership.</div>
              </div>
            </div>

            <div class="event">
              <div class="eyebrow">1977</div>
              <div class="desc">
                <strong>ICC Associate Membership</strong>
                <div style="color:#a0aec0;font-size:14px;margin-top:6px">On 26 July 1977 Bangladesh became an Associate member of the ICC and welcomed its first foreign coach, Robert Jones, sent by the MCC.</div>
              </div>
            </div>

            <div class="event">
              <div class="eyebrow">1978–1982</div>
              <div class="desc">
                <strong>Tours and International Competitions</strong>
                <div style="color:#a0aec0;font-size:14px;margin-top:6px">Sri Lanka visited (1978); Bangladesh appeared in the ICC Trophy (1979) winning matches against Fiji and Malaysia; Pakistan and other teams toured and Bangladesh finished 4th in the 1982 ICC Trophy.</div>
              </div>
            </div>
          </div>

          <aside class="aside">
            <img src="https://www.tigercricket.com.bd/images/2022/03/5.jpeg" alt="1976 MCC tour" class="thumb-small" loading="lazy" onclick="openModal(this.src,'MCC tour (1976)')">
            <div style="font-size:13px;color:#a7b1c1"><span class="tag">Bangladesh Era</span> Formation, international recognition and steady growth toward test status and broader success.</div>
          </aside>
        </div>
      </section>

      <footer>
        <div>Sources: Compiled history notes and archival images.</div>
        <div style="margin-top:6px">Made with ❤️ — <small>Images used from provided URLs</small></div>
      </footer>

    </main>
  </div>

  <div id="imgModal" class="modal" onclick="closeModal(event)">
    <span class="close" onclick="closeModal(event)">&times;</span>
    <img id="modalImg" src="" alt=""/>
  </div>

  <script>
    function openModal(src, alt){
      var m=document.getElementById('imgModal');
      var i=document.getElementById('modalImg');
      i.src=src; i.alt=alt; m.style.display='flex';
    }
    function closeModal(e){
      if(e.target!==e.currentTarget && e.target.className!=='close')return;
      var m=document.getElementById('imgModal');
      m.style.display='none';
      document.getElementById('modalImg').src='';
    }
  </script>
</body>
</html>
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<title>BCB Gallery - Bangladesh Cricket Board</title>

<!-- Bootstrap 5 -->
<link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/css/bootstrap.min.css" rel="stylesheet">

<!-- Font Awesome -->
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.0/css/all.min.css"/>

<style>
:root {
  --grad-main: linear-gradient(90deg, #009688, #00bcd4, #4caf50);
  --grad-bg: linear-gradient(135deg, #d0f0f7, #f1ffe0, #e8f8ff);
  --card-shadow: 0 8px 25px rgba(0,0,0,0.15);
}

body {
  font-family: 'Poppins', sans-serif;
  background: var(--grad-bg);
  color: #222;
  margin: 0;
  padding: 0;
  overflow-x: hidden;
}

/* Header */
.header {
  background: var(--grad-main);
  color: white;
  padding: 25px 0;
  text-align: center;
  box-shadow: 0 4px 15px rgba(0,0,0,0.2);
  position: relative;
}

.header img {
  width: 90px;
  height: 90px;
  border-radius: 50%;
  border: 3px solid white;
  margin-bottom: 10px;
  transition: transform 0.4s ease;
}
.header img:hover {
  transform: rotate(10deg) scale(1.1);
}

.header h1 {
  font-weight: 700;
  letter-spacing: 1px;
}
.header p {
  opacity: 0.9;
  font-size: 1.1rem;
}
.header a {
  background: white;
  color: #009688;
  font-weight: 600;
  border-radius: 25px;
  padding: 6px 16px;
  text-decoration: none;
  transition: all 0.3s;
}
.header a:hover {
  background: #00695c;
  color: white;
}

/* Gallery Section */
.gallery-section {
  padding: 60px 40px;
  max-width: 1400px;
  margin: auto;
}
.gallery-title {
  text-align: center;
  font-size: 2.6em;
  font-weight: 800;
  margin-bottom: 50px;
  background: linear-gradient(90deg, #00897b, #4db6ac, #00acc1);
  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent;
}
.gallery-grid {
  display: grid;
  grid-template-columns: repeat(4, 1fr);
  gap: 25px;
}
.gallery-item {
  position: relative;
  overflow: hidden;
  border-radius: 18px;
  box-shadow: var(--card-shadow);
  cursor: pointer;
  transition: transform 0.4s ease, box-shadow 0.3s ease;
}
.gallery-item:hover {
  transform: scale(1.05);
  box-shadow: 0 12px 35px rgba(0,0,0,0.25);
}
.gallery-item img {
  width: 100%;
  height: 250px;
  object-fit: cover;
  border-radius: 18px;
  transition: 0.4s ease;
}
.gallery-item:hover img {
  filter: brightness(0.85) contrast(1.1);
}
.gallery-item .caption {
  position: absolute;
  bottom: 0;
  width: 100%;
  padding: 12px 15px;
  background: rgba(0, 0, 0, 0.55);
  color: white;
  font-size: 1rem;
  text-align: center;
  font-weight: 500;
}

/* Lightbox */
.lightbox {
  position: fixed;
  inset: 0;
  background: rgba(0, 0, 0, 0.85);
  display: none;
  align-items: center;
  justify-content: center;
  z-index: 1000;
}
.lightbox img {
  max-width: 90%;
  max-height: 85%;
  border-radius: 15px;
  box-shadow: 0 0 25px rgba(255,255,255,0.3);
}
.lightbox.active {
  display: flex;
}
.close-btn {
  position: fixed;
  top: 30px;
  right: 40px;
  font-size: 40px;
  color: white;
  cursor: pointer;
  transition: 0.3s;
}
.close-btn:hover {
  color: #ffeb3b;
  transform: scale(1.2);
}

/* Responsive */
@media (max-width: 992px) {
  .gallery-grid { grid-template-columns: repeat(2, 1fr); }
}
@media (max-width: 600px) {
  .gallery-grid { grid-template-columns: 1fr; }
  .header img { width: 70px; height: 70px; }
}

/* Footer */
footer {
  background: #004d40;
  color: #cfeaf3;
  text-align: center;
  padding: 25px 0;
  margin-top: 60px;
  font-size: 15px;
  letter-spacing: 0.4px;
}
footer a {
  color: #aee6ff;
  text-decoration: none;
}
footer a:hover {
  text-decoration: underline;
}
</style>
</head>
<body>

<header class="header">
  <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSMsoVqejAmUo6m6AKjQ7vhzxYZCW-Jo3NsPQ&s" alt="BCB Logo">
  <h1><i class="fa-solid fa-trophy me-2"></i>Bangladesh Cricket Board Gallery</h1>
  <p>Glorious Moments of Tigers 🏏</p>
  <a href="/NadimBCB.HTML"><i class="fa fa-home"></i> Back to Home</a>
</header>

<section class="gallery-section">
  <h2 class="gallery-title">✨ Bangladesh Cricket Highlights</h2>
  <div class="gallery-grid">

    <div class="gallery-item">
      <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRXgwJzLh24LZoXwGNoLVuDK-EB0tzLKxxxwA&s" alt="Sher-e-Bangla">
      <div class="caption">Sher-e-Bangla Stadium, Mirpur</div>
    </div>

    <div class="gallery-item">
      <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQ8teMbBhjVgGDwUV_vqN6-ERk5adm6r7mgJM-X4nZSJg6Jbn2XhA5ZxD92or1EbdAHPHI&usqp=CAU" alt="Chattogram">
      <div class="caption">Zahur Ahmed Chowdhury Stadium, Chattogram</div>
    </div>

    <div class="gallery-item">
      <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSBYj4y5WtVHGFVXt0A_VwoonOvJ0ybEETiDg&s" alt="Sylhet">
      <div class="caption">Sylhet International Cricket Stadium</div>
    </div>

    <div class="gallery-item">
      <img src="https://bashat.com.bd/wp-content/uploads/2025/03/1-20-Copy.jpg" alt="National Stadium">
      <div class="caption">Bangladesh National Stadium, Gulistan</div>
    </div>

    <div class="gallery-item">
      <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQ1K8mCTmrz0nGRAF9bRAmgYd4urAB0os8gZQ&s" alt="Team Bangladesh">
      <div class="caption">Bangladesh National Team</div>
    </div>

    <div class="gallery-item">
      <img src="https://img.cricketnmore.com/uploads/gallery/1403242948bangladesh-cricket-team.jpg" alt="Winning Moment">
      <div class="caption">Wicket Celebration</div>
    </div>

    <div class="gallery-item">
      <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQTkFFspd0QLyw0JbGUKy1kDz2bagSC5ow4RpxuRpjpmQMjvkKqBNWg9M9CewzRNnogCRw&usqp=CAU" alt="Players Celebration">
      <div class="caption">Sad Moments</div>
    </div>

    <div class="gallery-item">
      <img src="https://c.ndtvimg.com/2020-02/0n13gidg_bangladesh-under19-icc_625x300_10_February_20.jpg" alt="Team Photo">
      <div class="caption">Under19 World Cup Champions</div>
    </div>
    <div class="gallery-item">
      <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSzyba5ZhIIGHHke5EH5f68R5uAuADXkJirXg&s" alt="Team Bangladesh">
      <div class="caption">Fans With Tigers</div>
    </div>

    <div class="gallery-item">
      <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRgcBOCPeyQ-5SVf0QAObsD3RhUS4SGxg4Reg&s" alt="Winning Moment">
      <div class="caption">Victory Celebration 2024</div>
    </div>

    <div class="gallery-item">
      <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRzKjKauw3_s-m3klEXjZn6eMKYHzIXdvizug&s" alt="Players Celebration">
      <div class="caption">Bangladesh Cricket Fans</div>
    </div>

    <div class="gallery-item">
      <img src="https://amarbangla.co/wp-content/uploads/2022/02/Bangladesh-Cricket-1.jpg" alt="Team Photo">
      <div class="caption">Bangladesh Tigers Team Spirit</div>
    </div>

  </div>
</section>

<!-- Lightbox -->
<div class="lightbox" id="lightbox">
  <span class="close-btn" id="closeBtn">&times;</span>
  <img src="" alt="Expanded Photo" id="lightboxImg">
</div>

<footer>
  <p>© <span id="year"></span> Bangladesh Cricket Board | Designed by <strong>Nadimul Islam</strong></p>
</footer>

<script>
document.getElementById('year').textContent = new Date().getFullYear();

const lightbox = document.getElementById('lightbox');
const lightboxImg = document.getElementById('lightboxImg');
const closeBtn = document.getElementById('closeBtn');

document.querySelectorAll('.gallery-item img').forEach(img => {
  img.addEventListener('click', () => {
    lightbox.classList.add('active');
    lightboxImg.src = img.src;
  });
});

closeBtn.addEventListener('click', () => {
  lightbox.classList.remove('active');
});
lightbox.addEventListener('click', (e) => {
  if (e.target !== lightboxImg) lightbox.classList.remove('active');
});
</script>

</body>
</html>
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<title>Contact | Bangladesh Cricket Board</title>

<!-- Bootstrap -->
<link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/css/bootstrap.min.css" rel="stylesheet">
<!-- Font Awesome -->
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.0/css/all.min.css"/>

<style>
/* 🌈 Animated Gradient Background */
body {
  font-family: "Poppins", sans-serif;
  background: linear-gradient(270deg, #001f3f, #004aad, #00c6ff, #00ffcc);
  background-size: 800% 800%;
  animation: gradientBG 12s ease infinite;
  color: white;
  margin: 0;
  padding: 0;
  overflow-x: hidden;
}

/* Smooth Background Motion */
@keyframes gradientBG {
  0% {background-position: 0% 50%;}
  50% {background-position: 100% 50%;}
  100% {background-position: 0% 50%;}
}

/* 🔰 Header */
header {
  text-align: center;
  padding: 40px 15px 20px;
  background: rgba(0, 0, 0, 0.25);
  backdrop-filter: blur(10px);
  box-shadow: 0 8px 30px rgba(0,0,0,0.3);
  border-bottom: 1px solid rgba(255,255,255,0.3);
}
header img {
  width: 90px;
  height: 90px;
  border-radius: 50%;
  border: 3px solid #00eaff;
  box-shadow: 0 0 25px #00eaff;
}
header h1 {
  font-size: 2.2rem;
  font-weight: 700;
  margin-top: 10px;
  color: #fff;
  text-shadow: 0 0 10px #00eaff;
}
header nav a {
  color: #e6faff;
  margin: 0 12px;
  text-decoration: none;
  font-weight: 600;
  transition: all 0.3s ease;
}
header nav a:hover {
  color: #00ffcc;
  text-shadow: 0 0 12px #00ffcc;
}

/* 💎 Contact Section */
.contact-section {
  max-width: 900px;
  margin: 60px auto;
  padding: 40px 30px;
  background: rgba(255,255,255,0.1);
  border: 1px solid rgba(255,255,255,0.2);
  backdrop-filter: blur(15px);
  border-radius: 20px;
  box-shadow: 0 0 25px rgba(0,255,204,0.3);
  animation: fadeIn 1.2s ease-in-out;
}
@keyframes fadeIn {
  from {opacity: 0; transform: translateY(20px);}
  to {opacity: 1; transform: translateY(0);}
}

.contact-section h2 {
  text-align: center;
  font-weight: 700;
  margin-bottom: 35px;
  color: #00ffcc;
  text-shadow: 0 0 15px #00ffcc;
}

/* 🧾 Form Design */
form label {
  font-weight: 600;
  color: #fff;
}
form input, form textarea {
  border-radius: 10px;
  border: none;
  background: rgba(255,255,255,0.15);
  color: white;
  transition: all 0.3s ease;
}
form input:focus, form textarea:focus {
  background: rgba(255,255,255,0.25);
  box-shadow: 0 0 12px #00eaff;
  outline: none;
}
form button {
  background: linear-gradient(90deg, #00c6ff, #00ffcc);
  color: #000;
  font-weight: 700;
  padding: 12px 30px;
  border-radius: 50px;
  border: none;
  transition: 0.3s ease;
  box-shadow: 0 0 20px rgba(0,255,204,0.4);
}
form button:hover {
  transform: scale(1.08);
  box-shadow: 0 0 40px rgba(0,255,204,0.8);
}

/* 📞 Contact Info */
.contact-info {
  text-align: center;
  margin-top: 40px;
}
.contact-info p {
  font-size: 1.1rem;
  margin-bottom: 10px;
  color: #e6faff;
}
.contact-info i {
  color: #00ffcc;
  margin-right: 8px;
}

/* ⚡ Footer */
footer {
  text-align: center;
  padding: 25px 10px;
  background: rgba(0,0,0,0.4);
  border-top: 1px solid rgba(255,255,255,0.2);
  color: #cfeaf3;
  font-size: 0.95rem;
}
footer strong {
  color: #00ffcc;
}
footer a {
  color: #00eaff;
  text-decoration: none;
}
footer a:hover {
  text-shadow: 0 0 10px #00eaff;
}

/* Responsive */
@media (max-width: 768px) {
  header h1 {font-size: 1.7rem;}
  .contact-section {margin: 30px 15px; padding: 30px 20px;}
}
</style>
</head>
<body>

<!-- Header -->
<header>
  <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSMsoVqejAmUo6m6AKjQ7vhzxYZCW-Jo3NsPQ&s" alt="BCB Logo">
  <h1>Contact Bangladesh Cricket Board</h1>
  <nav>
    <a href="/NadimBCB.HTML">🏠 Home</a>
   
   
</header>

<!-- Contact Form -->
<section class="contact-section">
  <h2>Get in Touch</h2>
  <form>
    <div class="mb-3">
      <label for="name">Full Name</label>
      <input type="text" id="name" class="form-control" placeholder="Enter your full name">
    </div>
    <div class="mb-3">
      <label for="email">Email Address</label>
      <input type="email" id="email" class="form-control" placeholder="Enter your email">
    </div>
    <div class="mb-3">
      <label for="phone">Phone Number</label>
      <input type="text" id="phone" class="form-control" placeholder="+880...">
    </div>
    <div class="mb-3">
      <label for="message">Your Message</label>
      <textarea id="message" rows="5" class="form-control" placeholder="Write your message here..."></textarea>
    </div>
    <div class="text-center">
      <button type="button" class="btn btn-lg">Send Message</button>
    </div>
  </form>

  <div class="contact-info mt-4">
    <p><i class="fa-solid fa-user"></i> <strong>Nadimul Islam</strong></p>
    <p><i class="fa-solid fa-school"></i> Cumilla Polytechnic Institute</p>
    <p><i class="fa-solid fa-phone"></i> +8801XXXXXXXXX</p>
    <p><i class="fa-solid fa-envelope"></i> nadimul@example.com</p>
  </div>
</section>

<footer>
  © 2025 Bangladesh Cricket Board | Designed by <strong>Nadimul Islam</strong> |
  <a href="index.html">Back to Home</a>
</footer>

</body>
</html>
