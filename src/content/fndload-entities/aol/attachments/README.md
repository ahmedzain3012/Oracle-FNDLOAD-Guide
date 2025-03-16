# Attachments

<br>

| Entity      | Sub-entities, if any                           | Download Parameters   |
| :----      | :--------                         | :----   |
| FND_ATTACHMENT_ FUNCTIONS         | FND_ATTACHMENT_BLOCKS                   | APPLICATION_ SHORT_NAME      |

<br>

## Commands

### Download 

```
FNDLOAD apps/<$apps_password> 0 Y DOWNLOAD $FND_TOP/patch/115/import/afftalrt.lct attach_XXDL_ATTACHMENT_us.ldt ATTACHMENT DOCUMENT_NAME="XXDL_ATTACHMENT"
```

### Upload

```
FNDLOAD apps/<$apps_password> 0 Y UPLOAD $FND_TOP/patch/115/import/afftalrt.lct attach_XXDL_ATTACHMENT_us.ldt
```

<br>
