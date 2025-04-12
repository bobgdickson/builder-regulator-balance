# Civilizational Balance Index (CBI)

## Overview
This project explores the hypothesis that modern populist movements represent a civilizational feedback loop—an attempt to restore balance between **builders** (those who create tangible value) and **regulators** (those who govern, manage, or administer systems).

We use historical employment and prosperity data to:
- Quantify shifts in employment structure over time (Builder-to-Lawyer, Public-to-Private ratios)
- Analyze correlations between these ratios and economic well-being (e.g., home affordability, savings rates)
- Visualize long-term patterns of civilizational imbalance and potential correction cycles
- Invite public and academic participation to explore policy, localism, and individual responses

## Initial Hypothesis
> Societal instability arises when the ratio between builders and regulators becomes chronically imbalanced. Modern populism may function as a **meta-civilizational correction mechanism**—a coarse but necessary response to systemic sclerosis.

# Civilizational Balance Thesis: Background and Observations

## 1. Background
Over the last half-century, advanced Western societies—especially the United States—have experienced a profound structural shift in how work, governance, and value are distributed. While productivity and wealth have continued to grow in aggregate, so too has a sense of institutional sclerosis, stagnation, and civic malaise.

These trends are often explained away through ideological lenses (capitalism, socialism, globalization, etc.), but they may reflect a deeper systems-level issue: the **ratio of builders to regulators** has inverted. Where once society elevated creators, tradespeople, and risk-tolerant entrepreneurs, it now favors administrators, compliance officers, and legal-technocratic functionaries.

## 2. Core Observations

- **Infrastructure gridlock**: Projects that once took months now take decades, blocked by permitting, lawsuits, or over-regulation.
- **Housing unaffordability**: Skyrocketing prices in core metro areas reflect a regulatory bottleneck—not lack of land or capital.
- **Decline in national capacity**: From energy grids to manufacturing and education, systems seem overloaded with oversight and underpowered in delivery.
- **Proliferation of non-productive work**: Entire sectors—legal, HR, DEI, compliance—have grown massively with little connection to actual output or service.
- **Rise in populist backlash**: Across the political spectrum, citizens express frustration with the perceived unresponsiveness of institutions and their gatekeepers.

## 3. The Core Question
Can we build a **simple, empirical metric** that tracks this imbalance over time?

Specifically:
- Can we measure the shifting ratio between builder roles (e.g. construction, manufacturing, engineering) and regulator roles (e.g. legal, government, compliance)?
- Can we correlate this with indicators of prosperity (housing affordability, savings rate, etc.)?
- Can we track how far society deviates from a historical norm—and whether political responses are attempts (conscious or not) to rebalance?

## 4. Hypothesis
> Societal collapse is not just a result of economic failure or inequality. It can stem from an **overcorrection toward control**, where productive energy is throttled by bureaucratic friction. Populism, in this view, is not a bug—it’s a meta-level correction mechanism.

This hypothesis treats populism as a **necessary but crude feedback loop**. It arises when governance becomes unresponsive, rigid, or extractive—when the "regulator-to-builder" ratio reaches a tipping point.

## 5. How This Project Responds
This project seeks to:
- Hypothesize the existence (and determine the components) of an optimal mix of actions or policies at both a civilizational or nation-state level down to the individuals that compose those larger conglomerates.
- Build an empirical **Builder-Regulator Index** and track it over time
- Compare it to prosperity indicators like affordability and savings
- Visualize historical inflection points and policy events
- Frame modern populism not as anomaly, but as predictable phase response
- Invite public feedback and decentralized refinement of both metric and model


### Visual Example
Below is a generated time-series visualization of the builder/regulator balance vs. prosperity metrics:

![Civilizational Balance Plot](/reports/figures/civilizational_balance_plot.png)


## 6. Broader Implications
If this theory holds, it may help explain:
- Why Western institutions feel increasingly brittle
- Why traditional left/right paradigms fail to diagnose core dysfunctions
- Why localism, decentralization, and renewed permission-to-build movements are gaining traction

It also suggests a new framing for political and civic engagement:
> Rather than arguing over policy outputs, we might do better to realign **structural inputs**—restoring balance between builders and regulators.

