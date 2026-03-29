Title: Verify Search event functionality for unlogged user  
Precondition: User is unlogged  
Steps:  
| Step | Action | Data | Expected Result |
| :--- | :--- | :--- | :--- |
| 1    | Press on a events key in site header     |      |User was redirected to events section of website                 |
| 2    | Press on a search events item in header     |      |Active search form, which accepts user input                 |
| 3    | Input already existing event name in Latin   |Some Event      |Website back specific event, that have that name                 |
| 4    | Input already existing event name in Numeric format  |123123      |Website back specific event, that have that name                 |
| 5    | Input already existing event name in Cyrillic   |енрн5ор6нг7ол6      |Website back specific event, that have that name                 |


Actual result: Step 3 and 5 do not respond Expected Results, Step 4 Actual Result corresponds Expected Results  
Status: Fail
