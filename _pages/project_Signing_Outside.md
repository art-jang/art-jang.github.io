---
layout: none
title: Signing Outside the Studio
permalink: /signing_outside
description: Benchmarking Background Robustness for Continuous Sign Language Recognition.
keywords: "Sign language recognition, Background bias, Vision and language"
title: "Signing Outside the Studio: Benchmarking Background Robustness for Continuous Sign Language Recognition"
venue: British Machine Vision Conference (BMVC 2022)
# pdf: False
# arxiv: False
# code: False
# slide: False
# poster: False
bibtex: >
  @inproceedings{jang2022signing, <br />
  &nbsp;&nbsp; title={Signing Outside the Studio: Benchmarking Background Robustness for Continuous Sign Language Recognition}, <br />
  &nbsp;&nbsp; author={Jang, Youngjoon and Oh, Youngtaek and Cho, Jae Won and Kim, Dong-Jin and Chung, Joon Son and Kweon, In So}, <br />
  &nbsp;&nbsp; booktitle={British Machine Vision Conference (BMVC)}, <br />
  &nbsp;&nbsp; year={2022} <br />
  }
#   &nbsp;&nbsp; pages={0000-0000} <br />

abstract: >
  <p>
    The goal of this work is background-robust continuous sign language recognition. Most existing Continuous Sign Language Recognition (CSLR) benchmarks have fixed backgrounds and are filmed in studios with a static monochromatic background. However, signing is not limited only to studios in the real world. 
  </p>
  <p>
    In order to analyze the robustness of CSLR models under background shifts, we first evaluate existing state-of-the-art CSLR models on diverse backgrounds. To synthesize the sign videos with a variety of backgrounds, we propose a pipeline to automatically generate a benchmark dataset utilizing existing CSLR benchmarks. Our newly constructed benchmark dataset consists of diverse scenes to simulate a real-world environment. We observe that even the most recent CSLR method cannot recognize glosses well on our new dataset with changed backgrounds. 
  </p>
  <p>
    In this regard, we also propose a simple yet effective training scheme including (1) background randomization and (2) feature disentanglement for CSLR models. The experimental results on our dataset demonstrate that our method generalizes well to other unseen background data with minimal additional training images.
  </p>
---


<!-- <!DOCTYPE html> -->
<html>
<head>
  <meta charset="utf-8">
  <meta name="description"
        content="{{ page.description }}">
  <meta name="keywords" content="{{ page.keywords }}">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>{{ page.title }}</title>

  <!-- Global site tag (gtag.js) - Google Analytics -->
  {% include scripts/analytics.html %}
  <!-- mathjax -->
  <script type="text/x-mathjax-config"> 
    MathJax.Hub.Config({ tex2jax: { inlineMath: [ ['$','$'], ["\\(","\\)"] ], processEscapes: true } }); 
  </script>
  <script src='https://cdnjs.cloudflare.com/ajax/libs/mathjax/2.7.2/MathJax.js?config=TeX-MML-AM_CHTML'></script>
  <!--/ mathjax -->
  <link href="https://fonts.googleapis.com/css?family=Google+Sans|Noto+Sans|Castoro" rel="stylesheet">

  <link rel="stylesheet" href="./assets/nerfies/css/bulma.min.css">
  <link rel="stylesheet" href="./assets/nerfies/css/bulma-carousel.min.css">
  <link rel="stylesheet" href="./assets/nerfies/css/bulma-slider.min.css">
  <link rel="stylesheet" href="./assets/nerfies/css/fontawesome.all.min.css">
  <link rel="stylesheet"
        href="https://cdn.jsdelivr.net/gh/jpswalsh/academicons@1/css/academicons.min.css">
  <link rel="stylesheet" href="./assets/nerfies/css/index.css">

  <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.5.1/jquery.min.js"></script>
  <script defer src="./assets/nerfies/js/fontawesome.all.min.js"></script>
  <script src="./assets/nerfies/js/bulma-carousel.min.js"></script>
  <script src="./assets/nerfies/js/bulma-slider.min.js"></script>
  <script src="./assets/nerfies/js/index.js"></script>
