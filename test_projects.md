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
  object-fit: contain;
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
          <img src="https://github.com/user-attachments/assets/cd9072cb-acd3-4e19-80f0-f3e599102c14" alt="Project Map dashboard screenshot" />
        </div>
      <div class="proj-body">
        <div>
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




<!-- PROJECT 4 -->
  <div class="proj-card">
    <div class="proj-card-inner">
      <div class="proj-image">
          <img src="https://github.com/user-attachments/assets/bd9970d6-d942-4941-9441-ab9e7d442292" alt="Project Timeline visual screenshot" />
        </div>
      <div class="proj-body">
        <div>
          <p class="proj-category">Power BI Dashboard · Project Timeline Gantt Chart</p>
          <a class="proj-title" href="https://github.com/jameszka997/Data-Solutions-Repository/blob/main/Map%20Visual/Map_Visual_readme.md">
            Project Timeline Tracker (Gantt Chart)
          </a>
          <p class="proj-desc">
            Built an interactive Power BI Gantt dashboard consolidating 100+ projects across multiple owners into a centrally tracked, auto-refreshing timeline with colour-coded milestones and dynamic filtering to replace scattered Excel-based manual reporting.
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
          <a class="proj-link" href="https://github.com/user-attachments/assets/bd9970d6-d942-4941-9441-ab9e7d442292">
            View on GitHub →
          </a>
        </div>
      </div>
    </div>
  </div>



  <!-- PROJECT 5 -->
  <div class="proj-card">
    <div class="proj-card-inner no-image">
      <div class="proj-body">
        <div>
          <p class="proj-category">Exploratory Analysis & Reporting</p>
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




  <!-- PROJECT 6 -->
  <div class="proj-card">
    <div class="proj-card-inner no-image">
      <div class="proj-body">
        <div>
          <p class="proj-category">SQL Querying · Problem Solving</p>
          <a class="proj-title" href="https://github.com/jameszka997/SQL-Noir---Case-Files---Workflows">
            SQL-Noir Case Files Solutions
          </a>
          <p class="proj-desc">
            Documented SQL query workflows and solutions across six mystery-themed SQL Noir cases, practicing database querying, table joins, and analytical thinking.
          </p>
        </div>
        <div class="proj-footer">
          <div class="tools-row">
            <span class="tool-badge xl">Excel</span>
            <span class="tool-badge xl">Pivot Tables</span>
            <span class="tool-badge viz">Charts &amp; Visualisation</span>
            <span class="tool-badge sql">EDA</span>
          </div>
          <a class="proj-link" href="https://github.com/jameszka997/SQL-Noir---Case-Files---Workflows">
            View on GitHub →
          </a>
        </div>
      </div>
    </div>
  </div>





  <!-- PROJECT 7 -->
  <div class="proj-card">
    <div class="proj-card-inner">
      <div class="proj-image">
        <img src="https://github.com/user-attachments/assets/017b9e4d-4290-4288-884b-bb22f2d097a7" alt="R Data Science Graphs snapshot" />
      </div>
      <div class="proj-body">
        <div>
          <p class="proj-category">R · Data Science · Visualization</p>
          <a class="proj-title" href="https://github.com/jameszka997/R-for-Data-Science2e-me">
            R for Data Science – Learning Log
          </a>
          <p class="proj-desc">
            A hands-on learning log documenting my journey through the R for Data Science (2nd edition) workbook, covering data wrangling, transformation, and visualization using tidyverse, dplyr, and ggplot2 (snippet of graphs included above).
          </p>
        </div>
        <div class="proj-footer">
          <div class="tools-row">
            <span class="tool-badge xl">Excel</span>
            <span class="tool-badge xl">Pivot Tables</span>
            <span class="tool-badge viz">Data Visualisation</span>
            <span class="tool-badge">Scenario Modelling</span>
          </div>
          <a class="proj-link" href="https://github.com/jameszka997/R-for-Data-Science2e-me">
            View on GitHub →
          </a>
        </div>
      </div>
    </div>
  </div>





  <!-- PROJECT 8 -->
  <div class="proj-card">
    <div class="proj-card-inner no-image">
      <div class="proj-body">
        <div>
          <p class="proj-category">SQL · Problem Solving</p>
          <a class="proj-title" href="https://github.com/jameszka997/SQL-Interview-Practice---DataLemur">
            SQL Interview Practice - DataLemur
          </a>
          <p class="proj-desc">
            Practising and documenting solutions to real-world SQL interview questions from DataLemur, spanning pharmaceutical sales analysis, candidate filtering, assembly line tracking, and messaging analytics using PostgreSQL.
          </p>
        </div>
        <div class="proj-footer">
          <div class="tools-row">
            <span class="tool-badge xl">Excel</span>
            <span class="tool-badge xl">Pivot Tables</span>
            <span class="tool-badge viz">Charts &amp; Visualisation</span>
            <span class="tool-badge sql">EDA</span>
          </div>
          <a class="proj-link" href="https://github.com/jameszka997/SQL-Interview-Practice---DataLemur">
            View on GitHub →
          </a>
        </div>
      </div>
    </div>
  </div>




  <!-- PROJECT 9 -->
  <div class="proj-card">
    <div class="proj-card-inner no-image">
      <div class="proj-body">
        <div>
          <p class="proj-category">Bioinformatics · RNA-sequencing </p>
          <a class="proj-title" href="https://github.com/jameszka997/RNA-seq-Uppsala-code">
            RNA-Seq Data Analysis Workshop
          </a>
          <p class="proj-desc">
            Completed a five-day SciLifeLab/NBIS workshop at Uppsala University covering the full RNA-seq analysis pipeline, from raw data quality control and read mapping through to differential gene expression and gene set enrichment analysis using R and Linux.
          </p>
        </div>
        <div class="proj-footer">
          <div class="tools-row">
            <span class="tool-badge xl">Excel</span>
            <span class="tool-badge xl">Pivot Tables</span>
            <span class="tool-badge viz">Charts &amp; Visualisation</span>
            <span class="tool-badge sql">EDA</span>
          </div>
          <a class="proj-link" href="https://github.com/jameszka997/RNA-seq-Uppsala-code">
            View on GitHub →
          </a>
        </div>
      </div>
    </div>
  </div>




  <!-- PROJECT 10 -->
  <div class="proj-card">
    <div class="proj-card-inner no-image">
      <div class="proj-body">
        <div>
          <p class="proj-category">Data Science · R · SQL</p>
          <a class="proj-title" href="https://github.com/jameszka997/Clinical_Data_Science_Projects_Repository">
            Clinical Data Science Projects
          </a>
          <p class="proj-desc">
            Coursework repository from the University of Colorado's Clinical Data Science program, featuring projects spanning EHR-based hypertension phenotyping, ICU mortality risk prediction modelling, and NLP keyword extraction from clinical notes.
          </p>
        </div>
        <div class="proj-footer">
          <div class="tools-row">
            <span class="tool-badge xl">Excel</span>
            <span class="tool-badge xl">Pivot Tables</span>
            <span class="tool-badge viz">Charts &amp; Visualisation</span>
            <span class="tool-badge sql">EDA</span>
          </div>
          <a class="proj-link" href="https://github.com/jameszka997/Clinical_Data_Science_Projects_Repository">
            View on GitHub →
          </a>
        </div>
      </div>
    </div>
  </div>




  <!-- PROJECT 11 -->
  <div class="proj-card">
    <div class="proj-card-inner no-image">
      <div class="proj-body">
        <div>
          <p class="proj-category">Excel · Word · Mass Email Sending</p>
          <a class="proj-title" href="https://github.com/jameszka997/Mail_Merge_using_Excel_and_Word">
            Mail Merge using Excel & Word
          </a>
          <p class="proj-desc">
            Documented a stakeholder email workflow using Excel functions (SUMPRODUCT, XLOOKUP, TEXTBEFORE/AFTER) to validate, extract, and structure contact data from merged strings for use in a customised Word mail merge campaign.
          </p>
        </div>
        <div class="proj-footer">
          <div class="tools-row">
            <span class="tool-badge xl">Excel</span>
            <span class="tool-badge xl">Pivot Tables</span>
            <span class="tool-badge viz">Charts &amp; Visualisation</span>
            <span class="tool-badge sql">EDA</span>
          </div>
          <a class="proj-link" href="https://github.com/jameszka997/Mail_Merge_using_Excel_and_Word">
            View on GitHub →
          </a>
        </div>
      </div>
    </div>
  </div>




  <!-- PROJECT 12 -->
  <div class="proj-card">
    <div class="proj-card-inner no-image">
      <div class="proj-body">
        <div>
          <p class="proj-category">Excel · Healthcare data · Database harmonization</p>
          <a class="proj-title" href="https://github.com/jameszka997/ICD-Health-Code-Dataset-Harmonization-">
            ICD Health Code Dataset Harmonization
          </a>
          <p class="proj-desc">
            Cross-referenced and harmonized a dataset of ~200 Swedish ICD-8/9/10 disease codes against international WHO classifications for X-chromosome related autoimmune diseases at Linköping University's Nestor Lab, identifying and documenting key coding discrepancies across classification systems using Excel.
          </p>
        </div>
        <div class="proj-footer">
          <div class="tools-row">
            <span class="tool-badge xl">Excel</span>
            <span class="tool-badge xl">Pivot Tables</span>
            <span class="tool-badge viz">Charts &amp; Visualisation</span>
            <span class="tool-badge sql">EDA</span>
          </div>
          <a class="proj-link" href="https://github.com/jameszka997/ICD-Health-Code-Dataset-Harmonization-">
            View on GitHub →
          </a>
        </div>
      </div>
    </div>
  </div>





