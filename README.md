## Selenium Grid demo

1. Start the Selenium Grid standalone Chrome container:
   ```bash
   ./run-selenium-grid-chrome-standalone.sh
   ```
   This script launches a single-node grid that exposes the WebDriver endpoint on `http://127.0.0.1:14444/wd/hub`.

2. Run the Selenium demo script that visits the PTT homepage and prints the page HTML and cookies:
   ```bash
   python selenium-demo.py
   ```
