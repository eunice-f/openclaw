<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="utf-8">
<title>OpenClaw Project Page</title>
<meta name="viewport" content="width=device-width, initial-scale=1">

<style>

/* ---------- global ---------- */
*,
*::before,
*::after{
  box-sizing:border-box;
}

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
  font-size:3em;
  margin-bottom:15px;
  line-height:1.25;
  font-weight:600;
}

.main-title{
  display:flex;
  align-items:center;
  justify-content:center;
  gap:9px;
}

.main-title img{ height:2.5em; }

.authors{
  text-align:center;
  font-size:1.15em;
}

.affiliation{
  text-align:center;
  color:#666;
  margin-bottom:28px;
}

/* ---------- buttons ---------- */
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

.links a.disabled{
  pointer-events:none;
  cursor:default;
  opacity:.45;
}

/* ---------- sections ---------- */
.section{ margin-top:55px; }

h2{
  border-bottom:2px solid #eee;
  padding-bottom:6px;
  font-weight:600;
}

p{ font-size:17px; }

/* ---------- KPI cards (FIXED) ---------- */
.kpi{
  display:grid;
  grid-template-columns:repeat(auto-fit,minmax(220px,1fr));
  gap:14px;
  margin-top:22px;
}

.kpi .card{
  border:1px solid #eee;
  border-radius:12px;
  padding:16px;
  background:#fff;
  box-shadow:0 4px 18px rgba(0,0,0,.05);
}

.kpi .big{
  font-size:20px;
  font-weight:700;
}

.kpi .small{
  font-size:13px;
  color:#666;
  margin-top:6px;
}

/* ---------- video ---------- */
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
  inset:0;
  width:100%;
  height:100%;
  border:0;
}

/* ---------- images ---------- */
.teaser{
  width:100%;
  border-radius:12px;
  box-shadow:0 4px 18px rgba(0,0,0,.08);
}

/* ---------- video grid ---------- */
.yt-grid{
  display:grid;
  grid-template-columns:repeat(2,1fr);
  gap:28px;
}

.yt-card{text-align:center;}

.yt-wrap{
  position:relative;
  width:100%;
  padding-bottom:56.25%;
  border-radius:12px;
  overflow:hidden;
  box-shadow:0 4px 18px rgba(0,0,0,.08);
  background:#000;
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

.section-caption{
  margin-top:14px;
  font-size:15px;
  color:#444;
  line-height:1.55;
}

/* ---------- footer ---------- */
.footer{
  text-align:center;
  margin-top:70px;
  font-size:.9em;
  color:#888;
}

/* ---------- responsive ---------- */
@media (max-width:700px){
  .yt-grid{ grid-template-columns:1fr; }
  h1{ font-size:2.2em; }
}

</style>
</head>

<body>
<div class="container">

<h1 class="main-title">
<img src="icon.png">
OpenClaw: A Wrist-Frame Fingertip Force Sensing Hand for Contact-Rich Removal Manipulation
</h1>

<div class="authors">Anonymous Authors</div>
<div class="affiliation">Affiliation withheld for double-blind review</div>

<div class="links">
<a href="https://youtu.be/fToNWljt--Q" target="_blank">Video</a>
<a class="disabled">Code</a>
<a class="disabled">Dataset</a>
<a class="disabled">Hardware</a>
<a class="disabled">Paper</a>
</div>

<!-- ABSTRACT -->
<div class="section">
<h2>Abstract</h2>
<p>
We introduce OpenClaw, an open three-finger hand with modular three-axis fingertip force sensing and a wrist-frame multi-finger force representation, together with a nine-task contact-rich removal manipulation suite spanning adhesive detachment, cleaning, self-cleaning, and occluded retrieval. We evaluate a unified ACT-based imitation learning policy conditioned on RGB, joint state, and wrist-frame fingertip forces under strict success criteria and held-out real-robot tests, and use controlled ablations to quantify the contribution of wrist-frame force sensing in sequential contact interactions under uncertainty.
</p>

<div class="kpi">

<div class="card">
<div class="big">Wrist-frame forces</div>
<div class="small">
Multi-finger fingertip forces expressed in a common wrist frame for consistent contact representation across changing finger configurations.
</div>
</div>

<div class="card">
<div class="big">9-task benchmark</div>
<div class="small">
Contact-rich removal suite spanning adhesive detachment, cleaning, self-cleaning, and occluded retrieval under held-out real-robot tests.
</div>
</div>

<div class="card">
<div class="big">OpenClaw platform</div>
<div class="small">
Open three-finger hand with modular three-axis fingertip force sensing for reproducible real-world evaluation.
</div>
</div>

</div>
</div>

<!-- VIDEO -->
<div id="video" class="section">
<h2>Project Video</h2>
<div class="video">
<iframe src="https://www.youtube.com/embed/fToNWljt--Q" allowfullscreen></iframe>
</div>
</div>

<!-- RESULTS -->
<div class="section">
<h2>Results Highlights</h2>

<div class="yt-grid">
<!-- videos here (保持你原内容即可) -->
</div>

<div class="section-caption">
<strong>Results Highlights.</strong>
Representative executions across the nine-task removal suite under held-out real-robot conditions with synchronized multi-view observations and fingertip force traces.
</div>

</div>

<!-- FOOTER -->
<div class="footer">
Project page for robotics research papers
</div>

</div>
</body>
</html>
