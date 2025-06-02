# Complete File Analysis Guide for MCP Server on Mac
*Created: May 23, 2025*

## 🎯 Overview

Your MCP server provides powerful file analysis capabilities directly on your Mac. This guide shows you all the ways to load, analyze, and extract insights from your files.

## 📁 Available Tools

### 1. **File System Operations**
- `list_directory` - See what's in any folder
- `directory_tree` - Get full folder structure
- `search_files` - Find files by pattern
- `get_file_info` - Get file metadata (size, dates, permissions)

### 2. **File Reading**
- `read_file` - Read single files
- `read_multiple_files` - Read several files at once
- `edit_file` - Make changes to files

### 3. **Analysis Engine**
- `repl` (Analysis Tool) - JavaScript analysis engine for processing data
- Complex calculations and data manipulation
- CSV/JSON parsing and analysis
- Pattern recognition and insights

## 🔍 Step-by-Step Analysis Examples

### **Example 1: Configuration File Analysis**

**Step 1:** Read the file
```
Ask: "Can you read my config.json file in the trading-platform folder?"
```

**Step 2:** Analyze with code
```
Ask: "Use the analysis tool to extract key metrics from this configuration"
```

**Result:** Detailed breakdown of settings, risk parameters, and recommendations

### **Example 2: Log File Analysis**

**Step 1:** Find log files
```
Ask: "Search for all .log files in my directories"
```

**Step 2:** Read and analyze
```
Ask: "Read the access-log.txt and analyze the security patterns"
```

**Result:** Security insights, activity patterns, and recommendations

### **Example 3: Multiple File Comparison**

**Step 1:** Read several files
```
Ask: "Read all markdown files in my Financial-Analysis folder"
```

**Step 2:** Compare and analyze
```
Ask: "Compare these files and find common themes using analysis"
```

**Result:** Cross-file analysis, pattern identification, and insights

### **Example 4: Code Analysis**

**Step 1:** Read Python/code files
```
Ask: "Read my main.py file and analyze the code structure"
```

**Step 2:** Analyze architecture
```
Ask: "Use analysis to evaluate code quality, dependencies, and architecture"
```

**Result:** Code quality metrics, security analysis, and improvement suggestions

## 📊 File Types I Can Analyze

### **✅ Fully Supported**
- **Text files** (.txt, .md, .rtf)
- **Configuration** (.json, .yaml, .config)
- **Code files** (.py, .js, .html, .css)
- **Data files** (.csv - with analysis tool)
- **Log files** (.log, access logs)
- **Documentation** (.md, .rtf)

### **🔧 With Analysis Tool**
- **CSV data** - Full spreadsheet analysis
- **JSON data** - Complex data structure analysis
- **Large datasets** - Statistical analysis
- **Complex calculations** - Mathematical processing

## 🎯 Common Analysis Patterns

### **1. Security Analysis**
```
"Read my security logs and identify any concerning patterns"
```

### **2. Configuration Review**
```
"Analyze my platform configuration for optimization opportunities"
```

### **3. Documentation Analysis**
```
"Read all my guides and create a summary of key topics"
```

### **4. Data Processing**
```
"Load this CSV file and give me statistical insights"
```

### **5. Code Review**
```
"Analyze my Python code for quality and security issues"
```

## 🔍 Advanced Analysis Techniques

### **Pattern Recognition**
- Identify recurring themes across documents
- Find security patterns in logs
- Detect configuration inconsistencies
- Analyze code quality patterns

### **Cross-File Analysis**
- Compare multiple documents
- Find relationships between files
- Identify missing components
- Track changes over time

### **Statistical Analysis**
- CSV data processing
- Financial data analysis
- Performance metrics
- Risk calculations

### **Content Extraction**
- Key information extraction
- Summary generation
- Insight identification
- Recommendation creation

## 📝 How to Request Analysis

### **Simple File Reading**
```
"Can you read my [filename] and tell me what it contains?"
```

### **Targeted Analysis**
```
"Analyze my [filename] for [specific aspect - security, performance, etc.]"
```

### **Complex Analysis**
```
"Use the analysis tool to process my [filename] and extract [specific insights]"
```

### **Multi-File Analysis**
```
"Read all files in [folder] and find common patterns"
```

### **Data Processing**
```
"Load my CSV file and calculate [specific metrics]"
```

## 🚨 Security & Privacy

### **Safe Files to Analyze**
- ✅ Configuration files (without credentials)
- ✅ Documentation and guides
- ✅ Code files
- ✅ Log files (sanitized)
- ✅ Analysis data

### **Files to Avoid**
- ❌ Personal financial data
- ❌ Authentication credentials
- ❌ Private correspondence
- ❌ Sensitive business information

## 💡 Pro Tips

### **1. Be Specific**
Instead of: "Analyze this file"
Try: "Analyze this configuration for security issues and optimization opportunities"

### **2. Use the Analysis Tool for Complex Data**
For CSV, JSON, or complex calculations, specifically ask for the analysis tool:
"Use the analysis tool to process this data and calculate statistics"

### **3. Ask for Multiple Perspectives**
"Analyze this from both security and performance perspectives"

### **4. Request Actionable Insights**
"What specific actions should I take based on this analysis?"

### **5. Combine Multiple Files**
"Read these 3 files and find connections between them"

## 🔧 Troubleshooting

### **File Not Found**
- Check the exact file path
- Use `list_directory` to see available files
- Ensure file is in `/Users/benitomartinlopez/Documents/Claude-Access/`

### **Analysis Not Detailed Enough**
- Ask specifically for the analysis tool
- Request specific metrics or insights
- Break complex analysis into steps

### **Large Files**
- For very large files, ask for specific sections
- Use the analysis tool for processing
- Consider breaking into smaller chunks

## 🎯 Example Requests

### **Quick Analysis**
```
"What's in my access-log.txt file?"
```

### **Detailed Analysis**
```
"Read my trading platform configuration and use the analysis tool to evaluate the risk management settings, then provide recommendations for optimization"
```

### **Comparative Analysis**
```
"Read all markdown files in my Financial-Analysis folder and identify the key themes, then create a summary of the most important concepts across all documents"
```

### **Data Processing**
```
"Load my portfolio data CSV and calculate return statistics, risk metrics, and provide investment insights using the analysis tool"
```

---

## 🚀 Ready to Analyze!

Your MCP server is ready to analyze any file type. Just specify what you want to analyze and what insights you're looking for!

**Quick Start:** Try saying "Can you read my [filename] and analyze it for [what you want to know]?"
