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
    .page__title {
      margin-top: 8px !important; /* 你之前在横屏测试完美的数值 */
    }
  }

  /* 2. 竖向大显示器 / 平板电脑（竖屏，且宽度足以并排显示左右两列） */
  @media (min-width: 768px) and (orientation: portrait) {
    .page__title {
      /* 请在你的大竖屏上用审查元素测试，填入能让它对齐的精确数值（如 20px 或 24px） */
      margin-top: 24px !important; 
    }
  }

  /* 彻底隐藏左侧空头像占位符，消除基础误差 */
  .author__avatar {
    display: none !important;
  }

  /* ---------------- 下方保留你的照片响应式排版 ---------------- */
  .profile-wrap {
    display: flex;
    align-items: flex-start;
    justify-content: space-between;
    margin-top: 30px;
    gap: 30px; /* 添加 gap 增加呼吸感 */
  }
  .profile-text {
    flex: 1;
    text-align: left;
  }
  .profile-pic {
    width: 320px; /* 桌面端稍微把照片调小一点，给文字留更多空间 */
    border-radius: 8px;
    flex-shrink: 0;
    margin-top: 5px;
  }
  
  /* 关键修改：将断点扩大到 1024px，让 iPad (横/竖屏) 也采用上下堆叠，释放文字宽度 */
  @media (max-width: 1024px) {
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