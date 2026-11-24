# PXPlay/ PSPlay Application Hosting

PXPlay is currently supported on Android, iOS, Apple TV, Windows 10/11, Linux x64 PCs and Mac Silicon/ Intel PCs.

## Key Features
- **Third-Party Controller Support**: Works with USB and Bluetooth controllers.
- **Bitrate Adjustments**: Manually adjust bitrate to optimize streaming quality.
- **Keyboard Support**: Offers basic keyboard functionality for navigation and gameplay.
- **Multiple Console Registration**: Allows registration of multiple consoles for easy switching.
- **Fullscreen Streaming Mode**: Fullscreen mode available with options to stretch and zoom without black bars.
- **Optimized User Interface**: User interface designed for easy navigation with both mouse and gamepad.
- **Advanced Decoding and Rendering**: Supports multiple decoder and rendering engines, including zero-copy rendering with image enhancement through Vulkan.
- **Optimized for Peak Streaming Performance**: Ensures a fast and stable streaming experience through extensive optimization and beta testing.


## Open Source Contributions
The development of PXPlay has been supported by several excellent open-source libraries:

- [JavaCV](https://github.com/bytedeco/javacv)
- [libplacebo](https://github.com/haasn/libplacebo)
- [OpenGLFX](https://github.com/husker-dev/openglfx)
- [LWJGL3](https://github.com/LWJGL/lwjgl3)
- [FFmpeg](https://github.com/FFmpeg/FFmpeg)

Parts of the PXPlay PC port, such as the Vulkan rendering pipeline and the gamepad handling via SDL2 through Jamepad, are open-sourced here:

- [libplacebo JNI project](https://github.com/streamingdv/libplacebo-jni)
- [Jamepad with D-Sense/ D-Shock features](https://github.com/grill2010/Jamepad)

## 3rd Party integration

For a launcher or frontend that wants to stream a PlayStation console through PXPlay you can find more information [here.](3rd_party_integration/THIRD_PARTY_LAUNCHER_API.md)


**Disclaimer:** This project is not endorsed or certified by Sony Interactive Entertainment LLC.
