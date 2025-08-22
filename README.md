# Merge CSV - By Bankai

![Merge CSV Logo](https://raw.githubusercontent.com/w4rrl3ss/merge_csv/refs/heads/main/csv.png)

A powerful desktop application for merging CSV files from multiple folders with advanced processing options and a sleek dark theme interface.

## Features

### Multi-Folder Processing
Process CSV files from multiple folders simultaneously with intelligent filtering based on folder names.

### FastStartup & Shutdown Modes
Choose between FastStartup and Shutdown modes with automatic file detection for each mode.

### Comma to Dot Conversion
Optionally convert comma decimal separators to dots for numeric values in your CSV files.

### Dark Theme UI
Enjoy a sleek, modern dark theme interface that's easy on the eyes during extended use.

### Progress Tracking
Monitor processing progress with a visual progress bar and detailed logging.

### Export Results
Export merged data to a new CSV file with customizable filename and location.

## How to Use

1. Select the root directory containing your CSV folders
2. Choose the processing mode (FastStartup or Shutdown)
3. Optionally enable comma to dot conversion for numeric values
4. Select output directory and filename (automatically generated based on mode)
5. Click "Start Processing" to begin merging CSV files
6. Review the results and click "Export to CSV" to save the merged data
7. Use "Clear Results" to reset the application for a new operation

## Technical Details

**Built with:** Python, PyQt5

**Compatibility:** Windows executable available (can be compiled for other platforms)

**Processing:** Multi-threaded operation to prevent UI freezing during file processing

**Output Format:** CSV files with columns: Source Folder, Region, Duration (s), Start Time (s), Stop Time (s)

## Download

[View on GitHub](https://github.com/w4rrl3ss/merge_csv) | [Download Executable](https://github.com/w4rrl3ss/merge_csv/releases)

## Screenshot

![Merge CSV Interface](https://raw.githubusercontent.com/w4rrl3ss/merge_csv/refs/heads/main/merge_csv.png)

---

Merge CSV - By Bankai © 2025. All rights reserved.

This application is provided as-is without warranty. Use at your own risk.
