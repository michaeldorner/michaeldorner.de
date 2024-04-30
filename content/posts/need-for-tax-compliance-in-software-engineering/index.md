---
title: 'Need for Tax Compliance in Software Engineering'
date: 2024-04-27
description: "The third article of a series on tax compliance in software engineering we  the fundemantal challenges unique to software engineering."
summary: "In third blog post in the series on tax compliance in software engineering, we will estimate the prevelance of cross-border collaboration, and therefore, the need for tax compliance in software engineering by measuring cross-border code review in a multinational software company."
research: ["tax compliance in software engineering", "code review"]
series: 
    - "Tax Compliance for Software Engineering"
series_order: 3
---

So, is cross-border collaboration and, therefore, also the taxation of it, a real issue?

## Approximating Cross-border Collaboration

To estimate the prevalence of cross-border collaboration, we measure cross-border code reviews as proxy for cross-border collaboration in a typical industrial setting. A cross-border code review is code review with participants from more than one country. Although it originated in collocated, waterfall-like code inspections, its modern stances are lightweight and asynchronous discussions among developers around a code change. Different tools are in use, for example, Gerrit or Github and Gitlab with their implementation of code review as so-called pull and merge requests, respectively. Although code review is by far not the only type of collaboration that may include taxable transactions and is also likely not sufficient to determine company-wide transfer prices, the following characteristics make code review a suitable first proxy for cross-border collaboration:

- **More than code only:** Code review not only includes the actual code change and its authors but also includes the feedback from reviewers that may have formed or changed the code change significantly but is no longer visible in the repository after merging the code change into the code base. Therefore, our proxy goes beyond existing code-based measurements for collaboration.
- **Accessible & complete:** The code review discussions are (company-internally) public by default and are, thus, accessible. Unlike other tools like instant messaging services or e-mail, code review does not split into public and private, whose analysis may cause privacy concerns.
- **Persistent:** Code review tools are the backbone of modern code review and ease data extraction. Other types of code review (for example, private or synchronous discussion around a code change through meetings or instant messaging) may not be captured through the tooling, though.

## Measurement

We measured the share of cross-border code reviews at a multinational company delivering software and related services worldwide with main R&D locations in three countries. For many years the company has tried to allocate products to particular sites to avoid the burden of cross-border collaboration. However, our analysis shows that developers represent more than 25 locations because the new corporate work flexibility policy permits relocations. The company uses a single, central, and company-wide tool for its internal software development and code review. Understandably, our case company wants to remain anonymous. Therefore, we are not able to describe the case any further. However, we believe that our case company is exemplary for a multinational enterprise developing software.

{{< alert "github">}}
We provide a [replication package to reproduce our results for any GitHub Enterprise instance](https://github.com/michaeldorner/tax_se). Due to the sensitive topic, we are not able to share our data.
{{< /alert >}}

From the code review tool, we extracted all code reviews that were completed in 2019, 2020, 2021, and 2022 including their activities. All bot activities were removed and were not considered in our analysis. We then [modelled code reviews as communication channels among code review participants](). We consider a code review as a discussion thread that is completed as soon as no more information regarding a particular code change is exchanged (i.e., the code review is closed). We complement each code review participant with the information of the country of the employing subsidiaries at the time of the code review.

## Results

![Cross-border collaboration](cross-border-collaboration.png "The share of cross-border code review at our case company in the years 2019, 2020, 2021 and 2022 (black line) monthly sampled. Since not all historical locations of all code review participants could be reliably retrieved, the share of cross-border reviews could be more significant (indicated by the red area).")

The figure above shows an increase in relative cross-border code reviews over time. The share of cross-border code reviews was between 6% and 10% in 2019 and 2020. Yet, we see a further steep increase reaching between 25% and 30% at the end of 2022.

Interestingly, 6% of all cross-border code reviews involve participants from more than two countries. This means transfer pricing in collaborative software engineering becomes not only a bilateral but a multilateral problem with not only two but multiple—in our case company up to six—different jurisdictions and tax authorities involved in the transfer pricing process.

Although the share of cross-border collaboration may vary among companies, yet, our findings suggest that—through the proxy of cross-border code reviews—cross-border collaboration becomes a significant part of daily life in multinational software companies. It is fair to assume that a further increase in cross-border collaborations in software engineering will draw the attention of tax authorities.

## Conclusion

On the one hand, the arm's length principle is the de-facto standard for multinational enterprises that any multinational company must comply with. On the other hand, software engineering is highly collaborative; beyond geographical and organizational boundaries. Determining a reasonable transfer price for this cross-border collaboration brings the general challenge of taxing intangibles to a new level of complexity.

Pretending to be dead for tax reasons is no option because ignoring the significant cross-border collaboration in modern software development, as we exemplarily found, is a slippery slope: Cross-border collaborations in software engineering will draw the attention of tax authorities. Also, ceasing or forbidding all cross-border collaboration in software engineering is not a valid solution: Reversing the collaborative nature of modern software engineering is likely too costly and takes too long.

Obviously, there are neither simple solutions for such a complex and interdisciplinary problem, nor a single article that can solve this complex problem potentially affecting every software-developing company with developers employed by subsidiaries in more than one country. However, our article aims to bring this eminent and unsolved problem of taxing collaborative software engineering to the audience that can solve this issue. As a software engineering community, we will need to find a common understanding of what constitutes taxable transactions and each company that develops software collaboratively within more than one country needs to learn how to track and value cross-border collaboration, how to estimate the transfer pricing, and how to report these to the tax authorities to be compliant.
