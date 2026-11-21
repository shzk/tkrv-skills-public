# Release TKRV Skills

This repository owns the source of skills listed in its README. Before publishing, review source files, documentation, and release assets for internal references and confirm the rights to distribute them. Keep private setup details in the consuming team's own tooling records.

1. Change the owning files under `skills/<name>/`. Run the skill validator, verify the references and metadata, and exercise a bounded example suitable for the change. Preserve provenance and license terms when adapting someone else's work.
2. Review the diff before merging. Choose a new `vMAJOR.MINOR.PATCH` collection tag. In GitHub Releases, describe what changed for each affected skill and any compatibility or upgrade steps. Tag the reviewed commit on `main`.
3. Package each published skill from the tagged source as a ZIP rooted at its skill folder. Confirm that archive entries match the tagged files. Verify the release tag, assets, and notes after publishing.
4. If installation is in scope, update the authorized Work and Codex copies from the tagged files. Verify availability and invocation separately where possible. Record what was checked and the release link in your team's tooling catalog, if it maintains one.

Publishing a release and updating an installation are separate operations. Keep release history in GitHub Releases and leave the source and catalog focused on current behavior.
