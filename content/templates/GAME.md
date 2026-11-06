---
title: "{{title}}"
tags:
  - 
players: " игрока"
duration: " мин"
complexity: "easy"
shelf: ""
video_id: ""
image_url: ""
---

<div class="game-cover-container">
  <img src="`" + "src" + "`" class="game-image" src="{{image_url}}" alt="Обложка игры">
</div>

<div class="game-express-info">
  <div class="info-badge bg-medium">
    <span>👥</span>
    <span>{{players}}</span>
  </div>
  <div class="info-badge bg-medium">
    <span>⏳</span>
    <span>{{duration}}</span>
  </div>
  <div class="info-badge bg-easy">
    <span>🟢</span>
    <span>В клубе</span>
  </div>
</div>

<div class="action-buttons-group">
  <a href="#rules-video" class="action-btn btn-video">
    🎬 Смотреть видео-правила
  </a>
  <div class="action-btn btn-location">
    📍 Где взять в клубе: <strong>Полка {{shelf}}</strong>
  </div>
</div>

### Коротко об игре
Введите сюда 3-4 простых предложения описания без использования сложного гиковского сленга. 

---

<h3 id="rules-video">🎬 Видео-правила</h3>
<div class="video-container">
  <iframe src="https://youtube.com{{video_id}}" allowfullscreen></iframe>
</div>
