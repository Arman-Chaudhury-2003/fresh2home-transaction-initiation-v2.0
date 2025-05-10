# 🥗 Fresh2Home - Transaction Initiation v2.0

This project is part of the **Fresh2Home** food delivery ecosystem, enabling secure and fast **transaction initiation** using UPI QR codes. It supports real-time order placement with auto-generated UPI QR based on the cart amount and provides flexible options for payment verification via Gmail or iMessages.

## 🚀 Features

- 📦 Dynamic cart total-based UPI QR generation
- 🧾 Checkout integration with owner’s UPI ID
- 📥 Payment verification via:
  - 📧 Gmail (email scans for payment confirmation)
  - 💬 iMessages (macOS local iMessage DB parsing)
- ✅ Auto-confirmation with popup after payment success

## 🖼️ Preview

> Upload your screenshots to an image host like [Imgur](https://imgur.com/upload) or [PostImages](https://postimages.org/) and paste the direct image links below.

[![temp-Imagep-RUR1-W.avif](https://i.postimg.cc/Wb2pDZS3/temp-Imagep-RUR1-W.avif)](https://postimg.cc/WtHcChBL)
![QR Code Generation](https://your-image-link.com/qr.png)
![Email/iMessage Confirmation](https://your-image-link.com/confirmation.png)

## 🧱 Tech Stack

- **Frontend**: React.js, Tailwind CSS
- **Backend**: Node.js, Express.js
- **Payment**: Static UPI QR code generation with dynamic amount
- **Verification**:
  - Gmail API (using OAuth2)
  - macOS iMessage `chat.db` scan (SQLite)

## 🛠️ How to Run

### 📦 Prerequisites

- Node.js & npm
- macOS (for iMessage verification)
- Gmail with enabled Gmail API (for email scan)

### ⚙️ Setup

```bash
# Clone the repository
git clone https://github.com/Arman-Chaudhury-2003/fresh2home-transaction-initiation-v2.0.git
cd fresh2home-transaction-initiation-v2.0

# Install dependencies
npm install
