---
layout: page
permalink: /publications/
title: publications
description: For the most up-to-date list of publications, please visit my <a href="https://scholar.google.com/citations?user=44AyCnIAAAAJ&hl=en" target="_blank" rel="noopener noreferrer">Google Scholar profile</a> or <a href="https://www.ncbi.nlm.nih.gov/myncbi/liesl.broadbridge.2/bibliography/public/" target="_blank" rel="noopener noreferrer">MyNCBI bibliography</a>.
nav: true
nav_order: 2
---

<!-- _pages/publications.md -->

<!-- Bibsearch Feature -->

{% include bib_search.liquid %}

<div class="publications">

<details open>
  <summary class="card-title font-weight-medium" style="cursor: pointer;">Manuscripts</summary>
  <div class="mt-2">
    {% bibliography --query @article %}
  </div>
</details>

<details>
  <summary class="card-title font-weight-medium" style="cursor: pointer;">Book Chapters</summary>
  <div class="mt-2">
    {% bibliography --query @incollection %}
  </div>
</details>

<details>
  <summary class="card-title font-weight-medium" style="cursor: pointer;">Other</summary>
  <div class="mt-2">
    {% bibliography --query @misc %}
    {% bibliography --query @unpublished %}
  </div>
</details>

</div>
