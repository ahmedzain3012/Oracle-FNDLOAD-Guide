# Executable

| Entity      | Sub-entities, if any |  #   | Download Parameters   |
| :----       | :--------            | :--: | :----   |
| EXECUTABLE  |          -           | 1    |EXECUTABLE_NAME    |


## Commands

### Download 

```
FNDLOAD apps/<$apps_password> 0 Y DOWNLOAD $FND_TOP/patch/115/import/afcpprog.lct exe_XXDL_EXECUTABLE_NAME_us.ldt EXECUTABLE EXECUTABLE_NAME="XXDL_EXECUTABLE_NAME" APPLICATION_SHORT_NAME="XXDL"
```

### Upload

```
FNDLOAD apps/<$apps_password> 0 Y UPLOAD $FND_TOP/patch/115/import/afcpprog.lct exe_XXDL_EXECUTABLE_NAME_us.ldt
```

<br>
