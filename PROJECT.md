# The Project

This program is built around one project you start in Week 1 and ship in
Week 8: **an application that solves a real problem using a local or
self-deployed LLM (or SLM).**

> [!IMPORTANT]
> **You are not building a model.** The goal is a tool that profiles a dataset and reports what's wrong with it — missing values, duplicates, outliers, type mismatches, inconsistent categories — in plain language, not a predictive model or a dashboard product.

## What "detecting problems in a dataset" means here

The project is done when someone else can point the tool at a CSV (any reasonably similar one, not just yours) and get a readable report of what's wrong with it. A notebook that only makes sense scrolling through your own analysis is not a finished project; a script or CLI that produces the same report for a new file is.

Concretely, your application should:

* **Work on a real dataset** — yours, your workplace's (anonymized if needed), or a public dataset with genuine quality issues. Not a synthetic, pre-cleaned example.
* **Detect concrete data-quality problems** — at minimum: missing values, duplicate rows, numeric outliers, and type/format inconsistencies. Pick at least one more relevant to your dataset (inconsistent categories, invalid ranges, encoding issues).
* **Produce a readable report** — console output, a Markdown file, or a notebook — that a non-expert could read and understand what's wrong with the data and why it matters.
* **Be reusable on a different file.** Hardcoded column names and paths for your one dataset are a start, not the finish line — the checks should generalize to a similarly shaped file.

## Some directions (not a menu — pick your own)

These are here to show the shape of a good project, not to be copied directly:

* A CLI that profiles any CSV and prints a data-quality report (missing values, dtypes, outliers, duplicates)
* A tool that compares two snapshots of the same dataset and flags what changed or broke
* A notebook-based auditor for a public dataset (e.g. from Kaggle or data.gov) that documents every problem found
* A tool that flags inconsistent categorical values (typos, casing, encoding drift) in survey or form data
* A small report generator that turns raw sensor/log data into a "is this data trustworthy" summary

If your idea doesn't look like any of these, that's fine — the test is "does this surface real problems in real data," not "does it match this list."

## Scoping it to 8 weeks

You don't need the full idea working in Week 1. The syllabus is built so the project grows with you:

1. **Weeks 1-2** — Pick the dataset and get comfortable with its raw structure using plain Python before reaching for pandas.
2. **Week 3** — Load the dataset into pandas and run your first exploratory pass.
3. **Week 4** — Build the first data-quality checks — missing values and duplicates.
4. **Week 5** — Add a numeric outlier check using NumPy statistics.
5. **Week 6** — Add cleaning/type/category checks, and decide what "flagged" vs. "fixed" means for your tool.
6. **Week 7** — Add feature/visualization support and turn the findings into a report.
7. **Week 8** — Polish, document, ship it publicly, and record the final demo.

If by Week 4 your tool still can't say anything concrete about your actual dataset, that's the moment to narrow the dataset or the checks — not Week 8.

## What "done" looks like

See the [self-assessment checklist](./SELF_ASSESSMENT.md) for the concrete bar: documented, tested, generalizable, and public.
