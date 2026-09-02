
 <html lang="en" >
 <head >
 <meta charset="UTF-8" >
 <meta name="viewport" content="width=device-width, initial-scale=1.0" >
 <title > Excel Electricals | Motor Winding & Repair</title >
  <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: Arial, Helvetica, sans-serif;
            background: #080a0d;
            color: #fff;
        }

        header {
            background: #0d1117;
            padding: 20px 7%;
            position: sticky;
            top: 0;
            z-index: 100;
            border-bottom: 1px solid #252b33;
        }

        .logo {
            color: #ffbd00;
            font-size: 24px;
            font-weight: 900;
        }

        nav {
            margin-top: 10px;
        }

            nav a {
                color: #ddd;
                text-decoration: none;
                margin-right: 25px;
                font-size: 14px;
            }

                nav a: hover {
                    color: #ffbd00;
                }
        /* hero */

        .hero {
            min-height: 85vh;
            display: flex;
            align-items: centre;
            padding: 80px 7%;
            background: #090c10;
        }

        .hero-content {
            width: 50%;
        }

        .hero h1 {
            font-size: 60px;
            line-height: 1.05;
        }

            .hero h1 span {
                color: #ffbd00;
            }

        .hero p {
            color: #b7bdc5;
            margin: 25px 0;
            font-size: 18px;
        }

        .button {
            display: inline-block;
            padding: 14px 22px;
            background: #ffbd00;
            color: #111;
            text-decoration: none;
            border-radius: 7px;
            font-weight: bold;
        }

        .hero-image {
            width: 50%;
            padding-left: 40px;
        }

            .hero-image img {
                width: 100%;
                height: 450px;
                object-fit: cover;
                border-radius: 20px;
                border: 2px solid #ffbd00;
            }
        /* section */

        section {
            padding: 90px 7%;
        }

        .title {
            text-align: centre;
            margin-bottom: 50px;
        }

            .title small {
                color: #ffbd00;
                font-weight: bold;
                letter-spacing: 2px;
            }

            .title h2 {
                font-size: 42px;
                margin-top: 10px;
            }

            .title p {
                color: #9ea5ad;
                margin-top: 10px;
            }
        /* motor gallery */

        .motor-gallery {
            background: #0d1117;
        }

        .gallery {
            display: grid;
            grid-template-columns: repeat(3,1fr);
            gap: 20px;
        }

        .motor-card {
     background: #151a21;
     border: 1px solid #2b323b;
     border-radius: 15px;
     overflow: hidden;
     transition: .3s;
 }

     .motor-card:hover {
         transform: translateY(-8px);
         border-color: #ffbd00;
     }

     .motor-card img {
         width: 100%;
         height: 250px;
         object-fit: cover;
     }

 .motor-info {
     padding: 20px;
 }

     .motor-info h3 {
         color: #ffbd00;
         margin-bottom: 8px;
         
     }

     .motor-info p {
         color: #aeb5bd;
         font-size: 14px;
     }
        /* winding */

        .winding {
            background: #080a0d;
        }

        .winding-grid {
            display: grid;
            grid-template-columns: repeat(2,1fr);
            gap: 25px;
        }

        .winding-card {
            position: relative;
            height: 400px;
            overflow: hidden;
            border-radius: 18px;
        }

            .winding-card img {
                width: 100%;
                height: 100%;
                object-fit: cover;
            }

        .winding-text {
            position: absolute;
            bottom: 0;
            width: 100%;
            padding: 50px 25px 25px;
            background: linear-gradient(transparent,rgba(0,0,0,.95));
        }

            .winding-text h3 {
                color: #ffbd00;
                font-size: 26px;
            }

            .winding-text p {
                color: #ddd;
            }
        /* service */

        .services {
            background: #0d1117;
        }

        .service-grid {
            display: grid;
            grid-template-columns: repeat(3,1fr);
            gap: 20px;
        }

        .service {
            padding: 30px;
            background: #151a21;
            border: 1px solid #2b323b;
            border-radius: 12px;
        }

            .service h3 {
                color: #ffbd00;
                margin-bottom: 10px;
            }

            .service p {
                color: #aeb5bd;
            }
        /* contact */

        .contact {
            text-align: centre;
            background: #080a0d;
        }

            .contact h2 {
                font-size: 40px;
            }

            .contact p {
                color: #aaa;
                margin: 15px 0 25px;
            }

        footer {
            text-align: centre;
            padding: 30px;
            border-top: 1px solid #252b33;
            color: #777;
        }

            footer span {
                color: #ffbd00;
            }
        /* mobile */

        @media(max-width:850px) {
            .hero {
                flex-direction: column;
            }

            .hero-content, .hero-image {
                width: 100%;
            }

            .hero-image {
                padding: 30px 0 0;
            }

            .hero h1 {
                font-size: 45px;
            }

            .gallery, .service-grid {
                grid-template-columns: 1fr 1fr;
            }
        }

        @media(max-width:550px) {
            .gallery, .winding-grid, .service-grid {
                grid-template-columns: 1fr;
            }

            .hero h1 {
                font-size: 38px;
            }

            .title h2 {
                font-size: 32px;
            }

            .hero-image img {
                height: 300px;
            }
       
    </style>
</head>
<body>

    <!-- HEADER --> <header> <div class="logo"> ⚡ EXCEL ELECTRICALS </div> <nav> <a href="#home">Home</a> <a href="#motors">Motors</a> <a href="#winding">Winding</a> <a href="#services">Services</a> <a href="#contact">Contact</a> </nav> </header> <!-- HERO --> <section class="hero" id="home"> <div class="hero-content"> <h1> ELECTRIC MOTOR <span>WINDING & REPAIR</span> </h1> <p> Professional electric motor rewinding, motor repair, stator winding, rotor service and motor component replacement in Choondy, Aluva. </p> <a class="button" href="tel:+918590259451"> 📞 CALL NOW </a> <a class="button" href="mailto:excelelectricalswork@gmail.com">Email </a> </div> <div class="hero-image"> <!-- ELECTRIC MOTOR IMAGE --> <img src="75%20Hp.webp" alt="75 HP Motor"> </div> </section> <!-- MOTOR PICTURES --> <section class="motor-gallery" id="motors"> <div class="title"> <small>ELECTRIC MOTOR</small> <h2>Motor Pictures</h2> <p> Electric motors, stators, rotors and motor components </p> </div> <div class="gallery">
    
  <div class="motor-card">
    <img src="Inducton%20motor.webp" alt="Induction Motor">
    <div class="motor-info">
      <h3>Electric Motor</h3>
      <p>Electric motor repair and maintenance.</p>
    </div>
  </div>

  <div class="motor-card">
    <img src="Motor.webp" alt="Electric Motor">
    <div class="motor-info">
      <h3>Electric Motor</h3>
      <p>Motor service and electrical maintenance.</p>
    </div>
  </div>

  <div class="motor-card">
    <img src="Field%20Winding.webp" alt="Field Winding">
    <div class="motor-info">
      <h3>Motor Stator</h3>
      <p>Stator and electrical motor components.</p>
    </div>
  </div>

  <div class="motor-card">
    <img src="Ex%20Rotor%20winding.webp" alt="Rotor Winding">
    <div class="motor-info">
      <h3>Motor Stator</h3>
      <p>Stator and electrical motor compnment.</p>
    </div>
  </div>

  <div class="motor-card">
    <img src="25%20Hp.jpg" alt="25 HP Motor">
   <div class="motor-info">
   <h3>motor Components</h3>
   <p>Motor parts and repair components.</p>
  </div>
 </div>
   
 <div class="motor-card">
    <img src="75%20Hp.webp" alt="75 HP Motor">
   <div class="motor-info">
   <h3>Motor Winding</h3>
   <p>Electrical winding and rewinding service.</p>
  </div>
 </div>
 
 </section>
<!-- WINDING SECTION -->
<section class="winding" id="winding">
  <div class="title">
    <small>MOTOR REWINDING</small>
    <h2>Motor Winding</h2>
    <p>Professional winding and rewinding-related images</p>
  </div>
</div>
 
     <div class="winding-grid">
     <div class="winding-card">
      <img src="motor%20wind..webp" alt="Stator Winding">
      <h3>Stator Winding</h3>
      <p>Professional electric motor winding service</p>
    </div>
    </div>

    <div class="winding-card">
      <img src="repair%20motor.webp" alt="Motor Rewinding">
      <h3>Motor Rewinding</h3>
      <p>Complete motor rewinding and repair work</p>
    </div>
  </div>

  
</section> <!-- SERVICES --> <section class="services" id="services"> <div class="title"> <small>OUR SERVICES</small> <h2>Motor Services</h2> </div> <div class="service-grid"> <div class="service"> <h3>⚡ Motor Winding</h3> <p> Motor winding and rewinding for electric motors. </p> </div> <div class="service"> <h3>⚙️ Motor Repair</h3> <p> Complete electrical and mechanical motor repair. </p> </div> <div class="service"> <h3>🔩 Bearing Change</h3> <p> Bearing inspection and replacement. </p> </div> <div class="service"> <h3>🔋 Capacitor Change</h3> <p> Motor capacitor testing and replacement. </p> </div> <div class="service"> <h3>🌀 Stator & Coil</h3> <p> Stator coil and winding related service. </p> </div> <div class="service"> <h3>🔧 Motor Parts</h3> <p> Motor component replacement and fitting. </p> </div> </div> </section> <!-- CONTACT --> <section class="contact" id="contact"> <h2>EXCEL ELECTRICALS</h2> <p> Motor Winding & Repair<br> Choondy, Aluva, Kerala </p> <a class="button" href="https://wa.me/918590259451" target="_blank"> 💬 WHATSAPP </a> <a class="button" href="tel:+918590259451"> 📞 CALL </a> <a class="button"  href="mailto:excelelectricalswork@gmail.com" >Email </a> <!-- FOOTER --> <footer> <p> © 2026 <span>EXCEL ELECTRICALS</span> </p> GSTIN/UIN:32AAGPX3837Q1ZZ <p> Motor Winding • Motor Repair • Choondy • Aluva </p> </footer>

