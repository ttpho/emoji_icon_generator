# Emoji Icon Generator

A simple web app to generate PNG icon files from any emoji, for use as favicons, app icons, or anywhere you need emoji-based graphics.

![Screenshot 2025-06-01 at 22 58 21](https://github.com/user-attachments/assets/f40b1633-ab51-4530-a866-7c55da78e84e)

## Features

- **Emoji Input:** Enter any emoji or pick from a set of popular emoji buttons.
- **Instant Generation:** Icons are generated automatically as you type or select an emoji.
- **Multiple Sizes:** Generates PNG icons in common sizes (32x32, 192x192, 512x512, and maskable variants).
- **Download Links:** Preview and download each generated icon instantly.
- **Responsive UI:** Clean, mobile-friendly interface using Tailwind CSS.

---

## How to Use

1. **Open index.html in your browser.**
2. **Enter an emoji** in the input field or click one of the emoji buttons.
3. **Scroll down** to the "Generated Icons" section.
4. **Preview** the icons and click "Download" to save any size you need.

---

## Customization

- **Add More Emoji Buttons:**  
  Edit the `.emoji-buttons` section in the HTML to add your favorite emoji.
- **Change Icon Sizes:**  
  Modify the `iconSpecs` array in the JavaScript to add or remove icon sizes and filenames.

---

## Technical Notes

- **No dependencies:**  
  Only uses Tailwind CDN for styling; all logic is in vanilla JavaScript.
- **Font rendering:**  
  Uses system emoji fonts for best compatibility.
- **No server required:**  
  All processing is done in the browser.

---

## File Structure

```
emoji_icon_generator/
├── index.html   # Main app (HTML, CSS, JS in one file)
```

---

## License

MIT License.  
Feel free to use, modify, and share!

---

**Made with ❤️ and JavaScript.**
