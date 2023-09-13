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

