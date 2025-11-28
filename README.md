# 🌮 Cocina Chefcito

A smart kitchen assistant and inventory management web application focused on Mexican cuisine. This app helps users track their pantry items, reduce food waste, and discover recipes using AI.

## ✨ Features

### 📦 Smart Inventory (Offline Mode)

- **Local Storage:** All data is saved directly to your device's browser. No internet connection or login required.
- **Freshness Tracking:** Visual indicators (Green/Orange/Red) show the freshness of ingredients based on their shelf life.
- **Quick Actions:** Easily add or remove items with a tap. Haptic feedback is included for better interaction.

### 🤖 "Chefcito" AI Chef

- **Powered by Gemini:** Uses Google's Gemini 2.0 Flash-Lite model to generate custom recipes.
- **Context Aware:** The AI knows exactly what ingredients you have and their freshness status.
- **Chef's Table:** Select specific ingredients you want to use, add notes (e.g., "make it spicy"), and get a unique recipe instantly.

### 📖 Recipe Discovery

- **Smart Matching:** Shows how many ingredients you already have for built-in recipes (e.g., "80% match").
- **Favorites:** Save your favorite recipes for quick access.
- **Search:** Instant search across recipes and categories.

### ⚙️ Settings & Privacy

- **BYOK (Bring Your Own Key):** Users provide their own Gemini API Key for privacy and control.
- **QR Scanner:** Built-in scanner to easily input your API Key via QR code.

## 🛠️ Tech Stack

- **Core:** HTML5, JavaScript (ES6+)
- **Styling:** Tailwind CSS (CDN), Custom Glassmorphism CSS
- **Icons:** Font Awesome 6
- **Libraries:**
  - `SweetAlert2` (Modals & Alerts)
  - `Marked.js` (Markdown parsing for AI recipes)
  - `html5-qrcode` (QR Scanning)
- **AI Model:** Gemini 2.0 Flash-Lite Preview

## 🚀 How to Run

1. **Download:** Save the `index.html` file.
2. **Open:** Double-click the file to open it in any modern web browser (Chrome, Safari, Edge).
3. **Install (Optional):** On mobile, use "Add to Home Screen" for a full-screen app experience.

## 🔑 AI Setup

To enable the "Chefcito" features:

1. Get a free API Key from [Google AI Studio](https://aistudio.google.com/).
2. Open the app settings (⚙️ icon).
3. Paste the key or scan it via QR code.

## 📱 Mobile Optimization

The app is designed with a "Liquid Glass" aesthetic optimized for mobile touch interactions, including:

- Large touch targets.
- Bottom navigation bar.
- Prevented overscroll/bounce effects.
- Dynamic viewport sizing.

*Desarrollado con ❤️ y mucho picante.*
