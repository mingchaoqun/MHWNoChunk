﻿MHWNoChunk:
Developed by Jodo @ DMQW Modding Group.
Nexusmods link to MHWNoChunk: https://www.nexusmods.com/monsterhunterworld/mods/411
Github link to MHWNoChunk: https://github.com/zhangtaoxinzi/MHWNoChunk

﻿The tool learns from the WorldChunkTool to deal with the decompressing process.  Thanks to the author MHVuze's great work on WorldChunkTool.
Nexusmods link to ﻿WorldChunkTool :https://www.nexusmods.com/monsterhunterworld/mods/6/
﻿Github link to WorldChunkTool: https://github.com/mhvuze/WorldChunkTool
﻿
﻿This tool can decompress part of the MHW chunk file as you want. 
﻿2x speed and 0.5x disk usage. No .PKG file created.

﻿v1.3.1 update:
﻿﻿Added progressbar value sight. Added auto copy .dll file.
﻿v1.3.0 update:
﻿﻿Added combine extract mode. Once combine and extract all files with all the newest version.
﻿v1.2.1 update:
﻿﻿Fixed memory leaking problem while extracting big files like bgm_ingame.npck
﻿v1.2 update:
﻿﻿Added decompressed file size sight.
﻿v1.1 update:
﻿﻿Added progress bar.﻿

﻿Usage:
﻿﻿0.The tool requires .net framework 4.7.2. If you can't open the software properly, download it from  https://dotnet.microsoft.com/download/dotnet-framework-runtime.
﻿﻿1.*Copy oo2core_5_win64.dll from the root directory of you MHW game to the directory of "MHWNoChunk.exe"  if you don't use chunkN.bin file from the original path.
﻿﻿2.Double click the "MHWNoChunk.exe" file to start.
﻿﻿3.Drag and drop a chunk*.bin file you want to decompress from chunk directory of your MHW root folder to the blank area of the software GUI. Check the 'Combine all chunks' option on the right side before dragdrop file if you want to once combine all chunkNs and extract with all the newest-versioned-files.
﻿﻿4.Check the checkbox of the files you want.
﻿5.Click the "Extract Selected" button and select the directory you want to export to.

--------------------------------------------------------------------------------------
MHW部分解包器：
由Jodo @ 狩技MOD组开发
MHWNoChunk Nexusmods 链接: https://www.nexusmods.com/monsterhunterworld/mods/411
MHWNoChunk Github 链接: https://github.com/zhangtaoxinzi/MHWNoChunk
MHWNoChunk 3dm论坛 链接: http://bbs.3dmgame.com/thread-5804181-1-1.html

本工具学习了WorldChunkTool的解包原理，非常感谢原作者MHVuze在游戏文件解包方面作出的重要贡献。
WorldChunkTool Nexusmods链接 :https://www.nexusmods.com/monsterhunterworld/mods/6/
WorldChunkTool GitHub链接: https://github.com/mhvuze/WorldChunkTool

﻿
自选解包，一步到位，立等可取，不需要生成中间文件浪费空间，2x速度，0.5x磁盘占用。

v1.3.1 增加进度条数值显示，增加自动复制oo2core功能
v1.3.0 增加全chunk联合解包模式，一次性解析所有chunk并解包相应最新文件，先勾选“”联合解析全部chunk”并随意拖入一个chunkN.bin即可开始联合解包
v1.2.1 修复大文件解包错误
v1.2 更新增加了文件尺寸显示
v1.1 更新增加了进度条

使用方法：
0.软件基于.net framework 4.7.2框架制作，如果无法运行，则需先从 https://dotnet.microsoft.com/download/dotnet-framework-runtime 下载并安装运行环境。
1.*如提示未找到oo2core_5_win64.dll，请从你的怪物猎人：世界游戏安装目录拷贝该文件至本程序文件夹
﻿﻿2.双击"MHWNoChunk.exe"来启动程序
﻿﻿3.将需要解包的chunk*.bin拖入软件所示白色区域即可读取chunk内容。如果想要联合解包，则需要在拖拽前先勾选“联合解析全部chunk”
﻿﻿4.单击希望解包的文件前的选择框即可选中该文件/文件夹，选中文件夹的子文件将全部被选中
﻿5.单击右下角的“提取所选文件”，然后在弹出的文件夹选择框中选择希望解包到的目录，程序会在选中目录下自动创建与所选chunk文件名相同的文件夹并向该文件夹输出所选择要解包的内容。