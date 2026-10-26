---
permalink: /
title: "Welcome to my website!"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

<style>
  .page__title {
    margin-top: 8px !important; 
  }
  .profile-wrap {
    display: flex;
    align-items: flex-start;
    justify-content: space-between;
    margin-top: 30px;
  }
  .profile-text {
    flex: 1;
    padding-right: 40px;
    text-align: left;
  }
  .profile-pic {
    width: 360px;
    border-radius: 8px;
    flex-shrink: 0;
    margin-top: 5px;
  }
  
  /* 核心修复：针对手机、平板，以及任何竖向放置的显示器 */
  @media (max-width: 1024px), (orientation: portrait) {
    .profile-wrap {
      flex-direction: column-reverse; /* 照片在上，文字在下 */
      align-items: center;            /* 让照片在竖屏时居中，显得更规整 */
    }
    .profile-text {
      padding-right: 0; 
      width: 100%;                    /* 确保文字彻底释放，撑满整行宽度 */
    }
    .profile-pic {
      width: 100%; 
      max-width: 320px;               /* 竖屏下微调照片最大宽度，防止变得突兀和巨大 */
      margin-bottom: 30px;            /* 照片与文字之间的距离 */
      margin-top: 10px;
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