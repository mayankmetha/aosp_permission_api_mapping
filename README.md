# AOSP API to permissions mapping list
This tool is meant to extract:
* Android APIs with @RequiresPermission
* Maps the APIs with the permission

**This tool is only compatible with Python >= 3.5**

## Preliminaries
First of all, you have to clone the huge AOSP repository:
```
mkdir AOSP
git clone https://android.googlesource.com/platform/frameworks/base AOSP
```
## Usage
```
pip install git+https://github.com/mayankmetha/aosp_permission_api_mapping
aosp_permission_api_mapping [path to AOSP folder] [destination folder]
```
the destination folder will be automatically created.
