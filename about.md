---
layout: page
title: 关于
permalink: /about/
---

<style>
.about-container {
  max-width: 680px;
  margin: 0 auto;
  padding: 3rem 1.2rem;
  line-height: 1.8;
  color: #1a202c;
  font-weight: 400;
}

.section {
  margin-bottom: 3.5rem;
  transition: all 0.3s ease;
}

.section:hover {
  transform: translateX(4px);
}

.section h2 {
  color: #099268;
  font-size: 1.2rem;
  font-weight: 600;
  margin-bottom: 1.5rem;
  letter-spacing: 0.02em;
  border-left: 3px solid #20c997;
  padding-left: 0.8rem;
  display: flex;
  align-items: center;
  transition: all 0.3s ease;
}

.section:hover h2 {
  border-left-width: 4px;
  padding-left: 1rem;
}

.section-icon {
  margin-right: 0.5rem;
  font-size: 1.1rem;
}

.bio, .interests-list {
  color: #2d3748;
  font-size: 1rem;
  margin: 0;
  padding-left: 2rem;
}

/* 技术栈特殊样式 */
.tech-stack {
  color: #4a5568;
  background: #f7fafc;
  padding: 1rem 1.5rem;
  border-radius: 6px;
  margin-left: 2rem;
  font-size: 0.95rem;
  border: 1px solid #e2e8f0;
}

/* 链接样式 */
.section a {
  color: #099268;
  text-decoration: none;
  border-bottom: 1px dashed #20c997;
  transition: all 0.2s ease;
}

.section a:hover {
  color: #20c997;
  border-bottom-style: solid;
}

/* 分隔线 */
.divider {
  text-align: center;
  color: #718096;
  font-size: 0.9rem;
  margin: 4rem 0 2rem;
  position: relative;
  font-style: italic;
}

.divider::before {
  content: "";
  position: absolute;
  left: 50%;
  top: -1.5rem;
  transform: translateX(-50%);
  width: 40px;
  height: 1px;
  background: linear-gradient(to right, transparent, #cbd5e0, transparent);
}

.divider::after {
  content: "✦";
  display: block;
  margin-top: 0.5rem;
  color: #cbd5e0;
  font-size: 0.8rem;
}

/* 标签样式 */
.tag {
  display: inline-block;
  padding: 0.2rem 0.5rem;
  background: #f0fff4;
  color: #099268;
  border-radius: 4px;
  font-size: 0.85rem;
  margin: 0 0.2rem;
  border: 1px solid #c6f6d5;
}

/* 响应式 */
@media (max-width: 768px) {
  .about-container {
    padding: 2rem 1rem;
  }
  
  .section h2 {
    font-size: 1.1rem;
  }
  
  .bio, .interests-list {
    padding-left: 1.5rem;
  }
  
  .tech-stack {
    margin-left: 1.5rem;
    padding: 0.8rem 1rem;
  }
}

/* 深色模式支持 */
@media (prefers-color-scheme: dark) {
  .about-container {
    color: #e2e8f0;
  }
  
  .section h2 {
    color: #20c997;
  }
  
  .bio, .interests-list {
    color: #cbd5e0;
  }
  
  .tech-stack {
    background: #2d3748;
    color: #a0aec0;
    border-color: #4a5568;
  }
  
  .divider {
    color: #a0aec0;
  }
}
</style>

<div class="about-container">

  <div class="section">
    <h2><span class="section-icon">💼</span>现在</h2>
    <p class="bio">
      在一家网络安全公司做 Java 后端开发，写过不少与数据安全、国产化改造相关的系统。<br>
      目标简单：让复杂的东西优雅可控，让安全不止是口号。
    </p>
  </div>

  <div class="section">
    <h2><span class="section-icon">🚀</span>经历</h2>
    <p class="bio">
      毕业于网络工程专业，之后一直从事 Java 开发工作。<br>
      做过政企信息化系统、数据治理平台、数据迁移工具，也参与过安全相关的产品研发。<br>
      一路走来，踩过不少坑，也总结了不少"工程师的生存技巧"。
    </p>
  </div>

  <div class="section">
    <h2><span class="section-icon">🎯</span>关注</h2>
    <p class="interests-list">
      分布式系统、微服务架构、数据安全防护。<br>
      有时研究性能优化和代码重构，有时折腾新技术栈。<br>
      对开源保持好奇，偶尔贡献点小 patch。
    </p>
  </div>

  <div class="section">
    <h2><span class="section-icon">⚡</span>技术</h2>
    <div class="tech-stack">
      后端：Java / Spring Boot / Spring Cloud / MyBatis<br>
      数据：MySQL / PostgreSQL / Redis / Elasticsearch<br>
      运维：Docker / Kubernetes / Linux / Nginx<br>
      工具：Git / Maven / Jenkins / Markdown
    </div>
  </div>

  <div class="section">
    <h2><span class="section-icon">✨</span>其他</h2>
    <p class="interests-list">
      代码之外，喜欢旅行、拍照和读点散文。<br>
      相信"慢慢来比较快"，更相信"写下来，才是你的"。<br>
      这个博客就是我的 <span class="tag">数字花园</span>，记录成长，分享思考。
    </p>
  </div>

  <div class="divider">
    记录与分享，不过是写给未来的自己
  </div>

</div>
