# scripts/_archive

One-shot scripts that have already executed against their target state and are preserved for git-history reference only. Do not invoke; the contracts they encoded (env vars, target paths, expected dependencies) may no longer hold.

Each archived script carries a single-line banner after the shebang naming the archival date and reason. New archives append a row to the table below.

## Inventory

| Script | Archived | Reason |
|---|---|---|
| `migrate-library.ts` | 2026-05-26 | One-shot migration from local `~/.vade/library/` to the cloud-backed library; already run in production. |
