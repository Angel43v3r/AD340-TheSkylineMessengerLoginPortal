# The Skyline Messenger Login Portal
![Android Studio](https://github.com/Angel43v3r/AD340-Assignments-TheSkylineMessenger/blob/master/Android_Studio_icon.png)
## Assignment 9 - The Skyline Messenger App
### AD340 - Mobile Application Development
### North Seattle College (Spring 2026)
### Date: May 12, 2026


## Table Of Contents
1. [Objective](#objective)
2. [How to Use](#how-to-use)
3. [Version Control](#version-control-github)
4. [Contributing](#contributing)
5. [License](#license)


## Objective
A professional-grade login screen that remains responsive across different screen sizes. Learn nesting layouts, handling user input types, and managing image assets using Android Studio.


## How to Use
### Prerequisites
Make sure you have the following installed:
- **Visual Studio Code (VS Code)**
    - You can use any editor, VSC is recommended for this project. You can download from [VS Code official website](https://code.visualstudio.com/).

- **Android Studio**
    - **Android Studio** is required to run the app on an Android emulator or a physical device.
    - It provides the Android SDK, emulator, and build tools needed for React Native development.
    - You can download from the [Android Studio official website](https://developer.android.com/studio).

### Installation & Environment Setup
#### 1. Clone the Repository
   In the folder you want to save your project in, run:

```bash
git clone git@github.com:Angel43v3r/AD340-Assignment-TheSkylineMessengerLoginPortal.git
```

#### 2. Navigate to the app folder:

```
cd AD340-Assignment-TheSkylineMessengerLoginPortal
```

#### 3. Navigate to the folder
```
cd <Folder_Name>
```

#### 4. Now, let’s initialize a modern Android project template.

**STEP 1:** Open Android Studio and select `File` -> `New` -> `New Project`.

**STEP 2:** Choose `Empty Views Activity` (This is crucial!).

**STEP 3:** Configure the project:

**Name:** TheSkylineMessenger

**Package name:** com.example.theskylinemessenger

**Minimum SDK:** API 24 (Android 7.0) or higher.

**Build configuration language:** Kotlin DSL (build.gradle.kts).

**STEP 4:** Click Finish

- Wait for Gradle to finish "syncing" (this may take a few minutes on the first run).

### Assignment Instruction
Navigate to the activity_main.xml file
```
app/
 └── res/
      └── layout/
           └── activity_main.xml
```
#### Phase 1: The Blueprint (Layout Structure)
Your goal is to create a UI that looks consistent. Use **ConstraintLayout** as your parent container to position the main elements.

- **Logo Section:** Place an `ImageView` at the top. Use a placeholder icon from the Android Asset Studio (Vector Asset).

- **Input Fields:** Use two `TextInputLayout` components (from the Material Design library) containing `TextInputEditText`.

-- **Field 1:** Hint: "Email", InputType: `textEmailAddress`.

-- **Field 2:** Hint: "Password", InputType: `textPassword`.

- **The Action Button:** A `MaterialButton` centered horizontally with the text "Sign In".

#### Phase 2: Design & Styling
A login screen needs to feel "tappable" and clean. Apply the following attributes:

|**Element**|**Requirement**|
|----------------|--------------------------------------------------------------------------------------------------------|
|**Padding/Margins** | Use standard spacing (e.g., `16dp` or `24dp`) to avoid elements touching the screen edges.             |
|**Button Style**	   | Apply a corner radius of `8dp` and a custom background color (e.g., `#6200EE`).                        |
|**Typography**	     | Use a `TextView` above the inputs that says "Welcome Back" with a text size of `28sp` and bold weight. |
|**Images**	         | Ensure the `ImageView` has a `contentDescription` for accessibility.                                   |
 

#### Phase 3: The "Linear" Challenge (Footer)
At the bottom of your screen, create a "Sign Up" prompt. To practice different layout logic, use a **horizontal LinearLayout** for this specific section:

1. **TextView:** "Don't have an account?"

2. **TextView:** "Register Now" (Style this as bold and a different color to make it look like a link).

3. **Constraint:** Anchor this `LinearLayout` to the bottom of the parent container.

 

## Version Control (GitHub)
### GitHub Initial Setup
1. Open Android Studio
2. Select `File` -> `Git` -> `Share Project On GitHub`

### To Commit:
Select `File` -> `Git` -> `GitHub` -> Commit

### To Push:
Select `File` -> `Git` -> `GitHub` -> Pull

### To Pull:
Select `File` -> `Git` -> `GitHub` -> Pull


## Contributing
Developed By: **Jovy Ann Nelson**

Instructor: **BC Ko**

Course: **AD340 - Mobile Application Development**

College: **North Seattle College**

Term: **Spring 2026**

Date: **May 3, 2026** to **May 12, 2026**


## License

This project is licensed under the MIT License. Please refer to the [LICENSE](https://github.com/Angel43v3r/AD340-Assignment-TheSkylineMessengerLoginPortal/blob/main/LICENSE) for more details.
