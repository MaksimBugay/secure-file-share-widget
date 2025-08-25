# Secure File Share Widget Integration

A simple, secure file sharing widget that can be easily integrated into any website with end-to-end encryption and AI-resistant CAPTCHA protection.

## 🚀 Quick Integration

### Basic Integration

Add the secure file share widget to your website using an iframe:

```html
<iframe 
    src="https://secure.fileshare.ovh/file-sharing-embedded.html"
    width="100%" 
    height="600"
    frameborder="0"
    allow="clipboard-read; clipboard-write"
    sandbox="allow-same-origin allow-scripts allow-forms allow-popups allow-modals">
    <p>Your browser does not support iframes. Please visit 
    <a href="https://secure.fileshare.ovh/file-sharing-embedded.html" target="_blank">
        Secure File Share
    </a> directly.</p>
</iframe>
```

### Responsive Integration

For responsive design, wrap the iframe in a container:

```html
<div style="position: relative; width: 100%; height: 600px; border-radius: 10px; overflow: hidden;">
    <iframe 
        src="https://secure.fileshare.ovh/file-sharing-embedded.html"
        style="position: absolute; top: 0; left: 0; width: 100%; height: 100%; border: none;"
        allow="clipboard-read; clipboard-write"
        sandbox="allow-same-origin allow-scripts allow-forms allow-popups allow-modals">
        <p>Secure file sharing not supported in your browser.</p>
    </iframe>
</div>
```

### Styled Integration

Example with custom styling:

```html
<div class="secure-fileshare-container">
    <h3>Share Files Securely</h3>
    <iframe 
        src="https://secure.fileshare.ovh/file-sharing-embedded.html"
        class="secure-fileshare-widget"
        allow="clipboard-read; clipboard-write"
        sandbox="allow-same-origin allow-scripts allow-forms allow-popups allow-modals">
    </iframe>
</div>

<style>
.secure-fileshare-container {
    max-width: 800px;
    margin: 20px auto;
    padding: 20px;
    border: 2px solid #4CAF50;
    border-radius: 15px;
    background: #f8f9fa;
}

.secure-fileshare-widget {
    width: 100%;
    height: 600px;
    border: none;
    border-radius: 10px;
}
</style>
```

## 🔧 Integration Options

### Required Attributes

| Attribute | Description |
|-----------|-------------|
| `src` | Widget URL: `https://secure.fileshare.ovh/file-sharing-embedded.html` |
| `allow` | Permissions: `clipboard-read; clipboard-write` for paste functionality |
| `sandbox` | Security: `allow-same-origin allow-scripts allow-forms allow-popups allow-modals` |

### Recommended Settings

| Setting | Value | Purpose |
|---------|-------|---------|
| `width` | `100%` or fixed pixels | Responsive or fixed width |
| `height` | `600px` minimum | Adequate space for interface |
| `frameborder` | `0` | Clean appearance |
| `loading` | `lazy` | Performance optimization |

## 🎯 Features

- **End-to-End Encryption** - Files encrypted with user passwords
- **AI-Resistant CAPTCHA** - Advanced bot protection
- **Drag & Drop Support** - Easy file selection
- **Clipboard Integration** - Paste files with Ctrl+V
- **Multiple File Upload** - Batch file sharing
- **No Registration Required** - Instant usage

## ⚠️ Important Notes

### Browser Compatibility
- Modern browsers (Chrome 80+, Firefox 75+, Safari 13+, Edge 80+)
- JavaScript must be enabled
- HTTPS recommended for full functionality

### Security Considerations
- **Clipboard access** may be limited in iframe context due to browser security
- For full functionality, consider providing a direct link option
- Files are automatically deleted after sharing period expires

### Limitations
- **Cross-origin restrictions** may affect some browser features
- **Clipboard paste (Ctrl+V)** may not work in all iframe implementations
- Consider providing alternative access methods for full functionality

## 📋 Complete Example

```html
<!DOCTYPE html>
<html>
<head>
    <title>My Website with Secure File Sharing</title>
    <style>
        .file-share-section {
            max-width: 900px;
            margin: 40px auto;
            padding: 20px;
            text-align: center;
        }
        .widget-container {
            border: 3px solid #4CAF50;
            border-radius: 15px;
            overflow: hidden;
            box-shadow: 0 5px 20px rgba(76, 175, 80, 0.3);
            margin-top: 20px;
        }
    </style>
</head>
<body>
    <div class="file-share-section">
        <h2>Share Files Securely</h2>
        <p>Upload and share files with end-to-end encryption</p>
        
        <div class="widget-container">
            <iframe 
                src="https://secure.fileshare.ovh/file-sharing-embedded.html"
                width="100%" 
                height="600"
                frameborder="0"
                loading="lazy"
                allow="clipboard-read; clipboard-write"
                sandbox="allow-same-origin allow-scripts allow-forms allow-popups allow-modals"
                title="Secure File Share Widget">
                <p>
                    Your browser doesn't support embedded file sharing. 
                    <a href="https://secure.fileshare.ovh/file-sharing-embedded.html" target="_blank">
                        Open Secure File Share
                    </a>
                </p>
            </iframe>
        </div>
        
        <p><small>
            For full functionality including clipboard paste, 
            <a href="https://secure.fileshare.ovh/file-sharing-embedded.html" target="_blank">
                open in new tab
            </a>
        </small></p>
    </div>
</body>
</html>
```

## 🔗 Additional Resources

- **Demo Page**: [Live Demo](demo.html)
- **Documentation**: [User Manual](secure-fileshare-documentation.html)
- **Privacy Policy**: [Privacy Information](privacy-policy.html)
- **Direct Service**: [secure.fileshare.ovh](https://secure.fileshare.ovh/file-sharing-embedded.html)

## 📞 Support

For integration support or questions:
- **Email**: sfile4share@gmail.com
- **Service URL**: https://secure.fileshare.ovh/file-sharing-embedded.html

---

**Free to use** for personal and commercial projects. No registration required.
