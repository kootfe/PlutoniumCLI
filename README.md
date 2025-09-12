# PlutoiumCLI - General QoL


## What is PlutoiumCLI
PlutoiumCLI (plcli) is a tool that provides general Quality of Life features for your Command Line Interface (CLI). It helps you work much faster.

## Features To-Do
- [ ] Bulk rename files
- [ ] Improved directory tree
- [ ] Enhanced `ls` command
- [ ] Advanced filtering
- [ ] Undo/Redo functionality
- [ ] Plutoium Plugin Manager (PM)
- [ ] Automatic aliases

## What is Plutoium PM 
PlutoiumPM (plpm) is the Plutoium Plugin Manager. It lets you install packages from GitHub, GitLab, or Codeberg.

```shell
    plpm add <user>/<repo> -gl
```
> By default, it uses `--github` (`-gh`), but you can also use `--gitlab` (`-gl`) or `--codeberg` (`-cb`).

### Using Plugin features

```shell
    plpm <pluginId> run <feature>
```
> You can add this to your `.zshrc` or `.bashrc` as an alias for easier use.

