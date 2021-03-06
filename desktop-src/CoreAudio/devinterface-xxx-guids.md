---
Description: The DEVINTERFACE\_XXX GUIDs are used to represent the GUIDs for device interfaces.
ms.assetid: 2503463B-D7C6-4C82-8421-424D79FD1C2A
title: DEVINTERFACE_XXX GUIDs
ms.topic: reference
ms.date: 05/31/2018
---

# DEVINTERFACE\_XXX GUIDs

The DEVINTERFACE\_XXX GUIDs are used to represent the GUIDs for device interfaces.

<dl> <dt>

<span id="DEVINTERFACE_AUDIO_CAPTURE"></span><span id="devinterface_audio_capture"></span>**DEVINTERFACE\_AUDIO\_CAPTURE**
</dt> <dd> <dl> <dt>



Specifies the query string used to enumerate all audio capture devices on the system. This value is returned by [**MediaDevice::GetAudioCaptureSelector**](https://docs.microsoft.com/uwp/api/windows.media.devices.mediadevice.getaudiocaptureselector).

Passing this value to [**ActivateAudioInterfaceAsync**](/windows/desktop/api/mmdeviceapi/nf-mmdeviceapi-activateaudiointerfaceasync) activates the requested interface on the default audio capture device.


</dt> </dl> </dd> <dt>

<span id="DEVINTERFACE_AUDIO_RENDER"></span><span id="devinterface_audio_render"></span>**DEVINTERFACE\_AUDIO\_RENDER**
</dt> <dd> <dl> <dt>



Specifies the query string used to enumerate all audio render devices on the system. This value is returned by [**MediaDevice::GetAudioRenderSelector**](https://docs.microsoft.com/uwp/api/windows.media.devices.mediadevice.getaudiorenderselector).

Passing this value to [**ActivateAudioInterfaceAsync**](/windows/desktop/api/mmdeviceapi/nf-mmdeviceapi-activateaudiointerfaceasync) activates the requested interface on the default audio render device.


</dt> </dl> </dd> <dt>

<span id="DEVINTERFACE_MIDI_INPUT"></span><span id="devinterface_midi_input"></span>**DEVINTERFACE\_MIDI\_INPUT**
</dt> <dd> <dl> <dt>



Specifies the query string used to enumerate all [**MidiInPort**](https://docs.microsoft.com/uwp/api/Windows.Devices.Midi.MidiInPort) objects on the system. This value is returned by [**MidiInPort::GetDeviceSelector**](https://docs.microsoft.com/uwp/api/windows.devices.midi.midiinport.getdeviceselector).


</dt> </dl> </dd> <dt>

<span id="DEVINTERFACE_MIDI_OUTPUT"></span><span id="devinterface_midi_output"></span>**DEVINTERFACE\_MIDI\_OUTPUT**
</dt> <dd> <dl> <dt>



Specifies the query string used to enumerate all [**MidiOutPort**](https://docs.microsoft.com/uwp/api/Windows.Devices.Midi.MidiOutPort) objects on the system. This value is returned by [**MidiOutPort::GetDeviceSelector**](https://docs.microsoft.com/uwp/api/windows.devices.midi.midioutport.getdeviceselector).


</dt> </dl> </dd> </dl>

## Requirements



|                   |                                                                                          |
|-------------------|------------------------------------------------------------------------------------------|
| Header<br/> | <dl> <dt>Mmdeviceapi.h</dt> </dl> |



 

 




