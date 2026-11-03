<p align="left"><sub>SOFTWARE · SYSTEMS · REAL-WORLD PROBLEMS</sub></p>

<h1>Sree Ram.</h1>

<h3>I care about what happens after the happy path.</h3>

Software fails at the edges: an unexpected input, a missing record, a requirement that meant something different to the person using it. My starting point is testing those edges. My next step is building the software around them.

**SDET at Broadridge · Preparing for SWE & Forward Deployed Engineering roles**

[LinkedIn](https://www.linkedin.com/in/pavan-kumar-malleboina/) &nbsp; / &nbsp; [Email](mailto:srrmpavankumar@gmail.com) &nbsp; / &nbsp; [LeetCode](https://leetcode.com/u/pavanerror/)

---

<table>
<tr>
<td width="50%" valign="top">

<h3>01 / My starting point</h3>
<p><strong>Software quality at Broadridge.</strong></p>
<p>Testing assumptions, finding edge cases, and reasoning about failures. I want to carry that discipline into implementation, from the data model to the user-facing workflow.</p>

</td>
<td width="50%" valign="top">

<h3>02 / My direction</h3>
<p><strong>Engineering close to the problem.</strong></p>
<p>Python and SQL are my current foundations. I’m developing the backend and integration skills to turn a user’s unclear request into a small, useful application.</p>

</td>
</tr>
</table>

## 03 / Project brief

### Customer Support Operations Hub

**Stage: planning · First milestone: a working ticket workflow**

> “Which customer needs attention next—and what has already happened?”

That is the question this project will address. The first version is deliberately small: create a ticket, find it by status or priority, update it, and retain its history.

| User need | Proposed implementation | What I will verify |
| :--- | :--- | :--- |
| Find work that needs attention | Status and priority filters | Combined filters, no matches, invalid values |
| Follow a ticket from creation to resolution | Stored tickets and an update history | Missing tickets and invalid status changes |
| Keep work across application restarts | A database-backed API | Saved changes survive a restart |

<details>
<summary><strong>The decisions behind the first version</strong></summary>

<br>

**Start with one complete workflow.** Ticket creation, retrieval, and updates need to work together before the application grows.

**Make failures understandable.** Invalid input and missing records should produce useful responses that a caller can act on.

**Make the result inspectable.** The first release should include setup instructions, example requests, tests, and a short explanation of the data model and trade-offs.

**Evaluate AI later.** Once the workflow works, ticket summarization could be explored against concrete examples. It is a future experiment, not part of the current implementation.

</details>

<!-- When the first version ships, replace the planning status with its actual
release state. Add the real repository and demo URLs, a screenshot, and a
verified result. Keep proposed capabilities distinct from implemented ones. -->

## 04 / How I approach a problem

**Clarify the outcome.** What does the user need to accomplish, and what would a correct result look like?

**Build the smallest complete solution.** Understand the logic, implement it, and explain the trade-offs.

**Try to break it.** Check the boundaries, the missing data, and the assumptions that made the first attempt seem easy.

## 05 / A milestone

**Smart India Hackathon 2023 — Finalist**

---

<h3>Let’s talk about the problem you’re trying to solve.</h3>

I’m interested in SWE and FDE opportunities where understanding users and building dependable software belong to the same job.

[srrmpavankumar@gmail.com](mailto:srrmpavankumar@gmail.com) &nbsp; · &nbsp; [Connect on LinkedIn](https://www.linkedin.com/in/pavan-kumar-malleboina/)