## 7. Next Steps
- Validate the model with additional datasets and nations
- Develop local/regional index calculators for civic use
- Explore policy reforms that reduce regulatory drag while preserving oversight integrity
- Provide individuals with diagnostic tools to assess their own contribution to systemic balance

---

**Working Thesis**: A civilization maintains health through balance. When too many guard the gates and too few build the walls, collapse is inevitable. This project asks: *can we see it coming—and do something about it?*


## Project Components
- **Data Ingest**: CSVs from FRED (employment, income, home price, savings)
- **Feature Engineering**:
  - Builder-to-Lawyer Ratio = Construction / Legal Services Employment
  - Public-to-Private Ratio = Government / Private Sector Employment
  - Home Affordability = Median Income / Median Home Price
- **Normalization**: All metrics scaled for comparative analysis
- **Visualizations**: Time series graphs showing correlation and divergence
- **Interpretation Layer**:
  - Peaks: Times of high builder energy, low regulation
  - Troughs: Times of bureaucratic saturation and diminishing returns

## Project Roadmap

### ✅ Phase 1: Initial Model and Visualization
- [X] Ingest CSVs for employment and prosperity data
- [X] Calculate key ratios and normalized indicators
- [X] Visualize imbalance over time
- [ ] Annotate with policy events (e.g. 1980 deregulation, 2008 bailouts)
- [X] Begin README/public brief for launch
- [X] Add `requirements.txt` and modular structure for easy colab/testing

### 🛠️ Phase 2: Modular Dataset Pipeline
- [ ] `src/data/get_fred_data.py` — pull datasets directly from FRED
- [ ] `src/data/build_dataset.py` — compute ratios from raw files and export clean data
- [ ] `src/plots.py` — load dataset and produce updated plot

### 🚀 Phase 3: Expansion and Insight Modeling
- [ ] Collect historical policy mix data
- [ ] Compare to other nations (e.g. China, Japan, Nordic countries)
- [ ] Develop agent-based or historical simulations
- [ ] Model optimal governance ratios by population size, birthrate, expansion phase, etc.
- [ ] Propose bottom-up individual actions for balance restoration

## Future Directions
- Annotate historical events and policy shifts
- Layer in other nations for comparative civilizational analysis
- Develop agent-based simulations
- Create policy scenario models
- Explore optimal regulator/builder ratios by era, region, or condition

## Contributing
We welcome feedback, forks, and ideas for further investigation. If you'd like to contribute case studies, alternate visualizations, or policy modeling suggestions, please reach out or open a pull request.

## License
MIT


```
├── LICENSE            <- Open-source license
├── README.md          <- The top-level README for developers using this project.
├── data
│   ├── external       <- Data from third party sources.
│   ├── interim        <- Intermediate data that has been transformed.
│   ├── processed      <- The final, canonical data sets for modeling.
│   └── raw            <- The original, immutable data dump.
│
├── docs               <- Additional project documentation
│
├── models             <- Trained and serialized models, model predictions, or model summaries
│
├── notebooks          <- Jupyter notebooks. Naming convention is a number (for ordering),
│                         the creator's initials, and a short `-` delimited description, e.g.
│                         `1.0-rgd-initial-data-exploration`.
│
├── references         <- Data dictionaries, manuals, and all other explanatory materials.
│
├── reports            <- Generated analysis as HTML, PDF, LaTeX, etc.
│   └── figures        <- Generated graphics and figures to be used in reporting
│
├── requirements.txt   <- The requirements file for reproducing the analysis environment, e.g.
│                         generated with `pip freeze > requirements.txt`
│
└── src                <- Source code for use in this project.
    │
    ├── __init__.py             <- Makes src a Python module
    │
    ├── config.py               <- Store useful variables and configuration
    │
    ├── dataset.py              <- Scripts to download or generate data
    │
    ├── features.py             <- Code to create features for modeling
    │
    ├── modeling                
    │   ├── __init__.py 
    │   ├── predict.py          <- Code to run model inference with trained models          
    │   └── train.py            <- Code to train models
    │
    └── plots.py                <- Code to create visualizations
```

--------