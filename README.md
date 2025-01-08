# reddit-rss-proxy
Helps Feedly grab the latest RSS feeds for various subreddits from Old Reddit by acting as an Atom proxy.

To use it:

- Fork the repo
- List the subreddit names in subreddits.csv
- Give GitHub Actions Read/Write permissions on your repo in: https://github.com/yourusername/reddit-rss-proxy/settings/actions
- GitHub Actions should run every 15 minutes but may need enabling
- The feed files are then in /feeds
- Give Feedly a feed URL for each one like: https://raw.githubusercontent.com/conoro/reddit-rss-proxy/refs/heads/main/feeds/LocalLLaMA.xml

LICENSE Apache-2.0

Copyright Conor O'Neill 2025, conor@conoroneill.com