# Linux Driver Tutorial

Here you can find examples for simple Linux Kernel Modules and Linux Drivers.

## Preparation

I used a Raspberry Pi 3 to develop and test my modules and drivers. To compile them, you need to install the Kernel headers on your Pi. On Raspbian you can do this with the following command:

```bash
sudo apt update
sudo apt install raspberrypi-kernel-headers
```

Raspberry Pi OS is only installs the latest kernel headers. So, make sure, you are running the latest kernel. You can do this by running: 

```bash
sudo apt upgrade
```

You also need the build utils (make, gcc, ...) but they come preinstalled on Raspbian.

## Content

In this repo you can find examples for:
1. Simple Kernel Module
2. Device Numbers and Device Files
3. Create device file in driver and callbacks
4. GPIO Driver (DEPRECATED - from kernel 6.6 configuring GPIOs must be done via the device tree)
5. Text LCD Driver
6. PWM Module
7. Temperature Sensor (I2C)
8. Timer in Linux Kernel Modules
9. High Resolution Timer in Linux Kernel Modules
10. Accessing SPI with a Linux Kernel Module (BMP280 sensor again)
11. Using a GPIO Interrupt in a Linux Kernel Module
12. Using Parameters in a Linux Kernel Module
13. IOCTL in a Linux Kernel Module
14. Threads in a Linux Kernel Module
15. Sending a signal from a Linux Kernel Module to an userspace application
16. The poll callback
17. Waitqueues in a Linux Kernel Module
18. Create procfs entries from a Linux Kernel Module
19. Create sysfs entries from a Linux Kernel Module
20. Parse the device tree from a Linux Kernel Module to get the deivce properties of a specific device
21. Device Tree GPIO Driver 
22. Device Tree Driver for I2C Device
23. Dynamical memory management in a Linux Kernel module
24. Serial (UART) Driver
25. Industrial IO compatible driver for an ATMEGA I2C ADC
26. Device Tree SPI Driver (IIO compatible driver for Atmega SPI ADC)
27. Misc Device
28. Mutex for exclusive access to shared resource
29. Completions for synchronisation
30. Direct Memory Access (DMA) memcopy example
31. Accessing files form a Linux Driver
32. The mmap callback
33. Linked Lists
34. Registering device numbers, read and write callback in character devices Take 2
35. Private Data in struct file
36. I2C Device Driver without Device Tree 
37. Sysfs Class
38. Kernel Log levels


## More Information

For more information about my Linux Driver examples check out my [videos and my playlist](https://www.youtube.com/watch?v=x1Y203vH-Dc&list=PLCGpd0Do5-I3b5TtyqeF1UdyD4C-S-dMa)

## Support me

If you want to support me, you can buy me a coffee [buymeacoffee.com/johannes4linux](https://www.buymeacoffee.com/johannes4linux).
