# maxsat-tools
Some tools to script {sat, maxsat, asp} solver evaluation e.g. on maxsat competition instances

## Scripts

### parse_max_sat.py

Call

```
python parse_max_sat.py $evaluation.html src=$source_folder dst=$destination_folder
```

Parses the `$evaluation.html`, which is includes the table for 2015s results of a maxsat track (e.g. maxsat.ia.udl.cat/detailed/complete-ms-crafted-table.html). In the script, you can set a filter on relevant solver and execution time. The script then copies the instances matching this criteria from the `$source_folder` to the `$destination_folder`.