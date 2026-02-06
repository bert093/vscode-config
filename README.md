<div align="center">
    <h1>VS Code Config</h4>
</div>

## Preview
![fullscreen](https://github.com/user-attachments/assets/ade25642-89f9-4eb0-9237-498e24f9c382)
![windowed](https://github.com/user-attachments/assets/c99f2e51-30bc-4d18-8e42-80a0bccc9130)
![split-editor](https://github.com/user-attachments/assets/cabbacc5-5d22-4234-8f5f-0a0717fd3607)
<br></br>

> [!TIP]
> [Check here](shortcut/README.md) to see the vscode shortcut.

A minimal and personalized Visual Studio Code setup focusing on the settings.json file. This configuration enhances the developer experience with customized editor preferences designed for consistency, performance, and productivity.

## What's Inside?
- settings.json – Tailored VS Code settings for an optimized development workflow

## Required Extensions
To achieve the full visual and functional effect shown in the preview, please install the following extensions:
1. [Glassit-VSC](https://marketplace.visualstudio.com/items?itemName=s-nlf-fh.glassit) - Adds acrylic/glass-like transparency to the VS Code interface.
2. [Custom UI Style](https://marketplace.visualstudio.com/items?itemName=subframe7536.custom-ui-style) - Allows injecting custom CSS for a highly stylized look.
3. [VSCode Animations](https://marketplace.visualstudio.com/items?itemName=BrandonKirbyson.vscode-animations) - Adds smooth animations for UI interactions and transitions.
4. [Font Switcher](https://marketplace.visualstudio.com/items?itemName=evan-buss.font-switcher) – Easily switch fonts via the command palette
> [!WARNING]
> Some extensions like Glassit-VSC and Custom UI Style require additional configuration and enabling custom CSS/JS. Make sure to follow their documentation carefully.

> [!IMPORTANT]
> Click below to automatically install the VSCode extension.
<details>
<summary>Click for automatic install extension for VSCode!</summary>

### Here is the full list of the extension:
Better Comments - By Aaron Bond: code --install-extension aaron-bond.better-comments
Bookmarks - By Alessandro Fragnanni: code --install-extension alefragnani.Bookmarks
Code Runner - By Jun Han: code --install-extension formulahendry.code-runner
CodeSnap - By adpyke: code --install-extension adpyke.codesnap
Custom UI Style - By subframe7536: code --install-extension subframe7536.custom-ui-style 	
Dart - By Dart Code: code --install-extension Dart-Code.dart-code
Flutter - By Dart Code: code --install-extension Dart-Code.flutter
Error Lens - By Alexander: code --install-extension usernamehw.errorlens
Flutter Color - By Nilesh Chavan: code --install-extension circlecodesolution.ccs-flutter-color
Flutter Tree - By Marcelo Velasquez: code --install-extension marcelovelasquez.flutter-tree
Flutter Widget Snippets - By Alexis Villegas Torres: code --install-extension alexisvt.flutter-snippets
Font Switcher - By Evan Buss: code --install-extension evan-buss.font-switcher
GitLens - By GitKraken: code --install-extension eamodio.gitlens
GlassIt-VSC - By hikarin522: code --install-extension s-nlf-fh.glassit
Markdown Preview Enhanced - By Yiyi Wang: code --install-extension shd101wyy.markdown-preview-enhanced
Material Icon Theme - By Philipp Kief: code --install-extension PKief.material-icon-theme
Multiple cursor case preserve - By Cardinal90: code --install-extension Cardinal90.multi-cursor-case-preserve
Prettier - By Prettier (Legacy): code --install-extension esbenp.prettier-vscode
project-tree - By zhucy: code --install-extension zhucy.project-tree
Python - By Microsoft: code --install-extension ms-python.python
Tailwind CSS IntelliSense - By Tailwind Labs: code --install-extension bradlc.vscode-tailwindcss
Tailwind Docs - By Austen Cameron: code --install-extension austenc.tailwind-docs
VSCode Animations - By Brandon Kirbyson: code --install-extension BrandonKirbyson.vscode-animations
ESLint - By Microsoft: code --install-extension dbaeumer.vscode-eslint
Live Share - By Microsoft: code --install-extension MS-vsliveshare.vsliveshare
Live Preview - By Microsoft: code --install-extension ms-vscode.live-server
HTML CSS Support - By ecmel: code --install-extension ecmel.vscode-html-css
YAML - By Red Hat: code --install-extension redhat.vscode-yaml
Remote - SSH - By Microsoft: code --install-extension ms-vscode-remote.remote-ssh

> [!NOTE]
> You can uninstall it if you don't want it!.
```
code --install-extension aaron-bond.better-comments --install-extension alefragnani.Bookmarks --install-extension formulahendry.code-runner --install-extension adpyke.codesnap --install-extension Dart-Code.dart-code --install-extension Dart-Code.flutter --install-extension usernamehw.errorlens --install-extension circlecodesolution.ccs-flutter-color --install-extension marcelovelasquez.flutter-tree --install-extension alexisvt.flutter-snippets --install-extension evan-buss.font-switcher --install-extension eamodio.gitlens --install-extension s-nlf-fh.glassit --install-extension shd101wyy.markdown-preview-enhanced --install-extension PKief.material-icon-theme --install-extension Cardinal90.multi-cursor-case-preserve --install-extension zhucy.project-tree --install-extension ms-python.python --install-extension bradlc.vscode-tailwindcss --install-extension austenc.tailwind-docs --install-extension BrandonKirbyson.vscode-animations --install-extension subframe7536.custom-ui-style --install-extension dbaeumer.vscode-eslint --install-extension MS-vsliveshare.vsliveshare --install-extension ms-vscode.live-server --install-extension ecmel.vscode-html-css --install-extension redhat.vscode-yaml --install-extension ms-vscode-remote.remote-ssh
```

</details>

## Required Fonts

To achieve the exact font rendering as seen in the preview, make sure the following fonts are installed on your system:
1. Fira Code – [Download here](https://github.com/ryanoasis/nerd-fonts/releases/download/v3.4.0/FiraCode.zip) (for ligatures and modern code style)
2. JetBrains Mono – [Download here](https://github.com/ryanoasis/nerd-fonts/releases/download/v3.4.0/JetBrainsMono.zip) (excellent readability and aesthetics)
3. Source Code Pro Nerd Font – [Download here](https://github.com/ryanoasis/nerd-fonts/releases/download/v3.4.0/SourceCodePro.zip) (Adobe’s developer font, patched with Nerd Font glyphs)
4. Roboto Mono Nerd Font – [Download here](https://github.com/ryanoasis/nerd-fonts/releases/download/v3.4.0/RobotoMono.zip) (Clean and modern monospace, patched with icons)
> [!NOTE]
> You can select your preferred font via the editor.fontFamily setting inside settings.json.

## Optional Theme

For a more visually refined and modern look (as seen in the preview), you may optionally use the Anyshphere Modern theme:
1. Anyshphere Modern - [Download here](https://marketplace.visualstudio.com/items?itemName=GustavoPrietodePaula.anysphere-modern) “This is the theme I use daily for coding. It offers a clean, elegant aesthetic with soft syntax colors that reduce eye strain and keep me focused.”

## Optional Wallpaper

To complete the overall aesthetic, I also use a custom wallpaper that blends well with the transparent VS Code setup:
1. [Aurora Dotfiles Hyprland](https://github.com/flickowoa/dotfiles/tree/aurora/config/hypr/wallpapers)
> This is the wallpaper I currently use with my VS Code theme. I discovered it from a Hyprland rice called [Aurora Dotfiles](https://github.com/flickowoa/dotfiles/tree/aurora), and it matches perfectly with the soft, bluish tones of the UI.
2. [walls](https://github.com/dharmx/walls/blob/main/fogsmoke/a_foggy_forest_with_trees_05.jpg)
> This is a wallpaper I often use with VS Code. The original image comes from Wallpaper Engine; I found a copy in the **walls** repository by dharmx.

## Purpose
This repository serves as a portable, version-controlled configuration for Visual Studio Code. Perfect for syncing your environment across devices or sharing a trusted setup with teammates.

## Getting Started
1. Clone or download this repository
2. Copy settings.json to your VS Code user configuration folder:
```
Windows:   %APPDATA%\Code\User  
macOS:     ~/Library/Application Support/Code/User 
Linux:     ~/.config/Code/User  
```
3. Restart VS Code and you're ready to go!
