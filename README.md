# Google-Sheet-AI-Content-Wizard
Generate personalized email openers, subject lines, SMS and cold calling script, for each of your lead, using AI.
The code and content are sponsored by VBOUT and Openbuild AI.
VBOUT is the industry leading platform for Email Marketing, Automation and AI chatbots. With over 14 marketing tools combined, marketers can generate leads, nurture them using automation and retain relationships with paid customer, all from one dashboard.
For a comprehensive demo of VBOUT, visit https://www.vbout.com .


This guide will walk you through the process of installing and using the provided Google Apps Script to generate email openers, cold calling scripts, SMS copy, and website analysis with outreach suggestions. This enhanced version includes support for different OpenAI models and clarifies column usage.
Prerequisites
•	Google Account: You'll need a Google account to access Google Sheets and Apps Script.
•	OpenAI API Key: Sign up for an OpenAI account at https://platform.openai.com/ and obtain an API key. This key is necessary to access the GPT models.
•	Google Sheet: Prepare a Google Sheet with the following columns in the exact order (do not alter the column order, add, or remove columns without updating the corresponding values in the script): 
o	Column A: Contact Email
o	Column B: Contact Phone
o	Column C: First Name
o	Column D: Last Name
o	Column E: Full Name
o	Column F: Website
o	Column G: Company Name
o	Column H: Seniority
o	Column I: Departments
o	Column J: Industry
o	Column K: Personal Linkedin Url
o	Column L: Website Scraping and AI Personalization 🧠
o	Column M: Technologies
o	Column N: Annual Revenue
o	Column O: Website SEO Title
o	Column P: GPT Personalized Email Opener 🧠
o	Column Q: GPT Personalized Subject Line 🧠
o	Column R: GPT Personalized Call Script 🧠
o	Column S: GPT Personalized SMS 🧠
o	Column T: GPT Personalized Video 🧠 (Unavailable)
o	Column V: GPT Personalized Music 🧠 (Unavailable)
o	Column W: Personalized Gif URL
Installation
1.	Choose Your Model:
o	You have 3 script files available, each optimized for a different OpenAI model: 
	gpt-3.5-turbo.js (most cost-effective)
	gpt-4-1106-preview.js (most powerful)
	gpt-4o-mini.js (balance of cost and performance)
o	Select the script file that corresponds to the model you want to use.
2.	Open Script Editor:
o	In your Google Sheet, go to "Extensions" > "Apps Script."
3.	Copy and Paste the Script:
o	Copy the entire content of the chosen script file and paste it into the Apps Script editor.
4.	Replace API Key:
o	Replace YOUR_API_KEY_HERE with your actual OpenAI API key.
5.	Save the Script:
o	Click "File" > "Save" (or Ctrl+S).
6.	Authorize the Script:
o	Run any of the functions (e.g., click the "Run" button next to generateEmailOpeners).
o	A dialog box will appear asking you to authorize the script. Review the permissions and click "Allow."
7.	Refresh the Sheet:
o	Go back to your Google Sheet and refresh it.
Usage
1.	Access Custom Menu:
o	You should now see a "Custom Menu" in your Google Sheet's menu bar.
2.	Generate Content:
o	Click "Custom Menu" to see the available functions: 
	Generate Email Openers: Generates email openers and subject lines.
	Generate Cold Calling Scripts: Generates cold calling scripts.
	Generate SMS Copy: Generates SMS copy.
	Analyze Website & Suggest Outreach: Scrapes website content, summarizes it, and suggests outreach strategies.
3.	Select Function:
o	Click the function you want to execute. The script will run and populate the corresponding columns in your sheet with the generated content.
Important Notes
•	API Usage: Be mindful of your OpenAI API usage and potential costs. Monitor your usage on the OpenAI platform.
•	Error Handling: The script does not include extensive error handling. Consider adding try...catch blocks to handle potential errors during API calls or web scraping.
•	Adjust max_tokens: Modify the max_tokens parameter in each function to control the length of the generated content.
•	Customize Prompts: Feel free to adjust the prompts in each function to better suit your specific needs and preferences.
•	Website Scraping: The analyzeWebsiteAndSuggestOutreach function uses IMPORTXML to scrape website content. You might need to adjust the XPath expression (//p) based on the website structure.
•	Column Order: Do not alter the column order, add, or remove columns in the sheet without updating the corresponding column indexes in the script. For example, if you move "Website URL" to column G, you need to change 'F' + (i + 1) to 'G' + (i + 1) in the analyzeWebsiteAndSuggestOutreach function.
This comprehensive guide should help you effectively install and utilize the script for generating sales content and analyzing websites.

You have full license to use the script on your own Google Sheets accounts, for personal or commercial use. The finished code is proprietary of VBOUT and any distribution must be credited back to the original author.
