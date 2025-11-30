<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Inferential Statistics — README</title>
  <style>
    :root{--bg:#0f172a;--card:#0b1220;--muted:#94a3b8;--accent:#7c3aed;--glass:rgba(255,255,255,0.03)}
    body{font-family:Inter, ui-sans-serif, system-ui, -apple-system, 'Segoe UI', Roboto, 'Helvetica Neue', Arial; background:linear-gradient(180deg,#071024 0%, #07193a 100%); color:#e6eef8; margin:0; padding:40px;}
    .container{max-width:900px;margin:0 auto;background:var(--card);padding:28px;border-radius:12px;box-shadow:0 6px 30px rgba(2,6,23,0.6);}
    h1{margin:0 0 8px;font-size:28px}
    p.lead{color:var(--muted);margin-top:0}
    section{margin-top:22px}
    h2{font-size:18px;margin:14px 0}
    ul{margin:8px 0 0 20px}
    pre{background:var(--glass);padding:12px;border-radius:8px;overflow:auto;color:#dbeafe}
    table{width:100%;border-collapse:collapse;margin-top:8px}
    th,td{padding:8px 10px;text-align:left;border-bottom:1px solid rgba(255,255,255,0.04);font-size:14px}
    th{color:#cfe8ff;background:rgba(255,255,255,0.02)}
    .note{color:var(--muted);font-size:13px;margin-top:8px}
    .cta{display:inline-block;margin-top:14px;padding:8px 12px;border-radius:8px;background:linear-gradient(90deg,var(--accent),#4f46e5);color:white;text-decoration:none}
    footer{color:var(--muted);font-size:13px;margin-top:20px}
  </style>
</head>
<body>
  <div class="container">
    <header>
      <h1>Inferential Statistics — Easy Explanation</h1>
      <p class="lead">Make conclusions or predictions about a population by studying a sample.</p>
    </header>

    <section>
      <h2>Why we need Inferential Statistics</h2>
      <p>Because we cannot measure everyone in the population. For example, to estimate the average height of all college students in India we might measure a sample of 1,000 students and infer about the whole population.</p>
    </section>

    <section>
      <h2>Two Main Goals</h2>
      <ol>
        <li><strong>Estimation</strong> — use a sample to estimate a population parameter (mean, proportion, variance, SD).
          <ul>
            <li><em>Point estimate</em> — single value (e.g., sample mean = 165 cm).</li>
            <li><em>Interval estimate</em> — confidence interval (e.g., 160–170 cm).</li>
          </ul>
        </li>
        <li><strong>Hypothesis testing</strong> — test a claim about a population (e.g., bulbs last 1000 hours on average).</li>
      </ol>
    </section>

    <section>
      <h2>Key Concepts</h2>
      <ul>
        <li><strong>Population</strong> — the entire group of interest.</li>
        <li><strong>Sample</strong> — a subset of the population.</li>
        <li><strong>Sampling error</strong> — difference between sample result and true population value.</li>
        <li><strong>Sampling distribution</strong> — distribution of a statistic (e.g., sample mean) over many samples.</li>
        <li><strong>Central Limit Theorem (CLT)</strong> — when n ≥ 30, the sampling distribution of the mean is approximately normal, regardless of population shape.</li>
      </ul>
    </section>

    <section>
      <h2>Hypothesis Testing — Simple Steps</h2>
      <ol>
        <li>State hypotheses: <code>H0</code> (no change) and <code>H1</code> (there is change).</li>
        <li>Choose significance level: commonly <code>α = 0.05</code>.</li>
        <li>Compute test statistic (z, t, χ², F, etc.).</li>
        <li>Find p-value.</li>
        <li>Decision: if <code>p &lt; α</code> → reject <code>H0</code>; else fail to reject <code>H0</code>.</li>
      </ol>
    </section>

    <section>
      <h2>Common Inferential Tests</h2>
      <table>
        <thead>
          <tr><th>Test</th><th>When used?</th></tr>
        </thead>
        <tbody>
          <tr><td>Z-test</td><td>Sample size &gt;= 30, or population σ known</td></tr>
          <tr><td>T-test</td><td>Sample size &lt; 30, population σ unknown</td></tr>
          <tr><td>Chi-square test</td><td>Categorical data (goodness-of-fit, independence)</td></tr>
          <tr><td>ANOVA</td><td>Compare more than 2 group means</td></tr>
          <tr><td>Correlation</td><td>Relationship between two variables</td></tr>
          <tr><td>Regression</td><td>Predict one variable using another</td></tr>
        </tbody>
      </table>
      <p class="note">Tip: use a Z-test when σ is known or n is large; otherwise prefer t-test.</p>
    </section>

    <section>
      <h2>Quick Reference — CLT &amp; Sample Size</h2>
      <p class="note">Rule of thumb: when <strong>n ≥ 30</strong>, the sampling distribution of the mean is approximately normal (CLT), which simplifies inference.</p>
    </section>

    <footer>
      <p>Created for a GitHub README — copy this HTML into your <code>README.md</code> or a standalone <code>.html</code> file.</p>
      <a class="cta" href="#">Use this as README</a>
    </footer>
  </div>
</body>
</html>
