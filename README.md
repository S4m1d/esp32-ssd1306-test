# Setup
## First compilation
To download libraries and compile app for the first time run:
```bash
pio run
```

## LSP
Generate `compile_commands.json` for correct LSP behaviour
```bash
pio run --target compiledb
```

Generate `.clangd` for correct LSP behaviour:
```bash
. clangd_gen.sh
```

# Build and upload
```bash
pio run --target upload
```
