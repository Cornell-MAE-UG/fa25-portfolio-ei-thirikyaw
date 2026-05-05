---
layout: page
title: "SLF Crushers – Project X-termination"
permalink: /projects/slf-crushers/
---

# 🐝 Project X-termination of SLF
**Team:** SLF Crushers  
**Client(s):** Cornell CALS Extension / E&J Gallo Winery / National Grape  

---

## 📑 Table of Contents
- [Client Pitch](#client-pitch)
- [Functional Prototype](#functional-prototype)
- [Exhibit & Client Report](#exhibit-client-report)

---

## 🔷 Client Pitch
<a id="client-pitch"></a>

### Problem Statement
Vineyard growers face severe spotted lanternfly (SLF) infestations during the final three months before harvest, when grape sugar content is highest and fruit is most vulnerable. SLF cluster on vines and fruit, feeding on sap and producing honeydew that promotes mold and reduces yield.  

In heavily infested regions, losses can reach **30–50%**, often requiring repeated pesticide applications that increase labor and chemical costs. However, current removal methods—such as shaking, suction, brushing, or high-force airflow—risk damaging grapes or interfering with harvesting machinery.  

There is currently **no effective method to remove SLF during harvest without harming the crop**.

---

### Impact
This project focuses on removing spotted lanternflies while preserving grapevine health. Since SLF feeding weakens vines and reduces yield, any viable solution must eliminate insects **without damaging leaves, stems, or fruit**.

---

### Proposed Direction
Our long-term vision is a **cylindrical autonomous trap** approximately the height of vineyard trellises and ~2 feet in diameter.  

- Continuously rotating system  
- Attracts SLF away from vines  
- Guides insects into a containment chamber  

For this milestone, we developed a **scaled prototype** using:
- 3D printed components  
- Servo motors  
- Attractant solutions  
- Controlled rotational motion  

---

### Concept
**How it works:**
1. Attractants (scent, sound, sugary sap) lure SLF  
2. Entry or triggered intake draws insects inside  
3. Rotating blade guides them inward  
4. Central chamber captures and eliminates them  

**Why it’s better:**
- Non-destructive to crops  
- Low maintenance  
- Compatible with vineyard operations  

---

### Key Risks / Unknowns

**1. Competitive Attraction Failure**  
SLF may prefer real grapevines over artificial lures  
- *Test:* Compare SLF attraction between vines vs. trap  

**2. SLF Evasion**  
Rotation may trigger escape behavior  
- *Test:* Optimize rotational speed using video analysis  

---

### Client Questions
- Vineyard spacing constraints?  
- Can traps be moved during harvesting?  
- Restrictions on organic/food-safe attractants?  

---

### References
- [Penn State SLF Research](https://www.psu.edu/news/research/story/lanternflys-attraction-vertical-silhouettes-could-help-monitor-trap-it)  
- [Cornell SLF Management](https://cals.cornell.edu/integrated-pest-management/outreach-education/whats-bugging-you/spotted-lanternfly)  
- [Union County SLF Info](https://ucnj.org/slf/)  
- [SLF Trap Guide](https://extension.psu.edu/how-to-build-a-spotted-lanternfly-circle-trap)  

---

## 🔷 Functional Prototype
<a id="functional-prototype"></a>

### Purpose
The prototype was designed to test whether a **rotating mechanical system can effectively attract, guide, and capture spotted lanternflies (SLF)** while preserving grapevine integrity.

---

### What Was Tested
We evaluated three primary subsystems:

- **Guidance Performance Index (GPI)** – Ability to move SLF toward the center  
- **Capture Rate Index (CRI)** – Effectiveness of containment  
- **Rotational Stability Index (RSI)** – Consistency and reliability of motion  

Testing focused on how rotational motion and geometry influence insect behavior and capture efficiency.

---

### Results / Outcomes
- **GPI:** 93.0  
- **CRI:** 92.5  
- **RSI:** 85.0  

✅ The system successfully:
- Guided insects inward with high consistency  
- Achieved strong capture performance  
- Maintained continuous operation with minimal intervention  

Performance improvements were achieved through:
- Alignment corrections  
- Friction reduction  
- Incremental mechanical tuning  

---

### Key Insights
- Rotational motion can effectively **control insect movement without direct force**
- Small mechanical adjustments produced **significant performance gains**
- Stability is important but not critical at prototype scale  

---

### Limitations
- Prototype is **scaled down**
- Not tested in real vineyard environments  
- Attractant effectiveness still being validated  

---

### Next Steps
- Scale to vineyard-sized system  
- Conduct field testing  
- Optimize attractants  
- Improve rotational stability  

---

## 🧪 Exhibit & Client Report
<a id="exhibit-client-report"></a>

### Exhibit (What Was Demonstrated)
The prototype was presented as a **working physical exhibit** demonstrating:

- Continuous rotational operation  
- Guided movement of insects toward a central collection region  
- Successful transfer into a containment chamber  

The exhibit visually communicated how **mechanical motion alone can influence SLF behavior**, supporting the feasibility of a non-destructive trapping method.

---

### Client-Focused Results
From a client perspective (Cornell CALS Extension / Gallo Winery), the prototype demonstrated:

- ✔ **Feasibility:** The concept works as a functional system  
- ✔ **Effectiveness:** High guidance and capture rates (>90%)  
- ✔ **Scalability potential:** Design can be expanded to vineyard scale  

---

### Engineering Validation
The prototype validated key design assumptions:

- Rotating systems can replace high-force removal methods  
- Controlled motion reduces risk of crop damage  
- Mechanical guidance can outperform passive trapping approaches  

These findings support continued development toward a **field-deployable agricultural device**.

---

### Client Takeaways
- The design aligns with the need for **non-destructive SLF removal**
- System shows promise for **reducing pesticide reliance**
- Further development is justified based on strong prototype performance  

---

### Supporting Materials
- 🌐 [Full Project Site](https://alicepark0703.github.io/slf-crushers-mae2250/)
- 📄 [Client Report / Documentation](https://docs.google.com/document/d/1pr_hIzGqb1cMbX0hKJa9c80RG8Kt0VbS1zQ42y45qvE/edit?usp=sharing)

---

## 🎨 (Optional) Clean Styling
Add this to your CSS file (`assets/css/style.scss`) if you want a nicer look:

```css
h1, h2, h3 {
  margin-top: 1.5em;
}

a {
  text-decoration: none;
  color: #2a7ae2;
}

a:hover {
  text-decoration: underline;
}

ul {
  line-height: 1.6;
}

hr {
  margin: 2em 0;
}