# pastepocket
PastePocket, as MacOS clipboard tool

Copyright © 2025 Jules Le Masson Fletcher.
All rights reserved.

# PastePocket

**PastePocket** is a powerful, elegant top‑bar clipboard manager for macOS. It monitors your system clipboard in real time, maintains a history of your copied items (including text and files), and provides advanced features such as file previews, source app identification, and session saving—all from your menu bar.

## Features

- **Top‑Bar Clipboard Manager:**  
  Runs as a lightweight, menu‑bar–only app that stays out of your Dock.

- **Real-Time Clipboard Monitoring:**  
  Continuously tracks your clipboard and stores copied text, files, and folders.

- **File & Multi‑File Support:**  
  - For file items, displays the file’s icon, full file path, and size.  
  - For multiple file copies, aggregates them into a single item with a summary (e.g. "Multiple files (3, 2.1 MB)") and shows previews for all files when you hover over the item.

- **Source Application Information:**  
  Each ClipboardItem records the source app (e.g. Finder, Chrome, TextEdit) where the copy occurred.

- **Actions and Management:**  
  - **Pinning:** Keep important items at the top of your history.  
  - **Deletion:** Remove items you no longer need.  
  - **Clear Unpinned:** Quickly clear out all non‑pinned items.  
  - **Save Session:** Save your clipboard history to disk so that it can be restored later.

- **Visual Feedback:**  
  The header displays transient debug messages (e.g., "copied", "deleted", "pinned", "cleared", "saved") whenever you perform actions. The top‑bar icon also blinks (alternates between two symbol states) when a new item is copied.

- **Expand/Collapse View:**  
  Easily expand the widget into a larger window for enhanced viewing, then collapse back to the compact popover.


## Installation

1. **Download the Release:**  
   - Visit the [GitHub Releases](https://github.com/mrjulesfletcher/PastePocket/releases) page and download the latest exported binary (e.g. a ZIP file or DMG).

2. **Install the App:**  
   - Unzip (or open) the downloaded file and drag **PastePocket.app** into your Applications folder.

3. **Launch PastePocket:**  
   - Run PastePocket. It will appear as an icon in your macOS menu bar.


## Usage

- **Clipboard History:**  
  Copy text, files, or folders in any application. PastePocket automatically adds each item to your clipboard history.

- **Viewing Clipboard Items:**  
  Left‑click the PastePocket menu‑bar icon to open the widget. Browse your history, which displays the copied content along with file icons (if applicable), source app information, and file size.

- **Multi‑File Previews:**  
  If an item represents multiple files, hover over it to reveal previews of all the files included.

- **Managing Items:**  
  Use the pin and delete icons on each row to manage your clipboard history.  
  Use the “Clear Unpinned” and “Save Session” buttons in the bottom toolbar to further manage your items.

- **Expand/Collapse View:**  
  Tap the expand/collapse icon in the bottom toolbar to open a larger window view of PastePocket.


## License

© 2025 Jules Le Masson Fletcher. All rights reserved.

This software is proprietary. You are granted a limited, non‑transferable license to use this application solely for personal use. Unauthorized copying, modification, distribution, or commercial exploitation is strictly prohibited without explicit written permission from the copyright holder.

## Contributing

This repository contains the exported binary for PastePocket. The source code is proprietary; however, if you have questions or suggestions regarding the app, feel free to contact jules.lemasson@gmail.com.

## Acknowledgments

PastePocket was created to provide an elegant, feature‑rich clipboard manager for macOS. Special thanks to the Apple Developer documentation and the SwiftUI community for guidance on building modern macOS apps.






This software and associated documentation files (the "Software") are the sole property of Jules Le Masson Fletcher and are provided for your personal, non-commercial use only. You may not reproduce, modify, distribute, or create derivative works of the Software without the prior written consent of Jules Le Masson Fletcher.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT.

