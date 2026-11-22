# Setup `dbman`

This GitHub Action installs the DatabaseManager CLI (`dbman`) from GitHub Releases and adds it to the PATH.

To use it in your workflow, invoke it in a step prior to using the `dbman` CLI:

```yaml
- uses: tcfoss/setup-dbman@v1
  with:
    version: 1.4.2   # optional

- run: dbman compute-changes ...
```
