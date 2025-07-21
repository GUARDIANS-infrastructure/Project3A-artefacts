**Data access request flow pain points and Jobs to be done (JBD).**

This document captures key insights from internal research sessions focused on improving the data access request process. We interviewed stakeholders and reviewed the end-to-end workflow to understand pain points, communication breakdowns, and reporting challenges. This summary is intended for designers, developers, researchers, and contributors working on streamlining this workflow.

These findings help surface critical jobs to be done and user needs that should inform product decisions, feature prioritization, and system improvements. Use this as a foundation for designing and building tools that make the request process more transparent, efficient, and reliable for all users involved.


**🔴 Painpoints table**

| PP#   | Category           | Pain Point                                                                                                                                            |
| ---- | ------------------ | ----------------------------------------------------------------------------------------------------------------------------------------------------- |
| PP01 | Workflow           | Applications are manually tracked via spreadsheets, increasing the risk of errors or lost data.                                                       |
| PP02 | Workflow           | Forms are Word documents; applicants often miss required fields, leading to delays and back-and-forth communication.                                  |
| PP03 | Workflow           | Applicants can lock and return forms in ways that prevent internal teams from executing agreements (e.g., due to incompatible e-signature workflows). |
| PP04 | Workflow           | The review process spans multiple Excel files and reviewers, making it difficult to consolidate feedback for meetings.                                |
| PP05 | Communication      | Communication primarily happens through email, which causes delays, confusion, and lost threads.                                                      |
| PP06 | Communication      | It’s hard to track what information was shared with whom and when due to scattered email communication.                                               |
| PP07 | Communication      | Applicants' messages can get lost in inboxes, especially when threads become long or span teams.                                                      |
| PP08 | Decision Tracking  | There’s no standardized way to log who made decisions or why, leading to poor audit trails.                                                           |
| PP09 | Reporting          | Annual reporting is manual and time-consuming, requiring piecing together emails, forms, and spreadsheets.                                            |
| PP10 | Reporting          | No quick way to answer simple metrics like number of requests received or pending in a given time frame.                                              |
| PP11 | Process Continuity | When team members are away, the lack of structured records makes it hard to pick up or continue their work.                                           |
| PP12 | Workflow Confusion | Too many different forms and flows exist depending on request type (EGA, Sample, Internal), causing confusion.                                        |


**✅ Jobs to be done table**

| When...                                           | I want to...                                        | So I can...                                                                             |
| ------------------------------------------------- | --------------------------------------------------- | --------------------------------------------------------------------------------------- |
| A researcher submits a data access request        | log and track the request in one place              | easily monitor its status and ensure nothing falls through the cracks                   |
| I need additional information from the applicant  | communicate from a single space instead of email    | keep track of which application it relates to                                           |
| I'm reviewing a submitted application             | receive complete and clearly structured information | avoid following up multiple times to clarify or fix errors                              |
| The committee makes a decision on a request       | log who made the decision and why                   | maintain a clear audit trail for future reference                                       |
| I need to generate a report about access activity | quickly retrieve accurate, structured data          | confidently answer stakeholder questions without digging through emails or spreadsheets |
| A committee member is away or leaves              | have easy-to-understand records and processes       | prevent loss of important knowledge or context                                          |
| I'm managing different request types              | use a standard, unified workflow                    | avoid confusion about which form or process to follow                                   |
