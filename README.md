<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 400 400" width="400" height="400">
  <defs>
    <radialGradient id="bgGrad" cx="50%" cy="50%" r="50%">
      <stop offset="0%" stop-color="#302b63"/>
      <stop offset="60%" stop-color="#1a1742"/>
      <stop offset="100%" stop-color="#0f0c29"/>
    </radialGradient>
    <radialGradient id="coreGlow" cx="50%" cy="50%" r="50%">
      <stop offset="0%" stop-color="#a78bfa"/>
      <stop offset="40%" stop-color="#7c3aed"/>
      <stop offset="100%" stop-color="#4c1d95"/>
    </radialGradient>
    <radialGradient id="ringGlow" cx="50%" cy="50%" r="50%">
      <stop offset="0%" stop-color="#c4b5fd" stop-opacity="0.9"/>
      <stop offset="100%" stop-color="#7c3aed" stop-opacity="0.3"/>
    </radialGradient>
    <filter id="glow">
      <feGaussianBlur stdDeviation="3" result="coloredBlur"/>
      <feMerge>
        <feMergeNode in="coloredBlur"/>
        <feMergeNode in="SourceGraphic"/>
      </feMerge>
    </filter>
    <filter id="softGlow">
      <feGaussianBlur stdDeviation="6" result="coloredBlur"/>
      <feMerge>
        <feMergeNode in="coloredBlur"/>
        <feMergeNode in="SourceGraphic"/>
      </feMerge>
    </filter>
  </defs>

  <!-- Background circle -->
  <circle cx="200" cy="200" r="196" fill="url(#bgGrad)" stroke="#4c1d95" stroke-width="1.5"/>

  <!-- Outer orbit ring -->
  <ellipse cx="200" cy="200" rx="155" ry="155" fill="none" stroke="#6d28d9" stroke-width="0.8" stroke-dasharray="4 6" opacity="0.5"/>

  <!-- Mid orbit ring -->
  <ellipse cx="200" cy="200" rx="115" ry="115" fill="none" stroke="#7c3aed" stroke-width="0.6" stroke-dasharray="3 8" opacity="0.4"/>

  <!-- Electron orbit path 1 (tilted) -->
  <ellipse cx="200" cy="200" rx="90" ry="35" fill="none" stroke="#a78bfa" stroke-width="1.2" opacity="0.7" transform="rotate(-30 200 200)" filter="url(#glow)"/>

  <!-- Electron orbit path 2 (tilted other way) -->
  <ellipse cx="200" cy="200" rx="90" ry="35" fill="none" stroke="#a78bfa" stroke-width="1.2" opacity="0.7" transform="rotate(30 200 200)" filter="url(#glow)"/>

  <!-- Electron orbit path 3 (horizontal) -->
  <ellipse cx="200" cy="200" rx="90" ry="35" fill="none" stroke="#c4b5fd" stroke-width="1" opacity="0.5"/>

  <!-- Electrons on orbits -->
  <circle cx="290" cy="200" r="5" fill="#c4b5fd" filter="url(#glow)"/>
  <circle cx="155" cy="157" r="4" fill="#e879f9" filter="url(#glow)"/>
  <circle cx="248" cy="243" r="3.5" fill="#818cf8" filter="url(#glow)"/>

  <!-- Core atom nucleus -->
  <circle cx="200" cy="200" r="28" fill="url(#coreGlow)" filter="url(#softGlow)"/>
  <circle cx="200" cy="200" r="20" fill="#7c3aed" opacity="0.9"/>

  <!-- Stars scattered around -->
  <circle cx="60" cy="70" r="1.5" fill="white" opacity="0.8"/>
  <circle cx="340" cy="55" r="1" fill="white" opacity="0.6"/>
  <circle cx="355" cy="140" r="1.5" fill="#c4b5fd" opacity="0.7"/>
  <circle cx="45" cy="310" r="1" fill="white" opacity="0.5"/>
  <circle cx="370" cy="340" r="1.5" fill="white" opacity="0.8"/>
  <circle cx="80" cy="350" r="1" fill="#a78bfa" opacity="0.6"/>
  <circle cx="320" cy="350" r="1.5" fill="white" opacity="0.5"/>
  <circle cx="130" cy="50" r="1" fill="#c4b5fd" opacity="0.7"/>
  <circle cx="290" cy="45" r="1.5" fill="white" opacity="0.6"/>

  <!-- Monogram "NN" in nucleus -->
  <text x="200" y="207" text-anchor="middle" dominant-baseline="middle"
        font-family="Georgia, serif" font-size="16" font-weight="700"
        fill="#ede9fe" letter-spacing="2" filter="url(#glow)">NN</text>

  <!-- Name text -->
  <text x="200" y="290" text-anchor="middle"
        font-family="Georgia, 'Times New Roman', serif"
        font-size="18" font-weight="600" fill="#c4b5fd"
        letter-spacing="3" filter="url(#glow)">NAVEERA NAZNEEN</text>

  <!-- Tagline -->
  <text x="200" y="316" text-anchor="middle"
        font-family="'Courier New', monospace"
        font-size="9.5" fill="#7c3aed" letter-spacing="2.5" opacity="0.9">PHYSICIST  ·  DEVELOPER  ·  SPACE</text>

  <!-- Bottom decorative line -->
  <line x1="120" y1="328" x2="280" y2="328" stroke="#6d28d9" stroke-width="0.8" opacity="0.6"/>

  <!-- Tiny sigma / equation hint at bottom -->
  <text x="200" y="348" text-anchor="middle"
        font-family="Georgia, serif"
        font-size="11" fill="#6d28d9" opacity="0.7" letter-spacing="1">∇²ψ + k²ψ = 0</text>
</svg>
