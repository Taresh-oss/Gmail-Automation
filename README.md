# Gmail-Automation

I was applying for jobs in different companies and I realized that it took a lot of time to apply for a single company while sending cover letter and resume to multiple people in the same organization via mail. To reduce this I came up with the idea to auomtate Gmail which can send an email to the concerned person of the company with your details, updated cover letter as per the Company Name, Job Profile and resume. The fields like **Receiver's email, Subject, Greeting(*Hey ABC*) and Body Message** in the mail composed, can also be reflected as per the company name, job profile and email referred to, using an excel sheet which contains all such fields and their specific data.

For reference I have uploaded an excel sheet that will give you an idea of how the data need is stored in the excel sheet to make this python script work.[Link to the Excel Sheet](https://github.com/Taresh-oss/Gmail-Automation/blob/main/Gmail%20AUtomation.csv)

Also, the original cover letter will be referred and a new word as well as pdf file of Cover letter with new name will be generated in the specified path, as per the company name and Job Profile. This updated cover letter along with your resume will be uploaded and sent to the respective person addressed. An overview of how the updated cover letter looks like, can be seen in the image given below:

![Cover Letter Changes](https://user-images.githubusercontent.com/61029579/120125699-cda7bd00-c187-11eb-86b5-b966d3110efb.JPG)

One of the best feature of this automation file is that user can even schedule an email for the desired date and time. It saves a lot of time.

### Concept Used

The main concept behind this automation is Web Scraping. For Web Scraping, I have used Selenium package in python. The first step for automating this process is by giving your code access to your internet brwoser. Such access can be provided by downloading the web driver sepcific to the browser you are using and pass the path of the file in the script provided. In my case, I have used Google Chrome web driver which can be downloaded from [here](https://chromedriver.chromium.org/downloads).

The material of how to use selenium for web scraping, which I referred while designing this project is available [here](https://selenium-python.readthedocs.io/). 


