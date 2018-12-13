# pelux_browser


   1. Build project with SDK. It should be done under docker
   2. Upload binaries and resources on target by path: /opt/neptune3/apps
   3. Pack via command appman-packager create-package project_name.tar.gz com.test.pelux_browser
   4. Install via command appman-controller install-package -a project_name.tar.gz
