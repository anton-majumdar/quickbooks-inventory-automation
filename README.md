# Case Study: QuickBooks Inventory & Invoice Automation Pipeline

## 🏢 The Business Problem
An e-commerce and wholesale business owner was using **QuickBooks Online** to manage their finances, but tracking their stock levels was an operational nightmare. Every day, they had to manually download sales sheets from their website, open Excel, calculate remaining stock items, and then manually type those updated numbers back into QuickBooks to keep their inventory accurate. This manual data entry was taking 6 hours a week and led to frequent stock-outs.

## 🛠️ The Business-Efficiency Solution
I engineered an automated Excel-to-QuickBooks data pipeline that completely eliminates manual data entry and keeps inventory counts completely accurate.

* **Automated Sales Processing:** Built automated Excel tables that instantly aggregate daily sales lines, mapping product SKU numbers to the exact inventory format required by QuickBooks.
* **Bulk Upload Preparation:** Programmed the system to automatically generate flawless `.CSV` import files that match QuickBooks' strict item-update guidelines (Item Name, Description, Quantity on Hand, Asset Account).
* **Stock Alert Dashboard:** Created an automated dashboard tab that highlights critically low stock items in bright yellow before inventory drops to zero.

## 📈 The Business Value Delivered
* **Time Saved:** Slashed daily administrative manual entry from **1 hour down to less than 60 seconds**.
* **Eliminated Stock Errors:** Stopped human typographical errors entirely, ensuring QuickBooks inventory perfectly reflects actual warehouse numbers.
* **Proactive Reordering:** The owner can now place inventory reorders days in advance, completely avoiding lost sales from out-of-stock items.
