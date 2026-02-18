<div align="center">

<!-- Animated Gradient Background -->
<div style="position: fixed; top: 0; left: 0; width: 100%; height: 100%; z-index: -1; background: linear-gradient(-45deg, #0a0a0a, #1a1a2e, #16213e, #0f3460, #1a1a2e); background-size: 400% 400%; animation: gradientBG 15s ease infinite;">
</div>

<style>
@keyframes gradientBG {
  0% { background-position: 0% 50%; }
  50% { background-position: 100% 50%; }
  100% { background-position: 0% 50%; }
}
@keyframes float {
  0%, 100% { transform: translateY(0px); }
  50% { transform: translateY(-10px); }
}
@keyframes glow {
  0%, 100% { box-shadow: 0 0 20px rgba(97, 218, 251, 0.3); }
  50% { box-shadow: 0 0 40px rgba(97, 218, 251, 0.6); }
}
@keyframes typing {
  from { width: 0; }
  to { width: 100%; }
}
@keyframes blink {
  50% { border-color: transparent; }
}
.glass-card {
  background: rgba(255, 255, 255, 0.05);
  backdrop-filter: blur(10px);
  border: 1px solid rgba(255, 255, 255, 0.1);
  border-radius: 16px;
  padding: 24px;
  margin: 16px;
  transition: all 0.3s ease;
}
.glass-card:hover {
  background: rgba(255, 255, 255, 0.1);
  border: 1px solid rgba(97, 218, 251, 0.3);
  transform: translateY(-5px);
}
.terminal {
  background: rgba(10, 10, 10, 0.9);
  border-radius: 12px;
  padding: 20px;
  font-family: 'Fira Code', 'JetBrains Mono', monospace;
  max-width: 600px;
  border: 1px solid #30363d;
  box-shadow: 0 20px 50px rgba(0, 0, 0, 0.5);
}
.terminal-header {
  display: flex;
  gap: 8px;
  margin-bottom: 16px;
}
.terminal-dot {
  width: 12px;
  height: 12px;
  border-radius: 50%;
}
.terminal-dot.red { background: #ff5f56; }
.terminal-dot.yellow { background: #ffbd2e; }
.terminal-dot.green { background: #27c93f; }
.terminal-line {
  color: #c9d1d9;
  margin: 4px 0;
  font-size: 14px;
}
.prompt { color: #79c0ff; }
.path { color: #d2a8ff; }
.output { color: #56d364; }
.comment { color: #8b949e; }
.keyword { color: #ff7b72; }
.string { color: #a5d6ff; }
.variable { color: #ffa657; }
</style>

<!-- Profile Header with Glow Effect -->
<div style="padding: 40px 20px;">

<!-- Animated Avatar with Glow -->
<div style="animation: float 3s ease-in-out infinite;">
  <img src="https://avatars.githubusercontent.com/u/your-uid?v=4" 
       style="width: 150px; height: 150px; border-radius: 50%; border: 4px solid transparent; 
              background: linear-gradient(45deg, #61dafb, #b061ff, #ff6181, #61dafb) border-box;
              background-clip: padding-box, border-box; animation: glow 2s ease-in-out infinite alternate;
              box-shadow: 0 0 30px rgba(97, 218, 251, 0.4);" 
       alt="avatar" />
</div>

<!-- Typing Animation Header -->
<div style="margin-top: 30px;">
  <h1 style="font-size: 2.5em; margin: 0; background: linear-gradient(90deg, #61dafb, #b061ff, #ff6181);
             -webkit-background-clip: text; -webkit-text-fill-color: transparent; 
             background-clip: text; font-weight: 800;">
    <span class="txt-rotate" data-period="2000" 
          data-rotate='["Hi there, I'm Andy", "Full Stack Developer", "Open Source Enthusiast", "andys-code Creator"]'>
    </span>
  </h1>
  <p style="color: #8b949e; font-size: 1.2em; margin-top: 10px;">
    <span style="color: #56d364;">✦</span> Building the future, one commit at a time <span style="color: #56d364;">✦</span>
  </p>
  <!-- andy-code Badge -->
  <div style="margin-top: 20px;">
    <a href="https://github.com/andysama/andys-code">
      <img src="https://img.shields.io/badge/andys_code-v1.0-61dafb?style=for-the-badge&logo=github&logoColor=white" 
           alt="andys-code" />
    </a>
    <p style="color: #8b949e; font-size: 0.9em; margin-top: 8px; max-width: 500px;">
      🤖 My AI coding assistant — Full Stack + DevOps + Design Intelligence
    </p>
  </div>
</div>

<!-- Wave Divider -->
<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&height=100&section=header" 
     style="margin-top: 20px; max-width: 100%;" alt="wave" />

</div>

</div>

<br/>

<!-- Terminal Section -->
<div align="center">
<div class="terminal">
  <div class="terminal-header">
    <div class="terminal-dot red"></div>
    <div class="terminal-dot yellow"></div>
    <div class="terminal-dot green"></div>
  </div>
  <div class="terminal-line"><span class="prompt">➜</span> <span class="path">~</span> whoami</div>
  <div class="terminal-line output">Andy — Full Stack Developer & Open Source Enthusiast</div>
  <div class="terminal-line" style="margin-top: 12px;"><span class="prompt">➜</span> <span class="path">~</span> cat skills.txt</div>
  <div class="terminal-line output">["Vue.js" "React" "TypeScript" "Rust" "Go" "Python" "GenAI" "Node.js"]</div>
  <div class="terminal-line" style="margin-top: 12px;"><span class="prompt">➜</span> <span class="path">~</span> echo $MOTTO</div>
  <div class="terminal-line output">"Code is poetry, and I'm still learning the verses."</div>
  <div class="terminal-line comment" style="margin-top: 12px;"># Currently exploring: Rust, WebAssembly, and AI/ML</div>
</div>
</div>

<br/><br/>

<!-- Tech Stack Section - Glass Cards -->
<div align="center">
<h2 style="color: #fff; font-size: 1.8em; margin-bottom: 30px;">
  <span style="color: #61dafb;">❖</span> Tech Arsenal <span style="color: #61dafb;">❖</span>
</h2>

<div style="display: flex; flex-wrap: wrap; justify-content: center; gap: 16px; max-width: 900px;">
  
  <!-- Frontend Card -->
  <div class="glass-card" style="flex: 1 1 280px; max-width: 400px;">
    <h3 style="color: #61dafb; margin: 0 0 16px 0; font-size: 1.1em;">🎨 Frontend</h3>
    <a href="https://skillicons.dev"><img src="https://skillicons.dev/icons?i=vue,react,nextjs,ts" /></a><br/>
    <a href="https://skillicons.dev"><img src="https://skillicons.dev/icons?i=html,css,sass,tailwind" style="margin-top: 8px;"/></a>
  </div>

  <!-- Backend Card -->
  <div class="glass-card" style="flex: 1 1 280px; max-width: 400px;">
    <h3 style="color: #b061ff; margin: 0 0 16px 0; font-size: 1.1em;">⚡ Backend</h3>
    <a href="https://skillicons.dev"><img src="https://skillicons.dev/icons?i=nodejs,express,nestjs,go,rust" /></a><br/>
    <a href="https://skillicons.dev"><img src="https://skillicons.dev/icons?i=graphql,postgres,mongodb,redis" style="margin-top: 8px;"/></a>
  </div>

  <!-- DevOps & Tools Card -->
  <div class="glass-card" style="flex: 1 1 280px; max-width: 400px;">
    <h3 style="color: #ff6181; margin: 0 0 16px 0; font-size: 1.1em;">🛠️ DevOps & Tools</h3>
    <a href="https://skillicons.dev"><img src="https://skillicons.dev/icons?i=git,docker,k8s,aws" /></a><br/>
    <a href="https://skillicons.dev"><img src="https://skillicons.dev/icons?i=linux,nginx,firebase" style="margin-top: 8px;"/></a>
  </div>

</div>
</div>

<br/><br/>

<!-- Stats Section -->
<div align="center">
<h2 style="color: #fff; font-size: 1.8em; margin-bottom: 30px;">
  <span style="color: #56d364;">📊</span> GitHub Analytics
</h2>

<table>
  <tr>
    <td>
      <img src="https://github-readme-stats.vercel.app/api?username=andysama&show_icons=true&theme=tokyonight&hide_border=true&bg_color=0d1117&count_private=true" 
           height="180" alt="stats" />
    </td>
    <td>
      <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=andysama&layout=compact&theme=tokyonight&hide_border=true&bg_color=0d1117&langs_count=8" 
           height="180" alt="languages" />
    </td>
  </tr>
</table>

<img src="https://github-readme-streak-stats.herokuapp.com/?user=andysama&theme=tokyonight&hide_border=true&background=0d1117" 
     alt="streak" style="margin-top: 16px;" />

</div>

<br/><br/>

<!-- Trophies Section -->
<div align="center">
<h2 style="color: #fff; font-size: 1.8em; margin-bottom: 20px;">
  <span style="color: #ffd700;">🏆</span> Achievements
</h2>
<a href="https://github.com/ryo-ma/github-profile-trophy">
  <img src="https://github-profile-trophy.vercel.app/?username=andysama&theme=gitdimmed&no-frame=true&no-bg=true&margin-w=4" 
       alt="trophies" />
</a>
</div>

<br/><br/>

<!-- Contribution Section -->
<div align="center">
<h2 style="color: #fff; font-size: 1.8em; margin-bottom: 20px;">
  <span style="color: #a5d6ff;">🧩</span> Contribution Activity
</h2>

<!-- 3D Contribution Graph -->
<a href="https://github.com/andysama/andysama">
  <img src="profile-3d-contrib/profile-night-rainbow.svg" alt="3D Contribution" width="800" />
</a>

<br/><br/>

<!-- Snake Animation -->
<a href="https://github.com/andysama/andysama/blob/output/github-contribution-grid-snake.svg">
  <img src="https://github.com/andysama/andysama/blob/output/github-contribution-grid-snake.svg?raw=true" 
       alt="snake" />
</a>
</div>

<br/><br/>

<!-- Social Links -->
<div align="center">
<h2 style="color: #fff; font-size: 1.8em; margin-bottom: 30px;">
  <span style="color: #79c0ff;">🔗</span> Let's Connect
</h2>

<div style="display: flex; flex-wrap: wrap; justify-content: center; gap: 16px;">
  
  <a href="https://github.com/andysama" style="text-decoration: none;">
    <div class="glass-card" style="padding: 12px 24px; display: flex; align-items: center; gap: 8px;">
      <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" />
    </div>
  </a>
  
  <a href="https://twitter.com/andysama" style="text-decoration: none;">
    <div class="glass-card" style="padding: 12px 24px; display: flex; align-items: center; gap: 8px;">
      <img src="https://img.shields.io/badge/Twitter-1DA1F2?style=for-the-badge&logo=twitter&logoColor=white" alt="Twitter" />
    </div>
  </a>
  
  <a href="https://linkedin.com/in/andysama" style="text-decoration: none;">
    <div class="glass-card" style="padding: 12px 24px; display: flex; align-items: center; gap: 8px;">
      <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
    </div>
  </a>
  
  <a href="mailto:your.email@example.com" style="text-decoration: none;">
    <div class="glass-card" style="padding: 12px 24px; display: flex; align-items: center; gap: 8px;">
      <img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" />
    </div>
  </a>

</div>
</div>

<br/><br/>

<!-- Footer Wave -->
<div align="center">
<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&height=100&section=footer" 
     style="max-width: 100%;" alt="footer wave" />

<div style="color: #8b949e; margin-top: 20px; font-size: 0.9em;">
  <p>⭐ From <a href="https://github.com/andysama" style="color: #61dafb;">andysama</a> with <span style="color: #ff6181;">♥</span></p>
  <p>Last updated: <span id="last-updated"></span></p>
</div>

<script>
document.getElementById('last-updated').textContent = new Date().toLocaleDateString('en-US', { 
  year: 'numeric', month: 'long', day: 'numeric' 
});
</script>
</div>

<!-- Typing Animation Script -->
<script>
class TextRotate {
  constructor(el, toRotate, period) {
    this.toRotate = toRotate;
    this.el = el;
    this.loopNum = 0;
    this.period = parseInt(period, 10) || 2000;
    this.txt = '';
    this.tick();
    this.isDeleting = false;
  }
  tick() {
    const i = this.loopNum % this.toRotate.length;
    const fullTxt = this.toRotate[i];
    
    if (this.isDeleting) {
      this.txt = fullTxt.substring(0, this.txt.length - 1);
    } else {
      this.txt = fullTxt.substring(0, this.txt.length + 1);
    }
    
    this.el.innerHTML = '<span class="wrap">'+this.txt+'</span>';
    
    let delta = 100 - Math.random() * 100;
    if (this.isDeleting) delta /= 2;
    
    if (!this.isDeleting && this.txt === fullTxt) {
      delta = this.period;
      this.isDeleting = true;
    } else if (this.isDeleting && this.txt === '') {
      this.isDeleting = false;
      this.loopNum++;
      delta = 500;
    }
    
    setTimeout(() => this.tick(), delta);
  }
}

document.addEventListener('DOMContentLoaded', () => {
  const elements = document.getElementsByClassName('txt-rotate');
  for (let i = 0; i < elements.length; i++) {
    const toRotate = elements[i].getAttribute('data-rotate');
    const period = elements[i].getAttribute('data-period');
    if (toRotate) {
      new TextRotate(elements[i], JSON.parse(toRotate), period);
    }
  }
});
</script>

