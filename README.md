<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <!-- 5.2 SEO Title and Meta Description -->
    <title>Beginner-Friendly Budget Trackers | Everyday Budget</title>
    <meta name="description" content="Simplify your finances with our easy-to-use Excel and Google Sheets budget templates. Pay off debt and save for holidays effortlessly.">
    
    <style>
        /* CSS Styling: Using calming blues and greens for financial trust */
        :root {
            --primary-color: #2C7A7B; /* Calming Teal */
            --secondary-color: #319795; 
            --accent-color: #DD6B20; /* High-contrast Orange for CTAs */
            --text-dark: #2D3748;
            --bg-light: #F7FAFC;
        }

        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }

        body {
            background-color: var(--bg-light);
            color: var(--text-dark);
            line-height: 1.6;
        }

        /* Navigation */
        nav {
            background-color: white;
            padding: 1rem 5%;
            display: flex;
            justify-content: space-between;
            align-items: center;
            box-shadow: 0 2px 4px rgba(0,0,0,0.1);
        }

        .logo {
            font-size: 1.5rem;
            font-weight: bold;
            color: var(--primary-color);
        }

        /* Hero Section */
        header {
            background-color: var(--primary-color);
            color: white;
            text-align: center;
            padding: 5rem 1rem;
        }

        header h1 {
            font-size: 2.5rem;
            margin-bottom: 1rem;
        }

        header p {
            font-size: 1.2rem;
            margin-bottom: 2rem;
            max-width: 600px;
            margin-left: auto;
            margin-right: auto;
        }

        .cta-button {
            background-color: var(--accent-color);
            color: white;
            padding: 15px 30px;
            text-decoration: none;
            font-size: 1.2rem;
            font-weight: bold;
            border-radius: 5px;
            transition: background-color 0.3s ease;
            display: inline-block;
        }

        .cta-button:hover {
            background-color: #C05621;
        }

        /* Features / Products Section */
        .products {
            padding: 4rem 5%;
            text-align: center;
        }

        .product-grid {
            display: flex;
            flex-wrap: wrap;
            gap: 2rem;
            justify-content: center;
            margin-top: 2rem;
        }

        .card {
            background: white;
            padding: 2rem;
            border-radius: 8px;
            box-shadow: 0 4px 6px rgba(0,0,0,0.05);
            width: 300px;
            text-align: left;
            border-top: 5px solid var(--secondary-color);
        }

        .card h3 {
            margin-bottom: 1rem;
            color: var(--text-dark);
        }

        .price {
            font-size: 1.5rem;
            font-weight: bold;
            color: var(--primary-color);
            margin-bottom: 1rem;
        }

        /* Social Proof Section */
        .social-proof {
            background-color: #E6FFFA;
            padding: 3rem 5%;
            text-align: center;
            border-top: 1px solid #B2F5EA;
            border-bottom: 1px solid #B2F5EA;
        }

        .social-proof p {
            font-style: italic;
            font-size: 1.2rem;
            color: var(--primary-color);
            margin-bottom: 1rem;
        }

        /* Footer & Privacy Note */
        footer {
            background-color: var(--text-dark);
            color: white;
            text-align: center;
            padding: 2rem;
            font-size: 0.9rem;
        }
        
        .privacy-note {
            font-size: 0.8rem;
            color: #A0AEC0;
            margin-top: 10px;
        }
    </style>
</head>
<body>

    <nav>
        <div class="logo">Everyday Budget Trackers</div>
    </nav>

    <header>
        <h1>Stress-Free Budgeting for Beginners</h1>
        <p>Stop guessing where your money goes. Use our simple, pre-formatted Excel and Google Sheets templates to track spending, pay off debt, and save for your next holiday.</p>
        <!-- CTA using persuasive copy and high contrast -->
        <a href="#products" class="cta-button">Start Saving Today</a>
    </header>

    <section class="social-proof">
        <!-- Social Proof Principle -->
        <p>"I've always hated spreadsheets, but this template was so easy to set up. I saved $500 for my trip in just 3 months!"</p>
        <strong>- Sarah J., Verified Customer</strong><br>
        <span style="font-size: 0.9rem; color: #4A5568;">Join over 1,000 beginners taking control of their finances.</span>
    </section>

    <section class="products" id="products">
        <h2>Choose Your Tracker</h2>
        <div class="product-grid">
            
            <div class="card">
                <h3>Daily Spending Tracker</h3>
                <div class="price">$5.00</div>
                <p>Log your daily coffee, groceries, and bills. Includes automated charts so you can see exactly where your money goes.</p>
                <br>
                <!-- CTA Principle -->
                <a href="#" class="cta-button" style="padding: 10px 20px; font-size: 1rem; width: 100%; text-align: center;">Get Template</a>
            </div>

            <div class="card">
                <h3>Debt Payoff Planner</h3>
                <div class="price">$7.00</div>
                <p>Visual progress bars to keep you motivated. Calculate your payoff date and track your monthly minimums easily.</p>
                <br>
                <a href="#" class="cta-button" style="padding: 10px 20px; font-size: 1rem; width: 100%; text-align: center;">Get Template</a>
            </div>

            <div class="card">
                <h3>Holiday Savings Goal</h3>
                <div class="price">$5.00</div>
                <p>Set a target amount for your next trip. Enter your weekly savings to automatically see how many weeks left until you hit your goal.</p>
                <br>
                <a href="#" class="cta-button" style="padding: 10px 20px; font-size: 1rem; width: 100%; text-align: center;">Get Template</a>
            </div>

        </div>
    </section>

    <footer>
        <p>&copy; 2024 Everyday Budget Trackers. All rights reserved.</p>
        <!-- Privacy/Ethics Note -->
        <p class="privacy-note">Privacy Note: We respect your data. This site uses basic cookies for traffic analytics only. No financial data is collected or stored on this website.</p>
    </footer>

</body>
</html>
