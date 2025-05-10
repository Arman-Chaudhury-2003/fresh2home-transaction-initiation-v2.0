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

> Login Page
[![temp-Imagep-RUR1-W.avif](https://i.postimg.cc/Wb2pDZS3/temp-Imagep-RUR1-W.avif)](https://postimg.cc/WtHcChBL)

> Home Page
[![Picture-2.png](https://i.postimg.cc/bw5qFBPD/Picture-2.png)](https://postimg.cc/XrwMrxp4)

> Menu Page
[![temp-Image-Sn-Wz-GE.avif](https://i.postimg.cc/26wJg1Wc/temp-Image-Sn-Wz-GE.avif)](https://postimg.cc/2b12Z82h)

> Contact us 
[![Picture-4.png](https://i.postimg.cc/mgHnBXMF/Picture-4.png)](https://postimg.cc/Mnz5YY9W)

> cart
[![Picture-5.png](https://i.postimg.cc/KY7sg10G/Picture-5.png)](https://postimg.cc/KKz568Xw)

> checkout
[![Picture-6.png](https://i.postimg.cc/vmwNBrL2/Picture-6.png)](https://postimg.cc/LJvTQZWj)

> payment gateway
[![temp-Imageu-Wi6-S1.avif](https://i.postimg.cc/NF26mVQ6/temp-Imageu-Wi6-S1.avif)](https://postimg.cc/Mfxf89MH)
[![temp-Image94-Xy-JR.avif](https://i.postimg.cc/63gHkC3h/temp-Image94-Xy-JR.avif)](https://postimg.cc/XGKcFG9Z)

> Backend
[temp-Image-O9-OCqf.avif](https://postimg.cc/G91X2rv8)
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
