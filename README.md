# HomeCredit
Trial Project

# Business Problem
Home Credit wants to create methods of serving customers that do not have traditional credit scores for the following reasons:

  1: Rejecting good applicants means lost business opportunities
  2: Approving high-risk applicants may lead to financial losses and increased default rates.
  3: Many potential customers lack conventional credit histories, making traditional scoring methods inadequate

Using the information already collected on their clients as well as results of previous loans given, we can create an algorithm to determine whether or not a client will be likely to repay their loan.

# Group Solution

Our team decided to remove data that was non-critical and also had more than 60% of the fields blank. We believed doing so would skew the data. We then used multiple types of analysis,
regression, random forest, and decision tree, to create an algorithm that will provide an answer to whether or not the client is going to repay their loan based on the data points provided.

# My Contribution

I created an initial analysis that graphed correlation of the individual variables to the target variable. I then created multiple prediction methods to run against a testing set, after segmentation.
From there, I used confusion matrices to determine what was and wasn't more impactful that random guessing. From there, I also brought in a secondary dataset to run against the target variable to
also graph correlation to have a visual representation of whether or not those factors were useful in predicting the desired target, which would be to determine if providing a loan will be profitable.

With the other information provided by the team, I then applied confusion matrices to their data and adjusted the tolerance levels in order to fine-tune them. This resulted in fewer clients having a positive
target variable, but also far fewer false positives and so less loss to the firm in bad loans. Before these additions, there was a very large overestimation on who would repay loans, skewing the results.

# Value of Solution

This solution provides the firm with an additional revenue stream of an underserved client based. This not only increases their revenue, but also garners them an increased reputation in being able to 
help those that don't have a traditional credit/banking background. Even when using a traditional credit reporting method, this method improves probability in positive outcomes by using more current
information to evaluate credit worthiness than a simple history would. Combining both sides improves overall results.

# Difficulties Encountered

There were difficulties in getting some of the methods to run. For example, we weren't able to get a CV method to work properly with the system and so removed the code from the final project entirely. Also, 
our data consistently skewed to a positive result and by adjusting thresholds, there was a conversation on what was the best decision on what tolerance levels to use. On one hand, it would cost the business
potential clients, but on the other hand it would reduce overall risk. This is where a firm understanding of the business is critical so we could make a recommendation with the firm's risk tolerance in mind.

# Lessons Learned

I had the importance of proper risk tolerances and the firm's vision further instilled in my process. Even though we can provide a solution, and perhaps many solutions, not all solutions will fit the company's
unique perspective and goals. Also, there was growth in working with other individuals and their different styles and strengths, which is something I hope to always improve on as no two groups and projects
will ever be the same. Finally, I also learned the importance of feedback. Sometimes you think you have a good solution, but when you discuss it with other people who have been around longer, they can ask
questions you may not have considered. Even people who know little about analysis can ask very basic "why" questions that will help you re-think your process and refine it further. This has taught me to slow
down and think more. You can code as fast as you like, but if proper thought hasn't gone into the finished project, you can miss the mark entirely.
