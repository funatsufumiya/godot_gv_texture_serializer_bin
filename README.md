# godot_gv_texture_serializer_bin

binary repository of [godot_gv_texture_serializer](https://github.com/funatsufumiya/godot_gv_texture_serializer)

if you need `godot_gv_texture_serializer` [releases](https://github.com/funatsufumiya/godot_gv_texture_serializer/releases) as `git submodule`, please use this repository.

## Simple usage example

```bash
cd PROJECT_DIR_OF_YOUR_GODOT
cd addons
git submodule add https://github.com/funatsufumiya/godot_gv_texture_serializer_bin.git gv_texture_serializer
# or simply: git clone https://github.com/funatsufumiya/godot_gv_texture_serializer_bin.git gv_texture_serializer
```

but I recommend to use `godotenv addons install`. see [GodotEnv's readme](https://github.com/chickensoft-games/GodotEnv?tab=readme-ov-file#initializing-godotenv-in-a-project). GodotEnv's `addons.jsonc` config is below (partial):

```json
    "gv_texture_serializer": {
      "url": "https://github.com/funatsufumiya/godot_gv_texture_serializer_bin",
      "checkout": "v0.1.0",
    },
```
