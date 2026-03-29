Title: Verify event filtering for unlogged user  
Precondition: User is unlogged  
Steps:  

| Step | Action | Data | Expected Result |
| :--- | :--- | :--- | :--- |
| 1    | Press on a filter status item in header     |      |Lists of active checkbox                  |
| 2    | Press on checkbox "Any status" from status listbox    |      |Website back all events, that have any status                 |
| 3    | Press on checkbox "Open" from status listbox    |      |Website back all events, that have status "Open"                |
| 4    | Press on checkbox "Closed" from status listbox    |      |Website back all events, that have status "Closed"                 |


Actual result: On step 2 website don't back the closed event with name "Test2", Actual Result does not match Expected Result  
On steps 3 and 4  Actual Result match Expected Result

Status: Fail
