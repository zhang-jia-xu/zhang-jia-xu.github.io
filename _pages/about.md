---
permalink: /
title: "Welcome to my website!"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

<style>
  /* 1. 彻底隐藏左侧空头像占位符 */
  .author__avatar {
    display: none !important;
  }
  
  /* 2. 消除左侧名字自带的顶部推力（防止内部错位） */
  .author__name {
    margin-top: 0 !important;
  }

  /* 3. 终极水平对齐：强制左侧信息区和右侧大标题拥有完全相同的、舒适的顶部距离 */
  .author__profile, .page__title {
    margin-top: 30px !important; 
    padding-top: 0 !important;
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
  
  /* 针对手机、平板及竖屏的响应式优化 */
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