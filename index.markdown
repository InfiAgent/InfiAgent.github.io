---
layout: mydefault
---

<html>

<head>
  <meta charset="utf-8">
  <meta name="description" content="InfiAgent: An Open-source Agent Framework">
  <meta name="keywords" content="InfiAgent-DS, code-generation, large-language-model, benchmark">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>InfiAgent: Building and Evaluating Agent on Data Analysis</title>

  <link href="https://fonts.googleapis.com/css?family=Google+Sans|Noto+Sans|Castoro" rel="stylesheet">

  <link rel="stylesheet" href="./static/css/bulma.min.css">
  <link rel="stylesheet" href="./static/css/bulma-carousel.min.css">
  <link rel="stylesheet" href="./static/css/bulma-slider.min.css">
  <link rel="stylesheet" href="./static/css/fontawesome.all.min.css">
  <link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/jpswalsh/academicons@1/css/academicons.min.css">
  <link rel="stylesheet" href="./static/css/index.css">

  <link rel="stylesheet" href="./bower_components/bootstrap/dist/css/bootstrap.table.min.css">
  <!--  <link rel="stylesheet" href="bower_components/bootstrap/dist/css/bootstrap.min.css">-->
  <link rel="stylesheet" href="./stylesheets/layout.css">
  <link rel="stylesheet" href="./stylesheets/index.css">

  <!-- for print the table -->
  <script type="text/javascript" charset="utf8" src="https://code.jquery.com/jquery-3.6.0.slim.min.js"></script>

  <link rel="stylesheet" type="text/css" href="https://cdn.datatables.net/1.11.3/css/jquery.dataTables.css">
  <script type="text/javascript" charset="utf8" src="https://cdn.datatables.net/1.11.3/js/jquery.dataTables.js"></script>

  <link rel="stylesheet" type="text/css" href="https://cdn.datatables.net/1.11.3/css/dataTables.bootstrap5.min.css">
  <script src="https://cdn.datatables.net/1.11.3/js/dataTables.bootstrap5.min.js"></script>

  <link rel="icon" href="./static/images/inficoder_eval_logo2.png">

  <script defer src="./static/js/fontawesome.all.min.js"></script>
  <script src="./static/js/bulma-carousel.min.js"></script>
  <script src="./static/js/bulma-slider.min.js"></script>
  <script src="./static/js/index.js"></script>
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
        <a class="navbar-item" href="https://github.com/infi-coder">
          <span class="icon">
            <i class="fas fa-home"></i>
          </span>
        </a>

        <div class="navbar-item has-dropdown is-hoverable">
          <a class="navbar-link">
            More
          </a>
          <div class="navbar-dropdown">
            <a class="navbar-item" href="https://github.com/infi-coder">
              InfiCoder Organization
            </a>
          </div>
        </div>
      </div>

    </div>
  </nav>

  <div class="container">
    <div class="column has-text-centered">
      <img style="max-width: 200px; margin-bottom: -50px;" src="static/images/inficoder_eval_logo2.png">
    </div>
  </div>

  <section class="hero">
    <div class="hero-body">
      <div class="container is-max-desktop">
        <div class="columns is-centered">
          <div class="column has-text-centered">
            <h1 class="title is-1 publication-title">InfiAgent-Eval: Evaluating Agent on Data Analysis
            </h1>
            <div class="is-size-5 publication-authors">
              <span class="author-block">
                InfiAgent Team @ ByteDance Ltd. and Zhejiang University 
              </span>
              <br>
              <!-- <span class="author-block">
                Main Maintainer: <a href="mailto:linyi.li@bytedance.com">Linyi Li</a>
                <br>
                Team Lead: <a href="mailto:hx.yang@bytedance.com">Hongxia Yang</a>
              </span> -->
              <!-- <span class="author-block">
                <a href="https://xxx.github.io/">Siwei Wang</a><sup>1</sup></span>
			        <br/> -->
            </div>

            <div class="is-size-5 publication-authors">
              <!-- <span class="author-block"><sup>1</sup>Caption of Quận 5, Ho Chi Minh City, Vietnam</span> -->
              <!-- <span class="author-block"><sup>2</sup>Peking University,</span> -->
            </div>

            <div class="column has-text-centered">
              <div class="publication-links">
                
                <!-- Dataset Link. -->
                <span class="link-block">
                  <a href="https://github.com/infi-coder/ffqa-evaluation-harness"
                     class="external-link button is-normal is-rounded is-dark" target='_blank'>
                    <span class="icon">
                      <i class="fab fa-github"></i>
                    </span>
                    <span>Inference Repo</span>
                  </a>
                  <a href="https://github.com/infi-coder/inficoder-eval-framework"
                     class="external-link button is-normal is-rounded is-dark" target='_blank'>
                    <span class="icon">
                      <i class="fab fa-github"></i>
                    </span>
                    <span>Evaluation Repo</span>
                  </a>
                </span>
                <!-- Twitter Link. -->
                <!-- <span class="link-block">
                  <a href="https://twitter.com/taoyds/status/1595086401309388801"
                    class="external-link button is-normal is-rounded is-dark">
                    <span class="icon">
                      <i class="fab fa-twitter"></i>
                    </span>
                    <span>Twitter</span>
                  </a>
                </span> -->
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>


  <section class="hero teaser">
    <div class="container is-max-desktop">
      <div class="hero-body">
        <h2 class="subtitle has-text-centered">
          InfiAgent is a project to build and evalute agent. We start from data analysis and build an agent DA-Agent and a benchmark DA-Agent-Eval. 
        </h2>
        <img src="static/images/framework.png">
      </div>
    </div>
  </section>


  <section class="section">
    <div class="container is-max-desktop">
      <!-- Abstract. -->
      <div class="columns is-centered has-text-centered">
        <div class="column is-four-fifths">
          <h2 class="title is-3">Overview</h2>
          <div class="content has-text-justified">
            <p>
              The advent of Large Language Models (LLMs) has spurred the development of LLM-augmented Autonomous Agents (LAAs). These agents are capable of generating and executing code through ongoing interactions between their core LLM and the code execution environment. In this project, we introduce Infinite Agent (InfiAgent), a LAA focused data analysis and code writing. Our agent is fine-tuned on multiple open-sourced LLMs including Llama2, chatGLM3, and Code Llama. The fine-tuning process employs a unique pipeline for Supervised Fine-Tuning (SFT) data collection, involving the creation and optimization of ReAct conversations using GPT. Furthermore, we have developed a GPT-enabled automatic evaluation benchmark question set, which covers various data analysis aspects such as visualization, correlation analysis, and data transformation, providing a comprehensive means for quantitatively assessing LAAs' performance across diverse tasks. Our preliminary results suggest that Infinite Agent could significantly advance the field of autonomous code generation and execution, with potential implications in areas such as software development, data science, and automated problem-solving.
            </p>
          </div>
        </div>
      </div>
      <!--/ Abstract. -->
    </div>
  </section>


  <section class="section">
    <div class="container is-max-desktop">
      <!-- Example. -->
      <div class="columns is-centered has-text-centered">
        <div class="column is-four-fifths">
          <h2 class="title is-3">Statistics and Examples</h2>
          <div class="content has-text-justified">
            
            We classify files used in the evaluation dataset into 9 categories based on their domains:

            - Finance and Economics
            - Health and Medical
            - Demographics and Social Science
            - Marketing and Consumer Behavior
            - Energy and Environmental Monitoring
            - Transportation, Logistics, and Tourism
            - Culture, Entertainment, and Media
            - Scientific Research and Technology
            - Other Categories

            Here's the pie chart for the file categorization:

             <img src="static/images/domain.png">

            We also do statistics on the concepts involved by each question (if a question involve multiple concepts, we calculate every concept.)

            <img src="static/images/concept.png">

          </div>
        </div>
      </div>
      <!--/ Example. -->
    </div>
  </section>

  <section class="section">
    <div class="container is-max-desktop">
      <!-- Comparison. -->
      <div class="columns is-centered has-text-centered">
        <div class="column is-four-fifths">
          <h2 class="title is-3">Metrics and Results</h2>
          <div class="content has-text-justified">

          <img src="static/images/leaderboard.jpeg">
          For closed-form questions, 

          - Accuracy proportional by subquestions: All the questions have a same weight and every subquestion shares the weight equally, which means a question contains more subquestions, every subquestion under it takes a lighter weight.

          - Accuracy by questions: Only all the subquestions under the question answered correctly we consider the question right.
          - Accuracy by subquestions: All the subquestions have a same weight.

          We set temperature=0.2, top_p=1.0 and frequency_penalty=0.0 for all the models.


          </div>
        </div>
      </div>
      <!--/ Comparison. -->
    </div>
  </section>


  <!-- <section class="section" id="Acknowledgement">
    <div class="container is-max-desktop content">
      <div class="bibtex-body">
        <h2 class="title">Acknowledgement</h2>
        <p>...</p>
      </div>
    </div>
  </section> -->

  <section class="section" id="BibTeX">
    <div class="container is-max-desktop content">
      <div class="bibtex-body">
        <h2 class="title">BibTeX</h2>
        <pre><code>@misc{li2023inficodereval,
  author = {InfiAgent Team},
  title = {InfiAgent: Building and Evaluating Agent on Data Analysis},
  year = {2023},
  publisher = {Github Pages},
  howpublished = "\url{https://infiagent.github.io/}"
}</code></pre>
      </div>
    </div>
  </section>


  <footer class="footer">
    <div class="container">
      <div class="content has-text-centered">
        <a class="icon-link" href="./static/report/inficoder_eval_report_draft.pdf">
          <i class="fas fa-file-pdf" style="color:white"></i>
        </a>
        <a class="icon-link" href="https://github.com/infi-coder" class="external-link" disabled>
          <i class="fab fa-github" style="color:white"></i>
        </a>
      </div>
      <div class="columns is-centered">
        <div class="column is-8">
          <div class="content">
            <p>
              This website is adapted from <a href="https://ds1000-code-gen.github.io/">ds1000-code-gen.github.io</a> and is licensed under a <a rel="license"
                href="http://creativecommons.org/licenses/by-sa/4.0/">Creative
                Commons Attribution-ShareAlike 4.0 International License</a>.
            </p>
            <p>
              This means you are free to borrow the <a href="https://github.com/infi-coder/inficoder-eval">source
                code</a> of this website,
              we just ask that you link back to this page in the footer.
            </p>
          </div>
        </div>
      </div>
    </div>
  </footer>
  
  <script>
    $(document).ready( function () {
      $('.mainTable').DataTable({ordering: true, order: [[3, 'desc']], columns: [{ "type": "num" },{ "type": "html" },{ "type": "num" },{ "type": "num-fmt" },{ "type": "num-fmt" },{ "type": "num-fmt" },{ "type": "num-fmt" },{ "type": "num-fmt" },{ "type": "num-fmt" },{ "type": "html", "orderable": false }]});
    } );
  </script>

</body>

</html>
