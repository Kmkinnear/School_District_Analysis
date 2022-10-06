# School_District_Analysis

## Project Overview
The purpose of this project was to take a newer version of the "Student District Analysis" dataset and work with it to find the different deliverables. THe biggest difference between this dataset and the original dataset is that it included a new column for the "School Budget".

## School District Analysis Discoveries:
- The first discovery we had involved comparing the budgets of Charter schools vs. Public schools. We can look at the data and see that Public schools had a higher budget average of about $4,000.  We found this by using the "groupby" and "mean" functions in our code.

  ![image](https://user-images.githubusercontent.com/110848660/194407599-ae92c196-75da-4167-9088-21323f93650d.png)
  
  ![image](https://user-images.githubusercontent.com/110848660/194407436-4a8032c2-2f71-4369-afa6-fca576da12ec.png)

- The next discovery we saw involved data where we sorted the schools by "student count" and listed them in descending order. There was quite a difference in student count when looking at the most populated (2,038 students) and the least populated schools(171 students). Nine of the fifteen schools we looked at all had less than 1,000 students. We utilized the "groupby" and "count" function in our code to get this deliverable. Then we added in the "sort" function to get it in descending order.

  ![image](https://user-images.githubusercontent.com/110848660/194412240-1bef36ef-6682-45c3-bb71-54bf3bca5f3a.png)

  ![image](https://user-images.githubusercontent.com/110848660/194412312-ec5ab6d7-0111-426c-87d4-614fab74dc0b.png)

- The last discovery that we found while looking at the drilled down data involved looking at the math scores amongst the grades in Charter and Public schools. While looking at the Charter schools, we see that 9th graders had the highest math score when compared to the other grades. There was a difference of almost 10 points when comparing 9th and 12th grade scores in Charter schools. When we compared those results to the Public schools, there was a lot less variance among the grade levels. The scores were slightly lower when compared the Charter schools, but there was not as much of a swing among grade levels like we saw in the Charter schools. We found this last deliverable using the "groupby" and "mean" functions.

  ![image](https://user-images.githubusercontent.com/110848660/194412569-5536a3a7-81f7-4d3c-81c0-febdd35de069.png)

  ![image](https://user-images.githubusercontent.com/110848660/194412707-a2434db1-a467-4f19-9d7d-3f3427cf9963.png)

## School District Analysis Summary
- We only scratched the surface with our discoveries that we could find by looking at this data set. There are numerous other things that we could've looked at among the schools and grade levels. One immediate thing that I thought would be interesting to look at would be to add in the "reading score" column with the math scores in the last exercise. That way we could compare the two different scores because it's possible that one set of schools focused on reading more than math scores. That would let the school know that they may need to spend a little less time on reading scores and more time on math scores to get the two closer to one another. The same could go for the grade level where there may be a tradeoff in certain grades where one of the scores is greatly different than the other which would mean more resources should go to bringing up the lower score of the two. Another thing that would be interesting to look at is to take the lowest performing schools and look at their budget amounts compared to the higher performing schools. That was we could see if there is any correlation between budget amounts and test scores.
