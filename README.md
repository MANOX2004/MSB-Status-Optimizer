# MSB Status Optimizer

**Prepare your videos for WhatsApp Status with ease.**

MSB Status Optimizer is a Windows desktop application designed to prepare video files as MP4 for WhatsApp Status. Choose automatic size optimization or set your own target file size while keeping video quality in mind.

Video processing happens locally on your computer. Your videos are not uploaded to WhatsApp or any external server by this application.

---

## ✨ Features

- **Automatic Size Optimization** – Automatically prepares videos for WhatsApp Status.
- **Smart MP4 Processing** – Preserves compatible H.264/AAC MP4 streams whenever possible.
- **High-Quality Encoding** – Other videos are encoded when stream preservation is not possible.
- **Custom Target Size** – Choose an output size between 1 MB and 100 MB.
- **Two-Pass Encoding** – Uses two-pass H.264 encoding in custom target size mode.
- **Bilingual Interface** – Switch between English and Sinhala.
- **Saved Language Preference** – Your selected language is remembered.
- **Update Notifications** – Checks GitHub Releases for newer versions when the application opens.

---

## 📥 Download

### Latest Installer – Version 1.0.0

**[Download MSB Status Optimizer (.exe)](https://github.com/MANOX2004/MSB-Status-Optimizer/releases/download/v1.0.0/MSBStatusOptimizerSetup-1.0.0.exe)**

### System Requirements

| Requirement | Details |
|---|---|
| Operating System | Windows 10 / Windows 11 |
| Architecture | 64-bit (x64) |
| Framework | .NET 10 |
| Video Processing | FFmpeg and FFprobe |
| Output Format | MP4 |

[View All Releases](https://github.com/MANOX2004/MSB-Status-Optimizer/releases)

---

## 🚀 Installation

Follow these steps to install MSB Status Optimizer.

### 1. Download the Installer

Download the latest setup file:

[MSBStatusOptimizerSetup-1.0.0.exe](https://github.com/MANOX2004/MSB-Status-Optimizer/releases/download/v1.0.0/MSBStatusOptimizerSetup-1.0.0.exe)

### 2. Install the Application

- Open the downloaded installer.
- Follow the installation instructions.
- Launch MSB Status Optimizer after installation.

### 3. Install FFmpeg and FFprobe

MSB Status Optimizer requires two external tools:

- **FFmpeg** – Handles video encoding and processing.
- **FFprobe** – Reads video information and properties.

> ⚠️ Important: FFmpeg and FFprobe are not bundled with the application. They must be installed separately and made accessible to the application.

---

## 🎬 How to Use

Preparing a video is straightforward.

### Step 1 – Select Your Video

Open MSB Status Optimizer and select the video file you want to prepare for WhatsApp Status.

### Step 2 – Choose the Output Location

Select where you want the processed MP4 video to be saved.

### Step 3 – Choose an Optimization Mode

MSB Status Optimizer provides two processing modes.

### Automatic Size Mode

- Select Automatic Size mode.
- The application checks whether the video can be preserved without re-encoding.
- Compatible H.264/AAC MP4 streams are preserved whenever possible.
- Other videos are encoded at high quality.

### Custom Target Size Mode

- Select Custom Target Size mode.
- Enter your preferred output size.
- Choose a target between **1 MB and 100 MB**.
- The application uses two-pass H.264 encoding to target the selected file size.

### Step 4 – Process Your Video

Start processing and allow the application to prepare your MP4 video.

### Step 5 – Use Your Video

Once processing is complete, locate the saved MP4 file and upload it to your WhatsApp Status.

---

## 🔄 Update Notifications

MSB Status Optimizer checks GitHub Releases for a newer version whenever the application opens.

If an update is available, you can choose:

- **Update** – Opens the GitHub Releases page so you can download the newer version.
- **Later** – Dismisses the notification and continues using the current version.

Updates are **not installed automatically**. You remain in control of when to download and install a newer version.

[Check Available Releases](https://github.com/MANOX2004/MSB-Status-Optimizer/releases)

---

## 🔒 Privacy

Your privacy matters.

MSB Status Optimizer processes video files locally on your Windows computer.

- Videos are not uploaded to WhatsApp by the application.
- Videos are not uploaded to external servers by the application.
- Video processing takes place on your local computer.

The application only checks GitHub Releases for newer versions when it opens.

---

## ⚠️ Important Notes & Limitations

Please keep the following points in mind:

- WhatsApp may re-encode videos after you upload them.
- The final playback quality on WhatsApp may differ from the processed video.
- Custom target size mode involves a trade-off between file size and video quality.
- A smaller target size may require more compression and can reduce visual quality.
- Automatic Size mode preserves compatible H.264/AAC MP4 streams when possible. Other videos require encoding.
- FFmpeg and FFprobe must be installed separately.

**Note:** MSB Status Optimizer prepares your video before uploading. It cannot control how WhatsApp processes or displays the uploaded video.

---

## 🛠️ Troubleshooting

If you encounter a problem, try the following checks.

| Problem | What to Check |
|---|---|
| Application does not start | Check that your Windows installation meets the system requirements. |
| FFmpeg not found | Make sure FFmpeg is installed and accessible to the application. |
| FFprobe not found | Make sure FFprobe is installed and accessible to the application. |
| Video processing fails | Check that the input video exists and can be accessed. |
| Output file is not created | Check the output location and available disk space. |
| Custom target size is not achieved | Check the selected target size and try a different target. |
| Output quality is lower than expected | Consider using a larger target size or Automatic Size mode. |
| Update notification does not appear | Check your internet connection and visit the Releases page manually. |

If the problem continues, please report it through the repository's Issues section.

[Report a Problem on GitHub](https://github.com/MANOX2004/MSB-Status-Optimizer/issues)

---

## 🖼️ Screenshots

Application screenshots will be added here.

> [Add screenshot – Main Application Window]

> [Add screenshot – Automatic Size Mode]

> [Add screenshot – Custom Target Size Mode]

---

## 💻 Technology

| Component | Technology |
|---|---|
| Programming Language | C# |
| Desktop Framework | WPF |
| Runtime | .NET 10 |
| Video Processing | FFmpeg |
| Video Information | FFprobe |
| Platform | Windows 10/11 (x64) |

---

## 📄 License

MSB Status Optimizer is licensed under the **MIT License**, subject to the repository's LICENSE file.

See the [LICENSE](LICENSE) file for license details.

---

## 🔗 Links

- **GitHub Repository:** [MSB Status Optimizer](https://github.com/MANOX2004/MSB-Status-Optimizer)
- **Download:** [Latest Installer](https://github.com/MANOX2004/MSB-Status-Optimizer/releases/download/v1.0.0/MSBStatusOptimizerSetup-1.0.0.exe)
- **All Releases:** [GitHub Releases](https://github.com/MANOX2004/MSB-Status-Optimizer/releases)
- **Issues & Support:** [GitHub Issues](https://github.com/MANOX2004/MSB-Status-Optimizer/issues)

---

<p align="center">

**MSB Status Optimizer**

*Simple. Efficient. Local Video Processing.*

Made for preparing videos for WhatsApp Status.

</p>
