---
permalink: /
title: "Welcome to my website!"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

<style>
  /* 纯净的照片响应式排版，彻底删除所有 CSS 的高度干预 */
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

<script>
  /* 自动追踪对齐脚本：告别死像素，跨容器物理对齐 */
  function autoAlignTitle() {
    const leftName = document.querySelector('.author__name');
    const rightTitle = document.querySelector('.page__title');
    
    if (leftName && rightTitle) {
      // 1. 每次计算前先重置偏移，获取最原始的自然落差
      rightTitle.style.transform = 'none'; 
      
      // 2. 物理抓取左侧名字和右侧标题在屏幕上的绝对高度
      const leftRect = leftName.getBoundingClientRect();
      const rightRect = rightTitle.getBoundingClientRect();
      
      // 3. 只有当屏幕宽度足够（处于左右分栏状态）时，才执行平移对齐
      if (leftRect.right < rightRect.left) {
        const heightDiff = leftRect.top - rightRect.top;
        // 精确下推自然落差的距离
        rightTitle.style.transform = `translateY(${heightDiff}px)`;
      }
    }
  }

  // 页面加载完毕以及用户拉伸窗口、翻转屏幕时，自动执行计算
  window.addEventListener('load', autoAlignTitle);
  window.addEventListener('resize', autoAlignTitle);
</script>

<div class="profile-wrap">
  <div class="profile-text">
    <p>I am a Ph.D. candidate in Management and Strategy at the University of Hong Kong. I obtained a Bachelor of Economics degree from Wuhan University and a Master of Economics degree from the University of Hong Kong.</p>
    
    <p>My research interests lie in international trade, organizational economics, and applied microeconomics. My work primarily focuses on global sourcing, production networks, and supply chain reallocation, bridging theoretical models with both structural and reduced-form empirical analyses.</p>
    
    <p>You can reach me at <a href="mailto:zhjiaxu@connect.hku.hk">zhjiaxu@connect.hku.hk</a>.</p>
    
  </div>

  <img class="profile-pic" src="/images/photo2.JPG">
</div>