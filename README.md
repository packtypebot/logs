<div align="center">
  <img src="https://cdn.jsdelivr.net/gh/packtypebot/imagens/logo.webp" alt="Project Logo" width="200">
  <h1>🚀 Project Documentation</h1>
</div>

# 📝 Version Log

## 🌟 Version 5 - 25/02/2025

### 🔧 Bug Fixes

- 🔄 **Queue System Improvements**
  - Fixed media sending in queue (QueueOptionController.ts, QueueController.ts, wbotMessageListener.ts)
  - Fixed Contact typo in wbotMessageListener.ts
    ```
    Line 2108: const body = `\u200e ${whatsapp.outOfHoursMessage}`;
    ```

### 🎯 WHATICKET Queue System Enhancement

- 🔄 Removed regex-based verification that blocked queue selection after invalid messages
- ✨ Now accepts any valid numeric input regardless of previous bot messages
- 📝 Invalid option messages now include the options list for retry
- 📂 Updated file: `backend/src/services/WbotServices/wbotMessageListener.ts`

### ✅ Major Improvements

- 🖥️ Fixed ticket area resizing issue
- 🔔 Resolved toastError.js problems
- 📱 Enhanced number validation in ContactModal
- 🤖 Updated OpenAI to version "3.3.0"
- ⭐ Corrected rating system from 1 to 5 stars
- 📊 Implemented rating messages only for active tickets
- ⏰ Added support for alternating schedules
- 🎨 Dynamic logo switching based on Light/Dark theme
- 📋 Kanban implementation and redesign
- 🔊 Fixed iPhone audio playback issues
- 🌙 Dark mode chat corrections
- 📁 Implemented company-specific folders in "public"

---

<div align="center">
  <p>Made with ❤️ for better user experience</p>
</div>
