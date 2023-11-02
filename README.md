# Email-scrapping
This repository mentions different ways of webscrapping - using BeautifulSoup, AppScript, and Ngrok

Sure, let's summarize the disadvantages of using each tool:

**1. Ngrok:**
- **Temporary Setup:** The ngrok URL changes every time you restart the Flask app in Colab.
- **Not Meant for Production:** Since I used Colab server, it is not intended to be a production or long-term server.
- **Security Concerns:** The ease with which tools like localtunnel and ngrok allow local servers to be exposed to the internet has led to misuse by some individuals, such as hosting malicious sites. The new security features included in localtunne made ngrok a better option to use.

**2. BeautifulSoup:**
- **Time-consuming:** The given approach could take 30 hours.
- **Delay in Extraction:** There's a 3-second delay during each data extraction iteration.
- **Risk of IP Ban:** Intentional pauses between two scraping activities are necessary to avoid potential IP bans from sites like Google.
- **Captcha Challenge Risk:** If Google or another site introduces a captcha challenge during the scraping process, it can disrupt or halt the scraping.

**3. AppScript:**
- **Incomplete Results:** Websites may not always contain desired data like email addresses on their first page, leading to fetching blank results.
- **Daily Limits:** Google's services have constraints on the number of queries, allowing only 10,000 results to be fetched per day in the given scenario.

Do note that these disadvantages are specific to the context provided. Each tool has its strengths and can be very useful in other scenarios.
For the rows where e-mail retrieval was unsuccessful, manual search using Bing AI is considered and performed. 
