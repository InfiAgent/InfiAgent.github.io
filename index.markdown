---
layout: mydefault
---

<html>

<head>
  <meta charset="utf-8">
  <meta name="description" content="InfiAgent-DABench: Evaluating Agents on Data Analysis Tasks">
  <meta name="keywords" content="InfiAgent-DABench, code-generation, large-language-model, benchmark">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>InfiAgent-DABench: Evaluating Agents on Data Analysis Tasks</title>

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

  

  <script defer src="./static/js/fontawesome.all.min.js"></script>
  <script src="./static/js/bulma-carousel.min.js"></script>
  <script src="./static/js/bulma-slider.min.js"></script>
  <script src="./static/js/index.js"></script>

  <script type="text/javascript" async
  src="https://cdnjs.cloudflare.com/ajax/libs/mathjax/2.7.7/MathJax.js?config=TeX-AMS_HTML">
  </script>
  <script type="text/x-mathjax-config">
  MathJax.Hub.Config({
    tex2jax: {
      inlineMath: [['$', '$'], ['\\(', '\\)']],
      displayMath: [['$$', '$$'], ['\\[', '\\]']],
      processEscapes: true
    }
  });
  </script>

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
        <a class="navbar-item" href="hhttps://github.com/InfiAgent/InfiAgent/tree/main">
          <span class="icon">
            <i class="fas fa-home"></i>
          </span>
        </a>

        <div class="navbar-item has-dropdown is-hoverable">
          <a class="navbar-link">
            More
          </a>
          <div class="navbar-dropdown">
            <a class="navbar-item" href="https://github.com/InfiAgent/InfiAgent/tree/main/examples/DA-Agent">
              InfiAgent-DABench
            </a>
          </div>
        </div>
      </div>

    </div>
  </nav>

  <div class="container">
    <div class="column has-text-centered">
      
    </div>
  </div>

  <div class="container">
    <div class="column has-text-centered">
      <img style="max-width: 200px; margin-bottom: -50px;" src="static/images/infiagent_logo.png">
    </div>
  </div>

  <section class="hero">
    <div class="hero-body">
      <div class="container is-max-desktop">
        <div class="columns is-centered">
          <div class="column has-text-centered">
            <h1 class="title is-1 publication-title">ICML2024: InfiAgent-DABench: Evaluating Agents on Data Analysis Tasks
            </h1>
        <div class="is-size-5 publication-authors">
              <span class="author-block">
                Xueyu Hu<sup>1</sup>, Ziyu Zhao<sup>1</sup>, Shuang Wei<sup>2</sup>, Ziwei Chai<sup>1</sup>, Qianli Ma<sup>3</sup>,
              </span>
              <br>
              <span class="author-block">
                Guoyin Wang<sup>3</sup>, Xuwu Wang<sup>3</sup>, Jing Su<sup>3</sup>, Jingjing Xu<sup>3</sup>, Ming Zhu<sup>3</sup>, Yao Cheng<sup>3</sup>, Jianbo Yuan<sup>3</sup>
              </span>
              <br>
              <span class="author-block">
                Jiwei Li<sup>1</sup>, Kun Kuang<sup>1</sup>, Yang Yang<sup>1</sup>, Hongxia Yang<sup>3</sup>, Fei Wu<sup>1</sup>
              </span>
          </div>

        <div class="is-size-5 publication-authors">
		<span class="author-block"><sup>1</sup>Zhejiang University</span>
		<span class="author-block"><sup>2</sup>Rochester Institute of Technology</span>
		<span class="author-block"><sup>3</sup>ByteDance Inc.</span>
        </div>

            <div class="column has-text-centered">
              <div class="publication-links">
	      <!-- PDF Link. -->
	      <span class="link-block">
	        <a href="https://arxiv.org/abs/2401.05507"
		  class="external-link button is-normal is-rounded is-dark" target='_blank'>
		  <span class="icon">
		    <i class="ai ai-arxiv"></i>
		  </span>
		  <span>Paper</span>
	        </a>
	      </span>
                
                <!-- Dataset Link. -->
                <span class="link-block">
                  <a href="https://github.com/InfiAgent/InfiAgent/tree/main"
                     class="external-link button is-normal is-rounded is-dark" target='_blank'>
                    <span class="icon">
                      <i class="fab fa-github"></i>
                    </span>
                    <span>Project Repo</span>
                  </a>
                  <a href="https://github.com/InfiAgent/InfiAgent/tree/main/examples/DA-Agent"
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
          InfiAgent-DABench is a project to build and evalute agents for advanced data analysis. Agent evaluation has been an open and challenging problem. 
        </h2>
        <img src="static/images/framework.png">
      </div>
    </div>
  </section>



  <section class="section">
    <div class="container is-max-desktop">
        <div class="columns is-centered has-text-centered">
        <div class="column is-four-fifths">
          <h2 class="title is-3">Leaderboard</h2>

          <div class="content has-text-justified">
          <p>In this section, we furnish a comprehensive evaluation of both close-source LLMs such as GPT-4 and GPT-3.5, as well as widely-utilized open-source LLMs. In addition, we test our DAAgent, which is an agent for data analysis with instruction-tuning.</p>
           <img src="static/images/main_results.png">
           </div>
        </div>
      </div>
    </div>
    <!-- <br> -->
    <!-- <div class="container is-max-desktop has-text-justified">
      <div class="columns is-centered has-text-centered">
        <div class="column is-four-fifths">
          <div>
            <img src="static/images/all_results.png">
          </div>
          <p>Each blue point corresponds to one open-source model, with error bars for those smaller than 30B parameters. Proprietary models are plotted as lines with uncertainty ranges.</p>
        </div>
      </div>
    </div> -->
    <div class="cover" id="contentCover">
      <!-- Baseline. -->
      <div class="container-t">
        <div class="row">
          <div class="col-md-12">
            <div class="infoCard">
              <div class="infoBody">
                <p align="left">
                
               
                  <div class="left"><b>Notice</b>: We set temperature=0.2, top_p=1.0 and frequency_penalty=0.0 for all the models.  
                  <!-- <p style="color: red;"> Regrettably, the open-source LLMs enumerated below are currently incapable of adhering to agent directives or delivering substantively meaningful responses. In response to this limitation, we have developed a Supervised Fine-Tuning (SFT) dataset aimed at refining these models. For these open-source LLMs, the table below delineates the enhancements observed post-finetuning. Please anticipate the imminent release of both the SFT dataset and its comprehensive details. </p> -->
                  </div>
                 
                </p>
                <!-- <p align="left">
                  <div class="left">We evenly split the 270 benchmark questions to 135-question dev set and 135-question test set. Dev set is publicly available, and the test set is on held where evaluation is available upon request (see below for instructions). 
                  Models are ranked according to full set scores.
                  </div>
                </p>
                <p align="left">
                  <div class="left">For models with >30B parameters, we evaluate once due to resource limit, otherwise we evaluate three times and report the mean and standard deviation.
                  </div>
                </p> -->
                <br>
                <table class="table maintable stripe hover row-border order-column" id="maintable">
                  <thead>
                    <tr>
                      <th>Rank</th>
                      <th>Model Name</th>
                      <th># Params. (in B)</th>
                      <th>Proportional Accuracy by Subquestions</th>
                      <th>Accuracy by Questions</th>
                      <th>Uniform Accuracy by Subquestions</th>
                      <!-- <th>Dev Set Std</th>
                      <th>Test Set Score</th>
                      <th>Test Set Std</th>
                      <th></th> -->
                    </tr>
                  </thead>
                  <tbody>
                    {% for item in site.data.leaderboard.records %}
                    <tr>
                      <td>{{ item.rank }}</td>
                      {% if item.link != null %}
                        <td><a href="{{ item.link }}">{{ item.title }}</a></td>
                      {% else %}
                        <td>{{ item.title }}</td>
                      {% endif %}
                      {% if item.size != null %}
                        <td class="dt-center">{{ item.size }}</td>
                      {% else %}
                        <td class="dt-center">/</td>
                      {% endif %}
                      <!-- <td>{{ item.score }}</td> -->
                      <td class="dt-center">{{ item.aps_score }}</td>
                      <td class="dt-center">{{ item.as_score }}</td>
                      <td class="dt-center">{{ item.a_score }}</td>
                      <!-- {% if item.score_std != null %}
                        <td>{{ item.score_std }}</td>
                      {% else %}
                        <td></td>
                      {% endif %}
                      <td>{{ item.devscore }}</td>
                      {% if item.devscore_std != null %}
                        <td>{{ item.devscore_std }}</td>
                      {% else %}
                        <td></td>
                      {% endif %}
                      <td>{{ item.testscore }}</td>
                      {% if item.testscore_std != null %}
                        <td>{{ item.testscore_std }}</td>
                      {% else %}
                        <td></td>
                      {% endif %} -->
                      <td>{{ item.comment }}</td>
                    </tr>
                    {% endfor %}
                  </tbody>
                </table>
              </div>
            </div>
          </div>

        </div>
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
              The advent of Large Language Models (LLMs) has spurred the development of LLM-augmented Autonomous Agents (LAAs). These agents are capable of generating and executing code through ongoing interactions between their core LLM and the code execution environment. In this project, we introduce InfiAgent-DABench, the first benchmark specifically designed to evaluate LLM-based agents in data analysis tasks. This benchmark contains DAEval, a dataset consisting of data analysis questions derived from CSV files, and an agent framework to evaluate LLMs as data analysis agents.
              
              <!-- we introduce Infinite Agent (InfiAgent), a LAA focused data analysis and code writing. We have developed an automatic evaluation benchmark (InfiAgent-Eval), which covers various data analysis topics such as summary statistics, correlation analysis, and data transformation, providing a comprehensive means for quantitatively assessing LAAs' performance.  -->
              This page describes the details of InfiAgent-DABench framework, including features such as dataset construction, evaluation metrics, analytical assessment, and the procedural details about pipeline onboarding. 
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
          <h2 class="title is-3">Dataset Construction</h2>
          <div class="content has-text-justified">


          We build data analysis query and response given existing csv files.  Here is the construction pipeline. 
          <img src="static/images/dataset_construction_eval.png"> 
            
            We split the dataset into a validation set and a test set. The validation dataset contains 311 questions with 55 csv files. We only public the validation set to avoid data leakage. Here're some examples:
	  <img src="static/images/question_examples.png"> 
     	    We categorize CSV files within the dataset into nine distinct categories, determined by their respective domains:

            <ul>
              <li>Finance and Economics </li>
              <li>Health and Medical</li>
              <li>Demographics and Social Science</li>
              <li>Marketing and Consumer Behavior</li>
              <li>Energy and Environmental Monitoring</li>
              <li>Transportation, Logistics, and Tourism</li>
              <li>Culture, Entertainment, and Media</li>
              <li>Scientific Research and Technology</li>
              <li>Other Categories</li>
            </ul>

            <p>Below is the pie chart depicting the categorical distribution:</p>

             <img src="static/images/domains.png">

            <p>We conduct statistical analyses on the individual concepts associated with each question, accounting for scenarios where a question encompasses multiple concepts:</p>

            <img src="static/images/concepts.png">

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
          <h2 class="title is-3">Evaluation</h2>
          <div class="content has-text-justified">

            
            <p>For closed-form questions, we prompt LLMs with question description. Considering that most models hardly follow the format requirements, we add a reformat step for all models by using gpt-3.5-turbo-16k to format the responses given the format requirements. Here's a figure illustrating this process: </p>
		        <img src="static/images/case-study-eval-data.png">
          </div>
        </div>
      </div>
      <!--/ Comparison. -->
    </div>
  </section>

  <section class="section">
    <div class="container is-max-desktop">
      <!-- Comparison. -->
      <div class="columns is-centered has-text-centered">
        <div class="column is-four-fifths">
          <h2 class="title is-3">Metrics</h2>
          <div class="content has-text-justified">

            <!-- <img src="static/images/leaderboard.jpeg"> -->
            
            For closed-form questions, we have defined the following metrics:

