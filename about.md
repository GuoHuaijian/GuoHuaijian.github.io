---
layout: page
title: 关于
permalink: /about/
---

<div class="content-wrapper">
  <div class="falling-leaves"></div>
  <header class="page-header">
    <h1>🏔️ 问道江湖</h1>
    <div class="subtitle-wrapper">
      <div class="subtitle-line">修行路上，无非是见自己，见天地，见众生</div>
    </div>
  </header>

<style>
.subtitle-wrapper {
  margin-top: 1.2rem;
  padding: 0.5rem 1rem;
  text-align: center;
}

.subtitle-line {
  position: relative;
  display: inline-block;
  color: #666;
  font-style: italic;
  padding: 0.5rem 0;
  transition: all 0.3s ease;
}

.subtitle-line::after {
  content: '';
  position: absolute;
  bottom: 0;
  left: 50%;
  width: 0;
  height: 1px;
  background: #42b983;
  transition: all 0.3s ease;
  transform: translateX(-50%);
}

.subtitle-line:hover {
  color: #42b983;
}

.subtitle-line:hover::after {
  width: 100%;
}
</style>

  <section class="intro">
    <p>我本是江湖一散修，偶得机缘踏入编程大道，以键盘为剑，以代码为符，在 <code>☕ Java</code> 的山水之间寻一份"万物皆对象"的天道真意。</p>
    <p>曾于 <code>🌿 Spring</code> 秘境中闭关三年，悟得 <code>IoC</code> 反转乾坤、<code>AOP</code> 斩因果之术；又在 <code>⚔️ 并发剑冢</code> 里苦修多日，方知"锁如心魔，线程似众生，一念阻塞，万法皆空"。</p>
  </section>

  <section class="weapons">
    <h2>⚔️ 本命法宝</h2>
    <div class="weapons-grid">
      <div class="weapon-item">🗡️ <code>Java</code> —— 剑意绵长，重剑无锋</div>
      <div class="weapon-item">📦 <code>IntelliJ IDEA</code> —— 匣藏万法，一念生符</div>
      <div class="weapon-item">🛡️ <code>Spring Boot</code> —— 气机圆转，生生不息</div>
      <div class="weapon-item">📖 <code>Clean Code</code> —— 大道至简，代码如诗</div>
    </div>
  </section>

  <section class="timeline">
    <h2>🔥 历劫之地</h2>
    <div class="timeline-items">
      <div class="timeline-item">
        <span class="icon">🤯</span>
        <p>曾与 <code>OutOfMemoryError</code> 鏖战三天三夜，终以 <strong>JVM 调优</strong> 破其阵法。</p>
      </div>
      <div class="timeline-item">
        <span class="icon">🌊</span>
        <p>在 <code>分布式事务</code> 的混沌深渊中，借 <code>Seata</code> 之光斩开一线天机。</p>
      </div>
      <div class="timeline-item">
        <span class="icon">👀</span>
        <p>遇生产环境诡异 <code>NullPointerException</code> 时，方知"<strong>世间万般Bug，皆是心不静</strong>"。</p>
      </div>
    </div>
  </section>

  <section class="philosophy">
    <h2>🛤️ 问道之心</h2>
    <div class="philosophy-items">
      <div class="philosophy-item">💻 写代码时，常记 <code>齐静春</code> 之言：<strong>"顺序，分支，循环，便是人间。"</strong></div>
      <div class="philosophy-item">📐 解难题时，默念 <code>崔瀺</code> 之算计：<strong>"天下算法，不过空间换时间，时间换空间。"</strong></div>
      <div class="philosophy-item">😌 倦怠时，想起 <code>剑灵</code> 所言：<strong>"你手中的代码，便是你的道理。"</strong></div>
    </div>
  </section>

  <section class="connect">
    <h2>🍵 道友共勉</h2>
    <div class="connect-content">
      <p class="connect-intro">若道友亦是：</p>
      <ul class="journey-list">
        <li>在 <strong>Git</strong> 的版本长河中，追寻 <code>commit</code> 真意 🌀</li>
        <li>于 <strong>设计模式</strong> 的万法归一中，窥见 <code>开闭之道</code> 🎭</li>
        <li>愿以 <strong>单元测试</strong> 为剑 🏹，破 "牵一发而动全身" 之因果劫</li>
      </ul>
      <p>不妨共饮一杯 <code>☕ Java</code>，论道于 <a href="https://github.com/GuoHuaijian" target="_blank">GitHub</a>，修那"<strong>代码无瑕，架构通明</strong>"的大逍遥境界。</p>
    </div>
  </section>

  <section class="epilogue">
    <h2>🚀 行远自迩</h2>
    <div class="epilogue-content">
      <div class="motto-card">道阻且长，行则将至</div>
      <div class="verse-cards">
        <div class="verse-card">
          <span class="verse-icon">⚡</span>
          <div class="card-content">世间有剑，可斩因果，可断江河，可开天门</div>
        </div>
        <div class="verse-card">
          <span class="verse-icon">🌠</span>
          <div class="card-content">亦有少年，负剑星河，纵横天地，问道江湖</div>
        </div>
        <div class="verse-card">
          <span class="verse-icon">✨</span>
          <div class="card-content">若有一日，提剑登高，回望来路，愿此道不负少年志</div>
        </div>
      </div>
    </div>
  </section>

