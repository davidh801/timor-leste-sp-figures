# Timor-Leste SP paper — figures dashboard

Companion HTML dashboard for the working paper **Adjudicating past sacrifice
and present need: Deservingness and the legitimacy of post-conflict
distribution** (Pruce, Mcloughlin, Hudson).

The `index.html` file is a self-contained page (base64-embedded PNGs, no
external dependencies) that hosts the figures the Word draft refers to.
Each figure has a stable anchor id so hyperlinks in the Word draft jump
straight to it.

## Live URL

    https://davidh801.github.io/timor-leste-sp-figures/

## Word-doc hyperlink pattern

    https://davidh801.github.io/timor-leste-sp-figures/#tab_sample_composition
    https://davidh801.github.io/timor-leste-sp-figures/#tab_deservingness_items
    https://davidh801.github.io/timor-leste-sp-figures/#fig_deservingness_distributions
    https://davidh801.github.io/timor-leste-sp-figures/#tab_governance_items
    https://davidh801.github.io/timor-leste-sp-figures/#fig_governance_distributions
    https://davidh801.github.io/timor-leste-sp-figures/#fig_citizen_vs_govt_aggregate
    https://davidh801.github.io/timor-leste-sp-figures/#fig_citizen_vs_govt_per_hh

The anchor ids are shown in small text at the bottom of each figure panel
on the dashboard itself.

## Updating

Rebuild the dashboard locally by re-running `build_sweep_dashboard.py`
(under `prucetimorleste/03_code/` or wherever the build script lives),
then upload the refreshed `index.html` to this repo. GitHub Pages
picks up the change automatically within a minute or two.