</head>
<body>

<nav class="navbar" role="navigation" aria-label="main navigation">
  <div class="navbar-brand">
    <a role="button" class="navbar-burger" aria-label="menu" aria-expanded="false">
      <span aria-hidden="true"></span>
      <span aria-hidden="true"></span>
      <span aria-hidden="true"></span>
    </a>
  </div>
  <div class="navbar-menu">
    <div class="navbar-start" style="flex-grow: 1; justify-content: center;">
      <a class="navbar-item" href="https://art-jang.github.io">
      <span class="icon">
          <i class="fas fa-home"></i>
      </span>
      </a>
    </div>
  </div>
</nav>

<section class="hero">
  <div class="hero-body">
    <div class="container is-max-desktop">
      <div class="columns is-centered">
        <div class="column has-text-centered">
          <h1 class="title is-3 publication-title">{{ page.title }}</h1>
          <div class="is-size-4 publication-authors">
            <span class="author-block">
              <a href="https://art-jang.github.io">Youngjoon Jang</a><sup>1</sup>,</span>
            <span class="author-block">
              <a href="https://ytaek-oh.github.io">Youngtaek Oh</a><sup>1</sup>,</span>
            <span class="author-block">
              <a href="https://chojw.github.io/">Jae Won Cho</a><sup>1</sup>,</span>
            <span class="author-block">
              <a href="https://sites.google.com/site/djkimcv/">Dong-Jin Kim</a><sup>2</sup>,</span>
            <span class="author-block">
              <a href="https://mm.kaist.ac.kr/joon/">Joon Son Chung</a><sup>1</sup>,</span>
            <span class="author-block">
              <a href="https://scholar.google.com/citations?user=XA8EOlEAAAAJ&hl=ko">In So Kweon</a><sup>1</sup>,</span>
          </div>
          <div class="is-size-5 publication-authors">
            <span class="author-block"><sup>1</sup>KAIST / Daejeon, South Korea.</span>
            <span class="author-block"><sup>2</sup>Hanyang University / Seoul, South Korea.</span>
          </div>
          <div class="column has-text-centered">
            <div class="publication-links">
              <!-- PDF Link. -->
              {%- if page.pdf %}
              <span class="link-block">
                <a href="{{ page.pdf }}" target="_blank"
                   class="external-link button is-normal is-rounded is-dark">
                  <span class="icon">
                      <i class="fas fa-file-pdf"></i>
                  </span>
                  <span>Paper</span>
                </a>
              </span>
              {%- endif %}
              {%- if page.arxiv %}
              <span class="link-block">
                <a href="{{ page.arxiv }}"
                   class="external-link button is-normal is-rounded is-dark">
                  <span class="icon">
                      <i class="ai ai-arxiv"></i>
                  </span>
                  <span>arXiv</span>
                </a>
              </span>
              {%- endif %}
              {%- if page.video %}
              <!-- Video Link. -->
              <span class="link-block">
                <a href="{{ page.video }}"
                   class="external-link button is-normal is-rounded is-dark">
                  <span class="icon">
                      <i class="fab fa-youtube"></i>
                  </span>
                  <span>Video</span>
                </a>
              </span>
              {%- endif %}
              {%- if page.code %}
              <!-- Code Link. -->
              <span class="link-block">
                <a href="{{ page.code }}"
                   class="external-link button is-normal is-rounded is-dark">
                  <span class="icon">
                      <i class="fab fa-github"></i>
                  </span>
                  <span>Code</span>
                  </a>
              </span>
              {%- endif %}
              {%- if page.slide %}
              <!-- slide Link. -->
              <span class="link-block">
                <a href="{{ page.slide | prepend: '/assets/daso/' }}" target="_blank"
                   class="external-link button is-normal is-rounded is-dark">
                  <span class="icon">
                      <i class="far fa-file-powerpoint"></i>
                  </span>
                  <span>Slides</span>
                  </a>
              </span>
              {%- endif %}
              {%- if page.poster %}
              <!-- poster Link. -->
              <span class="link-block">
                <a href="{{ page.poster | prepend: '/assets/daso/' }}" target="_blank"
                   class="external-link button is-normal is-rounded is-dark">
                  <span class="icon">
                      <i class="fas fa-file-powerpoint"></i>
                  </span>
                  <span>Poster</span>
                  </a>
              </span>
              {%- endif %}
            </div>
          </div>
          <div class="column has-text-centered">
            <div class="is-size-5 publication-authors">
              {{ page.venue }}
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</section>
<!-- project_page.html -->
<section class="hero teaser">
  <div class="container is-max-desktop">
    <div class="hero-body">
      <div class="columns is-centered">
        <div class="column is-11">
          <img src="assets/signing_outside/scene-phoenix.png"/>
        </div>
      </div>
      <h2 class="subtitle has-text-centered is-size-5">
        Examples of our Scene-PHOENIX with backgrounds for evaluating the background robustness of the model. To best our knowledge, we are the first to construct a benchmark dataset with various backgrounds that can evaluate the background robustness of the CSLR model, and it has a reasonable construction cost in that it reuses existing CSLR datasets and scene datasets.
      </h2>
    </div>
  </div>
