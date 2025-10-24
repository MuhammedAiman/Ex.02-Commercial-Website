# Ex02 Commercial Website
## Date:24/10/2025
## Name:MUHAMMED AIMAN S
## Reg no:212224240097

## AIM
To create a commercial website using CSS Flexbox.

## ALGORITHM
### STEP 1
Create an HTML file (index.html)

### STEP 2
Create a CSS file (style.css)

### STEP 3
Include a navigation bar with links to different sections.

### STEP 4
Add structured sections for Homepage, Products / Services, About Us, Contact Details and User Account.

### STEP 5
Include social media links at the footer with copyright information.

### STEP 6
Define global styles for fonts, colors, and layout.

### STEP 7
Style the header, navigation bar, and sections.

### STEP 8
Use Flexbox for layout design.

### STEP 9
Add hover effects and transitions for interactivity.

### STEP 10
Add Images and Media.

### STEP 11
Use optimized images for a professional look.

### STEP 12
Open the HTML file in a browser to check layout and functionality.

### STEP 13
Fix styling issues and refine content placement.

### STEP 14
Deploy the website.

### STEP 15
Upload to GitHub Pages for free hosting.

## PROGRAM
```
<!doctype html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Simple Commercial Website</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
      background: #f8f9fa;
      color: #333;
    }
    header {
      background: #0d6efd;
      color: white;
      padding: 15px;
      display: flex;
      justify-content: space-between;
      align-items: center;
    }
    header h1 {
      margin: 0;
      font-size: 22px;
    }
    nav a {
      color: white;
      text-decoration: none;
      margin-left: 15px;
    }
    nav a:hover {
      text-decoration: underline;
    }

    .hero {
      display: flex;
      flex-direction: column;
      align-items: center;
      text-align: center;
      padding: 60px 20px;
      background: white;
    }
    .hero h2 {
      font-size: 28px;
      margin-bottom: 10px;
    }
    .hero p {
      max-width: 600px;
      color: #555;
    }

    .features {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      gap: 20px;
      padding: 40px 20px;
      background: #e9ecef;
    }
    .feature {
      background: white;
      padding: 20px;
      border-radius: 8px;
      width: 250px;
      text-align: center;
      box-shadow: 0 2px 5px rgba(0,0,0,0.1);
    }

    .products {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      gap: 20px;
      padding: 40px 20px;
    }
    .product {
      background: white;
      padding: 15px;
      border-radius: 8px;
      width: 250px;
      text-align: center;
      box-shadow: 0 2px 5px rgba(0,0,0,0.1);
    }
    .product img {
      width: 100%;
      border-radius: 6px;
    }
    .product h4 {
      margin: 10px 0 5px;
    }

    footer {
      background: #0d6efd;
      color: white;
      text-align: center;
      padding: 15px;
    }
  </style>
</head>
<body>
  <header>
    <h1>Acme Solutions</h1>
    <nav>
      <a href="#features">Features</a>
      <a href="#products">Products</a>
      <a href="#contact">Contact</a>
    </nav>
  </header>

  <section class="hero">
    <h2>Grow Your Business Smarter</h2>
    <p>We help you scale faster with powerful tools for sales, analytics, and automation.</p>
  </section>

  <section id="features" class="features">
    <div class="feature">
      <h3>Fast Setup</h3>
      <p>Start in minutes with simple onboarding.</p>
    </div>
    <div class="feature">
      <h3>Secure</h3>
      <p>Your data stays protected at all times.</p>
    </div>
    <div class="feature">
      <h3>Support</h3>
      <p>Our team is here 24/7 for your needs.</p>
    </div>
  </section>

  <section id="products" class="products">
    <div class="product">
      <img src="c:\Users\admin\OneDrive\Desktop\CRM_header_Mar25.webp" alt="Product 1">
      <h4>CRM Software</h4>
      <p>Manage your leads easily.</p>
      <p><strong>₹799 / month</strong></p>
    </div>
    <div class="product">
      <img src="c:\Users\admin\OneDrive\Desktop\download.jpeg" alt="Product 2">
      <h4>Analytics Tool</h4>
      <p>Understand your business better.</p>
      <p><strong>₹1,499 / month</strong></p>
    </div>
  </section>

  <footer>
    <p>© <span id="year"></span> Acme Solutions. All rights reserved.</p>
  </footer>

  <script>
    document.getElementById('year').textContent = new Date().getFullYear();
  </script>
</body>
</html>

```

## OUTPUT
<img width="1920" height="1200" alt="Screenshot (7)" src="https://github.com/user-attachments/assets/4ab90120-e08f-4186-9033-78ce76899fdb" />


## RESULT
The program for creating commercial website using CSS Flexbox is executed successfully.
