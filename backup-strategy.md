# Backup Strategy

**Category:** engineering

**Description:** None

## Instructions

Neon auto-backups with 5-snapshot retention. identity DB is the immortal layer — never drop tables here. Ops DB can be reconstructed from identity if needed. Export memories and credentials weekly to a JSON file stored in Google Drive (will@scana.fun).
