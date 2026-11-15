
# MSB Status Optimizer

<p align="center">
  <strong>Optimize your videos for WhatsApp Status — easily and efficiently.</strong>
</p>

<p align="center">
  A simple Windows application that helps prepare your videos as MP4 files for WhatsApp Status.
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Platform-Windows%2010%20%7C%2011-blue?style=for-the-badge&logo=windows" alt="Windows">
  <img src="https://img.shields.io/badge/Framework-.NET%2010-purple?style=for-the-badge&logo=dotnet" alt=".NET 10">
  <img src="https://img.shields.io/badge/Language-C%23-239120?style=for-the-badge&logo=csharp" alt="C#">
  <img src="https://img.shields.io/badge/License-MIT-green?style=for-the-badge" alt="MIT License">
</p>

---

## 📸 Application Preview

<p align="center">
  <img src="./screenshot%20(1).png" alt="MSB Status Optimizer - Screenshot 1" width="48%">
  <img src="./screenshot%20(2).png" alt="MSB Status Optimizer - Screenshot 2" width="48%">
</p>

---

## ✨ Features

- **WhatsApp Status Optimization** – Prepare videos for WhatsApp Status.
- **Automatic Size Optimization** – Automatically optimize videos for a suitable output size.
- **Custom Target Size** – Set your preferred output size from 1 MB to 100 MB.
- **High-Quality Encoding** – Uses H.264 video encoding for compatible output.
- **MP4 Output** – Export optimized videos in MP4 format.
- **Two-Pass Encoding** – Uses two-pass encoding for custom target-size processing.
- **English & Sinhala Support** – Switch between English and Sinhala.
- **Preference Saving** – Remembers your selected language.
- **Update Notifications** – Checks GitHub Releases for newer versions when the application starts.

## 📥 Download

Get the latest version of MSB Status Optimizer:

<p align="center">
  <a href="https://github.com/MANOX2004/MSB-Status-Optimizer/releases">
    <img src="https://img.shields.io/badge/Download-Latest%20Release-28a745?style=for-the-badge&logo=github" alt="Download Latest Release">
  </a>
</p>

**Direct Download – Version 1.0.0**

[Download MSB Status Optimizer Setup](https://github.com/MANOX2004/MSB-Status-Optimizer/releases/download/v1.0.0/MSBStatusOptimizerSetup-1.0.0.exe)

## 💻 System Requirements

- Windows 10 or Windows 11
- 64-bit (x64) operating system
- FFmpeg
- FFprobe

## ⚙️ Installation

1. Download the installer from the [Releases](https://github.com/MANOX2004/MSB-Status-Optimizer/releases) page.
2. Run `MSBStatusOptimizerSetup-1.0.0.exe`.
3. Complete the installation.
4. Make sure FFmpeg and FFprobe are installed and accessible on your system.
5. Launch MSB Status Optimizer.

### FFmpeg and FFprobe Setup

MSB Status Optimizer requires FFmpeg and FFprobe to process and inspect video files.

They must be installed separately. They are not bundled with the application.

Make sure both tools are available through your system PATH, or configure them as required by your installation.

- [FFmpeg Official Website](https://ffmpeg.org/)
- [FFmpeg Downloads](https://ffmpeg.org/download.html)

## 🚀 How to Use

1. Open MSB Status Optimizer.
2. Select the video you want to optimize.
3. Choose your preferred optimization mode.
4. For automatic optimization, use the automatic-size option.
5. To target a specific file size, select custom size and enter a value between 1 MB and 100 MB.
6. Start the optimization process.
7. Save the resulting MP4 video.

Your optimized video is now ready to be used for WhatsApp Status.

## 🔄 Update Notifications

MSB Status Optimizer checks the GitHub Releases page when the application starts.

When a newer version is available:

- **Update** – Opens the latest release page.
- **Later** – Dismisses the update notification.

The application does not automatically download or install updates.

## 🔒 Privacy

Your privacy matters.

- Video processing is performed locally on your computer.
- Your videos are not uploaded to WhatsApp or any external server by this application.
- The application checks GitHub Releases for update information when it starts.
- Your selected language preference is saved locally.

## ⚠️ Important Notes & Limitations

- FFmpeg and FFprobe must be installed separately.
- Automatic-size optimization may preserve compatible H.264/AAC MP4 streams when possible.
- Videos that cannot be preserved in their existing format may be re-encoded.
- Custom target-size processing uses two-pass H.264 encoding.
- The final output size may vary slightly depending on video content and encoding conditions.
- WhatsApp may re-encode videos after uploading. Therefore, identical quality or completely lossless playback cannot be guaranteed.

## 🛠️ Troubleshooting

**FFmpeg or FFprobe not found**

Make sure FFmpeg and FFprobe are installed correctly and accessible through your system PATH.

**Video processing fails**

Check whether the input video is supported and verify that FFmpeg is working correctly.

**Output file is larger or smaller than expected**

Encoding results can vary depending on the video content. Custom target-size mode uses two-pass encoding to help reach the requested size.

**Update notification does not appear**

Make sure your computer has an active internet connection and try launching the application again.

## 📄 License

MSB Status Optimizer is intended to be distributed under the MIT License, subject to the repository's `LICENSE` file.

See [LICENSE](LICENSE) for details.

---

<p align="center">
  <strong>MSB Status Optimizer</strong>
  <br>
  Made for easy WhatsApp Status video optimization.
  <br><br>
  <a href="https://github.com/MANOX2004/MSB-Status-Optimizer">GitHub Repository</a>
  ·
  <a href="https://github.com/MANOX2004/MSB-Status-Optimizer/releases">Releases</a>
</p>
