# Twitter Bot

Following this guide: https://www.youtube.com/watch?v=JF-BRYzNPdc

## Prepare

Go to https://developer.twitter.com, set up a developer account and fill out the form to apply for **Elevated access**.

Put your credentials in a file called `.env` on this format:

```
CONSUMER_KEY=<redacted>
CONSUMER_SECRET=<redacted>
ACCESS_TOKEN=<redacted>
ACCESS_TOKEN_SECRET=<redacted>
```

## Run

```
source .env
go run main.go
```
