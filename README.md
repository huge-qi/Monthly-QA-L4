# Monthly Monitoring Dashboard

A static website for recording monthly monitoring measurements, viewing trends, applying simple arithmetic formulas, and tracking approvals.

## Features
- Groups: Mechanical, Dosimetry, Imaging, Safety, Other
- Monthly records with base value, optional formula (`x` is the base value), units, lower/upper limits, and comments
- Entered-by and timestamp fields; approval name and timestamp
- Trend chart and date range filters
- CSV export and JSON backup/restore
- Browser `localStorage` autosave

## Deploy with GitHub Pages
1. Create a GitHub repository (for example `monthly-monitoring-dashboard`).
2. Upload `index.html` and this `README.md` to the repository root.
3. In the repository, open **Settings → Pages**.
4. Under **Build and deployment**, select **Deploy from a branch**.
5. Select branch **main** and folder **/(root)**, then click **Save**.
6. Wait for deployment. Your website URL will be shown on the Pages settings screen and will usually look like `https://YOUR-USERNAME.github.io/REPOSITORY/`.

## Data storage and limitations
This dashboard saves records in the browser's local storage, not in GitHub. Records are device- and browser-specific and do not automatically sync to other users or computers. Use **Backup JSON** regularly and store the backup somewhere safe. Use **Restore JSON** to load a backup.

Local browser storage is not an institution-approved audit trail, secure electronic signature, or validated clinical QA database. Avoid storing patient-identifiable or other sensitive information here.
