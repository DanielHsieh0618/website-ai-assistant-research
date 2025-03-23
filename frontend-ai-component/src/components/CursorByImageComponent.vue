<template>
  <div class="photo-community">
    <!-- Header -->
    <header class="header">
      <div class="logo">
        <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round">
          <path d="M23 19a2 2 0 0 1-2 2H3a2 2 0 0 1-2-2V8a2 2 0 0 1 2-2h4l2-3h6l2 3h4a2 2 0 0 1 2 2z"/>
          <circle cx="12" cy="13" r="4"/>
        </svg>
        <span>photo</span>
      </div>
      <nav class="nav-links">
        <a href="#" class="active">Features</a>
        <a href="#">Pricing</a>
        <a href="#">Community</a>
        <a href="#">Support</a>
      </nav>
      <div class="auth-buttons">
        <button class="login-btn">Log in</button>
        <button class="register-btn">Register</button>
      </div>
    </header>

    <!-- Hero Section -->
    <section class="hero">
      <div class="hero-content">
        <div class="play-button">
          <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="#fff">
            <path d="M8 5v14l11-7z"/>
          </svg>
        </div>
        <h1>The largest community of photo enthusiasts</h1>
        <button class="join-today-btn">Join Today</button>
      </div>
    </section>

    <!-- Features Section -->
    <section class="features">
      <h2>Snap photos and share like never before</h2>
      
      <div class="feature-grid">
        <div class="feature-card">
          <h3>Sed ut perspiciatis</h3>
          <p>Nemo enim ipsam voluptatem quia voluptas sit aspernatur aut odit aut fugit, sed quia consequuntur magni dolores eos qui ratione voluptatem sequi nesciunt. Neque porro quisquam est.</p>
          <a href="#" class="learn-more">Learn more</a>
        </div>

        <div class="feature-card">
          <h3>Lorem ipsum dolor</h3>
          <p>Amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi.</p>
          <a href="#" class="learn-more">Learn more</a>
        </div>

        <div class="feature-card">
          <h3>Nemo enim ipsam</h3>
          <p>Consequuntur magni dolores eos qui ratione voluptatem sequi nesciunt. Neque porro quisquam est, qui dolorem ipsum quia dolor sit amet, consectetur, adipisci velit, sed quia non numquam.</p>
          <a href="#" class="learn-more">Learn more</a>
        </div>

        <div class="feature-card">
          <h3>Tempor incididunt</h3>
          <p>Eos qui ratione voluptatem sequi nesciunt. Neque porro quisquam est, qui dolorem ipsum quia dolor sit amet, consectetur, adipisci velit, sed quia non numquam eius modi tempora.</p>
          <a href="#" class="learn-more">Learn more</a>
        </div>
      </div>
    </section>

    <!-- Content sections with image -->
    <section class="content-with-image">
      <div class="image-placeholder"></div>
      <div class="content">
        <h3>Sed ut perspiciatis unde omnis</h3>
        <p>Nemo enim ipsam voluptatem quia voluptas sit aspernatur aut odit aut fugit, sed quia consequuntur magni dolores eos qui ratione voluptatem sequi nesciunt. Neque porro quisquam est, qui dolorem.</p>
      </div>
    </section>

    <section class="content-with-image reversed">
      <div class="content">
        <h3>Sed ut perspiciatis unde omnis</h3>
        <p>Nemo enim ipsam voluptatem quia voluptas sit aspernatur aut odit aut fugit, sed quia consequuntur magni dolores eos qui ratione voluptatem sequi nesciunt. Neque porro quisquam est, qui dolorem.</p>
      </div>
      <div class="image-placeholder"></div>
    </section>

    <!-- Community Section -->
    <section class="community">
      <h2>You're in good company</h2>
      <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore</p>
      
      <div class="company-logos">
        <div class="logo-placeholder"></div>
        <div class="logo-placeholder"></div>
        <div class="logo-placeholder"></div>
        <div class="logo-placeholder"></div>
        <div class="logo-placeholder"></div>
        <div class="logo-placeholder"></div>
        <div class="logo-placeholder"></div>
        <div class="logo-placeholder"></div>
      </div>
    </section>

    <!-- CTA Section -->
    <section class="cta">
      <div class="cta-content">
        <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore</p>
        <div class="cta-buttons">
          <button class="join-today-btn">Join Today</button>
          <button class="contact-btn">Contact us</button>
        </div>
      </div>
    </section>

    <!-- Footer -->
    <footer>
      <div class="footer-links">
        <div class="footer-column">
          <h4>Mobile app</h4>
        </div>
        <div class="footer-column">
          <h4>Community</h4>
        </div>
        <div class="footer-column">
          <h4>Company</h4>
        </div>
        <div class="footer-logo">
          <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round">
            <path d="M23 19a2 2 0 0 1-2 2H3a2 2 0 0 1-2-2V8a2 2 0 0 1 2-2h4l2-3h6l2 3h4a2 2 0 0 1 2 2z"/>
            <circle cx="12" cy="13" r="4"/>
          </svg>
          <span>photo</span>
        </div>
        <div class="footer-column">
          <h4>Help desk</h4>
        </div>
        <div class="footer-column">
          <h4>Blog</h4>
        </div>
        <div class="footer-column">
          <h4>Resources</h4>
        </div>
      </div>
      
      <div class="social-links">
        <a href="#" class="social-icon">
          <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round">
            <circle cx="12" cy="12" r="10"></circle>
          </svg>
        </a>
        <a href="#" class="social-icon">
          <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round">
            <circle cx="12" cy="12" r="10"></circle>
          </svg>
        </a>
        <a href="#" class="social-icon">
          <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round">
            <circle cx="12" cy="12" r="10"></circle>
          </svg>
        </a>
        <a href="#" class="social-icon">
          <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round">
            <circle cx="12" cy="12" r="10"></circle>
          </svg>
        </a>
      </div>
      
      <div class="copyright">
        © Photo Inc. 2019. We love our users!
      </div>
    </footer>
  </div>
