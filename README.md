<div id="header" align="center">
  <img src="https://media.giphy.com/media/M9gbBd9nbDrOTu1Mqx/giphy.gif" width="100"/>
</div>

<div id="badges" align="center">
  <a href="https://id.linkedin.com/in/mochamad-robi-9b4615206/">
    <img src="https://img.shields.io/badge/LinkedIn-blue?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn Badge"/>
  </a>
  <a href="https://instagram.com/">
    <img src="https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white" alt="Instagram Badge"/>
  </a>
</div>

<div id="header" align="center">
  <a href="https://surisalbi.com">
    <img src="https://img.shields.io/website?url=https%3A%2F%2Fsurisalbi.com" alt="Website"/>
  </a>
  <img src="https://komarev.com/ghpvc/?username=your-github-username&style=flat-square&color=blue" alt=""/>
<h1>
  hey there
  <img src="https://media.giphy.com/media/hvRJCLFzcasrR4ia7z/giphy.gif" width="30px"/>
</h1>
</div>

<!-- Cybersecurity Animation -->
<div align="center">
  <svg width="600" height="300" viewBox="0 0 600 300" xmlns="http://www.w3.org/2000/svg">
    <defs>
      <style>
        @keyframes shieldPulse {
          0%, 100% { filter: drop-shadow(0 0 5px rgba(0, 255, 136, 0.5)); }
          50% { filter: drop-shadow(0 0 15px rgba(0, 255, 136, 1)); }
        }
        
        @keyframes lockShake {
          0%, 100% { transform: rotate(0deg); }
          25% { transform: rotate(2deg); }
          75% { transform: rotate(-2deg); }
        }
        
        @keyframes holePulse {
          0%, 100% { filter: drop-shadow(0 0 5px rgba(0, 255, 136, 0.5)); }
          50% { filter: drop-shadow(0 0 10px rgba(0, 255, 136, 1)); }
        }
        
        @keyframes nodeFloat {
          0%, 100% { 
            r: 4px;
            filter: drop-shadow(0 0 5px rgba(0, 255, 136, 0.8));
          }
          50% { 
            r: 6px;
            filter: drop-shadow(0 0 10px rgba(0, 255, 136, 1));
          }
        }
        
        @keyframes titleGlow {
          0%, 100% { filter: drop-shadow(0 0 5px rgba(0, 255, 136, 0.8)); }
          50% { filter: drop-shadow(0 0 15px rgba(0, 255, 136, 1)); }
        }
        
        @keyframes lineAnimation {
          0% { 
            stroke-dashoffset: 100;
            opacity: 0;
          }
          50% { 
            opacity: 1;
          }
          100% { 
            stroke-dashoffset: 0;
            opacity: 0;
          }
        }
        
        .shield { animation: shieldPulse 2s ease-in-out infinite; }
        .lock { animation: lockShake 0.5s ease-in-out 2s infinite; }
        .lock-hole { animation: holePulse 1s ease-in-out infinite; }
        .title { animation: titleGlow 2s ease-in-out infinite; }
        
        .node1 { animation: nodeFloat 3s ease-in-out infinite; }
        .node2 { animation: nodeFloat 3.5s ease-in-out 0.5s infinite; }
        .node3 { animation: nodeFloat 3.2s ease-in-out 1s infinite; }
        .node4 { animation: nodeFloat 3.8s ease-in-out 1.5s infinite; }
        .node5 { animation: nodeFloat 3.3s ease-in-out 2s infinite; }
        
        .line1 { animation: lineAnimation 3s ease-in-out infinite; }
        .line2 { animation: lineAnimation 3s ease-in-out 0.8s infinite; }
        .line3 { animation: lineAnimation 3s ease-in-out 1.6s infinite; }
      </style>
    </defs>
    
    <!-- Background -->
    <defs>
      <linearGradient id="bgGradient" x1="0%" y1="0%" x2="100%" y2="100%">
        <stop offset="0%" style="stop-color:#0f0c29;stop-opacity:0.9" />
        <stop offset="50%" style="stop-color:#302b63;stop-opacity:0.9" />
        <stop offset="100%" style="stop-color:#24243e;stop-opacity:0.9" />
      </linearGradient>
    </defs>
    
    <rect width="600" height="300" fill="url(#bgGradient)"/>
    <rect width="600" height="300" fill="rgba(0,0,0,0.3)"/>
    
    <!-- Border -->
    <rect x="50" y="20" width="500" height="260" fill="none" stroke="#00ff88" stroke-width="2" rx="5" opacity="0.6"/>
    
    <!-- Network Nodes -->
    <circle class="node1" cx="100" cy="60" r="4" fill="#00ff88"/>
    <circle class="node2" cx="480" cy="240" r="4" fill="#00ff88"/>
    <circle class="node3" cx="520" cy="150" r="4" fill="#00ff88"/>
    <circle class="node4" cx="440" cy="90" r="4" fill="#00ff88"/>
    <circle class="node5" cx="120" cy="220" r="4" fill="#00ff88"/>
    
    <!-- Connection Lines -->
    <line class="line1" x1="100" y1="60" x2="300" y2="150" stroke="#00ff88" stroke-width="2" opacity="0.6" stroke-dasharray="100"/>
    <line class="line2" x1="480" y1="240" x2="300" y2="150" stroke="#00ff88" stroke-width="2" opacity="0.6" stroke-dasharray="100"/>
    <line class="line3" x1="520" y1="150" x2="300" y2="150" stroke="#00ff88" stroke-width="2" opacity="0.6" stroke-dasharray="100"/>
    
    <!-- Central Shield -->
    <g transform="translate(300, 110)">
      <!-- Shield body -->
      <path class="shield" 
            d="M -40,-30 L 40,-30 L 40,20 Q 0,60 -40,20 Z" 
            fill="rgba(0,255,136,0.1)" 
            stroke="#00ff88" 
            stroke-width="2"/>
      
      <!-- Lock group -->
      <g class="lock" transform="translate(0, 5)">
        <!-- Lock shackle -->
        <path d="M -8,-8 Q -8,-18 0,-18 Q 8,-18 8,-8" 
              fill="none" 
              stroke="#00ff88" 
              stroke-width="2" 
              stroke-linecap="round"/>
        
        <!-- Lock body -->
        <rect x="-12" y="0" width="24" height="16" 
              fill="none" 
              stroke="#00ff88" 
              stroke-width="2" 
              rx="2"/>
        
        <!-- Lock hole -->
        <circle class="lock-hole" cx="0" cy="8" r="2" fill="#00ff88"/>
      </g>
    </g>
    
    <!-- Title Text -->
    <text class="title" x="300" y="240" font-size="24" font-weight="bold" fill="#00ff88" text-anchor="middle" letter-spacing="3">
      SECURE
    </text>
    
    <!-- Subtitle -->
    <text x="300" y="265" font-size="12" fill="#00ff88" text-anchor="middle" opacity="0.8" font-style="italic">
      Cybersecurity First
    </text>
    
    <!-- Code text -->
    <text x="300" y="285" font-size="10" fill="#00ff88" text-anchor="middle" font-family="monospace">
      $ security.enabled = true
    </text>
  </svg>
