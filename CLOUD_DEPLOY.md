# Deploying to Streamlit Community Cloud

1. Create a new public GitHub repo (e.g., `vsm-observer-form`).
2. Upload all files from this folder into the repo (keep the same structure).
3. Go to https://share.streamlit.io -> New app:
   - Repository: your `vsm-observer-form`
   - Branch: main
   - Main file path: `app.py`
   - (Optional) Advanced: ensure Python = 3.11 (runtime.txt provided)
4. Click Deploy.

Troubleshooting:
- If PPTX/PDF export errors, check Logs in "Manage app".
- Make sure `requirements.txt` installed successfully.
- If you change any file, commit & push → app redeploys automatically.