# NoSleep ☕

A pleasant, lightweight web app that keeps your screen awake and prevents it from sleeping.

## Major Features

- **Screen Wake Lock**: Prevents the display of the device being used from going dark.
- **Modern UI**: Lovely dark theme with animated gradients and glass morphism effects.
- **Screensaver Mode**: Displays a live clock with idle status after waiting for 5 seconds
- **Tab Warnings**: Alerts you to tab switching (Wake Lock only works in the active tab)
- **Mobile Friendly**: Mobile and tablet designs with full responsiveness
- **No Dependencies**: Just plain HTML, CSS, and JavaScript; no installation required

## Imporatnt Notes

⚠️ **The Wake Lock is tab-specific**: The Wake Lock API only runs with the NoSleep tab open. If you go to another tab or window, your screen might go to sleep.

⚠️ **Browser Support**: This application is catered with the Screen Wake Lock API, which is supported in:
- Chrome/Edge 84+
- Firefox 121+
- Safari 16.4+
- Most modern mobile browsers

**But is Not Supported On**: Internet Explorer, older versions of Safari on macOS

## Technical Details

- **API Used**: [Screen Wake Lock API](https://developer.mozilla.org/en-US/docs/Web/API/Screen_Wake_Lock_API)
- **No cookies/no storage**: Your information remains on your device.
- **No tracking**: Privacy-centric, entirely magic in your browser.
- **Lightweight**: Less than 15KB in total.
