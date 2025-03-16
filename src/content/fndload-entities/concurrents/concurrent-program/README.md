# Concurrent Program

| Entity      | Sub-entities, if any |  #   | Download Parameters   |
| :----       | :--------            | :--: | :----   |
| PROGRAM     | INCOMPATIBILITY      | 1    |CONCURRENT_PROGRAM_NAME    |
|             |                      | 2    | APPLICATION_SHORT_NAME    |

<br>

## Commands

### Download 

```
FNDLOAD apps/<$apps_password> O Y DOWNLOAD $FND_TOP/patch/115/import/afcpprog.lct prog_XXDL_CONCURRENT_PROGRAM.ldt PROGRAM APPLICATION_SHORT_NAME="XXDL" CONCURRENT_PROGRAM_NAME="XXDL_CONCURRENT_PROGRAM"
```

### Upload

```
FNDLOAD apps/<$apps_password> 0 Y UPLOAD $FND_TOP/patch/115/import/afcpprog.lct prog_XXDL_CONCURRENT_PROGRAM.ldt - WARNING=YES UPLOAD_MODE=REPLACE CUSTOM_MODE=FORCE
```

<br>
