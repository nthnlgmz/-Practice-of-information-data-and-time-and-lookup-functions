# Information-Functions
><b>What are information functions?</b><br>
-The <b><i>INFO</b></i> function is a built in function in Excel that is categorized as an Information Function.<br>
-It can be used as a worksheet function (WS) in Excel.<br>
-As a worksheet function, the INFO function can be entered as part of a formula in a cell of a worksheet.<br>
The functions listed below are grouped into INFORMATION FUNCTIONS category. <br>
-Error info functions<br>
-Numerical info functions<br>
>-Other data type functions<br>

<b>ISERROR Function</b><br>
>-The Excel <b><i>ISERROR</b></i> function returns TRUE for any error type excel generates, including #N/A, #VALUE!, #REF!, #DIV/0!, #NUM!, #NAME?, or #NULL!<br>
<b>Syntax</b><br>
=ISERROR (value)<br>
![image](https://github.com/ralphgrm/Information-Functions/assets/134179620/4460fc7f-2d7c-4862-bb93-dfe84d441edd)


<b>ISERR Function</b><br>
>-The Excel <b><i>ISERR</b></i> function returns TRUE for any error type except the #N/A error.<br>
<b>Syntax</b><br>
=ISERR(value)<br>
![image](https://github.com/ralphgrm/Information-Functions/assets/134179620/b2772d65-5d3f-482a-bc65-7a2f074d7156)


<b>ISNA Function</b><br>
>-The Excel <b><i>ISNA</b></i> function returns TRUE when a cell contains the #N/A error and FALSE for any other value, or any other error type.<br>
<b>Syntax</b><br>
=ISNA(value)<br>
![image](https://github.com/ralphgrm/Information-Functions/assets/134179620/01ac19f4-2850-4411-bdc3-73207252946e)


<b>ERROR.TYPE Function</b><br>
>-The Excel <b><i>ERROR.TYPE</b></i> function returns a number that corresponds to a specific error value.<br>
-You can use <b><i>ERROR TYPE</b></i> to test specific kinds of errors.<br>
-If no error exists, <b><i>ERROR.TYPE</b></i> returns #N/A.<br>
-See left for a key to the error codes returned by ERROR.TYPE<br>
<b>Syntax</b><br>
=ERROR.TYPE(value)<br>
![image](https://github.com/ralphgrm/Information-Functions/assets/134179620/67e66120-8a4b-412a-ba52-87f4ace8c9b1)


<b>ISNUMBER Function</b><br>
>-The Excel <b><i>ISNUMBER</b></i> function returns TRUE when a cell contains a number, and FALSE if not.<br>
<b>Syntax</b><br>
ISNUMBER (value)<br>
![image](https://github.com/ralphgrm/Information-Functions/assets/134179620/a4841fe8-25dc-4319-a352-fc7509823785)


<b>ISEVEN Function</b><br>
>-The Excel <b><i>ISEVEN</b></i> function returns TRUE when a numeric value is even, and FALSE for odd numbers.<br>
-<b><i>ISEVEN</b></i> will return the #VALUE error when a value is not numeric.<br>
<b>Syntax</b><br>
=ISEVEN(value)<br>
![image](https://github.com/ralphgrm/Information-Functions/assets/134179620/bda214fd-e7ca-4e25-8ddb-44382337c355)


<b>ISODD Function</b><br>
>-The Excel <b><i>ISODD</b></i> function returns TRUE when a numeric value is odd, and FALSE for even numbers.<br>
-<b><i>ISODD</b></i> will return the #VALUE error when a value is not numeric.<br>
<b>Syntax</b><br>
=ISODD (value)<br>
![image](https://github.com/ralphgrm/Information-Functions/assets/134179620/efa6e832-3d9b-4f7f-917a-a9801d00f72c)


<b>ISBLANK Function</b><br>
>-The Excel <b><i>ISBLANK</b></i> function returns TRUE when a cell contains is empty, and FALSE when a cell is not empty.<br>
<b>Syntax</b><br>
=ISBLANK(value)<br>
![image](https://github.com/ralphgrm/Information-Functions/assets/134179620/b6e2537d-857d-4219-8f45-be4316cfe0fa)

<b>ISLOGICAL Function</b><br>
>-The Excel <b><i>ISLOGICAL</b></i> function returns TRUE when a cell contains the logical values TRUE or FALSE, and returns FALSE for cells that contain any other value, including empty cells.<br>
<b>Syntax</b><br>
=ISLOGICAL(value)<br>
![image](https://github.com/ralphgrm/Information-Functions/assets/134179620/b61e00a7-901d-450a-b9ab-247ab0dc2d54)


<b>ISTEXT Function</b><br>
>-The Excel <b><i>ISTEXT</b></i> function returns TRUE when a cell contains a text, and FALSE if not.<br>
<b>Syntax</b><br>
=ISTEXT(value)<br>
![image](https://github.com/ralphgrm/Information-Functions/assets/134179620/d973050f-4d7f-4f57-869a-5b96ee83e91d)


<b>ISNONTEXT Function</b><br>
>-The Excel <b><i>ISNONTEXT</b></i> function returns TRUE for any non text value, for example, a number, a date, a time, etc.<br>
-The <b><i>ISNONTEXT</b></i> function also returns TRUE for blank cells, and for cells with formulas that return non text results.<br>
<b>Syntax</b><br>
=ISNONTEXT(value)<br>
![image](https://github.com/ralphgrm/Information-Functions/assets/134179620/773ae73b-1aa7-4cdb-900f-241f4aa969eb)


<b>ISREF Function</b><br>
>-The Excel <b><i>ISREF</b></i> returns TRUE when a cell contains a reference or space and FALSE if not.<br>
-You can use the <b><i>ISREF</b></i> function to check if a cell contains a valid reference.<br>
Syntax</b><br>
=ISREF(value)<br>
![image](https://github.com/ralphgrm/Information-Functions/assets/134179620/c9d147ec-2517-494b-b55b-79393694d2cf)


<b>ISFORMULA Function</b><br>
>-The Excel <b><i>ISFORMULA</b></i> function returns TRUE when a cell contains a formula, and FALSE if not.<br>
-When a cell contains a formula <b><i>ISFORMULA</b></i> will return TRUE regardless of the formula's output or error conditions<br>
<b>Syntax</b><br>
=ISFORMULA(value)<br>
![image](https://github.com/ralphgrm/Information-Functions/assets/134179620/787080ac-1500-4f78-b2c0-44b2ea1f3b7e)


<b>TYPE Function</b><br>
>-The Excel <b><i>TYPE</b></i> function returns a numeric code representing "type" in 5 categories:<br>
number = 1, text = 2, logical = 4, error = 16, and array = 64.<br>
-Use <b><i>TYPE</b></i> when the operation of a formula depends on the type of value in a particular cell.<br>
<b>Syntax</b><br>
=TYPE(value)<br>
![image](https://github.com/ralphgrm/Information-Functions/assets/134179620/5f4575c5-0dc7-4178-8a47-0ccdebb20025)

# DATE-AND-TIME-FUNCTION

<b> What are DATE AND TIME Function?</b><br>
-Date and Time Function are set of Function in Microsoft Excel that are useful to work with dates.<br>
-And used to schedule payroll and payments,track employee performance reviews,years of service and keep track of orders and payments.<br>

# CREATING DATE AND TIME FUNCTION

<b>The function listed below are grouped into DATE and TIME category.</b><br>
-DATE()<br>
-TIME()<br>
-DATEVALUE()<br>
-TIMEVALUE()<br>

# DATE FUNCTION 

-<b>The Excel DATE function creates a valid date from individual year,month,and day components.</b><br>
-<b>The DATE function is useful for assembling dates that need to change dynamically based on onther values in a worksheet<./b><br>

*Syntax=Date(Year,Month<Day)

![image](https://github.com/DMBysnGnzls/Practice-of-information-data-and-time-and-lookup-functions/assets/143982031/b7d8c881-0429-45d9-9a2e-e90b15c2b01d)

# TIME FUNCTION
<b>-The Excel TIME function is a built in function that allows you to create a time with individual hour,minute,and second components.</b><br>
<b>-Useful when you want to assemble a proper time inside another formula.</b><br>

*Syntax=TIME(Hour,Minute,Second)

![image](https://github.com/DMBysnGnzls/Practice-of-information-data-and-time-and-lookup-functions/assets/143982031/5de67859-cdf2-4c16-a82d-088d266cf77b)


# DATEVALUE FUNCTION
<b>-The Excel DATEVALUE function converts text that appears in a recognized format(i.e.a Number,Date,or Time format) into a numeric value.</b><br>

*Syntax=Datevalue("year-month-day")

![image](https://github.com/DMBysnGnzls/Practice-of-information-data-and-time-and-lookup-functions/assets/143982031/9da956d3-162d-4ccc-b316-ba5e6e15315a)

# TIMEVALUE FUNCTION
<b>-The Excel TIMEVALUE function converts a time represented as text into a proper Excel time.</b><br>
*Syntax=TIMEVALUE("Time_text")

![image](https://github.com/DMBysnGnzls/Practice-of-information-data-and-time-and-lookup-functions/assets/143982031/93b8bdd7-6d50-4f58-ba8c-13ee27b2b5d7)

# CURRENT DATE AND TIME
<b>-The functions listed below are grouped into Current Date and Time category.</b><br>
-NOW()<br>
-TODAY()<br>
![image](https://github.com/DMBysnGnzls/Practice-of-information-data-and-time-and-lookup-functions/assets/143982031/c7425ad2-937a-48f6-ae69-e87d8a0ca14b)

# NOW AND TODAY FUNCTION
<b>-The Excel NOW() function returns the current date and time,updated continuously when a worksheet is changed or opened.<br>
-The Excel TODAY() function returns the current date, updatedcontinuously when a worksheet is changed or opened.
</b><br>

*NOTE:<br>
-Both function takes no arguments.<br>
*Syntax<br>
=NOW()<br>
=TODAY()<br>

![image](https://github.com/DMBysnGnzls/-Practice-of-information-data-and-time-and-lookup-functions/assets/143982031/f1c41a4f-eef3-4568-b249-b1588d5f534c)


# EXTRACTING THE COMPONENTS OF A TIME
<b>-The functions listed below are grouped into Extracting The Components of a Time category</b><br>
*HOUR()<br>
*MINUTE()<br>
*SECOND()<br> 

# HOUR FUNCTION-
<b>-The Excel HOUR function returns the hour component of a time
as a number between 0 23. For example, with a time of 9:30 AM,
HOUR will return 9.</b><br>
*Syntax=HOUR(serial_number)<br>

<b>Serial Number</b><br>
-Microsoft Excel stores dates as sequential serial numbers so
they can be used in calculations.<br>
-By default, January 1, 1900 is serial number 1, and January
At 2008 is serial number 39448 because it is 39,448 days
after January 1, 1900.<br>

# MINUTE FUNCTION
<b>The Excel MINUTE function extracts the minute component of a time as a number between 0 59,</b><br>
-For example, with a time of 9:34 AM, minute will return 34.
*Syntax=MINUTE(serial_number)<br>

# SECOND FUNCTION
<b>The Excel SECOND function returns the second component of a time as a number between 0 59.</b>
-For example, with a time of 9:10:15 AM, second will return 15.<br>
*Syntax=SECOND(serial_number)

![image](https://github.com/DMBysnGnzls/-Practice-of-information-data-and-time-and-lookup-functions/assets/143982031/17181f4e-b596-4718-b97b-6c3102ceaa02)


# Extracting The Components of a Date
<b>-The functions listed below are grouped into Extracting The
Components of a Date category.</b><br>
*DAY()<br>
*MONTH()<br>
*YEAR()<br>
*WEEKNUM()<br>
*WEEKDAY()<br>

# DAY FUNCTION
<b>-The Excel DAY function returns the day of the month as a
number between 1 to 31 from a given date.<br>
-You can use the DAY function to extract a day number from a
date into a cell.</b><br>
*Syntax=DAY(serial_number)

# MONTH FUNCTION
<b>-The Excel MONTH function extracts the month from a given date as number between 1 to 12.</b><br>
*Syntax=MONTH(serial_number)

# YEAR FUNCTION
<b>-The Excel YEAR function returns the year component of a
date as a 4 digit number.</b><br>
*Syntax=YEAR(serial_number)

![image](https://github.com/DMBysnGnzls/-Practice-of-information-data-and-time-and-lookup-functions/assets/143982031/370501b2-b50d-4be2-8d94-23e92188c735)


# WEEKNUM FUNCTION
<b>-The Excel WEEKNUM function takes a date and returns a week number (1 54) that corresponds to the week of year.<br>
-The WEEKNUM function starts counting with the week that contains January 1.<br>
-By default, weeks begin on Sunday.</b><br>
*Syntax=WEEKNUM(serial_number)

![image](https://github.com/DMBysnGnzls/-Practice-of-information-data-and-time-and-lookup-functions/assets/143982031/da047dcf-f892-4048-94c4-2d2ca483fce6)


# WEEKDAY FUNCTION
<b>-The Excel WEEKDAY function takes a date and returns a number between 1 7 representing the day of week.<br>
-By default, WEEKDAY returns 1 for Sunday and 7 forSaturday.</b><br>
*Syntax=WEEKDAY(serial_number)

![image](https://github.com/DMBysnGnzls/-Practice-of-information-data-and-time-and-lookup-functions/assets/143982031/ef38abcf-d700-40e6-9bb8-e562f7347ff4)

# EDATE FUNCTION
<b>-The Excel EDATE function returns a date on the same day of the month, n months in the past or future.<br>
-You can use EDATE to calculate expiration dates, maturity dates, and other due dates.</b><br>
*Syntax=EDATE(start_date,months)

![image](https://github.com/DMBysnGnzls/-Practice-of-information-data-and-time-and-lookup-functions/assets/143982031/105ce4ae-c99f-4c8e-a50d-a3d6cc7e0b4b)


# EOMONTH FUNCTION
<b>-The Excel EOMONTH function returns the last day of the month.</b><br>
*Syntax=EOMONTH(start_date,months)

![image](https://github.com/DMBysnGnzls/-Practice-of-information-data-and-time-and-lookup-functions/assets/143982031/c88fb74f-a988-4ecf-8614-21c2080c7a2b)


# WORKDAY FUNCTION
<b>-The Excel WORKDAY function takes a date and returns the nearest working day in the future or past.<br>
-You can use the WORKDAY function to calculate things like ship dates, delivery dates, and completion dates that need to take into account working and non working days</b><br>
*Formula=WORKDAY(start_date,days,[holidays])<br>
<b>-Parameters<br>
start_date - The date from which to start.<br>
days - The working days before or after start_date<br>
holidays - [optional] A list dates that should be considered non working days.</b><br>

![image](https://github.com/DMBysnGnzls/-Practice-of-information-data-and-time-and-lookup-functions/assets/143982031/2289d229-e603-497e-876f-6b0e394f4393)


# WORKDAY.INTL FUNCTION
<b>-The Excel WORKDAY.INTL function takes a date and returns the nearest working in the future or past, based on an offset value you provide. <br>
-Unlike the WORKDAY, WORKDAY.INTL allows you to customize which days are considered weekends (non working days).</b><br>
*Syntax=WORKDAY.INTL(start_date,days,[weekend],[holidays])<br>
<b>-Parameters
-start_date The start date.<br>
-days - The end date.<br>
-weekend - [optional] Setting for which days of the week should be considered weekends.<br>
-holidays - [optional] A list of one or more dates that should be considered non working days.</b><br>

![image](https://github.com/DMBysnGnzls/-Practice-of-information-data-and-time-and-lookup-functions/assets/143982031/4b53c710-c45d-4d5e-9e5b-9f91c4400965)


# DAYS FUNCTION
<b>-The Excel DAYS function returns the number of daysbetween two dates.<br>
-With a start date in A1 and end date in B1, =DAYS(B1,A1) will return the days between the two dates.</b><br>
*Syntax=DAYS(end_date,start_date)

![image](https://github.com/DMBysnGnzls/-Practice-of-information-data-and-time-and-lookup-functions/assets/143982031/6d99d4d2-b121-4e7b-91ce-2f71a85642ab)




# Lookup-Functions

<b>LOOKUP Function</b><br>
>👉The <b><i>LOOKUP</b></i> function in Excel is a versatile function that can perform both approximate and exact matches. It is often used to search for a value in a single row or column and return a corresponding value from another row or column.<br>
>👉Syntax: =LOOKUP(lookup_value, lookup_vector, result_vector)<br>
<b><i>lookup_value</b></i>: The value you want to find in the lookup_vector.<br>
<b><i>lookup_vector</b></i>: The range of cells that contains the values you want to search within.<br>
<b><i>result_vector</b></i>: The range of cells that contains the corresponding values you want to retrieve.<br>
>👉The <b><i>LOOKUP</b></i> function is not case-sensitive and assumes the data in the lookup_vector is sorted in ascending order. If the data is not sorted, it may return unexpected results.<br>
>![image](https://github.com/nthnlgmz/Lookup-Functions/assets/143614589/c918b24c-a97e-42c4-9a91-f3b7f82d6ee7)

<b>VLOOKUP Function</b><br>
>👉The VLOOKUP function (Vertical Lookup) is used to search for a value in the leftmost column of a table and return a corresponding value from a specified column to the right.<br>
>👉Syntax: =VLOOKUP(lookup_value, table_array, col_index_num, [range_lookup])<br>
<b><i>lookup_value</b></i>: The value you want to find in the leftmost column of the table_array.<br>
<b><i>table_array</b></i>: The range of cells that contains the data you want to search in. This range should include the leftmost column and the column from which you want to retrieve data.<br>
<b><i>col_index_num</b></i>: The column number from which you want to retrieve data (1 for the leftmost column, 2 for the second column, and so on).<br>
<b><i>[range_lookup]</b></i>: An optional argument that can be set to TRUE (approximate match) or FALSE (exact match). If omitted or set to TRUE, VLOOKUP will perform an approximate match, and if set to FALSE, it will perform an exact match.<br>
>👉<b><i>VLOOKUP</b></i> is commonly used for vertical data lookup, such as searching for information in a table based on a unique identifier.<br>
>![image](https://github.com/nthnlgmz/Lookup-Functions/assets/143614589/91901cff-2448-4cf9-830f-9a7684afdfa7)