</div>

<div align="center">
  <img src="https://media.giphy.com/media/dWesBcTLavkZuG35MI/giphy.gif" width="600" height="300"/>
</div>

### :woman_technologist: About Me :

I am a Full Stack Developer or Backend Developer from Serang, Banten, Indonesian.
- I am a Software Engineer who develops systems and applications on both the back-end and front-end sides.
- I have more than 4 years of experience in software development, including websites, information systems, mobile applications, and desktop applications.
- I strongly uphold commitment, integrity, and professional work ethics.
- In my spare time, I make time to learn and explore new technologies.

<br>

### :hammer_and_wrench: Languages and Tools :
<div>
  <h4>Backend</h4>
  <img src="https://github.com/devicons/devicon/blob/master/icons/php/php-original.svg" title="PHP" alt="PHP" width="40" height="40"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/laravel/laravel-original-wordmark.svg" title="Laravel" alt="Laravel" width="40" height="40"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/codeigniter/codeigniter-plain-wordmark.svg" title="Codeigniter" alt="Codeigniter" width="40" height="40"/>&nbsp;
  <h4>Frontend</h4>
  <img src="https://github.com/devicons/devicon/blob/master/icons/react/react-original-wordmark.svg" title="React" alt="React" width="40" height="40"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/tailwindcss/tailwindcss-original.svg" title="Tailwind" alt="Tailwind" width="40" height="40"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/bootstrap/bootstrap-original.svg" title="Bootstrap" alt="Bootstrap" width="40" height="40"/>&nbsp;
  <h4>Mobile</h4>
  <img src="https://github.com/devicons/devicon/blob/master/icons/reactnative/reactnative-original-wordmark.svg" title="React Native" alt="React Native" width="40" height="40"/>&nbsp;
  <h4>Database</h4>
  <img src="https://github.com/devicons/devicon/blob/master/icons/mysql/mysql-original-wordmark.svg" title="MySQL"  alt="MySQL" width="40" height="40"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/postgresql/postgresql-original-wordmark.svg" title="PostgreSql" **alt="PostgreSql" width="40" height="40"/>
  <h4>Version Control</h4>
  <img src="https://github.com/devicons/devicon/blob/master/icons/github/github-original-wordmark.svg" title="GitHub" **alt="GitHub" width="40" height="40"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/gitlab/gitlab-plain-wordmark.svg" title="GitLab" **alt="GitLab" width="40" height="40"/>&nbsp;
  <h4>More Tools</h4>
  <img src="https://github.com/devicons/devicon/blob/master/icons/linux/linux-original.svg" title="Linux" **alt="Linux" width="40" height="40"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/googlecloud/googlecloud-original.svg" title="GCP" **alt="GCP" width="40" height="40"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/docker/docker-original.svg" title="Docker" **alt="Docker" width="40" height="40"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/grafana/grafana-original.svg" title="Grafana" **alt="Grafana" width="40" height="40"/>&nbsp;
</div>

<br>
