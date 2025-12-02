# Metadata Curation - Session 2

This folder contains the materials needed for **Step 2: Programmatic Metadata Curation**.

After importing the study in Step 1, you will use these files to:
- apply curation rules programmatically,
- update metadata fields,
- validate changes through the SDK.

---

## 📄 Files in This Folder

### **curation-script.txt**
A Python-based script that:
- calls the curation rules file,
- applies metadata corrections to the imported study,
- performs validation checks,
- prints status messages and errors (if any).

Replace the token in the script with your personal API token before running.

---

### **rules_for_curation.json**
This JSON file defines:
- fields to update,
- allowed values,
- normalisation or correction rules,
- validation logic.

The script will read and apply these rules automatically.

---

## ✔️ Requirements
- Study imported successfully in Step 1  
- API token available  
- Genestack SDK installed  

---

If you encounter validation errors, we will walk through troubleshooting during the session.
