# samiullaansari.github.io

Personal site built with Jekyll.

## Local Development

Run the site from WSL, not from the Windows Ruby environment.

### 1. Install gems locally in the repo

```bash
bundle config set --local path 'vendor/bundle'
bundle install
```

This keeps gems inside the project and avoids permission issues with the system Ruby directories.

### 2. Start the development server

```bash
bundle exec jekyll serve --livereload
```

Open the local URL printed by Jekyll, usually:

```text
http://127.0.0.1:4000/
```

## Notes

- Use `bundle exec` so Jekyll runs with the versions pinned in `Gemfile.lock`.
- If you update `Gemfile` or `Gemfile.lock`, run `bundle install` again.
- Build output is generated in `_site/` and is ignored by Git.
