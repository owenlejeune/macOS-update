# macOS Update
A simple CLI tool handling macOS software updates

### Usage
macosupdate offers several options for controlling how software updates are handled. When no options are specified, macosupdate will install all available updates
```bash
$ macos-update
# equivalent to
$ software -i -a
```
Using the **list** argument allows you to view a list of all availbe updates without installing them.
```bash
$ macos-update list
# equivalent to
$ softwareupdate -l
```
Using the **install** argument allows you to install a specific software updated based on the update name.
```bash
$ macos-update install <NAME>
# equivalent to
$ softwareupdate -i <NAME>
```
Using the **download** argument allows you to download a specific software updated based on the update name *without* installing it.
```bash
$ macos-update download <NAME>
# equivalent to
$ softwareupdate -d <NAME>
```

### Installation
#### Manual
1. Clone to repo
2. Execute the script from the cloned directory using `$ ./maco-supdate`
3. **Optional:** add the cloned folder to your system PATH to use anyway
