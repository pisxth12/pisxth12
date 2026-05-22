<div align="center">

![Radar](https://i.pinimg.com/originals/2c/6e/2f/2c6e2f8e8b8e8c8e8b8e8c8e8b8e8c.gif)

</div>

---

Or use this working version:

<div align="center">
  <img src="https://media.giphy.com/media/3o6Zt6KHxJTbXCnSvu/giphy.gif" width="200" height="200">
</div>

---

Or this animated SVG that works:

<div align="center">
  <svg width="200" height="200" viewBox="0 0 200 200" xmlns="http://www.w3.org/2000/svg">
    <defs>
      <style>
        @keyframes spin { to { transform: rotate(360deg); } }
        @keyframes pulse { 0%, 100% { opacity: 0.3; } 50% { opacity: 1; } }
        .radar-line { animation: spin 4s linear infinite; transform-origin: 100px 100px; }
        .radar-dot { animation: pulse 2s ease-in-out infinite; }
      </style>
    </defs>
    <circle cx="100" cy="100" r="90" fill="none" stroke="#00ff00" stroke-width="2" opacity="0.3"/>
    <circle cx="100" cy="100" r="60" fill="none" stroke="#00ff00" stroke-width="1" opacity="0.2"/>
    <circle cx="100" cy="100" r="30" fill="none" stroke="#00ff00" stroke-width="1" opacity="0.2"/>
    <line x1="100" y1="100" x2="100" y2="20" stroke="#00ff00" stroke-width="2" class="radar-line"/>
    <circle cx="100" cy="100" r="5" fill="#00ff00" class="radar-dot"/>
  </svg>
</div>
