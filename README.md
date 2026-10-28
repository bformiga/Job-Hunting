# Job Hunting

Personalized employer collector and Google Sheets application tracker. Adapted from nautry/job-search-tracker (reference commit a973b8af464860298afcac1e0ca413545a621aac).

Primary: computer architecture, ASIC/SoC, RTL, verification, FPGA and silicon hardware. Secondary: embedded, software, networks and data science. May 2027 graduation and earliest start. Nationwide US. Salary above USD 70,000 is a preference requiring manual review, not a hard filter.

Run `python -m src.puller`. Configure sources in config/boards.json and matching in config/preferences.json. Source failures and partial coverage are recorded in data/jobs.json. A configured employer is not proof of working coverage. Failed sources retain past records without advancing last_seen. Scores are prioritization aids, not hiring probabilities.

See START_HERE.md for activation and CHECK_JOBS.md for daily review. Never commit resumes, contact information, credentials, application statuses, or notes here.
