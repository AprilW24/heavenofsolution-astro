---
title: "6 Steps to Unlocking a Rooted Android Phone Without a Password"
description: "If you've forgotten the password, PIN, or pattern lock on your rooted Android device, there's no need to worry. Having a rooted phone provides additional"
pubDate: "2024-06-26T07:26:16+07:00"
category: "Tools Apps"
featuredImage: "/wp-content/uploads/2024/06/HeavenofSolution_RootedPhone.jpg"
---

If you’ve forgotten the password, PIN, or pattern lock on your rooted Android device, there’s no need to worry. Having a rooted phone provides additional options to regain access without losing your important data. In this article, we’ll explore several methods to unlock your rooted phone when you’re locked out, all without needing to use any complex commands.

## The Advantage of Rooting for Unlocking

Rooting your Android phone grants you high-level administrative access to the operating system. This allows you to customize many aspects of the OS and access files that are normally restricted. When it comes to unlocking, rooting is a major advantage.

On a standard non-rooted device, unlocking options are limited if you forget your password. Usually you’re forced to perform a factory reset, which deletes all your personal data. However, with root access on your side, you can surgically remove just the lock screen password while keeping the rest of your apps and data untouched.

## Using a File Manager App

One of the easiest methods to unlock a rooted phone is by using a file manager app. For this to work, you need to have previously enabled USB debugging on your device and authorized your computer. Here are the steps:

1. **Download a root-enabled file manager** like MiXplorer onto your computer.

2. **Connect your locked phone to the computer** with a USB cable.

3. **Open the file manager app and grant it root access** when prompted.

4. Using the file manager, **navigate to the /data/system directory** on your phone.

5. **Look for and delete the following files**: password.key, gesture.key, locksettings.db, and locksettings.db-shm.

6. **Reboot your phone**. After it restarts, your device should be unlocked!

By deleting these key password files, you’re essentially removing the lock screen security. With the lock screen gone, you can access your phone’s interface and data without needing to enter a password.

## Flashing a Custom Recovery

If you didn’t enable USB debugging beforehand, you can still unlock your rooted phone by flashing a custom recovery. This process is a bit more technical but doesn’t require any commands. First, you’ll need to download the TWRP recovery image that matches your specific device model.

### 1. Booting into Fastboot Mode

With the TWRP image ready, you now need to boot your phone into bootloader/fastboot mode. The button combination differs between manufacturers, but generally involves holding a volume button and the power button simultaneously as the device boots up.

### 2. Flashing the Custom Recovery

Once you’re in fastboot mode, connect the phone to your computer with a USB cable. On your computer, use a flashing tool to install the TWRP image to your phone’s recovery partition. This will replace the stock recovery with TWRP.

### 3. Deleting Password Files in TWRP

After flashing is complete, use the volume buttons to select the **Recovery mode** option and boot into TWRP. In TWRP, tap on the **Advanced** button and then select **File Manager**. Using the file manager, navigate to the /data/system/ directory and delete the same password files as in the previous method: password.key, gesture.key, locksettings.db, and locksettings.db-shm.

### 4. Rebooting Your Unlocked Phone

Once you’ve deleted the password files, tap the **Reboot** button and select **System**. Your phone will restart and boot up unlocked, without the old password!

## Conclusion

As you can see, rooting your Android phone provides powerful options to unlock it if you get locked out. Whether using a USB file manager or booting a custom recovery, you can delete the lock screen security and access your device without losing data.

The key is to think ahead and enable USB debugging or install a custom recovery before you encounter any lock screen issues. With these unlocking methods in your toolkit, you can have peace of mind knowing that you can always get back into your rooted phone!