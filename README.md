# 🏷️ Old Navy Email Ops Studio

A specialized configuration studio for personalizing email campaigns, Movable Ink / Constructor widget setups, and deployment tickets.

---

## 🚀 How to Open

Open [`index.html`](file:///C:/Users/jsoukkh/.gemini/antigravity/scratch/email-template-generator/index.html) in your browser:
```powershell
Start-Process "C:\Users\jsoukkh\.gemini\antigravity\scratch\email-template-generator\index.html"
```

---

## ⚡ 1-Click Brand Presets

| Preset | Markets | Languages | POD IDs | TIDs | Rules & Stripping |
|---|---|---|---|---|---|
| **⚡ BAU** | `US`, `CDA-EN`, `CDA-FR` | `US`, `CDA-EN`, `CDA-FR` | `onus_email_mi_uf`, `onca_email_mi_en_uf`, `onca_email_mi_fr_uf` | `onem013383`, `ocem003398` | EV_Segment 1 = `Y`<br>Sale/Promo/Clearance = `N`<br>Tracking ID = `Y`<br>Customer ID = `N`<br>Cache Token = `Y` |
| **🇺🇸 US Only** | `US` | `US` | `onus_email_mi_uf` | `onem013383` | EV_Segment 1 = `Y`<br>Sale/Promo/Clearance = `N`<br>Tracking ID = `Y`<br>Customer ID = `N`<br>Cache Token = `Y` |
| **🇨🇦 CDA Only** | `CDA-EN`, `CDA-FR` | `CDA-EN`, `CDA-FR` | `onca_email_mi_en_uf`, `onca_email_mi_fr_uf` | `ocem003398` | EV_Segment 1 = `Y`<br>Sale/Promo/Clearance = `N`<br>Tracking ID = `Y`<br>Customer ID = `N`<br>Cache Token = `Y` |

---

## 📋 Field Definitions & Controls

| Field Name | Type | Description / Options |
|---|---|---|
| **Requester** | Text input | Requester name or ID (e.g. `Jordan Soukkh`) |
| **Total Items** | 8 or 16 | Segmented buttons (`8 Items (Standard)`, `16 Items (Expanded)`) |
| **Brand** | Text input | `Old Navy` (default) |
| **Market** | **Multi-Select** Pills | Pick one or more: `US`, `CDA-EN`, `CDA-FR` (with quick-select for `All`, `US`, `Canada`) |
| **Language** | **Multi-Select** Pills | Pick one or more: `US`, `CDA-EN`, `CDA-FR` (with 1-click `Sync with Market`) |
| **POD ID** | **Multi-Select** Pills + Custom Type-in | Presets (`onus_email_mi_uf`, `onca_email_mi_en_uf`, `onca_email_mi_fr_uf`) + add arbitrary custom tags with remove chips |
| **TID** | **Multi-Select** Pills + Custom Type-in | Presets (`onem013383`, `ocem003398`) + add arbitrary custom tags with remove chips |
| **CID** | Text input (Clean) | **Category ID** (Constructor Category ID; all placeholder text removed) |
| **Recommend Sale Only?** | Y / N | Segmented tactile switch (Default: `N`) |
| **Recommend Promo Only?** | Y / N | Segmented tactile switch (Default: `N`) |
| **Recommend Clearance Only?** | Y / N | Segmented tactile switch (Default: `N`) |
| **EV_Segment 1 Enabled?** | Y / N | Segmented tactile switch (Default: `N`, presets set to `Y`) |
| **Remove trackingid** | Y / N | Segmented tactile switch (Default: `N`, presets set to `Y`) |
| **Remove CustomerID** | Y / N | Segmented tactile switch (Default: `N`) |
| **Remove Cache Token** | Y / N | Segmented tactile switch (Default: `N`, presets set to `Y`) |

---

## ✉️ Generated Email Intro Text

> *"Please find the Constructor widget configuration parameters below:"*

Includes 1-click Rich Text HTML and Plain Text clipboard support with confetti feedback, formatted badges, and macOS mock email client preview.
