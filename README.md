# Multimedia Inventory

Hebrew RTL inventory and installation management, delivered as a standalone HTML application.

This public distribution starts with no inventory, customers, jobs, price catalog, email recipients, or personal video. Business data entered or imported in the browser is saved only in that browser's local storage. It is not uploaded to this repository or synchronized between users.

Open `index.html` locally or use the GitHub Pages website. No server or build dependencies are required. Inventory minimum thresholds, order quantities, and email recipients can be configured in the inventory interface. Email drafts use the computer's configured mail handler; the application does not send email automatically.

Use JSON backup and restore to move your own data between the local file and the website. Browser storage is separate for each origin; opening the website does not automatically import data from the local HTML file. A downloaded shared HTML or JSON backup contains your business data and must not be committed to this public repository.

Bundled third-party license notices are in `licenses/`.