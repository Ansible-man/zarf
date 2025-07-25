---
title: zarf package
description: Zarf CLI command reference for <code>zarf package</code>.
tableOfContents: false
---

<!-- Page generated by Zarf; DO NOT EDIT -->

## zarf package

Zarf package commands for creating, deploying, and inspecting packages

### Options

```
  -h, --help                  help for package
  -k, --key string            Path to public key file for validating signed packages
      --oci-concurrency int   Number of concurrent layer operations when pulling or pushing images or packages to/from OCI registries. (default 6)
```

### Options inherited from parent commands

```
  -a, --architecture string        Architecture for OCI images and Zarf packages
      --insecure-skip-tls-verify   Skip checking server's certificate for validity. This flag should only be used if you have a specific reason and accept the reduced security posture.
      --log-format string          Select a logging format. Defaults to 'console'. Valid options are: 'console', 'json', 'dev'. (default "console")
  -l, --log-level string           Log level when running Zarf. Valid options are: warn, info, debug, trace (default "info")
      --no-color                   Disable terminal color codes in logging and stdout prints.
      --plain-http                 Force the connections over HTTP instead of HTTPS. This flag should only be used if you have a specific reason and accept the reduced security posture.
      --tmpdir string              Specify the temporary directory to use for intermediate files
      --zarf-cache string          Specify the location of the Zarf cache directory (default "~/.zarf-cache")
```

### SEE ALSO

* [zarf](/commands/zarf/)	 - The Airgap Native Packager Manager for Kubernetes
* [zarf package create](/commands/zarf_package_create/)	 - Creates a Zarf package from a given directory or the current directory
* [zarf package deploy](/commands/zarf_package_deploy/)	 - Deploys a Zarf package from a local file or URL (runs offline)
* [zarf package inspect](/commands/zarf_package_inspect/)	 - Displays the definition of a Zarf package (runs offline)
* [zarf package list](/commands/zarf_package_list/)	 - Lists out all of the packages that have been deployed to the cluster (runs offline)
* [zarf package mirror-resources](/commands/zarf_package_mirror-resources/)	 - Mirrors a Zarf package's internal resources to specified image registries and git repositories
* [zarf package publish](/commands/zarf_package_publish/)	 - Publishes a Zarf package to a remote registry
* [zarf package pull](/commands/zarf_package_pull/)	 - Pulls a Zarf package from a remote registry and save to the local file system
* [zarf package remove](/commands/zarf_package_remove/)	 - Removes a Zarf package that has been deployed already (runs offline)