<!-- PROJECT 13 -->
  <div class="proj-card">
    <div class="proj-card-inner">
      <div class="proj-image">
        <img src="https://github.com/user-attachments/assets/5ff81a12-0cf4-43bc-a583-5707d473d267" alt="Bioinformatic pipelines development snapshot" />
      </div>
      <div class="proj-body">
        <div>
          <p class="proj-category">Bioinformatics · Shell · Genomics · R</p>
          <a class="proj-title" href="https://github.com/user-attachments/assets/5ff81a12-0cf4-43bc-a583-5707d473d267">
            Bioinformatic Pipeline Developments
          </a>
          <p class="proj-desc">
            Developed and implemented modular genomics and transcriptomics pipelines at Linköping University's Nestor Lab, spanning LP-WGS alignment, RAP-seq RNA processing, and R-based Copy Number Variation analysis using Bash, Python, and R. Example above for expression profile from DNA CNV analysis.
          </p>
        </div>
        <div class="proj-footer">
          <div class="tools-row">
            <span class="tool-badge xl">Excel</span>
            <span class="tool-badge xl">Pivot Tables</span>
            <span class="tool-badge viz">Data Visualisation</span>
            <span class="tool-badge">Scenario Modelling</span>
          </div>
          <a class="proj-link" href="https://github.com/jameszka997/Bioinformatic-Pipeline-Development-Projects">
            View on GitHub →
          </a>
        </div>
      </div>
    </div>
  </div>




