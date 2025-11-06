---
layout: home
title: "Ecem Şimşek"
---

<div class="intro">
  <h1>Ecem Şimşek</h1>

  <p class="lead">
    I’m an M.Sc. student in Electrical and Electronics Engineering department at Bilkent University. I am working on <strong>graph signal processing</strong>, <strong>graph neural networks</strong>, <strong>hypergraphs</strong>, and especially <strong>visibility graphs</strong> and their applications in fields ranging from natural language processing to time series analysis. I’m particularly interested in developing graph-based methods theoretically, and making their applications using graph neural networks.
  </p>

  <p class="fulbright">
    I am also selected as a <strong>Principal Candidate</strong> for the 2026–2027 <strong>Fulbright Ph.D. scholarship</strong>. Scroll down for more!
  </p>

  <ul class="links">
    <li>
      <a href="mailto:ecem.simsek@bilkent.edu.tr">
        <i class="fa fa-envelope" aria-hidden="true"></i><span>Email</span>
      </a>
    </li>
    <li>
      <a href="assets/Ecem_Simsek_Resume.pdf">
        <i class="fa fa-file-text-o" aria-hidden="true"></i><span>CV</span>
      </a>
    </li>
    <li>
      <a href="https://scholar.google.com/citations?user=ZrC2RNwAAAAJ" target="_blank" rel="noopener">
        <i class="ai ai-google-scholar" aria-hidden="true"></i><span>Google Scholar</span>
      </a>
    </li>
    <li>
      <a href="https://github.com/ecemsimsekk" target="_blank" rel="noopener">
        <i class="fa fa-github" aria-hidden="true"></i><span>GitHub</span>
      </a>
    </li>
    <li>
      <a href="https://www.linkedin.com/in/ecem-%C5%9Fim%C5%9Fek-3601b618b/" target="_blank" rel="noopener">
        <i class="fa fa-linkedin" aria-hidden="true"></i><span>LinkedIn</span>
      </a>
    </li>
  </ul>
</div>

<hr />

