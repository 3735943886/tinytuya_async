## tinytuya_async

**`tinytuya_async`** is a minimal, **`asyncio`** implementation derived from the popular `tinytuya` library.

The main `tinytuya` project is currently preparing for a major version **2.0** release with **native async support**. This effort involves significant changes to support the wide variety of devices, protocol versions, new features like callbacks, and device type handling already supported by `tinytuya`, which will take time.

Therefore, **`tinytuya_async`** is a **minimal change** library that focuses only on replacing the core **socket I/O** of a single device with an asynchronous implementation (`DeviceAsync`). This repository is intended to be used as a stopgap solution until the official `tinytuya` 2.0 release is available.

-----

### Project Status & Maintenance Notice

> ⚠️ **Important Notice:** This repository is a **temporary stopgap** created solely to provide basic async functionality until the official `tinytuya 2.0` release is available. 
>
> * **Not Actively Maintained:** This project is not actively maintained, and there are no plans to add new features or provide ongoing support.
> * **Provided AS-IS:** The code is provided strictly "as-is." If you encounter bugs or require additional Tuya protocol features, we highly encourage you to contribute via Pull Requests or look forward to the upcoming official `tinytuya` v2.0.

-----

### Installation

Install the library using pip:

```bash
pip install tinytuya-async
```
