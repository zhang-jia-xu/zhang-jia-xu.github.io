---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

<style>
  /* 1. 常规横向电脑屏幕（横屏，且宽度较大） */
  @media (min-width: 1025px) and (orientation: landscape) {
    .page__title {
      margin-top: 8px !important; 
    }
  }

  /* 2. 竖向大显示器 / 平板电脑（竖屏，且宽度足以并排显示左右两列） */
  @media (min-width: 768px) and (orientation: portrait) {
    .page__title {
      margin-top: 24px !important; 
    }
  }

  /* 彻底隐藏左侧空头像占位符，消除基础误差 */
  .author__avatar {
    display: none !important;
  }

  /* 1. 限制点击区域，只包裹文字宽度，点空白处不再触发 */
  .abstract-summary {
    cursor: pointer;
    display: inline-flex;  /* 让它紧凑排列 */
    align-items: center;
    width: max-content;    /* 关键：宽度仅限文字大小，不拉伸到整行 */
    list-style: none;      /* 隐藏系统自带的默认小三角 */
  }
  .abstract-summary::-webkit-details-marker {
    display: none;         /* 针对苹果设备的隐藏 */
  }

  /* 2. 给小箭头单独加一个平滑的旋转动画 */
  .arrow-icon {
    display: inline-block;
    transition: transform 0.25s ease; /* 0.25秒的平滑转身 */
  }
  
  /* 3. 当菜单处于展开 (open) 状态时，箭头向下旋转 90 度 */
  details[open] .arrow-icon {
    transform: rotate(90deg);
  }

/* JMP 高亮标签专属样式 (白天模式/默认) */
  .jmp-tag {
    display: inline-block;
    background-color: #8b1c1c; /* 白天：沉稳的暗红色 */
    color: #ffffff;            /* 纯白文字 */
    font-size: 0.55em;         
    font-weight: 600;
    padding: 3px 8px;          
    border-radius: 4px;        
    vertical-align: middle;    
    margin-left: 10px;         
    position: relative;
    top: -2px;                 
    letter-spacing: 0.5px;
  }

  /* JMP 高亮标签 - 自动适配夜间模式 (Dark Mode) */
  @media (prefers-color-scheme: dark) {
    .jmp-tag {
      background-color: #e55353; /* 夜间：换成更明亮的亮红色/珊瑚红，防止和黑底融合 */
      color: #ffffff;            /* 文字保持白色 */
    }
  }
.coauthor {
    text-decoration: none !important; /* 强制去掉下划线 */
    border-bottom: none !important;   /* 强制去掉可能存在的边框下划线 */
    box-shadow: none !important;      /* 防止某些主题用阴影做下划线 */
  }
</style>

## Job Market Paper
**"Vertical Integration and the Sourcing Style"**, Oct 2026.

<details>
  <!-- <summary class="abstract-summary">
    <b>[ <span class="arrow-icon">&#9654;</span> Abstract ]</b>
    <span style="margin-left: 15px;"><b>[ <a href="mailto:zhjiaxu@connect.hku.hk?subject=Request for Draft: Vertical Integration and the Sourcing Style">Request Draft</a> ]</b></span>
  </summary> -->
  <summary class="abstract-summary">
    <b>[ <span class="arrow-icon">&#9654;</span> Abstract ]</b>
    <span style="margin-left: 15px;"><b>[ <a href="/files/paper_SourcingStyle.pdf">Working Paper</a> ]</b></span>
  </summary>
  
  <p style="margin-top: 10px; margin-bottom: 1.5em; text-align: left;">
  <i>I build a model of the boundary of the firm incorporating asset ownership to show how firms' organizational form and sourcing systems are complementary. I show that, given that both ``Japanese''-style and ``American''-style sourcing ensure similar quality levels, vertical integration and ``Japanese''-style sourcing are complementary. Sourcing from related parties is more likely to result in a long-term relationship with high-frequency shipments and small shipment sizes. Complementarity is stronger when the upstream firm's assets are more valuable and when the upstream firm is in an industry with greater quality differentiation. Combining the ORBIS data, which provides large-scale firm-to-firm ownership information, with the Panjiva data, which includes all the maritime firm-to-firm transaction records, I provide empirical evidence consistent with these theoretical predictions.</i>
  </p>
</details>

## Working Papers
**"Communication Costs, Direct Flights and International Trade"** (with <a href="https://www.furusawa.e.u-tokyo.ac.jp/home/" target="_blank" class="coauthor">Taiji Furusawa</a>, <a href="https://pweb.fbe.hku.hk/~sunc/" target="_blank" class="coauthor">Chang Sun</a>, and <a href="http://www.hwtang.com" target="_blank" class="coauthor">Heiwai Tang</a>), conditionally accepted, *Journal of International Economics*, Aug 2026.

<details>
  <summary class="abstract-summary">
    <b>[ <span class="arrow-icon">&#9654;</span> Abstract ]</b>
    <span style="margin-left: 15px;"><b>[ <a href="/files/paper_Airlines.pdf">Working Paper</a> ]</b></span>
  </summary>
  
  <p style="margin-top: 10px; margin-bottom: 1.5em; text-align: left;">
  <i>We build a general equilibrium model of endogenous communication, quality control, and trade. The model yields a structural gravity equation in which exogenous communication costs raise the probability of product failure and reduce trade more for products with a lower elasticity of substitution. We treat direct flight connectedness as a key determinant of communication costs and estimate its causal effect on trade using an instrument based on the discontinuity of direct flights at around 6,000 miles created by air travel regulations. Novel data on international business lawsuits show that air connectedness lowers the probability of product failure. Combining the estimates with the model, we quantify the aggregate impact of air connectedness in three episodes: the long-run improvement in air connectedness, the disruption of international travel during the COVID-19 pandemic, and the closure of Russian and Ukrainian airspace after the outbreak of the war in Ukraine.</i>
  </p>
</details>

**"Production and Ownership Networks"** (with <a href="https://sites.google.com/view/chengchenwebpage/home?authuser=0" target="_blank" class="coauthor">Cheng Chen</a>, <a href="https://pweb.fbe.hku.hk/~sunc/" target="_blank" class="coauthor">Chang Sun</a>, and <a href="https://www.rieti.go.jp/users/zhang-hong-yong/index_en.html" target="_blank" class="coauthor">Hongyong Zhang</a>), Nov 2025.

<details>
  <summary class="abstract-summary">
    <b>[ <span class="arrow-icon">&#9654;</span> Abstract ]</b>
    <span style="margin-left: 15px;"><b>[ <a href="/files/paper_TSR.pdf">Working Paper</a> ]</b></span>
  </summary>
  
  <p style="margin-top: 10px; margin-bottom: 1.5em; text-align: left;">
  <i>Using data on both buyer-supplier and owner-subsidiary links between Japanese firms, we characterize the interconnection between production and ownership networks. In the cross-section, we find that the majority of the owner-subsidiary links are also buyer-supplier links, highlighting the role of goods or services transactions in vertical relationships. In addition, we find that firms are more likely to use buyers/suppliers that are already adopted by related parties, suggesting an indirect benefit of integration.</i>
  </p>
</details>

---

## Work in Progress
**"Firm-specific Policy, Resource Allocation, and Optimal Tariffs"** (with <a href="https://pweb.fbe.hku.hk/~sunc/" target="_blank" class="coauthor">Chang Sun</a>).