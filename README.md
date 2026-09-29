<svg width="1200" height="350" viewBox="0 0 1200 350"
     xmlns="http://www.w3.org/2000/svg">

  <defs>

    <!-- Background gradient -->
    <linearGradient id="background"
                    x1="0%" y1="0%"
                    x2="100%" y2="100%">

      <stop offset="0%" stop-color="#020617"/>
      <stop offset="45%" stop-color="#312e81"/>
      <stop offset="100%" stop-color="#0f172a"/>

    </linearGradient>

    <!-- Name gradient -->
    <linearGradient id="nameGradient"
                    x1="0%" y1="0%"
                    x2="100%" y2="0%">

      <stop offset="0%" stop-color="#a78bfa"/>
      <stop offset="50%" stop-color="#ffffff"/>
      <stop offset="100%" stop-color="#60a5fa"/>

    </linearGradient>

    <!-- Glow effect -->
    <filter id="glow">

      <feGaussianBlur
        stdDeviation="6"
        result="blur"/>

      <feMerge>

        <feMergeNode in="blur"/>
        <feMergeNode in="SourceGraphic"/>

      </feMerge>

    </filter>

  </defs>


  <!-- Background -->

  <rect
    width="1200"
    height="350"
    rx="30"
    fill="url(#background)"
  />


  <!-- Decorative glowing circles -->

  <circle
    cx="100"
    cy="70"
    r="70"
    fill="#8b5cf6"
    opacity="0.12"
  />

  <circle
    cx="1100"
    cy="280"
    r="100"
    fill="#3b82f6"
    opacity="0.12"
  />

  <circle
    cx="1050"
    cy="60"
    r="35"
    fill="#a78bfa"
    opacity="0.18"
  />

  <circle
    cx="150"
    cy="290"
    r="35"
    fill="#60a5fa"
    opacity="0.15"
  />


  <!-- Small decorative dots -->

  <circle cx="220" cy="70" r="4" fill="#ffffff" opacity="0.5"/>
  <circle cx="980" cy="100" r="4" fill="#ffffff" opacity="0.5"/>
  <circle cx="300" cy="280" r="3" fill="#ffffff" opacity="0.4"/>
  <circle cx="900" cy="260" r="3" fill="#ffffff" opacity="0.4"/>


  <!-- Greeting -->

  <text
    x="600"
    y="105"
    text-anchor="middle"
    font-family="Arial, Helvetica, sans-serif"
    font-size="34"
    font-weight="700"
    fill="#ffffff">

    Hi There, I'm

  </text>


  <!-- Name -->

  <text
    x="600"
    y="175"
    text-anchor="middle"
    font-family="Arial, Helvetica, sans-serif"
    font-size="58"
    font-weight="900"
    fill="url(#nameGradient)"
    filter="url(#glow)">

    Yididiya Beyene

  </text>


  <!-- Profession -->

  <text
    x="600"
    y="225"
    text-anchor="middle"
    font-family="Arial, Helvetica, sans-serif"
    font-size="28"
    font-weight="700"
    fill="#e2e8f0">

    Software Engineer

  </text>


  <!-- Bottom decorative line -->

  <rect
    x="480"
    y="255"
    width="240"
    height="3"
    rx="2"
    fill="url(#nameGradient)"
  />

</svg>
<!--
**Yididiya16/Yididiya16** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
