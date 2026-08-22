<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1200 340" width="1200" height="340" role="img" aria-label="Suraj Singh - Software Engineer, full-stack MERN and Next.js">
  <title>Suraj Singh — Software Engineer</title>

  <defs>
    <linearGradient id="base" x1="0" y1="0" x2="1" y2="1">
      <stop offset="0%" stop-color="#0a0e1a"/>
      <stop offset="48%" stop-color="#141b31"/>
      <stop offset="100%" stop-color="#0a0e1a"/>
    </linearGradient>

    <radialGradient id="blobA"><stop offset="0%" stop-color="#7c3aed" stop-opacity=".95"/><stop offset="100%" stop-color="#7c3aed" stop-opacity="0"/></radialGradient>
    <radialGradient id="blobB"><stop offset="0%" stop-color="#22d3ee" stop-opacity=".9"/><stop offset="100%" stop-color="#22d3ee" stop-opacity="0"/></radialGradient>
    <radialGradient id="blobC"><stop offset="0%" stop-color="#f472b6" stop-opacity=".8"/><stop offset="100%" stop-color="#f472b6" stop-opacity="0"/></radialGradient>

    <linearGradient id="shine" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%"   stop-color="#22d3ee"/>
      <stop offset="30%"  stop-color="#a78bfa"/>
      <stop offset="60%"  stop-color="#f472b6"/>
      <stop offset="85%"  stop-color="#facc15"/>
      <stop offset="100%" stop-color="#22d3ee"/>
      <animateTransform attributeName="gradientTransform" type="translate"
                        values="-1 0; 0 0; -1 0" dur="9s" repeatCount="indefinite"/>
    </linearGradient>

    <linearGradient id="rule" x1="0" y1="0" x2="1" y2="0">
      <stop offset="0%" stop-color="#22d3ee" stop-opacity="0"/>
      <stop offset="25%" stop-color="#22d3ee"/>
      <stop offset="55%" stop-color="#a78bfa"/>
      <stop offset="80%" stop-color="#f472b6"/>
      <stop offset="100%" stop-color="#f472b6" stop-opacity="0"/>
    </linearGradient>

    <filter id="soften" x="-60%" y="-60%" width="220%" height="220%">
      <feGaussianBlur stdDeviation="58"/>
    </filter>

    <filter id="glow" x="-40%" y="-40%" width="180%" height="180%">
      <feGaussianBlur stdDeviation="7" result="b"/>
      <feMerge><feMergeNode in="b"/><feMergeNode in="SourceGraphic"/></feMerge>
    </filter>

    <pattern id="grid" width="42" height="42" patternUnits="userSpaceOnUse">
      <path d="M42 0H0V42" fill="none" stroke="#ffffff" stroke-opacity=".05" stroke-width="1"/>
    </pattern>

    <clipPath id="frame"><rect width="1200" height="340" rx="18"/></clipPath>
  </defs>

  <g clip-path="url(#frame)">
    <rect width="1200" height="340" fill="url(#base)"/>
    <rect width="1200" height="340" fill="url(#grid)"/>

    <g filter="url(#soften)">
      <circle r="180" fill="url(#blobA)">
        <animate attributeName="cx" values="220;400;180;220" dur="17s" repeatCount="indefinite"/>
        <animate attributeName="cy" values="90;250;140;90"  dur="21s" repeatCount="indefinite"/>
      </circle>
      <circle r="160" fill="url(#blobB)">
        <animate attributeName="cx" values="980;760;1040;980" dur="19s" repeatCount="indefinite"/>
        <animate attributeName="cy" values="250;80;200;250"   dur="15s" repeatCount="indefinite"/>
      </circle>
      <circle r="140" fill="url(#blobC)">
        <animate attributeName="cx" values="640;900;520;640" dur="23s" repeatCount="indefinite"/>
        <animate attributeName="cy" values="300;60;280;300"  dur="18s" repeatCount="indefinite"/>
      </circle>
    </g>

    <g fill="#ffffff">
      <circle cx="120"  cy="300" r="1.8" opacity=".7"><animate attributeName="cy" values="330;-10" dur="11s" repeatCount="indefinite"/><animate attributeName="opacity" values="0;.8;0" dur="11s" repeatCount="indefinite"/></circle>
      <circle cx="330"  cy="300" r="1.4" opacity=".6"><animate attributeName="cy" values="350;-10" dur="14s" begin="1.5s" repeatCount="indefinite"/><animate attributeName="opacity" values="0;.7;0" dur="14s" begin="1.5s" repeatCount="indefinite"/></circle>
      <circle cx="560"  cy="300" r="2.1" opacity=".5"><animate attributeName="cy" values="340;-10" dur="12s" begin="3s" repeatCount="indefinite"/><animate attributeName="opacity" values="0;.6;0" dur="12s" begin="3s" repeatCount="indefinite"/></circle>
      <circle cx="800"  cy="300" r="1.6" opacity=".7"><animate attributeName="cy" values="360;-10" dur="16s" begin="0.8s" repeatCount="indefinite"/><animate attributeName="opacity" values="0;.75;0" dur="16s" begin="0.8s" repeatCount="indefinite"/></circle>
      <circle cx="1010" cy="300" r="1.3" opacity=".6"><animate attributeName="cy" values="330;-10" dur="13s" begin="2.2s" repeatCount="indefinite"/><animate attributeName="opacity" values="0;.7;0" dur="13s" begin="2.2s" repeatCount="indefinite"/></circle>
      <circle cx="1130" cy="300" r="1.9" opacity=".5"><animate attributeName="cy" values="345;-10" dur="15s" begin="4s" repeatCount="indefinite"/><animate attributeName="opacity" values="0;.6;0" dur="15s" begin="4s" repeatCount="indefinite"/></circle>
    </g>

    <g stroke="#22d3ee" stroke-opacity=".55" stroke-width="2" fill="none">
      <path d="M34 74V40h34"/><path d="M1166 266v34h-34"/>
    </g>

    <g font-family="'Segoe UI', Ubuntu, 'Helvetica Neue', Helvetica, Arial, sans-serif" text-anchor="middle">
      <text x="600" y="96" font-size="15" letter-spacing="7.5" fill="#8b96b8" font-weight="500">
        SOFTWARE ENGINEER
        <animate attributeName="opacity" values="0;1" dur="1.1s" fill="freeze"/>
      </text>

      <text x="600" y="182" font-size="82" font-weight="700" letter-spacing="3" fill="url(#shine)" filter="url(#glow)">
        SURAJ SINGH
        <animate attributeName="opacity" values="0;1" dur="1.3s" begin="0.2s" fill="freeze"/>
      </text>

      <path d="M330 214H870" stroke="url(#rule)" stroke-width="2.5" stroke-linecap="round"
            stroke-dasharray="540" stroke-dashoffset="540">
        <animate attributeName="stroke-dashoffset" from="540" to="0" dur="1.4s" begin="0.6s" fill="freeze"/>
      </path>

      <text x="600" y="254" font-size="19" letter-spacing="2.6" fill="#c7d0ea" font-weight="500">
        Full-stack &#183; MERN &#183; Next.js &#183; Node &#183; MongoDB
        <animate attributeName="opacity" values="0;1" dur="1.2s" begin="0.9s" fill="freeze"/>
      </text>

      <g>
        <animate attributeName="opacity" values="0;1" dur="1.2s" begin="1.2s" fill="freeze"/>
        <rect x="470" y="278" width="260" height="34" rx="17" fill="#ffffff" fill-opacity=".06" stroke="#22d3ee" stroke-opacity=".35"/>
        <circle cx="497" cy="295" r="4.5" fill="#4ade80">
          <animate attributeName="opacity" values="1;.25;1" dur="2s" repeatCount="indefinite"/>
        </circle>
        <text x="609" y="301" font-size="14" letter-spacing="1.2" fill="#dbe4ff">Open to remote work</text>
      </g>
    </g>
  </g>
</svg>
