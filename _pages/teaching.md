---
title:  "Teaching"
date:   2024-11-18 16:00:00 -0500
permalink: /teaching/
---

![Becker](/assets/images/\Becker.jpg)

## Courses

<button class="accordion">History of Capitalism</button>
<div class="panel">
  <a href="/lectures/hoc_1.html">Lecture 1: The World the Market Made</a>
  <a href="/lectures/hoc_2.html">Lecture 2: Slavery and the Balance Sheet</a>
  <a href="/lectures/hoc_3.html">Lecture 3: Railroads and Risk</a>
</div>

<button class="accordion">Comparative Political Economy</button>
<div class="panel">
  <a href="/lectures/cpe_1.html">Lecture 1: State and Market</a>
  <a href="/lectures/cpe_2.html">Lecture 2: Institutions and Inequality</a>
</div>

## Various Talks and Lectures

- [**Institutions and Economic Growth**](/assets/documents/UR_Institutions_Growth.pdf)  
- [**The Great Depression**](/assets/documents/GreatDepression.pdf)
- [**Are Markets Efficient?**](/assets/documents/MC_5_Efficiency.pdf)
- [**Are Market Outcomes Fair?**](/assets/documents/MC_4_Inequality.pdf)

<style>
  .accordion {
    cursor: pointer;
    padding: 15px;
    width: 100%;
    text-align: left;
    border: none;
    outline: none;
    transition: 0.3s;
    font-size: 18px;
    background-color: #f1f1f1;
    margin-top: 10px;
  }

  .accordion.active, .accordion:hover {
    background-color: #e2e2e2;
  }

  .panel {
    padding: 0 15px;
    display: none;
    background-color: #fafafa;
    overflow: hidden;
    border-left: 3px solid #ccc;
  }

  .panel a {
    display: block;
    padding: 8px 0;
    color: #336699;
    text-decoration: none;
  }

  .panel a:hover {
    text-decoration: underline;
  }
</style>

<script>
  document.addEventListener("DOMContentLoaded", function() {
    const acc = document.querySelectorAll(".accordion");
    acc.forEach(button => {
      button.addEventListener("click", () => {
        button.classList.toggle("active");
        const panel = button.nextElementSibling;
        panel.style.display = panel.style.display === "block" ? "none" : "block";
      });
    });
  });
</script>