Proportional Accuracy by Subquestions (PASQ):
$$
\text{PSAQ} = \frac{1}{N} \sum_{i=1}^{N} \left( \frac{1}{M_i} \sum_{j=1}^{M_i} I_{ij} \right)
$$
Here, $N$ is the total number of questions, $M_i$ is the number of subquestions for the i-th question, and $I_{ij}$ is the indicator function for the j-th subquestion of the i-th question.
Accuracy by Questions (ABQ):
$$
\text{ABQ} = \frac{1}{N} \sum_{i=1}^{N} \left( \prod_{j=1}^{M_i} I_{ij} \right)
$$
In this expression, the product 
$\prod_{j=1}^{M_i} I_{ij}$ equals 1 if all subquestions of the \(i\)-th question are answered correctly, and 0 otherwise.
Uniform Accuracy by Subquestions (UASQ):
$$
\text{UASQ} = \frac{1}{\sum_{i=1}^{N} M_i} \sum_{i=1}^{N} \sum_{j=1}^{M_i} I_{ij}
$$
Here, the total accuracy is the sum of the values of the indicator function across all subquestions, normalized by the total number of subquestions in the dataset.
          </div>
        </div>
      </div>
      <!--/ Comparison. -->
    </div>
  </section>

  

  
  <section class="section">
    <div class="container is-max-desktop">
      <!-- Benchmarking Tutorial -->
      <div class="columns is-centered has-text-centered">
        <div class="column is-four-fifths">
          <h2 class="title is-3">Pipeline Onboarding</h2>
          <div class="content has-text-justified">
            <h3>Setup</h3>
            <ol>
		<li>Please initialize the environment using the following code:</li>
              <pre><code>conda create -n agent python==3.9.12
