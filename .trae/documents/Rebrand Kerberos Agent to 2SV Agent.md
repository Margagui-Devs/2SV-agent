I will rebrand "Kerberos Agent" to "2SV Agent" by updating text and display strings across the frontend, backend, and documentation, ensuring no functional code or internal identifiers are broken.

### Frontend (UI)
1.  **Update Page Title**:
    -   `ui/public/index.html`: Change `<title>` from "Kerberos Agent..." to "2SV Agent...".
2.  **Update Branding Components**:
    -   `ui/src/pages/Login/blocks/Footer/Footer.jsx`: Change "Kerberos.io" to "2SV Agent".
    -   `ui/src/pages/Login/blocks/Logo/Logo.jsx`: Change logo alt text and `<h3>` from "Kerberos.io" to "2SV Agent".
3.  **Update Dashboard & Settings**:
    -   `ui/src/pages/Dashboard/Dashboard.jsx`: Change "Kerberos Hub" card title to "2SV Hub".
    -   `ui/src/pages/Settings/Settings.jsx`: Update dropdown labels, search tags, and link texts from "Kerberos Hub/Vault" to "2SV Hub/Vault".
4.  **Update Translations**:
    -   `ui/public/locales/**/*.json`: Iterate through all language files and replace user-facing strings containing "Kerberos Agent", "Kerberos Hub", and "Kerberos Vault" with "2SV Agent", "2SV Hub", and "2SV Vault".

### Backend (Go)
1.  **Update Startup Logs**:
    -   `machinery/main.go`: Change the startup log message "You are currently running Kerberos Agent..." to "You are currently running 2SV Agent...".
2.  **Update ASCII Art**:
    -   `machinery/src/utils/main.go`: Replace the "Kerberos Agent" ASCII art with "2SV Agent".
3.  **Update API Documentation**:
    -   `machinery/docs/swagger.yaml` & `machinery/docs/docs.go`: Update the API Title and Description to "2SV Agent API".

### Documentation
1.  **Update README**:
    -   `README.md`: Update the project title and descriptive text from "Kerberos Agent" to "2SV Agent" and related product names (Hub/Vault) to "2SV Hub/Vault".

This plan ensures a complete visual rebrand while preserving all underlying functionality, configuration keys, and API endpoints.