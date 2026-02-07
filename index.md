---
layout: "default"
title: "🛠️ sql-seed - Generate SQL Data Easily"
description: "📊 Generate realistic SQL INSERT statements from CSV files with automatic type inference and customizable batch sizes for smooth database integration."
---
# 🛠️ sql-seed - Generate SQL Data Easily

[![Download sql-seed](https://img.shields.io/badge/Download-sql--seed-blue.svg)](https://github.com/imfhussain/sql-seed/releases)

## 🚀 Getting Started

Welcome to sql-seed! This application helps you create realistic SQL INSERT statements from CSV files. It automatically figures out the correct data types and can handle multiple records at once. Perfect for developers wanting to seed a database with test data without any hassle.

## 📥 Download & Install

To get started with sql-seed, follow these steps:

1. Visit this page to download: [GitHub Releases](https://github.com/imfhussain/sql-seed/releases).

2. Look for the most recent version. You will see files for different operating systems. Choose the one that fits your system.

3. Click on the appropriate file to start the download.

4. Once the download completes, locate the file on your computer. This is usually in your "Downloads" folder.

5. Open the file to run sql-seed.

## ⚙️ System Requirements

- **Operating System**: Windows 10, MacOS, or any Linux distribution.
- **Python Version**: Ensure you have Python 3.6 or higher installed on your system.

## 📂 How to Use sql-seed

Using sql-seed is straightforward. Follow these steps to generate your SQL INSERT statements:

1. Prepare your CSV file. Make sure it includes headers that match your database table’s columns.
  
2. Open a terminal or command prompt.

3. Navigate to the folder where you stored the sql-seed file. You can do this by using the `cd` command.

4. Run sql-seed by entering this command in your terminal:

   ```bash
   python sql_seed.py --file yourfile.csv --database yourdatabase
   ```

   Replace `yourfile.csv` with the name of your CSV file and `yourdatabase` with the database you want to seed.

5. The application will analyze your CSV file and generate SQL INSERT statements. 

6. Copy the generated SQL statements from your terminal and paste them into your database management tool to run.

## 🎯 Features

- **Automatic Type Inference**: sql-seed accurately identifies data types from your CSV.
- **Batch Sizing**: You can configure how many records to insert at once, optimizing performance.
- **Multi-Database Support**: Works with MySQL and PostgreSQL.

## 📄 Command-Line Options

When you run sql-seed, you can use the following options to customize its behavior:

- `--file <path>`: Specify your CSV file.
- `--database <name>`: Name of the database where data will be inserted.
- `--batch-size <number>`: Set how many records are inserted at once. Default is 100.

## 🔄 Updating sql-seed

To keep sql-seed up to date, periodically check the [GitHub Releases](https://github.com/imfhussain/sql-seed/releases) page for new versions. Follow the earlier steps to download and run newer releases.

## 🛠️ Troubleshooting

If you encounter issues while using sql-seed, here are some common problems and solutions:

- **Python Not Found**: Ensure Python is installed and added to your system's PATH variable.
- **Invalid CSV Format**: Ensure that your CSV file has a header row and each row of data lines up correctly with the headers.

## 🤝 Contributing

Your input is welcome! If you have ideas or improvements, feel free to submit a pull request. All contributions are appreciated. 

## 📞 Support

If you need help, please reach out via the Issues section on the GitHub repository. Just describe the problem you're facing, and we'll assist you as best we can.

Thank you for using sql-seed! Happy seeding!