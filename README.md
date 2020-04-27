# Coronavirustracking
Coronavirustracking for World and USA

##Script details:

##Intended use -> Coronavirus 2020 automated tracking and texting

##This script is for testing purposes only and free for use on own discretion

##This script sources information from https://www.worldometers.info/coronavirus/

##This script needs to be deployed on a Linux server on cron

##In last text statement, the mail recipient, gmail username/password and sender name has to be updated for user

##In user GMAIL email settings set this to On -> Less secure app access. Gmail recommendation is to set to OFF but has to be ON if script is required since linux terminal logs in to Gmail in this case to send text to phone

##The yourphonenumber@phonecompanyemaildomain has to be replaced example phonenumber@txt.att.net for ATT and phonenumber@tmomail.net for T-Mobile. Other mobile providers will have domain names which will be need to be replaced respectively.

##After changes, provide permissions on script using command -> chown u+x Source_web_html_data_Corona_and_text.sh. Then the deployment is to just schedule the Source_web_html_data_Corona_and_text.sh script on cron at intended time
