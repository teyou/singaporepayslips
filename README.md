# Singapore Payslips Dashboard

An unofficial community dashboard for exploring public salary posts from r/singaporepayslips.

Live dashboard: https://teyou.github.io/singaporepayslips/

Public dataset: https://teyou.github.io/singaporepayslips/data.json

## Why this exists

r/singaporepayslips has many useful salary-sharing posts, but Reddit is hard to scan once the number of posts grows.

This dashboard turns those public posts into a more explorable view, so people can compare salary ranges by occupation, industry, years of experience, and other signals.

## Features

- Salary distribution grouped by years of experience
- Occupation map showing salary band vs YOE
- Industry and occupation breakdowns
- Account age bands*
- Multi-select filtering
- Searchable and sortable post table
- Public JSON dataset for people who want to inspect or fork the data

*Account age is calculated from the Reddit account creation date compared against the post date.

## Read this before interpreting the numbers

This is not an official salary benchmark.

The dataset is based on self-reported Reddit posts. It is likely biased toward people who choose to post, people with unusual compensation, and people comfortable sharing salary information publicly.

Some salary numbers may be:

- masked or partially hidden
- inferred from screenshots
- rounded or normalized
- excluded when the post is not clearly a payslip or salary-sharing post

So the dashboard is best used for directional browsing and community discussion, not as a replacement for formal salary surveys.

## About account age

Account age is included as a rough context signal. It may help readers notice very new or throwaway accounts, but it should not be treated as proof that a post is real or fake.

The dashboard does not automatically label posts as fake.

## Published files

This repository is mainly the GitHub Pages publish target.

Published files include:

- `index.html` - dashboard UI
- `data.json` - compact public dataset

Private scrape caches, OCR artifacts, logs, credentials, and local environment files are not intended to be published.

## Credits

Built from public posts on r/singaporepayslips. This is an unofficial community project.
