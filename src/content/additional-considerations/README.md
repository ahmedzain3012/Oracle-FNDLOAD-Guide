# Additional Considerations

<br>

## Configuration of the Environment for Multilingual Support

<br>

### Verify NLS_LANG in SQL Session

``` sql
SELECT DECODE (PARAMETER,
               'NLS_LANGUAGE', 'LANGUAGE',
               'NLS_TERRITORY', 'TERRITORY',
               'NLS_CHARACTERSET', 'CHARACTER SET')    ATTRIBUTES,
       VALUE
  FROM NLS_DATABASE_PARAMETERS
 WHERE PARAMETER IN ('NLS_LANGUAGE', 'NLS_TERRITORY', 'NLS_CHARACTERSET');
```

``` sql
SELECT *
  FROM nls_session_parameters
 WHERE parameter LIKE 'NLS_%';
```

```sql
SELECT NLS_LANGUAGE, NLS_TERRITORY, NLS_CODESET
  FROM FND_LANGUAGES
 WHERE 1 - 1 AND NLS_TERRITORY = 'EGYPT'
```

<br>

### Set NLS_LANG Based on Database Character Set

##### Set NLS_LANG Syntax
``` bash
EXPORT NLS_LANG=<language>_<territory>.<character set>
```

##### For Linux/Unix:

``` bash
export NLS_LANG="ARABIC_UNITED ARAB EMIRATES.AR8MSWIN1256"
```

##### For Windows (Command Prompt - CMD):

``` cmd
set NLS_LANG=ARABIC_UNITED ARAB EMIRATES.AR8MSWIN1256
```

### Reset to Default NLS Settings (If Needed)

##### For Linux/Unix:

``` bash
unset NLS_LANG
```
