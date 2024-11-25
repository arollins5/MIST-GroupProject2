# MIST4610 Team 10 Group Project 2
## Team Name
4610Fa24Group10

# Group Members
- Addie Rollins [@addisonrollins](https://github.com/arollins5/MIST-GroupProject2)
- Nozomi Thacker [@nozomithacker](https://github.com/n-thacker/MIST4610Group10Project2) 

# Description of the Dataset:
Our dataset details the crimes that occurred in Los Angeles from 2020 to present day. We found it on the provided [US Data gov website](https://catalog.data.gov/dataset/crime-data-from-2020-to-present). This dataset contains 28 fields of attributes about the crime. According to Tableau, the dataset includes String, Date & Time, and Whole Number data types. The String datatype was used in fields such as the type of crime, the location it took place in, and the descent of the victim of the crime. The Number datatype was used in fields such the report number (Dr no), crime code, and the the area of LA that the crime took place in. The Date & Time datatype includes fields that detail the time the crime occurred as well as the time that the crime was officially reported. Overall, this dataset uses different datatypes in numerous ways to create many openings for examining the crimes of Los Angeles. Below is a list of the 28 fields with descriptions of what each captures.  

![DataDescriptors](https://github.com/user-attachments/assets/cd67a002-4636-48cd-93b4-bebee7fd17e1)


# Question 1 
Are there crimes where the victim is more likely to be of a certain descent? 

### Importance:
Knowing which descents in the population are victims of certain crimes can allow for more specialized resources to those descents. By understanding these connections, generalized programs and local relief or hotlines can better cater and augment their resources to better assist the descents that are facing the highest victimization rates in specific crimes. For example, Descent B, Black, accounts for over half of the human trafficking victims in LA. With this in mind, a public program to cater to this descent to report human trafficking and seek help if they think they are being trafficked can be created. While specific states and the national government have these hotlines in place, specializing it within LA and within a certain descent based on this data would have a more precise and personable impact and prompt a response to help lessen the victimization rate of this descent. Another example is Descent H, Hispanic and Latino descents, who are seeing an upward trend in being victims of child abuse. By understanding a year-by-year increase in child abuse cases within this descent, by as much as 10%, the local government can assess the resources and programs that are currently being put into reducing these crimes. Furthermore, they can converse about increasing the funding and promotion of these services and intiatives and programs that can be conducted to create a sustained reduction in child abuse cases within this descent.  

### Visualization 
![p1](https://github.com/user-attachments/assets/06a1e813-ff30-47ea-b40c-b74db684adcb)
![p2](https://github.com/user-attachments/assets/47dcd4f0-8ffd-461e-8789-f88c16c12194)
![p3](https://github.com/user-attachments/assets/b22c101c-89fe-44c4-9366-8b7ed594e68e)
![p4](https://github.com/user-attachments/assets/494dc413-d816-46c6-ba12-a9e68a141e9b)
![p5](https://github.com/user-attachments/assets/fce73e56-27b4-4f23-9f20-bfd63819b5d2)
![p6](https://github.com/user-attachments/assets/259cce8b-8de7-4fa9-8ac8-59bacbc6192e)
![p7](https://github.com/user-attachments/assets/a0aa01ed-85d4-4908-94c2-801a09c48eb1)
![p8](https://github.com/user-attachments/assets/fccf1ffb-94ab-4068-894e-993dfede520b)
![p9](https://github.com/user-attachments/assets/dd0f4f65-5c66-44ac-b3b7-699cc8dbd0cf)
![p10](https://github.com/user-attachments/assets/6a3945a2-cd2c-4af0-ba74-8e3d77d1288d)

### Manipulations
In order to achieve this view, the victim descent rows needed to exclude the rows that were designated as Null and had a non-descriptor entry. With this, the legend provided by the LAPD for their victim descent codes now matched the dataset. The victim descent rows originally only provided the letter code for each descent; for easier interpretation of the data, each descent row was edited to include the letter code as well as the descent that it corresponds with per the LAPD. DR No, the case numbers for each crime, were originally expected by Tableau to be summed up, which needed to be changed into a count in order to measure every single report that was filed based on descent. To find the percent of victimization, DR No count underwent a quick calculation to convert the count into a percent of the total column so that the percent of victimization based on crime could be assessed by descent. Using Analysis in Tableau, a grand row total percentage was also calculated to see overall which descents were most often victims of crimes. For clarity and visibility, a Square Color Marker was used on the percentage of totals per column to make it easier for users to quickly identify which descents held majority victimization per crime. 

### Analysis and Results
While this visualization gives an overall percent and allows users to determine which descents are most likely to be victims of specific crimes, it also allows for a wider picture of overall descent-crime victimization analysis through the use of the grand row percentage column and presents the finding that Descent H, W, and B are most likely to be victims of any crimes committed in LA as seen from the aggregate of the last four years of data. This view also allows for a specialized, narrow picture by filtering through each year from 2020 to the present. The ability to manipulate the view in this manner allows for observations such as seeing an uptick in Descent H victimization in child abuse from 2020 to now and does the same for Descent B and human trafficking. While making the broader observations is important, being able to manipulate the view year by year and by descent allows for more specific and descent-focused programs and actions by the local government to help reduce the chances these descents will be victims of specific crimes. 

# Question 2 

### Importance: 

asdf

## Visualization
## Manipulations
## Analysis and Results

# Tableau File

# Presentation File:
[Click Here](https://docs.google.com/presentation/d/1mtWjV2PD5ErVfyruj9rhXnFr_Nm4JiCdXVZYa0byuDs/edit?usp=sharing)