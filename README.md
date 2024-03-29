<div style="text-align: center;">
  <div align="center">
    <h1>Marvel Cinematic Universe Box Office Dataset</h1>
  </div>
</div>

![marvel group8](https://github.com/aprilrhose/Movie_MCU-Dataset_GROUP8/assets/143881769/3dbd2a98-8e66-4a39-b06b-a6bf3f50b1cb)

<div align="center">
  <div style="font-style: Autor one;">
  Authors: Niela Mae Dimaculangan, Clarence Joy Ilagan, and April Rhose Mercado
  </div>
</div>  
<br>

<br>
<div align="center">
  <strong>This repository contains dashboards for Marvel Cinematic Universe Box Office Dataset starting from the year 2008 to year 2021.</strong>
</div>  
<br>

![MCU](https://github.com/aprilrhose/Movie_MCU-Dataset_GROUP8/assets/143881769/bbda7c5f-ed47-44d9-9caf-b40631f4c335)
<br>
<br>
<div align="center">
  Here are the set of data that will be used throughout the discussion. If you want to see it clearly or if you want to have access on the original file, you can go to this link: https://www.kaggle.com/datasets/davidgdong/marvel-cinematic-universe-box-office-dataset/data 
</div>

![DATA SET (1)](https://github.com/aprilrhose/Movie_MCU-Dataset_GROUP8/assets/143881769/742c9cf8-9773-40a5-9d22-84fb8da208d4)

<br>

<div style="text-align: center;">
  <div align="center">
    <h1>𝗠𝗖𝗨 𝗗𝗔𝗦𝗛𝗕𝗢𝗔𝗥𝗗</h1>
  </div>
</div>

<p align="center">
  <img src="https://github.com/NielaMaeD/Movie_MCU-Dataset_GROUP8/assets/144228573/3a5b863f-cc62-467d-a1a0-d6cfc116369f">
</p>

# **EXCEL FUNCTIONS**
<details>
<summary>Text Function</summary>
  
>In Microsoft Excel, the **TEXT function** is a function that allows you to format a numeric value as text based on a specified format code. You can use this function to display texts, numbers, dates, and times in a way that makes them more readable, user-friendly or adheres to a specific format. This function is valuable for creating custom-formatted labels, data exports, reports, and more. For this part, LEN function, UPPER function, LOWER function, Proper Function, and LEFT function will be shown.

<details>
  <summary>𝗟𝗘𝗡 𝗙𝘂𝗻𝗰𝘁𝗶𝗼𝗻</summary>
  
>The **LEN Function** is used to count the number of characters in a given text string, including letters, numbers, symbols, and spaces. The basic syntax for this function  is **=LEN(text)**. 

>For example, if cell A1 contains the text "Iron Man", then you can use **=LEN(A1)**. The result will be 8 as there are 8 characters in the text including letters, comma, and spaces.
  <p align="center">
  <img src="https://github.com/aprilrhose/Movie_MCU-Dataset_GROUP8/assets/143881769/cc708df8-ec60-4c8b-9e78-260b0e57e828">
  </p>
</details>

<details>
  <summary>𝗨𝗣𝗣𝗘𝗥 𝗙𝘂𝗻𝗰𝘁𝗶𝗼𝗻</summary>

>The **UPPER function** is a text function that is used to convert all the letters in a given text string to uppercase. It is a simple yet valuable tool for text manipulation and data processing. The basic syntax for this function is UPPER(text).

>For example, if cell A1 contains the text "Iron Man", then you can use **=UPPER(A1)**. The result will be "IRON MAN" as all the letters are converted to uppercase.
  <p align="center">
  <img src="https://github.com/aprilrhose/Movie_MCU-Dataset_GROUP8/assets/143881769/02d64771-65e4-4cb7-93e3-65df5b0d575c">
  </p>
</details>

<details>
  <summary>𝗟𝗢𝗪𝗘𝗥 𝗙𝘂𝗻𝗰𝘁𝗶𝗼𝗻</summary>
  
>The **LOWER function** is a text function used to convert all the letters in a given text string to lowercase. Same with UPPER function, it is also a fundamental tool for text manipulation and data processing. The basic syntax for this function is **=LOWER(text)**.

>For example, if cell A1 contains the text "Thor" or "THOR", then you can use **=LOWER(A1)**. The result will be "thor" as all the letters are converted to lowercase.
  <p align="center">
  <img src="https://github.com/aprilrhose/Movie_MCU-Dataset_GROUP8/assets/143881769/c802a37e-66a7-4be0-b0e3-7d2947f0c44a">
  </p>  
</details>

<details>
  <summary>𝗣𝗥𝗢𝗣𝗘𝗥 𝗙𝘂𝗻𝗰𝘁𝗶𝗼𝗻</summary>
  
>The **PROPER function** is a text function used to capitalize the first letter of each word in a text string while converting the rest of the letters to lowercase. It is a valuable tool for text manipulation, especially when dealing with data where you want to ensure consistent and well-formatted capitalization. The basic syntax for this function is **=PROPER(text)**.

>For example, if cell A1 contains the text "Guardians of the Galaxy," then you can use **=PROPER(A1)**. The result will be "Guardians Of The Galaxy" as the first letter of each word is capitalized.
  <p align="center">
  <img src="https://github.com/aprilrhose/Movie_MCU-Dataset_GROUP8/assets/143881769/61ea976d-d8da-4eef-aec2-bc53821b25dc">
  </p>
</details>

<details>
  <summary>𝗟𝗘𝗙𝗧 𝗙𝘂𝗻𝗰𝘁𝗶𝗼𝗻</summary>

>The **LEFT function** is a text function that is used to extract a specified number of characters from the beginning or on the left side of a text string. It is a simple yet highly important tool for text manipulation and data extraction tasks. The basic syntax for this function is **=LEFT(text, num_chars)**.

>For example, if cell B4 contains the text "Iron Man" and you want to extract the first 4 characters, then you can use **=LEFT(B4, 4)**. The result will be "Iron".
  <p align="center">
  <img src="https://github.com/aprilrhose/Movie_MCU-Dataset_GROUP8/assets/143881769/a4ef7a44-61c1-4759-b732-be4d49c40cc5">
  </p>
</details>

<div align="center">
  <strong>Overall, the TEXT function is a versatile tool in Excel that plays a significant role in data formatting and presentation, making data more understandable and visually appealing. It's widely used in financial, accounting, and data analysis tasks, among others.</strong>
</div>

</details>

<details>
  <summary>Math Functions</summary>
  
>**Math Function** generally refers to a category of mathematical functions and operations that can be performed in mathematical calculations within Excel and similar programs. For this part, SUM function, AVERAGE function, MIN & MAX function, ROUND Function, and TRUNC function will be shown.

  <details>
    <summary>𝗦𝗨𝗠 𝗙𝘂𝗻𝗰𝘁𝗶𝗼𝗻</summary>
    
>The **SUM function** is one of the most fundamental and widely used mathematical functions. It is essential for adding a range of numbers together. The basic syntax for this function is **=SUM(number1, number2, ...)**.

>For example, if you have a range of numbers in cells A1 to A5, you can use **=SUM(A1:A5)**

>The **SUM function** will add up all the values in cells A1 to A5 and return the total.

  <div align="center">
    <strong>For this table of values, SUM function was used to get the total sales of the movies from its opening weekend,</strong>
  </div>
  <div align="center">
    <strong>its domestic box office and from its worldwide box office.</strong>
  </div>
  <p align="center">
  <img src="https://github.com/aprilrhose/Movie_MCU-Dataset_GROUP8/assets/143881769/99a131b7-7208-409a-aa04-8de18144db21">
  </p>
  <br>
  </details>

  <details>
    <summary>𝗔𝗩𝗘𝗥𝗔𝗚𝗘 𝗙𝘂𝗻𝗰𝘁𝗶𝗼𝗻</summary>

>The **AVERAGE function** is a mathematical function used to calculate the average or arithmetic mean of a set of numbers. It is an essential tool for analyzing data and deriving a central tendency or average value. The basic syntax for this function is **=AVERAGE(number1, number2, ...)**

>For example, if you have a range of test scores in cells A1 to A10, you can use **=AVERAGE(A1:A10)**

>The AVERAGE function will calculate the average of the test scores in cells A1 to A10 and return the result.

<br>
<div align="center">
  <strong>For this table of values, AVERAGE function was used to get the average sales of the movies from its opening weekend,</strong>
</div>
<div align="center">
  <strong>its domestic box office and from its worldwide box office.</strong>
</div>

<p align="center">
  <img src="https://github.com/aprilrhose/Movie_MCU-Dataset_GROUP8/assets/143881769/c593455b-bece-4f40-98d9-f26762325e33">
</p>
<br>
  </details>

  <details>
    <summary>𝗠𝗜𝗡 & 𝗠𝗔𝗫 𝗙𝘂𝗻𝗰𝘁𝗶𝗼𝗻</summary>
    
>The **MIN and MAX Functions** are mathematical functions used to find the minimum (lowest) and maximum (highest) values within a range of numbers or cells, respectively. These functions are essential for various tasks, particularly when you need to identify the extremes or boundaries of a dataset.

>The **MIN Function** is used to find the smallest value in a set of numbers. The basic syntax for this function is **=MIN(number1, number2, ...)** where **number1, number2, ...** represents the individual numbers or cell references you want to compare to find the minimum value.

>For example, if you have a range of test scores in cells A1 to A10, you can use **=MIN(A1:A10).** It will return the lowest test score in that range.

>**MAX Function**, on the other hand, is used to find the largest value in a set of numbers. The basic syntax for this function is **=MAX(number1, number2, ...)**

>If you have a range of sales figures in cells B1 to B10, you can use **=MAX(B1:B10).** It will return the highest sales figure in that range.
<br>

<div align="center">
  <strong>For this table of values, MIN and MAX functions were used to get the minimum and maximum sales of the movies</strong>
</div>
<div align="center">
  <strong>from its opening weekend, its domestic box office and from its worldwide box office.</strong>
</div>
<p align="center">
  <img src="https://github.com/aprilrhose/Movie_MCU-Dataset_GROUP8/assets/143881769/e41c389c-db14-4e32-abec-c4098ea4b2e3">
</p>     
  </details>

  <details>
    <summary>𝗥𝗢𝗨𝗡𝗗 𝗙𝘂𝗻𝗰𝘁𝗶𝗼𝗻</summary>

>The **ROUND function** is a mathematical function used to round a number to a specified number of decimal places. It is important for several reasons and plays a critical role in various applications. The basic syntax for this function **is =ROUND(number, num_digits)**

>The **number** is the number you want to round while the **num_digits** is the number of decimal places to which you want to round the number.

>For this table of values, since data are all whole numbers, we rounded it up to the nearest millions thus, the formula used was **=ROUND(A3,-6)**

<p align="center">
  <img src="https://github.com/aprilrhose/Movie_MCU-Dataset_GROUP8/assets/143881769/4bcd7e49-2ca6-4e30-bdc0-e09b76220b8b">
</p>
  </details>

  <details>
    <summary>𝗧𝗥𝗨𝗡𝗖 𝗙𝘂𝗻𝗰𝘁𝗶𝗼𝗻</summary>

>The **TRUNC function** is used to truncate a number to a specified number of decimal places. It essentially removes the decimal portion of a number, leaving only the integer part. The basic syntax for this function is **=TRUNC(number, [num digits])**.

>The **number** represents the number you want to truncate while **[num digits]** is the number of decimal places you want to truncate the number. If omitted, it defaults to 0 which means the number is truncated to a whole number. 

>For this table of values, since data are all whole numbers, we truncated the numbers with -8, the formula used was **=TRUNC(A3,-8)** thus the values defaults to 0.

<p align="center">
  <img src="https://github.com/aprilrhose/Movie_MCU-Dataset_GROUP8/assets/143881769/f2f84976-7103-4bd7-9f4d-82cf420a59f5">
</p>
  </details>
  
<div align="center">
  <strong>The importance of mathematical functions in Excel and similar tools cannot be overstated. These functions are used in various fields, including finance, engineering, science, statistics, and data analysis. They enable users to perform complex calculations, analyze data, and make informed decisions. Mathematical functions are critical for creating models, generating reports, and solving a wide range of problems in different industries and disciplines.</strong>
</div>

</details>

<details>
  <summary>LOGICAL Functions</summary>
  
>Logical functions in Excel are a category of functions that help make decisions and perform calculations based on conditions or logical tests. These functions are crucial for creating more complex and dynamic spreadsheets, automating tasks, and performing data analysis. For this part of discussion, IF Function, AND Function, OR Function, NOT Function and OR Function will be used.

  <details>
    <summary>𝗜𝗙 𝗙𝘂𝗻𝗰𝘁𝗶𝗼𝗻</summary>

>The **IF function** is one of the most fundamental and widely used functions in Excel. It is essential for making logical decisions and performing different actions based on specific conditions. The IF function allows you to create conditional statements in your spreadsheets. The basic syntax for this function is **=IF(logical_test, value_if_true, value_if_false)**

>**logical_test** is a condition that you want to evaluate. If this condition is met, the function returns value_if_true. If the condition is not met, the function returns value_if_false.

>**value_if_true** is the value that the function returns if the logical_test evaluates to TRUE.

>**value_if_false** is the value that the function returns if the logical_test evaluates to FALSE.

<br>
<div align="center">
  <strong>This data used the IF Function by comparing the production budget for the films and its box office sales</strong>
</div>

<div align="center">
  <strong>from the opening weekend, domestic, and worldwide sales to determine if it gained Profit or Loss</strong>
</div>


<p align="center">
  <img src="https://github.com/aprilrhose/Movie_MCU-Dataset_GROUP8/assets/143881769/894681f5-708a-4aba-8e10-e24d12bd81e4">
</p>
  </details>

  <details>
    <summary>𝗔𝗡𝗗 𝗙𝘂𝗻𝗰𝘁𝗶𝗼𝗻</summary>

>The **AND function** is a logical function that allows you to perform a logical "AND" operation on multiple conditions. It returns TRUE if all the specified conditions are met, and FALSE if any one of the conditions is not met. The basic syntax for this function is **=AND(logical1, logical2, logical3, ...)**

>**logical1, logical2, logical3,** and so on are the conditions or logical tests you want to evaluate

<br>
<div align="center">
  <strong>For this dataset, AND Function was used to determine if all of the three sales are greater than the</strong>
</div>

<div align="center">
  <strong>production budget</strong>
</div>

<p align="center">
  <img src="https://github.com/aprilrhose/Movie_MCU-Dataset_GROUP8/assets/143881769/9617ca6b-f39f-4188-8800-677c49e645a3">
</p>     
  </details>
  
  <details>
    <summary>𝗢𝗥 𝗙𝘂𝗻𝗰𝘁𝗶𝗼𝗻</summary>
 
>The **OR function** is a logical function that allows you to perform a logical "OR" operation on multiple conditions. It returns TRUE if at least one of the specified conditions is true, and FALSE only if all of the conditions are false. Here's the basic syntax for this function is **=OR(logical1, logical2, logical3, ...)**

>logical1, logical2, logical3, and so on are the conditions or logical tests you want to evaluate. You can include up to 255 different conditions.

<br>
<div align="center">
  <strong>For this table of values, OR Function was used to determine if either of the three sales are greater than the</strong>
</div>

<div align="center">
  <strong>production budget</strong>
</div>

<p align="center">
  <img src="https://github.com/aprilrhose/Movie_MCU-Dataset_GROUP8/assets/143881769/ec2724ba-5e43-40ba-9d80-a60c297582ed">
</p>     
  </details>

  <details>
    <summary>𝗡𝗢𝗧 𝗙𝘂𝗻𝗰𝘁𝗶𝗼𝗻</summary>

>The **NOT function** is a logical function that allows you to perform a logical "NOT" operation on a single condition. It returns TRUE if the specified condition is false and FALSE if the condition is true. The basic syntax for this function is **=NOT(logical)**

>**logical** is the condition or logical test you want to evaluate.

<br>
<div align="center">
  <strong>For this dataset, NOT Function was used to negate the F column</strong>
</div>

<p align="center">
  <img src="https://github.com/aprilrhose/Movie_MCU-Dataset_GROUP8/assets/143881769/052af042-7644-4162-b9d4-91bafbe20901">
</p>
  </details>

  <details>
    <summary>𝗫𝗢𝗥 𝗙𝘂𝗻𝗰𝘁𝗶𝗼𝗻</summary>
    
>The **XOR function** is a logical function that returns TRUE if one of its arguments is TRUE and FALSE if both arguments are TRUE or neither is TRUE. It is also known as the "exclusive OR" function.

<br>

<p align="center">
  <img src="https://github.com/aprilrhose/Movie_MCU-Dataset_GROUP8/assets/143881769/a06fc50f-d42e-4d67-ac18-4a2341c8ae9c">
</p>

<br>
<br>
  </details>
<div align="center">
<strong>Logical functions are fundamental to creating dynamic and intelligent spreadsheets that respond to changing data or user inputs. They help streamline data analysis, automate tasks, and ensure that the spreadsheet's behavior adapts to specific conditions, making Excel a versatile tool for various purposes.</strong>
</div>      

</details>

<details>
  <summary>INFORMATION Functions</summary>
  
>Information functions are a category of functions that provide various types of information about data, cells, or ranges within a spreadsheet. These functions are important for retrieving metadata, such as cell content, formatting, and characteristics. For this part of discussion, ISEVEN Function, ISODD Function, ISNUMBER Function, ISTEXT Function, and ISLOGICAL Function will be shown.

  <details>
    <summary>𝗜𝗦𝗘𝗩𝗘𝗡 𝗙𝘂𝗻𝗰𝘁𝗶𝗼𝗻</summary>

>The **ISEVEN function** is a logical function that returns TRUE if the specified number is even, and FALSE if the specified number is odd. The basic syntax for this function is **=ISEVEN(number)**


<br>
<div align="center">
  <strong>ISEVEN function was used in this table on determining whether the total movie duration is even or not>
</div>
    
<p align="center">
  <img src="https://github.com/aprilrhose/Movie_MCU-Dataset_GROUP8/assets/143881769/6738b22a-f274-4a76-b06b-d3d55618e27f">
</p>
  </details>

  <details>
    <summary>𝗜𝗦𝗢𝗗𝗗 𝗙𝘂𝗻𝗰𝘁𝗶𝗼𝗻</summary>

>The **ISODD function** is a logical function that returns TRUE if the specified value is odd, and FALSE if the specified value is even. The basic syntax for this function is **=ISODD(value)**

<br>

<div align="center">
  <strong>ISODD function was used in this table on determining whether the total movie duration is odd or not>
</div>
    
<p align="center">
  <img src="https://github.com/aprilrhose/Movie_MCU-Dataset_GROUP8/assets/143881769/86562025-748f-4a16-9902-053fbd2a9924">
</p>
  </details>

  <details>
    <summary>𝗜𝗦𝗡𝗨𝗠𝗕𝗘𝗥 𝗙𝘂𝗻𝗰𝘁𝗶𝗼𝗻</summary>

>The **ISNUMBER function** is a logical function that returns TRUE if the specified value is a number, and FALSE if the specified value is not a number. The basic syntax for this is **ISNUMBER(value)**
<br>
<div align="center">
  <strong>ISNUMBER function was used in this table on identifying whether the total movie duration is indeed a number>
</div>
    
<p align="center">
  <img src="https://github.com/aprilrhose/Movie_MCU-Dataset_GROUP8/assets/143881769/ab028216-79dd-42b7-9062-b441c00818aa">
</p>
  </details>

  <details>
    <summary>𝗜𝗦𝗧𝗘𝗫𝗧 𝗙𝘂𝗻𝗰𝘁𝗶𝗼𝗻</summary>

>The **ISTEXT function** is a logical function that returns TRUE if the specified value is text, and FALSE if the specified value is not text. The basic syntax for this function is **=ISTEXT(value)**
<br>
<div align="center">
  <strong>ISTEXT function was used in this table on identifying whether the chosen values are text or not>
</div>
<p align="center">
  <img src="https://github.com/aprilrhose/Movie_MCU-Dataset_GROUP8/assets/143881769/5d88f5fb-26b7-49ae-907e-4f9e3de4f210">
</p>
  </details>

  <details>
    <summary>𝗜𝗦𝗟𝗢𝗚𝗜𝗖𝗔𝗟 𝗙𝘂𝗻𝗰𝘁𝗶𝗼𝗻</summary>

>The **ISLOGICAL function** is a logical function that returns TRUE if the specified value is a logical value (TRUE or FALSE), and FALSE if the specified value is not a logical value. The basic syntax for this function is **=ISLOGICAL(value)**
<br>
<div align="center">
  <strong>ISLOGICAL function was used in this table on identifying whether the chosen values are logical or not>
</div>
<p align="center">
  <img src="https://github.com/aprilrhose/Movie_MCU-Dataset_GROUP8/assets/143881769/4f598f95-99fd-4484-aa01-a59fdcd40bcc">
</p>
  </details>
<div align="center">
<strong>Information functions provide critical details about spreadsheet data and characteristics, contributing to data validation, formatting control, troubleshooting, and creating dynamic and user-friendly reports. While they may not be as commonly used as basic mathematical or logical functions, they play a valuable role in managing and analyzing data effectively in Excel.</strong>
</div>    
</details>

<details>
  <summary>DATE and TIME Functions</summary>
  
>Date and time functions are a category of functions used to work with date and time values. These functions are crucial for managing, calculating, and formatting dates and times in spreadsheets. For this part of discussion, DAY, MONTH, YEAR Function, WEEKNUM Function, DATE Function, WEEKNUM Function and EO Function will be shown.

  <details>
    <summary>𝗗𝗔𝗬, 𝗠𝗢𝗡𝗧𝗛, 𝗬𝗘𝗔𝗥 𝗙𝘂𝗻𝗰𝘁𝗶𝗼𝗻</summary>

>The **DAY, MONTH, and YEAR functions** are date and time functions that return the day, month, and year of a date value, respectively. The basic syntax for these functions are;

>**=DAY(date)** where date is the date value that you want to extract the day from. The MONTH function has the following syntax:

>**=MONTH(date)** where date is the date value that you want to extract the month from.

>**=YEAR(date)** where date is the date value that you want to extract the year from.

<br>

<div align="center">
  <strong>The DAY, MONTH, and YEAR Functions were used in this data sheet in regards>
</div>

<div align="center">
  <strong>to the release dates of the following Marvel movies>
</div>

<p align="center">
  <img src="https://github.com/aprilrhose/Movie_MCU-Dataset_GROUP8/assets/143881769/4915db68-b07e-431a-bcf2-a60b55ddd614">
</p>
  </details>

  <details>
    <summary>𝗪𝗘𝗘𝗞𝗡𝗨𝗠 𝗙𝘂𝗻𝗰𝘁𝗶𝗼𝗻</summary>
      
>The **WEEKNUM function** is a date and time function that returns the week number of a date serial number. The week number is based on the ISO standard, which defines the first week of the year as the week that contains the first Thursday of the year. The syntax for this function is **=WEEKNUM(serial_number, return_type)**
where:

>**serial_number** is the date serial number that you want to get the week number for.

>**return_type** is an argument that controls which day of the week begins a new week number. The default value is 1, which sets new week numbers to start on Sunday. If you want new week numbers to start on Monday, set the return_type argument to 2.

<br>

<div align="center">
  <strong>The WEEKNUM Fuction was used in this table to determine the date the film was released, in terms of the number of week>
</div>

<p align="center">
  <img src="https://github.com/aprilrhose/Movie_MCU-Dataset_GROUP8/assets/143881769/21c358fe-6520-4b9e-a4be-99f11978a913">
</p>      
  </details>

  <details>
    <summary>𝗗𝗔𝗧𝗘 𝗙𝘂𝗻𝗰𝘁𝗶𝗼𝗻</summary>

>The **DATE function** is a date and time function that returns the date serial number that represents a particular date. The date serial number is a number that represents the number of days since January 1, 1900. The syntax for this function is **=DATE(year, month, day)**

<br>
<div align="center">
  <strong>The DATE Fuction was used in this table for the serial date the films were released>
</div>

<p align="center">
  <img src="https://github.com/aprilrhose/Movie_MCU-Dataset_GROUP8/assets/143881769/23a9684b-548a-4cb8-be98-840c79457cf6">
</p>
  </details>

  <details>
    <summary>𝗪𝗘𝗘𝗞𝗗𝗔𝗬 𝗙𝘂𝗻𝗰𝘁𝗶𝗼𝗻</summary>

>The **WEEKDAY function** is a date and time function that returns the day of the week for a given date. The day of the week is returned as a number, with 1 representing Sunday and 7 representing Saturday. The syntax for this function is **=WEEKDAY(date, [return_type])**

<p align="center">
  <img src="https://github.com/aprilrhose/Movie_MCU-Dataset_GROUP8/assets/143881769/f15ff7ce-3eb8-4288-b38d-848018d75871">
</p>
  </details>

  <details>
    <summary>𝗘𝗢𝗠𝗢𝗡𝗧𝗛 𝗙𝘂𝗻𝗰𝘁𝗶𝗼𝗻</summary>
      
>The **EOMONTH function** is a date and time function that returns the last day of the month that is a specified number of months before or after a start date. The syntax for this function is **=EOMONTH(start_date, months)**

>**start_date** is the date that you want to use as the starting point for the calculation.
>**months** is the number of months before or after the start date that you want to return the last day of the month for. A positive value for months returns a future date, and a negative value for months returns a past date.

<p align="center">
  <img src="https://github.com/aprilrhose/Movie_MCU-Dataset_GROUP8/assets/143881769/b2292e9a-a66b-4a51-bb1f-1717952d052a">
</p>
  </details>
<div align="center">
<strong>Date and time functions are fundamental for working with temporal data in Excel. It enable users to perform calculations, track events, and create dynamic reports that adapt to changes in date and time values. This makes it a versatile tool for tasks ranging from simple date tracking to complex project management and financial modeling.</strong>
</div>
</details>

<details>
  <summary>LOOKUP Functions</summary>

>In Excel, "LOOKUP" generally refers to a category of functions used to search for and retrieve specific data from a table or range of values. There are several lookup functions in Excel and each of it serves a different purpose. For this part, VLOOKUP, MATCH, CHOOSE and AREAS Function will be shown.

  <details>
    <summary>𝗟𝗢𝗢𝗞𝗨𝗣 𝗙𝘂𝗻𝗰𝘁𝗶𝗼𝗻</summary>
 
>The **LOOKUP function** is used to find a specific value within a range of cells and return a corresponding value from another range. The basic syntax for this function is **=LOOKUP(lookup_value, lookup_vector, result_vector)**

>**lookup_value** corrrespondst to the value you want to find within the lookup_vector. It can be a number, text, or logical value.

>**lookup_vector** is the range of cells where Excel searches for the lookup_value. The values in this range must be sorted in ascending order.

>**result_vector**: is the range of cells from which you want to retrieve the corresponding value. The result_vector should be in the same row or column as the lookup_vector.

<br>

<div align="center">
  <strong>For this table of values, the LOOKUP Function was used to find the Marvel movies based on its release date</strong>
</div>

<p align="center">
  <img src="https://github.com/aprilrhose/Movie_MCU-Dataset_GROUP8/assets/143881769/5a2fc70f-da6f-4c2d-9540-2d08562591fa">
</p>
     
  </details>

  <details>
    <summary>𝗩𝗟𝗢𝗢𝗞𝗨𝗣 𝗙𝘂𝗻𝗰𝘁𝗶𝗼𝗻</summary>
    
>The **VLOOKUP function** is one of the most commonly used and important functions for searching and retrieving data from a table or range. "V" in VLOOKUP stands for "vertical," indicating that it is used to search for values in a vertical column. The basic syntax for this function is **=VLOOKUP(lookup_value, table_array, col_index_num, [range_lookup])**

>**lookup_value** is the value you want to find in the first column of your table or range.

>**table_array** is the range of cells where you want to search for the lookup_value. It should include the column containing the lookup_value and the columns from which you want to retrieve data.

>**col_index_num** is the column number from which you want to retrieve the data. It indicates how many columns to the right of the lookup_value column the data is located.

>**[range_lookup]** is typically either TRUE or FALSE (or 1 or 0). If you use TRUE or omit this argument, VLOOKUP will perform an approximate match, finding the closest match to the lookup_value. If you use FALSE or 0, it will perform an exact match.>

<br>

<div align="center">
  <strong>For this dataset, the VLOOKUP Function was used to find what phase of MCU the film belongs</strong>
</div>


<p align="center">
  <img src="https://github.com/aprilrhose/Movie_MCU-Dataset_GROUP8/assets/143881769/a7719536-98a9-481e-a1a4-ac719ae8da17">
</p>   
  </details>

  <details>
    <summary>𝗠𝗔𝗧𝗖𝗛 𝗙𝘂𝗻𝗰𝘁𝗶𝗼𝗻</summary>
    
>The **MATCH function** is used for finding the relative position of a specific value within a range or an array. It gives the position of the item you're looking for. The basic syntax for this function is **=MATCH(lookup_value, lookup_array, [match_type])**

>**lookup_value** is the value you want to find within the lookup_array.

>**lookup_array** is the range or array where you want to search for the lookup_value.

>**[match_type]** specifies the type of match you want to perform. For this example, the match type that was used oughts to find the exact match
<br>

<div align="center">
  <strong>The MATCH Function for this dataset was used to find the position of the films</strong>
</div>

<p align="center">
  <img src="https://github.com/aprilrhose/Movie_MCU-Dataset_GROUP8/assets/143881769/4439f788-5015-4f3b-b67a-c4f17ded30b5">
</p>
  </details>

  <details>
    <summary>𝗖𝗛𝗢𝗢𝗦𝗘 𝗙𝘂𝗻𝗰𝘁𝗶𝗼𝗻</summary>

>The **CHOOSE function** is a simple yet valuable function used to select and return a value from a list of choices based on a specified index number. It allows you to create custom lists or arrays of values and then pick a specific value from that list by providing the index number. The basic syntax for this function is **=CHOOSE(index_num, value1, value2, value3, ...)**

>**index_num** is the index number that indicates which value from the list you want to return. It can be an integer or a reference to a cell containing an integer.

>**value1, value2, value3, ...** are the values that make up the list of choices.
<br>


<div align="center">
  <strong>For this dataset, CHOOSE Function was used for allocating the Phase Titles of the MCU Films</strong>
</div>
<p align="center">
  <img src="https://github.com/aprilrhose/Movie_MCU-Dataset_GROUP8/assets/143881769/3e9b48ba-8faa-460e-83a0-f266ebefadd0">
</p>    
  </details>

  <details>
    <summary>𝗔𝗥𝗘𝗔𝗦 𝗙𝘂𝗻𝗰𝘁𝗶𝗼𝗻</summary>
    
>The **AREAS function** is a lookup and reference function that returns the number of areas in a reference. An area is a range of contiguous cells or a single cell. The basic syntax for this function is **=AREAS(reference)** where _reference_ is a reference to a cell or range of cells.

<p align="center">
  <img src="https://github.com/aprilrhose/Movie_MCU-Dataset_GROUP8/assets/143881769/3e1c6129-97ce-4e17-a7d4-3576e2252474">
</p>
  </details>
  
<div align="center">
<strong>The importance of lookup functions in Excel cannot be overstated because they streamline data retrieval and make working with large datasets more efficient. They are crucial for tasks such as searching for customer data in databases, looking up inventory or product information or retrieving historical or financial data. They allow users to automate the process of searching for and retrieving specific information, saving time and reducing the risk of errors in data-related tasks.</strong>
</div>     

</details>

  <div align="center">
    <h1>𝗖𝗛𝗔𝗥𝗧𝗦</h1>
  </div>
</div>
<img src="https://github.com/aprilrhose/Movie_MCU-Dataset_GROUP8/assets/144228573/7eb1c9c7-cc83-42ce-bffe-b966c5e6604a">

<details>
  <summary>Movie Phase</summary>   
  
>For this Movie Phase Pie Chart, you can see that the Phase 1 and Phase 2 of MCU has the same amount of movies based on the dataset that we have used. As we all know, the Phase 1 of MCU is all about “Avengers Assembled.” This is when Marvel introduced us to each of the Avengers. Phase 2, on the other hand, handles the fallout of the Avengers. It could also be noticed that Phase 3 has the most amount of movies among them all. This is also where the famous, gut-wrenching, and emotionally devastating Infinity War and Avengers: End Game belongs. Phase 4 also seconds the ranking.
</details>

<img src="https://github.com/aprilrhose/Movie_MCU-Dataset_GROUP8/assets/144228573/3cc65f3a-08c5-4624-a043-415a874946cd">

<details>
  <summary>Movie Duration</summary>   
  
>We all know that Marvel movies are famous for their always awaited post-credit scenes. What you can see here is a bar graph containing the movie duration of every Marvel film from the dataset. You can see the film titles on the horizontal axis while the vertical axis indicates the time duration in minutes. From this figure, you can perceive that Avengers: End Game has the longest duration among them all, followed by the Eternals and Spider-Man: No Way Home
</details>

<img src="https://github.com/aprilrhose/Movie_MCU-Dataset_GROUP8/assets/144228573/c9473c0f-e3d3-427a-84c3-f519f3768ffe">

<details>
  <summary>Audience Score</summary>   
  
>This graph shows the audience scores of the movies. This is measured on how much the audiences enjoyed the following films. From this graph, it could be observed that the audience score for every MCU movie has always been generally high, with most of it scoring above 80%. However, it could also be noticed that there are still variations for this set of films. For example, the highest audience score is 98% for the Shang-Chi and the Legend of the Ten Rings (2021), while the lowest got 52%, which is for Captain Marvel (2019).
></details>

<img src="https://github.com/aprilrhose/Movie_MCU-Dataset_GROUP8/assets/144228573/8b1fc936-7016-45ce-afcc-44c4e0de7e34">

<details>
  <summary>Sales</summary>   
  
>For this graph, you can see that there are obvious variations when it comes to sales. However, it is still noticeable how End Game and Infinity War got the highest sales among them all. This might be because of the huge devastation and cliff hanger the fans had felt during the end of Infinity War. Upon the release of Avengers: End Game, the fans had flocked to their own cinema house and witnessed themselves another tear-worthy goodbye. Coming second to the both movies is the crowd’s favorite, Spider-Man: No Way Home. Aside from its web story, Tom Holland, Tobey Maguire and Andrew Garfield in one film is never to be missed.
></details>

![avengers group 8](https://github.com/aprilrhose/Movie_MCU-Dataset_GROUP8/assets/143881769/20102374-ab9a-4ec2-a651-31c89e9de77d)


## **References**
<br>
- Ong, D. (2022, April, 22). Marvel Cinematic Universe Box Office Dataset. Kaggle . https://www.kaggle.com/datasets/davidgdong/marvel-cinematic-universe-box-office-dataset/data

- [Image of a Marvel Cinematic Universe Poster](https://images-wixmp-ed30a86b8c4ca887773594c2.wixmp.com/f/5298bac0-b8bf-4c80-af67-725c1272dbb0/defibp5-8019b091-dae8-426d-8276-7b6d15afcce8.jpg?token=eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJzdWIiOiJ1cm46YXBwOjdlMGQxODg5ODIyNjQzNzNhNWYwZDQxNWVhMGQyNmUwIiwiaXNzIjoidXJuOmFwcDo3ZTBkMTg8). (n.d.)

