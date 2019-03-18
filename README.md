https://github.com/linker402/ssr-win \
https://www.ssru.xyz/user/nodes \
https://ss.romdw.com/user \
https://en.ss8.fun \
https://global.ishadowx.net \
https://freess.cx \
https://free-ss.site \
https://www.wuwweb.com \
https://www.ssrshare.com \
https://doub.io/sszhfx \
https://github.com/max2max/freess \
https://github.com/max2max/freess/wiki/%E5%85%8D%E8%B4%B9ss%E8%B4%A6%E5%8F%B7 \
https://www.hanhanfilm.com \
http://www.youtubeto.com/zh \
https://y2mate.com \
http://finelybook.com \
http://www.hejizhan.com/html/search \
https://www.worldsrc.com/programs/crack.php?Ty=411&n=crack_For_Navicat_Premium \
http://element-cn.eleme.io/#/en-US \
https://official-kmspico.com/download/ \
https://www.youtube.com/playlist?list=PL6W3lurecOfyq3PucJuBNo5IWdH0FaTdo

# idea trial reset
#!/bin/bash

echo "removeing evaluation key" \
rm ~/.IntelliJIdea15/config/eval/idea15.evaluation.key

echo "resetting evalsprt in options.xml" \
sed -i '/evlsprt/d' ~/.IntelliJIdea15/config/options/options.xml

echo "resetting evalsprt in prefs.xml" \
sed -i '/evlsprt/d' ~/.java/.userPrefs/prefs.xml


## or:
#For IntelliJ IDEA 2017.1.2 EAP on Windows 10, I had to:
#
#Go to ´~/.IntelliJIdea2017.1/config´ \
#Remove the folder ´eval´ \
#Edit file options/options.xml and remove all properties that the name begins with evlsprt, such as: \
#\<property name="evlsprt3.171" value="18" \/\> \
#Go to Windows Registry and under subkeys of HKEY_CURRENT_USER\Software\JavaSoft\Prefs\jetbrains\idea delete keys that begin with evlsprt
