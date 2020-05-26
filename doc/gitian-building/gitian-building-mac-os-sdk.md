Gitian building Mac OS SDK
==========================

Get MacOSX10.14.sdk.tar.gz
--------------------------

Get `MacOSX10.14.sdk.tar.xz` from the following site and convert it to `MacOSX10.14.sdk.tgz`.
[https://github.com/phracker/MacOSX-SDKs/releases](https://github.com/phracker/MacOSX-SDKs/releases)


Copy SDK to Gitian VM:
----------------------

Login to the VM and:

```bash
mkdir -p gitian-builder/inputs
mv MacOSX10.14.sdk.tar.gz gitian-builder/inputs
```

