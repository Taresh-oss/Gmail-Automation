# Gmail-Automation

Hello everyone

I was applying for jobs in different companies and I realized that it took a lot of time to apply for a single company while sending cover letter and resume to multiple people in the same organization via mail. To reduce this I came up with the idea of auomtate Gmail  which can send an email to the concerned person of the company with your details, updated cover letter as per the Company Name, Job Profile and resume. The fields like To, the subject, Greeting and Body Message in the mail composed can also be changed according to the company and profile applied for and sent automatically within a few seconds. All you need is an excel sheet containing details like company name, Job profile, Employee Name, Employee email Id.

For reference I have uploaded an excel sheet that will give you an idea how the data need to be stored in the excel sheet.

[Link to the Excel Sheet](https://github.com/Taresh-oss/Gmail-Automation/blob/main/Gmail%20AUtomation.csv)

Also the original cover letter that will be referred and a new word as well as pdf version of Cover letter with new name will be generated in the specified path as per the company name and Job Profile. This updated cover letter along with your resume will be uploaded and sent to the respective person addressed. An overview of how the updation is cover letter looks like can be seen in the image given below:

![Cover Letter Changes](https://user-images.githubusercontent.com/61029579/120125699-cda7bd00-c187-11eb-86b5-b966d3110efb.JPG)

One of the best feature related to this automation file is that user can even schedule an email for the desired date and time. It saves a lot of time.

### Concept Used

The main concept behind this automation is web scraping. For Web Scraping, I have used Selenium package in python. The first step for automating this process is by giving your code access to your internet brwoser and give access to it. Such access can be provided by downloading the web driver sepcific tot he browser you are using. In my case, I have used Google Chrome web driver which can be downloaded from [here](https://chromedriver.chromium.org/downloads).


