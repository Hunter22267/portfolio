# How to Fix Headphones That Have No Sound in Windows 11

Your headphones aren’t making any sound. Don’t worry — this is usually not caused by a broken pair of headphones.

Work through these fixes in order, starting with the simplest checks.

Quick fix:

- Click the speaker icon in your taskbar.
- Select your headphones from the list.

## 1. Select Your Headphones as the Output Device

This problem is most often an output issue.

Windows may be sending audio to your PC speakers, monitor, or another connected device.

- Click the speaker icon in the bottom-right corner of your taskbar.
- Make sure your headphones are selected as the output device.
- Play some audio to check whether sound is restored.

*For more options, such as per-app volume or enhancements, go to Settings → System → Sound.*

## 2. Check the Volume Mixer

Windows can use separate volume and output settings for individual applications.

- Open Settings → System → Sound → Volume mixer.
- Check the application that has no sound.
- Make sure all of the following are true:
  - The system volume is turned up and not muted.
  - The application volume is turned up and the app is not muted.
  - The app’s output device is set to your headphones.
- Test the audio again.

This is especially useful when other applications are playing sound normally.

## 3. Restart Windows or Run the Audio Troubleshooter

A restart can resolve temporary problems with audio devices and services.

- Select Start → Power → Restart.
- Test your headphones again.
- If the problem continues, run the built-in audio troubleshooter:
  - Go to Settings → System → Troubleshoot → Other troubleshooters.
  - Find Playing Audio and select Run.
  - Follow the prompts.

The troubleshooter can identify common audio problems and may apply a fix automatically.

## 4. Reconnect or Re-pair Your Headphones

### Wired headphones

- Unplug the headphones and reconnect them securely.
- If possible, try another compatible headphone jack or USB port.
- This can help determine whether the original connection is causing the issue.

### Bluetooth headphones

- Make sure Bluetooth is working correctly.
  - Toggle Bluetooth on and off in Settings.
- If there is still no sound, remove and re-pair the headphones:
  - Go to Settings → Bluetooth & devices.
  - Locate your headphones.
  - Select More options (…) → Remove device.
  - Select Add device and pair the headphones again.

Microsoft also recommends running the Bluetooth troubleshooter in the Get Help app when Bluetooth audio problems persist.

## 5. Turn Off Audio Enhancements

Audio enhancements can interfere with playback on some devices.

- Go to Settings → System → Sound.
- Select your headphones under Output.
- Find Audio enhancements.
- If the setting is available, turn enhancements off.
- Test the audio again.

## 6. Restart the Windows Audio Services

Restarting Windows audio services can resolve temporary problems that prevent applications from playing sound.

- Press Windows + R.
- Enter services.msc and press Enter.
- Find Windows Audio.
- Right-click it and select Restart.
- Find Windows Audio Endpoint Builder.
- Right-click it and select Restart.
- Test your headphones again.

Microsoft recommends restarting these services when application audio is not working correctly.

## 7. Update or Reinstall Your Audio or Bluetooth Drivers

Outdated, incompatible, or corrupted drivers can prevent Windows from sending audio to a connected device.

### Start with Windows Update

- Go to Settings → Windows Update.
- Select Check for updates.
- Install any available updates.
- Restart your PC.

### Check for driver updates manually

- Open Device Manager.
- Expand Sound, video and game controllers.
- Right-click the relevant audio device.
- Select Update driver → Search automatically for drivers.
- Restart the PC.

For Bluetooth headphones, also expand Bluetooth and check the Bluetooth adapter for driver updates.

If updating the driver does not resolve the problem, uninstall the affected device in Device Manager and reinstall the latest driver from your PC or the audio-device manufacturer’s support website. Use the driver intended for your specific Windows 11 device.

### Advanced Bluetooth fix: Check the audio format

- Go to Settings → Bluetooth & devices → Devices.
- Select your connected headphones.
- Open Advanced sound properties.
- Under Output settings, check the available Format options.
- Try 2 channels, 16 bit, 48000 Hz (DVD Quality).

The Advanced sound properties option appears only while the Bluetooth device is connected.

## 8. Test the Headphones on Another Device

Testing the headphones on another device can help determine whether the problem is with the headphones or the Windows PC.

- Try the headphones on another computer, phone, or compatible device.
- Then try another pair of headphones on the Windows PC.

The results can narrow down the cause:

- If your headphones work on another device but no headphones work on the PC, the issue is more likely on the PC side, such as Windows audio settings, a driver, the Bluetooth adapter, or the headphone jack.
- If another pair of headphones works normally on the PC, the issue is more likely specific to the original headphones or their connection.

## Frequently Asked Questions

### Why does Windows say my headphones are connected but there is no sound?

- Windows may be using a different output device.
- The affected application may have its own volume or output setting.
- An audio or Bluetooth driver may be preventing playback.

### Why do my Bluetooth headphones connect but not play sound?

- Confirm that the headphones are selected under Settings → System → Sound → Output.
- Restart Bluetooth.
- If needed, remove and re-pair the headphones.
- Check the Bluetooth device’s advanced audio format settings.

### Why do my headphones work on my phone but not my PC?

- If the headphones work on another device, that suggests the headphones themselves are functioning.
- Check the Windows output device, Volume mixer, Bluetooth connection, audio services, and drivers on the PC.

### What should I do if none of these fixes work?

- The problem may involve the PC’s audio hardware, Bluetooth adapter, headphone jack, or a device-specific driver.
- At that point, consult your PC or headphone manufacturer’s support documentation for model-specific troubleshooting and drivers.
