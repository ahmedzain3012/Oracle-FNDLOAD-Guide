
# Forms Personalizations

  

### Personalizations

  
| Entity                | Sub-entities, if any |  #   | Download Parameters   |
| :----                 | :--------            | :--: | :----                 |
| PERSONALIZATION       |                      | 1    |                       |


  

<br>

  

### Personalizations Commands

  

###### Download

  

```

FNDLOAD apps/<$apps_password> 0 Y DOWNLOAD $FND_TOP/patch/115/import/affrmcus.lct per_XXDL_per_NAME_us.ldt FND_FORM_CUSTOM_RULES FORM_NAME="XXDL_ALERT_NAME"

```

  

###### Upload

  

```

FNDLOAD apps/<$apps_password> 0 Y UPLOAD $FND_TOP/patch/115/import/affrmcus.lct per_XXDL_per_NAME_us.ldt

```

  

<br>