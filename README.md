# neteaseMUSICdump
<h1>---------ENGLISH---------------------------</h1>
<p>tips: Please forgive me for my poor English level</p>
<p>some tools for netease music include"dump ncm file, get songlist music ID, Music ID to lrc and tlyric</p>
<p>File list:</p>
<p>--lrcget.py a example to get song lyric</p>
<p>--songlist_source.py an example to get songlist's music's ID</p>
<p>--Ncm2music_py2.py The tools to turn *.ncm to mp3 or flac file(MP3 files can restore songs, pictures and tags，FLAC files can restore the song labels and download the cover to local locations, with only some players supporting mounting surface images)</p>
<p>-------------------------------------------</p>
<h1>--------------中文--------------------------</h1>
<p>Netease Cloud Music Copyright Protection File Dump (Python version)</p>

<h2>简介</h2>
<p>Python版本解密ncm文件，根据贴吧某位大神的源码再开发而来，加了很多使用功能，比如嵌入歌曲tags和封面图片(flac嵌入图片有问题，但是保存为同名文件播放器是可以识别的,想要嵌入文件的童鞋可以自己琢磨一下mutagen库)还有下载歌词啥的。</p>
<p>依赖 pycrypto库 和 mutagen 库</p>
<p>pip(3) install pycrypto</p>
<p>推荐使用下面的crypto库！不安装上面的库</p>
<p>pip3 install -i https://pypi.douban.com/simple pycryptodome</p>
<p>如果发现明明安装了pycryptodome却不可以使用，请到python目录下，打开lib/site-packages (如C:\Python27\Lib\site-packages)找到crypto文件夹，将其更名为Crypto即可正常使用crypto库</p>
<p>嘤嘤嘤，嫌弃官方源太慢可以自行百度国内pypi源然后更换</p>
<p>使用pip install pycryptodome mutagen requests urllib3来安装依赖库</p>
<p>你也可以将软件使用pyinstaller编译成单个exe文件使用，此文件可以运行于python3或者python2环境中，但我只在python2环境中使用pyinstaller编译过，python3尚未测试编译</p>


<h3>部分源代码来自:-百度贴吧:http://tieba.baidu.com/p/5792928807?traceid=</h3>
<h3>部分源代码来自:-Github:https://github.com/lianglixin/ncmdump</h3>
<h3>本软件版权归KGDsave Software Studio所有，但是源代码可以供您随意使用(包括，二次开发，更改原文件等)，但是禁止用于商业用途。</h3>
<h3>CopyRight 2016-2020 KGDsave SoftWare Studio-------------------------2018.10.27 14:00 上传</h3>

<p>因为不知为何github在线无法上传文件，就只能扔到百度云盘了</p>
<h3>源码:链接: https://pan.baidu.com/s/1FJFCvXmumjgEro23xWAdXQ 提取码: 3dtc</h3>
<h3>编译版本(win10 x32 python2.7 make by pyinstaller):链接: https://pan.baidu.com/s/1uQktJ6pMG5bFsb8n7xPEgw 提取码: mjmg</h3>
