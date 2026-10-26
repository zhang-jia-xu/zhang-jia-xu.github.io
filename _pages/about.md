---
permalink: /
title: "Welcome to my website!"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

<style>
  /* 1. 标题对齐微调 */
  @media (min-width: 1025px) and (orientation: landscape) {
    .page__title { margin-top: 8px !important; }
  }
  @media (min-width: 768px) and (orientation: portrait) {
    .page__title { margin-top: 24px !important; }
  }
  .author__avatar { display: none !important; }

  /* 2. 默认大型电脑宽屏排版：左右并排，顶部对齐 */
  .profile-wrap {
    display: flex;
    align-items: flex-start; 
    justify-content: space-between;
    gap: 30px;
    margin-top: 30px;
  }
  
  .profile-text {
    flex: 1;
    text-align: left;
  }
  
  .profile-pic {
    width: 30%; 
    max-width: 320px;
    min-width: 240px;
    border-radius: 8px;
    flex-shrink: 0;
  }

  /* 3. iPad 及竖置大屏：上下堆叠，照片基于文本宽度按 60% 比例缩放 */
  @media (max-width: 1199px), (orientation: portrait) {
    .profile-wrap {
      flex-direction: column-reverse; 
      align-items: center; 
    }
    .profile-text {
      width: 100%;
    }
    .profile-pic {
      width: 60%; /* 如果觉得偏大或偏小，直接改这里的 60% 即可 */
      max-width: 100%; 
      margin-bottom: 30px; 
    }
  }

  /* 4. 极窄手机屏幕保护：空间太小时让照片撑满全宽 */
  @media (max-width: 767px) {
    .profile-pic {
      width: 100%; 
    }
  }
</style>

<div class="profile-wrap">
  <div class="profile-text">
    <p>I am a Ph.D. candidate in Management and Strategy at the University of Hong Kong. I obtained a Bachelor of Economics degree from Wuhan University and a Master of Economics degree from the University of Hong Kong.</p>
    
    <p>My research interests lie in international trade, organizational economics, and applied microeconomics. My work primarily focuses on global sourcing, production networks, and supply chain reallocation, bridging theoretical models with both structural and reduced-form empirical analyses.</p>
    
    <p>You can reach me at <a href="mailto:zhjiaxu@connect.hku.hk">zhjiaxu@connect.hku.hk</a>.</p>
    
  </div>

  <img class="profile-pic" src="/images/photo2.JPG">
</div>