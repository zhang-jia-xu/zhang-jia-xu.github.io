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

  /* 2. 默认大型电脑宽屏排版：左右并排，锁定最佳宽度 */
  .profile-wrap {
    display: flex;
    align-items: flex-start; 
    justify-content: space-between;
    gap: 40px;
    margin-top: 30px;
  }
  
  .profile-text {
    flex: 1;
    text-align: left;
  }
  
  .profile-pic {
    width: 360px; /* 横屏时固定为 360px，防止被过度压缩 */
    flex-shrink: 0;
    border-radius: 8px;
  }

  /* 3. iPad 及竖置大屏：上下堆叠，解除固定像素并按比例拉伸 */
  @media (max-width: 1199px), (orientation: portrait) {
    .profile-wrap {
      flex-direction: column-reverse; 
      align-items: center; 
    }
    .profile-text {
      width: 100%;
    }
    .profile-pic {
      width: 60%; /* 竖屏时自动放大到文本宽度的 60% */
      max-width: none; 
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
    <p>I am a Ph.D. candidate in Management and Strategy (Economics track) at the University of Hong Kong. I obtained a Bachelor of Economics degree from Wuhan University and a Master of Economics degree from the University of Hong Kong.</p>
    
    <p>My research interests lie in international trade, organizational economics, and applied microeconomics. My work primarily focuses on global sourcing, production networks, and supply chain reallocation, bridging theoretical models with both structural and reduced-form empirical analyses.</p>
    
    <p>You can reach me at <a href="mailto:zhjiaxu@connect.hku.hk">zhjiaxu@connect.hku.hk</a>.</p>
    
  </div>

  <img class="profile-pic" src="/images/photo2.JPG" alt="Zhang Jiaxu, Ph.D. candidate in Management and Strategy at HKU">
</div>