# FNDLOAD Temporary Staging Tables
Here is a list of FNDLOAD staging tables, along with their descriptions. These tables are primarily used during FNDLOAD upload operations to hold temporarily and process data before it is committed to the Oracle AOL base tables:

| Code   | Staging Table                  | Description      | Usage   | 
| :-:     | :--------                     | :----            | :----   | 
| 1    | FND_SEED_STAGE_CONFIG            | Stores configuration metadata extracted from the .lct (Loader Control) file. It includes definitions of entities, attribute mappings, and their relationships.| Used to interpret and control how data from .ldt is applied to the base AOL tables. |
| 2    | FND_SEED_STAGE_ENTITY            | Contains the data extracted from the .ldt (Loader Data) file, including the entity and attribute values to be loaded. | Temporary storage is used for validation before insert or update operations are applied to the AOL base tables.  |
| 3    | FND_SEED_STAGE_CONFIG_DEBUG      | Debug version of FND_SEED_STAGE_CONFIG, which includes extended metadata and configuration diagnostics. | Assists developers in identifying structural or mapping errors during unsuccessful uploads.  |
| 4    | FND_SEED_STAGE_ENTITY_DEBUG      | Here is a debug version of the FND_SEED_STAGE_ENTITY, which includes more detailed row-level data to assist with troubleshooting. | Used to inspect and debug invalid or inconsistent entity data during FNDLOAD operations. |
| 5    | FND_SEED_STAGE_LOG (if enabled)  |            |  |
| 6    | FND_SEED_STAGE_UTIL              |            |  |

