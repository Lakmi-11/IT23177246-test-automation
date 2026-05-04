# Test Automation Project - Option 2
**Student IT Number:** IT23177246
**Repository:** [https://github.com/Lakmi-11/IT23177246-test-automation](https://github.com/Lakmi-11/IT23177246-test-automation)

## 📌 Project Overview
This project contains an automated test suite for the **PixelsSuite PNG Converter** tool. It specifically tests the **Image Preview** functionality to ensure that images uploaded by users are correctly rendered in the preview area.

## 🚀 Installation Instructions
To set up the environment and install dependencies, follow these steps:

1. **Install Playwright:**
   ```bash
   pip install playwright
   playwright install chromium
   ```

## 🛠️ How to Run the Tests
You can run the automation script using Python. By default, it will use the provided sample image and generate results in the results folder.

```bash
python IT23177246_image_preview_test.py --png IT23177246_sample.png --csv IT23177246_execution_results.csv --out-dir IT23177246_results
```

### Command Line Arguments:
- `--url`: The target URL (default is PixelsSuite converter).
- `--png`: Path to the image file to upload.
- `--out-dir`: Directory where screenshots will be saved.
- `--csv`: Path to the CSV file where results will be appended.

## 📁 Required Submission Files
- `IT23177246_image_preview_test.py`: The core Playwright automation script.
- `IT23177246_execution_results.csv`: Log of test executions.
- `IT23177246_Manual_Test_Cases_Option_2.xlsx`: Detailed manual test cases as required for Option 2.
- `IT23177246_git_link.txt`: Link to this GitHub repository.
- `IT23177246_sample.png`: Test data (sample image).
- `IT23177246_results/`: Folder containing automated screenshots of the test results.
