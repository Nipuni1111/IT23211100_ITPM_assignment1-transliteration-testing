# IT23211100_ITPM_assignment1-transliteration-testing1

Playwright-based automation for testing Singlish to Sinhala transliteration accuracy | IT23211100 | IT3040 ITPM Assignment 1 | SLIIT Year 3

GITHUB LINK  - https://github.com/Nipuni1111/IT23211100_ITPM_assignment1-transliteration-testing.git

# IT23211100 – IT3040 Assignment 1

##  Project Title
Automated Testing for Singlish to Sinhala Transliteration System

##  Repository

https://github.com/Nipuni1111/IT23211100_ITPM_assignment1-transliteration-testing.git

##  Project Structure

IT3040_Assignment_1/

- test_automation.py           → Playwright automation script  
- IT - Test cases.xlsx → Excel file with test cases & results  
- requirements.txt             → Python dependencies  
- README.md                    → Project documentation  
- venv/ (optional)             → Virtual environment (not required)

---

##  Technologies Used

- Python  
- Playwright (UI Automation)  
- OpenPyXL (Excel handling)

---
## Prerequisites
Before running, make sure you have:
- Windows PC
- Python 3.11 or 3.12 installed → https://www.python.org/downloads/
- Google Chrome installed (recommended)


##  How to Run the Project

1. Open terminal inside project folder  

2. (Optional) Activate virtual environment  
   venv\Scripts\activate  

3. Install dependencies  
   pip install -r requirements.txt  
   playwright install  

4. Run the automation script  
   python test_automation.py --excel "IT - Test cases.xlsx" --url "https://www.pixelssuite.com/chat-translator"  

---
## How to Check Results

1. Go to the test_automation folder
2. Open "Assignment 1 - Test cases.xlsx"
3. Check the "Actual output" and "Status" columns
   - Pass = transliteration is correct
   - Fail = transliteration is incorrect

---

##  Output

- Results are automatically written to the Excel file  
- Columns updated:
  - Actual output  
  - Status (PASS / FAIL)  

---

##  Test Case Details

- Total Test Cases: 50+  
- Test Type: Negative Testing  

### Covered Scenarios:
- Mixed language inputs (Singlish + English)  
- Spelling variations  
- Emojis & symbols  
- Real-world scenarios (banking, travel, apps)  
- System-related messages (errors, logs)  
- Numeric and date inputs  

---

##  Important Notes

- This system uses strict comparison  
- Even small differences in Sinhala output (spacing, formatting, spelling) will result in FAIL  
- Some failures are expected due to:
  - Transliteration inconsistencies  
  - Mixed language complexity  
  - UI timing delays  

---

##  Student Information

- Student ID: IT23211100
- Studenet Name: Henegge.N.G.L.P
- Module: IT3040  
- Assignment: Assignment 1 (Option 1)  

---

##  Final Status

✔ Automation script working  
✔ Excel-based validation completed  
✔ Test coverage includes multiple edge cases  

---

##  Submission Notes

- Virtual environment (venv) is excluded from submission  
- All required files are included  
- Project is fully runnable using requirements.txt  