<style>
.epilogue {
  padding: 1.5rem;
  background: rgba(255, 255, 255, 0.8);
  text-align: left;
}

.motto-card {
  margin-bottom: 2rem;
  padding: 0.8rem 1rem;
  color: #2c3e50;
  font-style: italic;
  background: rgba(66, 185, 131, 0.05);
  border-radius: 6px;
}

.verse-cards {
  display: flex;
  flex-direction: column;
  gap: 1.2rem;
}

.verse-card {
  display: flex;
  align-items: flex-start;
  gap: 1rem;
  padding: 1rem;
  border-radius: 6px;
  transition: all 0.3s ease;
}

.verse-icon {
  font-size: 1.2rem;
  margin-top: 0.2rem;
}

.card-content {
  color: #2c3e50;
  line-height: 1.6;
  flex: 1;
}

.verse-card:hover {
  background: rgba(66, 185, 131, 0.05);
  transform: translateX(5px);
}
</style>

<style>
.epilogue {
  padding: 1rem;
  background: rgba(255, 255, 255, 0.8);
  text-align: left;  /* 添加这行确保左对齐 */
}

.epilogue h2 {
  text-align: left;  /* 专门为标题添加左对齐 */
}

.motto-card {
  display: inline-block;
  margin-bottom: 1.5rem;
  padding: 0.5rem 1rem;
  background: #f8f9fa;
  border-radius: 4px;
  color: #42b983;
  font-style: italic;
  text-align: left;  /* 确保引言也左对齐 */
}

.verse-cards {
  display: flex;
  flex-direction: column;
  gap: 0.8rem;
}

.verse-card {
  position: relative;
  padding: 0.8rem;
  background: #fff;
  border-radius: 6px;
  box-shadow: 0 2px 4px rgba(0,0,0,0.05);
  transition: all 0.3s ease;
}

.card-content {
  color: #2c3e50;
  line-height: 1.6;
}

.verse-card:hover {
  transform: translateX(5px);
  box-shadow: 2px 2px 8px rgba(66, 185, 131, 0.1);
}
</style>

<style>
.epilogue {
  padding: 1rem;
  background: rgba(255, 255, 255, 0.8);
}

.motto {
  margin-bottom: 1.5rem;
  padding: 0.5rem 1rem;
  color: #666;
  font-style: italic;
  border-left: 3px solid #42b983;
}

.verses {
  display: flex;
  flex-direction: column;
  gap: 1rem;
}

.verse {
  padding: 0.8rem 1rem;
  background: #f8f9fa;
  border-radius: 6px;
  border-left: 3px solid #42b983;
  color: #2c3e50;
  transition: all 0.3s ease;
}

