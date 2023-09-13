# Lookup-Functions

<b>LOOKUP Function</b><br>
>👉The <b><i>LOOKUP</b></i> function in Excel is a versatile function that can perform both approximate and exact matches. It is often used to search for a value in a single row or column and return a corresponding value from another row or column.<br>
>👉Syntax: =LOOKUP(lookup_value, lookup_vector, result_vector)<br>
<b><i>lookup_value</b></i>: The value you want to find in the lookup_vector.<br>
<b><i>lookup_vector</b></i>: The range of cells that contains the values you want to search within.<br>
<b><i>result_vector</b></i>: The range of cells that contains the corresponding values you want to retrieve.<br>
>👉The <b><i>LOOKUP</b></i> function is not case-sensitive and assumes the data in the lookup_vector is sorted in ascending order. If the data is not sorted, it may return unexpected results.<br>
![image](https://github.com/nthnlgmz/Lookup-Functions/assets/143614589/c918b24c-a97e-42c4-9a91-f3b7f82d6ee7)

<b>VLOOKUP Function</b><br>
>👉The VLOOKUP function (Vertical Lookup) is used to search for a value in the leftmost column of a table and return a corresponding value from a specified column to the right.<br>
>👉Syntax: =VLOOKUP(lookup_value, table_array, col_index_num, [range_lookup])<br>
<b><i>lookup_value</b></i>: The value you want to find in the leftmost column of the table_array.<br>
<b><i>table_array</b></i>: The range of cells that contains the data you want to search in. This range should include the leftmost column and the column from which you want to retrieve data.<br>
<b><i>col_index_num</b></i>: The column number from which you want to retrieve data (1 for the leftmost column, 2 for the second column, and so on).<br>
<b><i>[range_lookup]</b></i>: An optional argument that can be set to TRUE (approximate match) or FALSE (exact match). If omitted or set to TRUE, VLOOKUP will perform an approximate match, and if set to FALSE, it will perform an exact match.<br>
>👉<b><i>VLOOKUP</b></i> is commonly used for vertical data lookup, such as searching for information in a table based on a unique identifier.
![image](https://github.com/nthnlgmz/Lookup-Functions/assets/143614589/91901cff-2448-4cf9-830f-9a7684afdfa7)

