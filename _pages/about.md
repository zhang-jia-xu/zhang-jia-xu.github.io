---
permalink: /
title: "Welcome to my website!"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

<style>
  /* 核心对齐逻辑：彻底移除左侧空头像容器，消除它带来的隐形高度差 */
  .author__avatar {
    display: none !important;
  }

  /* ---------------- 以下仅保留主页关于照片的响应式排版（research页不需要加这段） ---------------- */
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
  
  @media (max-width: 1024px), (orientation: portrait) {
    .profile-wrap {
      flex-direction: column-reverse;
      align-items: center;            
    }
    .profile-text {
      padding-right: 0; 
      width: 100%;                    
    }
    .profile-pic {
      width: 100%; 
      max-width: 320px;               
      margin-bottom: 30px;            
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