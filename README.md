# Blasedemo Performance Testing

This repository contains a performance testing suite developed using **Apache JMeter** to load test the Blasedemo flight booking application.

## 📁 Project Structure

* **src/**: Contains the JMeter script (`blasedemobooking.jmx`).
* **reports/**: Placeholder folder for execution logs and HTML dashboards.
* **.gitignore**: Ensures temporary test logs and heavy reports are not uploaded to GitHub.

## 🚀 How to Run the Test (CLI Mode)

To get accurate performance results, always run your JMeter tests in Non-GUI (CLI) mode using the following command from the project's root folder:

```bash
jmeter -n -t src/blasedemobooking.jmx -l reports/result.jtl -e -o reports/html-report