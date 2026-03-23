# n8n Workflow for Job Application Targets

This workflow guides you through finding decision makers at job application targets and customizing resumes for each target using n8n, integrating Google Docs/Drive, Apify for scraping LinkedIn, and sending emails via Gmail.

## Workflow Overview

1. **Finding Decision Makers**:
   - Use tools like LinkedIn to identify key people at your targeted companies.
   - Employ Apify to automate the scraping of LinkedIn profiles to gather names, titles, and contact information.

2. **Customizing Resumes**:
   - Integrate Google Docs/Drive to create and customize resumes for each decision maker identified.
   - Utilize templates in Google Docs that can be filled with specific data from your workflow.

3. **Sending Targeted Emails**:
   - Leverage Gmail's API to send personalized emails to the decision makers.
   - Ensure that the emails are not only personalized but also compelling enough to grab attention.

## Detailed Steps

### Step 1: Setup LinkedIn Scraping
- Create an Apify actor that is designed to log in to LinkedIn, search for target industries or companies, and scrape relevant data about decision makers. 

### Step 2: Resume Customization
- After obtaining the contact details, map the information to your resume template stored in Google Drive. Automate the process of creating a new Google Doc for each target with the corresponding information filled in.

### Step 3: Emailing Decision Makers
- Set up the Gmail node in n8n to handle sending emails. Ensure the email content is highly personalized based on the data scraped from LinkedIn and the customized document.

## Conclusion
This n8n workflow provides a systematic approach to streamline the job application process by automating data collection and outreach, saving you time and increasing your chances of success.