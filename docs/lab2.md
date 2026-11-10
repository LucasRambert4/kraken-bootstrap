Le job `kraken / lint-test` doit réussir sur chaque pull request avant toute fusion.
Le job `kraken / build-push` reconstruit le Dockerfile et détecte une image qui ne se construit plus.
Le ruleset actif de `main` impose une pull request et bloque la fusion tant que ces deux checks ne sont pas verts.
