<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Daisy Birth/Postpartum Center</title>
  <style>
    :root {
      --primary-color: #FFB6B9;
      --secondary-color: #FFDAC1;
      --accent-color: #B5EAD7;
      --text-color: #333;
      --bg-color: #fff;
    }

    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      scroll-behavior: smooth;
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    }

    body {
      background-color: var(--bg-color);
      color: var(--text-color);
      line-height: 1.6;
    }

    header {
      background-color: var(--primary-color);
      padding: 2rem;
      text-align: center;
    }

    header h1 {
      font-size: 2.5rem;
      margin-bottom: 0.5rem;
    }

    nav {
      background-color: var(--secondary-color);
      padding: 1rem;
      display: flex;
      justify-content: center;
      gap: 2rem;
      flex-wrap: wrap;
    }

    nav a {
      color: var(--text-color);
      text-decoration: none;
      font-weight: bold;
    }

    nav a:hover {
      text-decoration: underline;
    }

    section {
      padding: 2rem;
      max-width: 1000px;
      margin: auto;
    }

    section h2 {
      font-size: 2rem;
      margin-bottom: 1rem;
      color: var(--primary-color);
    }

    .suites, .staff {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 1.5rem;
    }

    .card {
      border: 1px solid #eee;
      padding: 1rem;
      border-radius: 10px;
      background-color: var(--accent-color);
    }

    footer {
      background-color: var(--primary-color);
      color: white;
      text-align: center;
      padding: 1rem;
      margin-top: 2rem;
    }

    @media (max-width: 600px) {
      header h1 {
        font-size: 1.8rem;
      }
    }
  </style>
</head>
<body>

  <header>
    <h1>Daisy Birth/Postpartum Center</h1>
    <p>Gentle beginnings. Empowered motherhood.</p>
  </header>

  <nav>
    <a href="#about">About</a>
    <a href="#suites">Suites</a>
    <a href="#pricing">Pricing</a>
    <a href="#staff">Staff</a>
    <a href="#contact">Contact</a>
  </nav>

  <section id="about">
    <h2>About the Institution</h2>
    <p>At Daisy Birth/Postpartum Center, we believe in holistic, compassionate, and family-centered care for all birthing and postpartum individuals. Our serene, state-of-the-art facility offers an alternative to traditional hospital births, combining medical safety with a homelike environment where families can feel at peace.</p>
  </section>

  <section id="suites">
    <h2>Available Suites</h2>
    <div class="suites">
      <div class="card">
        <h3>Rose Suite</h3>
        <p>Includes a birthing tub, queen bed, and private bathroom. Perfect for water births and cozy family bonding.</p>
      </div>
      <div class="card">
        <h3>Lily Suite</h3>
        <p>Modern comforts with soft lighting, calming colors, and a full kitchenette for your stay.</p>
      </div>
      <div class="card">
        <h3>Tulip Suite</h3>
        <p>Spacious, peaceful environment ideal for postpartum recovery with doula support access.</p>
      </div>
    </div>
  </section>

  <section id="pricing">
    <h2>Pricing</h2>
    <p>We offer flexible pricing plans designed to accommodate families of all backgrounds. Insurance and HSA/FSA are accepted. </p>
    <ul>
      <li><strong>Birth Suite Package:</strong> $3,500 – Includes prenatal consults, suite stay, and 24-hour support.</li>
      <li><strong>Postpartum Recovery Package:</strong> $1,800 – 3-night stay with lactation, meal, and newborn care support.</li>
      <li><strong>Full Care Package:</strong> $4,900 – Includes birth + postpartum care.</li>
    </ul>
  </section>

  <section id="staff">
    <h2>Our Staff</h2>
    <div class="staff">
      <div class="card">
        <h3>Midwife Sarah Jenkins</h3>
        <p>Over 15 years of experience in birth support, specializing in natural and water births.</p>
      </div>
      <div class="card">
        <h3>Doula Maria Lopez</h3>
        <p>Certified postpartum doula, lactation consultant, and passionate advocate for gentle parenting.</p>
      </div>
      <div class="card">
        <h3>Dr. Elaine Carter</h3>
        <p>Board-certified OB-GYN overseeing medical safety and prenatal wellness for all clients.</p>
      </div>
    </div>
  </section>

  <section id="contact">
    <h2>Contact Us</h2>
    <p>We’re here to support you! Reach out to schedule a tour, ask questions, or book your suite.</p>
    <p>Email: <a href="mailto:info@daisybirthcenter.com">info@daisybirthcenter.com</a></p>
    <p>Phone: (555) 123-4567</p>
    <p>Location: 123 Blossom Way, Harmony City, USA</p>
  </section>

  <footer>
    <p>&copy; 2025 Daisy Birth/Postpartum Center. All rights reserved.</p>
  </footer>

</body>
</html>