<style>
  /* ---------- Theme ---------- */
  :root{
    --accent: #2f6fef;
    --text:   #1f2328;
    --muted:  #606774;
    --card:   #ffffff;
    --border: #e9ecef;
    --radius: 18px;
    --shadow-s: 0 1px 0 rgba(0,0,0,.04);
    --shadow-l: 0 10px 22px rgba(0,0,0,.08);
  }

  /* ---------- Intro (bigger + justified) ---------- */
  .intro{ max-width: 980px; margin: 0 auto; }
  .intro h1{
    margin: 1.2rem 0 1.15rem;  /* extra space under the hero image */
    font-size: clamp(3.2rem, 2.6vw + 1rem, 4.1rem);
    line-height: 1.1;
  }
  .intro .lead{
    margin: 0 0 1.2rem;        /* more space below main paragraph */
    font-size: clamp(1.50rem, .9vw + 1.05rem, 1.68rem);
    line-height: 1.75;
    text-align: justify; hyphens: auto; text-justify: inter-word;
  }
  .intro .fulbright{
    margin: 1.1rem 0 1.7rem;    /* gap around the Fulbright line */
    font-size: clamp(1.50rem, .9vw + 1.05rem, 1.68rem);
    line-height: 1.6;
  }

  /* Icon links row */
  .intro .links{
    margin: 1.0rem 0 1.6rem;   /* space above/below the links row */
    padding: 0;
    list-style: none;
    display: flex; flex-wrap: wrap;
    gap: .6rem 1.15rem;
    font-size: clamp(1.50rem, .9vw + 1.05rem, 1.68rem);
  }
  .intro .links li{ display: inline-flex; }
  .intro .links a{
    display: inline-flex; align-items: center; gap: .4rem;
    text-decoration: none;
  }
  .intro .links a:hover{ text-decoration: underline; }
  .intro .links i{ font-size: 1.05em; line-height: 1; }

  /* ---------- Section headings ---------- */
  .resume{
    max-width: 980px; margin: 0 auto;
    font-size: clamp(1.14rem, .6vw + 1rem, 1.28rem);
    line-height: 1.7;
  }
  .resume h2{
    display:flex; align-items:center; gap:.6rem;
    margin: 2.0rem 0 1.0rem;
    font-size: clamp(1.55rem, 1.2vw + 1.2rem, 2.0rem);
    letter-spacing:.2px;
  }
  .resume h2::before{ content:"▸"; color:var(--accent); font-weight:800; transform: translateY(1px); }

  /* ---------- Timeline cards ---------- */
  .timeline{ margin-top:1rem; }
  .timeline .item{
    position:relative; display:flex; gap:1.35rem; flex-wrap:wrap; align-items:flex-start;
    padding: 1.35rem 1.5rem; margin:1.05rem 0;
    background: var(--card); border:1px solid var(--border);
    border-radius: var(--radius);
    box-shadow: var(--shadow-s), var(--shadow-l);
    transition: transform .15s ease, box-shadow .15s ease;
  }
  .timeline .item:hover{ transform: translateY(-2px); box-shadow: var(--shadow-s), 0 16px 34px rgba(0,0,0,.12); }

  .timeline .logo{
    width:78px; height:78px; flex:0 0 78px; border-radius:999px; object-fit:cover;
    box-shadow: 0 0 0 1px rgba(0,0,0,.08); background:#fff;
  }

  /* --- SPECIFIC fixes for UMRAM & ASELSAN logos only --- */
  .timeline .logo.logo--umram,
  .timeline .logo.logo--aselsan{
    object-fit: contain;
    object-position: center;
    padding: 10px;
    background: #fff;
    box-shadow: 0 0 0 1px rgba(0,0,0,.12);
  }
  @media (max-width: 620px){
    .timeline .logo.logo--umram,
    .timeline .logo.logo--aselsan{ padding: 8px; }
  }
  /* ----------------------------------------------------- */

  .timeline .body{ flex:1 1 560px; min-width:320px; }

  .timeline .title{
    margin:0; color:var(--text); font-weight:670;
    font-size: clamp(1.28rem, .95vw + 1.1rem, 1.58rem);
    line-height:1.38;
  }
  .timeline .title em{ font-style:normal; font-weight:560; color:var(--muted); margin-left:.35rem; }

  .timeline .meta{
    margin:.4rem 0 0;
    font-size: clamp(1.20rem, .5vw + .98rem, 1.40rem);
    color:var(--muted);
  }
  .timeline .right{
    margin-left:auto; white-space:nowrap; color:var(--muted); font-weight:560;
    font-size: clamp(1.08rem, .5vw + .98rem, 1.24rem);
    padding-left:.8rem;
  }
  .timeline ul{ margin:.8rem 0 0 1.2rem; }
  .timeline li{ margin:.38rem 0; font-size: clamp(1.20rem, .5vw + .98rem, 1.40rem); }

  /* ---------- Publications ---------- */
  .pubs{ margin-top:.6rem; }
  .pub{
    display:grid; grid-template-columns: 140px 1fr; align-items:start;
    gap:1.05rem;
    padding:1.0rem 1.1rem;
    margin:1.0rem 0;
    background:var(--card);
    border:1px solid var(--border);
    border-radius:var(--radius);
    box-shadow: var(--shadow-s), 0 8px 18px rgba(0,0,0,.06);
  }
  .pub.featured{
    background:#fffbe7;                 /* highlight */
    border-color:#efe7b3;
  }
  .pub-thumb{
    width:140px; height:100px;
    object-fit:cover; object-position:center;
    border-radius:12px;
    box-shadow:0 1px 0 rgba(0,0,0,.05);
  }
  .pub .title{
    margin:0;
    font-weight:700;
    font-size:clamp(1.28rem, .95vw + 1.1rem, 1.58rem);
    line-height:1.3;
  }
  .pub .title a{ color:inherit; text-decoration:none; }
  .pub .title a:hover{ text-decoration:underline; }
  .pub .authors{ margin:.25rem 0 0; font-size: clamp(1.10rem, .5vw + .98rem, 1.30rem); }
  .pub .venue{
    margin:.15rem 0 .45rem;
    font-style:italic; color:var(--muted);
  }

  /* inline Abstract toggle (no caret) */
  details.abs{ margin-top:.1rem; }
  details.abs > summary{
    display:inline-block; cursor:pointer; color:var(--accent);
    font-weight:500; user-select:none; list-style:none;
  }
  details.abs > summary::-webkit-details-marker{ display:none; }
  details.abs > summary::before{ content:"["; color:inherit; }
  details.abs > summary::after { content:"]"; color:inherit; }
  .abs-body{ padding:.55rem 0 0; color:var(--text); }

  /* small top note */
  .pub-note{ margin:.2rem 0 .8rem; color:var(--muted); font-size: clamp(1.20rem, .5vw + .98rem, 1.40rem); }
  .pub-note mark{ background:#fffbe7; padding:0 .18rem; border-radius:.25rem; }

  /* Bigger left column for figures */
  .pubs .pub{
    grid-template-columns: 220px 1fr;   /* was 140px 1fr */
  }

  /* Larger thumbnails, no cropping, subtle frame */
  .pubs .pub-thumb{
    width: 220px;             /* was 140px */
    height: 150px;            /* was 100px */
    object-fit: contain;      /* avoid cropping so figures are readable */
    object-position: center;
    padding: 6px;
    background: #fff;
    border: 1px solid var(--border);
    border-radius: 12px;
  }

  /* Justify abstract text */
  details.abs .abs-body{
    padding: .55rem 0 0;
    color: var(--text);
    text-align: justify;
    text-justify: inter-word;
    hyphens: auto;
    line-height: 1.7;
  }

  /* Mobile: stack layout and keep images sensible */
  @media (max-width: 720px){
    .pubs .pub{ grid-template-columns: 1fr; }
    .pubs .pub-thumb{
      width: 100%;
      height: auto;
      max-height: 240px;      /* prevents super tall images on small screens */
    }
  }

  /* Publications: hover like other boxes */
  .pubs .pub{
    transition: transform .15s ease, box-shadow .15s ease;  /* smooth motion */
  }
  .pubs .pub:hover{
    transform: translateY(-2px);
    box-shadow: var(--shadow-s), 0 16px 34px rgba(0,0,0,.12);
  }

  /* ---------- Honors & Awards cards ---------- */
  .honors{ margin-top:.6rem; }
  .honor{
    display:flex; align-items:flex-start; gap:1.05rem;
    padding:1.0rem 1.1rem; margin:1.0rem 0;
    background:var(--card); border:1px solid var(--border);
    border-radius:var(--radius);
    box-shadow: var(--shadow-s), 0 8px 18px rgba(0,0,0,.06);
    transition: transform .15s ease, box-shadow .15s ease;
  }
  .honor:hover{
    transform: translateY(-2px);
    box-shadow: var(--shadow-s), 0 16px 34px rgba(0,0,0,.12);
  }
  .honor .logo{
    width:78px; height:78px; flex:0 0 78px;
    border-radius:999px; object-fit:contain; object-position:center;
    background:#fff; box-shadow:0 0 0 1px rgba(0,0,0,.08);
  }
  .honor .body{ flex:1 1 auto; min-width:300px; }
  .honor .title{
    margin:0; font-weight:670;
    font-size: clamp(1.28rem, .95vw + 1.1rem, 1.58rem);
    line-height:1.35;
  }
  .honor .meta{
    margin:.25rem 0 0; color:var(--muted);
    font-size:clamp(1.20rem, .5vw + .98rem, 1.40rem);
  }
  @media (max-width: 620px){
    .honor .logo{ width:66px; height:66px; flex-basis:66px; }
  }

  /* SIU logo: show full logo, no white strip */
  .honor .logo.logo--siu25{
    display: block;              /* remove baseline gap that looks like a white band */
    object-fit: contain;         /* don't crop */
    object-position: center;
    padding: 1px;               /* breathing room */
    background: transparent;     /* <— key: don't paint white behind transparent areas */
    box-shadow: 0 0 0 1px rgba(0,0,0,.10);  /* subtle ring */
  }

  @media (max-width: 650px){
    .honor .logo.logo--siu25{ padding: 8px; }
  }

  /* ---------- Generic section card (hover) ---------- */
  .section-card{
    display:flex; align-items:flex-start; gap:1.05rem;
    padding:1.05rem 1.2rem; margin:1.0rem 0;
    background:var(--card); border:1px solid var(--border);
    border-radius:var(--radius);
    box-shadow: var(--shadow-s), 0 8px 18px rgba(0,0,0,.06);
    transition: transform .15s ease, box-shadow .15s ease;
  }
  .section-card:hover{
    transform: translateY(-2px);
    box-shadow: var(--shadow-s), 0 16px 34px rgba(0,0,0,.12);
  }

  /* Left “logo” (emoji badge) */
  .section-card .logo{
    width:78px; height:78px; flex:0 0 78px;
    border-radius:999px; background:#fff;
    display:flex; align-items:center; justify-content:center;
    font-size:34px; line-height:1;
    box-shadow:0 0 0 1px rgba(0,0,0,.08);
  }
  @media (max-width: 620px){
    .section-card .logo{ width:66px; height:66px; flex-basis:66px; font-size:28px; }
  }

  .section-card .body{ flex:1 1 auto; min-width:300px; }
  .section-card .title{
    margin:0 0 .35rem 0; font-weight:670;
    font-size: clamp(1.28rem, .95vw + 1.1rem, 1.58rem);
    line-height:1.35;
  }
  .section-card .sub{
    margin:.2rem 0 .35rem; font-weight:600;
    font-size: clamp(1.20rem, .5vw + .98rem, 1.40rem);
    color:var(--text);
  }

  /* Teaching rows (course | role & years) */
  .teaching-grid{
    display:grid;
    grid-template-columns: 1fr auto;
    gap:.38rem .8rem;
    font-size: clamp(1.20rem, .5vw + .98rem, 1.40rem);
  }
  .teaching-grid .when{ color:var(--muted); white-space:nowrap; }
  @media (max-width: 720px){
    .teaching-grid{ grid-template-columns: 1fr; }
    .teaching-grid .when{ white-space:normal; }
  }

  /* Skills as pills, arranged in a responsive grid */
  .skills-grid{
    display:grid; gap:1.0rem 1.2rem;
    grid-template-columns: repeat(2, minmax(240px, 1fr));
  }
  @media (max-width: 720px){
    .skills-grid{ grid-template-columns: 1fr; }
  }
  .pills{
    margin:.1rem 0 0; padding:0; list-style:none;
    display:flex; flex-wrap:wrap; gap:.45rem .55rem;
  }
  .pill{
    padding:.28rem .6rem; border:1px solid var(--border);
    border-radius:999px; background:#f9fafb;
    font-size: clamp(1.20rem, .5vw + .98rem, 1.40rem);
}

  /* ---------- Footer ---------- */
  .footer-sep{
    border: 0;
    border-top: 1px solid var(--border);
    margin: 2.0rem 0 1.0rem;
  }
  .site-footer{
    max-width: 980px;
    margin: 0 auto 2.4rem;
    color: var(--muted);
    font-size: clamp(0.98rem, .48vw + .88rem, 1.12rem);
  }
  .site-footer a{ color: var(--accent); text-decoration: none; }
  .site-footer a:hover{ text-decoration: underline; }
</style>

<div class="resume">

## Education

<div class="timeline" markdown="0">
  <div class="item">
    <img class="logo" src="assets/logos/bilkent.png" alt="Bilkent University">
    <div class="body">
      <p class="title"><strong>M.Sc., Electrical &amp; Electronics Engineering</strong> — Bilkent University (Ankara, TR)</p>
      <p class="meta">Advisor: Asst. Prof. Aykut Koç • CGPA: 3.67</p>
    </div>
    <span class="right when">2023–present</span>
  </div>

  <div class="item">
    <img class="logo" src="assets/logos/bilkent.png" alt="Bilkent University">
    <div class="body">
      <p class="title"><strong>B.Sc., Electrical &amp; Electronics Engineering</strong> — Bilkent University (Ankara, TR)</p>
      <p class="meta">Cum Laude • CGPA: 3.20</p>
    </div>
    <span class="right when">2018–2023</span>
  </div>
</div>

## Professional Experience

<div class="timeline" markdown="0">
  <div class="item">
    <img class="logo logo--umram" src="assets/logos/umram.jpg" alt="UMRAM">
    <div class="body">
      <p class="title"><strong>UMRAM (National Magnetic Resonance Center)</strong> — <em>Graduate Researcher</em></p>
      <ul>
        <li>Working under the supervision of Asst. Prof. Aykut Koç.</li>
        <li>Making research on visibility graphs, hypergraphs, and their utilizations in domains ranging from natural language processing to time series analysis.</li>
      </ul>
    </div>
    <span class="right when">June 2023-Present</span>
  </div>

  <div class="item">
    <img class="logo logo--umram" src="assets/logos/umram.jpg" alt="UMRAM">
    <div class="body">
      <p class="title"><strong>UMRAM (National Magnetic Resonance Center)</strong> — <em>Undergraduate Researcher</em></p>
      <ul>
        <li>Worked under the supervision of Asst. Prof. Aykut Koç.</li>
        <li>Made research on graph neural networks, visibility graphs, and their utilization in text classification.</li>
      </ul>
    </div>
    <span class="right when">2022-2023</span>
  </div>

  <div class="item">
    <img class="logo logo--umram" src="assets/logos/umram.jpg" alt="UMRAM">
    <div class="body">
      <p class="title"><strong>UMRAM (National Magnetic Resonance Center)</strong> — <em>Research Intern</em></p>
      <ul>
        <li>Worked under the supervision of Prof. Ergin Atalar.</li>
        <li>Worked on and made research about acquisition and real-time display of digitized signals.</li>
        <li>Developed a Direct Memory Access pipeline in VHDL for high-speed analog-to-digital converter on Xilinx VC707 FPGA.</li>
      </ul>
    </div>
    <span class="right when">2020-2021</span>
  </div>
</div>

## Publications

<p class="pub-note">
  Selected publications are <mark>highlighted</mark>. The list of my publications can also be found in
  <a href="https://scholar.google.com/citations?user=ZrC2RNwAAAAJ" target="_blank" rel="noopener">Google Scholar</a>.
</p>

<!-- IMPORTANT: markdown="0" prevents kramdown from treating this HTML as code -->
<div class="pubs" markdown="0">

  <!-- EmoVis — featured -->
  <article class="pub featured">
    <img class="pub-thumb" src="assets/emovis.png" alt="EmoVis figure">
    <div>
      <p class="title">
        <a href="https://ieeexplore.ieee.org/abstract/document/10985783" target="_blank" rel="noopener">
          Emotion Classification with Visibility Graphs (EmoVis)
        </a>
      </p>
      <p class="authors"><strong>Ecem Şimşek</strong>, Atakan Topcu, Emirhan Koç, Emine Ülkü Sarıtaş, Aykut Koç</p>
      <p class="venue"><em>IEEE Signal Processing Letters (SPL)</em></p>
      <details class="abs">
        <summary>abstract</summary>
        <div class="abs-body">
          Transformers have gained prominence in natural language processing due to their representational capabilities and performances. Transformers process natural language as a sequence on finite context windows; however, global relationships among words beyond these windows cannot be completely modeled via sequence processing only. Graph neural network (GNN) based models have been proposed to alleviate this problem, as they provide geometric extensions to neural networks, enabling models to learn associations within a text. However, regular graph-based methods ignore the sequential nature of underlying texts. In this paper, we propose EmoVis, the first generic graph-based neural network that utilizes visibility graphs, which converts classical time-series information to graph representations. We cast the problem as an emotion classification task, enabling the proposed model to learn associations between the labels and words in a sentence. Moreover, EmoVis can be used as a highly modular graph-based extension to any transformer-based model, significantly improving their performance and learning capabilities in various languages. We experimentally show that EmoVis enables transformer-based models to outperform the state-of-the-art baselines across three diverse datasets in different languages in the SemEval2018 competition datasets and the GoEmotions dataset.
        </div>
      </details>
    </div>
  </article>

  <!-- FrVis — featured -->
  <article class="pub featured">
    <img class="pub-thumb" src="assets/ieee.jpg" alt="FrVis figure">
    <div>
      <p class="title">
        <!-- <a href=" " target="_blank" rel="noopener"-->
          Fractional Fourier-Guided Visibility Graphs
        <!--</a>-->
      </p>
      <p class="authors"><strong>Ecem Şimşek</strong>, Haldun Özaktaş, Aykut Koç</p>
      <p class="venue"><em>To be submitted to IEEE Signal Processing Letters (SPL)</em></p>
      <details class="abs">
        <summary>abstract</summary>
        <div class="abs-body">

        </div>
      </details>
    </div>
  </article>

  <!-- EpiGraphNet -->
  <article class="pub">
    <img class="pub-thumb" src="assets/epigrafnet.png" alt="EpiGraphNet figure">
    <div>
      <p class="title">
        <a href="https://ieeexplore.ieee.org/abstract/document/11111837" target="_blank" rel="noopener">
          EpiGraphNet: Epilepsy Recognition Architecture with Graph-Based EEG Analysis
        </a>
      </p>
      <p class="authors"><strong>Ecem Şimşek</strong>, Emirhan Koç, Aykut Koç</p>
      <p class="venue"><em>IEEE Signal Processing and Communications Applications Conference (SIU)</em></p>
      <details class="abs">
        <summary>abstract</summary>
        <div class="abs-body">
          Early and accurate detection of epileptic seizures is crucial for patients' quality of life and the treatment process. In this context, our study proposes EpiGrafNet, an innovative hybrid model that delivers high performance in epileptic seizure detection using electroencephalography (EEG) signals. The proposed method extracts both local and long-term temporal features from EEG signals via a one-dimensional convolutional neural network (CNN) and long short-term memory (LSTM) module; these features are then transformed into a graph structure by the utilization of correlation connection matrices (CCM), and integrated with graph convolutional neural networks (GCN). Experiments conducted with different sparsity values demonstrate that the developed model achieves superior accuracy, recall, precision, and F1 scores in both binary and multi-class epileptic seizure detection tasks, indicating that EpiGrafNet provides higher and more reliable results compared to existing methods. This approach, by effectively modeling the complex spatial and temporal relationships in EEG signals, significantly contributes to the development of automatic epileptic seizure detection systems in clinical applications.
        </div>
      </details>
    </div>
  </article>

  <!-- Wind Power -->
  <article class="pub">
    <img class="pub-thumb" src="assets/siu23.png" alt="Wind power figure">
    <div>
      <p class="title">
        <a href="https://ieeexplore.ieee.org/document/10223936" target="_blank" rel="noopener">
          Wind Power Prediction Using Machine Learning and Deep Learning Algorithms
        </a>
      </p>
      <p class="authors"><strong>Ecem Şimşek</strong>, Ayşemüge Güngör, Öykü Karavelioğlu, Mustafa Tolga Yerli, Nejat Göktuğ Kuyumcuoğlu</p>
      <p class="venue"><em>IEEE Signal Processing and Communications Applications Conference (SIU)</em></p>
      <details class="abs">
        <summary>abstract</summary>
        <div class="abs-body">
          In this study, it has been tried to predict the wind power generation values in a long-term period by using a dataset containing the wind power generation values of 10 zones using machine learning and deep learning methods. In this context, the importance of accurately predicting renewable energy production was emphasized by associating it with machine learning and deep learning methods. The methods to be used in the study were selected based on the literature review and the characteristics of the time series datasets. Since the dataset includes the basic wind components, a detailed feature analysis was performed, and the dataset was enriched with the newly added features. The hyperparameters of the utilized models were optimized for all regions in the dataset separately and the models were run with these hyperparameters. The results of the models were evaluated with different error metrics and compared with each other, and the models with the lowest error scores were determined.
        </div>
      </details>
    </div>
  </article>

  <!-- Basic Level Categories -->
  <article class="pub">
    <img class="pub-thumb" src="assets/blc.png" alt="BLC figure">
    <div>
      <p class="title">
        <a href="https://ieeexplore.ieee.org/document/11112453" target="_blank" rel="noopener">
          Automatic Detection of Basic Level Categories
        </a>
      </p>
      <p class="authors">Emirhan Koç, İrem Şanlı, <strong>Ecem Şimşek</strong>, Hasan Özekin, Aykut Koç</p>
      <p class="venue"><em>IEEE Signal Processing and Communications Applications Conference (SIU)</em></p>
      <details class="abs">
        <summary>abstract</summary>
        <div class="abs-body">
          Basic level categories (BLCs), which can be defined as the most inclusive level at which a concrete mental image of the entire category can be formed, have proven to be useful in a variety of applications in natural language processing (NLP) and computer vision (CV) tasks, such as word sense disambiguation, image searches, image description, and retrieval. Limiting their practical applications, current methods for detecting BLCs predominantly rely on rule-based methods and external knowledge sources rather than the information extracted directly from the text. In this manuscript, we propose a novel approach to detect BLCs that is merely based on the information obtained from the word embeddings, including Gaussian word embeddings (W2G) and embeddings retrieved from transformer-based models such as BERT and GPT-2. The proposed method significantly outperforms existing works in performance and practicality, demonstrating the effectiveness of contextual word embeddings for BLC detection.
        </div>
      </details>
    </div>
  </article>

</div>

## Honors and Awards

<!-- Converted to logo cards; keep assets under assets/logos/ -->
<div class="honors" markdown="0">

  <div class="honor">
    <img class="logo" src="assets/logos/fulbright.jpg" alt="Fulbright">
    <div class="body">
      <p class="title"><strong>Principal Candidate</strong>, Fulbright Ph.D. Scholarship (2026–2027)</p>
      <p class="meta">Selected for national nomination to the Fulbright doctoral scholarship cohort.</p>
    </div>
  </div>

  <div class="honor">
    <img class="logo logo--siu25" src="assets/logos/siulogo.png" alt="IEEE SIU">
    <div class="body">
      <p class="title"><strong>1st Place</strong>, 5-Minute Thesis Competition (M.Sc.), IEEE SIU 2025 Conference</p>
      <p class="meta">Best presentation award among graduate finalists in IEEE SIU 2025 Conference held at Işık University.</p>
    </div>
  </div>

  <div class="honor">
    <img class="logo" src="assets/logos/turktelekom.png" alt="Türk Telekom / BTK">
    <div class="body">
      <p class="title"><strong>5G and Beyond Graduate Support Scholarship</strong>, BTK / Türk Telekom</p>
      <p class="meta">Competitive research scholarship supporting graduate study, awarded by the Information and Communication Technologies Authority of Turkey (BTK), funded by Türk Telekom company.</p>
    </div>
  </div>

  <div class="honor">
    <img class="logo" src="assets/logos/bilkenthigh.jpeg" alt="Bilkent">
    <div class="body">
      <p class="title"><strong>Full Academic Scholarship</strong>, I.D.F. Bilkent High School</p>
      <p class="meta">Awarded based on top-3 performance in graduation from I.D.F. Bilkent Middle School.</p>
    </div>
  </div>

</div>

## Teaching

<div class="info" markdown="0">
  <div class="section-card">
    <div class="logo" aria-hidden="true">🎓</div>
    <div class="body">
      <p class="title">Teaching and Mentoring</p>
      <div class="teaching-grid">
        <div class="course">EEE493/494 — <strong>Industrial Design Project</strong> (Bilkent University)</div>
        <div class="when">Graduate TA • 2023–present</div>

        <div class="course">EEE342 — <strong>Feedback Control Systems</strong> (Bilkent University)</div>
        <div class="when">Lab Assistant • 2022–2023</div>

        <div class="course">CS115 — <strong>Introduction to Python Programming </strong>(Bilkent University)</div>
        <div class="when">Lab Assistant • 2020–2021, 2022</div>
      </div>
    </div>
  </div>
</div>

## Skills

<div class="info" markdown="0">
  <div class="section-card">
    <div class="logo" aria-hidden="true">🛠️</div>
    <div class="body">
      <p class="title">Skill Sets</p>

      <div class="skills-grid">
        <div>
          <p class="sub">Core</p>
          <ul class="pills">
            <li class="pill">Deep Learning</li>
            <li class="pill">Signal Processing</li>
            <li class="pill">Graph Signal Processing</li>
            <li class="pill">Graph Neural Networks</li>
            <li class="pill">Natural Language Processing</li>
            <li class="pill">Time Series Analysis</li>
          </ul>
        </div>

        <div>
          <p class="sub">Programming & Tools</p>
          <ul class="pills">
            <li class="pill">Python</li>
            <li class="pill">PyTorch</li>
            <li class="pill">PyTorch-Geometric</li>
            <li class="pill">TensorFlow</li>
            <li class="pill">MATLAB</li>
            <li class="pill">VHDL</li>
            <li class="pill">Vivado</li>
            <li class="pill">Arduino</li>
            <li class="pill">Cadence&nbsp;Virtuoso</li>
            <li class="pill">LTSpice</li>
            <li class="pill">Streamlit</li>
            <li class="pill">LaTeX</li>
          </ul>
        </div>

        <div>
          <p class="sub">Languages</p>
          <ul class="pills">
            <li class="pill">English</li>
            <li class="pill">French (beginner)</li>
            <li class="pill">Spanish (beginner)</li>
          </ul>
        </div>
      </div>

    </div>
  </div>
</div>

</div>

<hr class="footer-sep" />
<footer class="site-footer">
  <p>Template is from <a href="https://bamos.github.io/" target="_blank" rel="noopener">Brandon Amos</a>.</p>
</footer>