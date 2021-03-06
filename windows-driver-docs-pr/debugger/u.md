---
title: U (Windows Debugger Glossary)
description: Glossary page - U
Robots: noindex, nofollow
ms.assetid: f3866ed9-eb94-4433-8a73-3b37f7e67303
ms.author: windowsdriverdev
ms.date: 11/28/2017
ms.topic: article
ms.prod: windows-hardware
ms.technology: windows-devices
---

# U


<span id="user_mode"></span><span id="USER_MODE"></span>**user mode**  
Applications and subsystems run within Windows in *user mode*. Processes that run in user mode do so within their own virtual address spaces. They are restricted from gaining direct access to many parts of the system, including system hardware, memory that was not allocated for their use, and other portions of the system that might compromise system integrity. Because processes that run in user mode are effectively isolated from the system and other user-mode processes, they cannot interfere with these resources.

User-mode processes can be grouped in the following categories:

-   System Processes

    These perform important functions and are integral part of the operating system. System processes include such items as the logon process and the session manager process.

-   Server Processes

    These are operating system services such as the Event Log and the Scheduler. They can be configured to start automatically at boot time.

-   Environment Subsystems

    These are used to create a complete operating system environment for the applications. Windows provides the following three environments: Win32, POSIX, and OS/2.

-   User Applications

    There are five types: Win32, Windows 3.1, Microsoft MS-DOS, POSIX, and OS/2.

<span id="user_mode_debugging"></span><span id="USER_MODE_DEBUGGING"></span>**user-mode debugging**  
A debugger session in which the target is running in user mode.

<span id="user_mode_target"></span><span id="USER_MODE_TARGET"></span>**user-mode target**  
See target application.

 

 

[Send comments about this topic to Microsoft](mailto:wsddocfb@microsoft.com?subject=Documentation%20feedback%20[debugger\debugger]:%20U%20%20RELEASE:%20%285/15/2017%29&body=%0A%0APRIVACY%20STATEMENT%0A%0AWe%20use%20your%20feedback%20to%20improve%20the%20documentation.%20We%20don't%20use%20your%20email%20address%20for%20any%20other%20purpose,%20and%20we'll%20remove%20your%20email%20address%20from%20our%20system%20after%20the%20issue%20that%20you're%20reporting%20is%20fixed.%20While%20we're%20working%20to%20fix%20this%20issue,%20we%20might%20send%20you%20an%20email%20message%20to%20ask%20for%20more%20info.%20Later,%20we%20might%20also%20send%20you%20an%20email%20message%20to%20let%20you%20know%20that%20we've%20addressed%20your%20feedback.%0A%0AFor%20more%20info%20about%20Microsoft's%20privacy%20policy,%20see%20http://privacy.microsoft.com/default.aspx. "Send comments about this topic to Microsoft")




