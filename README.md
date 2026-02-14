<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="utf-8">
<title>OpenClaw Project Page</title>
<meta name="viewport" content="width=device-width, initial-scale=1">

<style>
body{
  font-family:-apple-system,BlinkMacSystemFont,"Segoe UI",Roboto,Helvetica,Arial,sans-serif;
  margin:0;
  background:#fff;
  color:#222;
  line-height:1.65;
}

.container{
  max-width:900px;
  margin:auto;
  padding:50px 20px;
}

h1{
  font-size:3.0em;
  text-align:center;
  margin-bottom:15px;
  line-height:1.25;
  font-weight:600;
}

.authors{
  text-align:center;
  font-size:1.15em;
  margin-bottom:6px;
}

.authors span{
  margin:0 6px;
}

.affiliation{
  text-align:center;
  color:#666;
  margin-bottom:28px;
}

.links{
  text-align:center;
  margin:30px 0 20px 0;
}

.links a{
  display:inline-block;
  margin:6px;
  padding:11px 20px;
  border-radius:9px;
  text-decoration:none;
  color:white;
  background:#2d6cdf;
  font-weight:600;
  font-size:15px;
  transition:.2s;
}

.links a:hover{
  background:#1b4fb3;
  transform:translateY(-1px);
}

.section{
  margin-top:55px;
}

h2{
  border-bottom:2px solid #eee;
  padding-bottom:6px;
  font-weight:600;
}

.video{
  position:relative;
  padding-bottom:56.25%;
  height:0;
  overflow:hidden;
  border-radius:12px;
  box-shadow:0 4px 18px rgba(0,0,0,.08);
}

.video iframe{
  position:absolute;
  top:0;
  left:0;
  width:100%;
  height:100%;
  border:0;
}

.teaser{
  width:100%;
  border-radius:12px;
  box-shadow:0 4px 18px rgba(0,0,0,.08);
}

p{
  font-size:17px;
}

ul{
  font-size:17px;
  padding-left:22px;
}

pre{
  background:#f6f6f6;
  padding:18px;
  overflow-x:auto;
  border-radius:10px;
  font-size:14px;
}

.footer{
  text-align:center;
  margin-top:70px;
  font-size:.9em;
  color:#888;
}

/* ---------- 3x3 YouTube grid ---------- */
.yt-grid{
  display:grid;
  grid-template-columns:repeat(3,1fr);
  gap:18px;
  margin-bottom:35px;
}

.yt-card{
  text-align:center;
}

.yt-wrap{
  position:relative;
  width:100%;
  padding-bottom:56.25%; /* 16:9 */
  border-radius:12px;
  overflow:hidden;
  box-shadow:0 4px 18px rgba(0,0,0,.08);
  background:#000;
  cursor:pointer;
}

.yt-wrap iframe{
  position:absolute;
  inset:0;
  width:100%;
  height:100%;
  border:0;
}

.yt-label{
  margin-top:6px;
  font-size:14px;
  font-weight:600;
  color:#333;
}

/* mobile */
@media (max-width:700px){
  .yt-grid{
    grid-template-columns:repeat(2,1fr);
  }
}
</style>
</head>

<body>

<div class="container">

<h1>OpenClaw: Wrist-Frame Fingertip Force Sensing Hand for Contact-Rich Removal Manipulation</h1>

<div class="authors">
  <span>Author1</span> ·
  <span>Author2</span> ·
  <span>Author3</span> ·
  <span>Author4</span>
</div>

<div class="affiliation">
  University / Lab Name
</div>

<div class="links">
  <a href="#">Paper</a>
  <a href="#video">Video</a>
  <a href="#">Code</a>
  <a href="#">Dataset</a>
  <a href="#">Hardware</a>
</div>

