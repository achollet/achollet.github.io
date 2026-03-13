<!-- Hero section moved from home.md -->
<section class="section section-home" style="background: linear-gradient(135deg, #0A0E27 0%, #1A1F3A 100%); min-height: 100vh; display: flex; align-items: center; justify-content: center; padding: 4rem 2rem; position: relative; overflow: hidden;">
  <!-- Diagonal shape background -->
  <div style="position: absolute; top: 0; right: 0; width: 50%; height: 100%; background: linear-gradient(135deg, rgba(255, 46, 92, 0.1) 0%, transparent 100%); clip-path: polygon(100% 0, 100% 100%, 0% 100%); z-index: 0;"></div>
  
  <div class="home-container" style="display: grid; grid-template-columns: 1fr 1fr; gap: 4rem; align-items: center; max-width: 1200px; width: 100%; z-index: 1; position: relative;">
    
    <!-- Left side: Profile -->
    <div style="display: flex; flex-direction: column; align-items: center; gap: 2rem;">
      <div style="width: 280px; height: 320px; background: linear-gradient(135deg, #FF2E5C 0%, #FF5C8A 100%); border-radius: 20px; padding: 8px; box-shadow: 0 20px 60px rgba(255, 46, 92, 0.3);">
        <img src="/assets/images/profile.png" alt="Alexis Chollet" style="width: 100%; height: 100%; object-fit: cover; border-radius: 16px; display: block;">
      </div>
      
      <div style="text-align: center;">
        <h2 style="color: #FF2E5C; font-size: 2rem; margin: 0 0 0.5rem 0; font-weight: 700;">Alexis Chollet</h2>
        <p style="color: #8B8B8B; font-size: 1.1rem; margin: 0;">Senior Backend Developer</p>
      </div>
    </div>
    
    <!-- Right side: Content -->
    <div class="home-content" style="display: flex; flex-direction: column; gap: 2rem; color: #F0F0F0;">
      <div>
        <h1 style="font-size: 3.5rem; margin: 0 0 1rem 0; color: #F0F0F0; font-weight: 700; line-height: 1.2;">Hello, I'm<br><span style="color: #FF2E5C;">Alexis Chollet</span></h1>
        <p style="font-size: 1.2rem; color: #8B8B8B; margin: 0; font-weight: 500;">.NET Senior Software Engineer</p>
      </div>
      
      <p style="color: #D0D0D0; line-height: 1.8; font-size: 1.05rem; margin: 0;">
        Backend developer since 2015 with a background in scientific research, I naturally gravitate toward solving complex problems with structured and thoughtful solutions.
        I care deeply about clean code, design for failure, and building tools that truly meet user needs.
      </p>

      <div style="display: flex; flex-direction: column; gap: 1rem;">
        <p style="color: #8B8B8B; font-size: 0.95rem; margin: 0; text-transform: uppercase; letter-spacing: 1px; font-weight: 600;">Tech Stack</p>
        <div class="badges" style="gap: 0.6rem;">
          <img src="https://img.shields.io/badge/C%23-13-239120?style=for-the-badge&logo=c-sharp&logoColor=white" alt="C# 13"/>
          <img src="https://img.shields.io/badge/.NET-9-512BD4?style=for-the-badge&logo=dotnet&logoColor=white" alt=".NET 9"/>
          <img src="https://img.shields.io/badge/T--SQL-CC2927?style=for-the-badge&logo=microsoftsqlserver&logoColor=white" alt="T-SQL"/>
          <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white" alt="PostgreSQL"/>
        </div>
        
        <div class="badges" style="gap: 0.6rem;">
          <img src="https://img.shields.io/badge/AWS-FF9900?style=for-the-badge&logo=amazonaws&logoColor=white" alt="AWS"/>
          <img src="https://img.shields.io/badge/Azure-0078D4?style=for-the-badge&logo=microsoftazure&logoColor=white" alt="Azure"/>
          <img src="https://img.shields.io/badge/BDD-25A162?style=for-the-badge" alt="BDD"/>
          <img src="https://img.shields.io/badge/TDD-CC0000?style=for-the-badge" alt="TDD"/>
        </div>
      </div>

      <div style="display: flex; gap: 1rem; margin-top: 1rem;">
        <a href="#contact" style="background: #FF2E5C; color: white; padding: 0.8rem 2rem; border-radius: 6px; text-decoration: none; font-weight: 600; transition: all 0.3s ease; border: 2px solid #FF2E5C;" onmouseover="this.style.background='transparent'; this.style.color='#FF2E5C';" onmouseout="this.style.background='#FF2E5C'; this.style.color='white';">
          Get in Touch
        </a>
        <a href="#resume" style="background: transparent; color: #FF2E5C; padding: 0.8rem 2rem; border-radius: 6px; text-decoration: none; font-weight: 600; transition: all 0.3s ease; border: 2px solid #FF2E5C;" onmouseover="this.style.background='#FF2E5C'; this.style.color='white';" onmouseout="this.style.background='transparent'; this.style.color='#FF2E5C';">
          View Resume
        </a>
      </div>
    </div>
  </div>

  <!-- Responsive adjustments -->
  <style>
    @media (max-width: 1024px) {
      .section-home .home-container {
        grid-template-columns: 1fr;
        gap: 2rem;
      }
    }
    
    @media (max-width: 768px) {
      .section-home {
        padding: 2rem 1rem;
      }
      
      .section-home .home-container {
        gap: 1.5rem;
      }
      
      .section-home h1 {
        font-size: 2.5rem !important;
      }
    }
  </style>
