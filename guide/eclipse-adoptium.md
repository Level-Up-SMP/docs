# Eclipse Adoptium Setup

This guide will walk you through the process of installing various versions of Eclipse Adoptium JDKs for use with Minecraft/CurseForge

## Why Eclipse Adoptium?

We use Eclipse Adoptium JDKs because they usually give Minecraft a smoother, more consistent experience than CurseForge's built-in Java. In practice, this often means fewer stutters or pauses during gameplay, especially with larger or heavier modpacks. These versions are also newer and regularly updated, so they include performance improvements, bug fixes, and security patches. Think of it as giving Minecraft a better foundation to run on, with minimal effort on your part.

## Obtaining the Installers

CurseForge currently supports Java versions **8**, **17**, **21**, and **25**.

Level Up SMP will be targeting Java 21, but it's recommended to repeat the process for all 4 versions so that you're covered in all cases for all modpacks.

You can find the installers required on Eclipse Adoptium's [releases](https://adoptium.net/temurin/releases) page.

1. On the releases page, select the Java version you wish to download.

    ![Select Version](/assets/img/eclipse-adoptium-selection.png)

2. Then click the download button for your platform

    ![Select Platform](/assets/img/eclipse-adoptium-platform.png)

## Installing the JDK

This portion of the guide will assume you are doing the installation on a Windows 10 or 11 system. If you need assistance with a macOS installation, please feel free to open a `Technical Support` request in the Discord.

1. Once the MSI executable is downloaded, you will need to run it. In many cases, this file will be found in the `Downloads` folder. The file will be named something like `OpenJDKXU-jdk_x64_windows_hotspot_X.X.X_X.msi`. Example below.

    ![Run Executable](/assets/img/eclipse-adoptium-msi.png)

2. Once you run the executable, you should see a dialog like this:

    ![Executable Window 1](/assets/img/executable-window-1.png)

    Click `Next` to continue.

3. From here you will see a window similar to the below. We will keep the defaults in 99% of cases:

    ![Executable Window 2](/assets/img/executable-window-2.png)

    Press `Next` again to continue.

4. Next, you will see a window similar to the below:

    ![Executable Window 3](/assets/img/executable-window-3.png)

    Press `Install` to continue.

5. After this window, it is expected that Window's UAC _(User Account Control)_ will pop-up and require approval. Click `Yes` or `Allow` to continue. In the event that you believe the installation is "stuck," you may see a window like the below:

    ![Executable Window 4](/assets/img/executable-window-4.png)

    If the installer seems frozen, check your taskbar for a blinking icon, this is likely the UAC prompt waiting for your approval.

6. At this point, we will wait for the installation is complete. You should notice a status bar as it progresses. Once it's complete, you should see a window like the below:

    ![Executable Window 5](/assets/img/executable-window-5.png)

    ![Executable Window 6](/assets/img/executable-window-6.png)

## Configuring CurseForge

In this section, we'll configure CurseForge to use the newly installed Java version(s).

1. Next, you're going to open your CurseForge App. Once, it's open, select the gear wheel on the bottom left, this will open the `Settings` menu.

    ![CurseForge App 1](/assets/img/curseforge-app-1.png)

2. Next, you're going to select `Minecraft` from the settings panel on the left.

    ![CurseForge App 2](/assets/img/curseforge-app-2.png)

3. From here, you will scroll down until you find the `Java Versions` section. Here, select the `Choose` button next to the version of Java you installed in the previous section.

    ![CurseForge App 3](/assets/img/curseforge-app-3.png)

4. In this next step, a selection windows similar to the below will open. Ensure that you are inside of `C:\Program Files\`. From there, select the `Eclipse Adoptium` folder.

    ![Select Java 1](/assets/img/select-java-1.png)

5. You will then select the folder that matches the version of java installed in the previous steps like below.

    ![Select Java 2](/assets/img/select-java-2.png)

6. You will then select the `bin` folder.

    ![Select Java 3](/assets/img/select-java-3.png)

7. Inside of this folder, select the executable titled `java`. It may also appear as `java.exe` depending on your folder settings.

    ![Select Java 4](/assets/img/select-java-4.png)

8. The CurseForge `Java Versions` should now show the updated Java path.

    ![CurseForge App 4](/assets/img/curseforge-app-4.png)

## Wrapping Things Up

While a reboot isn't strictly required, it's _highly_ recommended. Please repeat the process for any other Java versions you wish to use the new JDK.
