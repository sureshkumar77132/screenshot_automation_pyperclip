import webbrowser
import random 
from selenium import webdriver
import webbrowser, sys, pyperclip
driver=webdriver.Firefox()


if len(sys.argv) > 1:
    # Get address from command line.
    address = ' '.join(sys.argv[1:])  //enter the address of the site to check with the site 
else:
    # Get address from clipboard.
    address = pyperclip.paste()       //Automatically paste the content from the command line 
     

    driver.get('https://sitecheck.sucuri.net/results/' + address) //here you can paste any web site links what to you want to get the results 
    driver.save_screenshot("screenshot-"+str(random.choice([1, 4, 8, 10, 3, 50, 89, 65]))+".png")
    driver.close()

