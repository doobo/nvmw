Node.js的4.0以上版本的临时解决方案

Backup .nvmw/nvmw.bat

Create a new nvmw.bat file from:https://github.com/TimothyGu/nvmw/blob/f652299d30e5f4583d6b68d6024da423fd1005d5/nvmw.bat

Create .nvmw/v6.1.0 directory

Grab the npm source zip of the latest stable release from https://github.com/npm/npm

Rename the zip to npm.zip and place in the v6.1.0 directory.

Run nvmw install 6.1.0 if you're using 64bit, else don't use the architecture option

需要低版本的，可以：
   git checkout HEAD^  //退回上一个版本
或
   git checkout -- nvmw.bat //撤回nvmw的修改
