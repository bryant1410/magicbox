Javassist 使用:
https://www.ibm.com/developerworks/cn/java/j-dyn0916/


CLASS_ISPREVERIFIED的问题:
https://github.com/dodola/HotFix


https://github.com/bunnyblue/DroidFix



gradle commend-line:

http://stackoverflow.com/questions/29289200/in-gradle-exec-task-commandline-searching-environment-but-not-working-directory

http://blog.csdn.net/innost/article/details/48228651


使用方法:
将app-build-outputsd的app-debug.apk提取classes.dex文件，将这个文件压缩，生成一个只有代码没有资源的zip包，这个包便是补丁包，

同一个项目下生成的补丁，兼容不同的签名，debug生成的补丁也可以给release版本打补丁。