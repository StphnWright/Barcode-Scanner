ZipTest.java

ZipTest.java is the main class and communicates with Zipcode.java through lines
23 and 30 of the main. In Zipcode.java I used else if statements to convert barcodes
to digits and digits to barcodes. The else if statement was used for efficiency, 
given that it will return a digit or string as soon as a match is found. I converted
the zipcode to an array of digits in lines 85-94, starting from the right-most digit
and working backwards. I felt that working backwards would be more efficient and limit
additional steps to compute while isolating digits from the left-most point. I used if
statements in the methods to get barcode and get zipcode. If I were to do it differently,
I would add different layers of validation to block invalid entries in the main class,
such as letters or zipcodes longer than five digits. 
