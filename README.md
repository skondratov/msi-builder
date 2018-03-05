# msi-builder

Simple tool which allows to create msi file from any Windows executable.

It requires *wixtoolset* installed:
```
choco install wixtoolset
```

## Usage

Copy review ```artifacats/*``` folder, replace artifacts with you own. Rename ```example_config.ini``` to ```config.ini```. Adjust parameters in ```config.ini```.

Run ```MsiBuilder.exe path_to_your_app output_path version```