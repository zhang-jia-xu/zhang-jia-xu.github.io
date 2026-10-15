---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

<style>
  /* 独立微调 Research 页面主标题的顶部位置（保留你之前的设置） */
  .page__title {
    margin-top: 8px !important; 
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
</style>

## Working Papers

**"Communication Costs, Direct Flights and International Trade"** <span class="jmp-tag">Job Market Paper</span> <br> (with Taiji Furusawa, Heiwai Tang, and Chang Sun), revise and resubmit, *Journal of International Economics*, Aug 2026.

<details>
  <summary class="abstract-summary">
    <b>[ <span class="arrow-icon">&#9654;</span> Abstract ]</b>
    <span style="margin-left: 15px;"><b>[ <a href="/files/paper_Airlines.pdf">Working Paper</a> ]</b></span>
  </summary>
  
  <p style="margin-top: 10px; margin-bottom: 1.5em; text-align: left;">
  <i>We build a general equilibrium model of endogenous communication, quality control, and trade. The model yields a structural gravity equation in which exogenous communication costs raise the probability of product failure and reduce trade more for products with a lower elasticity of substitution. We treat direct flight connectedness as a key determinant of communication costs and estimate its causal effect on trade using an instrument based on the discontinuity of direct flights at around 6,000 miles created by air travel regulations. Novel data on international business lawsuits show that air connectedness lowers the probability of product failure. Combining the estimates with the model, we quantify the aggregate impact of air connectedness in three episodes: the long-run improvement in air connectedness, the disruption of international travel during the COVID-19 pandemic, and the closure of Russian and Ukrainian airspace after the outbreak of the war in Ukraine.</i>
  </p>
</details>

**"Vertical Integration and the Sourcing Style"**, Sept 2026.
*Draft available upon request.*

<details>
  <summary class="abstract-summary">
    <b>[ <span class="arrow-icon">&#9654;</span> Abstract ]</b>
    <span style="margin-left: 15px;"><b>[ <a href="mailto:zhjiaxu@connect.hku.hk?subject=Request for Draft: Vertical Integration and the Sourcing Style">Request Draft</a> ]</b></span>
  </summary>
  
  <p style="margin-top: 10px; margin-bottom: 1.5em; text-align: left;">
  <i>I build a model of the boundary of the firm with asset ownership to show how firms can complement their organizational form by choosing different sourcing systems. I show that, given that both the "Japanese" style sourcing and the "American" style sourcing ensure similar quality levels, vertical integration and the "Japanese" style sourcing are complementary. Sourcing from related parties is more likely to result in a long-term relationship with high-frequency shipments and small shipment sizes. Complementarity is stronger when the asset of the upstream firm has greater value. Combining the ORBIS data, which has large-scale firm-to-firm ownership information, with the Panjiva data, which includes all the maritime firm-to-firm transaction records, I provide empirical evidence consistent with the above theoretical predictions.</i>
  </p>
</details>

**"Production and Ownership Networks"** (with Cheng Chen, Chang Sun, and Hongyong Zhang), Oct 2026.

<details>
  <summary class="abstract-summary">
    <b>[ <span class="arrow-icon">&#9654;</span> Abstract ]</b>
    <span style="margin-left: 15px;"><b>[ <a href="/files/paper_TSR.pdf">Working Paper</a> ]</b></span>
  </summary>
  
  <p style="margin-top: 10px; margin-bottom: 1.5em; text-align: left;">
  <i>Using data on both buyer-supplier and owner-subsidiary links between Japanese firms, we characterize the interconnection between production and ownership networks. In the cross-section, we find that the majority of the owner-subsidiary links are also buyer-supplier links, highlighting the role of goods or services transactions in vertical relationships. In addition, we find that firms are more likely to use buyers/suppliers that are already adopted by related parties, suggesting an indirect benefit of integration. We also select a subsample of incidental mergers, and employing propensity score matching with difference-in-differences methods, provid evidence of a causal inference regarding this effect. Leveraging industry heterogeneity among upstream firms, we argue that the ownership network facilitates the use of related-party suppliers by subsidiaries through the mechanism of reducing contractual frictions and search costs.</i>
  </p>
</details>

---

## Work in Progress
**"Firm-specific Policy, Resource Allocation, and Optimal Tariffs"** (with Chang Sun).