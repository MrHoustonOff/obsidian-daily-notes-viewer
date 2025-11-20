# Daily Notes Viewer for Obsidian

A robust, native-feeling sidebar plugin for managing your daily knowledge workflow. 

**Daily Notes Viewer** provides a calendar-centric interface to visualize your activity. Instantly see which notes were **Created** or **Updated** on any specific day, organized in a clean, sortable list with color-coding capabilities.

![Interface Screenshot](https://via.placeholder.com/800x400?text=Screenshots+Coming+Soon)

## Key Features

### 📅 Interactive Calendar
- **Grid Layout:** A clean, responsive 7-column calendar that adapts to your sidebar width.
- **Native Design:** Built using Obsidian's CSS variables, ensuring it looks perfect in Light Mode, Dark Mode, and with any custom theme.
- **Seamless Navigation:** Jump between months and years effortlessly.

### 🗂 Activity Tracking
Select any date to view activity for that specific day:
- **Created Today:** Notes created on the selected date.
- **Updated Today:** Notes modified on the selected date.
- **Smart Sorting:** Files are automatically sorted from newest to oldest.
- **Collapsible Lists:** Keep your view tidy by expanding or collapsing sections.
- **Active File Highlighting:** The currently open note is highlighted in the list for better context.

### 🎨 Color Coding & Organization
Mark important notes visually directly from the sidebar:
- **Right-Click Context Menu:** Assign colors to specific notes via a native context menu.
- **Visual Indicators:** Colored borders and icons make high-priority notes stand out instantly.
- **Smart Persistence:** Colors differ from standard frontmatter tags. They are stored internally and **migrate automatically if you rename or move the file**.

### ⚙️ Customization
- **Color Palette:** Define your own set of custom colors in the plugin settings.
- **Palette Management:** Add, remove, or edit hex codes to match your personal workflow.
- **Reset Option:** Easily restore default settings if needed.

## Installation

### From Community Plugins
1. Open **Settings** > **Community Plugins** in Obsidian.
2. Turn on **Restricted Mode** (if not already).
3. Click **Browse** and search for `Daily Notes Viewer`.
4. Click **Install** and then **Enable**.

### Manual Installation
1. Download the latest `main.js`, `manifest.json`, and `styles.css` from the [Releases](https://github.com/yourusername/daily-notes-viewer/releases) page.
2. Create a folder named `daily-notes-viewer` inside your vault's `.obsidian/plugins/` directory.
3. Move the downloaded files into that folder.
4. Reload Obsidian and enable the plugin.

## Usage

1. Click the **Calendar Icon** in the right ribbon to open the view.
2. **Click a date** on the calendar to filter notes.
3. **Click a file** in the list to open it.
4. **Right-click a file** in the list to assign a color label.

## Development

If you want to contribute or modify the plugin:

```bash
# 1. Clone the repository
git clone [https://github.com/yourusername/daily-notes-viewer.git](https://github.com/yourusername/daily-notes-viewer.git)

# 2. Install dependencies
npm install

# 3. Build in watch mode (auto-updates main.js)
npm run dev

# 4. Build for production
npm run build
```

License
MIT
---