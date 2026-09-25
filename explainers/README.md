# From Power BI model to Fabric: a worked approach

Seven short, interactive lessons built on a real Power BI model: how it's shaped, how it explains itself, how it was checked, and how it would move to Microsoft Fabric.

## View the lessons

**Open the live series: https://senrabzil.github.io/bi-work-sample/explainers/**

Clicking an `.html` file in this repository shows its source code, because GitHub displays files rather than running them. Use the link above to see the lessons as web pages.

## Lessons

| # | Lesson | Try it |
|---|--------|--------|
| 01 | [One model, 53 wires](https://senrabzil.github.io/bi-work-sample/explainers/01_shape_of_the_model.html) | Trace any lookup table or report page through the model's real relationships |
| 02 | [Every number explains itself](https://senrabzil.github.io/bi-work-sample/explainers/02_tiles_that_explain.html) | Clear the filters and watch a shared measure fail silently |
| 03 | [Three rules, broken on purpose](https://senrabzil.github.io/bi-work-sample/explainers/03_design_decisions.html) | See which figures a commodity slicer really reaches |
| 04 | [The check passed. It was wrong.](https://senrabzil.github.io/bi-work-sample/explainers/04_found_fixed_guarded.html) | Step through the validator before and after a fix |
| 05 | [Same model, new floor](https://senrabzil.github.io/bi-work-sample/explainers/05_moving_to_fabric.html) | Choose Import or Direct Lake per table group |
| 06 | [Five routes, one groundwork](https://senrabzil.github.io/bi-work-sample/explainers/06_migration_playbook.html) | Rank migration routes against deadline, risk, debt and capacity |
| 07 | [Show it once. Then let it repeat.](https://senrabzil.github.io/bi-work-sample/explainers/07_coding_agent.html) | Step through the coding-agent loop, and see what breaks if a step is skipped |

## View them offline

No installation is needed. Each lesson is a single HTML file with its styles and scripts built in.

1. On the repository's main page, click **Code > Download ZIP**, then extract it.
2. Open the `explainers` folder and double-click `index.html`.
3. If it opens in a text editor instead of a browser, right-click it and choose **Open with > Microsoft Edge** (or any browser).

Keep all eight files in the same folder so the links between lessons work. An internet connection is only needed for the "further reading" links in lessons 05 and 06.

## About the content

The model is a minerals and metals intelligence mock-up built in Power BI. Its structure, counts and checks are real, taken from its project files in September 2026. The figures shown on its report pages are illustrative. Microsoft Fabric features change quickly, so check Microsoft's documentation for the current state.
