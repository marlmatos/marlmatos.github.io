---
layout: about
title: about
permalink: /
subtitle: Functional Genomics Postdoctoral Associate, <a href='https://www.nygenome.org/science-technology/faculty-labs/lappalainen-lab/'>New York Genome Center</a>

profile:
  align: right
  image: prof_pic.jpg
  image_circular: false # crops the image to make it circular
  address: >
    <p>New York Genome Center</p>
    <p>New York, NY</p>

news: false  # the usual auto-rendered news block is disabled here — it's manually placed in the two-column row below instead
latest_posts: false  # includes a list of the newest posts
selected_papers: true # includes a list of papers marked as "selected={true}"
social: true  # includes social icons at the bottom of the page
---

I'm a human genetics and functional genomics scientist with experience across both experimental biology and computational genomics. My work spans molecular and cellular assays, genomic data generation, and the analysis of population-scale single-cell and multi-omic datasets.

During my PhD, I integrated genetic association analyses, statistical fine-mapping, chromatin accessibility, single-cell gene expression, and predictions from machine-learning models to study how regulatory variation contributes to immune-mediated disease. As a postdoctoral researcher, I focus on trans-regulatory variation, mapping trans-eQTLs and investigating how genetic variants influence transcription factor activity and downstream gene-expression programs.

My experience across experimental and computational genomics allows me to connect study design and data generation with analytical decisions and biological interpretation.

Take a look at my [CV](/cv/), or reach out below.

<div class="row">
  <div class="col-sm-6 mt-3 mt-md-0">
    <h4>news</h4>
    {% include news.html limit=true %}
  </div>
  <div class="col-sm-6 mt-3 mt-md-0">
    <h4>on bluesky &amp; x</h4>
    <bsky-embed username="marlmatos.bsky.social" limit="3" link-target="_blank" mode="light" id="bsky-widget"></bsky-embed>
    <a class="twitter-timeline" data-height="400" href="https://twitter.com/mrm_matos?ref_src=twsrc%5Etfw">Posts by @mrm_matos</a>
  </div>
</div>

<script type="module" src="https://cdn.jsdelivr.net/npm/bsky-embed/dist/bsky-embed.es.js" async></script>
<script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>
<script>
  // keep the Bluesky widget's light/dark mode in sync with the site's theme toggle
  (function () {
    var el = document.getElementById('bsky-widget');
    function applyTheme() {
      var theme = document.documentElement.getAttribute('data-theme');
      if (el) el.setAttribute('mode', theme === 'dark' ? 'dark' : 'light');
    }
    applyTheme();
    new MutationObserver(applyTheme).observe(document.documentElement, { attributes: true, attributeFilter: ['data-theme'] });
  })();
</script>
