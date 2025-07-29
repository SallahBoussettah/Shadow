# GitHub Upload Guide for Shadow Theme

To make your theme work with the GitHub URLs, you need to upload these specific files to your repository:

## Required Files to Upload

### 1. Main Theme File
- Upload `Shadow.theme.css` to the root of your repository

### 2. Compiled CSS Files
- Upload the entire `public` folder to your repository
- This contains:
  - `main.css` (the main compiled theme)
  - `betterdiscord.css` (BetterDiscord specific styles)
  - `vencord.css` (Vencord specific styles)

### 3. Assets
- Upload the entire `assets` folder to your repository
- This contains:
  - `assets/images/Sung-jin.png` (your wallpaper)
  - `assets/icons/shadow-home.svg` (custom home icon)

### 4. Documentation
- Upload `README.md` to the root of your repository

## Quick Upload Steps

1. **Go to your GitHub repository**: https://github.com/SallahBoussettah/Shadow

2. **Upload the main theme file**:
   - Click "Add file" > "Upload files"
   - Drag `Shadow.theme.css` into the upload area
   - Commit the changes

3. **Upload the public folder**:
   - Click "Add file" > "Upload files"
   - Drag the entire `public` folder into the upload area
   - Commit the changes

4. **Upload the assets folder**:
   - Click "Add file" > "Upload files"
   - Drag the entire `assets` folder into the upload area
   - Commit the changes

5. **Upload README**:
   - Click "Add file" > "Upload files"
   - Drag `README.md` into the upload area
   - Commit the changes

## Alternative: Upload Your Image to Imgur

If you want a quick fix for just the background image:

1. Go to https://imgur.com
2. Upload your `Sung-jin.png` image
3. Copy the direct image URL (ends with .png)
4. Replace the background-image URL in your theme file with the Imgur URL

## Testing the Theme

Once uploaded, your theme will be accessible at:
- **Main theme**: `https://raw.githubusercontent.com/SallahBoussettah/Shadow/main/Shadow.theme.css`
- **Background image**: `https://raw.githubusercontent.com/SallahBoussettah/Shadow/main/assets/images/Sung-jin.png`
- **Home icon**: `https://raw.githubusercontent.com/SallahBoussettah/Shadow/main/assets/icons/shadow-home.svg`

## Temporary Solution

Use `Shadow-Local.theme.css` for immediate testing - it has all styles embedded and doesn't require external files.