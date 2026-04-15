## Featured Analytics Projects

### 1. Financial KPI Dashboarding
**Tech Stack:** Tableau, SQL, Python  
**Project Link:** [Financial Dashboard](https://github.com/Saisrinivas-kamakoti/portfolio-saisrinivaskamakoti)

Built an interactive financial analytics dashboard to monitor revenue, gross margins, customer segments, and cohort retention trends.  
The dashboard includes heatmaps, funnel views, treemaps, and cohort analysis to highlight growth opportunities and support revenue uplift strategies.

**Highlights**
- Tracked revenue and profitability across regions, periods, and customer segments
- Performed exploratory data analysis and cohort analysis to identify high-value growth opportunities
- Designed dashboard views that supported 15–20% revenue uplift strategy recommendations

---

### 2. ETL Pipeline Automation
**Tech Stack:** Python, SQL  
**Project Link:** [Portfolio Repository](https://github.com/Saisrinivas-kamakoti/portfolio-saisrinivaskamakoti)

Developed scalable ETL workflows with validation checks and monitoring logic to improve data reliability and processing efficiency.  
The project focused on pipeline health, schema validation, freshness checks, and issue tracking for production-ready data operations.

**Highlights**
- Built automated ETL pipelines with reusable validation and quality checks
- Improved data reliability and processing efficiency by 30%
- Monitored pipeline runs, SLA adherence, and failure reduction opportunities

---

### 3. Sales & Demand Forecasting
**Tech Stack:** Python, SQL, Time Series Forecasting  
**Project Link:** [Portfolio Repository](https://github.com/Saisrinivas-kamakoti/portfolio-saisrinivaskamakoti)

Created forecasting models to predict sales and demand patterns, improving planning accuracy and operational decision-making.  
The project compares actuals vs forecasts, tracks forecast bias, and supports better inventory and resource planning.

**Highlights**
- Built time series forecasting models for demand prediction
- Improved forecast accuracy by 25%
- Enabled better planning for inventory, replenishment, and resource allocation


<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Analytics Portfolio | Tableau Dashboard Concepts</title>
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Manrope:wght@400;500;700;800&family=Sora:wght@500;700;800&display=swap" rel="stylesheet">
  <link rel="stylesheet" href="analytics-dashboards.css">
</head>
<body>
  <div class="shell">
    <header class="hero">
      <nav class="topbar">
        <a class="brand" href="#financial-dashboard">
          <span class="brand-mark">AD</span>
          <span>Analytics Dashboard Portfolio</span>
        </a>
        <div class="nav-links">
          <a href="#financial-dashboard">Financial KPI</a>
          <a href="#etl-dashboard">ETL Automation</a>
          <a href="#forecast-dashboard">Forecasting</a>
        </div>
      </nav>

      <section class="hero-grid">
        <div class="hero-copy">
          <p class="eyebrow">Tableau + SQL + Python Portfolio</p>
          <h1>Dashboards</HTML>.</h1>
          <p class="hero-text">
            This page turns your analytics projects into presentation-ready Tableau dashboard concepts with KPI cards,
            filters, cohort views, quality monitoring, and forecast storytelling.
          </p>
          <div class="hero-actions">
            <a class="button button-primary" href="#financial-dashboard">Open dashboards</a>
            <a class="button button-secondary" href="index.html">Back to main page</a>
          </div>
        </div>

        <div class="hero-panel">
          <article class="hero-card">
            <p class="mini-label">Included dashboards</p>
            <div class="hero-metrics">
              <div><strong>Revenue</strong><span>Margin, segment, and cohort views</span></div>
              <div><strong>Data Ops</strong><span>Pipeline health and validation tracking</span></div>
              <div><strong>Forecasting</strong><span>Accuracy, bias, and planning signals</span></div>
            </div>
          </article>
          <article class="hero-card accent-card">
            <p class="mini-label">Portfolio angle</p>
            <h2>Built to look like Tableau dashboards, while staying editable in a simple static site.</h2>
            <p>The GitHub links now point to your portfolio repository.</p>
          </article>
        </div>
      </section>
    </header>

    <main>
      <section class="dashboard-section" id="financial-dashboard">
        <div class="section-heading">
          <div>
            <p class="eyebrow">Dashboard 01</p>
            <h2>Financial KPI Dashboarding</h2>
          </div>
          <a class="project-link light-link" href="https://github.com/Saisrinivas-kamakoti/portfolio-saisrinivaskamakoti" target="_blank" rel="noreferrer">Portfolio GitHub</a>
        </div>

        <div class="section-intro">
          <p>Interactive dashboard concept for revenue, margin, customer segments, and cohort-driven growth opportunities.</p>
          <div class="filter-row">
            <label>
              Region
              <select id="financialRegion"></select>
            </label>
            <label>
              Segment
              <select id="financialSegment"></select>
            </label>
            <label>
              Period
              <select id="financialPeriod"></select>
            </label>
          </div>
        </div>

        <div class="kpi-grid" id="financialKpis"></div>

        <div class="viz-grid viz-grid-financial">
          <article class="viz-card wide-card">
            <div class="viz-head">
              <div>
                <h3>Revenue Heatmap</h3>
                <p>Monthly revenue by region with color intensity.</p>
              </div>
            </div>
            <div id="financialHeatmap" class="heatmap"></div>
          </article>

          <article class="viz-card">
            <div class="viz-head">
              <div>
                <h3>Segment Funnel</h3>
                <p>Prospects to retained customers.</p>
              </div>
            </div>
            <div id="financialFunnel" class="funnel"></div>
          </article>

          <article class="viz-card">
            <div class="viz-head">
              <div>
                <h3>Revenue Treemap</h3>
                <p>Contribution by customer segment.</p>
              </div>
            </div>
            <div id="financialTreemap" class="treemap"></div>
          </article>

          <article class="viz-card wide-card">
            <div class="viz-head">
              <div>
                <h3>Cohort Analysis</h3>
                <p>Retention and revenue expansion by acquisition cohort.</p>
              </div>
            </div>
            <div id="financialCohorts" class="cohort-grid"></div>
          </article>
        </div>
      </section>

      <section class="dashboard-section dark-section" id="etl-dashboard">
        <div class="section-heading">
          <div>
            <p class="eyebrow">Dashboard 02</p>
            <h2>ETL Pipeline Automation</h2>
          </div>
          <a class="project-link light-link" href="https://github.com/Saisrinivas-kamakoti/portfolio-saisrinivaskamakoti" target="_blank" rel="noreferrer">Portfolio GitHub</a>
        </div>

        <div class="section-intro">
          <p>Operations dashboard for pipeline run health, validation checks, SLA adherence, and failure reduction opportunities.</p>
          <div class="filter-row">
            <label>
              Pipeline
              <select id="etlPipeline"></select>
            </label>
            <label>
              Environment
              <select id="etlEnvironment"></select>
            </label>
            <label>
              Window
              <select id="etlWindow"></select>
            </label>
          </div>
        </div>

        <div class="kpi-grid" id="etlKpis"></div>

        <div class="viz-grid">
          <article class="viz-card">
            <div class="viz-head">
              <div>
                <h3>Pipeline Health</h3>
                <p>Success rate by pipeline.</p>
              </div>
            </div>
            <div id="etlHealth" class="bar-stack"></div>
          </article>

          <article class="viz-card">
            <div class="viz-head">
              <div>
                <h3>Validation Matrix</h3>
                <p>Completeness, duplicates, schema, freshness.</p>
              </div>
            </div>
            <div id="etlValidation" class="heatmap compact-heatmap"></div>
          </article>

          <article class="viz-card wide-card">
            <div class="viz-head">
              <div>
                <h3>SLA Trend</h3>
                <p>Daily processing time against target.</p>
              </div>
            </div>
            <canvas id="etlTrendChart" width="760" height="280"></canvas>
          </article>

          <article class="viz-card wide-card">
            <div class="viz-head">
              <div>
                <h3>Issue Funnel</h3>
                <p>Rows flagged, quarantined, fixed, and promoted.</p>
              </div>
            </div>
            <div id="etlFunnel" class="funnel horizontal-funnel"></div>
          </article>
        </div>
      </section>

      <section class="dashboard-section accent-section" id="forecast-dashboard">
        <div class="section-heading">
          <div>
            <p class="eyebrow">Dashboard 03</p>
            <h2>Sales & Demand Forecasting</h2>
          </div>
          <a class="project-link" href="https://github.com/Saisrinivas-kamakoti/portfolio-saisrinivaskamakoti" target="_blank" rel="noreferrer">Portfolio GitHub</a>
        </div>

        <div class="section-intro">
          <p>Forecast performance dashboard comparing actuals vs predictions, bias by channel, and planning impact by category.</p>
          <div class="filter-row">
            <label>
              Category
              <select id="forecastCategory"></select>
            </label>
            <label>
              Channel
              <select id="forecastChannel"></select>
            </label>
            <label>
              Horizon
              <select id="forecastHorizon"></select>
            </label>
          </div>
        </div>

        <div class="kpi-grid" id="forecastKpis"></div>

        <div class="viz-grid">
          <article class="viz-card wide-card">
            <div class="viz-head">
              <div>
                <h3>Actual vs Forecast</h3>
                <p>Demand trend with forecast line and variance bars.</p>
              </div>
            </div>
            <canvas id="forecastTrendChart" width="760" height="280"></canvas>
          </article>

          <article class="viz-card">
            <div class="viz-head">
              <div>
                <h3>Forecast Accuracy</h3>
                <p>Category performance snapshot.</p>
              </div>
            </div>
            <div id="forecastAccuracy" class="bar-stack"></div>
          </article>

          <article class="viz-card">
            <div class="viz-head">
              <div>
                <h3>Bias Heatmap</h3>
                <p>Under and over-forecast patterns by month.</p>
              </div>
            </div>
            <div id="forecastBias" class="heatmap compact-heatmap"></div>
          </article>

          <article class="viz-card wide-card">
            <div class="viz-head">
              <div>
                <h3>Planning Actions</h3>
                <p>What operations teams do with the model output.</p>
              </div>
            </div>
            <div id="forecastActions" class="action-grid"></div>
          </article>
        </div>
      </section>
    </main>
  </div>

  <script src="analytics-dashboards.js"></script>
</body>
</html>
