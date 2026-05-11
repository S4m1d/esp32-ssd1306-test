# General
Procedural animations project, made for learning ssd1306 chip's specifics.
Made with:
- ssd1306 chip based LCD screen
- esp32
- espidf framework

[![Watch the video](https://img.youtube.com/vi/pgPdwBTOGuk/maxresdefault.jpg)](https://youtube.com/shorts/pgPdwBTOGuk?feature=share) 

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
