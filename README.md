Repro command:

```sh
bazel run @rules_apko//:apko -- lock ./ddclient_apko_image_config.yaml
```

result:

```
WARNING: Target pattern parsing failed.
ERROR: Skipping '@rules_apko//:apko': error loading package '@@rules_apko~//': Unable to find package for @@[unknown repo 'bazel_gazelle' requested from @@rules_apko~]//:def.bzl: The repository '@@[unknown repo 'bazel_gazelle' requested from @@rules_apko~]' could not be resolved: No repository visible as '@bazel_gazelle' from repository '@@rules_apko~'.
ERROR: error loading package '@@rules_apko~//': Unable to find package for @@[unknown repo 'bazel_gazelle' requested from @@rules_apko~]//:def.bzl: The repository '@@[unknown repo 'bazel_gazelle' requested from @@rules_apko~]' could not be resolved: No repository visible as '@bazel_gazelle' from repository '@@rules_apko~'.
INFO: Elapsed time: 0.178s
INFO: 0 processes.
ERROR: Build did NOT complete successfully
ERROR: Build failed. Not running target
```
