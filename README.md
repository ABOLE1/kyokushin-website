<!DOCTYPE html>
<html lang="fa" dir="rtl">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>استاد کیوکوشین - بیوگرافی، گالری و تماس | کیوکوشین ساباکی ایران</title>
  <meta name="description" content="صفحه رسمی استاد کیوکوشین، نماینده سبک ساباکی در ایران با بیش از 20 سال سابقه آموزش هنرهای رزمی">
  <link href="https://cdn.jsdelivr.net/gh/rastikerdar/vazir-font@v30.1.0/dist/font-face.css" rel="stylesheet" type="text/css" />
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
  <style>
    :root {
      --primary-color: #d10a11;
      --secondary-color: #222;
      --text-color: #eee;
      --background-color: #111;
    }
    
    body {
      font-family: 'Vazir', sans-serif;
      background-color: var(--background-color);
      color: var(--text-color);
      margin: 0;
      padding: 0;
      line-height: 1.6;
    }
    
    header {
      background-color: var(--secondary-color);
      padding: 1.5rem;
      text-align: center;
      border-bottom: 4px solid var(--primary-color);
      position: relative;
    }
    
    header h1 {
      margin: 0;
      font-size: 2.5rem;
      color: var(--primary-color);
      text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.5);
    }
    
    .logo {
      position: absolute;
      left: 20px;
      top: 50%;
      transform: translateY(-50%);
      width: 80px;
    }
    
    nav {
      display: flex;
      justify-content: center;
      gap: 1.5rem;
      background-color: #000;
      padding: 1rem;
      flex-wrap: wrap;
      position: sticky;
      top: 0;
      z-index: 100;
    }
    
    nav a {
      color: white;
      text-decoration: none;
      font-weight: bold;
      padding: 0.5rem 1rem;
      border-radius: 5px;
      transition: all 0.3s ease;
    }
    
    nav a:hover, nav a:focus {
      background-color: var(--primary-color);
      transform: translateY(-3px);
    }
    
    section {
      padding: 2rem 10%;
      max-width: 1200px;
      margin: 0 auto;
    }
    
    .bio, .gallery, .honors, .contact, .comments {
      margin-bottom: 3rem;
      background-color: rgba(0, 0, 0, 0.3);
      padding: 2rem;
      border-radius: 10px;
      box-shadow: 0 5px 15px rgba(0, 0, 0, 0.5);
    }
    
    h2 {
      color: var(--primary-color);
      font-size: 1.8rem;
      border-bottom: 2px solid var(--primary-color);
      padding-bottom: 0.5rem;
      margin-top: 0;
    }
    
    .profile-img {
      max-width: 100%;
      border-radius: 10px;
      float: left;
      shape-outside: circle(50%);
      margin: 0 1.5rem 1rem 0;
      border: 5px solid var(--primary-color);
      box-shadow: 0 5px 15px rgba(0, 0, 0, 0.5);
    }
    
    .gallery-container {
      display: grid;
      grid-template-columns: repeat(auto-fill, minmax(300px, 1fr));
      gap: 1rem;
      margin-top: 1.5rem;
    }
    
    .gallery-item {
      position: relative;
      overflow: hidden;
      border-radius: 10px;
      border: 3px solid var(--primary-color);
      transition: transform 0.3s ease;
      height: 250px;
    }
    
    .gallery-item:hover {
      transform: scale(1.03);
    }
    
    .gallery-item img {
      width: 100%;
      height: 100%;
      object-fit: cover;
      transition: transform 0.5s ease;
    }
    
    .gallery-item:hover img {
      transform: scale(1.1);
    }
    
    .honors-list {
      list-style-type: none;
      padding: 0;
    }
    
    .honors-list li {
      background-color: rgba(210, 10, 17, 0.1);
      margin-bottom: 0.8rem;
      padding: 1rem;
      border-right: 4px solid var(--primary-color);
      border-radius: 5px;
      position: relative;
      padding-right: 2rem;
    }
    
    .honors-list li::before {
      content: "🏆";
      position: absolute;
      right: 0.5rem;
      top: 50%;
      transform: translateY(-50%);
    }
    
    .contact-info {
      display: flex;
      flex-wrap: wrap;
      gap: 2rem;
      margin-top: 1.5rem;
    }
    
    .contact-card {
      background-color: rgba(210, 10, 17, 0.1);
      padding: 1.5rem;
      border-radius: 10px;
      flex: 1;
      min-width: 250px;
      border: 1px solid var(--primary-color);
      transition: transform 0.3s ease;
    }
    
    .contact-card:hover {
      transform: translateY(-5px);
    }
    
    .contact-card i {
      color: var(--primary-color);
      margin-left: 0.5rem;
      font-size: 1.2rem;
    }
    
    .map-container {
      margin-top: 2rem;
      border-radius: 10px;
      overflow: hidden;
      box-shadow: 0 5px 15px rgba(0, 0, 0, 0.5);
      height: 300px;
    }
    
    form {
      margin-top: 1.5rem;
    }
    
    .form-group {
      margin-bottom: 1.2rem;
    }
    
    form label {
      display: block;
      margin-bottom: 0.5rem;
      font-weight: bold;
    }
    
    form input, form textarea {
      width: 100%;
      padding: 0.8rem;
      margin: 0.5rem 0;
      border: 1px solid #444;
      border-radius: 8px;
      background-color: #222;
      color: white;
      font-family: 'Vazir', sans-serif;
    }
    
    form input:focus, form textarea:focus {
      outline: none;
      border-color: var(--primary-color);
      box-shadow: 0 0 5px rgba(210, 10, 17, 0.5);
    }
    
    form button {
      background-color: var(--primary-color);
      color: white;
      padding: 0.8rem 1.5rem;
      border: none;
      border-radius: 8px;
      cursor: pointer;
      font-weight: bold;
      font-family: 'Vazir', sans-serif;
      transition: all 0.3s ease;
      display: inline-flex;
      align-items: center;
      gap: 0.5rem;
    }
    
    form button:hover {
      background-color: #b0080e;
      transform: translateY(-2px);
      box-shadow: 0 5px 10px rgba(0, 0, 0, 0.3);
    }
    
    .social-links {
      display: flex;
      gap: 1rem;
      margin-top: 1.5rem;
    }
    
    .social-links a {
      color: white;
      background-color: var(--secondary-color);
      width: 40px;
      height: 40px;
      border-radius: 50%;
      display: flex;
      align-items: center;
      justify-content: center;
      transition: all 0.3s ease;
    }
    
    .social-links a:hover {
      background-color: var(--primary-color);
      transform: translateY(-3px);
    }
    
    footer {
      background-color: #000;
      color: #aaa;
      text-align: center;
      padding: 2rem;
      border-top: 2px solid var(--primary-color);
      margin-top: 2rem;
    }
    
    .copyright {
      margin-top: 1rem;
    }
    
    @media (max-width: 768px) {
      header h1 {
        font-size: 2rem;
      }
      
      .logo {
        position: static;
        transform: none;
        margin-bottom: 1rem;
      }
      
      section {
        padding: 1.5rem;
      }
      
      .profile-img {
        float: none;
        margin: 0 auto 1.5rem;
        display: block;
      }
      
      .gallery-container {
        grid-template-columns: 1fr;
      }
    }
    
    /* انیمیشن‌ها */
    @keyframes fadeIn {
      from { opacity: 0; transform: translateY(20px); }
      to { opacity: 1; transform: translateY(0); }
    }
    
    section {
      animation: fadeIn 0.8s ease forwards;
    }
    
    /* اسلایدر گالری */
    .slider-container {
      position: relative;
      max-width: 800px;
      margin: 0 auto;
    }
    
    .slider {
      display: flex;
      overflow: hidden;
      border-radius: 10px;
      border: 3px solid var(--primary-color);
    }
    
    .slide {
      min-width: 100%;
      transition: transform 0.5s ease;
    }
    
    .slide img {
      width: 100%;
      display: block;
    }
    
    .slider-nav {
      display: flex;
      justify-content: center;
      margin-top: 1rem;
    }
    
    .slider-dot {
      width: 12px;
      height: 12px;
      border-radius: 50%;
      background-color: #444;
      margin: 0 5px;
      cursor: pointer;
      transition: background-color 0.3s ease;
    }
    
    .slider-dot.active {
      background-color: var(--primary-color);
    }
  </style>
