# LinkedIn-Job-Crawler
Selenium and Beautiful Soup Crawler for LinkedIn Jobs

Run
``` 
pip install -r requirement.txt
```

Enter the Linkedin Credentials in Config.yaml

Paste the LinkedIn Job Search URL and run the script. 
```
driver.get("https://www.linkedin.com/jobs/search/?currentJobId=3569702242&f_TPR=r86400&geoId=103644278&keywords=software%20engineer&location=United%20States&refresh=true")
```


You can change the number of page to crawl in 

```
links = []
print('Links collecting now.')
try:
    for page in tqdm(range(2, 10)): 
```

At last
```
Python3 run crawler.py
```

It takes around an hour to crawl through 700 unique job links 