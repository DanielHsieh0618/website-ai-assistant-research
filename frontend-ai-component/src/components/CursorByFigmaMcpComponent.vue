<template>
  <div class="sample-wireframe">
    <!-- Navigation Section -->
    <div class="navigation">
      <div class="logo">
        <span class="logo-text">photo</span>
        <div class="logo-icon"></div>
      </div>
      
      <div class="nav-links">
        <a href="#" class="nav-link">Features</a>
        <a href="#" class="nav-link">Pricing</a>
        <a href="#" class="nav-link">Community</a>
        <a href="#" class="nav-link">Support</a>
      </div>
      
      <div class="auth-buttons">
        <button class="btn btn-primary">Register</button>
        <button class="btn btn-outline">Log in</button>
      </div>
    </div>
    
    <!-- Hero Section -->
    <div class="hero">
      <div class="hero-content">
        <h1 class="hero-title">The largest community of photo enthusiasts</h1>
        <button class="btn btn-primary btn-large">Join Today</button>
        <div class="play-button">
          <div class="play-circle"></div>
          <div class="play-triangle"></div>
        </div>
      </div>
      <div class="hero-image">
        <img src="../assets/hero-image.svg" alt="Hero" />
      </div>
    </div>
    
    <!-- Body Section - Features -->
    <div class="body-section">
      <h2 class="section-title">Snap photos and share like never before</h2>
      
      <div class="features-grid">
        <div class="feature">
          <h3 class="feature-title">Sed ut perspiciatis</h3>
          <p class="feature-text">Nemo enim ipsam voluptatem quia voluptas sit aspernatur aut odit aut fugit, sed quia consequuntur magni dolores eos qui ratione voluptatem sequi nesciunt. Neque porro quisquam est.</p>
          <button class="btn btn-outline">Learn more</button>
        </div>
        
        <div class="feature">
          <h3 class="feature-title">Lorem ipsum dolor</h3>
          <p class="feature-text">Amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi.</p>
          <button class="btn btn-outline">Learn more</button>
        </div>
        
        <div class="feature">
          <h3 class="feature-title">Nemo enim ipsam</h3>
          <p class="feature-text">Consequuntur magni dolores eos qui ratione voluptatem sequi nesciunt. Neque porro quisquam est, qui dolorem ipsum quia dolor sit amet, consectetur, adipisci velit, sed quia non numquam.</p>
          <button class="btn btn-outline">Learn more</button>
        </div>
        
        <div class="feature">
          <h3 class="feature-title">Tempor incididunt</h3>
          <p class="feature-text">Eos qui ratione voluptatem sequi nesciunt. Neque porro quisquam est, qui dolorem ipsum quia dolor sit amet, consectetur, adipisci velit, sed quia non numquam eius modi tempora.</p>
          <button class="btn btn-outline">Learn more</button>
        </div>
      </div>
    </div>
    
    <!-- Body Section - With Image -->
    <div class="body-section grey-bg">
      <div class="image-content-section">
        <div class="section-image">
          <img src="../assets/body-image-1.svg" alt="Feature" />
        </div>
        <div class="section-content">
          <h3 class="feature-title">Sed ut perspiciatis unde omnis</h3>
          <p class="feature-text">Nemo enim ipsam voluptatem quia voluptas sit aspernatur aut odit aut fugit, sed quia consequuntur magni dolores eos qui ratione voluptatem sequi nesciunt. Neque porro quisquam est, qui dolorem.</p>
        </div>
      </div>
    </div>
    
    <!-- Body Section - With Image Reversed -->
    <div class="body-section">
      <div class="image-content-section reverse">
        <div class="section-image">
          <img src="../assets/body-image-2.svg" alt="Feature" />
        </div>
        <div class="section-content">
          <h3 class="feature-title">Sed ut perspiciatis unde omnis</h3>
          <p class="feature-text">Nemo enim ipsam voluptatem quia voluptas sit aspernatur aut odit aut fugit, sed quia consequuntur magni dolores eos qui ratione voluptatem sequi nesciunt. Neque porro quisquam est, qui dolorem.</p>
        </div>
      </div>
    </div>
    
    <!-- Testimonials Section -->
    <div class="testimonial-section">
      <div class="testimonial-grid">
        <div class="testimonial-image" v-for="i in 8" :key="i">
          <img src="../assets/testimonial-1.svg" alt="Testimonial" />
        </div>
      </div>
      
      <div class="testimonial-content">
        <h2 class="testimonial-title">You're in good company</h2>
        <p class="testimonial-text">Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore</p>
      </div>
    </div>
    
    <!-- Signup Section -->
    <div class="signup-section">
      <p class="signup-text">Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore</p>
      <div class="signup-buttons">
        <button class="btn btn-primary btn-large">Join Today</button>
        <button class="btn btn-outline-white btn-large">Contact us</button>
      </div>
    </div>
    
    <!-- Footer -->
    <div class="footer">
      <div class="footer-top">
        <div class="footer-logo">
          <span class="logo-text">photo</span>
          <div class="logo-icon"></div>
        </div>
        
        <div class="footer-links">
          <div class="footer-column">
            <h4 class="footer-heading">Mobile app</h4>
            <div class="social-icons">
              <a href="#" class="social-icon" v-for="i in 4" :key="i"></a>
            </div>
          </div>
          
          <div class="footer-column">
            <h4 class="footer-heading">Community</h4>
          </div>
          
          <div class="footer-column">
            <h4 class="footer-heading">Company</h4>
            <div class="footer-link-list">
              <a href="#" class="footer-link">Help desk</a>
              <a href="#" class="footer-link">Blog</a>
              <a href="#" class="footer-link">Resources</a>
            </div>
          </div>
        </div>
      </div>
      
      <div class="footer-bottom">
        <p class="copyright">© Photo, Inc. 2019. We love our users!</p>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'CursorByFigmaMcpComponent'
}
</script>