</section>
<section class="section">
  <div class="container is-max-desktop">
    <!-- Abstract. -->
    <div class="columns is-centered has-text-centered">
      <div class="column is-four-fifths">
        <h2 class="title is-3">Abstract</h2>
        <div class="content has-text-justified">
          {{ page.abstract }}
        </div>
      </div>
    </div>
    <!--/ Abstract. -->
  </div>
</section>

<!-- Results -->
<section class="section">
  <div class="container is-max-desktop">
    <div class="columns is-centered">
      <div class="column is-full-width">
        <h2 class="title is-3">Introduction</h2> 
        <div class="content has-text-justified">
          <p>
            Most publicly available CSLR benchmarks are curated from either studio or TV broadcasts, where background images are fixed and monochromatic. A naïve solution to this would be constructing a new dataset outside the studio, but the cost of extensive gloss annotations as well as collecting sign videos with skilled signers present significant challenges.
          </p>
          <div class="columns is-centered">
            <div class="column is-8">
              <img src="assets/signing_outside/monochromatic.png"/>
            </div>
          </div> 
          <p>
            To tackle this issue, We make variants of development and test splits of PHOENIX-2014 [1] with our automated pipeline and name our benchmark dataset with diverse backgrounds Scene-PHOENIX.
          </p>
        </div>
        <h3 class="title is-5">Background Attack to CSLR models</h3>
        <div class="content has-text-justified">
          <p class="mb-4">
            Based on our Scene-PHOENIX dataset, we find that current CSLR approaches are not robust to background shifts. Baseline (ResNet-18 [2] + 1D-CNN) and VAC [3] which is the state-of-the-art model in the CSLR field severely degrade when tested on Scene-PHOENIX.
          </p>
        </div>
        <div class="hero-body">
          <div class="columns is-centered">
            <div class="column is-5">
              <img src="assets/signing_outside/attack.png"/>
            </div>
          </div>
          <h2 class="subtitle has-text-centered">
            Word Error Rate (WER) scores from test benchmarks. We attack the state-of-the-art model VAC by chainging the background images in the Test split of PHOENIX-2014 dataset. 
          </h2>
        </div>
        <!-- same imbalance -->
      </div>
    </div>
  </div>
