# Celebrity-Membership

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Ultimate Celebrity Fan Experience</title>
    <link href="https://fonts.googleapis.com/css2?family=Montserrat:wght@400;700&family=Playfair+Display:wght@700&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Montserrat', sans-serif;
            background-color: #f4f4f4;
            color: #333;
            margin: 0;
            padding: 0;
        }

        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 20px;
        }

        h1, h2, h3 {
            font-family: 'Playfair Display', serif;
            text-align: center;
            color: #2c3e50;
        }

        h1 {
            font-size: 48px;
            margin-top: 30px;
        }

        h2 {
            font-size: 36px;
            margin: 40px 0 20px;
        }

        h3 {
            font-size: 26px;
            margin-top: 20px;
            color: #34495e;
        }

        .intro {
            background: linear-gradient(135deg, #8e44ad, #3498db);
            padding: 40px;
            border-radius: 15px;
            box-shadow: 0 4px 15px rgba(0, 0, 0, 0.2);
            color: white;
            margin-bottom: 50px;
        }

        .membership-level {
            background-color: white;
            padding: 30px;
            margin: 20px 0;
            border-radius: 15px;
            box-shadow: 0 4px 15px rgba(0, 0, 0, 0.1);
            display: flex;
            flex-wrap: wrap;
            justify-content: space-between;
            border-left: 5px solid #8e44ad;
        }

        .level-details {
            width: 45%;
            margin-bottom: 20px;
        }

        .level-details h3 {
            font-size: 30px;
            color: #2c3e50;
        }

        .price {
            font-size: 26px;
            color: #e74c3c;
            margin-bottom: 15px;
        }

        ul.benefits {
            list-style-type: none;
            padding: 0;
            color: #34495e;
        }

        ul.benefits li {
            padding: 8px 0;
            border-bottom: 1px solid #eee;
        }

        .signup-button {
            background-color: #8e44ad;
            color: white;
            padding: 10px 30px;
            text-decoration: none;
            border-radius: 5px;
            margin-top: 20px;
            display: inline-block;
            transition: background-color 0.3s ease;
            font-weight: bold;
        }

        .signup-button:hover {
            background-color: #6c3483;
        }

        .celebrity-partners, .charity-section {
            background-color: #f8f9fa;
            padding: 30px;
            border-radius: 15px;
            box-shadow: 0 4px 15px rgba(0, 0, 0, 0.1);
            margin-bottom: 50px;
        }

        .celebrity-list, .charity-list {
            list-style-type: none;
            padding: 0;
        }

        .celebrity-list li, .charity-list li {
            padding: 10px 0;
            font-size: 18px;
            color: #2c3e50;
        }

        footer {
            text-align: center;
            margin-top: 30px;
            padding: 20px;
            background-color: #2c3e50;
            color: white;
        }

        @media screen and (max-width: 768px) {
            .level-details {
                width: 100%;
            }
        }

    </style>
</head>
<body>

    <div class="container">
        <h1>Welcome to the Ultimate Celebrity Fan Experience!</h1>
        <div class="intro">
            <p>As a cherished member of our Celebrity Fan Club, you're about to step into an unparalleled world of exclusive perks, personal connections, and unforgettable moments with your favorite stars.</p>
        </div>

        <h2>Our Mission</h2>
        <p>We're committed to bridging the gap between fans and celebrities, creating a unique community that celebrates shared passions. Our fan card program is designed to reward your loyalty, offering a suite of benefits that will elevate your fan experience to extraordinary heights.</p>

        <h2>Membership Levels</h2>

        <!-- Bronze Level -->
        <div class="membership-level">
            <div class="level-details">
                <h3>Bronze Level: Superfan</h3>
                <div class="price">$700</div>
                <ul class="benefits">
                    <li>Exclusive digital content, including behind-the-scenes stories and interviews.</li>
                    <li>Personalized digital autograph from your favorite celebrity.</li>
                    <li>Monthly newsletter with celebrity news and updates.</li>
                    <li>Complimentary digital download of a celebrity's book or album.</li>
                    <li>Access to a private Bronze Level Facebook group.</li>
                    <li>5% discount on celebrity merchandise.</li>
                </ul>
                <a href="mailto:your-email@example.com?subject=Bronze%20Level%20Sign%20Up&body=I%20would%20like%20to%20sign%20up%20for%20the%20Bronze%20Level%20membership" class="signup-button">Sign Up</a>
            </div>
        </div>

        <!-- Silver Level -->
        <div class="membership-level">
            <div class="level-details">
                <h3>Silver Level: VIP Access</h3>
                <div class="price">$1,000</div>
                <ul class="benefits">
                    <li>All Bronze Level benefits.</li>
                    <li>Early access to new releases and behind-the-scenes content.</li>
                    <li>Invitation to a virtual Q&A session with a celebrity.</li>
                    <li>Signed digital poster.</li>
                    <li>Priority access to event tickets (limited to 20 tickets per event).</li>
                    <li>10% discount on celebrity merchandise.</li>
                </ul>
                <a href="mailto:your-email@example.com?subject=Silver%20Level%20Sign%20Up&body=I%20would%20like%20to%20sign%20up%20for%20the%20Silver%20Level%20membership" class="signup-button">Sign Up</a>
            </div>
        </div>

        <!-- Gold Level -->
        <div class="membership-level">
            <div class="level-details">
                <h3>Gold Level: Backstage Pass</h3>
                <div class="price">$2,000</div>
                <ul class="benefits">
                    <li>All Silver Level benefits.</li>
                    <li>Personalized video message from a celebrity.</li>
                    <li>Invitation to exclusive virtual meet-and-greets.</li>
                    <li>Limited edition physical fan card, signed by the celebrity.</li>
                    <li>Gold Level-only virtual event access.</li>
                    <li>Complimentary hardcover edition of a celebrity's book.</li>
                    <li>15% discount on celebrity merchandise.</li>
                    <li>Priority access to event tickets (limited to 10 tickets per event).</li>
                </ul>
                <a href="mailto:your-email@example.com?subject=Gold%20Level%20Sign%20Up&body=I%20would%20like%20to%20sign%20up%20for%20the%20Gold%20Level%20membership" class="signup-button">Sign Up</a>
            </div>
        </div>

        <!-- Platinum Level -->
        <div class="membership-level">
            <div class="level-details">
                <h3>Platinum Level: Red Carpet Treatment</h3>
                <div class="price">$2,800</div>
                <ul class="benefits">
                    <li>All Gold Level benefits.</li>
                    <li>One-on-one video call with a celebrity.</li>
                    <li>Personalized, signed script or lyrics from a celebrity.</li>
                    <li>Recognition on the celebrity's website as a Platinum Level supporter.</li>
                    <li>VIP passes to select in-person events.</li>
                    <li>Exclusive, rare signed merchandise.</li>
                    <li>20% discount on celebrity merchandise.</li>
                    <li>Priority access to event tickets (limited to 5 tickets per event).</li>
                </ul>
                <a href="mailto:your-email@example.com?subject=Platinum%20Level%20Sign%20Up&body=I%20would%20like%20to%20sign%20up%20for%20the%20Platinum%20Level%20membership" class="signup-button">Sign Up</a>
            </div>
        </div>

        <!-- Diamond Level -->
        <div class="membership-level">
            <div class="level-details">
                <h3>Diamond Level: Ultimate Experience</h3>
                <div class="price">$4,000</div>
                <ul class="benefits">
                    <li>All Platinum Level benefits.</li>
                    <li>Customized fan experience package tailored to you.</li>
                    <li>Private lunch or dinner with a celebrity, either virtual or in-person.</li>
                    <li>Lifetime benefits!</li>
                </ul>
                <a href="mailto:your-email@example.com?subject=Diamond%20Level%20Sign%20Up&body=I%20would%20like%20to%20sign%20up%20for%20the%20Diamond%20Level%20membership" class="signup-button">Sign Up</a>
            </div>
        </div>

        <h2>Celebrity Partners</h2>
        <div class="celebrity-partners">
            <ul class="celebrity-list">
                <li>Bridgerton Stars: Jonathan Bailey, Phoebe Dynevor, Regé-Jean Page, and more!</li>
                <li>International Icons: Shah Rukh Khan, Deepika Padukone, Priyanka Chopra.</li>
                <li>Music Legends: Taylor Swift, Beyoncé, Kendrick Lamar.</li>
                <li>Hollywood Greats: Tom Hanks, Meryl Streep, Denzel Washington.</li>
            </ul>
        </div>

        <h2>Charitable Partnerships</h2>
        <div class="charity-section">
            <ul class="charity-list">
                <li>We're committed to supporting important causes like education, healthcare, and environmental conservation.</li>
                <li>Our celebrity partners are passionate about giving back to the community and their fans.</li>
            </ul>
        </div>
    </div>

    <footer>
        <p>&copy; 2024 Ultimate Celebrity Fan Club. All Rights Reserved.</p>
    </footer>
</body>
</html>
