
# Twitter Votes

Simple application to cast votes on Twitter.

Project of the book [Python Programming Blueprints](https://www.packtpub.com/mapt/book/application_development/9781786468161?utm_source=all%20updates&utm_campaign=a532fdc6a6-Mapt_new_title_releases_25_01_18&utm_medium=email&utm_term=0_c970747b22-a532fdc6a6-169822065&mc_cid=a532fdc6a6&mc_eid=b722ebf882)

# Required corrections from original project:
 - remove x_auth_expires

# Future improviments:
 - SOLID principles, like IoC etc

## Install

pip install -r requirements.txt

## Run

In order to make client work properly,  you should grant special rights to it, so first launch twitter_auth and autorize the 
app

### Create a twitter APP:
    - https://apps.twitter.com
    - Refresh your config.yaml with APP access data

### Authorize app 
python twitter_auth.py and access http://localhost:3000

### launch APP

python app.py --hashtags debian ubuntu arch windows
