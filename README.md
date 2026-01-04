# Swap Face Easy / 换脸易

[English](#english) | [中文](#中文)

---

## English

A fast and easy-to-use face swapping tool powered by AI.

### Features

- **Video Mode**: Swap faces in video files
- **Camera Mode**: Real-time face swapping with webcam
- Cross-platform: macOS, Windows, Linux
- GPU accelerated for fast processing

### Download

Download the latest release for your platform from the [Releases](https://github.com/jlvihv/swap-face-easy/releases) page.

| Platform | File | GPU Support |
|----------|------|-------------|
| macOS (Intel) | `swap-face-easy-macos-x86_64.tar.gz` | CoreML |
| macOS (Apple Silicon) | `swap-face-easy-macos-aarch64.tar.gz` | CoreML |
| Windows | `swap-face-easy-windows-x86_64.zip` | DirectML (all GPUs) |
| Linux | `swap-face-easy-linux-x86_64.tar.gz` | CUDA (NVIDIA) |

### System Requirements

#### macOS
- macOS 10.15 or later
- No additional dependencies required (CoreML is built-in)

#### Windows
- Windows 10 or later
- No additional dependencies required (DirectML is built-in)

#### Linux
- NVIDIA GPU with CUDA support
- NVIDIA Driver 525+ recommended
- CUDA Toolkit 12.x

Install CUDA on Ubuntu/Debian:
```bash
# Install NVIDIA driver
sudo apt install nvidia-driver-535

# Install CUDA Toolkit
sudo apt install nvidia-cuda-toolkit
```

### Usage

1. Download and extract the release for your platform
2. Run `swap-face-easy` (or `swap-face-easy.exe` on Windows)
3. On first run, models will be automatically downloaded (~520MB)
4. Select a source face image and target video/camera
5. Click "Start Swap"

### Models

AI models are automatically downloaded on first run and stored in:
- **Linux**: `~/.local/share/swap-face-easy/models`
- **macOS**: `~/Library/Application Support/swap-face-easy/models`
- **Windows**: `%APPDATA%/swap-face-easy/models`

---

## 中文

一款快速易用的 AI 换脸工具。

### 功能特点

- **视频模式**：对视频文件进行换脸处理
- **摄像头模式**：实时换脸
- 跨平台支持：macOS、Windows、Linux
- GPU 加速，处理速度快

### 下载

从 [Releases](https://github.com/jlvihv/swap-face-easy/releases) 页面下载适合你平台的版本。

| 平台 | 文件 | GPU 支持 |
|------|------|----------|
| macOS (Intel) | `swap-face-easy-macos-x86_64.tar.gz` | CoreML |
| macOS (Apple Silicon) | `swap-face-easy-macos-aarch64.tar.gz` | CoreML |
| Windows | `swap-face-easy-windows-x86_64.zip` | DirectML (支持所有显卡) |
| Linux | `swap-face-easy-linux-x86_64.tar.gz` | CUDA (NVIDIA 显卡) |

### 系统要求

#### macOS
- macOS 10.15 或更高版本
- 无需安装额外依赖（CoreML 已内置）

#### Windows
- Windows 10 或更高版本
- 无需安装额外依赖（DirectML 已内置）

#### Linux
- 需要 NVIDIA 显卡
- 推荐 NVIDIA 驱动 525+
- 需要 CUDA Toolkit 12.x

Ubuntu/Debian 安装 CUDA：
```bash
# 安装 NVIDIA 驱动
sudo apt install nvidia-driver-535

# 安装 CUDA Toolkit
sudo apt install nvidia-cuda-toolkit
```

### 使用方法

1. 下载并解压对应平台的发布包
2. 运行 `swap-face-easy`（Windows 上是 `swap-face-easy.exe`）
3. 首次运行会自动下载 AI 模型（约 520MB）
4. 选择源人脸图片和目标视频/摄像头
5. 点击"开始换脸"

### 模型存储位置

AI 模型会在首次运行时自动下载，存储在：
- **Linux**: `~/.local/share/swap-face-easy/models`
- **macOS**: `~/Library/Application Support/swap-face-easy/models`
- **Windows**: `%APPDATA%/swap-face-easy/models`

---

## License

MIT License
