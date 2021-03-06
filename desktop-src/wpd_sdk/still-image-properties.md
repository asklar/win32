---
Description: Windows Portable Devices supports the following still-image properties.
ms.assetid: 0b5a126c-5064-48e5-a635-00c3e9ab6a2c
title: Still Image Properties
ms.topic: reference
ms.date: 05/31/2018
topic_type: 
- APIRef
- kbSyntax
api_name: 
- Still
api_type: 
- HeaderDef
api_location: 
- PortableDevice.h
---

# Still Image Properties

Windows Portable Devices supports the following still-image properties.



| Property                                                                                                                                                       | VarType        | Description                                                                                                                                                                                                                                                                                                                  |
|----------------------------------------------------------------------------------------------------------------------------------------------------------------|----------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **WPD\_STILL\_IMAGE\_ARTIST**                                                                                                                                  | **VT\_LPWSTR** | The name of the owner/user of the device.                                                                                                                                                                                                                                                                                    |
| <span id="wpd_still_image_burst_interval"></span><span id="WPD_STILL_IMAGE_BURST_INTERVAL"></span>**WPD\_STILL\_IMAGE\_BURST\_INTERVAL**                       | **VT\_UI4**    | In a burst-mode image capture, the time delay between image captures, in milliseconds.                                                                                                                                                                                                                                       |
| <span id="wpd_still_image_burst_number"></span><span id="WPD_STILL_IMAGE_BURST_NUMBER"></span>**WPD\_STILL\_IMAGE\_BURST\_NUMBER**                             | **VT\_UI4**    | In a burst-mode image capture, the number of images to capture.                                                                                                                                                                                                                                                              |
| **WPD\_STILL\_IMAGE\_CAPTURE\_DELAY**                                                                                                                          | **VT\_UI4**    | Specifies the time delay between the command to capture an image and the actual capture, in milliseconds.                                                                                                                                                                                                                    |
| **WPD\_STILL\_IMAGE\_CAPTURE\_FORMAT**                                                                                                                         | **VT\_CLSID**  | The format to use to capture the image. This is one of the [format GUID values](object-format-guids.md) that is defined by Windows Portable Devices.                                                                                                                                                                        |
| <span id="wpd_still_image_capture_mode"></span><span id="WPD_STILL_IMAGE_CAPTURE_MODE"></span>**WPD\_STILL\_IMAGE\_CAPTURE\_MODE**                             | **VT\_UI4**    | A [**WPD\_CAPTURE\_MODES**](wpd-capture-modes.md) enumerator that specifies the capture mode to use to capture an image.                                                                                                                                                                                                    |
| **WPD\_STILL\_IMAGE\_CAPTURE\_RESOLUTION**                                                                                                                     | **VT\_LPWSTR** | A string that specifies the image size to capture. The image size is specified in pixels, in the format "*width*x*height*". For example: "800x600".                                                                                                                                                                          |
| **WPD\_STILL\_IMAGE\_COMPRESSION\_SETTING**                                                                                                                    | **VT\_UI8**    | Describes the image compression settings that are used when capturing an image. This is device-specific.                                                                                                                                                                                                                     |
| **WPD\_STILL\_IMAGE\_CONTRAST**                                                                                                                                | **VT\_UI4**    | A number that specifies the contrast setting to apply when capturing an image, with zero being the least contrast and larger numbers indicating greater contrast.                                                                                                                                                            |
| **WPD\_STILL\_IMAGE\_DIGITAL\_ZOOM**                                                                                                                           | **VT\_UI4**    | A number that specifies the amount of digital zoom to use when capturing an image. The number is 1 or higher, scaled by a factor of 10. A value of 1 (representing 10) indicates no digital zoom; a value of 2 (representing 20) indicates a 2x zoom (1/4 of the image seen by a 1x zoom will be captured).                  |
| **WPD\_STILL\_IMAGE\_EFFECT\_MODE**                                                                                                                            | **VT\_UI4**    | A [**WPD\_EFFECT\_MODES**](wpd-effect-modes.md) enumerator that specifies an image effect to use when capturing an image.                                                                                                                                                                                                   |
| **WPD\_STILL\_IMAGE\_EXPOSURE\_BIAS\_COMPENSATION**                                                                                                            | **VT\_UI4**    | A number that specifies the APEX units to adjust the exposure. Units are stops x 1,000. Specifying zero indicates the factory default.                                                                                                                                                                                       |
| **WPD\_STILL\_IMAGE\_EXPOSURE\_INDEX**                                                                                                                         | **VT\_UI4**    | A number that specifies the ISO film speed to emulate when capturing an image. A value of 0xFFFF indicates that this value should be set automatically.                                                                                                                                                                      |
| **WPD\_STILL\_IMAGE\_EXPOSURE\_METERING\_MODE**                                                                                                                | **VT\_UI4**    | A [**WPD\_EXPOSURE\_METERING\_MODES**](wpd-exposure-metering-modes.md) enumerator that specifies the metering mode to use when capturing an image.                                                                                                                                                                          |
| <span id="wpd_still_image_exposure_program_mode"></span><span id="WPD_STILL_IMAGE_EXPOSURE_PROGRAM_MODE"></span>**WPD\_STILL\_IMAGE\_EXPOSURE\_PROGRAM\_MODE** | **VT\_UI4**    | A [**WPD\_EXPOSURE\_PROGRAM\_MODES**](wpd-exposure-program-modes.md) enumerator that specifies the exposure program to use when capturing an image.                                                                                                                                                                         |
| **WPD\_STILL\_IMAGE\_EXPOSURE\_TIME**                                                                                                                          | **VT\_UI4**    | The shutter speed to use when capturing an image, in seconds x 10,000.                                                                                                                                                                                                                                                       |
| **WPD\_STILL\_IMAGE\_FLASH\_MODE**                                                                                                                             | **VT\_UI4**    | A [**WPD\_FLASH\_MODES**](wpd-flash-modes.md) enumerator that specifies the flash mode to use when capturing an image.                                                                                                                                                                                                      |
| **WPD\_STILL\_IMAGE\_FNUMBER**                                                                                                                                 | **VT\_UI4**    | A number that specifies the aperture of the lens when capturing an image. The number is the f-stop number 100 (so 14 would indicate f/1.4).This property is typically only valid when [WPD\_STILL\_IMAGE\_EXPOSURE\_PROGRAM\_MODE](https://docs.microsoft.com/windows) is set to manual or aperture priority.<br/> |
| **WPD\_STILL\_IMAGE\_FOCAL\_LENGTH**                                                                                                                           | **VT\_UI4**    | The focal length, in millimeters x 100, to use when capturing an image. So, for example, 35mm would be 3500.                                                                                                                                                                                                                 |
| **WPD\_STILL\_IMAGE\_FOCUS\_DISTANCE**                                                                                                                         | **VT\_UI4**    | The focus distance that a device should use, in millimeters. A value of 0xFFFF indicates infinite focus (more than 655 meters).                                                                                                                                                                                              |
| **WPD\_STILL\_IMAGE\_FOCUS\_METERING\_MODE**                                                                                                                   | **VT\_UI4**    | A [**WPD\_FOCUS\_METERING\_MODES**](wpd-focus-metering-modes.md) enumerator that specifies which focus mode an image capture device should use when deciding how to focus on a subject.                                                                                                                                     |
| **WPD\_STILL\_IMAGE\_FOCUS\_MODE**                                                                                                                             | **VT\_UI4**    | A [**WPD\_FOCUS\_MODES**](wpd-focus-modes.md) enumerator that specifies the focus mode to use when capturing an image.                                                                                                                                                                                                      |
| **WPD\_STILL\_IMAGE\_RGB\_GAIN**                                                                                                                               | **VT\_LPWSTR** | A null-terminated string that specifies the RGB gain to use when capturing an image. The string is three colon-delimited numbers with no intervening spaces, in the format "*R*:*G*:*B*".                                                                                                                                    |
| **WPD\_STILL\_IMAGE\_SHARPNESS**                                                                                                                               | **VT\_UI4**    | A number that specifies the sharpness to use when capturing an image, where zero is the least sharp and larger numbers indicate increasing sharpness.                                                                                                                                                                        |
| <span id="wpd_still_image_timelapse_interval"></span><span id="WPD_STILL_IMAGE_TIMELAPSE_INTERVAL"></span>**WPD\_STILL\_IMAGE\_TIMELAPSE\_INTERVAL**           | **VT\_UI4**    | The time delay between image captures in a time-lapse image capture, in milliseconds.                                                                                                                                                                                                                                        |
| <span id="wpd_still_image_timelapse_number"></span><span id="WPD_STILL_IMAGE_TIMELAPSE_NUMBER"></span>**WPD\_STILL\_IMAGE\_TIMELAPSE\_NUMBER**                 | **VT\_UI4**    | The number of images to capture in a time-lapse mode image capture.                                                                                                                                                                                                                                                          |
| **WPD\_STILL\_IMAGE\_UPLOAD\_URL**                                                                                                                             | **VT\_LPWSTR** | Specifies a URL where the device should send the image after it is captured.                                                                                                                                                                                                                                                 |
| **WPD\_STILL\_IMAGE\_WHITE\_BALANCE**                                                                                                                          | **VT\_UI4**    | A [**WPD\_WHITE\_BALANCE\_SETTINGS**](wpd-white-balance-settings.md) enumerated value that specifies the white balance settings to use when capturing an image.                                                                                                                                                             |



 

## Requirements



|                   |                                                                                             |
|-------------------|---------------------------------------------------------------------------------------------|
| Header<br/> | <dl> <dt>PortableDevice.h</dt> </dl> |



## See also

<dl> <dt>

[**WPD Properties and Attributes**](properties-and-attributes.md)
</dt> </dl>

 

 




