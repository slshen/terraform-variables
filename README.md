# terraform variables example

Example:

```
# fails
; checkov -d . --compact --check CKV_AWS_20
# passes
; checkov -d . --compact --check CKV_AWS_20 --var-file pass.tfvars
# passes
; checkov -d . --compact --check CKV_AWS_20 --var-file pass.tfvars.json
# fails
; checkov -d . --compact --check CKV_AWS_20 --var-file passvars.json
```
