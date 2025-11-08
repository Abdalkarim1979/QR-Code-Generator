# QR Code Generator  

## 📖 Project Description  
**QR Code Generator** is a simple web application that allows users to generate **QR codes** directly from text input. Built with **HTML, CSS, JavaScript, jQuery, and qrcode.js**, the app provides an intuitive interface where users can type any text or link and instantly convert it into a scannable QR code.  

---

## ✨ Features
- 🔗 **Text or Link Input**: Enter any text or URL to generate a QR code.  
- 📲 **Instant QR Code Generation**: Automatically creates a QR code using the `qrcode.js` library.  
- ⌨️ **Auto Update**: QR code refreshes when pressing **Enter** or leaving the input field.  
- 🎨 **Modern UI**: Clean design with styled input fields and QR display area.  
- 📦 **jQuery Integration**: Simplifies event handling for real‑time updates.  

---

## 🛠️ Technologies Used
- **HTML5 / CSS3** for structure and styling  
- **JavaScript (qrcode.js)** for QR code generation  
- **jQuery** for event handling  

---

## 🚀 How to Use
1. Open the `index.html` file in a modern browser.  
2. Type any text or URL into the input field.  
3. Press **Enter** or click outside the field to generate the QR code.  
4. Scan the generated QR code with any QR scanner app.  

---

### Explanation

1. **DOCTYPE Declaration**:
   - The `<!DOCTYPE html>` declaration defines the document type and version of HTML being used.

2. **HTML Tag**:
   - The `<html>` tag is the root element of the HTML document. It includes the `xmlns` attribute to specify the XML namespace and `lang` attributes for language settings.

3. **Head Section**:
   - The `<head>` section contains meta-information about the document, such as the title, character set, and viewport settings.
   - It also includes links to external JavaScript files (`jquery.min.js` and `qrcode.js`).

4. **CSS Styling**:
   - The `<style>` tag contains CSS to style the page, including the body, headings, input fields, and the QR code container.

5. **Body Section**:
   - The `<body>` section contains the main content of the page.
   - It includes a heading (`<h1>`), an input field (`<input>`) for entering text, and a `<div>` to display the generated QR code.

6. **JavaScript**:
   - The JavaScript code initializes a new QRCode object and assigns it to the `qrcode` variable.
   - The `makeCode` function generates a QR code based on the value entered in the input field.
   - Event listeners are added to the input field to generate the QR code when the input loses focus (`blur` event) or when the Enter key is pressed (`keydown` event).

This code creates a simple web page that allows users to generate a QR code from the text they enter. The QR code is displayed in the `#qrcode` div element.
  ## Contact
  avrmicrotech@gmail.com


