---
id: cscli_hubtest_create
title: cscli hubtest create
---
## cscli hubtest create

create [test_name]

```
cscli hubtest create [flags]
```

### Examples

```
cscli hubtest create my-awesome-test --type syslog
cscli hubtest create my-nginx-custom-test --type nginx
cscli hubtest create my-scenario-test --parsers crowdsecurity/nginx --scenarios crowdsecurity/http-probing
```

### Options

```
  -h, --help                    help for create
      --ignore-parsers          Don't run test on parsers
  -p, --parsers strings         Parsers to add to test
      --postoverflows strings   Postoverflows to add to test
  -s, --scenarios strings       Scenarios to add to test
  -t, --type string             Log type of the test
```

### Options inherited from parent commands

```
      --color string      Output color: yes, no, auto. (default "auto")
  -c, --config string     path to crowdsec config file (default "/etc/crowdsec/config.yaml")
      --crowdsec string   Path to crowdsec (default "crowdsec")
      --cscli string      Path to cscli (default "cscli")
      --debug             Set logging to debug.
      --error             Set logging to error.
      --hub string        Path to hub folder (default ".")
      --info              Set logging to info.
  -o, --output string     Output format: human, json, raw.
      --trace             Set logging to trace.
      --warning           Set logging to warning.
```

### SEE ALSO

* [cscli hubtest](/cscli/cscli_hubtest.md)	 - Run functional tests on hub configurations

