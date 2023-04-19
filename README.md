# LinkedIn-Job-Crawler
Selenium and Beautiful Soup Crawler for LinkedIn Jobs

Enter the Linkedin Credentials in Config.yaml

Paste the LinkedIn Job Search URL and run the script. 

You can change the number of page to crawl in 

links = []
print('Links collecting now.')
try:
    for page in tqdm(range(2, 10)): 