<style scoped>
/* Global Styles */
.sample-wireframe {
  font-family: 'Montserrat', sans-serif;
  color: #000000;
  margin: 0;
  padding: 0;
}

.btn {
  border-radius: 6px;
  font-weight: 500;
  cursor: pointer;
  padding: 12px 20px;
  font-size: 15px;
  text-align: center;
  border: none;
  transition: all 0.3s ease;
}

.btn-primary {
  background-color: #18A0FB;
  color: white;
  border: none;
}

.btn-outline {
  background-color: white;
  color: #18A0FB;
  border: 1px solid #18A0FB;
}

.btn-outline-white {
  background-color: transparent;
  color: #18A0FB;
  border: 1px solid #18A0FB;
}

.btn-large {
  font-size: 17px;
  padding: 15px 30px;
}

/* Navigation Styles */
.navigation {
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 20px 80px;
  background-color: white;
}

.logo {
  display: flex;
  align-items: center;
}

.logo-text {
  font-family: 'Comfortaa', sans-serif;
  font-size: 28px;
  font-weight: 400;
  margin-right: 10px;
}

.logo-icon {
  width: 40px;
  height: 40px;
  background-color: #CCCCCC;
}

.nav-links {
  display: flex;
  gap: 30px;
}

.nav-link {
  color: black;
  text-decoration: none;
  font-size: 15px;
  font-weight: 500;
}

.auth-buttons {
  display: flex;
  gap: 10px;
}

/* Hero Section */
.hero {
  display: flex;
  align-items: center;
  padding: 80px;
  background-color: white;
}

.hero-content {
  flex: 1;
  display: flex;
  flex-direction: column;
  align-items: center;
  gap: 30px;
}

.hero-title {
  font-size: 56px;
  font-weight: 400;
  text-align: center;
  max-width: 700px;
}

.play-button {
  position: relative;
  margin-top: 20px;
}

.play-circle {
  width: 80px;
  height: 80px;
  border-radius: 50%;
  background-color: #18A0FB;
}

.play-triangle {
  position: absolute;
  top: 50%;
  left: 55%;
  transform: translate(-50%, -50%);
  width: 0;
  height: 0;
  border-top: 15px solid transparent;
  border-left: 25px solid white;
  border-bottom: 15px solid transparent;
}

.hero-image {
  flex: 1;
}

.hero-image img {
  width: 100%;
  height: auto;
}

/* Body Section */
.body-section {
  padding: 80px;
  background-color: white;
}

.grey-bg {
  background-color: #F5F5F5;
}

.section-title {
  font-size: 48px;
  font-weight: 400;
  text-align: left;
  margin-bottom: 60px;
}

.features-grid {
  display: grid;
  grid-template-columns: repeat(2, 1fr);
  gap: 40px;
}

.feature {
  display: flex;
  flex-direction: column;
  gap: 20px;
}

