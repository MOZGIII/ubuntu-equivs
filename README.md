# ubuntu-equivs

`equivs` specs for useless ubuntu packages.

## Requirements

```shell
sudo apt-get install equivs
```

## Usage

1. Build a `.deb` from a spec file.

    Example:

    ```shell
    equivs-build gnome-shell-extension-appindicator
    ```

2. Install the generated `.deb` file.

    Example:

    ```shell
    sudo dpkg -i gnome-shell-extension-appindicator_999.0_all.deb
    ```