</section>
<!-- Analysis -->
<section class="section">
  <div class="container is-max-desktop">
    <div class="columns is-centered">
      <div class="column is-full-width">
        <h2 class="title is-3">Background Agnostic Framework</h2> 
        <div class="content has-text-justified">
          <p>
            Our framework comprises of (1) Background Randomization (BR), which simply generates a sign video with new background via mixup [4] to simulate background shift, and (2) Disentangling Auto-Encoder (DAE) that aims to disentangle the signer from videos with background in latent space.
          </p>
        </div>
        <!-- same imbalance -->
        <h3 class="title is-5">Background Randomization</h3>
        <div class="hero-body">
          <div class="columns is-centered">
            <div class="column is-7">
              <img src="assets/signing_outside/background_generation.png"/>
            </div>
          </div>
          <h2 class="subtitle has-text-centered">
            Data generation. (a) For Scene-PHOENIX, background matting is performed with scene images using person masks. (b) For training set, we apply mixup between a sign video and a scene image without person masks to reduce additional labeling cost in training.
          </h2>
        </div>
        <!-- different imbalance -->
        <h3 class="title is-5">Disentangling Auto-Encoder</h3>
        <div class="hero-body">
          <div class="columns is-centered">
            <div class="column is-12">
              <img src="assets/signing_outside/overall_architecture.png"/>
            </div>
          </div>
          <h2 class="subtitle has-text-centered">
            The overall architecture of the proposed model. The original video passes through Teacher Network, and the background-randomized video passes through Student Notwork. In the latent space, the signer features are swapped with each other. Then, the swapped features are input to the shared DAE decoder for reconstructing the original features.
          </h2>
        </div>
      </div>
    </div>
  </div>
</section>
<!--/ Analysis -->


<!-- Analysis -->
<section class="section">
  <div class="container is-max-desktop">
    <div class="columns is-centered">
      <div class="column is-full-width">
        <h2 class="title is-3">Experimental Restuls</h2> 
        <!-- same imbalance -->
        <h3 class="title is-5">Main Restuls</h3>
        <div class="hero-body">
          <div class="columns is-centered">
            <div class="column is-10">
              <img src="assets/signing_outside/main_result.png"/>
            </div>
          </div>
          <h2 class="subtitle has-text-centered">
            Experimental results on PHOENIX-2014 and Scene-PHOENIX. VAC-Oracle is a VAC model that is trained on all LSUN [5] background matted images. While the performance of the baselines severely degrades under Scene-PHOENIX, the proposed Background Randomization (BR) shows significant performance improvements. Our final model (BR + DAE) shows the best performance among the baseline models. Note that our final model with K = 1 outperforms all VAC w/ BR models. Moreover, Our with K = 1000 surpasses the VAC-Oracle and VAC in both dataset without any off-the-shelf human segmentation masks.
          </h2>
        </div>
        <!-- different imbalance -->
        <h3 class="title is-5">Ablation on Additional Training Data</h3>
        <div class="hero-body">
          <div class="columns is-centered">
            <div class="column is-6">
              <img src="assets/signing_outside/additional_training_data.png"/>
            </div>
          </div>
          <h2 class="subtitle has-text-centered">
            Using DAE is more efficient in annotation cost compared to using pose, which requires extra annotation. We emphasize using additional 100 scene images for BR is much cheaper than annotating pose for training.
          </h2>
        </div>
        <h3 class="title is-5">Different Backbone Network</h3>
        <div class="hero-body">
          <div class="columns is-centered">
            <div class="column is-5">
              <img src="assets/signing_outside/backbones.png"/>
            </div>
          </div>
          <h2 class="subtitle has-text-centered">
            Comparison of performances with different feature extractors: GoogLeNet [6] and ResNet18. Our framework consistently works well with different feature extractors.
          </h2>
        </div>
      </div>
    </div>
  </div>
</section>


