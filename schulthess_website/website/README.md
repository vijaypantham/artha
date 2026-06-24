# Schulthess India - Static Website

This directory contains the production-ready static website assets for `schulthess.in`. It has been fully audited, removing all e-commerce online ordering, shopping cart drawers, and checkout capabilities.

## Directory Structure
- `index.html` - Home Page (with interactive premium slideshow and callouts)
- `shop.html` - Appliance Catalog (with interactive category filters, specifications, product details quick view modals, and enquiry forms)
- `products.html` - Professional Ranges & Specifications Page
- `about.html` - Swiss Heritage and Distributorship Info Page
- `contact.html` - Inquiry / Quote Form (with automatic product query pre-filling)
- `styles.css` - Custom styling sheet
- `images/` - Cleaned assets directory containing only the 23 referenced images (no loose layouts or files)

## Cloudflare Pages Configuration
- **Root Directory**: `schulthess_website/website/` (or `/` if deploying from a repository containing only these static files)
- **Build Command**: None (leave empty)
- **Output Directory**: `.` (or empty)
