---
layout: page
title: Projects
---

<style>
.projects-grid {
  display: flex;
  flex-direction: column;
  gap: 1.5rem;
  margin-top: 1.5rem;
}

.proj-card {
  border: 1px solid #e2e0d8;
  border-radius: 10px;
  overflow: hidden;
  transition: border-color 0.2s, box-shadow 0.2s;
  background: #fff;
}

.proj-card:hover {
  border-color: #b0aca0;
  box-shadow: 0 2px 12px rgba(0,0,0,0.06);
}

.proj-card-inner {
  display: grid;
  grid-template-columns: 1fr 1fr;
}

.proj-card-inner.no-image {
  grid-template-columns: 1fr;
}

.proj-image {
  overflow: hidden;
  border-right: 1px solid #e2e0d8;
  min-height: 180px;
}

.proj-image img {
  width: 100%;
  height: 100%;
  object-fit: cover;
  display: block;
}

.proj-body {
  padding: 1.25rem 1.5rem;
  display: flex;
  flex-direction: column;
  gap: 0.75rem;
  justify-content: space-between;
}

.proj-category {
  font-size: 10px;
  font-weight: 600;
  letter-spacing: 0.1em;
  text-transform: uppercase;
  color: #888;
  margin: 0;
}

.proj-title {
  font-size: 15px;
  font-weight: 600;
  color: #1a1a1a;
  text-decoration: none;
  line-height: 1.4;
  display: block;
  margin: 0.25rem 0 0;
}

.proj-title:hover {
  color: #2563eb;
}

.proj-desc {
  font-size: 13px;
  color: #555;
  line-height: 1.65;
  margin: 0;
}

.proj-footer {
  display: flex;
  flex-direction: column;
  gap: 0.6rem;
  margin-top: 0.25rem;
}

.tools-row {
  display: flex;
  flex-wrap: wrap;
  gap: 5px;
}

.tool-badge {
  font-family: ui-monospace, SFMono-Regular, Menlo, monospace;
  font-size: 10px;
  padding: 3px 7px;
  border-radius: 4px;
  border: 1px solid #ddd;
  color: #555;
  background: #f5f5f3;
  letter-spacing: 0.02em;
}

