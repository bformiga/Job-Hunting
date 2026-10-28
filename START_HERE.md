# Activate your Google Sheet

1. Open your Job Hunting Google Sheet. Choose Extensions > Apps Script.
2. Replace the default Code.gs with google_apps_script/Code.gs from this repository. Save.
3. Select syncJobs in the function dropdown and click Run. Review Google's requested permissions. This personal script uses the current spreadsheet and fetches the public GitHub feed; an unverified-app warning can appear for your own unpublished script. Only proceed after reviewing the code and requested scopes.
4. Run installDailyTrigger once. Reload the Sheet. The Job search menu now offers manual refresh.
5. Confirm Settings B5 says Sync succeeded. Confirm Sources and Apply Next populate. Unknown Dates contains listings without verified publication dates.

The bound copy does not update when GitHub Code.gs changes. Replace it manually after script changes.

GitHub collection runs at 11:23 UTC (7:23 AM EDT / 6:23 AM EST). Sheet sync runs during 15:00–16:00 UTC (11 AM–noon EDT / 10–11 AM EST). Both run with your computer off after activation. GitHub and Google schedules may be delayed. Stale feed checks stop an old feed from being presented as current.

To collect manually: GitHub repository > Actions > Daily employer search > Run workflow > main > Run workflow.

Live Apps Script authorization and a successful real sync must be verified in your account; local mocks cannot prove this.

Google Sheet: https://docs.google.com/spreadsheets/d/1vZbhdFwnld0tThBQXTyEFfEoPgZgkHzr_1UG72p4vOQ/edit
