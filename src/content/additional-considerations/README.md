# Additional Considerations

<br>

## Translations




<br>

### Verify NLS_LANG in SQL Session

``` sql
SELECT *
  FROM nls_session_parameters
 WHERE parameter LIKE 'NLS_%';
```

### For Linux/Unix:

``` bash
export NLS_LANG="ARABIC_UNITED ARAB EMIRATES.AR8MSWIN1256"
```

### For Windows (Command Prompt - CMD):

``` cmd
set NLS_LANG=ARABIC_UNITED ARAB EMIRATES.AR8MSWIN1256
```