.verse:hover {
  transform: translateX(5px);
  background: rgba(66, 185, 131, 0.05);
}

.content-wrapper {
  max-width: 800px;
  margin: 0 auto;
  padding: 1rem;
  line-height: 1.6;
}

.page-header {
  text-align: center;
  margin-bottom: 2rem;
}

.page-header h1 {
  margin-bottom: 0.5rem;
  font-size: 2rem;
}

.subtitle {
  color: #666;
  font-style: italic;
}

section {
  margin: 1.5rem 0;
  padding: 1rem;
  background: rgba(255, 255, 255, 0.8);
  border-radius: 8px;
  box-shadow: 0 2px 8px rgba(0,0,0,0.05);
}

h2 {
  font-size: 1.4rem;
  margin-bottom: 1rem;
  color: #2c3e50;
}

.weapons-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(240px, 1fr));
  gap: 1rem;
}

.weapon-item {
  padding: 0.8rem;
  background: #f8f9fa;
  border-radius: 6px;
  border-left: 3px solid #42b983;
  transition: transform 0.2s;
}

.weapon-item:hover {
  transform: translateX(5px);
}

.timeline-items {
  border-left: 2px solid #42b983;
  padding-left: 1.5rem;
}

.timeline-item {
  position: relative;
  margin-bottom: 1rem;
}

.timeline-item .icon {
  position: absolute;
  left: -2rem;
  background: white;
  border-radius: 50%;
  padding: 0.2rem;
}

.philosophy-items {
  display: grid;
  gap: 1rem;
}

.philosophy-item {
  padding: 0.8rem;
  background: #f8f9fa;
  border-radius: 6px;
}

code {
  background: #f1f1f1;
  padding: 0.2em 0.4em;
  border-radius: 3px;
  color: #42b983;
}

a {
  color: #42b983;
  text-decoration: none;
  border-bottom: none;  /* 移除所有 a 标签的下边框 */
}

.connect-content a {
  border-bottom: 1px dashed;  /* 只在 connect-content 区域内的链接添加虚线 */
}

.connect-content a:hover {
  border-bottom-style: solid;  /* connect-content 区域内链接悬停时变为实线 */
}

.github-stats {
  text-align: center;
  margin-top: 2rem;
}

.github-stats img {
  border-radius: 8px;
  max-width: 100%;
}

@media (max-width: 768px) {
  .weapons-grid {
    grid-template-columns: 1fr;
  }
  
  section {
    padding: 0.8rem;
  }
}

.music-player {
  position: fixed;
  top: 10px;
  right: 10px;
  width: 300px;
  height: 80px;
  z-index: 1000;
  border-radius: 8px;
  overflow: hidden;
  box-shadow: 0 2px 10px rgba(0,0,0,0.1);
}

@media (max-width: 600px) {
  .music-player {
    width: 260px;
    height: 66px;
  }
}
.journey-list {
  list-style: none;
  padding-left: 0;
  margin: 1.5rem 0;
}

.journey-list li {
  margin: 1rem 0;
  position: relative;
  padding: 0.8rem 1rem 0.8rem 2.5rem;
  background: rgba(66, 185, 131, 0.05);
  border-radius: 6px;
  transition: all 0.3s ease;
}

.journey-list li::before {
  content: '✧';
  color: #42b983;
  position: absolute;
  left: 1rem;
  font-size: 1.2rem;
  opacity: 0.8;
}

.journey-list li:hover {
  transform: translateX(5px);
  background: rgba(66, 185, 131, 0.1);
  box-shadow: 0 2px 8px rgba(66, 185, 131, 0.1);
}

.journey-list li:hover::before {
  transform: rotate(180deg);
  transition: transform 0.5s ease;
}

.connect-intro {
  margin: 1rem 0;
  padding: 0.5rem;
  text-align: center;
  color: #2c3e50;
  font-size: 1.1rem;
  border-bottom: 1px dashed rgba(66, 185, 131, 0.3);
}

.connect-content {
  padding: 0 1rem;
}
.epilogue {
  text-align: center;
  position: relative;
  padding: 2rem;
  background: linear-gradient(to bottom, rgba(255,255,255,0.95), rgba(255,255,255,0.8));
}

