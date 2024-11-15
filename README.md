# Google Sheet AI Content Wizard Installation Guide  

### Overview  
Generate personalized email openers, subject lines, SMS, and cold-calling scripts for each of your leads using AI. This guide provides a **basic and free alternative** to platforms like Clay tables, powered by **Google Apps Script** and OpenAI.  

The code and content are sponsored by **[VBOUT](https://www.vbout.com)** and **[Openbuild AI](https://www.openbuild.ai)**, developed by **Richard Fallah**.  
VBOUT is a leading platform for email marketing, automation, and AI chatbots, offering over 14 marketing tools in one dashboard. For a full demo of VBOUT, visit [https://www.vbout.com/demo](https://www.vbout.com/demo).  

### Resources  
- 📹 **Video Tutorial:** [Step-by-Step Video Guide](https://youtu.be/mwS_0VLPiH4)  
- 📝 **Sample Google Sheet:** [Google Sheet Template](https://docs.google.com/spreadsheets/d/1WoV6zwcd1Ov5L4AGICUU9Rz6Xxtua-z-VjlPtKMqcMk/edit?usp=sharing)  
- 💻 **Github Code Repository:** [Google-Sheet-AI-Content-Wizard](https://github.com/richardfallah/Google-Sheet-AI-Content-Wizard)  

---

### Prerequisites  
1. **Google Account:** Access Google Sheets and Apps Script.  
2. **OpenAI API Key:** Obtain an API key from [OpenAI](https://platform.openai.com/).  
3. **Prepared Google Sheet:**  
   - Use the following columns in this exact order:  
     - Column A: Contact Email  
     - Column B: Contact Phone  
     - Column C: First Name  
     - Column D: Last Name  
     - Column E: Full Name  
     - Column F: Website  
     - Column G: Company Name  
     - Column H: Seniority  
     - Column I: Departments  
     - Column J: Industry  
     - Column K: Personal LinkedIn URL  
     - Column L: Website Scraping and AI Personalization 🧠  
     - Column M: Technologies  
     - Column N: Annual Revenue  
     - Column O: Website SEO Title  
     - Column P: GPT Personalized Email Opener 🧠  
     - Column Q: GPT Personalized Subject Line 🧠  
     - Column R: GPT Personalized Call Script 🧠  
     - Column S: GPT Personalized SMS 🧠  
     - Column T: GPT Personalized Video 🧠 (Unavailable)  
     - Column V: GPT Personalized Music 🧠 (Unavailable)  
     - Column W: Personalized GIF URL  

---

### Installation Steps  

1. **Choose Your Model:**  
   Select from the provided script files based on your requirements:  
   - `gpt-3.5-turbo.js` - Cost-effective.  
   - `gpt-4-1106-preview.js` - High-performance.  
   - `gpt-4o-mini.js` - Balanced performance and cost.  

2. **Open Script Editor:**  
   - In your Google Sheet, go to **Extensions > Apps Script**.  

3. **Copy and Paste the Script:**  
   - Paste the script content into the Apps Script editor.  

4. **Replace API Key:**  
   - Replace `YOUR_API_KEY_HERE` with your OpenAI API key.  

5. **Save the Script:**  
   - Click **File > Save** or press `Ctrl+S`.  

6. **Authorize the Script:**  
   - Run a function (e.g., `generateEmailOpeners`) to prompt authorization.  
   - Grant necessary permissions and click **Allow**.  

7. **Refresh Your Sheet:**  
   - Reload your Google Sheet to activate the custom menu.  

---

### Usage  

1. **Access Custom Menu:**  
   - Locate the new **Custom Menu** in your Google Sheet.  

2. **Generate Content:**  
   - Use the menu to run functions like:  
     - **Generate Email Openers**  
     - **Generate Cold Calling Scripts**  
     - **Generate SMS Copy**  
     - **Analyze Website & Suggest Outreach**  

3. **Execute Functions:**  
   - The script will populate corresponding columns with generated content.  

---

### Important Notes  

- **API Costs:** Monitor your API usage and costs via OpenAI.  
- **Error Handling:** Add `try...catch` blocks for error handling if needed.  
- **Token Limits:** Adjust `max_tokens` in the script to control content length.  
- **Customize Prompts:** Modify prompts to suit your needs.  
- **Website Scraping:** Update the `IMPORTXML` XPath if the website structure changes.  
- **Column Order:** Maintain the column structure or update the script accordingly.  

---

### License  
You are free to use the script for personal or commercial purposes on your Google Sheets accounts. The finished code is proprietary to VBOUT, and credit must be attributed to the original author for any distribution.  

---  

For questions or support, feel free to reach out or explore the [Github repository](https://github.com/richardfallah/Google-Sheet-AI-Content-Wizard).
