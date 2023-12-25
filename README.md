# Automation-with-Selenium
Automate web interactions using Selenium
from selenium import webdriver

driver = webdriver.Chrome('chromedriver.exe')  # Download and provide the path to your ChromeDriver executable
driver.get('https://example.com')

# Implement web automation tasks (e.g., form filling, button clicking)

driver.quit()
