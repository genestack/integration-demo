# Dictionaries & Ontologies - Session 2

This folder contains the files for **Step 3: Importing Custom Ontologies and Dictionaries**.

In this part of the session, you will learn how to:
- import custom ontology structures,
- manage hierarchical vocabularies,
- extend metadata schemas using the SDK.

---

## 📄 Files in This Folder

### **import-dictionary.txt**
Instructions and script to import dictionaries.  
It explains:
- how to select a dictionary from the list,
- how to use S3 links,
- where to insert your API token,
- how to run the import command.

**Note:**
Dictionaries must be imported using a **root-level** token.
Only dictionaries imported with elevated permissions can be recognised via SDKs and used in automated template imports.

---

### **path_to_dictionary.json**
This file contains:
- S3 URLs for the pre-prepared dictionaries,
- each dictionary’s name and description,
- the information the script reads to upload the dictionary.

---

### **custom-dictionary-1.json** - [R&D Phase](https://bio-test-data.s3.us-east-1.amazonaws.com/Training-Session-SRL/Dictionaries/RD_Phase.csv)  
### **custom-dictionary-2.json** - [Information Classification](https://bio-test-data.s3.us-east-1.amazonaws.com/Training-Session-SRL/Dictionaries/information_classification.csv)  
### **custom-dictionary-3.json** - [Regulatory Region](https://bio-test-data.s3.us-east-1.amazonaws.com/Training-Session-SRL/Dictionaries/Regulatory_Region.csv)
Three customised dictionaries created specifically for the QIAGEN PoC.

They demonstrate:
- hierarchical structures,
- controlled terms,
- vocabulary extension principles.

You will pick one of these during the exercise.

---

## Before You Begin
- Ensure your study is imported and curated up to Step 2  
- Confirm your API token  
- Check that the Genestack SDK is installed  

If you have questions during the exercise, feel free to ask during the live session.
