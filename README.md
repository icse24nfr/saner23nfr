# How Do Software Developers Discuss Non-Functional Requirements?: The Case of the Spring Ecosystem
## Complementary Material

# Abstract

<p>Non-Functional Requirements (NFR) should be defined in the early stages of the software development process, driving developers to make important architectural and design decisions. Neglecting the NFRs may lead developers to face several problems in the software lifecycle (e.g., delays in the system development, increasing the overall system maintenance cost). However, the definition of NFRs is often ad-hoc and scattered through multiple sources. Even though studies have explored how to automate the identification of NFRs, they miss an important artifact to be explored: discussions that take place in open-source software development. Developers tend to use Pull Requests (PRs) to discuss changes related to NFRs. Understanding how these discussions occur on PRs can be a starting point to identify who discusses these requirements. Therefore, in this study, we report the investigation of PR discussions available at repositories from three software systems of the Spring ecosystem. We collected and analyzed PR discussions addressing four categories of NFR: maintainability, security, performance, and robustness. We found that more than 77% of the discussions related to NFRs are triggered in the PR title and/or description, indicating that this was sufficient to start a discussion related to the NFRs. We also found that the discussions surrounding these PRs tend to address the introduction of a code change or explain some anomaly regarding a particular NFR. Moreover, we performed an in-depth analysis of 15 developers that stood out in collaborating with the mapped PRs. We identified that the role of these developers is intimately related to the NFR. For instance, we identified a developer as the Spring Security Senior Engineer. By identifying these developers, one can propose the best profiles suitable for tasks related to NFRs. By characterizing the NFR discussions, we aim to help future researchers to develop automated tools to identify NFRs. Finally, we provide a dataset with 1,533 PR discussions classified in terms of NFR presence.
</p>

<hr>

# Research Questions

<p>With this study, we have the goal of characterize NFRs that emerged from PR discussions and understand who are the developers who discuss these requirements. With this goal in mind, we defined two research questions (RQs). </p>

- RQ1. How are discussions related to non-functional requirements characterized?

- RQ2. Who are the developers that discuss non-functional requirements?

<hr>

# Developers Metrics

<hr>

# Developers' Inspection Protocol

<p>To answer RQ2, we selected 15 developers, contributing with PRs, to manually perform an inspection on their profiles and evaluate their social metrics. Since the profiles of these developers were not available in a specific document on the repository, we created a protocol for this evaluation, in which four authors participated. </p>


This protocol is available at [`/artifacts/Protocol to identify developers profile.pdf`](https://github.com/saner23nfrdiscussions/saner23nfr/blob/main/artifacts/Protocol%20to%20identify%20developers%20profile.pdf) 

<hr>

# Open Coding NFRs (Codes and Categories)

To understand the content of the NFR discussions, we focused on analyzing the titles and descriptions in the PRs discussions. For that purpose, we randomly selected 160 PRs to perform a qualitative analysis. To make sure that we were evaluating all NFRs equally, we divided this analysis based on the total number of each NFR in our dataset. This analysis was performed on the PRs that we knew mentioned the NFRs in the title or description. Through the process of open coding, we generated 35 codes and nine categories that allowed us to understand the content of these titles and descriptions. The list of codes and categories are available at [`/artifacts/Open Coding NFRs.pdf`](https://github.com/saner23nfrdiscussions/saner23nfr/blob/main/artifacts/Open%20Coding%20NFRs.pdf) 

We divided the file into pages to make the reading better. If accepted, we will make available the Miro link with the full board with the codes. The last page contains the whole coding.

<hr>

# Open Coding Developers (Codes and Categories)

We wanted to understand what makes the discuss NFRs. For that purpose, we analyzed other artifacts available (e.g., Github profile and Spring Team page) that could help us to understand what could make these developers be discussing specific NFRs. Our manual analysis through open coding generated 17 codes and 6 categories, which allow us to understand who are these developers. More details about these codes and categories are available at [`/artifacts/Open Coding Developers.pdf`](https://github.com/saner23nfrdiscussions/saner23nfr/blob/main/artifacts/Open%20Coding%20Developers.pdf) 



