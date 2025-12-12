<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <title>Data Scientist Portfolio</title>
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <meta name="description" content="Portfolio of a data scientist specializing in machine learning, NLP, and analytics." />

  <!-- Fonts -->
  <link rel="preconnect" href="https://fonts.googleapis.com" />
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin />
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600&family=Fira+Code:wght@400;500&display=swap" rel="stylesheet" />

  <link rel="stylesheet" href="assets/css/styles.css" />
</head>
<body>
  <div class="app-bg">
    <div class="editor-shell">

      <!-- Sidebar -->
      <aside class="sidebar">
        <div class="sidebar-title">EXPLORER</div>
        <div class="sidebar-section">
          <div class="sidebar-folder">
            <span class="chevron">▾</span>
            <span class="folder-name">PORTFOLIO</span>
          </div>
          <ul class="file-list">
            <li class="file active">about.py</li>
            <li class="file">projects.ipynb</li>
            <li class="file">skills.json</li>
            <li class="file">contact.md</li>
          </ul>
        </div>
      </aside>

      <!-- Main editor area -->
      <main class="editor">
        <!-- Tabs bar -->
        <div class="tab-bar">
          <div class="tab active">about.py</div>
          <div class="tab">projects.ipynb</div>
          <div class="tab">skills.json</div>
          <div class="tab">contact.md</div>
        </div>

        <!-- Code area -->
        <div class="code-area">
          <div class="line-numbers">
            <span>1</span>
            <span>2</span>
            <span>3</span>
            <span>4</span>
            <span>5</span>
            <span>6</span>
            <span>7</span>
            <span>8</span>
            <span>9</span>
            <span>10</span>
            <span>11</span>
            <span>12</span>
            <span>13</span>
            <span>14</span>
            <span>15</span>
            <span>16</span>
            <span>17</span>
            <span>18</span>
            <span>19</span>
            <span>20</span>
            <span>21</span>
            <span>22</span>
            <span>23</span>
            <span>24</span>
            <span>25</span>
            <span>26</span>
            <span>27</span>
            <span>28</span>
            <span>29</span>
            <span>30</span>
          </div>

          <pre class="code-block"><code>
<span class="kw">class</span> <span class="type">DataScientist</span>:

    <span class="kw">def</span> <span class="fn">__init__</span>(<span class="self">self</span>):
        <span class="self">self</span>.name = <span class="str">"Alex Morgan"</span>
        <span class="self">self</span>.role = <span class="str">"Senior Data Scientist"</span>
        <span class="self">self</span>.location = <span class="str">"San Francisco, CA"</span>
        <span class="self">self</span>.experience = <span class="num">5</span> <span class="comment"># years</span>

    <span class="kw">def</span> <span class="fn">get_bio</span>(<span class="self">self</span>) -&gt; <span class="type">str</span>:
        <span class="kw">return</span> <span class="str">"""
Passionate data scientist specializing in machine learning,
deep learning, and statistical modeling. I transform complex
data into actionable insights that drive business decisions.

My expertise spans across predictive analytics, NLP, computer
vision, and building end-to-end ML pipelines. I thrive on
solving challenging problems with elegant solutions.
"""</span>

    <span class="kw">def</span> <span class="fn">get_specializations</span>(<span class="self">self</span>) -&gt; <span class="type">List</span>[<span class="type">str</span>]:

        <span class="kw">return</span> [
            <span class="str">"Machine Learning &amp; Deep Learning"</span>,
            <span class="str">"Natural Language Processing"</span>,
            <span class="str">"Computer Vision"</span>,
            <span class="str">"Time Series Analysis"</span>,
            <span class="str">"A/B Testing &amp; Experimentation"</span>,
            <span class="str">"MLOps &amp; Model Deployment"</span>
        ]
</code></pre>
        </div>

        <!-- Status bar -->
        <footer class="status-bar">
          <div class="status-left">UTF-8   Python   Ln 1, Col 1</div>
          <div class="status-right">Data Scientist Portfolio</div>
        </footer>
      </main>
    </div>
  </div>
</body>
</html>
