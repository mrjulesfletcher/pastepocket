# PastePocket
A MacOS clipboard tool

Copyright © 2025 Jules Le Masson Fletcher.
All rights reserved.

**PastePocket** is an elegant and powerful clipboard manager for macOS that transforms the way you work with copied content. Living in your menu bar, PastePocket continuously monitors your system clipboard and saves every item you copy—be it text, files, images, links, or more. With this tool, you can copy as many items as you want throughout your day and then, whenever you need them, quickly browse your entire history and paste the exact snippet or file you’re looking for.

More than just a clipboard manager, PastePocket offers a revolutionary workflow that seamlessly blends note‑taking and bookmarking. Whether you’re saving important files, links, or texts, PastePocket lets you capture and organize your data so that nothing is ever lost—and everything is just a click away when you’re ready to paste or access it.

## Features

- **Top‑Bar Clipboard Manager:**  
  Runs as a lightweight, menu‑bar–only app that stays out of your Dock.

- **Real-Time Clipboard Monitoring:**  
  Continuously tracks your clipboard and stores copied text, files, images, and links.

- **File & Multi‑File Support:**  
  - **Single File:** Displays the file’s icon, full file path, and size.  
  - **Multiple Files:** Aggregates multiple files into a single item (e.g. "Multiple files (3, 2.1 MB)") and shows previews for all files when you hover over the item.

- **Clickable Links:**  
  If an item is a valid URL, it is displayed as a clickable link that opens in your default browser. Hovering over link items shows an expanded link preview.

- **Source Application Information:**  
  Each clipboard item records the source application (e.g. Finder, Chrome, TextEdit) from which the copy occurred.

- **Actions and Management:**  
  - **Pinning:** Keep important items at the top of your history.  
  - **Deletion:** Remove items you no longer need.  
  - **Clear Unpinned:** Quickly remove all non‑pinned items.  
  - **Save Session:** Save your clipboard history to disk so that it can be restored later.

- **Visual Feedback:**  
  The header displays transient debug messages (e.g., "copied", "deleted", "pinned", "cleared", "saved") whenever you perform actions. The top‑bar icon also blinks when a new item is copied.

- **Expanded View:**  
  Easily expand the widget into a larger window for enhanced viewing, then collapse back to the compact popover.

- **Integrated Note‑Taking and Bookmarking:**  
  Beyond traditional clipboard management, PastePocket lets you capture and organize a wide range of content—from text snippets to files and links—acting as both a clipboard manager and a bookmarking tool in one.


## Installation

1. **Download the Release:**  
   - Visit the [GitHub Releases](https://github.com/mrjulesfletcher/PastePocket/releases) page and download the latest exported binary (e.g. a ZIP file or DMG).

2. **Install the App:**  
   - Unzip (or open) the downloaded file and drag **PastePocket.app** into your Applications folder.

3. **Launch PastePocket:**  
   - Run PastePocket. It will appear as an icon in your macOS menu bar.
   ![Open Anyway instructions](https://raw.githubusercontent.com/mrjulesfletcher/pastepocket/refs/heads/main/install_open_anyway.png)

   *Note: If you see a warning that “PastePocket.app was blocked from opening because it is not from an identified developer,” right‑click (or Control‑click) the app in Finder and choose **Open**. Then, in System Preferences > Security & Privacy > General, click **Open Anyway**.*


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

