# **ProductHunt Dataset**  

### **Dataset Overview**  
The dataset consists of **three columns**:  
- **Product Category**  
- **Product Name**  
- **Brief Product Description**  

### **Challenges**  
ProductHunt restricts automated access. Even with **undetected-chromedriver**, which is designed to bypass detection, traditional scraping methods were unsuccessful.  

### **Solutions Implemented**  
1. **ProductHunt API** – Official access was used but limited to fetching only **50 products** due to API constraints.  
2. **PDF-Based Extraction** – Product pages were downloaded as PDFs and processed using:  
   - **Langchain’s PyPDFLoader** for document parsing  
   - **OpenAI’s GPT-4** for structured data extraction  

### **Next Steps**  
- Extract and analyze the number of users per product.
