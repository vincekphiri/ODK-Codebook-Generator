# 📘 ODK XLSForm Codebook Generator

This repository contains R Markdown code that generates a **codebook** from an **ODK XLSForm**. The code reads the `survey` and `choices` sheets from your XLSForm Excel file and produces a structured, human-readable codebook in **HTML** and **Word** formats.  

---

## 🚀 Features
- Automatically installs and loads required R packages.  
- Reads **survey** and **choices** sheets from an XLSForm.  
- Cleans and organizes variable information.  
- Generates a **codebook table** with:  
  - Variable names  
  - Question labels  
  - Data types  
  - Response options and labels  
- Outputs to **HTML** and **Word**.  

---

## 📂 Repository Structure
```
├── README.md            # Instructions for use
├── codebook.Rmd         # R Markdown script
├── example_form.xlsx    # (Optional) Example XLSForm
└── outputs/             # Generated codebooks
```

---

## 🛠️ Requirements
- **R (≥ 4.0)**  
- **RStudio** (recommended)  
- The following R packages (installed automatically if missing):  
  - `pacman`, `tidyverse`, `readxl`, `knitr`, `kableExtra`, `rmarkdown`

---

## ⚙️ Setup
1. Clone this repository:
   ```bash
   git clone https://github.com/<your-username>/<repo-name>.git
   cd <repo-name>
   ```

2. Open **RStudio** (or R console).  

3. Open `codebook.Rmd`.  

4. Update the Excel file path in the script to point to your XLSForm:
   ```r
   file_path <- "C:/path/to/your/ODKform.xlsx"
   ```

---

## ▶️ Usage
1. Run all code chunks in the `codebook.Rmd` file.  
2. Or click **"Knit"** in RStudio to render outputs.  
3. The codebook will be generated as:  
   - **HTML document**  
   - **Word document**  

Outputs will appear in the project directory (or in `outputs/` if you configure one).  

---

## 📑 Example Output
The generated codebook includes:  
- **Variable name**  
- **Question text (label)**  
- **Data type** (e.g., text, integer, select_one, select_multiple)  
- **Response options** and their labels  

Displayed in a clean, interactive table.  

---

## 🤝 Contributing
Contributions are welcome! Fork the repo, make your changes, and open a pull request.  

---

## 📜 License
This project is licensed under the **MIT License** – free to use, modify, and share.  

---

## 👨‍💻 Author
This code was developed by **Vincent Katunga-Phiri**.  

