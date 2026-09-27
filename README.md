# First-Assignment_2nd-week
My first assignment on 2nd week
Perform the following in the dataset from the 'Dataset' sheet.		
		
	1) Sum, Count, Average:	
		• What is the total price of all products in the dataset?
		• How many products are there in the dataset?
		• Calculate the average price of the products.
		
	2) Min and Max:	
		• Determine the minimum price among all products.
		• Find the maximum price among all products.
		
	3) IF Function:	
		• Using an IF function, create a new column named Price Range to categorize products with a price greater than or equal to $500 as 'High Price' and others as 'Standard Price'.
		
	4) SUMIF and COUNTIF:	
		• Calculate the total price for products in the 'Electronics' category using the SUMIF function.
		• Determine the count of products with a price less than $100 using the COUNTIF function.
		
	5) Text Formatting - LEFT, RIGHT, MID:	
		• Create a new column named Day with the first 2 characters of each 'Product ID' using the LEFT function.
		• Create a new column named Country Code by extracting the last 2 characters from the 'Product ID' column using the RIGHT function.
		• Create a new column named Month by extracting 4th to 6th characters from the 'Product ID' column using the MID function.
Answer:
First create one new sheet. Name is solution
Sum () syntax
=SUM (G2:G35)
count(),
=COUNT(G2:G35)
Round() 
=ROUND(AVERAGE(G2:G35),2)
Min()
=MIN(G2:G35)
max()
=MAX(G2:G35)
Sumif()
=SUMIF(J2:J35,"Electronics",G2:G35)
countif()
=COUNTIF(G2:G35,"<100")
if function
=IF(G2>=500,"High price","Standard Price")
left()
=LEFT(A2,2)
right()
=RIGHT(A2,2)
mid()
=MID(A2,4,3)
then am using table format,insert etc
These Function all are using this excel sheet
