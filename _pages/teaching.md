---
title:  "Teaching"
date:   2024-11-18 16:00:00 -0500
permalink: /teaching/
---
![Becker](/assets/images/\Becker.jpg)



<button class="accordion">Section 1</button>
<div class="panel">
  <p>Lorem ipsum...</p>
</div>


.accordion {
  background-color: #eee;
  color: #444;
  cursor: pointer;
  padding: 18px;
  width: 100%;
  text-align: left;
  border: none;
  outline: none;
  transition: 0.4s;
}


.active, .accordion:hover {
  background-color: #ccc;
}

.panel {
  padding: 0 18px;
  background-color: white;
  display: none;
  overflow: hidden;
}

var acc = document.getElementsByClassName("accordion");
var i;

for (i = 0; i < acc.length; i++) {
  acc[i].addEventListener("click", function() {
    /* Toggle between adding and removing the "active" class,
    to highlight the button that controls the panel */
    this.classList.toggle("active");

    /* Toggle between hiding and showing the active panel */
    var panel = this.nextElementSibling;
    if (panel.style.display === "block") {
      panel.style.display = "none";
    } else {
      panel.style.display = "block";
    }
  });
}

## Various Talks and Lectures

- [**Institutions and Economic Growth**](/assets/documents/UR_Institutions_Growth.pdf)  
- [**The Great Depression**](/assets/documents/GreatDepression.pdf)
- [**Are Markets Efficient?**](/assets/documents/MC_5_Efficiency.pdf)
- [**Are Market Outcomes Fair?**](/assets/documents/MC_4_Inequality.pdf)