.tool-badge.xl  { background: #ecfdf5; color: #166534; border-color: #bbf7d0; }
.tool-badge.vba { background: #f0fdf4; color: #15803d; border-color: #86efac; }
.tool-badge.py  { background: #eff6ff; color: #1d4ed8; border-color: #bfdbfe; }
.tool-badge.sql { background: #fffbeb; color: #92400e; border-color: #fde68a; }
.tool-badge.viz { background: #fef2f2; color: #991b1b; border-color: #fecaca; }

.proj-link {
  font-size: 11px;
  color: #2563eb;
  text-decoration: none;
  font-weight: 500;
  letter-spacing: 0.02em;
}

.proj-link:hover {
  text-decoration: underline;
}

@media (max-width: 600px) {
  .proj-card-inner {
    grid-template-columns: 1fr;
  }
  .proj-image {
    border-right: none;
    border-bottom: 1px solid #e2e0d8;
    min-height: 160px;
  }
}
</style>

<div class="projects-grid">

  <!-- PROJECT 1 -->
  <div class="proj-card">
    <div class="proj-card-inner">
      <div class="proj-image">
        <img src="https://github.com/user-attachments/assets/e99b0662-089b-44a3-90a3-0af9d285fe1c" alt="Audit Capacity Projection Model screenshot" />
      </div>
      <div class="proj-body">
        <div>
          <p class="proj-category">Workforce Planning · Excel Modelling</p>
          <a class="proj-title" href="https://github.com/jameszka997/Data-Solutions-Repository/blob/main/Audit%20Capacity%20Projection%20modelling/Audit%20Capacity%20Projection%20Model.md">
            Audit Capacity Projection Model
          </a>
          <p class="proj-desc">
            Dual-scenario workforce model forecasting month-by-month audit throughput for a 24-person regional hub team through 2025, accounting for staggered hiring, role-based training timelines, and vacation-adjusted realistic versus ideal capacity.
          </p>
        </div>
        <div class="proj-footer">
          <div class="tools-row">
            <span class="tool-badge xl">Excel</span>
            <span class="tool-badge xl">Pivot Tables</span>
            <span class="tool-badge viz">Data Visualisation</span>
            <span class="tool-badge">Scenario Modelling</span>
          </div>
          <a class="proj-link" href="https://github.com/jameszka997/Data-Solutions-Repository/blob/main/Audit%20Capacity%20Projection%20modelling/Audit%20Capacity%20Projection%20Model.md">
            View on GitHub →
          </a>
        </div>
      </div>
    </div>
  </div>

  <!-- PROJECT 2 -->
  <div class="proj-card">
    <div class="proj-card-inner no-image">
      <div class="proj-body">
        <div>
          <p class="proj-category">Exploratory Analysis · Strategic Planning</p>
          <a class="proj-title" href="https://github.com/jameszka997/Data-Solutions-Repository/blob/main/2025%20Audit%20Company%20List%20Evaluation.md">
            Audit List Data Analysis
          </a>
          <p class="proj-desc">
            Exploratory analysis of a confidential European audit company list using pivot tables and visualisations, uncovering geographic distribution patterns, company type breakdowns, priority category splits, and special audit requirements to support strategic resource planning.
          </p>
        </div>
        <div class="proj-footer">
          <div class="tools-row">
            <span class="tool-badge xl">Excel</span>
            <span class="tool-badge xl">Pivot Tables</span>
            <span class="tool-badge viz">Charts &amp; Visualisation</span>
            <span class="tool-badge sql">EDA</span>
          </div>
          <a class="proj-link" href="https://github.com/jameszka997/Data-Solutions-Repository/blob/main/2025%20Audit%20Company%20List%20Evaluation.md">
            View on GitHub →
          </a>
        </div>
      </div>
    </div>
  </div>




 <!-- PROJECT 3 -->
  <div class="proj-card">
    <div class="proj-card-inner">
      <div class="proj-image">
          <img src="https://github.com/user-attachments/assets/cd9072cb-acd3-4e19-80f0-f3e599102c14" />
        </div>
      <div class="proj-body">
        </div>
          <p class="proj-category">Power BI Dashboard · Data Visualization & Interaction</p>
          <a class="proj-title" href="https://github.com/jameszka997/Data-Solutions-Repository/blob/main/Map%20Visual/Map_Visual_readme.md">
            Project Map for interactive visualization dashboard
          </a>
          <p class="proj-desc">
            Developed an interactive Power BI dashboard using Azure Map visuals to geographically track hundreds of ongoing projects across Europe, with dynamic filtering by status, owner, and project type, fed by a daily-refreshed Excel data source.
          </p>
        </div>
        <div class="proj-footer">
          <div class="tools-row">
            <span class="tool-badge viz">Power BI</span>
            <span class="tool-badge viz">Data Visualisation</span>
            <span class="tool-badge viz">Power Query</span>
            <span class="tool-badge sql">Data Transformation</span>
            <span class="tool-badge sql">Data Import Pipeline</span>
          </div>
          <a class="proj-link" href="https://github.com/jameszka997/Data-Solutions-Repository/blob/main/Map%20Visual/Map_Visual_readme.md">
            View on GitHub →
          </a>
        </div>
      </div>
    </div>
  </div>






  <!-- ADD MORE PROJECTS BELOW — copy the block above and fill in the fields -->
  <!--
  <div class="proj-card">
    <div class="proj-card-inner no-image">
      <div class="proj-body">
        <div>
          <p class="proj-category">CATEGORY · METHOD</p>
          <a class="proj-title" href="GITHUB_LINK">Project Title</a>
          <p class="proj-desc">2–3 sentence description: what was built, what it accounts for, what it produced.</p>
        </div>
        <div class="proj-footer">
          <div class="tools-row">
            <span class="tool-badge xl">Excel</span>
            <span class="tool-badge py">Python</span>
            <span class="tool-badge sql">SQL</span>
            <span class="tool-badge vba">VBA</span>
            <span class="tool-badge viz">Power BI</span>
          </div>
          <a class="proj-link" href="GITHUB_LINK">View on GitHub →</a>
        </div>
      </div>
    </div>
  </div>
  -->

</div>
