# CS6200 / IS4200: Relevance Judgments

As we discussed in class, the most common way to evaluate ad hoc information retrieval systems is to create *test collections*, as in the [Text Retrieval Conferences (TREC)](https://trec.nist.gov/) run by the US [National Institute of Standards and Technology](https://www.nist.gov/). These consist of a set of information needs, called *topics*. Each topic contains a brief query (the *title*) and longer natural language query (the *description*) and an even longer *narrative* that explains what the user was looking for an what kinds of information count as relevant or not for that information need.

Here is one example TREC topic:

| field | contents |
| ----- | -------- |
| title | pet therapy |
| description | How are pets or animals used in therapy for humans and what are the benefits? |
| narrative | Relevant documents must include details of how pet- or animal-assisted therapy is or has been used. Relevant details include information about pet therapy programs, desscriptions of the circumstances in which pet therapy is used, the benefits of this type of therapy, the degree of success of this therapy, and any laws or regulations governing it. |

After these topics are created, annotators feed the queries to search engines and create *relevance judgments* by looking through the results. The document identifiers of relevant and non-relevant results are appended to each topic.

In this assignment, you will go through the process of creating relevance judgments for an existing set of topics created by the Library of Congress for their [_Chronicling America_](https://chroniclingamerica.loc.gov/) project, which digitized millions of pages of historic newspapers. As part of this project, librarians have created &ldquo;Research Guides&rdquo; on a few hundred topics. Here is [an alphabetical list of these research guides](https://guides.loc.gov/chronicling-america-topics/alphabetical-order), which you can also view by date, library subject heading, and some other categories.

As an example, consider the research guide for the [bicycle craze in the years around 1900](https://guides.loc.gov/chronicling-america-bicycle-craze). In addition to the narrative and a timeline of events, you can click [&ldquo;Read more about it!&rdquo;](https://guides.loc.gov/chronicling-america-bicycle-craze/selected-articles) to see a list of suggested queries and a few example relevant documents. For most topics, these relevant documents are by no means exhaustive.

*Your task* is to choose *three research guides*
