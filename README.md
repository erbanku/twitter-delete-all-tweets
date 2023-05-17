# Twitter Delete All Tweets

🗑️ A GitHub project that uses GitHub Actions and the Twitter Developer API to delete all tweets every Sunday at 4 PM (UTC).

## Usage

Before you can use this project, you need to get your Twitter Developer API keys from the [Twitter Developer Portal](https://developer.twitter.com/en/portal/dashboard). Once you have your keys, you can set the following environment variables:

- `TWITTER_ACCESS_TOKEN`
- `TWITTER_ACCESS_TOKEN_2`
- `TWITTER_ACCESS_TOKEN_SECRET`
- `TWITTER_ACCESS_TOKEN_SECRET_2`
- `TWITTER_CONSUMER_API_KEY`
- `TWITTER_CONSUMER_API_KEY_2`
- `TWITTER_CONSUMER_API_SECRET_KEY`
- `TWITTER_CONSUMER_API_SECRET_KEY_2`
- `TWITTER_USER`
- `TWITTER_USER_2`

You will need to set these environment variables for each Twitter account that you want to delete tweets from.

## How it works

This project uses GitHub Actions to schedule a job that runs every Sunday at 4 PM (UTC). The job uses the Twitter Developer API to delete all tweets from the specified Twitter account(s).

## Contributing

If you find a bug or have an idea for a new feature, please open an issue or submit a pull request. We welcome contributions from the community!