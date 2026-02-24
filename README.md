# CS501 IA3 - Q2 Box Layout: Profile Header + Overlay Card

**Student:** Wenhao Wang  
**Assignment:** Individual Assignment 3 (Q2)  
**Question:** Box Layout: Profile Header + Overlay Card

## Overview
This project implements a profile-style header screen using **Box layering** in Jetpack Compose and Material 3.

The layout demonstrates:
- layered header background
- circular avatar
- overlapping profile card ("profile card" effect)

---

## Q2 Requirements Addressed

### Layout Requirements
- ✅ Uses a **Box** to create layered UI
- ✅ Includes:
  - background header area (solid / gradient-like style using `Box` + `background`)
  - foreground avatar with circular shape
  - overlay `Card` partially overlapping the header
- ✅ Uses `contentAlignment`, `align(...)`, and `offset(...)` intentionally for placement

### Material 3 Requirements (5+ components)
This screen uses Material 3 components including:
- `TopAppBar`
- `Card`
- `Icon`
- `Button`
- `FilledTonalButton`
- `AssistChip`
- `Surface`
- `Text`

### Modifier Requirements
This screen demonstrates:
- `clip(CircleShape)` for avatar
- `offset(...)` (or overlap positioning approach)
- `zIndex(...)` (if needed for layering)
- card shadow/elevation via `CardDefaults.cardElevation(...)`
- fixed size and/or `aspectRatio(...)`

---

## Implementation Notes
- The avatar is visually separated from the background using shape + elevation/layering.
- The overlay card is intentionally positioned to overlap the header area.
- The screen emphasizes Box-based composition and visual polish.

---

## Screenshot
![Q2 Screenshot](Q2.png)

---

## How to Run
1. Open the project in **Android Studio**
2. Sync Gradle if prompted
3. Run on an emulator or Android device
4. Make sure `MainActivity.kt` displays the Q2 screen composable

---

## AI Disclosure
I used ChatGPT as a coding assistant for: debugging Compose modifiers (e.g., offset, zIndex, clip)
---

## Repository Link
<!-- Replace with your actual Q2 repo link -->
https://github.com/JefferyWenhaoWang/cs501-ia3-q2
