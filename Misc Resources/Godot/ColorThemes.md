https://github.com/Calinou/godot-syntax-themes

## Installation

Place the `.tet` files in your Godot text editor theme directory:

- On Linux: `~/.config/godot/text_editor_themes/`
- On macOS: `~/Library/Application Support/Godot/text_editor_themes/`
- On Windows: `%APPDATA%\Godot\text_editor_themes\`

**Note:** If you installed Godot using Steam, your Godot text editor theme folder should be placed in `steamapps/common/Godot Engine/editor_data/text_editor_themes/` in your Steam installation folder.

To change the theme, open a project in the editor, click on **Editor** in the top menu, then go to the **Editor Settings** then **Text Editor**. You should now be able to choose the desired theme.

**Tip:** You can clone this Git repository directly into the text editor themes path (if the destination folder does not exist) using the following command:

```shell
# On Linux:
git clone https://github.com/godotengine/godot-syntax-themes.git ~/.config/godot/text_editor_themes

# On macOS:
git clone https://github.com/godotengine/godot-syntax-themes.git "~/Library/Application Support/Godot/text_editor_themes"

# On Windows:
git clone https://github.com/godotengine/godot-syntax-themes.git "%APPDATA%\Godot\text_editor_themes"
```