</template>

<script setup>
// Component logic can be added here if needed
</script>

<style scoped>
.photo-community {
  font-family: Arial, sans-serif;
  color: #333;
  line-height: 1.6;
}

/* Header Styles */
.header {
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 1rem 2rem;
  border-bottom: 1px solid #eee;
}

.logo {
  display: flex;
  align-items: center;
  gap: 0.5rem;
  font-weight: bold;
}

.nav-links {
  display: flex;
  gap: 2rem;
}

.nav-links a {
  text-decoration: none;
  color: #333;
}

.nav-links a.active {
  color: #0095ff;
}

.auth-buttons {
  display: flex;
  gap: 1rem;
}

.login-btn {
  background: none;
  border: 1px solid #0095ff;
  color: #0095ff;
  padding: 0.5rem 1rem;
  border-radius: 4px;
  cursor: pointer;
}

.register-btn {
  background: #0095ff;
  border: none;
  color: white;
  padding: 0.5rem 1rem;
  border-radius: 4px;
  cursor: pointer;
}

/* Hero Section */
.hero {
  background-image: linear-gradient(rgba(230, 230, 230, 0.4), rgba(230, 230, 230, 0.4)), url("data:image/svg+xml,%3Csvg width='100%25' height='100%25' xmlns='http://www.w3.org/2000/svg'%3E%3Crect width='100%25' height='100%25' fill='none' stroke='%23CCCCCC' stroke-width='1' stroke-dasharray='10,10' stroke-dashoffset='0' stroke-linecap='square'/%3E%3C/svg%3E");
  height: 500px;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
}

.hero-content {
  max-width: 700px;
  padding: 2rem;
}

.play-button {
  background: #0095ff;
  width: 60px;
  height: 60px;
  border-radius: 50%;
  display: flex;
  justify-content: center;
  align-items: center;
  margin: 0 auto 2rem;
  cursor: pointer;
}

h1 {
  font-size: 2.5rem;
  margin-bottom: 2rem;
}

.join-today-btn {
  background: #0095ff;
  border: none;
  color: white;
  padding: 0.75rem 1.5rem;
  border-radius: 4px;
  font-size: 1rem;
  cursor: pointer;
}

/* Features Section */
.features {
  padding: 4rem 2rem;
  text-align: center;
}

.features h2 {
  font-size: 2rem;
  margin-bottom: 3rem;
}

