It will be live soon on 
[chatthings.nishanttheprogrammer.com](chatthings.nishanttheprogrammer.com)

# Installation Instructions
```sh
git clone https://github.com/NishantTheProgrammer/ChatThings.git
```
```sh
cd ChatThings/frontend
npm install     #node and npm should be installed.
npm run build
```
```sh
cd ../backend
python3 -m venv env
source env/bin/activate
pip install -r requirements.txt
python manage.py runserver
```
If you've any issue regarding venv click [here](https://packaging.python.org/guides/installing-using-pip-and-virtual-environments/)

Now open [http://127.0.0.1:8000/](http://127.0.0.1:8000/) in your browser.

# Features


## Chat (Individual + Group)
       Text
       Emoji
       Custom emoji (_futureUpdates_)
       Hyperlink
       Live remote video(YouTube, Facebook etc)
       Document
       Location

       Audio:
           Recording
           upload
       Video:
           Recording
           Upload
       Streaming:
           Same music on both end
       Chat Sharing:
           Select messages and share to other friend
       Report: fake identity, pornographic content
## News feed
        Post:
            Text ✅
            Image ✅
            Video ✅
            Audio ✅
            Report
        Comment:
            Reply
## Story
        Audio
        Video
        Text
        Combine
        Privacy settings
## Friends
         Request/Response
         Mutual
         Suggestion/find by criteria (name, sex, age, location)
         Tag / Mention
         Block-unblock
## Games
        Tic-tac-toe
        Custom KBC
## Authentication
        Username + Password ✅
        Google
        Facebook
