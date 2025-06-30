---
layout: default
title: Siva's Portfolio & Tools
---

<div class="profile-header">
  <div class="profile-avatar">
    <img src="https://github.com/siva4it.png" alt="Siva's Profile" class="avatar">
  </div>
  <div class="profile-info">
    <h1>👋 Hi, I'm Siva</h1>
    <p class="tagline">Full-Stack Developer | Open Source Enthusiast | Problem Solver</p>
    <div class="social-links">
      <a href="https://github.com/siva4it" target="_blank" class="social-link">
        <i class="fab fa-github"></i> GitHub
      </a>
      <a href="https://www.linkedin.com/in/sivanandan-ac/" target="_blank" class="social-link">
        <i class="fab fa-linkedin"></i> LinkedIn
      </a>
      <a href="mailto:sivanandan.ac@gmail.com" class="social-link">
        <i class="fas fa-envelope"></i> Email
      </a>
    </div>
  </div>
</div>

## 🚀 About Me

I'm a passionate developer who loves building useful tools and solving complex problems. My expertise spans across full-stack development, with a focus on creating practical solutions that make a difference.

### 🛠️ Skills & Technologies
- **Frontend**: React, Vue.js, HTML5, CSS3, JavaScript/TypeScript
- **Backend**: Node.js, Python, Java, .NET
- **Databases**: PostgreSQL, MongoDB, MySQL
- **DevOps**: Docker, AWS, CI/CD, GitHub Actions
- **Tools**: Git, VS Code, Postman, Figma

## 🛠️ My Tools & Projects

Here are some of the tools and projects I'm developing. Each one is designed to solve specific problems and make development easier:

### 🔧 Development Tools
<div class="tools-grid">
  <div class="tool-card">
    <h3>🔄 Code Generator</h3>
    <p>Automated code generation tool for common development patterns</p>
    <a href="#" class="tool-link">Coming Soon</a>
  </div>
  
  <div class="tool-card">
    <h3>📊 Data Visualizer</h3>
    <p>Interactive data visualization and analytics dashboard</p>
    <a href="#" class="tool-link">Coming Soon</a>
  </div>
  
  <div class="tool-card">
    <h3>🔍 API Tester</h3>
    <p>Advanced API testing and documentation tool</p>
    <a href="#" class="tool-link">Coming Soon</a>
  </div>
  
  <div class="tool-card">
    <h3>⚡ Performance Monitor</h3>
    <p>Real-time application performance monitoring</p>
    <a href="#" class="tool-link">Coming Soon</a>
  </div>
</div>

### 📚 Learning Resources
<div class="tools-grid">
  <div class="tool-card">
    <h3>📖 Dev Cheat Sheets</h3>
    <p>Quick reference guides for popular technologies</p>
    <a href="#" class="tool-link">Coming Soon</a>
  </div>
  
  <div class="tool-card">
    <h3>🎯 Project Templates</h3>
    <p>Starter templates for various frameworks and use cases</p>
    <a href="#" class="tool-link">Coming Soon</a>
  </div>
</div>

## 🎯 What I'm Working On

I'm currently focused on developing tools that help developers be more productive and efficient. Each tool is designed with the following principles:

- **Simplicity**: Easy to use and understand
- **Efficiency**: Saves time and reduces repetitive tasks
- **Reliability**: Well-tested and maintained
- **Open Source**: Available for the community to use and contribute

## 🤝 Get In Touch

I'm always interested in collaborating on interesting projects or discussing new ideas. Feel free to reach out!

- 📧 **Email**: sivanandan.ac@gmail.com
- 💼 **LinkedIn**: [sivanandan-ac](https://www.linkedin.com/in/sivanandan-ac/)
- 🐙 **GitHub**: [siva4it](https://github.com/siva4it)

---

<div class="footer">
  <p>Built with ❤️ using GitHub Pages | Last updated: {{ site.time | date: "%B %d, %Y" }}</p>
</div>

<style>
.profile-header {
  display: flex;
  align-items: center;
  gap: 2rem;
  margin-bottom: 3rem;
  padding: 2rem;
  background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
  border-radius: 15px;
  color: white;
}

.profile-avatar .avatar {
  width: 120px;
  height: 120px;
  border-radius: 50%;
  border: 4px solid white;
  box-shadow: 0 4px 15px rgba(0,0,0,0.2);
}

.profile-info h1 {
  margin: 0 0 0.5rem 0;
  font-size: 2.5rem;
  font-weight: 700;
}

.tagline {
  font-size: 1.2rem;
  margin: 0 0 1rem 0;
  opacity: 0.9;
}

.social-links {
  display: flex;
  gap: 1rem;
  flex-wrap: wrap;
}

.social-link {
  display: inline-flex;
  align-items: center;
  gap: 0.5rem;
  padding: 0.5rem 1rem;
  background: rgba(255,255,255,0.2);
  border-radius: 25px;
  color: white;
  text-decoration: none;
  transition: all 0.3s ease;
}

.social-link:hover {
  background: rgba(255,255,255,0.3);
  transform: translateY(-2px);
  color: white;
  text-decoration: none;
}

.tools-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
  gap: 1.5rem;
  margin: 2rem 0;
}

.tool-card {
  background: white;
  border: 1px solid #e1e4e8;
  border-radius: 10px;
  padding: 1.5rem;
  transition: all 0.3s ease;
  box-shadow: 0 2px 8px rgba(0,0,0,0.1);
}

.tool-card:hover {
  transform: translateY(-5px);
  box-shadow: 0 8px 25px rgba(0,0,0,0.15);
  border-color: #0366d6;
}

.tool-card h3 {
  margin: 0 0 1rem 0;
  color: #24292e;
  font-size: 1.3rem;
}

.tool-card p {
  margin: 0 0 1rem 0;
  color: #586069;
  line-height: 1.6;
}

.tool-link {
  display: inline-block;
  padding: 0.5rem 1rem;
  background: #0366d6;
  color: white;
  text-decoration: none;
  border-radius: 6px;
  font-weight: 500;
  transition: background 0.3s ease;
}

.tool-link:hover {
  background: #0256cc;
  color: white;
  text-decoration: none;
}

.footer {
  text-align: center;
  margin-top: 3rem;
  padding: 2rem;
  border-top: 1px solid #e1e4e8;
  color: #586069;
}

@media (max-width: 768px) {
  .profile-header {
    flex-direction: column;
    text-align: center;
  }
  
  .profile-info h1 {
    font-size: 2rem;
  }
  
  .tools-grid {
    grid-template-columns: 1fr;
  }
}
</style>
