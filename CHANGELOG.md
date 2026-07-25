# Changelog

Todas as mudanças importantes deste projeto serão documentadas neste arquivo.


## Unreleased



### Outras alterações


- Merge branch 'main' of https://github.com/Mods-Stardew-Valley/The-Alchemist-Dream

- Add release ZIP packaging and update changelog groups

Workflow: add a step that packages the repo into a <repo>-<version>.zip when a new tag is created (excludes .git, .github, .gitattributes, cliff.toml, README.md, CHANGELOG.md and other zips) and attach the ZIP to the release. cliff.toml: adjust commit grouping — remove style/build/ci groups and add a ^release parser mapped to the "🏗 Versão" group; keep other existing groups. These changes enable publishing a release artifact and refine changelog categorization.

- Merge branch 'main' of https://github.com/Mods-Stardew-Valley/The-Alchemist-Dream

- Merge branch 'main' of https://github.com/Mods-Stardew-Valley/The-Alchemist-Dream


### ✨ Novidades


- Add GitHub update key to manifest


### 🐛 Correções


- Update recipe default flags and README


### 📚 Documentação


- atualiza CHANGELOG.md [skip ci]

- Update README with Release v0.1.1 and plan v0.2.0

- atualiza CHANGELOG.md [skip ci]

- atualiza CHANGELOG.md [skip ci]

- atualiza CHANGELOG.md [skip ci]


## v0.1.1 - 2026-07-24



### Outras alterações


- Clean up manifest and reorganize changelog

Remove test comments from manifest.json and reorganize the README changelog by moving the 'Unreleased' section header to appear before the versioned releases.

- Bump version to 0.1.1


### ✨ Novidades


- Added update key.

- Add Pearl and Galaxy Soul recipes


### 🐛 Correções


- Add ingredient to Fragmento Prismatico recipe


### 📚 Documentação


- Update README with v0.1.1 and v0.1.2 changelog

- Add community engagement and support sections

- Add Pearl and Galaxy Soul recipes, fix naming

- atualiza CHANGELOG.md [skip ci]

- Reorganize README and add development roadmap

- atualiza CHANGELOG.md [skip ci]


### 🔧 Manutenção


- Translate crafting recipe names to English


### 🧪 Testes


- comentarios ao fim do manifest


## v0.1.0 - 2026-07-22



### Outras alterações


- Merge branch 'main' of https://github.com/Mods-Stardew-Valley/The-Alchemist-Dream

- Bump version to 0.1.0


### ✨ Novidades


- Expand crafting recipes with material progression

- Update crafting recipes to ore materials


### 📚 Documentação


- atualiza CHANGELOG.md [skip ci]

- Update README with project details and recipes

- Add mineral breaking recipes and format recipes

- atualiza CHANGELOG.md [skip ci]


## v0.0.0 - 2026-07-22



### Outras alterações


- Update manifest.json

- Update manifest.json

- Change commit sort order to newest

Update cliff.toml configuration to sort commits in reverse chronological order (newest first) instead of oldest first.

- Automate changelog and release workflow

Refactored the changelog workflow to automatically detect version changes from manifest.json, create git tags for new versions, and generate GitHub releases with changelog notes. Replaced manual cargo installation with the orhun/git-cliff-action for improved reliability.

- Add changelog workflow and git-cliff config

Add .github/workflows/changelog.yml and cliff.toml. Workflow runs on pushes to main, installs git-cliff via cargo, generates CHANGELOG.md and auto-commits it using stefanzweifel/git-auto-commit-action with message 'docs: atualiza CHANGELOG.md [skip ci]'. cliff.toml defines header/body templates, enables conventional commits parsing, maps commit types to Portuguese headings (with emojis), and sets git-cliff options including tag pattern v[0-9]*.

- Initial commit


### ♻️ Refatoração


- mod folder and update README/manifest


### 📚 Documentação


- Add alchemist recipes to README

- Add changelog and roadmap to README

- atualiza CHANGELOG.md [skip ci]


### 🔧 Manutenção


- Remove example configurations from content.json

- Reset version to 0.0.0

- Restructure mod files and update manifest