.feature-title {
  font-size: 24px;
  font-weight: 700;
  margin: 0;
}

.feature-text {
  font-size: 18px;
  font-weight: 400;
  color: rgba(0, 0, 0, 0.8);
  line-height: 1.6;
  margin: 0;
}

.image-content-section {
  display: flex;
  align-items: center;
  gap: 80px;
}

.image-content-section.reverse {
  flex-direction: row-reverse;
}

.section-image {
  flex: 1;
}

.section-image img {
  width: 100%;
  height: auto;
}

.section-content {
  flex: 1;
}

/* Testimonial Section */
.testimonial-section {
  padding: 80px;
  background-color: white;
  display: flex;
  flex-direction: column;
  align-items: center;
}

.testimonial-grid {
  display: grid;
  grid-template-columns: repeat(4, 1fr);
  gap: 20px;
  width: 100%;
  margin-bottom: 60px;
}

.testimonial-image img {
  width: 100%;
  height: auto;
  border: 1px solid rgba(0, 0, 0, 0.3);
}

.testimonial-content {
  text-align: center;
  max-width: 800px;
}

.testimonial-title {
  font-size: 48px;
  font-weight: 400;
  margin-bottom: 20px;
}

.testimonial-text {
  font-size: 36px;
  font-weight: 400;
  color: rgba(0, 0, 0, 0.8);
  line-height: 1.4;
}

/* Signup Section */
.signup-section {
  padding: 80px;
  background-color: #F5F5F5;
  display: flex;
  flex-direction: column;
  gap: 40px;
}

.signup-text {
  font-size: 36px;
  font-weight: 400;
  color: rgba(0, 0, 0, 0.8);
  line-height: 1.4;
  max-width: 800px;
}

.signup-buttons {
  display: flex;
  gap: 20px;
}

/* Footer */
.footer {
  background-color: white;
  padding: 80px 80px 40px;
}

.footer-top {
  display: flex;
  justify-content: space-between;
  margin-bottom: 40px;
}

.footer-logo {
  display: flex;
  align-items: center;
}

.footer-links {
  display: flex;
  gap: 80px;
}

.footer-column {
  display: flex;
  flex-direction: column;
  gap: 20px;
}

.footer-heading {
  font-size: 15px;
  font-weight: 700;
  margin: 0;
}

.social-icons {
  display: flex;
  gap: 10px;
}

.social-icon {
  width: 30px;
  height: 30px;
  border-radius: 50%;
  border: 1px solid rgba(0, 0, 0, 0.3);
  display: block;
}

.footer-link-list {
  display: flex;
  flex-direction: column;
  align-items: flex-end;
  gap: 10px;
}

.footer-link {
  font-size: 15px;
  font-weight: 700;
  color: black;
  text-decoration: none;
}

.footer-bottom {
  border-top: 1px solid rgba(0, 0, 0, 0.5);
  padding-top: 20px;
  display: flex;
  justify-content: center;
}

.copyright {
  font-size: 15px;
  font-weight: 400;
  color: rgba(0, 0, 0, 0.8);
}

/* Responsive Adjustments */
@media (max-width: 1200px) {
  .navigation, .hero, .body-section, .testimonial-section, .signup-section, .footer {
    padding: 60px 40px;
  }
  
  .hero-title {
    font-size: 48px;
  }
  
  .features-grid {
    grid-template-columns: 1fr;
  }
  
  .testimonial-grid {
    grid-template-columns: repeat(3, 1fr);
  }
}

@media (max-width: 768px) {
  .navigation {
    flex-wrap: wrap;
  }
  
  .nav-links {
    order: 3;
    margin-top: 20px;
    width: 100%;
    justify-content: center;
  }
  
  .hero {
    flex-direction: column;
  }
  
  .hero-content {
    margin-bottom: 40px;
  }
  
  .image-content-section, .image-content-section.reverse {
    flex-direction: column;
  }
  
  .section-image {
    margin-bottom: 40px;
  }
  
  .testimonial-grid {
    grid-template-columns: repeat(2, 1fr);
  }
  
  .footer-top {
    flex-direction: column;
    gap: 40px;
  }
  
  .footer-links {
    flex-direction: column;
    gap: 30px;
  }
}

@media (max-width: 480px) {
  .testimonial-grid {
    grid-template-columns: 1fr;
  }
  
  .signup-buttons {
    flex-direction: column;
  }
}
</style>