<!-- ===== 3x3 YouTube hover grid (before teaser) ===== -->
<div class="section">
<div class="yt-grid">

  <div class="yt-card">
    <div class="yt-wrap">
      <iframe class="yt-hover" data-id="fToNWljt--Q"></iframe>
    </div>
    <div class="yt-label">A1</div>
  </div>

  <div class="yt-card">
    <div class="yt-wrap">
      <iframe class="yt-hover" data-id="fToNWljt--Q"></iframe>
    </div>
    <div class="yt-label">A2</div>
  </div>

  <div class="yt-card">
    <div class="yt-wrap">
      <iframe class="yt-hover" data-id="fToNWljt--Q"></iframe>
    </div>
    <div class="yt-label">A3</div>
  </div>

  <div class="yt-card">
    <div class="yt-wrap">
      <iframe class="yt-hover" data-id="fToNWljt--Q"></iframe>
    </div>
    <div class="yt-label">A4</div>
  </div>

  <div class="yt-card">
    <div class="yt-wrap">
      <iframe class="yt-hover" data-id="fToNWljt--Q"></iframe>
    </div>
    <div class="yt-label">A5</div>
  </div>

  <div class="yt-card">
    <div class="yt-wrap">
      <iframe class="yt-hover" data-id="fToNWljt--Q"></iframe>
    </div>
    <div class="yt-label">B1</div>
  </div>

  <div class="yt-card">
    <div class="yt-wrap">
      <iframe class="yt-hover" data-id="fToNWljt--Q"></iframe>
    </div>
    <div class="yt-label">B2</div>
  </div>

  <div class="yt-card">
    <div class="yt-wrap">
      <iframe class="yt-hover" data-id="fToNWljt--Q"></iframe>
    </div>
    <div class="yt-label">C1</div>
  </div>

  <div class="yt-card">
    <div class="yt-wrap">
      <iframe class="yt-hover" data-id="fToNWljt--Q"></iframe>
    </div>
    <div class="yt-label">C2</div>
  </div>

</div>

</div>


<div class="section">
  <img src="teaser.png" class="teaser" alt="teaser image">
</div>

<div id="video" class="section">
  <h2>Video</h2>
  <div class="video">
    <iframe src="https://www.youtube.com/embed/fToNWljt--Q" allowfullscreen></iframe>
  </div>
</div>

<div class="section">
  <h2>Abstract</h2>
  <p>
    We study contact-rich removal manipulation, where objects must be detached,
    peeled, or extracted through sequential interactions under partial observability.
    We introduce OpenClaw, a three-finger robotic hand with modular fingertip force
    sensing and wrist-frame force representation, together with a nine-task real-robot
    evaluation suite. Experiments show that wrist-frame force sensing improves stability
    and generalization in removal tasks compared to local-frame sensing and vision-only baselines.
  </p>
</div>

<div class="section">
  <h2>Highlights</h2>
  <ul>
    <li>First real-robot benchmark suite for removal manipulation</li>
    <li>Wrist-frame force representation improves policy stability</li>
    <li>Nine-task evaluation with held-out generalization</li>
    <li>Open-source hardware platform for reproducible experiments</li>
  </ul>
</div>

<div class="section">
  <h2>Overview</h2>
  <p>
    OpenClaw is designed for studying contact-rich manipulation where interaction
    forces, occlusions, and sequential state transitions play a central role.
    The system integrates fingertip force sensing, a unified representation,
    and a multimodal policy, enabling reproducible evaluation across diverse
    removal scenarios.
  </p>
</div>

<div class="section">
  <h2>Citation</h2>
  <pre>
@article{openclaw2026,
title={OpenClaw: Wrist-Frame Fingertip Force Sensing Hand for Contact-Rich Removal Manipulation},
author={Author1 and Author2 and Author3},
journal={Under Review},
year={2026}
}
  </pre>
</div>

<div class="footer">
  Project page template for robotics research papers
</div>

</div>



<script>
document.querySelectorAll(".yt-hover").forEach(frame=>{
  const id = frame.dataset.id;

  const preview =
    `https://www.youtube.com/embed/${id}?mute=1&controls=0&rel=0&modestbranding=1&loop=1&playlist=${id}`;

  const play =
    preview + "&autoplay=1";

  frame.src = preview;

  const box = frame.closest(".yt-wrap");

  box.addEventListener("mouseenter", ()=>{
    frame.src = play;
  });

  box.addEventListener("mouseleave", ()=>{
    frame.src = preview;
  });
});
</script>

</body>
</html>
