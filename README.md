name: Generate Snake
on:
  schedule:
    - cron: "0 */6 * * *"  # Every 6 hours
  workflow_dispatch:

jobs:
  build:
    runs-on: ubuntu-latest
    steps:
    - uses: actions/checkout@v4
    - uses: Platane/snk@v3
      id: snake-gif
      with:
        github_user_name: 'ManasKeshari'  # YOUR username
        outputs: |
          dist/github-snake.svg
          dist/github-snake-dark.svg?palette=github-dark
    - uses: crazy-max/ghaction-github-pages@v4
      with:
        target_branch: output
        build_dir: dist