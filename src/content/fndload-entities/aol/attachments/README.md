# Attachments

<br>

| Entity                   | Sub-entities, if any          |   #   | Download Parameters   |
| :----                    | :--------                     | :--:  | :----   |
| FND_ATTACHMENT_FUNCTIONS | FND_ATTACHMENT_BLOCKS         | 1  | APPLICATION_ SHORT_NAME      |
|                          | FND_ATTACHMENT_BLOCK_ENTITIES | 2  | FUNCTION_NAME      |
|                          | FND_DOC_CATEGORY_USAGES       | 3  | FUNCTION_TYPE      |

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
