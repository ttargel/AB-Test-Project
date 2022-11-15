# AB-Test-Project

This project contains two parts:

<ol>
  <li>Prioritization of Hypotheses: 
    
  In this part, we examine nine possible hypotheses and decide which one to prioritize for testing.</li>
  <li>A/B Test Analysis:
    
  Following a 1-month AB test, we will analyze its results in order to determine whether the changes made to the product had any beneficial effects.</li>
</ol>

<b>The analysis outline and plan of action are described within the notebook itself.</b>

There are a few datasets in this project. Below are their basic details:

`hypotheses_us.csv`:

This dataset is used in the first part of the project, and contains information about the hypotheses.
<ul>
  <li>`Hypotheses` — brief descriptions of the hypotheses.</li>
  <li>`Reach` — user reach, on a scale of one to ten.</li>
  <li>`Impact` — impact on users, on a scale of one to ten.</li>
  <li>`Confidence` — confidence in the hypothesis, on a scale of one to ten.</li>
  <li>`Effort` — the resources required to test a hypothesis, on a scale of one to ten. The higher the Effort value, the more resource-intensive the test.</li>
</ul>

`orders_us.csv`:

This dataset is used in the second part of the project, and contains order information during the test.

<ul>
  <li>`transactionId` — order identifier.</li>
  <li>`visitorId` — identifier of the user who placed the order.</li>
  <li>`date` — of the order.</li>
  <li>`revenue` — from the order.</li>
  <li>`group` — the A/B test group that the user belongs to.</li>
</ul>

`visits_us.csv`:

This dataset is used in the second part of the project, and contains information about visits during the test.

<ul>
  <li>`date` — date</li>
  <li>`group` — A/B test group</li>
  <li>`visits` — the number of visits on the date specified in the A/B test group specified</li>
</ul>
