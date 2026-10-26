<div align="center">

  <h1>🌐 Global Intelligence & Macroeconomic Analytics Suite</h1>
  <p><b>An Executive Multi-Page Power BI Intelligence Suite Tracking Macroeconomic Indicators, Health Demographics, Infrastructure, and Global Trade Dynamics.</b></p>

  <!-- Clean Tech Stack Badge Bar -->
  <p align="center">
    <code>🟡 Microsoft Power BI</code> &bull; 
    <code>🟢 Multi-Fact Star Schema</code> &bull; 
    <code>🔵 Advanced DAX Calculations</code> &bull; 
    <code>🟣 Dark UI/UX Executive Design</code> &bull; 
    <code>🌍 Global Macro & Demographic Intelligence</code>
  </p>

  <br />

  <!-- Home / Landing Page First -->
  <img src="https://i.postimg.cc/d3p46WCr/Whats-App-Image-2026-10-26-at-2-06-51-AM.jpg" alt="Global Intelligence Analytics Portal Landing" width="100%" />

</div>

<hr />
<br />

<h2>📌 Executive Overview & Strategic Purpose</h2>
<p>
  This project delivers an enterprise-grade <b>Global Intelligence & Macroeconomic Diagnostic Suite</b> engineered in Microsoft Power BI. Tailored for macroeconomic researchers, investment analysts, and global policy strategists, the platform evaluates economic development tiers, demographic health burdens, international trade balances, and country-level rankings across a world population of <b>6 Billion</b> and cumulative trade volumes exceeding <b>$8.82 Trillion</b>.
</p>
<p>
  <b>Core Objective:</b> Enable decision-makers to track cross-continental GDP performance, examine life expectancy against economic output, evaluate import/export surplus and inflation trends, and perform granular drill-through audits per nation.
</p>

<br />

<h2>🔑 Macro Strategic Scorecards (Global Benchmarks)</h2>
<ul>
  <li><b>Total Population Analyzed:</b> 6 Billion global citizens evaluated across continents.</li>
  <li><b>Global Average GDP:</b> $243.0 Billion baseline economic output per nation (High-GDP cohort baseline at $3.2 Trillion).</li>
  <li><b>Global Life Expectancy:</b> 67.6 years worldwide average (reaching 76.71 years in European economies).</li>
  <li><b>International Trade Volume:</b> $8.82 Trillion in Total Exports and $8.82 Trillion in Total Imports ($1.20 Billion global trade balance).</li>
  <li><b>Global Economic Growth Rate:</b> 4.79% average GDP growth pace with a 5.86% mean inflation baseline.</li>
  <li><b>Leading Global Economies:</b> United States ($11.75 Trillion) and China ($7.26 Trillion) heading the world GDP ranking.</li>
</ul>

<br />
<hr />
<br />

<h2>🏗️ Data Engineering & Multi-Fact Relational Architecture</h2>

<p>
  The analytical engine is structured around a centralized dimensional entity (<code>Dim_Country</code>) bridging four specialized transactional Fact tables with strict 1-to-many (<code>1:*</code>) relationships, ensuring unified filter propagation and isolation across distinct macro domains:
</p>

<div align="center">
  <img src="https://i.postimg.cc/prpsDNmb/Screenshot-2026-10-26-210412.png" alt="Multi-Fact Relational Star Schema Model" width="95%" />
</div>

<br />

<ul>
  <li><b><code>Dim_Country</code>:</b> Master dimensional boundary storing country names, geographic land area, and segmented <code>GDP Category</code>.</li>
  <li><b><code>Fact_MacroEconomics</code>:</b> Granular economic facts tracking <code>Gross_Domestic_Product</code>, <code>Economic_Growth_Rate</code>, <code>External_Debt</code>, <code>Foreign_Reserves</code>, and <code>Current account balance</code>.</li>
  <li><b><code>Fact_Demographics</code>:</b> Vital statistics encompassing <code>Birth_Rate</code>, <code>Death_Rate</code>, and population health metrics.</li>
  <li><b><code>Fact_Infrastructure</code>:</b> Modernization indicators capturing <code>Highways_Length (km)</code>, <code>Railways_Length (km)</code>, <code>Internet users</code>, and telecommunications capacity.</li>
  <li><b><code>Fact_Energy</code>:</b> Energy dependency matrix monitoring <code>Daily Oil Production</code>, <code>Daily Oil consumption</code>, <code>Daily Oil imports</code>, and <code>Daily Oil Exports</code>.</li>
  <li><b><code>Dax measures</code>:</b> Isolated measure group housing all business logic, dynamic titling, rankings, and analytical ratios.</li>
</ul>

<br />
<hr />
<br />

<h2>📊 Report Modules & Diagnostic Dashboards</h2>

<h3>1. Country Development & Economic Analysis (Global Overview)</h3>
<p>
  Strategic macro tracking evaluating regional economic weight, continental population distributions, and Top 10 economies by nominal GDP:
</p>

<div align="center">
  <table border="0" width="100%">
    <tr>
      <td width="50%" align="center" valign="top">
        <h4>All-Economy Baseline Overview</h4>
        <img src="https://i.postimg.cc/sfN632Lr/Whats-App-Image-2026-10-26-at-2-07-51-AM.jpg" width="95%" alt="Global Macroeconomic Overview" />
        <p align="left"><small>Complete world distribution across North America, Asia, Europe, and Latin America.</small></p>
      </td>
      <td width="50%" align="center" valign="top">
        <h4>High-GDP Tier Filtered View</h4>
        <img src="https://i.postimg.cc/WzCX89Zd/Screenshot-2026-10-27-013533.png" width="95%" alt="High GDP Economic Tier" />
        <p align="left"><small>Filtered diagnostic view isolating premier economies and regional contributions.</small></p>
      </td>
    </tr>
  </table>
