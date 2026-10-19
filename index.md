---
layout: default
---

<style>
.page-title {
  text-align: center;
  font-size: 3.5em;
  font-weight: 400;
  margin-bottom: 30px;
  margin-top: 0;
  border: none !important;
  padding-bottom: 0 !important;
}

.profile-container {
  display: flex;
  align-items: flex-start;
  gap: 50px;
  margin-bottom: 40px;
  margin-left: -20px;
}

.profile-container img {
  width: 300px;
  height: auto;
  border-radius: 0;
  flex-shrink: 0;
}

.profile-text {
  flex: 2;
  max-width: none;
}

.section-divider {
  width: calc(100% + 20px) !important;
  border: 0 !important;
  height: 1px !important;
  background-color: #e1e4e8 !important;
  margin: 24px 0 24px -20px !important;
}

.research-title {
  text-align: center;
  font-size: 1.8em;
  font-weight: bold;
  margin: 40px 0 30px 0;
}

/* Remove all header borders */
h1, h2, h3, h4, h5, h6 {
  border-bottom: none !important;
  border-top: none !important;
  padding-bottom: 0 !important;
}

header {
  border-bottom: none !important;
  border-top: none !important;
}

.site-header {
  border-top: none !important;
  border-bottom: none !important;
}

/* Links in the Research section (paper titles, coauthors): same look as the text, blue on hover */
.research-title ~ p a:not(:hover) {
  color: inherit !important;
}

/* Abstract below a paper title */
.abstract {
  display: block;
  font-size: 0.85em;
  margin-top: 4px;
  text-align: justify;
}

@media (max-width: 768px) {
  .profile-container {
    flex-direction: column;
    margin-left: 0;
  }
  
  .profile-container img {
    width: 250px;
  }

  .section-divider {
    width: 100% !important;
    margin-left: 0 !important;
  }
}
</style>

<h1 class="page-title">Juan Segura</h1>

<div class="profile-container">
  <img src="/assets/img/profile.jpg" alt="Juan Segura">
  
  <div class="profile-text">
    <p>I am a PhD candidate at CEMFI.</p>
    <p>My research focuses on Macroeconomics, Firm dynamics and Endogenous Growth.</p>
    
    <p>You can find my CV <a href="/cv/CV_Segura.pdf"><strong>here</strong></a>.</p>
    
    <p><strong>Contact information:</strong><br>
    E-mail: <a href="mailto:juan.segura@cemfi.edu.es"><strong>juan.segura@cemfi.edu.es</strong></a><br>
    Twitter: <a href="https://twitter.com/jsegura_b">@jsegura_b</a></p>
  </div>
</div>

<hr class="section-divider">

<div class="research-title">Research</div>

## Working Papers

**["Financing the Scale-Up: Equity and Innovation"](/papers/Guccione_Segura_ScaleUp.pdf)** 
with [Andrea Guccione](https://andreaguccione.github.io/)
<span class="abstract">**Abstract:** Innovative firms rely on external finance to fund their operations, yet debt and equity may play distinct roles in shaping this process. Using balance-sheet and patent-level data on European patenting firms, we document two facts. First, external equity flows to small, young, collateral-poor, faster-growing firms, while debt reaches larger, more collateral-rich firms. Second, real outcomes, including innovation, respond positively to capital inflows, and these responses are substantially larger for external equity. We interpret these facts through a Schumpeterian model of innovation-led growth with financial frictions in which heterogeneous firms finance their operations with retained earnings, debt, and external equity. In the model, financially constrained firms invest less in R&D, because successful innovations are worth less when capital cannot be scaled to exploit them. This gives rise to selection: equity reaches the firms where new capital has the highest return and its effect on innovation is largest. Financial frictions also depress firm entry, further reducing growth. The calibrated model matches the dynamic correlation of patenting to capital injections and its heterogeneity across financing sources. We use the model to quantify the aggregate effects of financial frictions and evaluate growth policies. In the perfect credit benchmark, growth is 1.25 percentage points higher than in the baseline; frictionless equity markets recover 13% of this gap. Government subsidies to external equity deliver the largest welfare gains at low levels of government spending, while R&D subsidies become more effective as spending rises.</span>

**["The Role of Market Power in Capital Taxation"](/papers/Segura_Taxation.pdf)**
<span class="abstract">**Abstract:** Taxing wealth and taxing capital income are not equivalent when returns to investment are heterogeneous. Which tax is preferable depends on the source of this heterogeneity. I compare the two taxes in a model where entrepreneurs face collateral constraints and charge heterogeneous markups. I calibrate the model to the US under different levels of market power within the range of reported values. Replacing the capital income tax with a revenue-neutral wealth tax raises welfare when markups are low, but lowers it when they are high. Together with financial frictions, market power matters through two channels. First, entrepreneurs who grow out of their collateral constraints charge higher markups, which limits the efficiency gains from taxing wealth. Second, profits are part of the capital income tax base but not of the wealth tax base. Profits rise with markups, and so does the wealth tax rate that keeps government revenue constant, thus lowering most households’ return to saving and capital accumulation. The second channel is more sensitive to aggregate market power and explains most of the differences across economies. Once transitions are accounted for, taxing wealth still raises welfare only when markups are lowest, but only slightly.</span>

## Work in Progress

**"Production Beyond the Firm: The Aggregate Value of Subcontracting"** (JMP)
<span class="abstract">**Abstract:** This paper studies the macroeconomic effects of subcontracting, the practice of delegating production to external firms. Using administrative data on Portuguese firms, I show that a large share of aggregate input spending goes to subcontracting. Larger firms are more likely to subcontract, and those that subcontract do so more intensively. Subcontracting is unique among inputs in how much it moves with output: its expenses have an elasticity of 1.4 with respect to firm-level sales. I build a model of firm dynamics with labor adjustment frictions and task delegation. Firms subcontract for two reasons: flexibility, because delegating production allows them to circumvent adjustment frictions, and specialization, because the subcontractor is more efficient at performing certain tasks. Subcontracting raises aggregate productivity by 4.5%. Flexibility accounts for about a fifth of this gain, by letting firms’ size track their productivity more closely, and specialization for the remainder. Ignoring subcontracting overstates the productivity losses from firing costs by a fifth, and their output losses by half. Moreover, subcontracting allows firms to absorb idiosyncratic shocks, but its flexibility largely vanishes under aggregate ones.</span>

<script>
/* Open every link in a new tab, except e-mail links */
document.querySelectorAll('a[href]').forEach(function (link) {
  var href = link.getAttribute('href');
  if (href.indexOf('mailto:') !== 0 && href.charAt(0) !== '#') {
    link.target = '_blank';
    link.rel = 'noopener';
  }
});
</script>