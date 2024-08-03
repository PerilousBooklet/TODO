
- [ ] TODOTREEVIEW: rework config options with `common.merge`
- [ ] TODOTREEVIEW: decrease space between icon and text
- [ ] DEVICONS: Update file extensions for `devicons`, `lsp`, `lintplus` and all related `language_...` plugins
- [ ] Fix `devicons` manifest and update its stub

---

- [ ] Add project-wide refactoring command + custom tab to choose which entries to ignore, see [jgmdev's PR](https://github.com/pragtical/pragtical/pull/48)
- [ ] Add doc symbols treeview

- [ ] DEVICONS: Fix and add V, F#, AWK icons

- [ ] SCM: add git icons
- [ ] SCM: all still open files must close after doing a `git checkout branchname`
- [ ] SCM: add proper (VSCode-like) git support
- [ ] SCM: add a visual git-history tab with a custom icon font for lines and points (inspired by gitkraken, use EmptyView) (?)

- [ ] LSP: standardize (when possible) LSP servers install instructions in the `config.lua`
- [ ] LSP: Update `zls` status to `Works`
- [ ] LSP: Study `formatter` data storage design
- [ ] LSP: Study `snippets` data storage design
- [ ] LSP: Add java methods auto-import for classes/interfaces/enums
- [ ] LSP: Add edit-after and multiple-edits
- [ ] LSP: Doc views should exist at doc level
- [ ] LSP: doc views should not be scroll-bound by doc height
- [ ] LSP: Add functionality that allows adding custom additional dependency paths in the project file
- [ ] LSP: Write a plugin (similar to `exec`) that allows to run scripting code in a newly-spawned terminal instance
- [ ] LSP: Finish `language_ocaml`
- [ ] LSP: Finish `language_erlang`
- [ ] LSP: BUNDLES: add all remaining LSP servers

- [ ] LINT+: Add all remaining external linters

- [ ] FORMATTER: `config.format_on_save` should be `config.plugins.formatter.format_on_save`
- [ ] FORMATTER: Add the functionality for `code-insert-into-file`
- [ ] FORMATTER: update formatter run calls (`os.exec()` -> `process.start()`)
- [ ] FORMATTER: rework data storage (convert to the system used by `snippets`)
- [ ] FORMATTER: Add all remaining formatters

- [ ] PTM: add auto-fill for java class/interface/enum files upon creation (with context-menu widget to choose files)
- [ ] PTM: Add custom config files for the LSP servers that require them

