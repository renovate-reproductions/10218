# Current behavior

Finds no updates for `gitlab.com/adamsteinbok1/renovate/go-demo-module` due to detecting it as a submodule (instead of a Gitlab subgroup) and expecting version tags to be of the form `go-demo-module/vX.Y.Z`.

# Expected behavior

Detects update from `v0.1.0` to `v0.2.0` based on the `v0.2.0` tag.
