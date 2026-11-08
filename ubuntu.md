# Ubuntu Setup

### Git Setup
```bash
git clone --recursive --depth 1 --shallow-submodules https://github.com/akinomyoga/ble.sh.git
```

### Starship Config
> Paste the code snippet inside `.config/starship.toml`:

```toml
add_newline = true

format = """
$directory\
$git_branch\
$git_status\
$character"""

[directory]
style = "bold cyan"
truncation_length = 3
truncate_to_repo = false

[git_branch]
symbol = " "
style = "bold purple"

[git_status]
style = "bold yellow"

[character]
success_symbol = "[❯](bold green)"
error_symbol = "[❯](bold red)"
```

### Reference Image
<!-- Place your image inside the assets/ folder and update the filename below -->
![Reference Image](assets/reference.png)