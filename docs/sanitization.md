# Public export notes

The workflow files are sanitized copies of the supplied n8n exports. The originals remain unchanged and are not included in this repository.

## Removed or replaced

- Removed credential references, including account labels and IDs.
- Removed original workflow/version/instance metadata and chat webhook identifiers.
- Regenerated node and condition UUIDs for these public copies.
- Replaced the private Google spreadsheet locator and cached links with placeholders.
- Replaced the Pinecone index and namespace with shared setup placeholders.
- Removed pinned-data fields and retained inactive workflow status.
- Covered execution IDs and the partial chat session ID in screenshot copies. Original filenames and visible workflow/output content are preserved.

Prompts, expressions, node types/versions, connections, model selection and behavioural settings are preserved. Column-schema identifiers and player-identity field names are functional configuration, not private account identifiers.

## Verification scope

Both public exports were parsed as JSON and their connection targets were checked against node names. The copies were checked for the original credential references, private resource locators and workflow/node identifiers. Screenshot redactions were inspected visually.

These packaging checks are not an n8n import test or a rerun against live services. The demonstrated execution evidence comes from the supplied screenshots. A user must configure their own accounts and run the manual checks in the README.
