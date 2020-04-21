# Thorin
The tool collects endpoints from web archive and analyzes it and scan it from many vulnerabilities
## Features 
**Vulnerability:** 
* xss 
* open redirection 
* sql injection simple and blind and error base 
* local file inclusion 
* server-side template injection 
* crlf 
* os comman injection  
* HTTP PUT Method Enabled
* cross-origin resource sharing

**Other features:**
* Detect sensitive url like: .git or .svn folder/ Backup file like .back or .save or .old / token or api keys in url  like(slack,twilio,heroku,mailchamp,amazon,...)
* Detect base64 in url 
* Detect js files and and searching for data that might be sensitive, such as links or tokens or api keys 

## Usage
**Install:**

`pip3 install -r requirements.txt
`

**Run:**

`python3 thorin domain.com
`

`python3 thorin sub.domain.com
`

![Alt text](relative/path/to/img.jpg?raw=true "Title")