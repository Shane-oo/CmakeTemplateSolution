# Install Dependencies
1. ./vcpkg install
2. Change the CMAKE_TOOLCHAIN_FILE in CmakePresets.json.

    "name": "vcpkg-base",
   "hidden": true,
   "cacheVariables": {
   "CMAKE_TOOLCHAIN_FILE": {
   "type": "PATH",
   "value": "PATH TO vcpkg.cmake, i.e. C://Users/shane/Documents/repos/vcpkg/scripts/buildsystems/vcpkg.cmake"
   }

3. Install Vulkan SDK  https://www.lunarg.com/vulkan-sdk/

