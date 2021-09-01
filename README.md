# RustyPhishingHook

Shout out to TmLev for the project base structure
https://github.com/TmLev/crud-rest-api-rust-rocket-diesel-postgres

## Project structure

src
    <br />
  -- api
  </br >
  allows for raw text strings to be sent to endpoint, so that URLs can be stripped out and analysed 
  <br />
  -- job
  <br />
  provides a background processing capability for hitting Twilo APIs to receive inputs from SMSs send to honeypot mobile number and honeypot email accounts

## Project goal

- Run quick scan on URLs from phishing emails and sms 
- Determine how to report SMS and email phishing attempts
- Importantly, notify users quickly of malicious email or SMS contents