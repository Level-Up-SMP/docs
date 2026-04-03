# Modpack Setup Guide

## Requirements

- [CurseForge App](https://www.curseforge.com/download/app) installed
- Java 21 ([Eclipse Temurin](https://adoptium.net/temurin/releases/?version=21) _recommended_)

---

## Step 1 — Import the Modpack

1. Download the **Level Up SMP** `.zip` file from the Discord server
2. Open the **CurseForge App**
3. Click **My Modpacks** in the left sidebar
4. Click the **Import** button in the top right
5. Navigate to the downloaded `.zip` file and select it
6. Wait for the import and mod download to complete

---

## Step 2 — Configure JVM Arguments

Once the modpack has finished importing:

1. Find **Level Up SMP** in your modpack list
2. Click the **three dots (⋯)** menu on the modpack card
3. Select **Profile Options**
4. Scroll down to **Advanced Settings**
5. In the **Additional Arguments** field, paste the following:

    ```sh
    -XX:+UseZGC -XX:+ZGenerational --add-modules=jdk.incubator.vector
    ```

6. Click **Done**

---

## Step 3 — Launch

Click **Play** and enjoy Level Up SMP!

---

## Notes

- The JVM arguments above require **Java 21**. They will not work on older Java versions.
- If you are on **macOS**, omit `-XX:+UseZGC -XX:+ZGenerational` as ZGC has known issues on macOS. Your arguments would just be `--add-modules=jdk.incubator.vector`
- If you experience any issues, reach out in the Discord server.
