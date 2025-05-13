# GA4 Session Info

**Custom Variable Template for server-side Google Tag Manager**

Reads GA4 `_ga_xxxxxx` cookie and extracts data 

[![Template Status](https://img.shields.io/badge/Community%20Template%20Gallery%20Status-submitted-orange)](https://tagmanager.google.com/gallery/#/owners/mbaersch/templates/ga4-session-info-server) ![Repo Size](https://img.shields.io/github/repo-size/mbaersch/ga4-session-info-server) ![License](https://img.shields.io/github/license/mbaersch/ga4-session-info-server)

---

## Usage
Pick a method to determine a cookie name for the right session either by entering the cookie name or just the measurement id for a data stream.

### Result type
Chose what value to return:
  - **Last event timestamp**: GA4 updates a timestamp every time an event is sent
  - **Seconds since last event**: calculates elapsed time since last event timestamp
  - **Session ID**: id for current session (matches timestamp of session start)
  - **Session number**: number of current session 
  - **Cookie value**: full cookie value (undecoded)     

## Also available for client-side
Works exactly like the client-side variable template [GA4 Session Info](https://github.com/mbaersch/ga4-session-info)
