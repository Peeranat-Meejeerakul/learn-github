# learn-github

<!DOCTYPE html>
<html lang="th">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>สวนส้มมีจีรกุล & MeeCoffee</title>
  <style>
    body { font-family: sans-serif; margin: 0; background: #fffaf4; color: #333; }
    header, footer { background: #ff914d; color: white; padding: 1rem; text-align: center; }
    nav a { margin: 0 1rem; color: white; text-decoration: none; }
    .section { padding: 2rem; max-width: 900px; margin: auto; }
    h2 { color: #e96c00; }
    .products, .activities, .reviews { display: grid; grid-template-columns: 1fr 1fr; gap: 1rem; }
    .card { background: white; border-radius: 12px; padding: 1rem; box-shadow: 0 0 10px rgba(0,0,0,0.1); }
    .contact-info p { margin: 0.5rem 0; }
  </style>
</head>
<body>
  <header>
    <h1>สวนส้มมีจีรกุล & MeeCoffee</h1>
    <nav>
      <a href="#about">เกี่ยวกับเรา</a>
      <a href="#products">สินค้า & บริการ</a>
      <a href="#activities">กิจกรรม</a>
      <a href="#reviews">รีวิว</a>
      <a href="#contact">ติดต่อเรา</a>
    </nav>
  </header>

  <section class="section" id="about">
    <h2>เกี่ยวกับเรา</h2>
    <p>สวนส้มมีจีรกุล & MeeCoffee ตั้งอยู่ท่ามกลางธรรมชาติของอำเภอแม่แตง จังหวัดเชียงใหม่ เราคัดสรรส้มสายน้ำผึ้งคุณภาพปลอดสาร พร้อมให้บริการคาเฟ่ ขนมโฮมเมด และที่พักพร้อมอาหารเช้าในบรรยากาศเงียบสงบ</p>
  </section>

  <section class="section" id="products">
    <h2>สินค้า & บริการ</h2>
    <div class="products">
      <div class="card">
        <h3>🍊 ส้มสายน้ำผึ้ง</h3>
        <p>ปลอดสาร มาตรฐาน GAP สดจากสวน พร้อมจัดส่ง</p>
      </div>
      <div class="card">
        <h3>☕ กาแฟ MeeCoffee</h3>
        <p>กาแฟดริป Cold Brew และเมล็ดกาแฟคั่วเอง</p>
      </div>
      <div class="card">
        <h3>🍞 ขนมโฮมเมด</h3>
        <p>ขนมปังโชคุปัง และเบเกอรี่ พร้อมรับออเดอร์ส่งถึงบ้าน</p>
      </div>
      <div class="card">
        <h3>🏡 ที่พักพร้อมอาหารเช้า</h3>
        <p>บ้านพักกลางสวนส้ม พร้อมอาหารเช้าและบรรยากาศธรรมชาติ</p>
      </div>
    </div>
  </section>

  <section class="section" id="activities">
    <h2>กิจกรรม</h2>
    <div class="activities">
      <div class="card">
        <h3>เก็บส้มสดจากต้น</h3>
        <p>เปิดเฉพาะฤดูเก็บเกี่ยว สัมผัสความสดชื่นจากธรรมชาติ</p>
      </div>
      <div class="card">
        <h3>เวิร์กช็อปชงกาแฟ</h3>
        <p>เรียนรู้การชงกาแฟแบบมืออาชีพจาก MeeCoffee</p>
      </div>
    </div>
  </section>

  <section class="section" id="reviews">
    <h2>รีวิวจากลูกค้า</h2>
    <div class="reviews">
      <div class="card">
        <p>“ส้มหวานมาก! บรรยากาศดีสุด ๆ” – คุณนิด</p>
      </div>
      <div class="card">
        <p>“กาแฟหอมและขนมอร่อยมาก จะกลับมาอีกแน่นอน” – คุณเมย์</p>
      </div>
    </div>
  </section>

  <section class="section" id="contact">
    <h2>ติดต่อเรา</h2>
    <div class="contact-info">
      <p>📍 239 หมู่ 2 ตำบลป่าแป๋ อำเภอแม่แตง จังหวัดเชียงใหม่ 50150</p>
      <p>📞 โทร: 081-885-4918</p>
      <p>💬 LINE ID: air456</p>
      <p>📘 Facebook: สวนส้มมีจีรกุล & MeeCoffee</p>
      <iframe src="https://maps.google.com/maps?q=239%20หมู่%202%20ตำบลป่าแป๋%20อำเภอแม่แตง%20เชียงใหม่&t=&z=13&ie=UTF8&iwloc=&output=embed" width="100%" height="300" style="border:0;"></iframe>
    </div>
  </section>

  <footer>
    <p>© 2025 สวนส้มมีจีรกุล & MeeCoffee</p>
  </footer>
</body>
</html>
