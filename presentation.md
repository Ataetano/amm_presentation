---

marp: true
theme: academic
paginate: false
style: |
  .container {
    display: flex;
    width: 100%;
    height: 100%;
    justify-content: space-between;
    gap: 100px;
  }
  .column {
    flex: 1;
    padding: 0 0px;
  }
  img[alt~="center"] {
    display: block;
    margin: 0 auto;
  }
  svg[id^="mermaid-"] { 
    min-width: 550px; 
    max-width: 960px; 
    min-height: 400px; 
    max-height: 500px;
  }

---
<!-- _class: lead -->

<!-- <img src="img/math_logo.png" width="15%" /> -->
<!-- ![bg left:33% h:300px ](img/math_logo.png) -->

![bg blur:8px sepia:0.7](img/AI-Violin.gif)

<h1 style="color: white;"> A Chaos-Driven Approach to Augmenting and Enriching Symbolic Music Datasets </h1>

<!-- <div class="highlighted-text-shadow" style="text-align: left; background-color: blue;">
through Chaotic Dynamical Systems Exploration
</div>  -->

<br>

<div class="highlighted-text-shadow">
Kanatsanun Sub-udom <br>
Pichate Kunakornvong  <br>
Ratthaprom Promkam
</div> 

<br>

<!-- **21 May 2025** -->

---

<!-- header: Overview -->

![bg](img/problem1.png)

---

![bg](img/problem2.png)

---

<!-- header: Chaos-Driven Variation Method -->

<!-- <center>
<br>
<br>
<br>
<br>
<h1> Chaos-Driven </h1>
<center>

--- -->

![bg center](img/1.jpg)

---

![bg center](img/2.jpg)

---

![bg center](img/3.jpg)

---

![bg center](img/4.jpg)

---

![bg center](img/5.jpg)

---


![center h:600px](img/ov_beta1.png)

---

![center h:600px](img/ov_beta2.png)

---

![center h:600px](img/ov_beta3.png)

---

![bg center](img/6.jpg)

---

![center h:600px](img/ov_beta4.png)

---

![center h:600px](img/ov_beta5.png)

---

![bg center](img/7.jpg)

---

![center h:600px](img/ov_beta6.png)

---

![center h:600px](img/ov_beta7.png)

---

![bg center](img/8.jpg)

---

![center h:600px](img/ov_beta8.png)

---

![center h:600px](img/ov_beta9.png)

---

![bg center](img/9.jpg)

---

![center h:600px](img/ov_beta10.png)

---

![center h:600px](img/ov_beta11.png)

---

![bg center](img/10.jpg)

---

Following the mapping, we obtain:

$$
\beta(\tilde{\phi}(kh)) :=
\begin{cases}
\alpha(\phi(b)) & \text{if } \exists a, b \in \text{dom }(\phi; m, h) \text{ s.t. } \phi(a) < \tilde{\phi}_1(kh) \leq \phi(b) \\
& \text{and } \nexists c \in \text{dom }(\phi; m, h) \text{ s.t. } \phi(a) < \phi(c) \leq \phi(b), \\
\alpha(\min\{\phi(t)\}) & \text{if } \tilde{\phi}_1(kh) < \phi(t) \text{ for all } t \in \text{dom }(\phi; m, h), \\
\alpha(\max\{\phi(t)\}) & \text{if } \phi(t) < \tilde{\phi}_1(kh) \text{ for all } t \in \text{dom }(\phi; m, h),
\end{cases}
$$
where 
$$
\begin{aligned}
\text{dom }(\phi; m, h) &= \{0, 0.01, 0.02, \dots, (m - 1)h\}
\end{aligned}
$$

--- 

<!-- header: Chaos-Driven Variation Method with Rhythm Expansion -->

$$ 
{\small
\begin{aligned}
\{p_k\}_{k=0}^{4} &= \{C4, C4, G4, A4, F4\} \\[1em]
\end{aligned}
}
$$

---

$$ 
{\small
\begin{aligned}
\{p_k\}_{k=0}^{4} &= \{C4, C4, G4, A4, F4\} \\[1em]
&\Downarrow \textbf{(Expanded Symbolic Music Data)} \\[1em]
\{p^*_k\}_{k=0}^{9} &= \{C4, C4, C4, C4, G4, G4, A4, A4, F4, F4\} \\[1em]
\end{aligned}
}
$$

---

$$ 
{\small
\begin{aligned}
\{p_k\}_{k=0}^{4} &= \{C4, C4, G4, A4, F4\} \\[1em]
&\Downarrow \textbf{(Expanded Symbolic Music Data)} \\[1em]
\{p^*_k\}_{k=0}^{9} &= \{C4, C4, C4, C4, G4, G4, A4, A4, F4, F4\} \\[1em]
&\Downarrow \text{(Chaos-Driven Variation Method)} \\[1em]
\{p^\prime_k\}_{k=0}^{9} &= \{G4, C4, A4, G4, F4, F4, C4, C4, F4, C4\} \\[1em]
\end{aligned}
}
$$

---

$$ 
{\small
\begin{aligned}
\{p_k\}_{k=0}^{4} &= \{C4, C4, G4, A4, F4\} \\[1em]
&\Downarrow \textbf{(Expanded Symbolic Music Data)} \\[1em]
\{p^*_k\}_{k=0}^{9} &= \{C4, C4, C4, C4, G4, G4, A4, A4, F4, F4\} \\[1em]
&\Downarrow \text{(Chaos-Driven Variation Method)} \\[1em]
\{p^\prime_k\}_{k=0}^{9} &= \{G4, C4, A4, G4, F4, F4, C4, C4, F4, C4\} \\[1em]
&\Downarrow \textbf{(Reduced Symbolic Music Data)} \\[1em]
\{\dot{p}_k\}_{k=0}^{4} &= \{G4, A4, F4, C4, F4\}
\end{aligned}
}
$$

---

<!-- header: Showcases -->

<br>
<br>
<br>
<br>
<center>
  Pachelbell - Canon In D
</center>
<div class="container">
  <div class="column">
    <center>
    <h6>Original</h6>
    <br>
      <audio controls>
        <source src="mp3/Johann_Pachelbel_Canon_in_D_original.mp3" type="audio/mpeg">
        Your browser does not support the audio element.
      </audio>
    </center>
  </div>
  <div class="column">
    <center>
    <h6>Variation</h6>
    <br>
      <audio controls>
        <source src="mp3/Johann_Pachelbel_Canon_in_D_new.mp3" type="audio/mpeg">
        Your browser does not support the audio element.
      </audio>
    </center>
  </div>
</div>

---


<br>
<br>
<br>
<br>
<center>
  Yiruma, (이루마) - River Flows in You
</center>
<div class="container">
  <div class="column">
    <center>
    <h6>Original</h6>
    <br>
      <audio controls>
        <source src="mp3/River_Flows_In_You_original.mp3" type="audio/mpeg">
        Your browser does not support the audio element.
      </audio>
    </center>
  </div>
  <div class="column">
    <center>
    <h6>Variation</h6>
    <br>
      <audio controls>
        <source src="mp3/River_Flows_In_You_new.mp3" type="audio/mpeg">
        Your browser does not support the audio element.
      </audio>
    </center>
  </div>
</div>

---

https://ataetano.github.io/amm_presentation/presentation.html#1