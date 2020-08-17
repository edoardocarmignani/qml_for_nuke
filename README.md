# QML

QML modules for different Nuke versions.

## How to use

* Download the package wherever you want
* To let Nuke and Maya read the package you need the `QML2_IMPORT_PATH` so set it with the package folder _(replace the qt version and the operative system according to your needs)_.

    ```shell
    set QML2_IMPORT_PATH=/path/to/folder/qml_for_nuke/5.x.x/os/qml
    ```

* Now everything is ready

| Nuke      | Qt        |
| --------- | ---------:|
| 11.2 &>   | 5.6.1     |
| 12.0 &>   | 5.12.1    |