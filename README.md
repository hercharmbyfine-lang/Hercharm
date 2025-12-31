# Hercharm
Personal blog for fashion, beauty &amp; lifestyle 
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Hercharm</title>
  <link href="https://fonts.googleapis.com/css2?family=Playfair+Display:wght@400;700&family=Roboto&display=swap" rel="stylesheet">
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <header>
    <div class="container">
      <h1>Hercharm</h1>
      <nav>
        <a href="#home">Home</a>
        <a href="#about">About</a>
        <a href="#blog">Blog</a>
        <a href="#contact">Contact</a>
      </nav>
    </div>
  </header>

  <section id="home" class="hero">
    <div class="container">
      <h2>Everything Fashion, Beauty & Essentials for Women</h2>
      <p>Welcome to Hercharm – your daily dose of inspiration, style tips, and lifestyle essentials.</p>
    </div>
  </section>

  <section id="about" class="about">
    <div class="container">
      <h2>About Me</h2>
      <p>Hello! I’m Fine, the founder of Hercharm. Here, I share everything about fashion, beauty, and must-have essentials for women who love to look and feel their best.</p>
    </div>
  </section>

  <section id="blog" class="blog">
    <div class="container">
      <h2>Latest Blog Posts</h2>
      <div class="posts">
        <article class="post">
          <img src="https://via.placeholder.com/400x250" alt="Blog Post">
          <h3>5 Must-Have Skincare Products for Glowy Skin</h3>
          <p>Discover the top products that will give your skin a radiant, healthy glow this season...</p>
          <a href="#">Read More</a>
        </article>

        <article class="post">
          <img src="https://via.placeholder.com/400x250" alt="Blog Post">
          <h3>Fashion Trends Every Woman Should Try</h3>
          <p>Stay ahead with these chic trends that are dominating the fashion world...</p>
          <a href="#">Read More</a>
        </article>

        <article class="post">
          <img src="https://via.placeholder.com/400x250" alt="Blog Post">
          <h3>Essentials Every Woman Needs in Her Closet</h3>
          <p>From classic staples to statement pieces, here’s your ultimate checklist...</p>
          <a href="#">Read More</a>
        </article>
      </div>
    </div>
  </section>

  <section id="contact" class="contact">
    <div class="container">
      <h2>Contact Me</h2>
      <p>Have questions or suggestions? Reach out via email at <a href="mailto:Hercharmbyfine@gmail.com">Hercharmbyfine@gmail.com</a></p>
      <form action="mailto:Hercharmbyfine@gmail.com" method="post" enctype="text/plain">
        <input type="text" name="name" placeholder="Your Name" required>
        <input type="email" name="email" placeholder="Your Email" required>
        <textarea name="message" placeholder="Your Message" rows="5" required></textarea>
        <button type="submit">Send Message</button>
      </form>
    </div>
  </section>

  <footer>
    <div class="container">
      <p>&copy; 2025 Hercharm. All rights reserved.</p>
    </div>
  </footer>
</body>
</html>
/* Global Styles */
body {
  font-family: 'Roboto', sans-serif;
  margin: 0;
  padding: 0;
  color: #333;
  background-color: #fff8f5;
}

.container {
  width: 90%;
  max-width: 1100px;
  margin: auto;
}

a {
  text-decoration: none;
  color: #d98fbf;
}

/* Header */
header {
  background-color: #ffeef2;
  padding: 20px 0;
  box-shadow: 0 2px 4px rgba(0,0,0,0.05);
}

header h1 {
  display: inline-block;
  font-family: 'Playfair Display', serif;
  margin: 0;
  color: #d98fbf;
}

header nav {
  float: right;
}

header nav a {
  margin-left: 20px;
  font-weight: bold;
}

/* Hero Section */
.hero {
  text-align: center;
  padding: 80px 20px;
  background-color: #fff0f6;
}

.hero h2 {
  font-family: 'Playfair Display', serif;
  color: #d98fbf;
  font-size: 36px;
}

.hero p {
  font-size: 18px;
  margin-top: 10px;
}

/* About Section */
.about {
  padding: 60px 20px;
  text-align: center;
}

.about h2 {
  color: #d98fbf;
  font-family: 'Playfair Display', serif;
}

/* Blog Section */
.blog {
  padding: 60px 20px;
}

.blog h2 {
  text-align: center;
  color: #d98fbf;
  font-family: 'Playfair Display', serif;
}

.posts {
  display: flex;
  flex-wrap: wrap;
  justify-content: space-between;
  gap: 20px;
  margin-top: 40px;
}

.post {
  background-color: #fff0f6;
  padding: 20px;
  border-radius: 10px;
  flex: 1 1 calc(33% - 20px);
}

.post img {
  width: 100%;
  border-radius: 10px;
}

.post h3 {
  color: #d98fbf;
  font-family: 'Playfair Display', serif;
  margin-top: 15px;
}

.post p {
  margin-top: 10px;
  font-size: 16px;
}

.post a {
  display: inline-block;
  margin-top: 10px;
  font-weight: bold;
}

/* Contact Section */
.contact {
  padding: 60px 20px;
  text-align: center;
}

.contact form {
  max-width: 500px;
  margin: auto;
  display: flex;
  flex-direction: column;
  gap: 15px;
}

.contact input, .contact textarea {
  padding: 10px;
  border: 1px solid #d98fbf;
  border-radius: 5px;
  width: 100%;
}

.contact button {
  padding: 12px;
  background-color: #d98fbf;
  border: none;
  color: white;
  font-weight: bold;
  cursor: pointer;
  border-radius: 5px;
}

/* Footer */
footer {
  background-color: #ffeef2;
  text-align: center;
  padding: 20px 0;
  margin-top: 40px;
}