</head>
<body>

  <header>
    <img src="https://via.placeholder.com/80" alt="لوگو کیوکوشین ساباکی" class="logo">
    <h1>استاد کیوکوشین</h1>
    <p>نماینده رسمی سبک ساباکی در ایران</p>
  </header>

  <nav>
    <a href="#bio"><i class="fas fa-user"></i> بیوگرافی</a>
    <a href="#gallery"><i class="fas fa-images"></i> گالری</a>
    <a href="#honors"><i class="fas fa-trophy"></i> احکام و افتخارات</a>
    <a href="#contact"><i class="fas fa-address-card"></i> تماس با ما</a>
    <a href="#comments"><i class="fas fa-comment"></i> نظرات</a>
  </nav>

  <section id="bio" class="bio">
    <h2><i class="fas fa-user-tie"></i> بیوگرافی استاد</h2>
    <img src="https://via.placeholder.com/400x500" alt="تصویر استاد کیوکوشین" class="profile-img">
    <p>استاد <strong>عبدالصمد کیوکوشین</strong> متولد سال 1355 در تهران، از سن 12 سالگی تمرینات هنرهای رزمی را آغاز نمودند. ایشان پس از کسب مدارج مختلف در سبک‌های مختلف رزمی، در سال 1380 به سبک کیوکوشین ساباکی روی آوردند و در مدت کوتاهی به درجات عالی این سبک دست یافتند.</p>
    <p>استاد کیوکوشین با بیش از 25 سال سابقه آموزش، شاگردان بسیاری را تربیت کرده‌اند که بسیاری از آن‌ها امروز از مربیان و قهرمانان مطرح کشور هستند. فلسفه آموزشی ایشان ترکیبی از نظم، احترام و قدرت است که در قالب هنر رزمی کیوکوشین به شاگردان منتقل می‌شود.</p>
    <p>ایشان در سال 1390 به عنوان نماینده رسمی سبک ساباکی در ایران منصوب شدند و تاکنون چندین دوره مربیگری بین‌المللی را در ایران برگزار کرده‌اند. استاد کیوکوشین همچنین سابقه مربیگری تیم ملی کاراته ایران در مسابقات آسیایی را در کارنامه خود دارند.</p>
    <div class="stats" style="display: flex; justify-content: space-around; flex-wrap: wrap; margin-top: 2rem; text-align: center;">
      <div style="margin: 1rem;">
        <div style="font-size: 2rem; color: var(--primary-color); font-weight: bold;">25+</div>
        <div>سال تجربه</div>
      </div>
      <div style="margin: 1rem;">
        <div style="font-size: 2rem; color: var(--primary-color); font-weight: bold;">500+</div>
        <div>شاگرد تربیت شده</div>
      </div>
      <div style="margin: 1rem;">
        <div style="font-size: 2rem; color: var(--primary-color); font-weight: bold;">50+</div>
        <div>قهرمان ملی</div>
      </div>
      <div style="margin: 1rem;">
        <div style="font-size: 2rem; color: var(--primary-color); font-weight: bold;">10+</div>
        <div>دوره بین‌المللی</div>
      </div>
    </div>
  </section>

  <section id="gallery" class="gallery">
    <h2><i class="fas fa-camera"></i> گالری تصاویر</h2>
    <div class="slider-container">
      <div class="slider">
        <div class="slide">
          <img src="https://via.placeholder.com/800x500" alt="تمرینات استاد">
        </div>
        <div class="slide">
          <img src="https://via.placeholder.com/800x500" alt="مسابقات">
        </div>
        <div class="slide">
          <img src="https://via.placeholder.com/800x500" alt="سمینارها">
        </div>
      </div>
      <div class="slider-nav">
        <div class="slider-dot active"></div>
        <div class="slider-dot"></div>
        <div class="slider-dot"></div>
      </div>
    </div>
    
    <div class="gallery-container">
      <div class="gallery-item">
        <img src="https://via.placeholder.com/300x250" alt="تمرینات گروهی">
      </div>
      <div class="gallery-item">
        <img src="https://via.placeholder.com/300x250" alt="اعطای کمربند">
      </div>
      <div class="gallery-item">
        <img src="https://via.placeholder.com/300x250" alt="مسابقات استاد">
      </div>
      <div class="gallery-item">
        <img src="https://via.placeholder.com/300x250" alt="سمینار آموزشی">
      </div>
      <div class="gallery-item">
        <img src="https://via.placeholder.com/300x250" alt="تمرینات فردی">
      </div>
      <div class="gallery-item">
        <img src="https://via.placeholder.com/300x250" alt="افتخارات">
      </div>
    </div>
  </section>

  <section id="honors" class="honors">
    <h2><i class="fas fa-award"></i> احکام و افتخارات</h2>
    <ul class="honors-list">
      <li>حکم دان 5 از سازمان جهانی کیوکوشین ساباکی (2023)</li>
      <li>نماینده رسمی سبک ساباکی در ایران از سال 1390 تاکنون</li>
      <li>مدرس رسمی فدراسیون کاراته ایران از سال 1385</li>
      <li>مربی تیم ملی کاراته ایران در مسابقات آسیایی 2018</li>
      <li>برنده مدال طلا مسابقات بین‌المللی ژاپن 2015</li>
      <li>داوری بین‌المللی در مسابقات جهانی مالزی 2019</li>
      <li>مؤلف کتاب "فلسفه رزم در کیوکوشین" (1395)</li>
      <li>برنده جایزه بهترین مربی سال از فدراسیون کاراته (1397)</li>
      <li>مبتکر سبک ترکیبی کیوکوشین ساباکی-کیک‌بوکسینگ (1398)</li>
      <li>دارای مدرک بین‌المللی مربیگری از سازمان WKO (2021)</li>
    </ul>
  </section>

  <section id="contact" class="contact">
    <h2><i class="fas fa-envelope"></i> تماس با ما</h2>
    <div class="contact-info">
      <div class="contact-card">
        <h3><i class="fas fa-phone"></i> تماس تلفنی</h3>
        <p><a href="tel:+989361640746">+98 936 164 0746</a></p>
        <p><a href="tel:+982188776655">021-88776655</a></p>
      </div>
      <div class="contact-card">
        <h3><i class="fas fa-envelope"></i> ایمیل</h3>
        <p><a href="mailto:abolesayadi@gmail.com">abolesayadi@gmail.com</a></p>
      </div>
      <div class="contact-card">
        <h3><i class="fas fa-map-marker-alt"></i> آدرس باشگاه</h3>
        <p>تهران، خیابان ولیعصر، بالاتر از میدان ولیعصر، کوچه فلان، پلاک 123</p>
      </div>
    </div>
    
    <div class="map-container">
      <iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3239.748241483434!2d51.41437131526957!3d35.715523980187576!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x0%3A0x0!2zMzXCsDQyJzU1LjkiTiA1McKwMjQnNTUuMyJF!5e0!3m2!1sen!2sus!4v1620000000000!5m2!1sen!2sus" width="100%" height="100%" style="border:0;" allowfullscreen="" loading="lazy"></iframe>
    </div>
    
    <div class="social-links">
      <a href="#" aria-label="اینستاگرام"><i class="fab fa-instagram"></i></a>
      <a href="#" aria-label="تلگرام"><i class="fab fa-telegram"></i></a>
      <a href="#" aria-label="واتساپ"><i class="fab fa-whatsapp"></i></a>
      <a href="#" aria-label="یوتیوب"><i class="fab fa-youtube"></i></a>
    </div>
  </section>

  <section id="comments" class="comments">
    <h2><i class="fas fa-comments"></i> نظرات شاگردان</h2>
    
    <div style="background-color: rgba(0,0,0,0.2); padding: 1rem; border-radius: 8px; margin-bottom: 1.5rem;">
      <div style="display: flex; align-items: center; margin-bottom: 0.5rem;">
        <img src="https://via.placeholder.com/50" alt="شاگرد" style="width: 50px; height: 50px; border-radius: 50%; margin-left: 1rem;">
        <div>
          <strong>محمد رضایی</strong>
          <div style="color: var(--primary-color);">
            <i class="fas fa-star"></i>
            <i class="fas fa-star"></i>
            <i class="fas fa-star"></i>
            <i class="fas fa-star"></i>
            <i class="fas fa-star"></i>
          </div>
        </div>
      </div>
      <p>استاد کیوکوشین نه تنها یک مربی عالی هستند، بلکه یک الگوی اخلاقی واقعی می‌باشند. من پس از 5 سال آموزش تحت نظر ایشان به درجه دان 2 رسیدم و این تنها به لطف روش‌های آموزشی منحصر به فرد ایشان ممکن شد.</p>
      <small style="color: #aaa;">1402/05/15</small>
    </div>
    
    <div style="background-color: rgba(0,0,0,0.2); padding: 1rem; border-radius: 8px; margin-bottom: 1.5rem;">
      <div style="display: flex; align-items: center; margin-bottom: 0.5rem;">
        <img src="https://via.placeholder.com/50" alt="شاگرد" style="width: 50px; height: 50px; border-radius: 50%; margin-left: 1rem;">
        <div>
          <strong>فاطمه محمدی</strong>
          <div style="color: var(--primary-color);">
            <i class="fas fa-star"></i>
            <i class="fas fa-star"></i>
            <i class="fas fa-star"></i>
            <i class="fas fa-star"></i>
            <i class="fas fa-star-half-alt"></i>
          </div>
        </div>
      </div>
      <p>به عنوان یک خانم، همیشه نگران محیط باشگاه‌های رزمی بودم، اما باشگاه استاد کیوکوشین با حفظ کامل حریم‌ها و احترام، بهترین محیط ممکن را برای تمرین فراهم کرده‌اند. سپاسگزارم.</p>
      <small style="color: #aaa;">1402/03/22</small>
    </div>
    
    <h3 style="margin-top: 2rem;"><i class="fas fa-edit"></i> ارسال نظر جدید</h3>
    <form id="comment-form">
      <div class="form-group">
        <label for="name">نام شما:</label>
        <input type="text" id="name" name="name" required>
      </div>
      <div class="form-group">
        <label for="email">ایمیل (اختیاری):</label>
        <input type="email" id="email" name="email">
      </div>
      <div class="form-group">
        <label for="rating">امتیاز:</label>
        <select id="rating" name="rating" style="width: 100%; padding: 0.8rem; background-color: #222; color: white; border: 1px solid #444; border-radius: 8px;">
          <option value="5">عالی (5 ستاره)</option>
          <option value="4">خیلی خوب (4 ستاره)</option>
          <option value="3">متوسط (3 ستاره)</option>
          <option value="2">ضعیف (2 ستاره)</option>
          <option value="1">خیلی ضعیف (1 ستاره)</option>
        </select>
      </div>
      <div class="form-group">
        <label for="comment">نظر شما:</label>
        <textarea id="comment" name="comment" rows="5" required></textarea>
      </div>
      <button type="submit"><i class="fas fa-paper-plane"></i> ارسال نظر</button>
    </form>
  </section>

  <footer>
    <div style="display: flex; justify-content: center; gap: 2rem; flex-wrap: wrap;">
      <div>
        <h3 style="color: var(--primary-color);">لینک‌های مفید</h3>
        <ul style="list-style: none; padding: 0;">
          <li><a href="#" style="color: #aaa; text-decoration: none;">فدراسیون کاراته ایران</a></li>
          <li><a href="#" style="color: #aaa; text-decoration: none;">سازمان جهانی کیوکوشین</a></li>
          <li><a href="#" style="color: #aaa; text-decoration: none;">مسابقات آینده</a></li>
        </ul>
      </div>
      <div>
        <h3 style="color: var(--primary-color);">ساعات تمرین</h3>
        <ul style="list-style: none; padding: 0;">
          <li style="color: #aaa;">شنبه تا چهارشنبه: 16-20</li>
          <li style="color: #aaa;">پنجشنبه: 10-12</li>
          <li style="color: #aaa;">جمعه: تعطیل</li>
        </ul>
      </div>
      <div>
        <h3 style="color: var(--primary-color);">عضویت در خبرنامه</h3>
        <form style="display: flex; gap: 0.5rem;">
          <input type="email" placeholder="ایمیل شما" style="padding: 0.5rem; border-radius: 5px; border: none;">
          <button type="submit" style="background-color: var(--primary-color); color: white; border: none; border-radius: 5px; padding: 0 1rem; cursor: pointer;">عضویت</button>
        </form>
      </div>
    </div>
    <div class="copyright">
      <p>© ۱۴۰۲ تمام حقوق این وبسایت متعلق به استاد کیوکوشین می‌باشد.</p>
    </div>
  </footer>

  <script>
    // اسلایدر گالری
    let currentSlide = 0;
    const slides = document.querySelectorAll('.slide');
    const dots = document.querySelectorAll('.slider-dot');
    
    function showSlide(n) {
      slides.forEach(slide => {
        slide.style.transform = `translateX(-${n * 100}%)`;
      });
      
      dots.forEach((dot, index) => {
        dot.classList.toggle('active', index === n);
      });
      
      currentSlide = n;
    }
    
    dots.forEach((dot, index) => {
      dot.addEventListener('click', () => {
        showSlide(index);
      });
    });
    
    // اتوماتیک اسلاید
    setInterval(() => {
      currentSlide = (currentSlide + 1) % slides.length;
      showSlide(currentSlide);
    }, 5000);
    
    // فرم نظر
    const commentForm = document.getElementById('comment-form');
    commentForm.addEventListener('submit', function(e) {
      e.preventDefault();
      
      // در حالت واقعی اینجا باید به سرور ارسال شود
      alert('نظر شما با موفقیت ثبت شد. پس از تأیید نمایش داده خواهد شد.');
      commentForm.reset();
    });
