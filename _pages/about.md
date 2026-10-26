---
permalink: /
title: "Welcome to my website!"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

<style>
  /* 1. 常规横向电脑屏幕（横屏，且宽度较大） */
  @media (min-width: 1025px) and (orientation: landscape) {
    .page__title { margin-top: 8px !important; }
  }

  /* 2. 竖向大显示器 / 平板电脑（竖屏，且宽度足以并排显示左右两列） */
  @media (min-width: 768px) and (orientation: portrait) {
    .page__title { margin-top: 24px !important; }
  }

  /* 彻底隐藏左侧空头像占位符 */
  .author__avatar { display: none !important; }

  /* ---------------- 3. 照片与文字自适应排版 ---------------- */
  .profile-wrap {
    display: flex;
    flex-wrap: wrap-reverse; /* 空间不足时自动换行，且照片在文字上方 */
    align-items: center;
    justify-content: center;
    gap: 30px;
    margin-top: 30px;
  }
  
  .profile-text {
    flex: 1 1 400px; /* 文字区最小宽度 400px，低于此值则自动触发换行，拒绝挤压 */
    text-align: left;
  }
  
  .profile-pic {
    flex: 0 0 auto;
    width: 320px;
    max-width: 100%;
    border-radius: 8px;
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