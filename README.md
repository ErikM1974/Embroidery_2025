# Embroidery Margin & Costs Calculator (2025)

This application is designed to help you calculate embroidery pricing for garments and caps based on various parameters such as item cost, stitch count, handling fee, digitizing fee, and margins. It supports multiple tiers, additional logos, and applies specific rules for small orders and stitch counts.

## What Does the App Do?

- **Toggle Product Type:** Switch between **Garment** and **Cap** pricing modes.
- **User Inputs:** Enter base item cost, stitch count, handling fee, and digitizing fee.
- **Margins & Costs per Tier:** Define margin percentages and embroidery costs for different quantity tiers.
- **Additional Logos:** Add sleeve, back-of-neck, opposite chest (garment), or back/side (flag) and back text (cap) logos, each with their own cost structure.
- **Small Orders (<24):** For quantities 1-23, use the next available tier pricing plus handling and digitizing (if toggled on).
- **Stitch Count >8,000:** Adds $0.75 per thousand stitches (rounded up) beyond 8,000.
- **Rounding:** Blank cost rounds up to the nearest $0.25; no final rounding on the total price.

## Embroidery Pricing & Quantity Breaks

### Garment Pricing (Main Logo)
| Quantity Tier | Embroidery Cost (up to 8,000 stitches) |
|---------------|-----------------------------------------|
| 24-47         | $12.00                                  |
| 48-71         | $11.00                                  |
| 72+           | $10.00                                  |

For 1-23 garments, use 24-47 tier pricing plus handling and digitizing fees (if toggled).

**Garment Additional Logos:**  
Sleeve, back-of-neck, and opposite chest logos use the same tier-based cost as the main logo.

### Cap Pricing (Main Logo)
| Quantity Tier | Embroidery Cost (up to 8,000 stitches) |
|---------------|-----------------------------------------|
| 24-71         | $10.00                                  |
| 72-143        | $9.00                                   |
| 144-288       | $8.00                                   |
| 288+          | $7.50                                   |

For 1-23 caps, use the 24-71 tier pricing plus handling and digitizing fees (if toggled).

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

### Small Orders (1-23)

For both garments and caps, orders under 24 units use the next tier’s pricing plus handling and digitizing fees if toggled. The exact quantity must be entered after pressing "Calculate."

### Stitches Over 8,000

For stitch counts above 8,000, add $0.75 per additional 1,000 stitches (rounded up).

## How to Use

1. **Select Product Type:** Use the toggle to choose Garment or Cap.
2. **Enter Inputs:** Provide item cost, stitch count, handling fee, and digitizing fee.
3. **Configure Margins & Costs:** Set margin percentages and embroidery costs for each tier.
4. **Add Additional Logos:** Enable logos, set their stitch counts, and toggle digitizing if needed.
5. **Calculate:** Press "Calculate" to see results.  
   For the 1-23 tier, enter exact quantity after calculation to apply less-min pricing.
   
## Notes

- Blank cost is calculated after applying the margin, then rounded up to the nearest $0.25.
- No final rounding on the total cost.
- Stitches over 8,000 add $0.75/1000 stitches.
- This tool helps dial in pricing to ensure your margins and final prices align with your business goals.
