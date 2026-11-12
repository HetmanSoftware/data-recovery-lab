# Hetman Software Data Recovery Lab

Hetman Software Data Recovery Lab is a public collection of real-world recovery experiments, RAID and NAS failure scenarios, filesystem investigations, virtualization cases, encryption-related recovery tests, and cloud-storage research.

## Goals

- document reproducible storage failure scenarios;
- record the on-disk evidence observed during analysis;
- compare automatic and manual reconstruction workflows;
- preserve screenshots, configuration notes, and recovery results;
- publish technically useful case studies for engineers, administrators, and data-recovery specialists.

## Repository structure

```text
data-recovery-lab/
├── README.md
└── experiments/
    └── synology-ds409-raid1-to-raid5-migration-failure/
        ├── README.md
        └── images/
```

## Published experiments

### Synology / NAS

- [Synology DS409 RAID1 to RAID5 migration interrupted at 29.55%: what survived after losing an original disk?](experiments/synology-ds409-raid1-to-raid5-migration-failure/README.md)

### VeraCrypt / encrypted storage

- [VeraCrypt file containers, hidden volumes, and deleted encrypted partitions](experiments/veracrypt-containers-hidden-volumes-deleted-partitions/README.md)

### NTFS / EFS encrypted files

- [How to Recover Deleted EFS-Encrypted Files from an NTFS Drive](experiments/recover-deleted-efs-files-ntfs/README.md)

### BitLocker / encrypted storage

- [Recovering Deleted Files from BitLocker-Encrypted Drives: Windows 11, HDD, and USB](experiments/bitlocker-system-hdd-usb-data-recovery/README.md)

## Planned categories

- Synology NAS
- QNAP NAS
- TrueNAS / OpenZFS
- Linux MD RAID and LVM
- Proxmox VE / VMware / Hyper-V
- Encrypted storage (LUKS, BitLocker, VeraCrypt)
- Cloud block and file storage
- Filesystem internals and recovery edge cases

## Notes

All recovery experiments are documented from a research perspective. Unless stated otherwise, reconstruction is performed virtually and read-only.