---
layout: page
title: Ставы
category: staves
icon: fas fa-dharmachakra
order: 3
---
<style>
.page-status {
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
  min-height: 70vh;
  text-align: center;
  padding: 50px 20px;
  font-family: 'Segoe UI', Roboto, sans-serif;
  background: linear-gradient(135deg, #676f72, #4b4b4b);
  border-radius: 20px;
  box-shadow: 0 10px 30px rgba(0,0,0,0.5);
  transition: transform 0.3s ease, box-shadow 0.3s ease;
}

.page-status:hover {
  transform: translateY(-5px);
  box-shadow: 0 20px 40px rgba(0,0,0,0.7);
}

.page-status i {
  font-size: 100px;
  margin-bottom: 25px;
  transition: transform 0.3s ease, color 0.3s ease;
}

.page-status:hover i {
  transform: rotate(15deg) scale(1.1);
}

.page-status h1 {
  font-size: 42px;
  margin-bottom: 15px;
  color: #fdf6e3;
  letter-spacing: 1px;
  text-shadow: 1px 1px 3px rgba(0,0,0,0.7);
}

.page-status p {
  font-size: 20px;
  color: #dcdcdc;
  max-width: 600px;
  line-height: 1.6;
}

.status-material i {
  color: #f39c12;
}

.status-tech i {
  color: #3498db;
}

.status-dev i {
  color: #9b59b6;
}
</style>

<div class="page-status status-dev">
  <i class="fas fa-cogs"></i>
  <h1>В процессе разработки</h1>
  <p>Эта страница еще разрабатывается. Спасибо за терпение!</p>
</div>
