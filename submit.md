---
layout: page
title: Submit Your Project
permalink: /submit/
---

## How to submit your project

1. Fork this repository.
2. Create a new markdown file in `/_projects/` using the template below.
3. Fill in the front matter fields and write your project breakdown in Markdown.
4. Commit your file and open a Pull Request to this repository.

```md
---
title: "Your Project Title"
author: "Your Name"
institution: "Your Institution or University"
tech_stack:
  - "Primary Framework"
  - "Database or Tooling"
tags:
  - "Category"
  - "Domain"
github_url: "https://github.com/your-username/your-project"
demo_url: "https://your-live-demo-link"
thumbnail: "/assets/img/sample_cover.jpg"
architecture: "Brief architecture summary"
media:
  - label: "Demo Video"
    url: "https://..."
---

## Problem
Describe the problem you solved.

## Solution
Explain your implementation and design decisions.

## Results
Share outcomes, screenshots, or future improvements.
```

After your PR is merged, your project will automatically appear on the home page grid with peer feedback enabled through Giscus on your project page.
