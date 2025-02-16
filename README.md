# Interview Preparation

[C#.NET](#C#.NET)

[Collections & Generics](#Collections---Generics)

[LINQ](#LINQ)

[SQL & DB](#SQL---DB)

[EF](#EF)

[Angular](#Angular)

[Azure](#Azure)

[SOLID Principles](#SOLID-Principles)

[LLD](#LLD)

[HLD/System Design](#hld---system-design)

[MicroServices](#MicroServices)

[DevOps - Docker, k8s](#devOps---docker-k8s) 


*GitHub HELP on Anchors/Markdown :- *
* https://stackoverflow.com/questions/76402528/github-how-to-add-links-to-sections-of-readme-md
* https://gist.github.com/rachelhyman/b1f109155c9dafffe618#file-gistfile1-md
* https://github.com/fefong/markdown_readme?tab=readme-ov-file#getting-started-with-markdown
* https://stackoverflow.com/questions/27981247/github-markdown-same-page-link/45508928#45508928
      
-------------------------------------------------------------------------------------
## C#.NET
## Collections - Generics
## LINQ
-------------------------------------------------------------------------------------
## SQL - DB

### Practice - LeetCode-Top_50_SQL
Reference:- https://github.com/Raj-Kumar-Arora/SQL-LeetCode-Top_50_SQL

|#| KEYWORD | DETAILS |
|---|---|---|
|1| IS NULL | ![image](https://github.com/user-attachments/assets/1facfcb7-7ca5-497e-9e90-b5163429e86b) ![image](https://github.com/user-attachments/assets/8ef24014-c5f8-4f50-a59f-dc99125ffcc9)  ![image](https://github.com/user-attachments/assets/822554e2-1b7b-40ed-9588-61efb5600bb1)   ![image](https://github.com/user-attachments/assets/3ea99ce5-7725-44ed-89ec-867e6ee181e3) |
|2| LEN () | ![image](https://github.com/user-attachments/assets/96fc2ab3-c7fb-4609-abf5-dd8111fe7432)|
|3| CAST | ![image](https://github.com/user-attachments/assets/b3f20b1a-abcc-44f3-9aa0-0e085aabeaed) ![image](https://github.com/user-attachments/assets/cdaeec36-cc81-43ae-96f6-40d002c01fc4) |
|4| FORMAT |![image](https://github.com/user-attachments/assets/a247bc43-6e90-42a6-818f-bd602ab1867d) |
|5| STRING_AGG ()| To convert row/record values in a single string value  ![image](https://github.com/user-attachments/assets/964d5392-640b-4ced-96f0-3cf8877cc8ab)  
| |  | https://www.sqlshack.com/string_agg-function-in-sql/ https://learn.microsoft.com/en-us/sql/t-sql/functions/string-agg-transact-sql?view=sql-server-ver16  ![image](https://github.com/user-attachments/assets/e4f0f700-77b6-4d18-a814-441aee07dd45) |
|6| UPPER, LOWER, LEFT, RIGHT | String manipulation ![image](https://github.com/user-attachments/assets/4d12c398-8b07-4cd7-8774-6d4d6c721a05)|
|7| BETWEEN | Can be used with dates as well |
| | | ![image](https://github.com/user-attachments/assets/7dbb0db9-7b84-4e0b-a10d-d7430c3e5229) |
|8| DateAdd () | ![image](https://github.com/user-attachments/assets/bdbf4f70-9cbd-40b7-b712-10584a9ddc2f)  |
| | | ![image](https://github.com/user-attachments/assets/61b48ca4-af21-4da9-a910-1d1cddbeb208) |
| | |   ![image](https://github.com/user-attachments/assets/23561275-ea49-4151-be17-dd68b6c7c2e9) |
|9| DatePart () |![image](https://github.com/user-attachments/assets/1a924817-f822-48de-a8da-65461d8119e5)|
|10| Count, AVG, Sum () | ![image](https://github.com/user-attachments/assets/b99c3185-c720-4558-b4ba-4e5e44559689) ![image](https://github.com/user-attachments/assets/1f218942-f692-4a6a-9d93-10c3600c4294) |
|11| Min/Max () | ![image](https://github.com/user-attachments/assets/d3d0dcd8-891e-4ccd-83a8-d4cefc4dd921) ![image](https://github.com/user-attachments/assets/44d0da05-4db4-478a-96c0-1a8f81544b4b)    |
|12| CASE WHEN |If-Else like in sql ![image](https://github.com/user-attachments/assets/b15e412c-a0be-4bd1-b117-ea2bfad84a1f)|
|13| Union/UnionAll | ![image](https://github.com/user-attachments/assets/c82809f5-9946-4764-9047-05581328917c) |
|14| Having | ![image](https://github.com/user-attachments/assets/d4c5e547-f602-400b-8f31-19d9b5265826)  |
|15| Round ()| ![image](https://github.com/user-attachments/assets/28077a20-45f5-412a-b994-d7f6f8345128) |
|16| LEAD/LAG () | https://www.geeksforgeeks.org/mysql-lead-and-lag-function/  |
| |  | ![image](https://github.com/user-attachments/assets/8feb896d-0202-4f4d-948d-7a20c15972c5)  | 
|17| GROUP BY | Mostly all coln's that are put in GROUP BY are also included in SELECT coln's ![image](https://github.com/user-attachments/assets/d656ec87-94e2-4272-9144-fc130a7e8957) |
|18| JOINS - All Types | https://builtin.com/articles/sql-merge-two-tables | 
|  | CROSS JOIN | ![image](https://github.com/user-attachments/assets/79f67d72-7b80-4637-b66c-620beed511bd) |
|19| CTE | Common Table Expresssions https://www.geeksforgeeks.org/cte-in-sql/ | 
|20| WINDOWS FUNCTIONS | https://www.geeksforgeeks.org/window-functions-in-sql/ |
|21| Declaring Variables | ![image](https://github.com/user-attachments/assets/f5f7648a-b37e-4778-b67a-f779afe880a4) | 
|22| PERCENTAGE | ![image](https://github.com/user-attachments/assets/f5f7648a-b37e-4778-b67a-f779afe880a4) | 
|23| ALTERNATIVE TO LIMIT/OFFSET | https://www.geeksforgeeks.org/sql-limit-clause/ |
|  | | ![image](https://github.com/user-attachments/assets/27a67098-1c16-4d11-966d-8c7c90635475) |
|24| TIP | To convert an int value to float, no need to use CAST()/FORMAT(); just multiple/add that no by 1.0 |


-------------------------------------------------------------------------------------
## EF
## Angular
## Azure
## SOLID Principles
## LLD
## HLD - System Design
## MicroServices
## DevOps - Docker k8s
