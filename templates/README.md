# Debian distributions templates

To generate the configuration files, you can use `jinja2-cli`:

```
pip install jinja2-cli
jinja2 distributions.j2 variables.yml
```

Those templates are primarily used during a new release, see the `release` repo.
