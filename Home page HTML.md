<!DOCTYPE html>
<html lang="id">
  <head>
    <meta charset="utf-8" />
    <meta name="viewport" content="width=device-width,initial-scale=1" />
    <title>Selamat datang di laman Sally</title>
    <link
      href="https://fonts.googleapis.com/css2?family=Baloo+2:wght@400;700;800&family=Poppins:wght@300;600&display=swap"
      rel="stylesheet"
    />
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <div class="page" role="main">
      <div class="topbar" aria-hidden="true">
        <div class="menu" role="button" aria-label="Menu">
          <span></span>
          <span></span>
          <span></span>
        </div>
      </div>

      <div class="container">
        <h1>Selamat datang di laman Sally!</h1>
        <p class="lead">
          Di artikel ini kalian bisa mengetahui apa saja keberagaman yang ada di
          Indonesia
        </p>

        <div class="center-image" aria-hidden="false">
          <!-- Replace the src with your cartoon/group image. -->
          <img src="indonesia-kids.png" alt="Kids in Traditional Costume">
        </div>

        <a class="cta" href="#artikel">Baca artikel</a>

        <div class="preview" id="artikel" aria-label="Preview artikel"></div>
      </div>

      <!-- decorative flowers (simple inline SVGs) -->
      <div class="flower-row" aria-hidden="true">
        <div class="flower-left">
          <img src="blue-flowers.png" alt="Blue Flowers" />
            <g fill="none" fill-rule="evenodd">
              <ellipse cx="70" cy="120" rx="40" ry="22" fill="#cfe6ff" />
              <circle cx="40" cy="90" r="28" fill="#c6d9ff" />
              <circle cx="100" cy="70" r="30" fill="#bcd6ff" />
              <path
                d="M20 50 C40 30, 90 20, 110 40"
                stroke="#8aa"
                stroke-width="4"
                stroke-linecap="round"
                fill-opacity="0"
              />
            </g>
          </svg>
        </div>

        <div class="flower-right">
          <img src="blue-flowers.png" alt="Blue Flowers" />
            <g fill="none" fill-rule="evenodd">
              <ellipse cx="230" cy="120" rx="40" ry="22" fill="#cfe6ff" />
              <circle cx="210" cy="90" r="28" fill="#c6d9ff" />
              <circle cx="260" cy="70" r="30" fill="#bcd6ff" />
              <path
                d="M180 50 C200 30, 250 20, 270 40"
                stroke="#8aa"
                stroke-width="4"
                stroke-linecap="round"
                fill-opacity="0"
              />
            </g>
          </svg>
        </div>
      </div>
    </div>

  </body>
</html>