.feature-grid {
  display: grid;
  grid-template-columns: repeat(2, 1fr);
  gap: 2rem;
  max-width: 1200px;
  margin: 0 auto;
}

.feature-card {
  text-align: left;
  padding: 1.5rem;
}

.feature-card h3 {
  font-size: 1.25rem;
  margin-bottom: 1rem;
}

.learn-more {
  color: #0095ff;
  text-decoration: none;
  display: inline-block;
  margin-top: 1rem;
}

/* Content with Image Section */
.content-with-image {
  display: grid;
  grid-template-columns: 1fr 1fr;
  align-items: center;
  padding: 4rem 2rem;
  background-color: #f9f9f9;
}

.content-with-image.reversed {
  background-color: white;
}

.image-placeholder {
  background-image: url("data:image/svg+xml,%3Csvg width='100%25' height='100%25' xmlns='http://www.w3.org/2000/svg'%3E%3Crect width='100%25' height='100%25' fill='none' stroke='%23CCCCCC' stroke-width='1' stroke-dasharray='10,10' stroke-dashoffset='0' stroke-linecap='square'/%3E%3C/svg%3E");
  height: 300px;
  margin: 1rem;
}

.content {
  padding: 2rem;
}

.content h3 {
  font-size: 1.5rem;
  margin-bottom: 1.5rem;
}

/* Community Section */
.community {
  padding: 4rem 2rem;
  text-align: center;
  background-color: #f9f9f9;
}

.community h2 {
  font-size: 2rem;
  margin-bottom: 1rem;
}

.community p {
  max-width: 600px;
  margin: 0 auto 3rem;
}

.company-logos {
  display: grid;
  grid-template-columns: repeat(4, 1fr);
  gap: 2rem;
  max-width: 1000px;
  margin: 0 auto;
}

.logo-placeholder {
  background-image: url("data:image/svg+xml,%3Csvg width='100%25' height='100%25' xmlns='http://www.w3.org/2000/svg'%3E%3Crect width='100%25' height='100%25' fill='none' stroke='%23CCCCCC' stroke-width='1' stroke-dasharray='10,10' stroke-dashoffset='0' stroke-linecap='square'/%3E%3C/svg%3E");
  height: 60px;
  margin: 0.5rem;
}

/* CTA Section */
.cta {
  padding: 4rem 2rem;
  background-color: #f1f1f1;
  text-align: center;
}

.cta-content {
  max-width: 800px;
  margin: 0 auto;
}

.cta p {
  font-size: 1.25rem;
  margin-bottom: 2rem;
}

.cta-buttons {
  display: flex;
  justify-content: center;
  gap: 1rem;
}

.contact-btn {
  background: none;
  border: 1px solid #0095ff;
  color: #0095ff;
  padding: 0.75rem 1.5rem;
  border-radius: 4px;
  font-size: 1rem;
  cursor: pointer;
}

/* Footer */
footer {
  padding: 4rem 2rem 2rem;
  background-color: #f9f9f9;
}

.footer-links {
  display: grid;
  grid-template-columns: repeat(7, 1fr);
  gap: 1rem;
  margin-bottom: 3rem;
}

.footer-column h4 {
  font-size: 1rem;
  font-weight: bold;
  margin-bottom: 1rem;
}

.footer-logo {
  display: flex;
  flex-direction: column;
  align-items: center;
  gap: 0.5rem;
}

.social-links {
  display: flex;
  justify-content: center;
  gap: 1.5rem;
  margin-bottom: 2rem;
}

.social-icon {
  width: 40px;
  height: 40px;
  display: flex;
  align-items: center;
  justify-content: center;
  border-radius: 50%;
  background-color: #eee;
}

.copyright {
  text-align: center;
  color: #666;
  font-size: 0.875rem;
}

/* Responsive styles */
@media (max-width: 768px) {
  .feature-grid {
    grid-template-columns: 1fr;
  }
  
  .content-with-image {
    grid-template-columns: 1fr;
  }
  
  .company-logos {
    grid-template-columns: repeat(2, 1fr);
  }
  
  .footer-links {
    grid-template-columns: repeat(2, 1fr);
    gap: 2rem;
  }
  
  .footer-logo {
    grid-column: span 2;
    margin: 2rem 0;
  }
}
</style>