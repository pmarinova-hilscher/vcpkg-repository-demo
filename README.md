# vcpkg-repository-demo

A demo of a vcpkg artifact repository for netX Studio.

For more information on vcpkg artifacts see:
* https://devblogs.microsoft.com/cppblog/vcpkg-artifacts/
* https://github.com/microsoft/vcpkg-ce-catalog
* https://learn.arm.com/learning-paths/microcontrollers/vcpkg-tool-installation/


After making changes to the artifact descriptions, you need to update `index.yaml` with the `x-regenerate` command executed from the repository root:
```
vcpkg-shell x-regenerate .
```