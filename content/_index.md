---
# Leave the homepage title empty to use the site title
title: 'Jungang Zou'
date: 2026-10-10
type: landing

design:
  # Default section spacing
  spacing: '6rem'

sections:
  - block: resume-biography-3
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      text: ''
      # Show a call-to-action button under your biography? (optional)
      button:
        text: Download CV
        url: uploads/resume.pdf
      headings:
        about: ''
        education: ''
        interests: ''
    design:
      # Apply a gradient background
      css_class: hbx-bg-gradient
      # Avatar customization
      avatar:
        size: medium # Options: small (150px), medium (200px, default), large (320px), xl (400px), xxl (500px)
        shape: circle # Options: circle (default), square, rounded

  - block: markdown
    id: news
    content:
      title: "News"
      text: |
        - **Dec 2026** — Invited talk on AI4BayesCode at the Technology and Artificial Intelligence Learning Seminar (TAILS), Montana State University (forthcoming).
        - **Aug 2026** — Invited talk on Bayesian propensity score predictive inference at the SILVER Lab Meeting, Department of Epidemiology and Public Health, University of Maryland School of Medicine.
        - **Aug 2026** — Our Bayesian MI-LASSO paper won the **Student Paper Competition Award** of the ASA GSS/SRMS/SSS Sections at JSM 2026, where I also chaired the session *Sampling, Weighting, Missing Data and Variance Estimation*.
        - **Aug 2026** — AI4BayesCode received a **Paper Award at STAI-X 2026** (one of 9 awards selected from all 54 accepted papers) and was invited for a live demonstration at the Stats Up AI community table at JSM 2026.
        - **Jun 2026** — Received the **Outstanding Doctoral Teaching Assistant Award** from the Department of Biostatistics, Columbia University.
        - **Jun 2026** — Presented a poster at the IMSI workshop *New Horizons on Model Transportability and Data Integration* (Chicago, IL) with a travel award.
        - **Mar 2026** — Contributed talk at ENAR 2026 (Indianapolis, IN) on generalizing treatment effects from trials to EHR populations.

  - block: markdown
    id: manuscripts
    content:
      title: "Manuscripts"
      text: |
        ### Statistical Methodology

        1. **Jungang Zou**, Yudan Zou, and Liangyuan Hu (2027+). A Bayesian Iterative Conditional Expectation G-Formula for Causal Survival Analysis under Dynamic Treatment Strategies. In preparation.
        2. Yiheng Wei, **Jungang Zou**, and Qixuan Chen (2026+). MetaBART: Bayesian Additive Regression Trees for Meta-Regression and Generalization from Aggregate Data to Target Populations. In preparation.
        3. **Jungang Zou**, Alex Ziyu Jiang, and Qixuan Chen (2026+). Bayesian Federated Nonlinear Variable Selection under Site Heterogeneity with Unknown Sharing Structure. In preparation.
        4. **Jungang Zou**, Joseph E. Schwartz, Roderick Little, Nathalie Moise, and Qixuan Chen (2026+). Bayesian Propensity Score Predictive Inference for Extending Trial Findings to Target Populations. Submitted to *The Annals of Applied Statistics*. [[R package](https://cran.r-project.org/web/packages/PSPI/index.html)]
        5. **Jungang Zou**, Alex Ziyu Jiang, and Qixuan Chen (2026+). AI4BayesCode: From Natural Language Descriptions to Validated Modular Stateful Bayesian Samplers. Submitted to *Journal of the American Statistical Association* via the STAI-X 2026 fast-track review invitation. [[arXiv](https://arxiv.org/abs/2605.18476)] [[Website](https://zjg540066169.github.io/AI4BayesCode-hub/)] [[GitHub](https://github.com/zjg540066169/AI4BayesCode)]
            - *Paper Award, STAI-X 2026 (one of 9 awards selected from all 54 accepted papers)*
        6. **Jungang Zou** and Liangyuan Hu (2026+). Nonparametric Bayesian Additive Regression Trees for Prediction and Missing Data Imputation in Longitudinal Studies. Major revision, *Computational Statistics and Data Analysis*. [[R package](https://cran.r-project.org/web/packages/SBMTrees/index.html)]
        7. **Jungang Zou**, Sijian Wang, and Qixuan Chen (2026+). Bayesian MI-LASSO for Variable Selection on Multiply-Imputed Data. Minor revision, *Statistics in Medicine*. [[arXiv](https://arxiv.org/abs/2211.00114)] [[R package](https://cran.r-project.org/web/packages/BMIselect/index.html)]
            - *Student Paper Competition Award, ASA GSS/SRMS/SSS Sections, JSM 2026*
        8. Keming Zhang, Yaoyao Li, **Jungang Zou**, Sijian Wang, Bernadette A. Fausto, and Liangyuan Hu (2026). Multi-Level Variable Selection Using a BART-Enhanced Mixed-Effects Framework. *Statistics in Medicine*, 45: e70593. [[Paper](https://doi.org/10.1002/sim.70593)]
        9. Sharifa Z. Williams, **Jungang Zou**, Yutao Liu, Yajuan Si, Sandro Galea, and Qixuan Chen (2024). Improving Survey Inference Using Administrative Records without Releasing Individual-Level Continuous Data. *Statistics in Medicine*, 43(30): 5803–5813. [[Paper](https://doi.org/10.1002/sim.10270)] [[R package](https://cran.r-project.org/web/packages/AuxSurvey/index.html)]
        10. Liangyuan Hu, **Jungang Zou**, Chenyang Gu, Jiayi Ji, Michael Lopez, and Minal Kale (2022). A Flexible Sensitivity Analysis Approach for Unmeasured Confounding with Multiple Treatments and a Binary Outcome with Application to SEER-Medicare Lung Cancer Data. *The Annals of Applied Statistics*, 16(2): 1014–1037. [[Paper](https://doi.org/10.1214/21-AOAS1530)] [[R package](https://cran.r-project.org/web/packages/SAMTx/index.html)]
        11. **Jungang Zou**, Fan Lin, Siyu Gao, Gaoshan Deng, Wenhua Zeng, and Gil Alterovitz (2021). Transfer Learning Based Multi-Objective Genetic Algorithm for Dynamic Community Detection. arXiv preprint. [[arXiv](https://arxiv.org/abs/2109.15136)] [[PyPI](https://pypi.org/project/tmoga/)]
        ### Collaborative Research

        1. Kain Kim, **Jungang Zou**, Baoyi Feng, Mengxiao Luan, Amy Jones, Danielle Gadbois, Jessica Lim, Joseph E. Schwartz, Qixuan Chen, and Nathalie Moise (2026). Predictors of Sustainability in the Collaborative Care Medicaid Program for Depression: A Cross-Sectional Study. *Psychiatric Services*, 77(8): 718–724. [[Paper](https://doi.org/10.1176/appi.ps.20250212)]
        2. Nina M. Flores, Joan A. Casey, Stephanie Lovinsky-Desir, Ariel Spira-Cohen, Sybille Louis, Sarah Walters, Maureen Little, **Jungang Zou**, Kara E. Rudolph, Diana Hernández, Qixuan Chen, and Matthew S. Perzanowski (2026). Impact of a Large-Scale Mold Intervention in Public Housing on Asthma Emergency Department Visits. *American Journal of Respiratory and Critical Care Medicine*, aamag441. [[Paper](https://doi.org/10.1093/ajrccm/aamag441)]
        3. Zidu Xu, Danielle Scharp, Mollie Hobensack, Jiancheng Ye, **Jungang Zou**, Sirui Ding, Jingjing Shang, and Maxim Topaz (2025). Machine Learning-Based Infection Diagnostic and Prognostic Models in Post-Acute Care Settings: A Systematic Review. *Journal of the American Medical Informatics Association*, 32(1): 241–252. [[Paper](https://doi.org/10.1093/jamia/ocae278)]
        4. Chinelo Onyilofor, Baoyi Feng, **Jungang Zou**, Jennifer Mizhquiri Barbecho, Andrea T. Duran, Siqin Ye, Othanya Garcia, Jessica Singer, Qixuan Chen, and Nathalie Moise (2024). Assessing the Fidelity of Depression Screening Implementation in Coronary Heart Disease Patients: A Cross-Sectional Study. *Journal of the American Heart Association*, 13(21): e035550. [[Paper](https://doi.org/10.1161/JAHA.124.035550)]
        5. Abigail R. Greenleaf, Sarah Francis, **Jungang Zou**, Shannon M. Farley, Tšepang Lekhela, Fred Asiimwe, and Qixuan Chen (2024). Influenza-Like Illness in Lesotho from July 2020 to July 2021: Population-Based Participatory Surveillance Results. *JMIR Public Health and Surveillance*, 10: e55208. [[Paper](https://doi.org/10.2196/55208)]
        6. Nina M. Flores, Stephanie Lovinsky-Desir, Adnan Divjan, Lori A. Hoepner, **Jungang Zou**, Rachel L. Miller, Julie B. Herbstman, Frederica P. Perera, Matthew S. Perzanowski, and Qixuan Chen (2024). Trajectory Analysis of Rhinitis in a Birth Cohort from Lower-Income New York City Neighborhoods. *Journal of Allergy and Clinical Immunology*, 154(1): 111–119. [[Paper](https://doi.org/10.1016/j.jaci.2023.11.919)]
        7. Benjamin M. Jadow, Liangyuan Hu, **Jungang Zou**, Daniel Labovitz, Chinwe Ibeh, Bruce Ovbiagele, and Charles Esenwa (2023). Historical Redlining, Social Determinants of Health, and Stroke Prevalence in Communities in New York City. *JAMA Network Open*, 6(4): e235875. [[Paper](https://doi.org/10.1001/jamanetworkopen.2023.5875)]

  - block: markdown
    id: software
    content:
      title: "Software"
      text: |
        1. **[AI4BayesCode](https://zjg540066169.github.io/AI4BayesCode-hub/)** — From Natural Language Descriptions to Validated Modular Stateful Bayesian Samplers. [[Website](https://zjg540066169.github.io/AI4BayesCode-hub/)] [[GitHub](https://github.com/zjg540066169/AI4BayesCode)]
        2. **[PSPI](https://cran.r-project.org/web/packages/PSPI/index.html)** — Propensity Score Predictive Inference for Generalizability and Transportability. [[R (CRAN)](https://cran.r-project.org/web/packages/PSPI/index.html)] [[GitHub](https://github.com/zjg540066169/PSPI)]
        3. **[SBMTrees](https://cran.r-project.org/web/packages/SBMTrees/index.html)** — Sequential Imputation with Bayesian Trees Mixed-Effects Models for Longitudinal Data. [[R (CRAN)](https://cran.r-project.org/web/packages/SBMTrees/index.html)] [[GitHub](https://github.com/zjg540066169/SBMTrees)]
        4. **[AuxSurvey](https://cran.r-project.org/web/packages/AuxSurvey/index.html)** — Survey Analysis with Auxiliary Discretized Variables. [[R (CRAN)](https://cran.r-project.org/web/packages/AuxSurvey/index.html)] [[GitHub](https://github.com/zjg540066169/AuxSurvey)]
        5. **[SAMTx](https://cran.r-project.org/web/packages/SAMTx/index.html)** — Sensitivity Assessment to Unmeasured Confounding with Multiple Treatments. [[R (CRAN)](https://cran.r-project.org/web/packages/SAMTx/index.html)]
        6. **[BMIselect](https://cran.r-project.org/web/packages/BMIselect/index.html)** — Bayesian MI-LASSO Models for Variable Selection on Multiply-Imputed Data. [[R (CRAN)](https://cran.r-project.org/web/packages/BMIselect/index.html)] [[GitHub](https://github.com/zjg540066169/BMIselect)]
        7. **[TMOGA](https://pypi.org/project/tmoga/)** — A Multi-Objective Genetic Algorithm for Dynamic Community Detection. [[PyPI](https://pypi.org/project/tmoga/)] [[GitHub](https://github.com/zjg540066169/TMOGA)]

  - block: markdown
    id: presentations
    content:
      title: "Presentations"
      text: |
        ### Invited Presentations

        1. *AI4BayesCode: From Natural Language Descriptions to Validated Modular Stateful Bayesian Samplers.* Technology and Artificial Intelligence Learning Seminar (TAILS), Montana State University. December 2026 (forthcoming).
        2. *Bayesian Propensity Score Predictive Inference for Extending Trial Findings to Target Populations.* SILVER Lab Meeting, Department of Epidemiology and Public Health, University of Maryland School of Medicine. August 2026.
        3. *Nonparametric Bayesian Additive Regression Trees for Prediction and Missing Data Imputation in Longitudinal Studies.* ENAR 2023 Spring Meeting, Nashville, TN, USA. Invited session: Bayesian Machine Learning for Decision-Making with Incomplete Information. March 2023.
        ### Contributed Talks

        1. *Bayesian MI-LASSO for Variable Selection on Multiply-Imputed Data: Application to an Environmental Health Survey.* JSM 2026, Boston, MA, USA. August 2026.
        2. *AI4BayesCode: From Natural Language Descriptions to Validated Modular Stateful Bayesian Samplers.* STAI-X 2026, Boston, MA, USA. August 2026.
        3. *Generalizing Treatment Effects from Trials to EHR Populations Using Propensity Score Predictive Inference.* ENAR 2026 Spring Meeting, Indianapolis, IN, USA. March 2026.
        ### Posters

        1. **Jungang Zou**, Alex Ziyu Jiang, and Qixuan Chen. *AI4BayesCode: From Natural Language Descriptions to Validated Modular Stateful Bayesian Samplers.* STAI-X 2026, Boston, MA, USA. August 2026.
        2. **Jungang Zou**, Joseph E. Schwartz, Roderick Little, Nathalie Moise, and Qixuan Chen. *Transporting Treatment Effects from Randomized Trials to EHR Populations Using Bayesian Propensity Score Predictive Inference.* IMSI Workshop: New Horizons on Model Transportability and Data Integration, Chicago, IL, USA. June 2026.
        3. **Jungang Zou** and Liangyuan Hu. *Nonparametric Bayesian Additive Regression Trees for Prediction and Missing Data Imputation in Longitudinal Studies.* 14th International Conference on Bayesian Nonparametrics, Los Angeles, CA, USA. June 2025.
        4. **Jungang Zou**, Joseph E. Schwartz, Roderick Little, Nathalie Moise, and Qixuan Chen. *Generalizing Treatment Effects from EHR-Recruited Trials Using Bayesian Propensity Prediction.* 2025 Columbia Biostatistics Annual Research Symposium, New York, NY, USA. April 2025.
        5. **Jungang Zou**, Sijian Wang, and Qixuan Chen. *Variable Selection for Multiply-Imputed Data: A Bayesian Framework.* 2023 Columbia Biostatistics Annual Research Symposium, New York, NY, USA. September 2023.

---
