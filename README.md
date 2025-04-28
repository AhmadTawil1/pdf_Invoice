# 📄 Excel to PDF Invoice Generator
A **Python-based tool** that converts Excel invoice files into well-formatted PDFs using **FPDF and Pandas**.  
This project automates the generation of **structured invoice PDFs** from Excel data, making invoice management efficient and professional.

## 🌟 Key Features
✔ **Excel to PDF Conversion**: Seamlessly transforms Excel invoice data into professional PDFs  
✔ **Automated Processing**: Handles bulk invoice generation efficiently  
✔ **Professional Formatting**: Creates well-structured, branded invoice layouts  
✔ **Data Validation**: Ensures accurate data transfer from Excel to PDF  
✔ **Customizable Templates**: Flexible invoice design options  
✔ **Company Branding**: Incorporates logos and custom styling

## 🛠️ Installation & Setup
1. Clone the repository:
```bash
git clone https://github.com/AhmadTawil1/pdf-Invoice.git
cd excel-to-pdf-Invoice
```

2. Install required dependencies:
```bash
pip install -r requirements.txt
```

## 📋 Prerequisites
- Python 3.7 or higher
- Required Python packages (installed via requirements.txt):
  - pandas
  - fpdf
  - openpyxl

## 🚀 Usage
1. Place your Excel invoice file in the `invoices` directory
2. Run the main script:
```bash
python main.py
```
3. Generated PDFs will be saved in the `PDFs` directory

## 📁 Project Structure
```
pdf-Invoice/
│
├── main.py              # Main script for invoice generation
├── invoices/            # Directory for Excel invoice files
├── PDFs/               # Output directory for generated PDFs
├── requirements.txt    # Project dependencies
└── README.md          # Project documentation
```

## 📝 Input Excel Format
The Excel file should contain the following columns:
- product_id
- product_name
- amount_purchased
- price_per_unit
- total_price

## 🎨 Customization
You can customize the invoice appearance by modifying:
- Company logo
- Color scheme
- Font styles
- Layout structure

## 🤝 Contributing
Contributions are welcome! Please feel free to submit a Pull Request.

## 📄 License
This project is licensed under the MIT License - see the LICENSE file for details.

## 📞 Support
For support or questions, please open an issue in the GitHub repository.

## 🙏 Acknowledgments
- FPDF library developers
- Pandas library developers
- All contributors to this project