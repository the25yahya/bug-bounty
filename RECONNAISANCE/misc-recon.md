- service enumeration using : nmap - naabu
- passive service enumeration using shodam
- third party hosting : Take a look at the company’s third-party hosting footprint
  site:s3.amazonaws.com COMPANY_NAME / site:amazonaws.com COMPANY_NAME /amazonaws s3 COMPANY_NAME /
  amazonaws bucket COMPANY_NAME /amazonaws COMPANY_NAME / s3 COMPANY_NAME
- GrayhatWarfare (https://buckets.grayhatwarfare.com/) is an online search
engine you can use to find publicly exposed S3 buckets
- aws s3 cp TEST_FILE s3://BUCKET_NAME/ snippet to go back to bug bounty bootcamp's s3 buckets sec
- tools to auomate github recon phase : Gitrob (https://github.com/michenriksen/gitrob/) locates potentially sensitive
files pushed to public repositories on GitHub. TruffleHog (https://github.com/
trufflesecurity/truffleHog/) specializes in finding secrets in repositories by conducting regex searches and scanning for high-entropy strings.
- website liscence google dorking
- chekout the companies engenieering job offerings to determine the tech stack they use
- targeting employees linked in and other social media profiles to gather info on the company ... probably find leaked creds
- wayback machine enumeration to determine outdated components that the website still uses (https://github.com/tomnomnom/waybackurls/)  
