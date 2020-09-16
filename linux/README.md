# Terraform Credential Helpers

## Linux

In Linux, the helpers get installed into `${HOME}/.terraform.d/plugins`.

They also need to be registered in `${HOME}/.terraformrc`.

```
# eg. for .terraformrc
credentials_helper "lastpass" {}
```

