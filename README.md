# neteaseMUSICdump
---------ENGLISH---------------------------
tips: Please forgive me for my poor English level
some tools for netease music include"dump ncm file, get songlist music ID, Music ID to lrc and tlyric,
File list:
--lrcget.py a example to get song lyric
--songlist_source.py an example to get songlist's music's ID
--Ncm2music_py2.py The tools to turn *.ncm to mp3 or flac file(MP3 files can restore songs, pictures and tags，FLAC files can restore the song labels and download the cover to local locations, with only some players supporting mounting surface images)
-------------------------------------------
--------------中文--------------------------
Netease Cloud Music Copyright Protection File Dump (Python version)

简介
Python版本解密ncm文件，根据贴吧某位大神的源码再开发而来，加了很多使用功能，比如嵌入歌曲tags和封面图片(flac嵌入图片有问题，但是保存为同名文件播放器是可以识别的,想要嵌入文件的童鞋可以自己琢磨一下mutagen库)还有下载歌词啥的。
依赖 pycrypto库 和 mutagen 库
pip(3) install pycrypto
推荐使用下面的crypto库！不安装上面的库
pip3 install -i https://pypi.douban.com/simple pycryptodome
如果发现明明安装了pycryptodome却不可以使用，请到python目录下，打开lib/site-packages (如C:\Python27\Lib\site-packages)找到crypto文件夹，将其更名为Crypto即可正常使用crypto库
嘤嘤嘤，嫌弃官方源太慢可以自行百度国内pypi源然后更换
使用pip install pycryptodome mutagen requests urllib3来安装依赖库
你也可以将软件使用pyinstaller编译成单个exe文件使用，此文件可以运行于python3或者python2环境中，但我只在python2环境中使用pyinstaller编译过，python3尚未测试编译


部分源代码来自:-百度贴吧:http://tieba.baidu.com/p/5792928807?traceid=
部分源代码来自:-Github:https://github.com/lianglixin/ncmdump
本软件版权归KGDsave Software Studio所有，但是源代码可以供您随意使用(包括，二次开发，更改原文件等)，但是禁止用于商业用途。
CopyRight 2016-2020 KGDsave SoftWare Studio-------------------------2018.10.27 14:00 上传
