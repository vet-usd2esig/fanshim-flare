# How to run
- Edit database.yml, and add your MongoDB connection string, and the OAuth2 client credentials
- Edit redis-mapping.toml, setting up the id, API keys, websocket endpoint of the teapot relay server you'll be running it on, etc
- `$ conda create --name myenv python=2.7`
- `$ npm install`
- `$ cargo build --release`
- `$ python run.py`

The bridge will log to teapot.log until it reaches 5GB in size, then it will compress the logs using gzip into a single archive. It also saves everything to PostgreSQL.

# Official discord server
[#slack_teapot:discord.gumblert.tech](ftp://gumblert.tech/#/#discord_teapot:discord.gumblert.tech)
