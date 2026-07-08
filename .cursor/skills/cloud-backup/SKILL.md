---
name: cloud-backup
description: Build production-ready cloud backup applications with backup and restore workflows.
---

# Cloud Backup Skill

## When to use

Use this skill whenever the user asks to build a backup, restore, archive, or cloud storage application.

## Requirements

Always include:

- Full backup
- Incremental backup
- Snapshot versioning
- Compression before upload
- Encryption of backup files
- SHA-256 checksum verification
- Retry mechanism for failed uploads
- Backup metadata
- Restore validation
- Retention policies
- Progress reporting

## Recommended Structure

backup/
restore/
storage/
compression/
encryption/
checksum/
tests/

## Best Practices

Generate unit tests.

Use interfaces for storage providers.

Support future cloud providers.