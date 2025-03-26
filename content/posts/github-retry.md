---
title: "Retry for GitHub API"
description: "Mining data from GitHub comes with challenges like errors, timeouts, and rate limits. I built a small and robust GitHubRetry class for the requests Python library."
summary: "Mining data from GitHub comes with challenges like errors, timeouts, and rate limits. I built a small and robust  GitHubRetry class for the requests Python library."
date: 2025-03-08
---

As a software engineering researcher, you may need to mine data from GitHub.com or its Enterprise instances, as GitHub has become a---maybe even the major platform for collaborative software engineering. However, like any distributed system, GitHub is prone to errors, timeouts, and connection issues. Additionally, the strict [rate limits](https://docs.github.com/en/rest/using-the-rest-api/rate-limits-for-the-rest-api) add another challenge—demanding time and effort that, unfortunately, is often undervalued in academia.

In the followig, I implemented a `GitHubRetry` class for the popular `requests` Python library. The code is under MIT. Feel free to use and adjust it as you please. To see my code in action, please have a look into the following Gist:

{{< gist michaeldorner 9a7c852c1ae2bdfcd088157c7e5d8045 >}}

{{< alert >}}
**Warning for GraphQL users:** Although all HTTP errors can also happen when using the GraphQL API (andare properly handled by  the `GitHubRetry` class), errors in GraphQL show up in the repsonse JSON like

```
{"errors": [...]}
```

Keep that in mind, when using GraphQL API. It might require additional logic for your query.
{{< /alert >}}
