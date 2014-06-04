
### Install AMD APP OpenCL SDK

Download file `AMD-APP-SDK-v2.9-lnx64.tgz` from http://developer.amd.com/tools-and-sdks/opencl-zone/opencl-tools-sdks/amd-accelerated-parallel-processing-app-sdk/

``` bash
cd ~/Downloads/
mkdir AMDAPP
cp AMD-APP-SDK-v2.9-lnx64.tgz AMDAPP/
cd AMDAPP/
tar xzf AMD-APP-SDK-v2.9-lnx64.tgz 
echo Yes | sudo ./Install-AMD-APP.sh 
```

test
``` bash
clinfo 
```
