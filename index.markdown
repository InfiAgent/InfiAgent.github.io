---
layout: mydefault
---

<html>

<head>
  <meta charset="utf-8">
  <meta name="description" content="InfiCoder-Eval: Systematically Evaluating Question-Answering
  for Code Large Language Models">
  <meta name="keywords" content="InfiCoder-Eval, code-generation, large-language-model, benchmark">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>InfiCoder-Eval: Systematically Evaluating Question-Answering
    for Code Large Language Models</title>

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
            <h1 class="title is-1 publication-title">InfiCoder-Eval: Systematically Evaluating Question-Answering
              for Code Large Language Models
            </h1>
            <div class="is-size-5 publication-authors">
              <span class="author-block">
                InfiCoder Team @ ByteDance Ltd. and Peking University
              </span>
              <br>
              <span class="author-block">
                <!-- Main Maintainer: <a href="mailto:linyi.li@bytedance.com">Linyi Li</a> -->
                <br>
                Team Lead: <a href="mailto:hx.yang@bytedance.com">Hongxia Yang</a>
              </span>
              <!-- <span class="author-block">
                <a href="https://xxx.github.io/">Siwei Wang</a><sup>1</sup></span>
			        <br/>
            </div>

            <div class="is-size-5 publication-authors">
              <!-- <span class="author-block"><sup>1</sup>Caption of Quận 5, Ho Chi Minh City, Vietnam</span> -->
              <!-- <span class="author-block"><sup>2</sup>Peking University,</span> -->
            </div>

            <div class="column has-text-centered">
              <div class="publication-links">
                <!-- PDF Link. -->
                <span class="link-block">
                  <a href="./static/report/inficoder_eval_report_draft.pdf"
                    class="external-link button is-normal is-rounded is-dark" target='_blank'>
                    <span class="icon">
                      <i class="ai ai-arxiv"></i>
                    </span>
                    <span>Report (draft version)</span>
                  </a>
                </span>
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
          InfiCoder-Eval is a systematic benchmark and evaluation framework for the free-form question-answering ability of code language models.
        </h2>
        <img src="static/images/inficoder-eval-main.png">
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
              Large language models for code (code LLMs)
              have made huge progress. Evaluation benchmarks
              for code LLMs, such as <a href="https://github.com/openai/human-eval">HumanEval</a>, <a href="https://ds1000-code-gen.github.io/">DS-1000</a>,
              and <a href="https://arxiv.org/abs/2108.07732">MBPP</a>, predominantly focus on code generation. But they are insufficient to evaluate code
              LLMs’ multifaceted ability. To fill this gap, we
              propose InfiCoder-Eval, a large-scale free-form
              question-answering (QA) benchmark for code.
              InfiCoder-Eval comprises 270 carefully picked
              high-quality StackOverflow questions, covering
              18 programming languages. To tackle the evaluation challenge, InfiCoder-Eval includes an evaluation framework integrating four types of model-free metrics, and domain experts design the concrete criteria for each question. As confirmed
              with human experiments, InfiCoder-Eval evaluation aligns with humans better than model-based evaluation and runs much faster at the
              same time. We conduct a systematic evaluation with InfiCoder-Eval for more than 30 code
              LLMs, leading to several interesting findings. For
              example, though open-source code LLMs show
              competitive performance with proprietary models in code generation (e.g., HumanEval), they
              still have a large gap compared to proprietary
              ones in InfiCoder-Eval and even the best proprietary LLM (GPT4) is still far from perfect (best
              open-source model Deepseek-Coder 33B Instruct
              achieves 50.34% and GPT4 achieves 58.89%).
              Furthermore, our detailed analysis reveals several
              weaknesses of current code LLMs. Benchmark,
              evaluation tools, and detailed results are all publicly available.
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
            <p>
              InfiCoder-Eval comprises 270 carefully picked high-quality Stack Overflow questions, covering 18 programming languages.
            </p>

            <img src="static/images/data_domain_stats.png">

            <p>
              We recruited five domain experts to create the benchmark and annotate the correctness evaluation criteria.
              Specifically, the InfiCoder-Eval framework integrates four types of model-free metrics for evaluating the correctness: keywords matching, blank filling, unit testing, and dialogue similarity.
            </p>

            <img src="static/images/data_examples.png">

            <p>
              Below is the question type, metric type, and length statistics.
            </p>

            <center>
              <img src="static/images/general_statistics.png">
            </center>

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
          <h2 class="title is-3">Comparison</h2>
          <div class="content has-text-justified">
            <p>Existing benchmarks weigh heavily on code generation, unit-test-based evaluation, and a limited set of programming languages. InfiCoder-Eval processes a much higher diversity to reflect real-world code LLMs’ usage scenarios and is far from saturation.</p>
            <img src="static/images/comparison.png">
          </div>
        </div>
      </div>
      <!--/ Comparison. -->
    </div>
  </section>


  <section class="section">
    <div class="container is-max-desktop">
      <!-- Perturbation and Prompt. -->
      <div class="columns is-centered has-text-centered">
        <div class="column is-four-fifths">
          <h2 class="title is-3">Prompts and Evaluation Protocol</h2>
          <div class="content has-text-justified">
            Each question contains a system prompt and content prompt.
            For questions whose responses are mainly in natural language, the system prompt is
            <div class="highlighter-rouge">
              <div class="highlight">
                <code>You are a professional assistant for programmers. By default, questions and answers are in Markdown format. You are chatting with programmers, so please answer as briefly as possible.
                </code>
              </div>
            </div>
            For other questions, the system prompt is
            <div class="highlighter-rouge">
              <div class="highlight">
                <code>You are a professional assistant for programmers. By default, questions and answers are in Markdown format.
                </code>
              </div>
            </div>
            We then format the system prompt and content prompt following each model's default instruction template.
            If no instruction template specified, we use the prompt format 
            <div class="highlight">
              <code>{system prompt}\n{content prompt}
              </code>
            </div>
            <p>We adopt <b>best@10</b> as the main evaluation metric, where 10 responses are sampled and evaluated for each question and the best score per question is recorded and summed up.
              Throughout the evaluation, we set <b>sampling temperature T to be 0.2 and top p cut-off threshold to be 0.9</b>.
              We leave the exploration of other hyperparameters as the future work.
            </p>
            <p>For score computation, we treat each question equally with one point each.
              Given 270 questions in the benchmark, the full score is 270, and we by default report the percentage score (achieved score divided by the full score which is 270).
              The one point for each question can be further decomposed into a few scoring points within each question.
              For example, a question may contain four keywords with weights 2, 1, 1, and 1 each.
              Then, matching each keyword can contribute to 0.4, 0.2, 0.2, and 0.2 points respectively to the final score.
            </p>
          </div>
        </div>
      </div>
      <!--/ Perturbation and Prompt. -->
    </div>
  </section>

  <section class="section">
    <div class="container is-max-desktop">
        <div class="columns is-centered has-text-centered">
        <div class="column is-four-fifths">
          <h2 class="title is-3">Leaderboard</h2>
        </div>
      </div>
    </div>
    <br>
    <div class="container is-max-desktop has-text-justified">
      <div class="columns is-centered has-text-centered">
        <div class="column is-four-fifths">
          <div>
            <img src="static/images/all_results.png">
          </div>
          <p>Each blue point corresponds to one open-source model, with error bars for those smaller than 30B parameters. Proprietary models are plotted as lines with uncertainty ranges.</p>
        </div>
      </div>
    </div>
    <div class="cover" id="contentCover">
      <!-- Baseline. -->
      <div class="container-t">
        <div class="row">
          <div class="col-md-12">
            <div class="infoCard">
              <div class="infoBody">
                <p align="left">
                  <div class="left"><b>Notice</b>: we set the max tokens to generate=1024 (since GPT4 generates 662 tokens without the constraint, we provide some wiggle room by setting to 1024 tokens)
                  </div>
                </p>
                <p align="left">
                  <div class="left">We evenly split the 270 benchmark questions to 135-question dev set and 135-question test set. Dev set is publicly available, and the test set is on held where evaluation is available upon request (see below for instructions). 
                  Models are ranked according to full set scores.
                  </div>
                </p>
                <p align="left">
                  <div class="left">For models with >30B parameters, we evaluate once due to resource limit, otherwise we evaluate three times and report the mean and standard deviation.
                  </div>
                </p>
                <br>
                <table class="table maintable stripe hover row-border order-column" id="maintable">
                  <thead>
                    <tr>
                      <th>Rank</th>
                      <th>Model Name</th>
                      <th># Params. (in B)</th>
                      <th>Full Set Score</th>
                      <th>Full Set Std</th>
                      <th>Dev Set Score</th>
                      <th>Dev Set Std</th>
                      <th>Test Set Score</th>
                      <th>Test Set Std</th>
                      <th></th>
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
                        <td>{{ item.size }}</td>
                      {% else %}
                        <td>/</td>
                      {% endif %}
                      <td>{{ item.score }}</td>
                      {% if item.score_std != null %}
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
                      {% endif %}
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
      <!-- Benchmarking Tutorial -->
      <div class="columns is-centered has-text-centered">
        <div class="column is-four-fifths">
          <h2 class="title is-3">Try the Benchmark!</h2>
          <div class="content has-text-justified">
            <h3>Step 0: Setup</h3>
            <ol>
              <li>Convert or save your model weights in Hugging Face Transformers format.</li>
              <li>Clone the two repositories: <a href="https://github.com/infi-coder/ffqa-evaluation-harness">Inference Repo</a> and <a href="https://github.com/infi-coder/inficoder-eval-framework">Evaluation Repo</a>.</li>
              <p>No requirement on the local directory paths.</p>
              <li>Set global environment variable: </li>
              <div class="highlight"><code>export INFERENCE_REPO_PATH=[evaluation repo]/batched_prompts/suite_v2.0.0_dev.csv</code></div>
            </ol>
            <br>
            <h3>Step 1: Generate Response for Your Model</h3>
            <ol>
              <li>Set the working directory to <a href="https://github.com/infi-coder/ffqa-evaluation-harness">Inference Repo</a>.</li>
              <p>The inference repo is forked and slightly modified from <a href="https://github.com/bigcode-project/bigcode-evaluation-harness">bigcode-evaluation-harness</a> framework. We leverage its function for inference.</p> 
              <li>Determine the prompt format to use, which corresponds to task name.</li>
              <p>We support these format for now: <code>code-ffqa-v2</code> (the default one, system + '\n' + content), <code>code-ffqa-v2-endn</code> (system + '\n' + content + '\n'), <code>code-ffqa-v2-deepseek-chat</code> (deepseek-coder-instruct format), <code>code-ffqa-v2-baichuan2</code> (baichuan2 models format), <code>code-ffqa-v2-zypher</code> (zypher-7b-beta format), <code>code-ffqa-v2-octo</code> (octopack model format), <code>code-ffqa-v2-wizard</code> (wizard-python model format), <code>code-ffqa-v2-phi</code> (phi-1.5 model format), and <code>code-ffqa-v2-inficoder</code> (our InfiCoder model format).</p>
              <p>Feel free to contribute by adding your model format, which is easy - just slightly modify <code>bigcode_eval/tasks/code_ffqa_v200.py</code> a bit.</p> 
              <li>Run batch inference to generate responses for question prompts.</li>
              <div class="highlight"><code>accelerate launch [inference repo dir]/main.py --model [your model path / hugging face hub path] --tasks [determined task name above] --batch_size [batch_size] --precision bf16 --n_samples 30 --do_sample True --temperature 0.2 --top_p 0.9 --save_generations --save_references --trust_remote_code --generation_only --max_new_tokens 1024 --save_generations_path [output raw response file path].json --eos='[EOS string]'</code></div>
              <p>This command will output two files in your working directory: <code>[output raw response file path].json</code> which stores responses and <code>references.json</code> which stores case names as the index.</p>
              <li>Export responses and case names to evaluation-capatible csv file.</li>
              <div class="highlight"><code>python3 [inference repo dir]/ffqa_processor.py [output raw response file path].json references.json [response csv file].csv</code></div>
              <p>This command will join the two output files above into one csv file <code>[response csv file].csv</code> which can be processed by the evaluation framework below.</p>
            </ol>
            <br>
            <h3>Step 2: Evaluation (Dev Set)</h3>
            <ol>
              <li>Setup the evaluation framework: <a href="https://github.com/infi-coder/inficoder-eval-framework">Evaluation Repo</a>.</li>
              <p>At this point, we only support Linux environment.</p>
              <p>Run <code>pip3 install -r requirements.txt</code>, then <code>./setup.sh</code> (time costly, usually 1-2 hours) which installs necessary compilers and packages for multi-lingual execution environment.</p>
              <li>Check the evaluation environment.</li>
              <p>Run <code>python3 env_check.py</code> to check and fix the environment incompatibility according to the console output. If the console output is "You're good to go.", then we can proceed.</p>
              <li>Unpack the csv output.</li>
              <p>Unpack the csv output file from the previous inference step into a directory where each response is stored in a separate txt.</p>
              <div class="highlight"><code>python3 adaptors/csv_response_unpacker.py [response csv file].csv [response save dir]</code></div>
              <p>We recommend to save the responses in a directory in <code>responses/</code>, i.e., let <code>[response save dir]=responses/...</code>. The above script will create the <code>[response save dir]</code> directory if it does not exist.</p>
              <li>Run main evaluation.</li>
              <div class="highlight"><code>python3 grader_main.py suite_v2.0.0_dev.yaml [response save dir]</code></div>
              <p>The evaluation takes around 15 min - 45 min.</p>
              <p>When it finishes, there are two output files: <code>results/suite_v2.0.0_dev_[response save dir base name].txt</code> (short summary) and <code>results/suite_v2.0.0_dev_[response save dir base name].yaml</code> (all details).</p>
              <p>You can also customized the output paths by <code>--result_summary_path</code> and <code>--result_detail_path</code> arguments respectively.</p>
              <li>Get statistics and print the results.</li>
              <div class="highlight"><code>python3 print_result_stat.py [result detail path] [summary txt path]</code></div>
              <p>In console output and <code>[summary txt path]</code>, a nice table will be printed, including the overall score and percentage and the sub-scores for each question type, metric type, and programming language.</p>
            </ol>
            <h3>Step 3: Evaluate (Test Set)</h3>
            <p>
              Available upon request (<a href='mailto:linyi.li@bytedance.com'>email us</a>).
            </p>
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
        <pre><code>@misc{li2023inficodereval,
  author = {InfiCoderTeam},
  title = {InfiCoder-Eval: Systematically Evaluating Question-Answering for Code Large Language Models},
  year = {2023},
  publisher = {Github Pages},
  howpublished = "\url{https://github.com/infi-coder/inficoder-eval}"
}</code></pre>
      </div>
    </div>
  </section>


  <footer class="footer">
    <div class="container">
      <div class="content has-text-centered">
        <!-- <a class="icon-link" href="https://arxiv.org/pdf/2211.11501">
          <i class="fas fa-file-pdf" style="color:white"></i>
        </a> -->
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