</div>

<br />

<h3>2. Global Health & Demographics Analysis</h3>
<p>
  Evaluation of demographic stability, labor force capacity (3 Billion), infant mortality benchmarks, birth vs. death rates, and GDP-to-Life-Expectancy correlation:
</p>

<div align="center">
  <table border="0" width="100%">
    <tr>
      <td width="50%" align="center" valign="top">
        <h4>Worldwide Health & Labor Overview</h4>
        <img src="https://i.postimg.cc/05BW9N4r/Whats-App-Image-2026-10-26-at-2-27-31-AM.jpg" width="95%" alt="Worldwide Health & Demographics" />
        <p align="left"><small>Global demographic balance, birth rate comparisons, and longevity distributions.</small></p>
      </td>
      <td width="50%" align="center" valign="top">
        <h4>European Regional Demographic Focus</h4>
        <img src="https://i.postimg.cc/mkJ8jd9k/Screenshot-2026-10-27-013642.png" width="95%" alt="Europe Health & Demographics" />
        <p align="left"><small>Deep-dive into European labor force (252M), longevity leaders (Sweden, Switzerland), and birth-to-death ratios.</small></p>
      </td>
    </tr>
  </table>
</div>

<br />

<h3>3. Global Economic Performance & Trade Analysis</h3>
<p>
  Tracking international trade flows, export vs. import margins, trade balance indicators, inflation dispersion, and geographic GDP growth hotspots:
</p>

<div align="center">
  <table border="0" width="100%">
    <tr>
      <td width="50%" align="center" valign="top">
        <h4>Global Trade & Inflation Matrix</h4>
        <img src="https://i.postimg.cc/dtZW3YMD/Whats-App-Image-2026-10-26-at-2-28-41-AM.jpg" width="95%" alt="Global Trade Balance and Performance" />
        <p align="left"><small>Evaluation of $8.82T trade channels, top GDP growth economies (Iraq, Chad, Liberia), and regional inflation.</small></p>
      </td>
      <td width="50%" align="center" valign="top">
        <h4>China Trade & Macro Performance Deep-Dive</h4>
        <img src="https://i.postimg.cc/yxtvjfR0/Screenshot-2026-10-27-013758.png" width="95%" alt="China Trade Performance" />
        <p align="left"><small>Slicing trade balance ($30.70B surplus), 9.10% GDP expansion, and domestic trade flow indicators.</small></p>
      </td>
    </tr>
  </table>
</div>

<br />

<h3>4. Country Deep-Dive & Macro Indicators Ledger</h3>
<p>
  Granular multi-attribute matrix providing comprehensive benchmarking across sovereign rankings, economic expansion rate, inflation, longevity, and export volumes:
</p>

<div align="center">
  <img src="https://i.postimg.cc/hPQCvBFf/Whats-App-Image-2026-10-26-at-2-29-16-AM.jpg" alt="Comprehensive Country Performance Ledger" width="95%" />
</div>

<br />
<hr />
<br />

<h2>🧮 Core Analytical DAX Formulations</h2>
<p>Dynamic DAX measures engineered within the centralized measure table:</p>

<pre><code>// Dynamic Sovereign Ranking
Country Rank by GDP = 
RANKX(
    ALL(Dim_Country[Country]), 
    CALCULATE(SUM(Fact_MacroEconomics[Gross_Domestic_Product])), 
    , 
    DESC, 
    Dense
)

// Macro Trade Balance Indicator
Trade Balance Indicator = 
SUM(Fact_MacroEconomics[Exports]) - SUM(Fact_MacroEconomics[Imports])

// Demographic Longevity Metric
Average Life Expectancy = 
AVERAGE(Fact_Demographics[Life_Expectancy])

// Dynamic Metric Indicator for Header Cards
GDP Growth Indicator = 
AVERAGE(Fact_MacroEconomics[Economic_Growth_Rate])</code></pre>

<br />
<hr />
<br />

<h2>💡 Strategic Macroeconomic Findings & Insights</h2>
<ol>
  <li><b>Economic Longevity Decoupling:</b> Scatter correlation analysis indicates a non-linear relationship where life expectancy gains taper above $1.0T GDP, proving structural healthcare access outperforms pure gross economic output.</li>
  <li><b>Regional Trade Asymmetry:</b> Europe and Asia dominate international gross shipping channels, while Sub-Saharan Africa and Latin America exhibit the highest inflation sensitivity (22.4% and 16.5% respectively).</li>
  <li><b>Demographic Transition Disparities:</b> Mature economies in Europe and East Asia experience negative birth-to-death rate gaps, whereas developing regions demonstrate significant labor expansion pipelines.</li>
</ol>

<br />
<hr />
<br />

<h2>📂 Repository Architecture</h2>
<pre>
├── Data/                        # Global macroeconomic & demographic source datasets
├── Reports/                     # Global_Intelligence_Analytics_Suite.pbix
├── Screenshots/                 # Multi-page dark-themed analytics interfaces
└── README.md                    # Project documentation
</pre>

<br />

<div align="center">
  <p>Engineered and Designed by <b>Abdallah Elsayed</b> | Data & Business Intelligence Analyst</p>
</div>
