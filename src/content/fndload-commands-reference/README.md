# FNDLOAD Commands Reference

<br>

## Script Example
| Code   | Entity Name             | Download  | Upload  |  
| :-:    | :--------               | :----     | :----   | 
| 1      | Example     | FNDLOAD apps/password 0 Y DOWNLOAD $FND_TOP/patch/115/import/config-file.lct data-file.ldt [entity] [parameters] | FNDLOAD apps/password 0 Y UPLOAD $FND_TOP/patch/115/import/config-file.lct data-file.ldt|

<br>

# Concurrent Program Entities

| Code   | Entity Name             | Download  | Upload  |  
| :-:    | :--------               | :----     | :----   | 
| 1      | Concurrent Programs     | FNDLOAD apps/<APPS_PASSWORD> 0 Y DOWNLOAD $FND_TOP/patch/115/import/afcpprog.lct <Program>.ldt PROGRAM APPLICATION_SHORT_NAME="<APP_SHORT_NAME>" CONCURRENT_PROGRAM_NAME="<PROGRAM_NAME>" | FNDLOAD apps/<APPS_PASSWORD> 0 Y UPLOAD $FND_TOP/patch/115/import/afcpprog.lct <Program>.ldt|
| 2      | Executables             |           |         |
| 3      | Request Groups          | FNDLOAD apps/<APPS_PASSWORD> 0 Y DOWNLOAD $FND_TOP/patch/115/import/afcpreqg.lct <ReqGroup>.ldt REQUEST_GROUP REQUEST_GROUP_NAME="<GROUP_NAME>" APPLICATION_SHORT_NAME="<APP_SHORT_NAME>" | FNDLOAD apps/<APPS_PASSWORD> 0 Y UPLOAD $FND_TOP/patch/115/import/afcpreqg.lct <ReqGroup>.ldt |
| 4      | Request Sets            |           |         |
| 5      | Request Set Links       |           |         |
