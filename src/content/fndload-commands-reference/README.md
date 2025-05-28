# FNDLOAD Commands Reference

<br>

### Script Example
| Code   | Entity Name             | Download  | Upload  |  
| :-:    | :--------               | :----     | :----   | 
| 1      | Example     | FNDLOAD apps/password 0 Y DOWNLOAD $FND_TOP/patch/115/import/config-file.lct data-file.ldt [entity] [parameters] | FNDLOAD apps/password 0 Y UPLOAD $FND_TOP/patch/115/import/config-file.lct data-file.ldt|

<br>

<br>

## Application Object Library (AOL) Entities

<br>

### Concurrent Program Entities

| Code   | Entity Name             | Download  | Upload  |  
| :-:    | :--------               | :----     | :----   | 
| 1      | Concurrent Programs     | FNDLOAD apps/<APPS_PASSWORD> 0 Y DOWNLOAD $FND_TOP/patch/115/import/afcpprog.lct <PROGRAM_NAME>.ldt PROGRAM APPLICATION_SHORT_NAME="<APP_SHORT_NAME>" CONCURRENT_PROGRAM_NAME="<PROGRAM_NAME>" | FNDLOAD apps/<APPS_PASSWORD> 0 Y UPLOAD $FND_TOP/patch/115/import/afcpprog.lct <PROGRAM_NAME>.ldt|
| 2      | Executables             |           |         |
| 3      | Request Groups          | FNDLOAD apps/<APPS_PASSWORD> 0 Y DOWNLOAD $FND_TOP/patch/115/import/afcpreqg.lct <REQGROUP_NAME>.ldt REQUEST_GROUP REQUEST_GROUP_NAME="<GROUP_NAME>" APPLICATION_SHORT_NAME="<APP_SHORT_NAME>" | FNDLOAD apps/<APPS_PASSWORD> 0 Y UPLOAD $FND_TOP/patch/115/import/afcpreqg.lct <REQGROUP_NAME>.ldt |
| 4      | Request Sets            | FNDLOAD apps/<APPS_PASSWORD> 0 Y DOWNLOAD $FND_TOP/patch/115/import/afcprset.lct <REQSET_NAME>.ldt REQ_SET REQUEST_SET_NAME="<SET_NAME>"| FNDLOAD apps/<APPS_PASSWORD> 0 Y UPLOAD $FND_TOP/patch/115/import/afcprset.lct <REQSET_NAME>.ldt|
| 5      | Request Set Links       |           |         |

<br>

### Lookups

| Code   | Entity Name             | Download  | Upload  |  
| :-:    | :--------               | :----     | :----   | 

<br>

### Profile Options

| Code   | Entity Name             | Download  | Upload  |  
| :-:    | :--------               | :----     | :----   | 

<br>

### Flexfields

| Code   | Entity Name             | Download  | Upload  |  
| :-:    | :--------               | :----     | :----   | 

<br>

### Message Dictionary

| Code   | Entity Name             | Download  | Upload  |  
| :-:    | :--------               | :----     | :----   | 
| 1    | Message               | FNDLOAD apps/<$apps_password> 0 Y DOWNLOAD $FND_TOP/patch/115/import/afmdmsg.lct MSG_CODE_US.ldt FND_NEW_MESSAGES APPLICATION_SHORT_NAME='AR' MESSAGE_NAME=%XXEINV_ZATCA%     | FNDLOAD apps/<$apps_password> 0 Y UPLOAD $FND_TOP/patch/115/import/afmdmsg.lct MSG_CODE_US.ldt   | 



<br>

### Attachments

| Code   | Entity Name             | Download  | Upload  |  
| :-:    | :--------               | :----     | :----   | 

<br>

## Security & Access Control Entities

| Code   | Entity Name             | Download  | Upload  |  
| :-:    | :--------               | :----     | :----   | 


<br>

## Workflow & Approval Management Entities

### Workflow

| Code   | Entity Name             | Download  | Upload  |  
| :-:    | :--------               | :----     | :----   | 


### Approvals Management Engine (AME)

| Code   | Entity Name             | Download  | Upload  |  
| :-:    | :--------               | :----     | :----   | 


#### Transaction Types

| Code   | Entity Name             | Download  | Upload  |  
| :-:    | :--------               | :----     | :----   | 


#### Attributes

| Code   | Entity Name             | Download  | Upload  |  
| :-:    | :--------               | :----     | :----   | 


#### Conditions

| Code   | Entity Name             | Download  | Upload  |  
| :-:    | :--------               | :----     | :----   | 


#### Approver Groups

| Code   | Entity Name             | Download  | Upload  |  
| :-:    | :--------               | :----     | :----   | 


#### Rules

| Code   | Entity Name             | Download  | Upload  |  
| :-:    | :--------               | :----     | :----   | 


<br>

## Reporting & BI Publisher (XDO) Entities

| Code   | Entity Name             | Download  | Upload  |  
| :-:    | :--------               | :----     | :----   | 


<br>

## SOA, Integrations & Web ADI Entities

### Integrated SOA Gateway (ISG)

| Code   | Entity Name             | Download  | Upload  |  
| :-:    | :--------               | :----     | :----   | 


### Application Desktop Integrator (Web ADI)

| Code   | Entity Name             | Download  | Upload  |  
| :-:    | :--------               | :----     | :----   | 


### Alerts Entity

| Code   | Entity Name             | Download  | Upload  |
| :-:    | :--------               | :----     | :----   |   
| 1      |Alert                    |FNDLOAD apps/<$apps_password> 0 Y DOWNLOAD $ALR_TOP/patch/115/import/alr.lct <ALERT_NAME>.ldt ALERT ALERT_NAME="<ALERT_NAME>"|FNDLOAD apps/<$apps_password> 0 Y UPLOAD $ALR_TOP/patch/115/import/alr.lct <ALERT_NAME>.ldt| 


<br>

## Forms Personalization Entities

| Code   | Entity Name             | Download  | Upload  |  
| :-:    | :--------               | :----     | :----   | 



<br>
