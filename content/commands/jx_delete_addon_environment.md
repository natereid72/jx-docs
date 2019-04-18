---
date: 2019-04-18T22:47:49Z
title: "jx delete addon environment"
slug: jx_delete_addon_environment
url: /commands/jx_delete_addon_environment/
---
## jx delete addon environment

Deletes the Environment Controller 

### Synopsis

Deletes the Environment Controller

```
jx delete addon environment controller [flags]
```

### Examples

```
  # Deletes the environment controller
  jx delete addon envctl
```

### Options

```
  -h, --help             help for environment
  -p, --purge            Removes the release name from helm so it can be reused again (default true)
  -r, --release string   The chart release name (default "jxet")
```

### Options inherited from parent commands

```
  -b, --batch-mode                Runs in batch mode without prompting for user input (default true)
      --install-dependencies      Enables automatic dependencies installation when required
      --log-level string          Sets the logging level (panic, fatal, error, warning, info, debug) (default "info")
      --no-brew                   Disables brew package manager on MacOS when installing binary dependencies
      --skip-auth-secrets-merge   Skips merging the secrets from local files with the secrets from Kubernetes cluster
      --verbose                   Enables verbose output
```

### SEE ALSO

* [jx delete addon](/commands/jx_delete_addon/)	 - Deletes one or more addons

###### Auto generated by spf13/cobra on 18-Apr-2019