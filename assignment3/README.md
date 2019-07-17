# Data Diary
1. [Log into data set](https://data.cityofchicago.org/Administration-Finance/Current-Employee-Names-Salaries-and-Position-Title/xzkq-xp2w)
2. Export CSV for Excel
3. Import data to Google sheet and rename it scratch data
4. Insert two blank columns on the right side of column A “name”
5. Select column A and choose “split text to columns” under “data”
6. Choose “space” as separator and a new column appears in column B
7. Select column B and choose “split text to columns” under “data”
8. Choose “space” as separator and a new column appears in column C
9. Use =CONCATENATE(B2,(“ ”),C2,(“ ”),A2) to concatenate first name, middle name, last name in order
10. Copy down the formula to the entire column by double-clicking the plus
