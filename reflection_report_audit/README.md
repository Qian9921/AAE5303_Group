# Reflection Report Audit

This folder contains a repository-level audit of reflection report submissions listed in the group information files.

Files:

- `reflection_report_status.md` - human-readable summary and detailed member table.
- `reflection_report_status.csv` - member-level CSV with status, links, checked repository, top-level contents, detected report files, and notes.
- `reflection_repository_inventory.csv` - unique GitHub repository inventory for reflection-report targets.

Status rules:

- `Submitted - GitHub link supplied`: the group file contains a GitHub reflection link and the target repository was accessible with visible content through the GitHub API.
- `Link supplied - external non-GitHub link`: a reflection link exists, but it is outside GitHub, so repository contents were not inspected.
- `Missing - no reflection link in group info file`: no reflection-report link was found in that member entry.
- `Link supplied - GitHub repository empty/no contents found`: a GitHub URL was present, but the repository had no visible contents at inspection time.
- `Link supplied - GitHub target not accessible`: a GitHub URL was present, but the repository or target could not be inspected.
