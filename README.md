# Tunzy Top Up - HD Free Fire Receipt Generator

This is a **fully self-contained HTML site** that generates professional HD Free Fire top-up receipts with festive Christmas and diamond designs.

## Features

- 🎅 Tunzy Top Up receipt title with Christmas hat emoji  
- 💎 Diamond background with sparkle effect  
- ❄ Snow animation  
- Input fields for:
  - Name  
  - Free Fire UID  
  - Payment Option (Credit Card, PayPal, Bank Transfer)  
  - Diamonds purchased  
  - Amount Paid  
- Random transaction token generation  
- Download receipt as **HD PNG** using `html2canvas`  
- Fully self-contained HTML (no images or external assets needed)  

## How to Use

1. Open the site in a browser.  
2. Fill out all fields (Name, UID, Payment, Diamonds, Amount).  
3. Click **Generate Receipt** to view the receipt.  
4. Click **Download HD Receipt** to save a high-definition PNG file.

## Deployment on Render

1. Go to [Render](https://render.com/) and create a **Static Site**.  
2. Connect your GitHub repository: `tunzy-receipt`.  
3. Branch: `main`.  
4. **Build Command:** leave empty.  
5. **Publish Directory:** `/` (root folder).  
6. Click **Deploy** — Render will host your `index.html` directly.

> **Note:** No Docker or additional build steps are required. The site is fully static.

## License

This project is for personal or commercial use under [MIT License](https://opensource.org/licenses/MIT).
