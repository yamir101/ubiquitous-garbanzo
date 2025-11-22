<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1.0" />
<title>India Sewa Pro - Trusted Government Services Portal</title>

<link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap" rel="stylesheet">
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.0/css/all.min.css" />

<style>
* { margin: 0; padding: 0; box-sizing: border-box; }

body {
  font-family: 'Roboto', sans-serif;
  background: linear-gradient(to bottom right, #e0eafc, #cfdef3);
  color: #222;
  transition: 0.4s ease;
}

body.dark-mode {
  background: #0d0d0d;
  color: #fff;
}

header {
  text-align: center;
  padding: 50px 20px;
  background: rgba(255,255,255,0.7);
  backdrop-filter: blur(8px);
  border-bottom: 3px solid #003566;
}

header h1 { font-size: 3em; color: #003566; }
body.dark-mode header h1 { color: #d4af37; }

header img { width: 120px; margin-bottom: 10px; }

.toggle {
  position: fixed;
  top: 15px;
  right: 15px;
  background: #003566;
  color: white;
  padding: 12px;
  border-radius: 50%;
  font-size: 18px;
  border: none;
  cursor: pointer;
  z-index: 999;
}

.services {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(230px, 1fr));
  gap: 25px;
  padding: 25px;
  max-width: 1300px;
  margin: auto;
}

.service-box {
  background: rgba(255,255,255,0.9);
  padding: 22px;
  border-radius: 14px;
  text-align: center;
  transition: 0.35s ease;
  transform-style: preserve-3d;
  box-shadow: 0px 8px 20px rgba(0,0,0,0.1);
}

.service-box:hover {
  transform: translateY(-10px) rotateX(6deg);
  box-shadow: 0px 18px 30px rgba(0,0,0,0.3);
}

.service-box i {
  font-size: 40px;
  margin-bottom: 10px;
  color: #003566;
}

.btn {
  background: #003566;
  color: white;
  padding: 10px 25px;
  border-radius: 25px;
  text-decoration: none;
  display: inline-block;
  margin-top: 12px;
}

footer {
  background: #003566;
  padding: 18px;
  text-align: center;
  color: white;
  margin-top: 40px;
}
</style>
</head>

<body>

<button class="toggle" onclick="document.body.classList.toggle('dark-mode')">🌙</button>

<header>
  <img src="https://i.ibb.co/6WqQ3R8/ashoka.png" />
  <h1>India Sewa Pro</h1>
  <p>Trusted Government Services Portal</p>
</header>

<section>
  <div class="services">

    <!-- 30 SERVICES BELOW -->

    <div class="service-box"><i class="fa-solid fa-id-card"></i><h3>Aadhaar Card</h3><a href="https://uidai.gov.in" class="btn">Open</a></div>

    <div class="service-box"><i class="fa-solid fa-address-card"></i><h3>PAN Card</h3><a href="https://tin.tin.nsdl.com" class="btn">Open</a></div>

    <div class="service-box"><i class="fa-solid fa-square-check"></i><h3>Voter ID</h3><a href="https://nvsp.in" class="btn">Open</a></div>

    <div class="service-box"><i class="fa-solid fa-hospital-user"></i><h3>Ayushman Bharat</h3><a href="https://pmjay.gov.in" class="btn">Open</a></div>

    <div class="service-box"><i class="fa-solid fa-cloud"></i><h3>DigiLocker</h3><a href="https://digilocker.gov.in" class="btn">Open</a></div>

    <div class="service-box"><i class="fa-solid fa-bolt"></i><h3>Electricity Bill</h3><a href="https://bharatbillpay.com" class="btn">Pay</a></div>

    <div class="service-box"><i class="fa-solid fa-graduation-cap"></i><h3>Scholarship Portal</h3><a href="https://scholarships.gov.in" class="btn">Open</a></div>

    <div class="service-box"><i class="fa-solid fa-certificate"></i><h3>Birth Certificate</h3><a href="https://crsorgi.gov.in" class="btn">Open</a></div>

    <div class="service-box"><i class="fa-solid fa-car"></i><h3>Driving License</h3><a href="https://parivahan.gov.in" class="btn">Open</a></div>

    <div class="service-box"><i class="fa-solid fa-fire"></i><h3>Gas Subsidy</h3><a href="https://my.ebharatgas.com" class="btn">Check</a></div>

    <div class="service-box"><i class="fa-solid fa-bread-slice"></i><h3>Ration Card</h3><a href="https://nfsa.gov.in" class="btn">Open</a></div>

    <div class="service-box"><i class="fa-solid fa-gear"></i><h3>e-Shram Card</h3><a href="https://eshram.gov.in" class="btn">Open</a></div>

    <div class="service-box"><i class="fa-solid fa-passport"></i><h3>Passport Service</h3><a href="https://passportindia.gov.in" class="btn">Open</a></div>

    <div class="service-box"><i class="fa-solid fa-building-columns"></i><h3>PF / UAN</h3><a href="https://epfindia.gov.in" class="btn">Open</a></div>

    <div class="service-box"><i class="fa-solid fa-file-invoice"></i><h3>Income Tax</h3><a href="https://incometax.gov.in" class="btn">File</a></div>

    <div class="service-box"><i class="fa-solid fa-money-bill"></i><h3>GST Portal</h3><a href="https://gst.gov.in" class="btn">Open</a></div>

    <div class="service-box"><i class="fa-solid fa-gavel"></i><h3>eDistrict</h3><a href="#" class="btn">Open</a></div>

    <div class="service-box"><i class="fa-solid fa-heart"></i><h3>Marriage Certificate</h3><a href="#" class="btn">Open</a></div>

    <div class="service-box"><i class="fa-solid fa-wheat-awn"></i><h3>PM Kisan</h3><a href="https://pmkisan.gov.in" class="btn">Check</a></div>

    <div class="service-box"><i class="fa-solid fa-map"></i><h3>Land Records (Bhulekh)</h3><a href="#" class="btn">Open</a></div>

    <div class="service-box"><i class="fa-solid fa-droplet"></i><h3>Water Bill</h3><a href="#" class="btn">Pay</a></div>

    <div class="service-box"><i class="fa-solid fa-city"></i><h3>Municipal Tax</h3><a href="#" class="btn">Pay</a></div>

    <div class="service-box"><i class="fa-solid fa-house"></i><h3>PM Awas Yojana</h3><a href="https://pmaymis.gov.in" class="btn">Check</a></div>

    <div class="service-box"><i class="fa-solid fa-shield"></i><h3>Cyber Crime Portal</h3><a href="https://cybercrime.gov.in" class="btn">Report</a></div>

    <div class="service-box"><i class="fa-solid fa-school"></i><h3>School Admission</h3><a href="#" class="btn">Open</a></div>

    <div class="service-box"><i class="fa-solid fa-stethoscope"></i><h3>Health ID (ABHA)</h3><a href="https://healthid.ndhm.gov.in" class="btn">Create</a></div>

    <div class="service-box"><i class="fa-solid fa-list-check"></i><h3>RTI Portal</h3><a href="https://rtionline.gov.in" class="btn">File</a></div>

    <div class="service-box"><i class="fa-solid fa-wallet"></i><h3>PPF / NPS</h3><a href="#" class="btn">Open</a></div>

    <div class="service-box"><i class="fa-solid fa-bus"></i><h3>Fastag Recharge</h3><a href="https://fastag.org" class="btn">Recharge</a></div>

  </div>
</section>

<footer>
  © 2025 India Sewa Pro • Developed by Hyper Yamir
</footer>

</body>
</html>