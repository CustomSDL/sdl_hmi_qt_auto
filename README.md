# pelux_browser


   1. Download the test.tar.gz  from github to your local mashine
   2. Connect to the device with pelux via ssh and copy test.tar.gz to target by path ```/opt/neptune3/apps```. It can be done by command       (for instance) ```scp -r path/test.tar.gz root@192.168.0.100:/opt/neptune3/apps```
   3. Install package ```appman-controller install-package -a test.tar.tar.gz```
**Note!** that the neptune3 UI should be run at this time, for this porpuse we are connecting via ssh
   3. Run ```systemctl restart neptune3``` for restart neptune3 UI
   4. On apps set on pelux will appear the app with name - quicknanobrowser

 - For make package: ```appman-packager create-package project_name.tar.gz com.test.pelux_browser```
 - Install packaage: ```appman-controller install-package -a project_name.tar.gz```
