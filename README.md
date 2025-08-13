## Andeoid Studio Environment Setup 
 
- **Tools Installed**: Android Studio 2023.2.1, Java 17, Android SDK 34
  
- **Tutorials Completed**: Basic layouts, activities  

# procedure:

step-by-step procedure to set up Android Studio on your computer (Windows/macOS/Linux):

# Step 1: Check System Requirements

- Before installing, ensure your system meets the minimum requirements:

- Windows: 64-bit OS (Windows 10/11), 8 GB RAM (16 GB recommended), 4 GB disk space.

- **macOS**: macOS 10.14 (Mojave) or later, 8 GB RAM (16 GB recommended).

- **Linux**: 64-bit distribution, GNOME/KDE desktop, 8 GB RAM, 4 GB disk space.

# Step 2: Download Android Studio

- Go to the official Android Studio website:

👉 https://developer.android.com/studio

- Click "Download Android Studio" (for your OS).

# Step 3: Install Android Studio

- Run the downloaded .exe file.

- Follow the setup wizard (keep default settings unless you know what you're changing).

- Check "Android Virtual Device" (AVD) for emulator support.

- Complete installation and click "Finish".

# Step 4: Set Up Android Studio for the First Time

- Launch Android Studio.

- Select "Do not import settings" (if first-time install).

- Choose a UI theme (Light/Dark).

- Click "Next" and let it download necessary SDK components (may take time).

- Select "Standard" setup (recommended for beginners).

- Verify installation settings and click "Finish".

# Step 5: Install SDK & Tools

- After setup, go to Tools → SDK Manager.

- Ensure the latest Android SDK and Build Tools are installed.

- Select the Android version(s) you want to develop for (e.g., Android 14 (API 34)).

- Click "Apply" and wait for downloads to complete.

# Step 6: Configure Emulator (Optional)

- Go to Tools → Device Manager.

- Click "Create Device" and select a phone model (e.g., Pixel 6).

- Download a system image (e.g., Android 14, API 34).

- Click "Finish" and start the emulator.

# Step 7: Create Your First Project

- Click "New Project".

- Choose a template (e.g., "Empty Activity").

**Configure:**

- Name: my first Application.

- Package name: e.g., com.example.myapp.

- Save location: Where to store the project.

- Language: Kotlin (recommended) or Java.

- Minimum SDK: Select based on your target audience.

- Click "Finish".

# Step 8: Run Your App

- Connect an Android phone (enable USB Debugging in Developer Options) OR use the emulator.

- Click the green play button (▶) in the toolbar.

- Select your device/emulator and click "OK".
