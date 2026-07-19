# Persistent Volumes

Manifests demonstrating Kubernetes storage: static PersistentVolumes/Claims, a dynamically
provisioned claim, and mounting a claim into a Pod.

## Contents

- `pv.yml` — A manual/static `PersistentVolume` (`block-pv`, 1Gi, `manual` storage class).
- `pvc.yml` — A `PersistentVolumeClaim` bound against the manual storage class.
- `dynamic-pvc.yml` — A `PersistentVolumeClaim` relying on dynamic provisioning
  (`ReadWriteOnce`).
- `pod-pvc.yml` — A Pod (`pod-pvc`, nginx) that mounts a PVC as its storage.
- `VolumeDemo` — Supplementary notes walking through the static PV/PVC demo.