pip3 install -r requirements.txt</code></pre>
		    <li>We also build a Python code sandbox in our pipeline based on docker, you can use the following code to build your docker image:</li>
		    <pre><code>docker build -t myimg .</code></pre>
            </ol>
            <br>
            <h3>Example 1: Demo Usage</h3>
            <ol>
              <li>You can easily use the following command to start a demo using APIs.</li>
		    <pre><code># initialize poetry
poetry init
# Supported LLM: OPEN_AI, AZURE_OPEN_AI
# api_key is required for API-based models
bash run_demo.sh --llm AZURE_OPEN_AI --api_key 123</code></pre>
              <li>After running the above code, an interactive frontend interface will be displayed.</li> 
		    <img src="static/images/demo_fig.png">
              <li>You can enter prompts in the dialogue box, and if you need to upload a file, you can select the file for upload in the "browse files" section.</li>
              <li>Click the "run code interpreter" button, and the backend will execute our pipeline. The agent will generate code and execute it in the sandbox, and the results will be returned on the interactive page upon completion.</li>
            </ol>
            <br>
            <h3>Example 2: Running With Local Models</h3>
            <ol>
              <li>Our local LLM service is developed on vLLM. First, you can start a vLLM model serving by running this command:</li>
		    <pre><code># Take llama-2-7b as an example
