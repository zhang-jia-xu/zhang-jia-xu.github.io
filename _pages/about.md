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
    margin-top: 8px !important; /* 调整这个数值：如果是负数就往上移，正数就往下移 */
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
  /* 当屏幕宽度小于 768px (手机端) 时执行以下排版 */
  @media (max-width: 768px) {
    .profile-wrap {
      flex-direction: column-reverse; /* 将照片调至文字上方 */
    }
    .profile-text {
      padding-right: 0; /* 取消右侧留白 */
    }
    .profile-pic {
      width: 100%; /* 照片宽度撑满手机屏幕 */
      max-width: 360px;
      margin-bottom: 20px;
      margin-top: 20px;
    }
  }
</style>

<div class="profile-wrap">
  <div class="profile-text">
    <p>I am a Ph.D. candidate in Management and Strategy at the University of Hong Kong. I obtained a Bachelor of Economics degree from Wuhan University and a Master of Economics degree from the University of Hong Kong.</p>
    
    <p>My research interests lie in international trade, organizational economics, and applied microeconomics. I am particularly interested in global sourcing and how firms can leverage their organizational form for supply chain reallocation.</p>
    
    <p>You can reach me at <a href="mailto:zhjiaxu@connect.hku.hk">zhjiaxu@connect.hku.hk</a>.</p>
    
  </div>

  <img class="profile-pic" src="/images/photo2.JPG">
</div>