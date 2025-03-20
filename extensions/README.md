# Extensions

This is the top namespace for extensions.

## Adding New Extensions

Add to this folder the namespace for your extension or use one that already exists.

Your extension should be organized between `omnilake` and `omni` extensions, like the following example:

```

omnilake-extensions/
├─ extensions/
│  ├─ confluence/
│  │  ├─ omni/
│  │  │  ├─ __init__.py
│  │  │  ├─ README.md
│  │  ├─ omnilake/
│  │  │  ├─ __init__.py
│  │  │  ├─ README.md
│  ├─ jira/
│  │  ├─ omni/
│  │  │  ├─ __init__.py
│  │  │  ├─ README.md
│  │  ├─ omnilake/
│  │  │  ├─ __init__.py
│  │  │  ├─ README.md
```

Use the `__init__.py` files to expose your extension.
Use the `README.md` files to document behavior and usage.

Don't forget to add a reference to your `README.md` files to the root [README.md](../README.md#available-extensions) "Available Extensions" section.