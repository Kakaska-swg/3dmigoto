[EN](README.md) | 中文

# GI-Model-Importer
原神导入自定义模型的工具和说明

#### 免责声明：在官方服务器上使用本库中的MOD，很可能会被封号。我不推荐或纵容在官方服务器上使用这些脚本和程序，如果你依然要在官服上使用，我对由此产生的任何后果不承担责任。

GIMI 是我为了让 3DMigoto 兼容原神而将其修改后的工具

你可以随意使用或修改本库内的脚本，但如果你在你的项目中使用这里提供的程序，请注明出处。我将持续更新并修复这个程序/网页，所以请常回来看看。

故障排除指南: [Troubleshooting](Guides/Troubleshooting.md)

关于如何使用这些工具移除角色建模的简单指南，请参见[Mona Walkthrough](Guides/CN_MonaWalkthrough.md)。关于创建自定义武器的中级指南，请参见[自定义武器修改指南](Guides/BananaWeaponWalkthrough.md)。关于导入自定义模型的更高级的例子，请看塞伯坦伟大的视频指南[这里](https://www.youtube.com/watch?v=7ijMOjhEvBw)和SinsOfSeven#3164注释的文字记录和故障排除指南[这里](https://rentry.co/3dmigPlug_AnimeGame)。

模型文件位于[GI-Model-Importer-Assets](https://github.com/SilentNightSound/GI-Model-Importer-Assets)

## 安装指南 (3DMigoto)

1. 从此库中下载并解压 3dmigoto.zip。我提供了两个版本：
    - "3dmigoto (for development).zip" 是开发版，用于创作MOD，但比较慢。
    - "3dmigoto (for releasing mods).zip" 是精简版，用于发布MOD，比开发板快。

2. 根据你的 Genshin Impact.exe文件的位置，你可能需要更改 d3dx.ini 文件中的这一行，以指向你自己的安装位置。（游戏.exe，而不是启动器.exe）

<img src="https://user-images.githubusercontent.com/107697535/174322200-b1afea95-53f5-4add-be89-698f85503908.png" width="800"/>

3. 双击 "3DMigoto Loader.exe"启动加载器，然后通过 GenshinImpact.exe 启动原神。如果到目前为止一切正常，3DMigoto应该已被注入到游戏中，你应该能在游戏中看到一个绿色的文本（只有在使用开发版中显示，精简版不显示绿色文本）

![image](https://user-images.githubusercontent.com/107697535/174324967-049b9879-c537-4bd0-b190-4ad7444fb8f1.png)

<img src="https://user-images.githubusercontent.com/107697535/174325193-1f58ab2c-86f8-4ce9-8697-6e7d140b2014.png" width="800"/>

   - 注意：加载器显示 “unable to verify if 3dmigoto was loaded” 并不意味着 3dmigoto 未能注入 - 如果绿色文本/MODS有显示，就没有问题。

![image](https://user-images.githubusercontent.com/107697535/175563985-1e7d1298-08d0-4334-b6e8-c69769e3877a.png)

4. 安装完成！你现在应该就可以用 3DMigoto 加载自定义MOD并覆盖贴图和着色器了。想要要添加MODS，就请将它们放在Mods文件夹中（每个角色只能有一个mod），并在游戏中按F10加载它们。

![image](https://user-images.githubusercontent.com/107697535/175611402-c3f600ca-4136-4561-b33a-f4edf6153d1a.png)

&nbsp;
## 安装指南 (3DMigoto Blender 插件)

要是你想自行修改游戏模型，你还需要配置 Blender 插件和环境。3DMigoto 插件只适用于 Blender 2.80 以上的版本

1. 下载并安装 Blender

2. 下载并安装修改过的 [3DMigoto 插件](https://github.com/SilentNightSound/GI-Model-Importer/blob/main/Tools/blender_3dmigoto.py)。去到 Edit -> Preferences -> Add-Ons -> Install，选择刚下载的 .py 文件以安装插件。

3. 如果操作正确，你应该可在插件列表中看到 3DMigoto，以及在导入和导出菜单中的新选项。

<img src="https://user-images.githubusercontent.com/107697535/174328624-ccb14ded-57b2-4ac7-b0a0-0de118119174.png" width="800"/>

<img src="https://user-images.githubusercontent.com/107697535/174329025-981a1a9f-7c56-4f44-804b-1b0394b8bd33.png" width="800"/>

&nbsp;
## 使用指南

看[这里](Guides/CN_UsageInstructions.md)

另外，如果你有任何关于修改的问题，请加入原神MOD的Discord，网址是 https://discord.gg/agmg。

&nbsp;
## 致谢

衷心感谢DarkStarSword和bo3b的3dmigoto!
