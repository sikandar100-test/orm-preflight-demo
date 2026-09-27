# orm-preflight demo

A small TypeORM project that shows the [orm-preflight](https://github.com/sikandar100/orm-preflight)
GitHub Action at work. Every pull request runs `.github/workflows/migrations.yml`, which checks the
migrations the pull request adds or changes and annotates any hazard on the exact line.