.epilogue blockquote {
  border: none;
  position: relative;
  padding: 1.5rem;
  margin: 2rem auto;
  max-width: 600px;
  background: rgba(66, 185, 131, 0.05);
  border-radius: 8px;
}

.epilogue blockquote::before,
.epilogue blockquote::after {
  content: '"';
  position: absolute;
  color: #42b983;
  font-size: 3rem;
  opacity: 0.2;
}

.epilogue blockquote::before {
  top: -0.5rem;
  left: 0.5rem;
}

.epilogue blockquote::after {
  bottom: -2rem;
  right: 0.5rem;
}

.poetic-text {
  font-style: italic;
  line-height: 2.2;
  margin: 2rem 0;
  position: relative;
}

.poetic-text p {
  margin: 1rem 0;
  position: relative;
  transition: all 0.3s ease;
}

.poetic-text p:hover {
  transform: translateY(-2px);
  text-shadow: 2px 2px 4px rgba(0,0,0,0.1);
}

.epilogue::after {
  content: '⚔️';
  position: absolute;
  bottom: -1rem;
  left: 50%;
  transform: translateX(-50%);
  font-size: 1.5rem;
  opacity: 0.5;
  animation: float 2s ease-in-out infinite;
}

@keyframes float {
  0%, 100% { transform: translateX(-50%) translateY(0); }
  50% { transform: translateX(-50%) translateY(-10px); }
}
</style>

<div class="music-player">
  <iframe frameborder="no" border="0" marginwidth="0" marginheight="0" width="100%" height="100%"
    src="//music.163.com/outchain/player?type=2&id=1394167216&auto=1&height=66">
  </iframe>
</div>

<style>
.falling-leaves {
  position: fixed;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  pointer-events: none;
  z-index: 1;
}

.leaf {
  position: absolute;
  width: 20px;
  height: 20px;
  background: url("data:image/svg+xml,%3Csvg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 24 24'%3E%3Cpath fill='%2342b983' d='M17,8C8,10 5.9,16.17 3.82,21.34L5.71,22L6.66,19.7C7.14,19.87 7.64,20 8,20C19,20 22,3 22,3C21,5 14,5.25 9,6.25C4,7.25 2,11.5 2,13.5C2,15.5 3.75,17.25 3.75,17.25C7,8 17,8 17,8Z'/%3E%3C/svg%3E") center/contain no-repeat;
  opacity: 0.2;
  pointer-events: none;
}

@keyframes fall {
  0% {
    opacity: 0;
    top: -10%;
    transform: translateX(0) rotate(0deg) scale(0.8);
  }
  10% {
    opacity: 0.8;
  }
  20% {
    transform: translateX(25px) rotate(45deg) scale(1);
  }
  40% {
    transform: translateX(-15px) rotate(90deg) scale(0.9);
  }
  60% {
    transform: translateX(20px) rotate(180deg) scale(1.1);
  }
  80% {
    transform: translateX(-20px) rotate(270deg) scale(0.9);
  }
  100% {
    top: 110%;
    transform: translateX(0) rotate(360deg) scale(0.7);
    opacity: 0;
  }
}
</style>

<script>
function createLeaves() {
  const container = document.querySelector('.falling-leaves');
  const createLeaf = () => {
    const leaf = document.createElement('div');
    leaf.className = 'leaf';
    leaf.style.left = Math.random() * 100 + 'vw';
    leaf.style.animation = `fall ${Math.random() * 10 + 5}s linear forwards`;
    container.appendChild(leaf);
    
    setTimeout(() => {
      leaf.remove();
    }, 15000);
  };

  // 初始创建一些叶子
  for(let i = 0; i < 15; i++) {
    setTimeout(createLeaf, Math.random() * 5000);
  }
  
  // 持续创建新的叶子
  setInterval(() => {
    createLeaf();
  }, 2000);
}

document.addEventListener('DOMContentLoaded', createLeaves);
</script>