<!-- PROJECT 14 -->
  <div class="proj-card">
    <div class="proj-card-inner">
      <div class="proj-image">
        <img src="https://github.com/user-attachments/assets/29c9e8c2-464e-45ee-bce6-0217ec819914" alt="Toxicology Assessment Pipeline flowchart" />
      </div>
      <div class="proj-body">
        <div>
          <p class="proj-category">Data Modelling · R</p>
          <a class="proj-title" href="https://github.com/jameszka997/Toxicological-study-of-alcoholic-and-non-alcoholic-hand-sanitisers-on-Daphnia-pulex">
            Toxicology Modelling and Study (BSc project)
          </a>
          <p class="proj-desc">
            Investigated the acute and chronic toxicological effects of alcohol-based and non-alcohol-based hand sanitisers on the freshwater indicator species Daphnia pulex using probit regression, Kaplan-Meier survival analysis, and heart rate endpoints in R, identifying alcohol evaporation as a key methodological confound.
          </p>
        </div>
        <div class="proj-footer">
          <div class="tools-row">
            <span class="tool-badge xl">Excel</span>
            <span class="tool-badge xl">Pivot Tables</span>
            <span class="tool-badge viz">Data Visualisation</span>
            <span class="tool-badge">Scenario Modelling</span>
          </div>
          <a class="proj-link" href="https://github.com/jameszka997/Toxicological-study-of-alcoholic-and-non-alcoholic-hand-sanitisers-on-Daphnia-pulex">
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