python3 src/activities/vllm_api_server.py --model "meta-llama/Llama-2-7b-hf"  --served_model_name "meta-llama/Llama-2-7b-hf"</code></pre>
              <p>At this point, we only support Linux environment.</p>
              <li>You can try this command if the serving is successfully starting:</li>
	      <pre><code>curl http://localhost:8000/v1/completions \
    -H "Content-Type: application/json" \
    -d '{
        "model": "meta-llama/Llama-2-7b-hf",
        "prompt": "San Francisco is a",
        "max_tokens": 7,
        "temperature": 0
    }'</code></pre>
              <li>Then you can run the demo following this command:</li>
	      <pre><code>bash run_demo.sh --llm "meta-llama/Llama-2-7b-hf"</code></pre>
            </ol>
            <br>
            <h3>Example 3: Running Without Front-end</h3>
	<ol>
		<p>Our demo is designed to default to the use of the front-end. If you prefer not to use the front-end and instead perform command-line operations or process large amounts of data, you can refer to the following commands:</p>
		<pre><code># Run with API.
python3 ./src/activities/eval.py --llm AZURE_OPEN_AI --api_key 123
# Run with local model.Take llama-2-7b as an example.
python3 ./src/activities/eval.py --llm "meta-llama/Llama-2-7b-hf"</code></pre>
	</ol>
          </div>
        </div>
      </div>
      <!--/ Benchmarking Tutorial -->
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
        <pre><code>@misc{hu2024infiagentdabench,
      title={InfiAgent-DABench: Evaluating Agents on Data Analysis Tasks}, 
      author={Xueyu Hu and Ziyu Zhao and Shuang Wei and Ziwei Chai and Guoyin Wang and Xuwu Wang and Jing Su and Jingjing Xu and Ming Zhu and Yao Cheng and Jianbo Yuan and Kun Kuang and Yang Yang and Hongxia Yang and Fei Wu},
      year={2024},
      eprint={2401.05507},
      archivePrefix={arXiv},
      primaryClass={cs.CL}
}</code></pre>
      </div>
    </div>
  </section>


  <footer class="footer">
    <div class="container">
      <div class="content has-text-centered">
        <!-- <a class="icon-link" href="./static/report/inficoder_eval_report_draft.pdf">
          <i class="fas fa-file-pdf" style="color:white"></i>
        </a>
        <a class="icon-link" href="https://github.com/infi-coder" class="external-link" disabled>
          <i class="fab fa-github" style="color:white"></i>
        </a> -->
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
      $('.mainTable').DataTable({ordering: true, order: [[3, 'desc']], columns: [{ "type": "num" },{ "type": "html" },{ "type": "num" },{ "type": "num-fmt" },{ "type": "num-fmt" },{ "type": "num-fmt" }]});
    } );
  </script>

</body>

</html>
