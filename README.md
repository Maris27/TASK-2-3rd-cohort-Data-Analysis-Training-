**INTRODUCTION TO TASK 2(PRACTICING FUNCTIONS AND FORMULAR)**

After the trainig session on how to use functions and formular by Promise Chinonso ,we were assigned a task which is part of the learning process to ensure we understood what has beeen taught.

we were given a data set known as Sales Data,we were assigned to carry the following using the data set provided.

1. We were asked to determine the total Revenue and profit generated 

2. Determine the average Revenue and unit sold for every order

3. Calculate the total discount given in $

4. Determine the number of sales recorded

5. Calculate the highest profit generated

6. Creating a column named sales return to ascertain if its high sale or low sale when compared with the average value of sales.


  **DATA SET PROVIDED**.

  ![image](https://github.com/Maris27/TASK-2-3rd-cohort-Data-Analysis-Training-/assets/140453106/1724f2fa-097b-4a98-bdda-515ed0aaedc8)

 **ACTIVITIES**
     
    1. To determine Total revenue and profit generated,i used the sum function to sum the range that meant my criteria.
    
    Total revenue =sum(J2:J701).J2:J701 stands as the range for sales which also means Revenue ,while total profit =sum(K2:K701) this stands as the 
      for  profit.

    2.In other to get the average revenue and unit sold for every order ,i used the Average function.=Average(range)

    Average revenue =Average(J2:J701) 
    
    Average unit sold =AVERAGE(E2:E701)

    3.calulating the total discount given, i used the sum function i.e =sum(Range) to sum the total discount on the data set

    =SUM((I2:I701) and i changed the number format from general to currency,then selected the dollar sign.

    4.To ascertain this i used the count function =count((range),to count the total number of sales entry

    =COUNT(J2:J701) this is the range that meant my criteria

    5.I Used a function known as Max =max(range),with this i was able to get the highest profit generated.

    =MAX(K2:K701)

![image](https://github.com/Maris27/TASK-2-3rd-cohort-Data-Analysis-Training-/assets/140453106/2cc6ba7f-469a-4594-b9e7-3b38d6fd2337)


    6.i created another column as instructed and named it sales range.To get the sales range for each sales entry, i used a function known as IF.
    Syntax=IF(logical_test, Value_if_true, value_if_false) i.e if your arguments are corrects it should return true or if wrong it should 
    return false. In this case we are asked to determine the low sales and the high sales if sales were greater than average It should retun high 
    sales or if otherwise it should retun low sales.To achieve this ientered the arguments using the IF function.syntax 
    =IF(J2>=AVERAGE($J$2:$J$701),"High sales", "Low sales"),from the argument there is a dollar 
    sign symbol which is used to lock my value from average so it can be repeated on everyother cell.

  ![image](https://github.com/Maris27/TASK-2-3rd-cohort-Data-Analysis-Training-/assets/140453106/602ddcf4-d402-4d52-8460-019e2d0e6294)
  
    
  

**CONCLUSION**
Am super excited i worked on this task, hoping to work on more tasks and projects soon.

    
    
    

    
  
