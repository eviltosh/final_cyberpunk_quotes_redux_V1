# 💹 Cyberpunk Quotes

**Cyberpunk Quotes** is a neon-styled stock market dashboard built with Streamlit.  
It allows users to track stock performance, view company profiles, read recent news, and visualize price data with a cyberpunk-themed UI.  
The app now supports secure user-entered API keys and is optimized for mobile devices.

---

## 🚀 Features

- 🔍 **Search multiple stock tickers**
- 📰 **Company news with user-provided API key (Finnhub)**
- 📊 **Two chart modes:**
  - Cyberpunk Glow (Matplotlib + Neon Glow Effects)
  - Classic Trading Chart (Plotly Candlestick + Volume)
- 🌅 **Customizable background images (including user upload)**
- 🧠 **Auto-refresh option** (configurable)
- 📱 **Mobile-optimized title sizing**
- 🎨 Embedded cyberpunk styling (no external CSS dependencies)

---

## 🔑 API Key Requirement (Finnhub)

To access company news, the user must provide their Finnhub API key in the sidebar input field.

Why this change?

- ✔ Removes hard-coded API keys from source code
- ✔ Improves security and GitHub compliance
- ✔ Allows each user to use their own key

### Get a Free Finnhub API Key

1. Visit: https://finnhub.io
2. Click **Sign Up** for a free account
3. Copy your API key from your dashboard
4. Paste it into the **Finnhub API key** field in the app sidebar

---

## 📱 Mobile Optimization Update

The title (`CYBERPUNK QUOTES`) previously appeared oversized on mobile devices.  
This update introduces responsive styling:

| Device | Font Size | Notes |
|--------|------------|--------|
| Desktop | 6em | Same cyberpunk aesthetic retained |
| Mobile | 2.2rem | Reduced for readability and layout fit |

No changes were made to font style, glow, or animation.

---

## 🧩 Project Structure

