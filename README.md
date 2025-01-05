[![Android CI](https://github.com/0xMe/KMrite/actions/workflows/build.yml/badge.svg?branch=master&event=workflow_dispatch)](https://github.com/0xMe/KMrite/actions/workflows/build.yml)
# KMrite
Patch runtime process library(*.so) with offset & hex bytes
<br>
This project is made for you who like to build and injector app with no c++ at all.

## Screenshots
| Main Screen | Edit Screen | Work Screen |
|-----------|-----------|-----------|
| ![image](https://github.com/AbhiTheModder/KMrite/assets/85984486/2297e7ef-1ea1-40a2-abe3-7f297d0338dd) | ![image](https://github.com/AbhiTheModder/KMrite/assets/85984486/72d5d4fe-9ce0-46f3-9d7c-8cb484b32b6a) | ![image](https://github.com/AbhiTheModder/KMrite/assets/85984486/4f9f00fc-b977-49b6-aadb-b85d14722100) |


## Build & Usages 
You can also get the build output in the [actions](https://github.com/0xme/KMrite/actions) section of the repo or at my telegram channel [@AbhiTheM0dder](https://t.me/AbhiTheM0dder/1225)
- Download this project
    - `git --clone  [https://github.com/BryanGIG/KMrite](https://github.com/AbhiTheModder/KMrite)`
- Open and build the project
- Install the app into your android devices
    - If you had root, grant permission root
    - If you non-root, use virtual app
- Open app that you want to inject
- Open the KMrite
- Fill all needed information :
    - Package Name : **The package of your process**
    - Lib Name : **Library(*.so) name**
    - Offset : **0x...**
    - Hex : **200080D2C0035FD6**
- Click **START PATCH** to begin inject into the process

## Credits
- [LibInjector](https://github.com/jbro129/LibInjector) by [jbro129](https://github.com/jbro129)
- [libsu](https://github.com/topjohnwu/libsu) by [topjohnwu](https://github.com/topjohnwu) 
