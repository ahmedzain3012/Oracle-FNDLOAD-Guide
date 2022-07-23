# Oracle FNDLOAD Loader

The Generic Loader (FNDLOAD) is a concurrent program that can move Oracle E-Business Suite data between database and text file representations. The loader reads a configuration file to determine what data to access. For information on specific configuration files consult the Open Interfaces Guide for your product group. The following sections describe the operation of the Generic Loader.

<br>

## FNDLOAD Executable Syntax 

The Generic Loader is a concurrent program named FNDLOAD. The concurrent executable takes the following parameters:

> **FNDLOAD {apps/APPS_PASSWORD} {0 Y} {mode} {configfile} {datafile} {entity} [optional {param} {param}]**

<br>

| Code      | Variable                   | Description                   |
| :-:       | :--------                  | :--------------------------   |
| 1         | {apps/APPS_PASSWORD}       | The APPS schema and password       |
| 2         | {0 Y}                      | Concurrent program flags       |
| 3         | {mode}                     | UPLOAD or DOWNLOAD <br> - **UPLOAD** causes the datafile to be uploaded to the database. <br> - **DOWNLOAD** causes the loader to fetch rows and write them to the datafile.|
| 4         | {configfile}               | The configuration file to use (usually with a suffix of .lct, but not enforced or supplied by the loader).       |
| 5         | {datafile}                 | The data file to write (usually with a suffix of .ldt, but not enforced or supplied by the loader). If the data file already exists, it will be overwritten.       |
| 6         | {entity}                   | The entity(ies) to upload or download. When uploading, you should always upload all entities, so specify a "-" to upload all entities.       |
| 7         | [optional {param} {param}] | Zero or more additional parameters are used to provide bind values in the access SQL (both UPLOAD and DOWNLOAD). Each parameter is in the form NAME=VALUE. NAME should not conflict with an attribute name for the entities being loaded.       |

<br>

### Example

###### Download
```
FNDLOAD
```

###### Upload
```
FNDLOAD
```


<br>

## **FNDLOAD Entities**

- **<a href="https://github.com/demasy/Oracle-FNDLOAD-Loader#oracle-aol-configuration">Oracle AOL Configuration</a>**
  * Concurrent Programs
  * Request Groups
  * Lookups
    * Lookup Types
    * Lookup Values
  * Profile Options
    * Profile options definition
    * profile option values
  * Flexfields setup
    * Key flexfields
    * Descriptive flexfields 
    * Value sets
  * Attachments setup
  * Messages Dictionary
  * Security Information
    * Menu
    * Function
    * Form
    * Entry
- **Alerts**
- **Approvals Management Engine (AME)**
  * Transaction Types
  * Attributes
  * Attribute Definitions
  * Attribute Usages
  * Conditions
  * Approver Groups
    * Approver Groups Definitions
    * Approval Group Configuration
  * Rules
    * Rule Definitions
    * Rule Usages
- **XDO**
  * Data Definitions
  * XML Template
- **Generic**
  * Responsibility
  * Users
  * Request Set
  * Request Set Link
  * Workflow
  * SOA Gateway

<br>

### Oracle AOL Configuration 

| Code   | Entity Name                           | Configuration File   |
| :-     | :--------                             | :----   |
| 1.1    | <a href="#">Concurrent Programs</a>                  | afsload.lct|
| 1.2    | <a href="#">Request Groups</a>                  | afsload.lct|
| 1.3    | <a href="#">Lookup: Lookup Types</a>                  | afsload.lct|
| 1.4    | <a href="#">Lookup: Lookup Values</a>                  | afsload.lct|
| 1.5    | <a href="#">Profile Option: Definition</a>                  | afsload.lct|
| 1.6    | <a href="#">Profile Option: Values</a>                  | afsload.lct|
| 1.7    | <a href="#">Flexfield: Key flexfields</a>                  | afsload.lct|
| 1.8    | <a href="#">Flexfield: Descriptive flexfields</a>                  | afsload.lct|
| 1.9    | <a href="#">Flexfield: Value sets</a>                  | afsload.lct|
| 1.10   | <a href="#">Attachments</a>                  | afsload.lct|
| 1.11   | <a href="#">Messages</a>                  | afsload.lct|
| 1.12   | <a href="#">Security: Menu</a>                  | afsload.lct|
| 1.13   | <a href="#">Security: Function</a>                  | afsload.lct|
| 1.14   | <a href="#">Security: Form</a>                  | afsload.lct|
| 1.15   | <a href="#">Security: Entry</a>                  | afsload.lct|

<br>


## Contributors

| Author | GitHub & LinkedIn account |
| :-  | :---- |
| Ahmed El-Demasy (Original Author) | <a href="https://github.com/demasy">Github</a> & <a href="https://www.linkedin.com/in/demasy">LinkedIn</a> |
<br>

 ### Contributing to the Oracle FNDLOAD scripts
We welcome you to join and contribute to the Oracle FNDLOAD Scripts. If you are interested in helping please don’t hesitate to contact on an e-mail: founder@egyptianprogrammers.com

<br>

###### Suggestions & Issues
> If you find any issue or have a great idea in mind please create an issue on <a href="https://github.com/demasy/Oracle-FNDLOAD-Loader/issues">GitHub</a>.
