# IT23177246 – Test Automation Project
**Student IT Number:** IT23177246
**Repository:** [https://github.com/Lakmi-11/IT23177246-test-automation](https://github.com/Lakmi-11/IT23177246-test-automation)

## 📌 Project Overview
This project automates the **preview functionality** of the Pixelssuite website using Playwright. The test uploads a PNG image and verifies whether the preview is displayed correctly to ensure a seamless user experience.

---

## 🛠️ Requirements
Make sure you have installed:
* Python 3.11 or higher
* Google Chrome (or Playwright browsers)

---

## ⚙️ Setup Instructions
Install required packages:
```bash
pip install playwright openpyxl
```

Install Playwright browsers:
```bash
playwright install chromium
```

---

## ▶️ How to Run the Test
Run the following command in the project folder to execute the automation:
```bash
python IT23177246_image_preview_test.py --png IT23177246_sample.png --csv IT23177246_execution_results.csv --out-dir IT23177246_results
```

---

## 📊 Test Output
After running the script:
* **CSV File** (`IT23177246_execution_results.csv`): Updated with the test result (PASS/FAIL).
* **Screenshots**: Saved in the `IT23177246_results` folder (Example: `preview_pass.png`).

---

## 📁 Project Structure
* `IT23177246_image_preview_test.py` → Main automation script
* `IT23177246_execution_results.csv` → Test results log
* `IT23177246_Manual_Test_Cases_Option_2.xlsx` → Manual test cases for Option 2
* `IT23177246_results/` → Contains execution screenshots
* `IT23177246_sample.png` → Sample image used for testing
* `IT23177246_git_link.txt` → GitHub repository link

---

## ✅ Test Scenario
* **Upload**: Automates the upload of a PNG image.
* **Verify**: Checks if the image preview is displayed on the webpage.
* **Record**: Saves the result as **PASS** or **FAIL** in the CSV and takes a screenshot.

---

## 🔗 Repository
GitHub Repository: [https://github.com/Lakmi-11/IT23177246-test-automation](https://github.com/Lakmi-11/IT23177246-test-automation)
