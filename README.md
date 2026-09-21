# homebrew-utilz

The Homebrew tap for [Utilz](https://github.com/matthewsinclair/utilz): small command-line utilities behind one dispatcher.

```bash
brew install matthewsinclair/utilz/utilz
utilz doctor
```

The formula builds from source at the release tag, on macOS (Apple Silicon and Intel). Its source of truth is `packaging/homebrew/utilz.rb` in the Utilz repository, where `tools/formula-bump` writes each release's tag and commit; it is copied here after each release.
