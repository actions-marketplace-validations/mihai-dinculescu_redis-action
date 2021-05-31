# Redis GitHub Action

This [GitHub Action](https://github.com/features/actions) sets up Redis database.

Inspired by https://github.com/Harmon758/postgresql-action, @Harmon758 Thanks!

# Usage

See [action.yml](action.yml)

Basic:

```yaml
steps:
  - uses: mihai-dinculescu/redis-action@v1.2.0
    with:
      redis version: "latest" # Optional, default is "latest"
      number of databases: 16 # Optional, default is 16
      redis password: "" # Optional, default is empty
```

# License

The scripts and documentation in this project are released under the [MIT License](LICENSE)
