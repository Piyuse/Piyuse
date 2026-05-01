<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Profile Card</title>
  <style>
    * {
      box-sizing: border-box;
      margin: 0;
      padding: 0;
    }

    body {
      background: #050505;
      display: flex;
      justify-content: center;
      align-items: center;
      min-height: 100vh;
      font-family: 'Segoe UI', sans-serif;
    }

    .card {
      background: #0f0f0f;
      border: 0.5px solid #2e2e2e;
      border-radius: 16px;
      padding: 2rem;
      width: 360px;
    }

    .card h2 {
      font-size: 22px;
      font-weight: 500;
      color: #f0f0f0;
      margin-bottom: 0.25rem;
    }

    .card p.bio {
      font-size: 15px;
      color: #888;
      line-height: 1.7;
      margin-bottom: 0.4rem;
    }

    .card p.tagline {
      font-size: 13px;
      color: #666;
      line-height: 1.6;
      margin-bottom: 1.5rem;
      font-style: italic;
    }

    .links {
      display: flex;
      flex-direction: column;
      gap: 10px;
    }

    .link-item {
      display: flex;
      align-items: center;
      gap: 12px;
      padding: 12px 16px;
      background: #1a1a1a;
      border: 0.5px solid #2e2e2e;
      border-radius: 12px;
      text-decoration: none;
      transition: background 0.2s, border-color 0.2s;
    }

    .link-item:hover {
      background: #222;
      border-color: #444;
    }

    .link-item .icon {
      flex-shrink: 0;
    }

    .link-item .info .label {
      font-size: 11px;
      color: #555;
      text-transform: uppercase;
      letter-spacing: 0.05em;
      margin-bottom: 2px;
    }

    .link-item .info .value {
      font-size: 14px;
      font-weight: 500;
      color: #e0e0e0;
    }
  </style>
</head>
<body>

  <div class="card">
    <h2>Hi there!</h2>
    <p class="bio">Working in data implementation</p>
    <p class="tagline">Discuss me with system architecture and building cool stuffs</p>

    <div class="links">

      <!-- Email -->
      <a href="mailto:priyapiyuse@gmail.com" class="link-item">
        <div class="icon">
          <svg width="18" height="18" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg">
            <rect x="2" y="4" width="20" height="16" rx="2" stroke="#f09595" stroke-width="1.5"/>
            <path d="M2 7l10 7 10-7" stroke="#f09595" stroke-width="1.5" stroke-linecap="round"/>
          </svg>
        </div>
        <div class="info">
          <p class="label">Email</p>
          <p class="value">priyapiyuse@gmail.com</p>
        </div>
      </a>

      <!-- LinkedIn -->
      <a href="https://www.linkedin.com/in/your-linkedin-username" target="_blank" class="link-item">
        <div class="icon">
          <svg width="18" height="18" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg">
            <rect width="24" height="24" rx="4" fill="#2563a8"/>
            <path d="M7 9h2v8H7V9zm1-2.5A1.25 1.25 0 1 1 8 9a1.25 1.25 0 0 1 0-2.5zM11 9h2v1.1c.4-.7 1.2-1.1 2-1.1 2 0 3 1.3 3 3.3V17h-2v-4.5c0-1-.4-1.5-1.2-1.5-.9 0-1.8.6-1.8 2V17h-2V9z" fill="white"/>
          </svg>
        </div>
        <div class="info">
          <p class="label">LinkedIn</p>
          <p class="value">Connect with me</p>
        </div>
      </a>

    </div>
  </div>

</body>
</html>