<!-- Analysis -->
<section class="section">
  <div class="container is-max-desktop">
    <div class="columns is-centered">
      <div class="column is-full-width">
        <h2 class="title is-3">Qualitative Restuls</h2> 
        <!-- same imbalance -->
        <h3 class="title is-5">Grad-CAM Visualization</h3>
        <div class="hero-body">
          <div class="columns is-centered">
            <div class="column is-7">
              <img src="assets/signing_outside/gradcam_signer_background.png"/>
            </div>
          </div>
          <h2 class="subtitle has-text-centered">
            By virtue of our Disentangling Auto-Encoder, latent features consistently focus on the signer and background area respectively.
          </h2>
        </div>
        <!-- different imbalance -->
        <h3 class="title is-5">Gloss Predictions</h3>
        <div class="hero-body">
          <div class="columns is-centered">
            <div class="column is-12">
              <img src="assets/signing_outside/qualitative.png"/>
            </div>
          </div>
          <h2 class="subtitle has-text-centered">
            We visualize the frame-level gloss predictions from the models and show the difference when the background shifted. We observe that VAC fails to predict correct glosses with different backgrounds, while our method consistently recognizes glosses regardless of backgrounds.
          </h2>
        </div>
      </div>
    </div>
  </div>
</section>

<section class="section">
  <div class="container is-max-desktop">
    <!-- Concurrent Work. -->
    <div class="columns is-centered">
      <div class="column is-full-width">
        <h2 class="title is-3">References</h2>
        <div class="content has-text-justified">
          <p>
            [1] Koller, Oscar, Jens Forster, and Hermann Ney. "Continuous sign language recognition: Towards large vocabulary statistical recognition systems handling multiple signers." Computer Vision and Image Understanding 141 (2015): 108-125.
          </p>
          <p>
            [2] He, Kaiming, et al. "Deep residual learning for image recognition." Proceedings of the IEEE conference on computer vision and pattern recognition. 2016.
          </p>
          <p>
            [3] Min, Yuecong, et al. "Visual alignment constraint for continuous sign language recognition." Proceedings of the IEEE/CVF International Conference on Computer Vision. 2021.
          </p>
          <p>
            [4] Zhang, Hongyi, et al. "mixup: Beyond empirical risk minimization." arXiv preprint arXiv:1710.09412 (2017).
          </p>
          <p>
            [5] Yu, Fisher, et al. "Lsun: Construction of a large-scale image dataset using deep learning with humans in the loop." arXiv preprint arXiv:1506.03365 (2015).
          </p>
          <p>
            [6] Szegedy, Christian, et al. "Going deeper with convolutions." Proceedings of the IEEE conference on computer vision and pattern recognition. 2015.
          </p>
          <!-- <p>
            [6] Selvaraju, Ramprasaath R., et al. "Grad-cam: Visual explanations from deep networks via gradient-based localization." Proceedings of the IEEE international conference on computer vision. 2017.
           </p>-->
        </div>
      </div>
    </div>
  </div>
</section>

{%- if page.bibtex %}
<section class="section" id="BibTeX">
  <div class="container is-max-desktop content">
    <h2 class="title">BibTeX</h2>
    <p>
      If you find our work useful for your research, please cite with the following bibtex:
    </p>
    <pre><code>{{ page.bibtex }}</code></pre>
  </div>
</section>
{%- endif %}

<footer class="footer">
  <div class="container">
    <div class="content has-text-centered">
      {%- if page.pdf %}
      <a class="icon-link"
         href="{{ page.pdf }}">
        <i class="fas fa-file-pdf"></i>
      </a>
      {%- endif %}
      {%- if page.code %}
      <a class="icon-link" href="{{ page.code }}" class="external-link" disabled>
        <i class="fab fa-github"></i>
      </a>
      {%- endif %}
    </div>
    <div class="columns is-centered">
      <div class="column is-8">
        <div class="content">
          <p>This website is based on the <a href="https://github.com/nerfies/nerfies.github.io">Nerfies website template</a>,
            which is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/">Creative
            Commons Attribution-ShareAlike 4.0 International License</a>.
          </p>
        </div>
      </div>
    </div>
  </div>
</footer>

</body>
</html>