
<svg
        width="300"
        height="165"
        viewBox="0 0 300 165"
        fill="none"
        xmlns="http://www.w3.org/2000/svg"
        role="img"
        aria-labelledby="descId"
      >
        <title id="titleId"></title>
        <desc id="descId"></desc>
        <style>
          .header {
            font: 600 18px 'Segoe UI', Ubuntu, Sans-Serif;
            fill: #2f80ed;
            animation: fadeInAnimation 0.8s ease-in-out forwards;
          }
          @supports(-moz-appearance: auto) {
            /* Selector detects Firefox */
            .header { font-size: 15.5px; }
          }
          
    @keyframes slideInAnimation {
      from {
        width: 0;
      }
      to {
        width: calc(100%-100px);
      }
    }
    @keyframes growWidthAnimation {
      from {
        width: 0;
      }
      to {
        width: 100%;
      }
    }
    .stat {
      font: 600 14px 'Segoe UI', Ubuntu, "Helvetica Neue", Sans-Serif; fill: #434d58;
    }
    @supports(-moz-appearance: auto) {
      /* Selector detects Firefox */
      .stat { font-size:12px; }
    }
    .bold { font-weight: 700 }
    .lang-name {
      font: 400 11px "Segoe UI", Ubuntu, Sans-Serif;
      fill: #434d58;
    }
    .stagger {
      opacity: 0;
      animation: fadeInAnimation 0.3s ease-in-out forwards;
    }
    #rect-mask rect{
      animation: slideInAnimation 1s ease-in-out forwards;
    }
    .lang-progress{
      animation: growWidthAnimation 0.6s ease-in-out forwards;
    }
    

          
    /* Animations */
    @keyframes scaleInAnimation {
      from {
        transform: translate(-5px, 5px) scale(0);
      }
      to {
        transform: translate(-5px, 5px) scale(1);
      }
    }
    @keyframes fadeInAnimation {
      from {
        opacity: 0;
      }
      to {
        opacity: 1;
      }
    }
  
          
        </style>

        

        <rect
          data-testid="card-bg"
          x="0.5"
          y="0.5"
          rx="4.5"
          height="99%"
          stroke="#e4e2e2"
          width="299"
          fill="#fffefe"
          stroke-opacity="1"
        />

        
      <g
        data-testid="card-title"
        transform="translate(25, 35)"
      >
        <g transform="translate(0, 0)">
      <text
        x="0"
        y="0"
        class="header"
        data-testid="header"
      >Most Used Languages</text>
    </g>
      </g>
    

        <g
          data-testid="main-card-body"
          transform="translate(0, 55)"
        >
          
    <svg data-testid="lang-items" x="25">
      
  
  <mask id="rect-mask">
      <rect x="0" y="0" width="250" height="8" fill="white" rx="5"/>
    </mask>
    
        <rect
          mask="url(#rect-mask)"
          data-testid="lang-progress"
          x="0"
          y="0"
          width="214.61"
          height="8"
          fill="#DA5B0B"
        />
      
        <rect
          mask="url(#rect-mask)"
          data-testid="lang-progress"
          x="214.61"
          y="0"
          width="21.49"
          height="8"
          fill="#b07219"
        />
      
        <rect
          mask="url(#rect-mask)"
          data-testid="lang-progress"
          x="236.10000000000002"
          y="0"
          width="15.79"
          height="8"
          fill="#f1e05a"
        />
      
        <rect
          mask="url(#rect-mask)"
          data-testid="lang-progress"
          x="241.89000000000001"
          y="0"
          width="15.77"
          height="8"
          fill="#e34c26"
        />
      
        <rect
          mask="url(#rect-mask)"
          data-testid="lang-progress"
          x="247.66000000000003"
          y="0"
          width="11.26"
          height="8"
          fill="#198CE7"
        />
      
        <rect
          mask="url(#rect-mask)"
          data-testid="lang-progress"
          x="248.92000000000002"
          y="0"
          width="11.07"
          height="8"
          fill="#5e5086"
        />
      
  
    <g transform="translate(0, 25)">
      <g transform="translate(0, 0)"><g transform="translate(0, 0)">
    <g class="stagger" style="animation-delay: 450ms">
      <circle cx="5" cy="6" r="5" fill="#DA5B0B" />
      <text data-testid="lang-name" x="15" y="10" class='lang-name'>
        Jupyter Notebook 85.85%
      </text>
    </g>
  </g><g transform="translate(0, 25)">
    <g class="stagger" style="animation-delay: 600ms">
      <circle cx="5" cy="6" r="5" fill="#b07219" />
      <text data-testid="lang-name" x="15" y="10" class='lang-name'>
        Java 8.60%
      </text>
    </g>
  </g><g transform="translate(0, 50)">
    <g class="stagger" style="animation-delay: 750ms">
      <circle cx="5" cy="6" r="5" fill="#f1e05a" />
      <text data-testid="lang-name" x="15" y="10" class='lang-name'>
        JavaScript 2.32%
      </text>
    </g>
  </g></g><g transform="translate(150, 0)"><g transform="translate(0, 0)">
    <g class="stagger" style="animation-delay: 450ms">
      <circle cx="5" cy="6" r="5" fill="#e34c26" />
      <text data-testid="lang-name" x="15" y="10" class='lang-name'>
        HTML 2.31%
      </text>
    </g>
  </g><g transform="translate(0, 25)">
    <g class="stagger" style="animation-delay: 600ms">
      <circle cx="5" cy="6" r="5" fill="#198CE7" />
      <text data-testid="lang-name" x="15" y="10" class='lang-name'>
        R 0.51%
      </text>
    </g>
  </g><g transform="translate(0, 50)">
    <g class="stagger" style="animation-delay: 750ms">
      <circle cx="5" cy="6" r="5" fill="#5e5086" />
      <text data-testid="lang-name" x="15" y="10" class='lang-name'>
        Haskell 0.43%
      </text>
    </g>
  </g></g>
    </g>
  
    </svg>
  
        </g>
      </svg>
    

