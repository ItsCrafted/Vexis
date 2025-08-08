# Vexis

<img src="data:image/png;base64,YOUR_BASE64_STRING_HERE" alt="Vexis Preview" width="200"/>

---

**Vexis** runs full HTML and JavaScript code directly from base64-encoded images.  
It's a compact browser-based tool that decodes embedded image data and renders live web output.

---

## 🧠 How It Works

1. You provide a base64 image containing valid HTML/JS code.
2. Vexis extracts the code.
3. It opens a new tab and renders the result.

There’s no backend — it’s pure front-end magic.

---

## 🚀 Usage

Simply host `index.html` somewhere, or open it locally in your browser.  
Paste your base64-encoded image string, and Vexis will do the rest.

### 🖼 Example Image Format:
Make sure your image contains data like this:
```html
data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAA...
