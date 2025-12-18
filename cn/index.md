---
layout: home
title: 嘉美技术株式会社
nav: cn
classes: wide
---

<!-- =========================
 Hero 区（首页头图）
 去掉公司名，只保留价值主张
 加深色遮罩，保证文字清晰
========================= -->

<div class="page__hero--overlay"
     style="background-image: url('/assets/images/cn-hero.jpg');">

  <div class="wrapper"
       style="background: rgba(0,0,0,0.45); padding: 4em 2em; text-align: center;">

    <p class="page__lead"
       style="color: #ffffff; font-size: 1.4em; margin: 0;">
      小微企业数字化转型的长期伙伴
    </p>

  </div>
</div>

---

<!-- =========================
 业务介绍区
 使用 Minimal Mistakes 官方 feature_row
 固定 2 × 2，不会乱
========================= -->

## 我们的服务

{% feature_row %}

---

<!-- =========================
 feature_row 内容定义
========================= -->
{% assign feature_row = site.data.feature_cn %}

