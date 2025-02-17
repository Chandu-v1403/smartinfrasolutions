<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Smart Infra Solutions - Modern IT Infrastructure Services</title>
    <style>
        /* General Styles */
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f9f9f9;
            color: #333;
            line-height: 1.6;
        }

        header {
            background: linear-gradient(135deg, #0073e6, #0047ab);
            color: #fff;
            padding: 60px 20px;
            text-align: center;
            font-size: 32px;
            font-weight: bold;
            box-shadow: 0 4px 10px rgba(0, 0, 0, 0.1);
        }

        section {
            padding: 60px 20px;
            text-align: center;
        }

        h2 {
            color: #0073e6;
            font-size: 28px;
            margin-bottom: 40px;
            text-transform: uppercase;
            letter-spacing: 1.5px;
        }

        .content-box {
            background: #fff;
            padding: 25px;
            width: 300px;
            border-radius: 12px;
            box-shadow: 0 4px 15px rgba(0, 0, 0, 0.1);
            transition: transform 0.3s ease-in-out, box-shadow 0.3s ease-in-out;
        }

        .content-box:hover {
            transform: translateY(-10px);
            box-shadow: 0 8px 20px rgba(0, 0, 0, 0.15);
        }

        .services, .about {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            gap: 30px;
            max-width: 1200px;
            margin: 0 auto;
        }

        .services .content-box h3 {
            color: #0047ab;
            font-size: 22px;
            margin-bottom: 15px;
        }

        .services .content-box p {
            font-size: 16px;
            color: #555;
        }

        footer {
            background: #0047ab;
            color: #fff;
            padding: 20px;
            text-align: center;
            font-size: 18px;
            margin-top: 60px;
        }

        .contact {
            font-weight: bold;
            color: #ffd700;
        }

        /* Button Styles */
        .cta-button {
            display: inline-block;
            margin-top: 20px;
            padding: 12px 30px;
            background: #0073e6;
            color: #fff;
            text-decoration: none;
            border-radius: 25px;
            font-size: 16px;
            transition: background 0.3s ease-in-out;
        }

        .cta-button:hover {
            background: #0047ab;
        }

        /* Responsive Design */
        @media (max-width: 768px) {
            header {
                font-size: 24px;
                padding: 40px 20px;
            }

            h2 {
                font-size: 24px;
            }

            .content-box {
                width: 100%;
                margin: 10px;
            }
        }
    </style>
</head>
<body>
    <header>
        Smart Infra Solutions
        <p style="font-size: 18px; font-weight: normal; margin-top: 10px;">Building the Future of IT Infrastructure</p>
    </header>

    <section>
        <h2>About Us</h2>
        <div class="about">
            <div class="content-box">
                <p>At Smart Infra Solutions, we specialize in building comprehensive IT infrastructure for startups, ensuring a seamless and secure technology foundation. From network architecture to cybersecurity, we provide end-to-end solutions for your business.</p>
                <a href="#contact" class="cta-button">Learn More</a>
            </div>
        </div>
    </section>

    <section>
        <h2>Our Services</h2>
        <div class="services">
            <div class="content-box">
                <h3>Domain & Network Infrastructure</h3>
                <p>We help startups build their domain and network infrastructure with reliable solutions.</p>
            </div>
            <div class="content-box">
                <h3>IT Support for Software Companies</h3>
                <p>Providing seamless IT support to ensure your business runs without interruptions.</p>
            </div>
            <div class="content-box">
                <h3>Sophos Firewall Solutions</h3>
                <p>Protect your network with advanced security from Sophos firewall.</p>
            </div>
            <div class="content-box">
                <h3>Antivirus Protection</h3>
                <p>Secure your systems with leading antivirus solutions.</p>
            </div>
            <div class="content-box">
                <h3>Microsoft Server & Office 365 Licensing</h3>
                <p>Get licensed Microsoft solutions for seamless business operations.</p>
            </div>
            <div class="content-box">
                <h3>Cloud Computing & Virtualization</h3>
                <p>We provide cloud solutions, virtualization, and hybrid infrastructure for scalable business operations.</p>
            </div>
            <div class="content-box">
                <h3>Backup & Disaster Recovery</h3>
                <p>Ensure business continuity with our secure backup and disaster recovery solutions.</p>
            </div>
            <div class="content-box">
                <h3>Network Security & VPN Solutions</h3>
                <p>Secure remote access and protect your network with our advanced VPN and security solutions.</p>
            </div>
        </div>
    </section>

    <footer id="contact">
        <p>Contact Us: <span class="contact">info@smartinfrasolutions.com</span></p>
        <p style="margin-top: 10px;">&copy; 2023 Smart Infra Solutions. All rights reserved.</p>
    </footer>
</body>
</html>
