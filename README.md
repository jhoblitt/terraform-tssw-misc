deployment for miscellaneous TSSW aws resources
===

[![Build
Status](https://travis-ci.org/lsst-sqre/terraform-tssw-misc.png)](https://travis-ci.org/lsst-sqre/terraform-tssw-misc)

Usage
---

See [terraform-doc output](tf/README.md) for available arguments and
attributes.

`pre-commit` hooks
---

```bash
go get github.com/segmentio/terraform-docs
pip install --user pre-commit
pre-commit install

# manual run
pre-commit run -a
```

See also
---

* [`terraform`](https://www.terraform.io/)
* [`terragrunt`](https://github.com/gruntwork-io/terragrunt)
* [`terraform-docs`](https://github.com/segmentio/terraform-docs)
* [`pre-commit`](https://github.com/pre-commit/pre-commit)
* [`pre-commit-terraform`](https://github.com/antonbabenko/pre-commit-terraform)
