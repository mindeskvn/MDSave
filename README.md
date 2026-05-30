# MDSave - Download Social Videos (Multi-Platform)

Languages: 🇺🇸 **English** | [🇻🇳 **Tiếng Việt**](README.vi.md)

---

A client-side multimedia analysis and download application for major social media platforms, optimized for performance, safety, and security.

### Application Screenshot
![MDSave App Screenshot](preview.png)

### Key Features & Integrated Technologies
- **Modern User Interface**: Built on the PyQt5 framework, offering a smooth interactive experience and highly optimized layouts for download management.
- **High-Performance Multi-threaded Networking**: Combines advanced HTTP transmission techniques (using `curl_cffi` to mimic modern browser TLS fingerprints) with a parallel multi-threaded download engine (`aria2c`), maximizing bandwidth and achieving ultra-fast download speeds.
- **Intelligent Request Optimization**: Automatically structures and optimizes HTTP requests, safely navigating rate limits and security layers without compromising user data.
- **Asynchronous Task Queue**: A robust multi-threaded architecture manages parallel downloads seamlessly, keeping the UI responsive and stable even during large-scale batch tasks.
- **Secure Local Storage**: Features a lightweight local database to track download histories, supporting fast search filtering and task recovery.

### How to Use
1. Extract the downloaded `MDSave.zip` file from the [Releases](https://github.com/mindeskvn/MDSave/releases) page.
2. Run the `Setup.bat` file to automatically configure and install the required environment and libraries.
3. Once the installation is complete, double-click the `main.exe` file to start using the application.
