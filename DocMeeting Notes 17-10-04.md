Meeting 10/04/2017
======
  
### Discussion
Now that we have the data somewhat cleaned up, we decided that it would be best to gather both current early access games and ex-early access games. We now have tables of both, but we need to consolidate those two into one table. We also need to determine what are the conditions for a game to be considered successful.
  
### Tables
To begin the merging process, we need to make sure that it is distinguishable between current and former early access games. From our discussion, we can create a new "Early Access Status" column in our tables that will contain either true or false based on whether it is currently still in early access stage or not. We will populate these columns with true and false in the two early access and ex-early access files respectively, then begin the merging process since they will have common columns between them. Based on the current two tables, we need to merge the two to reach a final csv file containing all early access games, current or former. For some reason, one table contains current players while the other doesn't. However, we do not think we necessarily need this attribute. We also need to make sure that we have the app IDs of the games in the tables. We have access to this information, however it is not currently listed in the tables. A column can be added with the app IDs, but it would be preferred if it could be moved to the front of the table rather than being the last column.
  
### Grading
In our discussion we also determined that it must be decided how a game can be labeled as successful. We have potential plans to create a grading system that will incorporate and analyze a game's total owners, current players and review (with more possible attributes in the future). This system will incorporate all desired attributes and grade the games on a scale of 0 to 100 for success. This can be narrowed down later on when we have all of our data readily available, but it is something to think about.

### Changes to the Project
- Create columns in both early_access.csv and ex_early_access.csv to contain true/false for early access status
- Determine if current player count is a needed attribute and handle it accordingly
- Merge the two csv files into one
- Begin brainstorming a grading system for a game's success