</section>

<!-- About Me section -->
<section id="aboutme" class="section aboutme-section" style="background: linear-gradient(135deg, #0A0E27 0%, rgba(255, 46, 92, 0.05) 100%); min-height: 100vh; display: flex; flex-direction: column; justify-content: center; align-items: center; padding: 4rem 2rem;">
  <div style="max-width: 800px; text-align: center;">
    <h2 class="section-title" style="color: #FF2E5C; font-size: 2.5rem; margin-bottom: 2rem;">About Me</h2>
    
    <p style="color: #8B8B8B; line-height: 1.8; font-size: 1.1rem; margin-bottom: 3rem;">
      Développeur backend depuis 2015, avec un parcours en recherche scientifique, je suis naturellement porté vers la résolution de problèmes complexes par des solutions structurées et réfléchies.
      Attaché au clean code, à la résilience applicative et à l'utilité concrète des outils livrés, j'ai également une expérience en event sourcing et en conception de systèmes robustes.
    </p>
    
    <div style="display: flex; justify-content: center; gap: 3rem; flex-wrap: wrap; margin-top: 4rem;">
      <a href="mailto:your-email@example.com" style="display: flex; flex-direction: column; align-items: center; gap: 1rem; text-decoration: none; transition: all 0.3s ease; padding: 2rem; color: #F0F0F0;" onmouseover="this.style.transform='translateY(-10px)'; this.style.color='#FF2E5C';" onmouseout="this.style.transform='translateY(0)'; this.style.color='#F0F0F0';" class="contact-icon">
        <div style="font-size: 3.5rem;">✉️</div>
        <span style="font-weight: 500; font-size: 1.05rem;">Email</span>
      </a>
      
      <a href="https://linkedin.com/in/your-profile" target="_blank" style="display: flex; flex-direction: column; align-items: center; gap: 1rem; text-decoration: none; transition: all 0.3s ease; padding: 2rem; color: #F0F0F0;" onmouseover="this.style.transform='translateY(-10px)'; this.style.color='#FF2E5C';" onmouseout="this.style.transform='translateY(0)'; this.style.color='#F0F0F0';" class="contact-icon">
        <div style="font-size: 3.5rem;">💼</div>
        <span style="font-weight: 500; font-size: 1.05rem;">LinkedIn</span>
      </a>
      
      <a href="https://github.com/your-profile" target="_blank" style="display: flex; flex-direction: column; align-items: center; gap: 1rem; text-decoration: none; transition: all 0.3s ease; padding: 2rem; color: #F0F0F0;" onmouseover="this.style.transform='translateY(-10px)'; this.style.color='#FF2E5C';" onmouseout="this.style.transform='translateY(0)'; this.style.color='#F0F0F0';" class="contact-icon">
        <svg width="56" height="56" viewBox="0 0 24 24" fill="currentColor" style="color: inherit;">
          <path d="M12 0c-6.626 0-12 5.373-12 12 0 5.302 3.438 9.8 8.207 11.387.599.111.793-.261.793-.577v-2.234c-3.338.726-4.033-1.416-4.033-1.416-.546-1.387-1.333-1.756-1.333-1.756-1.089-.745.083-.729.083-.729 1.205.084 1.839 1.237 1.839 1.237 1.07 1.834 2.807 1.304 3.492.997.107-.775.418-1.305.762-1.604-2.665-.305-5.467-1.334-5.467-5.931 0-1.311.469-2.381 1.236-3.221-.124-.303-.535-1.524.117-3.176 0 0 1.008-.322 3.301 1.23.957-.266 1.983-.399 3.003-.404 1.02.005 2.047.138 3.006.404 2.291-1.552 3.297-1.23 3.297-1.23.653 1.653.242 2.874.118 3.176.77.84 1.235 1.911 1.235 3.221 0 4.609-2.807 5.624-5.479 5.921.43.372.823 1.102.823 2.222v 3.293c0 .319.192.694.801.576 4.765-1.589 8.199-6.086 8.199-11.386 0-6.627-5.373-12-12-12z"/>
        </svg>
        <span style="font-weight: 500; font-size: 1.05rem;">GitHub</span>
      </a>
    </div>
  </div>
</section>
