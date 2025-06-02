# Quick File Sharing Commands
# ===========================

## 📋 Copy Files to Claude-Access Folders:

### Analysis (for documents you want analyzed):
```bash
cp ~/Documents/your-file.pdf ~/Documents/Claude-Access/Analysis/
```

### Projects (for ongoing project work):
```bash
cp ~/Documents/project-doc.docx ~/Documents/Claude-Access/Projects/
```

### Reference (for materials Claude should remember):
```bash
cp ~/Documents/reference.pdf ~/Documents/Claude-Access/Reference/
```

### Temp (for one-time analysis, delete after):
```bash
cp ~/Documents/temp-data.csv ~/Documents/Claude-Access/Temp/
```

## 🔍 Check What Claude Can See:
```bash
ls -la ~/Documents/Claude-Access/
ls -la ~/Documents/Claude-Access/*/
```

## 🗑️ Clean Up After Analysis:
```bash
# Remove temporary files
rm ~/Documents/Claude-Access/Temp/*

# Remove specific file
rm ~/Documents/Claude-Access/Analysis/filename.pdf
```

## 📁 Create Custom Folders:
```bash
mkdir ~/Documents/Claude-Access/YourCustomFolder
```

## ⚡ All-in-One File Share:
```bash
# Copy file and ask Claude to analyze in one workflow:
cp ~/Documents/important.pdf ~/Documents/Claude-Access/Analysis/ && echo "File ready for Claude analysis"
```

---
**Tip:** Always review files before copying to ensure no sensitive data!