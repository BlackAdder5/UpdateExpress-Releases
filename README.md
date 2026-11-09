# Update Express Releases

Public update channel for **Update Express** (MicroSystems).

The private source repository is separate. Customer computers read only this public channel.

## latest.json

Clients check:

`https://raw.githubusercontent.com/BlackAdder5/UpdateExpress-Releases/main/latest.json`

| Field | Purpose |
|---|---|
| `version` | Newest available application version |
| `publishedAt` | UTC publish time |
| `releaseNotes` | Short notes shown to the technician |
| `downloadUrl` | HTTPS link opened when the user chooses download |
| `sha256` | Reserved for Phase 2 integrity checks |

Phase 1 only **checks** for updates. Installation/replacement is not performed by the client yet.
