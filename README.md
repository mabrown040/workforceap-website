# WorkforceAP Website

Squarespace template files, custom scripts, and automated backups for the WorkforceAP site (whale-yellow-72j5).

## Branch Strategy

| Branch | Purpose |
|--------|---------|
| `main` | Production — protected, requires 1 approval |
| `feature/*` | Feature branches — open write access (Sentinel) |
| `backup/YYYY-MM-DD` | Automated daily backup snapshots |

## Structure

```
/
├── templates/       # Squarespace template files synced from site
├── assets/          # Static assets (images, scripts, styles)
├── scripts/         # Automation and backup scripts
└── docs/            # Documentation and changelogs
```

## Automated Backups

Sentinel (monitor agent) has write access to feature branches and runs daily backups.

## Squarespace Connection

- **Repo URL:** https://github.com/mabrown040/workforceap-website
- **Branch:** main
- **Connected via:** GitHub Personal Access Token (repo scope)
