---
Bereich: git
tags:
  - git
  - settings
  - development
  - repository
---
## Wo platzieren?

`.gitignore` ist der Standard

* Verzeichnisabhängig möglich
* typischerweise Teil der Versionierung
* Im Repo

`.git/info/exclude` kann man als lokale (zusätzliche) Version nehmen
* lokal
* wird nicht synchronisiert
* bei *worktrees* im "main" Verzeichnis
* Notation ist wie bei `.gitignore`