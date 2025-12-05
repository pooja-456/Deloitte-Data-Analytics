Task 2: Pay Equality Classification Analysis

Objective:
Following multiple internal complaints regarding possible gender-based salary inequality, Daikibo’s Forensic Technology team generated an Equality Score for job roles across different factory locations. The dataset contained three columns: Factory, Job Role and Equality Score, where the score ranges from -100 to +100 and zero represents ideal equality. The objective of this task was to classify each role based on the level of pay equality displayed in the score.

Work Done:
- Opened the provided Equality Table dataset in Excel.
- Reviewed the Equality Score values to understand their ranges across all job roles and locations.
- Added a new column named Equality Class to assign each score into one of three groups:
  - Fair for scores between -10 and +10
  - Unfair for scores less than -10 or greater than +10
  - Highly Discriminative for scores less than -20 or greater than +20
- Applied conditional logic to correctly categorize each row based on the score.

Result:
The completed dataset shows clear variations in pay equality across factories. Certain leadership roles, such as Vice Presidents and Senior Managers, often fall into the Highly Discriminative category, particularly in the Meiyo and Seiko factories where scores such as -26, -25 and -24 indicate severe inequality. In contrast, operational and engineering roles tend to show Fair or mildly Unfair scores, especially in Berlin and Shenzhen. These results help highlight specific factories and job roles where pay discrimination is most serious and further investigation is needed. The final classified dataset is included in this folder.
