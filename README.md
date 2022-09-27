# Pewlett-Hackard-Analysis
## Purpose
SQL was utilized to create databases that would help Pewlett Hackard prepare for the future as employees begin to near retirement. The databases would provide a list of employees who would be nearing retirement and qualify for a retirement package as well as provide a list of employees to possibly fill the positions that would be left open following the retirement of an employee via a mentorship program.

## Results

1.	Majority of retiring employees hold senior positions (i.e Senior Engineer) and such filling these roles should be a priority to ensure that everything will run smoothly after an employee retires [retiring_titles](Data/retiring_titles.csv)
2.	If existing employees are promoted to fill senior positions via the mentorship program, the open positions need to be filled either from promoting existing employees or hiring new ones
3.	There are drastically more employees retiring than there are employees who would be able to fill the open position, the company needs to ensure that employees filling the open positions will have a smooth transition and thorough training to fill in possible gaps with the disparity [retirement_titles](Data/retirement_titles.csv)
4.	The mentorship program list excludes all employees not born within the year 1965, which means there could possibly be more employees eligible for the program [mentorship_eligibility](Data/mentorship_eligibility.csv)

## Summary
To accurately determine how many roles will need to be filled, a bar graph can be made to categorize retiring employees into age groups. Using this chart, the company project the rate at which new hires need to be brought in. The retirement_titles table can also be expanded to include more than just those born within the years 1952-1955, which would also give a better estimate of how large the hiring quota will be in the next coming years.

Based on current projections, there are not enough mentors to mentees for the next generation. However, if the mentorship_program table was expanded to include more employees born after 1965, the projection numbers would change. 
