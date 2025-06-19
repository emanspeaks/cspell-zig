# cspell-zig

[cSpell](https://cspell.org) library for the [Zig programming language](https://ziglang.org)

## Usage

It is recommended to add this repo as a submodule to your existing project:

```bash
git submodule add https://github.com/emanspeaks/cspell-zig.git .cspell/zig
```

Then, ensure you import the config file in your existing project `.cspell.json` or equivalent file:

```json
{
    "version": "0.2",
    "import": [
        ".cspell/zig/cspell.json"
    ]
}
```
