<h1 align="center">Neo-Zen</h1>
<div align="center">
    <a href="https://zen-browser.app/">
        <img width="120" alt="zen-badge-dark" src="https://github.com/user-attachments/assets/d6ab3ddf-6630-4062-92d0-22497d2a3f9a" />
    </a>
</div>

###

<div align="center">
  <img width="700" alt="Market-Image" src="https://github.com/user-attachments/assets/8fb6729e-5bef-4acb-af70-9d5066cb2e53" />
</div>

###

# Neo Zen  

Welcome to **Neo Zen** – a sleek, futuristic theme for Zen Browser that blends modern design with mindful simplicity. With **innovative features, refined UI enhancements, and adaptive styling**, Neo Zen creates a seamless, distraction-free browsing experience. 

> ## 🔄 Project Status – Rewrite Completed
> 
> The **rewrite of Neo Zen is finished**, delivering a cleaner and more maintainable foundation for the theme.  
> Many planned features are **still missing or not yet implemented**, but the new base is stable and ready for use.  
> 
> ### Branch Information
> - **Main Branch** – Contains the completed rewrite and is now the active branch.  
> - **Rewrite Branch** – Will be removed soon, since most of the work from that branch has already been merged and implemented.  
> 
> ### Current Version
> The latest release is: **1.21.3‑neo.1**  
> This version marks the first stable release of the completed rewrite.  
> 
> ### Versioning
> Neo Zen uses a **semantic overlay versioning scheme**:  
> - The first part (`1.21.3`) matches the **Zen Browser version** the theme is built for.  
> - The overlay (`neo.1`, `neo.2`, etc.) indicates the **theme’s own release number** for that Zen version.  
> 
> For example:  
> - Zen Browser: `1.21.3`  
> - Neo Zen Theme: `1.21.3‑neo.1` → first theme release for Zen Browser 1.21.3  
> - Neo Zen Theme: `1.21.3‑neo.2` → second theme release for Zen Browser 1.21.3 (bug fixes or improvements)  
> 
> This scheme makes compatibility explicit while keeping the version string concise and easy to parse.  

---

## 🎨 Matugen Compatibility

Neo Zen is fully compatible with **[Matugen]** —  
a dynamic theming engine that generates color palettes based on your wallpaper or system preferences.  

This integration allows Neo Zen to adapt its colors seamlessly, giving you a more personalized and cohesive browsing experience.  

### ⚙️ Setup Instructions

1. **Copy the template file**  
   Place the provided `Neo-Colors.css` file inside the `templates` folder of your Matugen configuration:

   ***~/.config/matugen/templates/Neo-Colors.css***


2. **Update your `config.toml`**  
Add the following block to your Matugen configuration file (`~/.config/matugen/config.toml`):

```
[templates.browser_theme]
input_path = '~/.config/matugen/templates/Neo-Colors.css'
output_path = '~/.config/matugen/output/Neo-Colors.css'
```
<br>

3. **Enable this on Zen Browser** `neo.features.color-fixer.matugen.enabled`
 
Once these steps are completed, the next time you change your wallpaper,  
Matugen will automatically generate new colors for Neo Zen — keeping your browser theme perfectly in sync with your desktop.

⚠️ **Note:** Currently, you need to restart the browser for the new colors to take effect.  
In the future, Neo Zen will likely add compatibility with **[Pywal]** to enable smoother updates without restarting.


## 🚀 Features  

---

### ⚙️ **Customization Made Easy**  
Modify Neo Zen’s behavior via the settings page (if you installed this through [Sine](https://github.com/CosmoCreeper/Sine)) or **"about:config"** if you did not.  
For detailed settings and adjustments, check out the [Settings Wiki](https://github.com/JustVibingWhileCoding/Neo-Zen/wiki/Settings).  

---

## 📸 Screenshots & Visuals

I know screenshots are useful, but honestly...  
I’m too lazy to add them right now 😅.  

I’ll upload them once I stop being lazy.  
Thanks for your patience! 

Sé que las imágenes ayudan, pero la verdad...  
me da hueva subirlas por ahora 😅.  

Las agregaré cuando se me quite la flojera.  
¡Gracias por la paciencia!

---

## ⚠️ Platform Support

Neo Zen is **only tested on Linux with Hyprland**.  
I have **no intention of verifying or ensuring compatibility** with other operating systems or environments.  

If you are able to contribute fixes or adjustments for other platforms, your help will be greatly appreciated.  
Community contributions are welcome to improve cross‑platform support. 

> **License Update:** Starting from version 1.2.3, this project is licensed under GPL-3.0.  
> Versions prior to 1.2.3 remain under the MIT License.

---

## 🏆 Credits  

Neo Zen's **tab transitions and animations** come directly from the **Nebula** theme, thanks to the generosity of its developer.  
A huge thanks to **[JustAdumbPrsn](https://github.com/JustAdumbPrsn)**, the creator of **Nebula**, for allowing the use of their code and contributing to a smoother browsing experience!  [No longer implemented after version 1.20.0-neo.1]

You can check out **Nebula** here: [Zen Nebula](https://github.com/JustAdumbPrsn/Zen-Nebula)

- **📄 PDF Viewer** – Integrated from the [Natsumi Browser](https://github.com/greeeen-dev/Natsumi-Browser), created by **greeeen-dev**.  
  A clean and functional viewer that greatly enhanced document support in Neo Zen.

- **🗂️ Tab Group System** – Based on code by [**Anoms12**](https://github.com/Anoms12).  
  Their implementation helped lay the foundation for Neo Zen’s tab group styling and behavior, [No longer implemented after version 1.20.0-neo.1].


