---
---
layout: home
title: หน้าหลักโครงการ
---

# ยินดีต้อนรับสู่ Documentation Project เฟอร์นิเจอร์

นี่คือศูนย์รวมเอกสารและข้อมูลด้านเทคนิคสำหรับ Engine คำนวณตู้ของเรา

## หัวข้อเอกสารหลัก
* [โครงสร้างตู้และการคำนวณวัสดุ](/topics/structure)
* [Shop Drawing และมาตรฐานการผลิต](/topics/shopdrawing)
<button onclick="calculateAndDisplay()" style="padding: 10px; background-color: #4CAF50; color: white; border: none; cursor: pointer;">
  คลิกเพื่อรัน Engine คำนวณ (2+2)
</button>

<p id="result-display" style="margin-top: 15px; font-weight: bold;">
  *ผลลัพธ์จะปรากฏที่นี่*
</p>
<script src="{{ site.baseurl }}/assets/js/engine.js"></script>
git add .
git commit -m "feat: Add JS calculation button to homepage"
git push

*เราจะสร้างเอกสารเหล่านี้ในหัวข้อถัดไป*