# Prestige Theme (HBC Customization)

This repository contains the customized **Prestige** Shopify theme (v11.0.0) for the HBC project. Prestige is a high-end, visual-driven theme designed for premium brands.

## 🚀 Getting Started

To work on this theme locally, you will need the [Shopify CLI](https://shopify.dev/docs/themes/tools/cli) installed.

### Prerequisites

- Node.js (latest LTS recommended)
- Shopify CLI
- A Shopify store for development/testing

### Local Development

1. **Clone the repository:**
   ```bash
   git clone https://github.com/wanybae/hbc-prestige-theme.git
   cd hbc-prestige-theme
   ```

2. **Authenticate with Shopify:**
   ```bash
   shopify login --store your-store-name.myshopify.com
   ```

3. **Start the development server:**
   ```bash
   shopify theme dev
   ```

4. **Pull latest changes from the store (optional):**
   ```bash
   shopify theme pull
   ```

## 📁 Project Structure

- `assets/`: Contains CSS, JavaScript, and image files.
- `blocks/`: Liquid block files for theme sections.
- `config/`: Configuration files for theme settings (`settings_schema.json` and `settings_data.json`).
- `layout/`: Theme layout files (e.g., `theme.liquid`).
- `locales/`: Translation files for internationalization.
- `sections/`: Reusable theme sections.
- `snippets/`: Reusable Liquid code snippets.
- `templates/`: JSON and Liquid templates for different page types.

## 🛠 Customizations

This theme includes specific customizations for the HBC brand. Please ensure any changes maintain the visual integrity and performance standards of the original Prestige theme.

## 📚 Documentation

- [Prestige Theme Documentation](https://support.maestrooo.com/)
- [Shopify Theme Development Documentation](https://shopify.dev/docs/themes)

---

**Author:** Maestrooo (Original) / wanybae (Customizations)
**Version:** 11.0.0
