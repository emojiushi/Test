# Test
个人测试用
p -r dir1 dir2 表示将dir1及其dir1下所包含的文件复制到dir2下
cp -r dir1/. dir2 表示将dir1下的文件复制到dir2,不包括dir1目录


cp -r "/home/fwx346468/agwatch/a00816863_nov/."  "/home/fwx346468/agwatch/yangnneggood/"
查看当前所在目录：
pwd

删除： /var/log/httpd/access
cd /var/log/httpd/   先到该目录下
rm -rf access                  然后删除本目录

guangda6699/build/HuaweiHealth/src/main/java/com/huawei/health/MainActivity.java

./health_common/services_api/src/main/java/com/huawei/hihealthservice/util/HealthAccessTokenUtil.java


删除指定目录下的文件


df -h  查看空间
1.rm -f 指定目录*

find ./yangneng/ -name DeviceActiveState.java
find -name HwHealthBrowserActionActivity.java

find . -name "*.gradle" | xargs grep "szg1.artifactory.inhuawei.com"

 cd D:/code/Watch_Face/Music_Themes_HwThemeManager/build_script
./build_local_release.sh

find . -name "*.gradle" | xargs grep "com.huawei.ohos.localability:localability"
com.huawei.ohos.localability:localability

git clone ssh:




adb shell "dumpsys activity top | grep '#1: ' | tail -n 1"  第二个


adb shell dumpsys activity top

adb shell mkdir -p /data/local/tmp/local/tmp  创建文件夹：


./gradlew clean

adb install -r -d C:\Users\yWX1138194\Desktop\HuaweiHealth-china-beta.apk

adb uninstall com.huawei.theme.watchfacemarket //卸载应用 包名

adb logcat >文本文件的位置

adb push 资源的绝对地址(将目标文件拖到此处即可)  ./sdcard

adb kill-server

adb start-server

adb shell kill []
adb shell ps|grep<com.huawei.theme.watchfacemarket>

adb shell pm clear com.huawei.hwid
adb uninstall com.huawei.hwid

adb shell pm clear com.huawei.health 
adb shell pm clear com.huawei.theme.watchfacemarket
adb shell pm clear com.huawei.watch.settings
adb shell pm clear com.huawei.android.thememanager
adb uninstall com.huawei.health 
查看目录结构 ：adb shell ls
adb logcat -c  清空日志缓存  

adb shell pm path com.huawei.health
adb pull /data/app/com.huawei.health-shk9hz6q1XHDfEQRGK_2hA==/base.apk /Users/myuser/Downloads



 cd D:/code/Watch_Face/Music_Themes_HwThemeManager/build_script
./build_local_release.sh


./gradlew app:assembleMirrorRelease -PdisableAgcPlugin   表盘市场测试

./gradlew app:assembleBetaRelease  表盘市场 现网

adb reboot resetfactory   恢复工厂模式
  
adb push HwWatchFace.apk /system/priv-app/HwWatchFaceMarket/

adb shell rm -rf /data/user_de/0/com.huawei.theme.watchfacemarket
adb shell rm -rf  /system/priv-app/HwWatchFaceMarket/
adb push HwWatchFaceMarket.apk /system/app/HwWatchFaceMarket/


pm list pacakage
pm list pacakage |grep   watchfacemarket

ls |grep   watchfacemarket

adb reboot resetfactory
adb devices

adb shell pm dump com.huawei.hwid | findstr "version"

FOR /f "usebackq" %%i IN (`PowerShell ^(Get-Date^).ToString^('yyyy-MM-dd-HH_mm_ss'^)`) DO SET Today=%%i
start cmd  /k "cd /d D:\dpan\scrcpy&&.\scrcpy -r %Today%.mp4"

