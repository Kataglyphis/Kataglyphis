# Kataglyphis profile repository

Before adding a Bash or PowerShell helper, workflow, or quality check, search this
repository and `third_party/ANTfrastructure` for reusable functionality. Use or
extend the hub implementation and pass profile-specific values as arguments.
See [the hub adoption guide](third_party/ANTfrastructure/docs/adopting-in-a-new-project.md#reuse-before-adding-functionality).

The scripts under `scripts/lib/` are bootstrap copies needed before the submodule
is available. Keep them synchronized with the hub's declared templates; make
behavior changes in ANTfrastructure first. Use `scripts/renovate-local.sh` for
dependency and direct-submodule updates.
