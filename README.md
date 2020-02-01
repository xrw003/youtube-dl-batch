# youtube-dl-batch
这些批处理文件仅用于简化Windows .exe版本对http://rg3.github.io/youtube-dl/（来源：https：//github.com/rg3/youtube-dl）的使用。只是想简单地将其youtube-dl用作从YouTube（或其他地方）下载高质量视频的工具，而无需使用第三方服务或软件客户端（因为这些通常带有视频质量限制），而不是将其用于开发目的。

视频质量高于720p的视频必须分别下载视频和音频文件，然后将它们合并为一个文件（这正是YouTube由于某种原因而工作的方式）。要合并视频和音频文件，youtube-dl需要在系统上安装FFmpeg（https://www.ffmpeg.org/）。另外，如果您不想安装FFmpeg，则可以下载youtube-dl-batch包含所有必需文件（包括FFmpeg）的发行版。也有该-noFFmpeg版本的版本。

** 请注意，该 youtube-dl.exe文件必须与.bat文件存储在同一目录中才能正常工作。

## ytdlBasic.bat
这个批处理文件是最基本的。默认情况下，它仅下载最佳质量的视频。

## ytdlAdvanced.bat
该批处理文件允许用户输入视频URL，然后继续列出该视频的所有可用格式。然后，它提示用户手动选择所需的视频和音频格式。

## ytdlCustom.bat
通过允许您手动输入多个命令行参数，此批处理文件允许非常高级的用法youtube-dl。

## ytdlInfo.bat
此批处理文件列出了有关当前youtube-dlWindows .exe版本的基本信息。

## ytdlUpdate.bat
youtube-dl如果有更新，此批处理文件将更新您当前的.exe文件。

## 注意
该存储库及其文件目前是非常准系统。这只是为了好玩而已，没有什么太严重的。稍后我可能会添加其他功能。如果您愿意，可以贡献自己的力量！
