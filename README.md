# Galxe AIO

 - Link Twitter account
 - Link email: IMAP or mail3.me
 - Link Discord
 - Complete requirements
 - Complete tasks
 - Claim rewards
 - Quiz solver
 - Accounts statistics

### Supported tasks:
 - Twitter: Follow, Retweet, Like, Quote
 - Visit link
 - Watch YouTube
 - Solve quiz
 - Follow Galxe space
 - Tries to verify all the others

### Supported rewards:
 - Points
 - Mystery Boxes
 - Gas-less OATs
 - Gas OATs and NFTs


### Settings
 - `files/evm_wallets.txt` - Wallets with EVM private keys
 - `files/proxies.txt` - Corresponding proxies for wallets
 - `files/twitters.txt` - Corresponding twitters for wallets
 - `files/emails.txt` - Corresponding emails for wallets
 - `files/discords.txt` - Corresponding discords for wallets. Can be empty if not needed
 - `config.toml` - Custom settings

### Config
 - `FAKE_TWITTER` - Verify Twitter tasks without real Twitter actions
 - `GALXE_CAMPAIGN_IDS` - Campaigns to complete, parent campaigns are supported
 - `HIDE_UNSUPPORTED` - Don't log unsuccessful completing of unsupported tasks

### Run

Python version: 3.11

Installing virtual env: \
`python3 -m venv venv`

Activating:
 - Mac/Linux - `source venv/bin/activate`
 - Windows - `.\venv\Scripts\activate`

Installing all dependencies: \
`pip install -r requirements.txt` \
`playwright install`

Run main script: \
`python main.py`

Run twitter checker: \
`python checker.py`

### Results

`results/` - Folder with results of run \
`logs/` - Folder with logs of run \
`storage/` - Local database
