+++
title = "dbmigrate"
+++
## cdsctl health dbmigrate

`Show DB Migrate status`

### Synopsis

`Show DB Migrate status`

```
cdsctl health dbmigrate [flags]
```

### Options

```
      --fields string   Only display specified object fields. 'empty' will display all fields, 'all' will display all object fields, 'field1,field2' to select multiple fields
      --filter string   Filter output based on conditions provided
      --format string   Output format: table|json|yaml (default "table")
  -h, --help            help for dbmigrate
  -q, --quiet           Only display object's key
```

### Options inherited from parent commands

```
  -f, --file string   set configuration file
  -k, --insecure      (SSL) This option explicitly allows curl to perform "insecure" SSL connections and transfers.
  -w, --no-warnings   do not display warnings
  -v, --verbose       verbose output
```

### SEE ALSO

* [cdsctl health](/cli/cdsctl/health/)	 - `Check CDS health`
