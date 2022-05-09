# School_District_Analysis
## 1. Overview of the school district analysis: Explain the purpose of this analysis.
A school district asked to perform school district analysis to show if there are some evidences of academic dishonesty in reading and math grades for Thomas High School ninth graders. We will perform check to replace the math and reading scores for Thomas High School with NaNs while keeping the rest of the data intact. Then compare the data with the orginal data and write up a report to describe how these changes affected the overall analysis.

## 2. Results: Using bulleted lists and images of DataFrames as support, address the following questions.
- How is the district summary affected?

  By comparing below screenshots, The %s passing math and reading for Thomas High School changed dramatically, but the average of math and reading scores had changed slightly
  
  **Original**

  ![image](https://user-images.githubusercontent.com/103073631/167359850-e7f658b2-0906-430d-a1aa-39713bc6ae1a.png)
 
  **Replaced with NaNs**

  ![image](https://user-images.githubusercontent.com/103073631/167360166-d1ebae92-0218-4d56-8a1e-b739a5b6edb5.png)

- How is the school summary affected?

  By comparing below two screenshots, the percentages changes slightly within 1% differences, so that the numbers of NaNs are relatively smaller than the whole dataset.
  
  **Original**

  ![image](https://user-images.githubusercontent.com/103073631/167363524-dd39eb1d-be96-4943-a7c8-857b70489970.png)
 
  **Replaced with 9th scores values with NaNs**
  
  ![image](https://user-images.githubusercontent.com/103073631/167363286-31201f4b-285b-4ac2-abee-9c31d2e2a167.png)
  
  **Excluded 9th values and counts and only 10th-12th graders from Thomas High School (THS)**
  
  ![image](https://user-images.githubusercontent.com/103073631/167364381-d05e8102-55fb-4dfc-bc16-42bc207d4763.png)

  
- How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?

  **Original**

  ![image](https://user-images.githubusercontent.com/103073631/167372021-72bec678-9d8b-46c4-9d83-15b755298fd2.png)
 
  **Replaced with 9th scores values with NaNs**
  
  ![image](https://user-images.githubusercontent.com/103073631/167371544-c3ac70fa-5c1c-471e-8cf7-3d89b3ffd4f6.png)
  
  **Excluded 9th scores values and counts and only 10th-12th graders from Thomas High School (THS)**
  
  ![image](https://user-images.githubusercontent.com/103073631/167371669-326ce1a8-485b-4536-8fd9-ef66db598f5c.png)


- How does replacing the ninth-grade scores affect the following:
  - Math and reading scores by grade
  
  From the original module, Thomas High School had 83.6 math average and 83.7 reading average for the 9th grade tests, then scores' values are replaced by NaNs.
    
    **Combined reading scores**

    ![image](https://user-images.githubusercontent.com/103073631/167367898-ba6aabbb-8ad7-410a-869d-cdfdd728ee35.png)
  
    **Combined math scores**
  
    ![image](https://user-images.githubusercontent.com/103073631/167367733-58548513-ed61-4c69-92b0-2ed782536ed8.png)


  - Scores by school spending

    **Original**
  
    ![image](https://user-images.githubusercontent.com/103073631/167368498-af42e545-a1e0-4b1f-8940-85a01926d886.png)

    **replacing the ninth-grade scores**
  
    ![image](https://user-images.githubusercontent.com/103073631/167370698-d0cdbc37-28f1-45bb-9bd4-86e05809e834.png)

  - Scores by school size

    **Original**

    ![image](https://user-images.githubusercontent.com/103073631/167366486-e934f06d-b20b-4b94-97e8-2a13a4d7c99e.png)

    **replacing the ninth-grade scores**

    ![image](https://user-images.githubusercontent.com/103073631/167366390-10ff68ad-c974-4223-9f6a-e45367b8400d.png)

  - Scores by school type

    **Original**

    ![image](https://user-images.githubusercontent.com/103073631/167365915-d8d2bb25-1481-4235-8994-6819d33d49d9.png)

    **replacing the ninth-grade scores**

    ![image](https://user-images.githubusercontent.com/103073631/167365959-b24c7a99-e4ba-4656-be01-6fa1776b985c.png)


## 3. Summary: Summarize four changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs.
- The % overall passing rate for Thomas High School changed from ```90.948012``` to ```65.076453``` 
- The %s passing math and reading for Thomas High School changed dramatically, but the average of math and reading scores had changed slightly
- Thomas High School ranked at ```bottom 5``` schools after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs.
- The reading and math scores for the students in 9th grade will be replaced by ```NaN```
