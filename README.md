# Embroidery Manual Pricing (Garment/Cap) - 2025

This internal application for NW Custom Apparel helps you calculate embroidery pricing for garments and caps using fixed margins and predefined embroidery costs. The tool supports handling fees, digitizing fees, small-order logic, and stitch count extras, while allowing you to easily switch between Garment and Cap pricing modes.

## Key Features

- **Product Type Toggle:** Seamlessly switch between **Garment** and **Cap** modes. A clear status line shows which type is currently selected.
- **Simple User Inputs:** Provide:
  - Item Cost
  - Stitch Count
  - Handling Fee
  - Digitizing Fee  
  No margin or embroidery cost configuration is needed—those values are fixed and hidden from the user.
  
- **Optional Additional Logos:** Additional logos (sleeve, back-of-neck, opposite chest for garments; back/side flag and back text for caps) are tucked behind an "Additional Logos (Optional)" toggle. Click it only if you need to add logos, keeping the interface uncluttered for most cases.

- **Small Orders (<24 Units):** For orders of 1-23 items, the pricing uses the next available tier plus handling and digitizing (if toggled). After calculating, simply enter the exact quantity to see immediate updates.

- **Stitch Count >8,000:** If the stitch count exceeds 8,000, add $0.75 per additional 1,000 stitches (rounded up).

- **Rounding:** Blank cost after margin rounds up to the nearest $0.25. There is no further rounding on the final total.

- **Reference Pricing Matrix:** A "Show Pricing Matrix (Reference)" link displays a hard-coded pricing matrix for both garments and caps, updating dynamically based on the selected product type.

## Embroidery Pricing & Quantity Breaks

### Garment Main Logo
| Quantity Tier | Embroidery Cost (up to 8,000 stitches) |
|---------------|-----------------------------------------|
| 24-47         | $12.00                                  |
| 48-71         | $11.00                                  |
| 72+           | $10.00                                  |

For 1-23 garments, use 24-47 tier pricing plus handling and digitizing if toggled.

**Garment Additional Logos:**  
Sleeve, back-of-neck, and opposite chest logos follow the same tier-based cost as the main logo.

### Cap Main Logo
| Quantity Tier | Embroidery Cost (up to 8,000 stitches) |
|---------------|-----------------------------------------|
| 24-71         | $10.00                                  |
| 72-143        | $9.00                                   |
| 144-288       | $8.00                                   |
| 288+          | $7.50                                   |

For 1-23 caps, use 24-71 tier pricing plus handling and digitizing if toggled.

**Cap Additional Logos:**

- **Cap Back/Side (Flag)**  
  | Quantity Tier | Cost  |
  |---------------|-------|
  | 24-71         | $8.00 |
  | 72-143        | $7.00 |
  | 144-288       | $6.00 |
  | 288+          | $5.50 |

- **Cap Back Text Only**  
  | Quantity Tier | Cost  |
  |---------------|-------|
  | 24-71         | $7.00 |
  | 72-143        | $6.00 |
  | 144-288       | $5.00 |
  | 288+          | $4.00 |

## How to Use

1. **Select Product Type:** Toggle between Garment or Cap. A status line shows "Currently Selected: Garment" or "Currently Selected: Cap" for clarity.
2. **Enter Inputs:** Provide the item cost, stitch count, handling fee, and digitizing fee.
3. **Add Additional Logos if Needed:** Click "Additional Logos (Optional)" to reveal the logos section and configure logos as desired.
4. **Calculate:** Press "Calculate" to compute pricing. For 1-23 units, enter the exact quantity post-calculation for immediate less-min updates.
5. **View Reference Pricing:** Click "Show Pricing Matrix (Reference)" to see preset pricing tables for garments or caps.

## Notes

- Margin is fixed at 40% behind the scenes—no user adjustment needed.
- Blank cost rounds up to the nearest $0.25 after margin.
- Stitches over 8,000 add $0.75 per 1,000 stitches (rounded up).
- No final rounding on the total.
- For orders <24, use next tier pricing plus handling/digitizing if toggled.
- This streamlined UI ensures a cleaner, faster experience for sales staff, focusing on essential pricing results.
