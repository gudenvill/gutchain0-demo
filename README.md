# Gutchain0 Widget Demo

A minimal demo showing how to embed the Gutchain0 voucher management widget in any website.

## 🚀 What is this?

This demo shows the Gutchain0 widget in action - a complete voucher management system that can be embedded anywhere with just 2 lines of HTML.

## ✨ Features

- **🔐 Real Authentication**: Integrates with moped-shop API using hash tokens
- **💬 Conversational Interface**: WhatsApp-style chat for creating vouchers
- **🎨 AI-Generated Backgrounds**: Google Imagen 4 creates unique images for each voucher
- **🍌 Smart Voucher Editing**: LLM-powered intelligent voucher modifications
- **📱 Complete Mobile Support**: Responsive design works everywhere

## 📋 Usage

Simply add these 2 lines to any HTML page:

```html
<div data-gutchain data-login="YOUR_HASH_TOKEN"></div>
<script src="https://imagegenerator.jolioo.com/gutchain-widget.iife.js"></script>
```

## 🎯 Demo

Open `index.html` in your browser to see the widget in action.

The demo includes:
- **Real authentication** with Bäckerei Buchgraber company account
- **Full voucher creation** - create spa, restaurant, café vouchers with natural language
- **Smart editing** - "make it $150 instead", "change to tropical theme"
- **Complete voucher history** with version management

## 🔧 Configuration

### Authentication
Replace `data-login` with your moped-shop hash token:
```html
<div data-gutchain data-login="f8bbc94fe347f0ab2b0426ce89f7cde7..."></div>
```

### Styling
The widget is completely self-contained with its own CSS. No external dependencies required.

## 🛠 Technical Details

- **Widget Size**: ~40KB minified IIFE
- **Framework**: Vanilla TypeScript with Lit components
- **Authentication**: Real moped-shop API integration
- **Backend**: Connects to FastAPI server for voucher operations
- **AI Integration**: Google Imagen 4 for backgrounds, LLM for smart editing

## 🌐 Live System

This demo connects to a live backend system that provides:
- Real moped-shop authentication
- AI voucher generation with Google Imagen 4
- Intelligent voucher editing with LLM classification
- Complete voucher version history
- WhatsApp-style conversation persistence

## 📊 Performance

- **Authentication**: ~200ms
- **Text-only edits**: ~2s
- **Image edits**: ~12s
- **Complete voucher generation**: ~18s

## 💡 Integration Examples

### Basic Integration
```html
<!DOCTYPE html>
<html>
<head><title>My Store</title></head>
<body>
  <h1>Welcome to our store!</h1>

  <!-- Gutchain0 Widget -->
  <div data-gutchain data-login="YOUR_TOKEN"></div>
  <script src="https://imagegenerator.jolioo.com/gutchain-widget.iife.js"></script>
</body>
</html>
```

### Multiple Widgets
```html
<!-- Customer portal -->
<div data-gutchain data-login="customer_token"></div>

<!-- Admin panel -->
<div data-gutchain data-login="admin_token"></div>

<script src="https://imagegenerator.jolioo.com/gutchain-widget.iife.js"></script>
```

## 🔗 Related

- **Main Repository**: [gutchain0](../gutchain0) - Complete voucher management system
- **Production Widget**: https://imagegenerator.jolioo.com/gutchain-widget.iife.js

---

**🎉 Ready to create beautiful vouchers with AI? Just add the widget to your site!**