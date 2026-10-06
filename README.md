# Quotation Maker

A responsive Web & Mobile PWA application for automated fabrication rate quotation generation.

🔗 **Live App:** [https://sachin814358.github.io/quotation-maker/](https://sachin814358.github.io/quotation-maker/)  
📂 **GitHub Repository:** [https://github.com/SacHiN814358/quotation-maker](https://github.com/SacHiN814358/quotation-maker)

---

## 🚀 Features

- **Exact Fabricator Format**: Formatted specifically for structural & fabrication rate quotes (DEEPA ENGINEERING, GSTIN, Contact, Work description).
- **Auto-calculating & Sequential SR.NO**: Automatic continuous serial numbers (1, 2, 3...) that re-sequence upon item addition or deletion.
- **Merged Space Row**: 1-click button to insert full merged blank rows for section dividers (e.g. *--- SHED WORK ---*) or spacing without column borders.
- **Auto-expanding Multiline Particulars**: Item descriptions wrap into new lines automatically without cutting text or distorting layout.
- **Unified Qty & Rate**: Supports natural input (`1 nos`, `1kg`, `10 mtr`) with automatic rate multiplication.
- **1-Click Export**:
  - 🖨️ / 📄 **Save as PDF**: Exact A4 standard printable sheet without screen buttons.
  - 📊 **Export to Excel**: Formatted `.xlsx` spreadsheet generation using SheetJS.
- **Mobile PWA Ready**: Installable on Android & iOS ("Add to Home Screen") as an app icon.
- **Persistent Header Settings**: Change Company Name, GSTIN, Mobiles, Address, and Terms with instant browser `localStorage` saving.

---

## 🛠️ Tech Stack

- **HTML5 / CSS3 / JavaScript (Vanilla)**
- **SheetJS (xlsx.full.min.js)** for client-side Excel generation
- **Web App Manifest & PWA Support**

---

## 💻 Local Usage

Double click `Open_Quotation_App.bat` or open `index.html` directly in any web browser.
