# JuniorAnalystGPT

This is a small project that implements an OpenAI Assistant using a Jupyter notebook. The assistant can provide financial information, market updates, and company insights using data from various sources.

## Prerequisites

To run this project, you'll need:

1. OpenAI API key
2. AlphaVantage API key
3. (Optional) Any files you'd like the assistant to be able to access

Make sure to set up these API keys before running the notebook.

## Worked Examples

This repository includes several worked examples to demonstrate the capabilities of JuniorAnalystGPT:

1. `JuniorAnalystGPT_marketupdate_walkthrough.txt`: Shows how to get market updates, including recent news in the technology sector and information about top gainers and losers.

2. `JuniorAnalystGPT_meta_walkthrough.txt`: Provides a detailed walkthrough of analyzing Meta (Facebook) stock, including price updates, earnings reports, and recent headlines.

3. `JuniorAnalystGPT_IBM_walkthrough.txt`: Demonstrates an analysis of IBM, including company overview, stock performance, revenue changes, and EPS history.

### Sample Walkthrough: IBM Analysis

Here's a snippet from the IBM walkthrough to give you an idea of how JuniorAnalystGPT works:

```
user > Sounds great! Let's start with some research into IBM. Give me an overview on the company and tell me how their stock has been recently.

JuniorAnalystGPT > calling get_company_overview function...

JuniorAnalystGPT > calling get_latest_price function...

JuniorAnalystGPT > I've got some exciting information about IBM for you! 🚀

### Company Overview:
- **Name:** International Business Machines (IBM)
- **Description:** IBM is an American multinational technology company known for its innovation in computer hardware, middleware, software, and services. It's a major player in the tech industry with a rich history of inventions like the ATM, floppy disk, and more.
- **Sector:** Technology
- **Industry:** Computer & Office Equipment
- **Market Capitalization:** $152.67 billion
- **Revenue (TTM):** $62.07 billion
- **EPS (TTM):** $8.83
- **Dividend Per Share:** $6.64
- **Latest Quarterly Earnings Growth (YoY):** 70.1%
- **Analyst Target Price:** $184.84
- **52-Week High:** $199.18
- **52-Week Low:** $116.36
- **Shares Outstanding:** 916,745,000

### Recent Stock Data:
- **Price:** $166.20
- **Open:** $166.49
- **High:** $166.76
- **Low:** $165.26
- **Previous Close:** $167.43
- **Volume:** 6,011,634
- **Change:** -$1.23
- **Change Percent:** -0.73%
- **Latest Trading Day:** April 30, 2024

IBM continues to be a key player in the tech world with consistent growth and a strong market presence! 🌟 Let me know if you need more details or have any other questions!

user > Great work. Compile all the info you have given me into a short summary. Make it informative but to the point. 

JuniorAnalystGPT > Absolutely! Here's a concise summary of the information on IBM:

🌟 **IBM Overview:** 
- IBM (International Business Machines) is a tech giant known for innovation in computer hardware, software, and services.
- It operates in the Technology sector and Computer & Office Equipment industry.
- Market capitalization is $152.67 billion, with revenue of $62.07 billion (TTM).
- IBM's EPS has varied over the years, from $13.82 in 2018 to $1.68 in the most recent quarter.

📊 **Financial Performance:**
- IBM's revenue fluctuated over the last 5 years, reaching a peak of $57.71 billion in 2019.
- The company maintains a significant amount of debt on its balance sheet, with total debt ranging from $107.76 billion to $132.19 billion in recent years.

💸 **Stock Performance:**
- IBM's stock price is around $166.20, with a 52-week high of $199.18 and low of $116.36.
- Recent trading volume was 6,011,634 shares, with the latest closing price at $166.20.

🚀 **Conclusion:**
- IBM continues to be a key player in the tech industry, adapting to market trends while navigating financial challenges effectively.

If you have any more questions or need further details, feel free to ask! 🚀📈
```


## Getting Started

1. Open the notebook in Google Collab 
2. Set up your API keys
3. Run the cells to interact with JuniorAnalystGPT
