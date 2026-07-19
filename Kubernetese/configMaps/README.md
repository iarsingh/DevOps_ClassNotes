# ConfigMaps

Notes and a manifest demonstrating Kubernetes ConfigMaps for externalizing application
configuration.

## Contents

- `configMapsNotes` — `kubectl` commands for creating ConfigMaps both from literal key/value
  pairs (`--from-literal`) and from a properties file (`--from-file`), plus inspecting them
  with `get`/`describe`.
- `podconfigmap.yml` — A Pod manifest (`pod-configmap`, nginx) that mounts a ConfigMap
  (`dev-config1`) as a volume at `/etc/config`.
