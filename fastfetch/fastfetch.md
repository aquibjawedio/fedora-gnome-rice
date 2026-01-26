## 1. Fastfetch Setup

### Generate the Fastfetch Configuration

Run the following command to generate the default configuration file:

```bash
fastfetch --gen-config
```

This command creates a default Fastfetch configuration file called `config.jsonc`.

On Fedora, the file is usually located at:

```text
~/.config/fastfetch/config.jsonc
```

### Apply the configuration

1. Open the `config.jsonc` file (_`nano`, `nvim`, etc._).
2. Copy **my Fastfetch config**.
3. Paste it into `config.jsonc`, replacing the existing content.
4. Save the file.
5. Download the `logo.txt` file and place it in the `fastfetch` folder where `config.jsonc` is located.
6. Your Fastfetch customization is complete. Now run:

```bash
fastfetch
```
