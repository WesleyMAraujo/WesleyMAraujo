<svg width="850" height="450" viewBox="0 0 850 450" fill="none" xmlns="http://www.w3.org/2000/svg">
  <style>
    @keyframes orbit {
      from { transform: rotate(0deg) translateX(10px) rotate(0deg); }
      to   { transform: rotate(360deg) translateX(10px) rotate(-360deg); }
    }
    
    .node { 
      animation: orbit 10s linear infinite; 
      transform-box: fill-box;
      transform-origin: center;
    }
    
    .label { 
      fill: #e2e8f0; 
      font-family: 'Segoe UI', Tahoma, sans-serif; 
      font-size: 13px; 
      font-weight: 600;
    }

    .icon { width: 24px; height: 24px; }
    
    /* Variações de tempo para movimento natural */
    .d1 { animation-duration: 12s; }
    .d2 { animation-duration: 15s; animation-direction: reverse; }
    .d3 { animation-duration: 18s; }
    
    .line { stroke: rgba(100, 255, 218, 0.1); stroke-width: 1; }
  </style>

  <rect width="850" height="450" fill="#0d1117" rx="10"/>

  <g class="lines">
    <line class="line" x1="150" y1="100" x2="320" y2="80" />
    <line class="line" x1="320" y1="80" x2="500" y2="120" />
    <line class="line" x1="500" y1="120" x2="700" y2="100" />
    <line class="line" x1="150" y1="100" x2="200" y2="280" />
    <line class="line" x1="200" y1="280" x2="420" y2="350" />
    <line class="line" x1="420" y1="350" x2="650" y2="280" />
    <line class="line" x1="650" y1="280" x2="750" y2="180" />
  </g>

  <g class="node d1">
    <foreignObject x="130" y="80" width="100" height="40">
      <div xmlns="http://www.w3.org/1999/xhtml" style="display: flex; align-items: center; gap: 5px;">
        <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/php/php-original.svg" width="20" height="20"/>
        <span style="color: #777BB4; font-family: sans-serif; font-size: 14px; font-weight: bold;">PHP</span>
      </div>
    </foreignObject>
  </g>

  <g class="node d2">
    <foreignObject x="300" y="60" width="100" height="40">
      <div xmlns="http://www.w3.org/1999/xhtml" style="display: flex; align-items: center; gap: 5px;">
        <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/laravel/laravel-original.svg" width="20" height="20"/>
        <span style="color: #FF2D20; font-family: sans-serif; font-size: 14px; font-weight: bold;">Laravel</span>
      </div>
    </foreignObject>
  </g>

  <g class="node d3">
    <foreignObject x="480" y="100" width="100" height="40">
      <div xmlns="http://www.w3.org/1999/xhtml" style="display: flex; align-items: center; gap: 5px;">
        <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/vuejs/vuejs-original.svg" width="20" height="20"/>
        <span style="color: #4FC08D; font-family: sans-serif; font-size: 14px; font-weight: bold;">Vue.js</span>
      </div>
    </foreignObject>
  </g>

  <g class="node d1">
    <foreignObject x="180" y="260" width="110" height="40">
      <div xmlns="http://www.w3.org/1999/xhtml" style="display: flex; align-items: center; gap: 5px;">
        <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/javascript/javascript-original.svg" width="20" height="20"/>
        <span style="color: #F7DF1E; font-family: sans-serif; font-size: 14px; font-weight: bold;">JavaScript</span>
      </div>
    </foreignObject>
  </g>

  <g class="node d2">
    <foreignObject x="630" y="260" width="100" height="40">
      <div xmlns="http://www.w3.org/1999/xhtml" style="display: flex; align-items: center; gap: 5px;">
        <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" width="20" height="20"/>
        <span style="color: #3776AB; font-family: sans-serif; font-size: 14px; font-weight: bold;">Python</span>
      </div>
    </foreignObject>
  </g>

  <g class="node d3">
    <foreignObject x="400" y="330" width="100" height="40">
      <div xmlns="http://www.w3.org/1999/xhtml" style="display: flex; align-items: center; gap: 5px;">
        <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/cplusplus/cplusplus-original.svg" width="20" height="20"/>
        <span style="color: #00599C; font-family: sans-serif; font-size: 14px; font-weight: bold;">C++</span>
      </div>
    </foreignObject>
  </g>

  <g class="node d1">
    <foreignObject x="680" y="160" width="100" height="40">
      <div xmlns="http://www.w3.org/1999/xhtml" style="display: flex; align-items: center; gap: 5px;">
        <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/mysql/mysql-original.svg" width="20" height="20"/>
        <span style="color: #4479A1; font-family: sans-serif; font-size: 14px; font-weight: bold;">MySQL</span>
      </div>
    </foreignObject>
  </g>

  <g class="node d2">
    <foreignObject x="350" y="180" width="110" height="40">
      <div xmlns="http://www.w3.org/1999/xhtml" style="display: flex; align-items: center; gap: 5px;">
        <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/graphql/graphql-plain.svg" width="20" height="20"/>
        <span style="color: #E10098; font-family: sans-serif; font-size: 14px; font-weight: bold;">GraphQL</span>
      </div>
    </foreignObject>
  </g>

</svg>
