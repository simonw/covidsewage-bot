# covidsewage-bot

The [@covidsewage](https://twitter.com/covidsewage) Twitter bot

Tweets a daily image of the charts from the County of Santa Clara [SARS-CoV-2 Sewage Monitoring Data](https://covid19.sccgov.org/dashboard-wastewater).

## How it works

The bot runs using [this scheduled GitHub Actions workflow](https://github.com/simonw/covidsewage-bot/blob/main/.github/workflows/tweet.yml).

It uses these two tools:

- [shot-scraper](https://datasette.io/tools/shot-scraper) to take the screenshot
- [tweet-images](https://github.com/simonw/tweet-images) to send the tweet

I wrote notes on [how to get credentials for a Twitter bot](https://til.simonwillison.net/twitter/credentials-twitter-bot).
