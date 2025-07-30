+++
author = ["Zhang Tao"]
title = "Authoring The Redaction History"
description = "How to set up the redaction history in Hugo Brewm theme"
date = "2025-02-03"
type = "post"
draft = false
translationKey = "history"
coffee = 1
tags = ["authoring", "redaction", "history"]
categories = ["authoring"]
stage = "evergreen"
history = [
  {date = "2025-02-01", stage="seedling", author = "Zhang Tao", reviewer = "Reviewer Name", note = "Example"},
  {date = "2025-02-02", stage="budding", author = "Zhang Tao", editor = "Editor Name", note = "Addendum (example)"},
  {date = "2025-02-03", stage="evergreen", note = "Errata (example)"},
]
toot = "https://infosec.exchange/@foxx/113979609651534969"
+++

The redaction history functionality enables you to track and communicate content modifications to readers. 
Within the post's front matter, you can specify details such as `editor`, `reviewer`, and include explanatory notes (`note`) about the changes made.
This feature requires manual configuration in the post's front matter section.

```toml
+++
title = "Authoring The Redaction History"
history = [
    {date = "2025-02-01", author = "Zhang Tao", reviewer = "Reviewer Name", note = "Example"},
    {date = "2025-02-02", author = "Zhang Tao", editor = "Editor Name", note = "Addendum (example)"},
    {date = "2025-02-03", note = "Errata (example)"},
    ]
+++
```

A chronological timeline displaying these information will appear under the article's information section, as demonstrated in this example post.