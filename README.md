<div align="center">
  <!-- ANIMATED NEON FRAME -->
  <svg width="900" height="60" viewBox="0 0 900 60" style="margin-bottom: 10px;">
    <defs>
      <linearGradient id="neonGlow" x1="0%" y1="0%" x2="100%" y2="0%">
        <stop offset="0%" style="stop-color:#58A6FF;stop-opacity:0" />
        <stop offset="50%" style="stop-color:#58A6FF;stop-opacity:1" />
        <stop offset="100%" style="stop-color:#58A6FF;stop-opacity:0" />
      </linearGradient>
      <filter id="glow">
        <feGaussianBlur stdDeviation="3" result="coloredBlur"/>
        <feMerge>
          <feMergeNode in="coloredBlur"/>
          <feMergeNode in="SourceGraphic"/>
        </feMerge>
      </filter>
    </defs>
    
    <!-- Animated pulse line -->
    <line x1="0" y1="30" x2="900" y2="30" stroke="url(#neonGlow)" stroke-width="2" filter="url(#glow)">
      <animate attributeName="x1" values="0;900;0" dur="4s" repeatCount="indefinite" />
      <animate attributeName="x2" values="900;0;900" dur="4s" repeatCount="indefinite" />
    </line>
  </svg>
</div>

<!-- Add this CSS for pulsing badges -->
<style>
  /* Make all your badges pulse gently */
  img[src*="img.shields.io"] {
    animation: badgePulse 3s ease-in-out infinite;
    transition: all 0.3s;
  }
  img[src*="img.shields.io"]:hover {
    transform: scale(1.1);
    filter: drop-shadow(0 0 8px #58A6FF);
  }
  @keyframes badgePulse {
    0%, 100% { opacity: 0.85; }
    50% { opacity: 1; filter: drop-shadow(0 0 4px #58A6FF); }
  }
  
  /* Terminal block glow */
  pre, .terminal-box {
    animation: terminalGlow 4s ease-in-out infinite;
    border-left: 2px solid #58A6FF;
  }
  @keyframes terminalGlow {
    0%, 100% { box-shadow: 0 0 0px #58A6FF; }
    50% { box-shadow: 0 0 20px rgba(88, 166, 255, 0.15); }
  }
</style>
