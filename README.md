# Qt音视频播放器

## 项目简介

本项目是一个基于Qt框架开发的音视频播放器，结合了FFmpeg、SDL2.0和QOpenGLWidget技术，实现了音视频的解码与播放。该播放器支持多种音视频格式的播放，并具备播放控制、全屏控制、音量控制、播放列表管理、网络流播放、文字水印添加以及视频自适应显示等功能。

## 功能特点

1. **音视频解码与播放**：
   - 使用FFmpeg和SDL2.0进行音视频的解码，支持多种音视频格式的播放。
   - 视频图像解码为YUV420格式，并通过QOpenGLWidget进行显示。

2. **播放控制**：
   - 支持播放、暂停、停止、下一个、上一个等基本播放控制功能。
   - 提供播放进度条控制，方便用户快速定位播放位置。
   - 支持全屏播放和音量调节。

3. **播放列表管理**：
   - 附带播放列表功能，可记录播放的视频路径，方便用户管理多个视频文件。

4. **网络流播放**：
   - 支持播放各种网络流，包括RTMP、HTTP、RTSP、FLV等格式。

5. **文字水印**：
   - 支持在播放视频时添加文字水印，方便用户进行个性化设置。

6. **视频自适应显示**：
   - 播放视频时，视频窗口可根据视频的分辨率大小自动调整，确保最佳显示效果。

## 平台支持

- **Windows**：经过测试，本播放器在Windows操作系统下运行稳定。
- **Linux**：同样经过测试，本播放器在Linux操作系统下也能正常运行。

## 第三方库支持

- **FFmpeg**：用于音视频的解码。
- **SDL2.0**：用于音频的播放。
- **QOpenGLWidget**：用于视频图像的显示。

## 使用说明

1. **下载资源文件**：
   - 下载本仓库中的资源文件，解压后即可使用。

2. **运行播放器**：
   - 打开解压后的文件夹，找到可执行文件并运行。

3. **添加视频文件**：
   - 在播放器界面中，通过播放列表功能添加本地视频文件或网络流地址。

4. **播放控制**：
   - 使用播放器界面上的控制按钮进行播放、暂停、停止等操作。

5. **全屏播放**：
   - 点击全屏按钮，即可进入全屏播放模式。

6. **音量调节**：
   - 使用音量控制滑块调节播放音量。

7. **添加水印**：
   - 在播放器设置中，添加文字水印，并调整水印的位置和样式。

## 注意事项

- 本播放器在Windows和Linux系统下均可使用，但请确保系统中已安装必要的依赖库。
- 播放网络流时，请确保网络连接稳定。

## 贡献

欢迎大家提出改进建议或提交代码，共同完善这个音视频播放器项目。

## 许可证

本项目采用MIT许可证，详情请参阅LICENSE文件。

## 下载链接

[Qt音视频播放器](https://pan.quark.cn/s/a1b64f4456bb)