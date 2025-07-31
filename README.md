<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta name="description" content="Welcome to Example Site - Learn about accessibility, semantic HTML, and SEO basics through a simple example.">
  <meta name="author" content="Your Name">
  <title>Accessibility & SEO Friendly HTML5 Page</title>
</head>
<body>

  <header>
    <h1>Welcome to Example Site</h1>
    <p>Your guide to accessibility, semantic HTML5, and SEO.</p>
  </header>

  <nav aria-label="Main navigation">
    <ul>
      <li><a href="#about" title="Learn more about this site">About</a></li>
      <li><a href="#services" title="View the services we offer">Services</a></li>
      <li><a href="#contact" title="Get in touch with us">Contact</a></li>
    </ul>
  </nav>

  <main>
    <section id="about" aria-labelledby="about-heading">
      <h2 id="about-heading">About This Site</h2>
      <p>This web page is built using semantic HTML5 tags and structured to support screen readers and SEO-friendly indexing.</p>
    </section>

    <section id="services" aria-labelledby="services-heading">
      <h2 id="services-heading">Our Services</h2>
      <article>
        <h3>Accessible Design</h3>
        <p>We ensure every website is usable by people of all abilities, using semantic structure and ARIA roles.</p>
      </article>
      <article>
        <h3>SEO Optimization</h3>
        <p>Using clean code, metadata, and proper headings, we help websites rank better in search results.</p>
      </article>
    </section>

    <section id="contact" aria-labelledby="contact-heading">
      <h2 id="contact-heading">Contact Us</h2>
      <p>Email us at <a href="mailto:info@example.com">info@example.com</a> or call <a href="tel:+123456789">+1 (234) 567-89</a>.</p>
    </section>
  </main>

  <footer>
    <p>&copy; 2025 Example Site. All rights reserved.</p>
  </footer>

</body>
</html>
