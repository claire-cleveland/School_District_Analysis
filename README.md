# School_District_Analysis
Module 4 - PyCity Schools with Pandas 

Overview 
This analysis was performed to better understand the relationships between student grades in math and reading and the school size, type and spending per student. Then one high schools scores for 9th graders was removed to understand how that school's 9th graders influenced school and district-wide statistics. 

Results: 

- How is the district summary affected?
The district summaries changed when the Thomas High School 9th graders were removed from the analysis. 

In the new analysis, without their scores, the average math score decreased, the average reading score stayed the same, the passing math and reading percentage decreased, and the overall passing percentage decreased by .1 %.
<img width="1061" alt="New District Summary" src="https://user-images.githubusercontent.com/85316096/125887801-2b3a7d29-0aad-4411-813e-1ac75e619306.png">
<img width="1037" alt="Old District Summary" src="https://user-images.githubusercontent.com/85316096/125889043-fc93903e-e97c-43a7-8690-dc2e96eb655e.png">

- How is the school summary affected?
The school summary 

<img width="1012" alt="New School Summary" src="https://user-images.githubusercontent.com/85316096/125888327-f35bf0ce-853a-4bb2-8459-a550f2adf157.png">
<img width="1013" alt="Old School Summary" src="https://user-images.githubusercontent.com/85316096/125888349-1e9c59bb-d467-4b1c-adb1-b8e4c2af820c.png">

- How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
    - Relative to other schools, 

- How does replacing the ninth-grade scores affect the following:
 
    - Math and reading scores by grade
    Thomas High School had no grades to report for 9th graders. The scores for all other schools remained       the same.
 
    - Scores by school spending
    Schools that fall into the $601-650 range were affected by Thomas High School scores being replaced. 
      - The math passing percentage dropped from 73% to 67%. 
      - The reading passing percentage dropped from 84% to 77%. 
      - The overall passing percentage fropped from 63% to 56%. 

<img width="848" alt="New Spending Per Student" src="https://user-images.githubusercontent.com/85316096/125888948-940000fb-c74a-4ea1-9e98-49f79d150655.png">
<img width="832" alt="Old Spending per Student" src="https://user-images.githubusercontent.com/85316096/125888954-20d10b22-a721-4e97-80e8-074a4ae0c55f.png">
  
    - Scores by school size
    Schools that call into the medium-sized schools range (1000-2000) were impacted:
      - Percentage passing math dropped from 94% to 85%.
      - Percentage passing reading dropped from 97% to 91%.
      - Overall passing percentage dropped from 91% to 85%.

<img width="766" alt="New Scores by Size" src="https://user-images.githubusercontent.com/85316096/125888974-9d23d430-e6e4-44c2-8de1-e7919f9281a8.png">
<img width="777" alt="Old Scores by Size" src="https://user-images.githubusercontent.com/85316096/125888977-0b206b69-d233-4866-8e2b-af494069312c.png">
 
 		- Scores by school type
		Scores by schools type were affected in the following ways:
   		- Percentage passing math dropped from 94% to 90%
    	- Percentage passing reading dropped from 97% to 93%
    	- Overall passing percentage dropped from 90% to 87%

<img width="724" alt="New Scores by Type" src="https://user-images.githubusercontent.com/85316096/125888988-7672b0b6-95c6-4433-bfea-cc984fc7648f.png">
<img width="737" alt="Old Scores by Type" src="https://user-images.githubusercontent.com/85316096/125889004-91f89a7b-4b9a-4b6c-a071-cbb98cc8719c.png">

Summary: 

Removing 9th grade student scores from Thomas High School affected the school district in the following ways:

	- Average math scores dropped slightly (<1%)
	- Average reading scores were not affected
	- Percentage of students passing math dropped slightly (-1%)
	- Percentage of students passing reading dropped slightle (-1%)
	- The overall passing rate dropped (-1%)
