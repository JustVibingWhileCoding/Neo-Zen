# 🧩 Neo Zen Settings

A customizable suite of features and UI enhancements for browser theming, interaction, and workflow optimization.

---

## 🔧 Neo Features

### **General Settings**
- **Disable all Neo features**, reverting to the browser’s native layout and behavior while keeping **Neo Zen** styling intact.  
  `neo-features-disabled`

---

### **Neo Sidebar**
- **Disable Neo Sidebar**, including its custom background and alignment features.  
  `neo-features-sidebar-disabled`

---

### **Neo Bottom Section**
- **Disable the Neo Bottom section**, returning to default extension and toolbar behavior.  
  `neo-features-bottom-disabled`  
- **Keep the bottom section expanded** with scrollable behavior — allows up to two extra rows before scrolling is required.  
  `neo-features-bottom-keep-expanded`  
- **Move the bottom section to the bottom** (default is top).  
  `neo-bottom-at-bottom`  
- **Customize the height of the Neo Bottom in collapsed mode**  
  `neo-features-bottom-height`  
  Options: `120px` to `520px` (Default: `220px`)

---

### **Neo Essentials – Collapsed Mode**
- **Disable Neo Essentials**, removing scrollable behavior and restoring native layout logic.  
  `neo-features-essentials-disabled`  
- **Keep the essentials area expanded**, allowing scrollable access to pinned, container, or essential tabs.  
  `neo-features-essentials-keep-expanded`

---

### **Neo Workspace**
- **Disable Workspace features** entirely.  
  `neo-features-workspace-disabled`  
- **Disable Halo Mode in both modes**, revealing all subbuttons.  
  `neo-features-workspace-halo-mode-disabled`  
- **Disable Halo Mode only in collapsed mode**, enabling scrollable subbuttons.  
  `neo-features-workspace-halo-mode-collapsed-disabled`  
- **Disable Halo Mode only in expanded mode**, displaying all subbuttons persistently.  
  `neo-features-workspace-halo-mode-expanded-disabled`  
- **Hide the Workspace button**, auto-expanding the bottom section and displaying all subbuttons.  
  `neo-features-workspace-button-hidden`

---

### **Neo Media**
- **Disable Neo Media**, removing controls from collapsed mode.  
  `neo-features-media-disabled`

ℹ️ *When disabled, media controls will not appear unless expanded manually.*

---

### **Neo Split Groups**
- **Disable Neo Split Groups**, reverting to static collapsed tabs.  
  `neo-features-split-groups-disabled`  
- **Keep SplitGroups expanded across all modes**  
  `neo-features-split-groups-expanded`  
- **Keep SplitGroups expanded only in compact mode**  
  `neo-features-split-groups-expanded-compact`

📌 *Expanded visibility ensures smoother navigation and workspace management.*

---

### **Neo Tab Groups**
- **Disable Tab Group logic**, reverting to native tab layout.  
  `neo-features-tab-groups-disabled`  
- **Disable Tab Group styling**, but preserve behavior.  
  `neo-theme-tab-groups-disabled`  
- **Center tabs within Tab Groups** for better alignment.  
  `neo-features-tab-groups-tabs-centered`

📌 *Combine settings for full control over function and visuals.*

---

### **Neo Findbar**
- **Disable the Neo floating Findbar**, reverting to the default browser search bar.  
  `neo-features-findbar-disabled`  
- **Enable hover-to-show behavior** for Neo Findbar.  
  `neo-features-findbar-hover-enabled`

📌 *Disabling restores native layout; hover can be used independently.*

---

### **Neo Search**
- **Disable the Neo Search feature**, reverting to the browser’s native search behavior.  
  `neo-features-search-disabled`

📌 *Disabling Neo Search will restore default layout and functionality for in-page search.*

---

## 🎨 Theme & UI Customization

### **General Theme Settings**
- **Disable Neo Zen’s theme styling**, restoring native visuals while keeping feature logic intact.  
  `neo-theme-disabled`  
- **Restore original Zen background**  
  `neo-theme-background-enabled`  
- **Enable tab background shadow**  
  `neo-theme-shadow-enabled`  
- **Enable sidebar scrollbar**  
  `neo-theme-scrollbar-enabled`

---

### **Customization Screen**
- **Disable styling in customization mode**  
  `neo-theme-customization-toolbar-disabled`

---

### **Window Buttons**
- **Disable custom window button styling**  
  `neo-theme-window-buttons-disabled`  
- **Keep window buttons colorful when inactive**  
  `neo-theme-window-buttons-colorful-enabled`

---

### **Workspace Button**
- **Disable Workspace button styling**  
  `neo-theme-workspace-button-disabled`

---

### **Workspace Indicator**
- **Hide the Workspace indicator**  
  `neo-hide-workspace-indicator`  
- **Disable its styling**  
  `neo-theme-workspace-indicator-disabled`

---

### **Nebula Tab Animations**
- **Disable animations from Nebula extension**  
  `neo-external-nebula-animations-tabs-disabled`

📌 *See [Nebula documentation](https://github.com/JustAdumbPrsn/Zen-Nebula) for details.*

---

### **Media Controls**
- **Disable styling for media controls** (removes glow and hover effects)  
  `neo-theme-media-disabled`

📌 *Affects visuals only — media functionality remains.*

---

### **Tab Customization**
- **Disable styling for all tabs**  
  `neo-theme-tabs-disabled`  
- **Disable close button styling**  
  `neo-theme-close-button-disabled`  
- **Disable styling by category**:  
  - Essentials → `neo-theme-tabs-essentials-disabled`  
  - Pinned Tabs → `neo-theme-tabs-pinned-disabled`  
  - New Tab Button → `neo-theme-tabs-newtab-button-disabled`  
  - Normal Tabs → `neo-theme-tabs-normals-disabled`  
  - Containers → `neo-theme-tabs-containers-disabled`  
  - Essentials in Containers → `neo-theme-tabs-containers-essentials-disabled`

---

### **Overflow Indicators**
- **Disable styling for overflow indicators**  
  `neo-theme-tabs-overflow-indicators-disabled`

---

### **Findbar**
- **Disable Findbar styling**  
  `neo-theme-findbar-disabled`

---

### **URL Bar**
- **Disable URL bar styling**, restoring the native address field design and interactions.  
  `neo-theme-urlbar-disabled`  
- **Disable both glow and border** styling for the floating URL bar.  
  `neo-theme-urlbar-glow-border-disabled`  
- **Disable only the glow effect** around the floating URL bar, while preserving the border.  
  `neo-theme-urlbar-glow-disabled`  
- **Disable only the border** around the floating URL bar, while keeping the glow.  
  `neo-theme-urlbar-border-disabled`

📌 *Each toggle gives precise control over visual layering. Combine for full minimalism or hybrid styling.*
