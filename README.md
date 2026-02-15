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

/* ---------- 2x4 YouTube grid ---------- */
.yt-grid{
  display:grid;
  grid-template-columns:repeat(2,1fr);
  gap:28px;
  max-width:900px;
  margin:0 auto;
}
.yt-card{
  text-align:center;
}
.yt-card:last-child{
  grid-column:1 / -1;
  justify-self:center;
  width:50%;
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

.main-title{
  display:flex;
  align-items:center;
  justify-content:center;
  gap:8px;
}

.main-title img{
  height:2.5em;
  transform:translateY(2px);
}

</style>
</head>

<body>

<div class="container">
<h1 class="main-title">
  <img src="icon.png" alt="logo">
  OpenClaw: A Wrist-Frame Fingertip Force Sensing Hand for Contact-Rich Removal Manipulation
</h1>

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

<div class="section">
  <h2>Abstract</h2>
  <p>
  We introduce OpenClaw, an open three-finger hand with modular three-axis fingertip force sensing and a wrist-frame multi-finger force representation, together with a nine-task contact-rich removal manipulation suite spanning adhesive detachment, cleaning, self-cleaning, and occluded retrieval. We evaluate a unified ACT-based imitation learning policy conditioned on RGB, joint state, and wrist-frame fingertip forces under strict success criteria and held-out real-robot tests, and use controlled ablations to quantify the contribution of wrist-frame force sensing in sequential contact interactions under uncertainty.
  </p>
</div>

<div id="video" class="section">
  <h2>Project Video</h2>
  <div class="video">
    <iframe src="https://www.youtube.com/embed/fToNWljt--Q" allowfullscreen></iframe>
  </div>
</div>

<div class="section">
  <h2>OpenClaw for Contact-Rich Removal Manipulation</h2>
  <img src="teaser.png" class="teaser" alt="teaser image">
  <p class="caption">
  OpenClaw performs contact-rich removal behaviors (e.g., detachment and cleaning) by conditioning an ACT-based imitation learning policy on RGB, joint state, and wrist-frame multi-finger fingertip forces, enabling progressive debonding and sequential contact under uncertainty.
  </p>
</div>

<div class="section">
  <h2>Multimodal ACT Policy with Wrist-Frame Forces</h2>
  <img src="framework.png" class="teaser" alt="teaser image">
  <p class="caption">
  We express each fingertip force in a common wrist frame (via forward kinematics), encode RGB / joint state / contact forces, and predict an action chunk using an Action Chunking Transformer for robust contact-rich control.
  </p>
</div>

<div class="section">
  <h2>OpenClaw Platform and Real-Robot Evaluation Setup</h2>
  <img src="platform.png" class="teaser" alt="teaser image">
  <p class="caption">
  A leader–follower OpenClaw setup with multi-view cameras supports demonstration collection and held-out real-robot evaluation; inset shows the modular three-axis fingertip force sensor used for contact feedback.
  </p>
</div>


<!-- ===== 3x3 YouTube hover grid (before teaser) ===== -->
<div class="section">
<h2>Results Highlights</h2>
<div class="yt-grid">

<div class="yt-card"><div class="yt-wrap">
<iframe src="https://www.youtube.com/embed/yExUtIoSRzw?autoplay=1&mute=1&loop=1&playlist=yExUtIoSRzw&controls=0&rel=0&modestbranding=1" allow="autoplay"></iframe>
</div><div class="yt-label">A1: Barnacle removal </div></div>

<div class="yt-card"><div class="yt-wrap">
<iframe src="https://www.youtube.com/embed/cD3NlRmJ6lw?autoplay=1&mute=1&loop=1&playlist=cD3NlRmJ6lw&controls=0&rel=0&modestbranding=1" allow="autoplay"></iframe>
</div><div class="yt-label">A2: 3D-print removal</div></div>

<div class="yt-card"><div class="yt-wrap">
<iframe src="https://www.youtube.com/embed/rsJYUgpaC-I?autoplay=1&mute=1&loop=1&playlist=rsJYUgpaC-I&controls=0&rel=0&modestbranding=1" allow="autoplay"></iframe>
</div><div class="yt-label">A3: Blu-Tack removal</div></div>

<div class="yt-card"><div class="yt-wrap">
<iframe src="https://www.youtube.com/embed/hTsSUf5eFuc?autoplay=1&mute=1&loop=1&playlist=hTsSUf5eFuc&controls=0&rel=0&modestbranding=1" allow="autoplay"></iframe>
</div><div class="yt-label">A4: Wood-ear extraction</div></div>

<div class="yt-card"><div class="yt-wrap">
<iframe src="https://www.youtube.com/embed/X9mF51GZDHo?autoplay=1&mute=1&loop=1&playlist=X9mF51GZDHo&controls=0&rel=0&modestbranding=1" allow="autoplay"></iframe>
</div><div class="yt-label">A5: Self-cleaning</div></div>

<div class="yt-card"><div class="yt-wrap">
<iframe src="https://www.youtube.com/embed/fToNWljt--Q?autoplay=1&mute=1&loop=1&playlist=fToNWljt--Q&controls=0&rel=0&modestbranding=1" allow="autoplay"></iframe>
</div><div class="yt-label">B1: Plate wiping</div></div>

<div class="yt-card"><div class="yt-wrap">
<iframe src="https://www.youtube.com/embed/fToNWljt--Q?autoplay=1&mute=1&loop=1&playlist=fToNWljt--Q&controls=0&rel=0&modestbranding=1" allow="autoplay"></iframe>
</div><div class="yt-label">B2: Hand wiping</div></div>

<div class="yt-card"><div class="yt-wrap">
<iframe src="https://www.youtube.com/embed/fToNWljt--Q?autoplay=1&mute=1&loop=1&playlist=fToNWljt--Q&controls=0&rel=0&modestbranding=1" allow="autoplay"></iframe>
</div><div class="yt-label">C1: Sand excavation</div></div>

<div class="yt-card"><div class="yt-wrap">
<iframe src="https://www.youtube.com/embed/fToNWljt--Q?autoplay=1&mute=1&loop=1&playlist=fToNWljt--Q&controls=0&rel=0&modestbranding=1" allow="autoplay"></iframe>
</div><div class="yt-label">C2: Cat litter removal</div></div>

</div>
</div>



<div class="section">
  <h2>Citation</h2>
  <pre>
@article{openclaw2026,
title={OpenClaw: A Wrist-Frame Fingertip Force Sensing Hand for Contact-Rich Removal Manipulation},
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


</body>
</html>
