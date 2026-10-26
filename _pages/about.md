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

  /* 3. iPad（无论横竖）及所有窄屏：强制上下堆叠，拒绝挤压文字 */
  @media (max-width: 1199px), (orientation: portrait) {
    .profile-wrap {
      flex-direction: column-reverse; /* 照片在上，文字在下 */
      align-items: center; /* 整体居中 */
    }
    .profile-text {
      width: 100%;
    }
    .profile-pic {
      width: 100%;
      max-width: 320px;
      margin-bottom: 25px; /* 照片与下方文字的间距 */
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