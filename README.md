# MemeFiBot
🖱️ clicker for [https://t.me/memefi_coin_bot](https://t.me/memefi_coin_bot?start=r_684aed1a82)

## Recommendation before use
# 🔥🔥 Use PYTHON 3.10 🔥🔥

## Functionality
| Functional                                                     | Supported |
|----------------------------------------------------------------|:---------:|
| Multithreading                                                 |     ✅     |
| Binding a proxy to a session                                   |     ✅     |
| Auto-purchase of items if you have coins (tap, energy, charge) |     ✅     |
| Random sleep time between clicks                               |     ✅     |
| Random number of clicks per request                            |     ✅     |
| Support tdata / pyrogram .session / telethon .session          |     ✅     |

## [Settings](https://github.com/sizifart/MemeFiBot/.env-example)
| Настройка                | Описание                                                                                                                   |
|--------------------------|----------------------------------------------------------------------------------------------------------------------------|
| **API_ID / API_HASH**    | Platform data from which to launch a Telegram session (stock - Android)                                                    |
| **MIN_AVAILABLE_ENERGY** | Minimum amount of available energy, upon reaching which there will be a delay (eg 100)                                     |
| **SLEEP_BY_MIN_ENERGY**  | Delay when reaching minimum energy in seconds (eg 200)                                                                     |
| **ADD_TAPS_ON_TURBO**    | How many taps will be added when turbo is activated (eg 2500)                                                              |
| **AUTO_UPGRADE_TAP**     | Improve the tap boost  (True / False)                                                                                      |
| **MAX_TAP_LEVEL**        | Maximum level of tap boost (eg 5)                                                                                          |
| **AUTO_UPGRADE_ENERGY**  | Upgrade the energy boost (True / False)                                                                                    |
| **MAX_ENERGY_LEVEL**     | Maximum level of energy boost (eg 5)                                                                                       |
| **AUTO_UPGRADE_CHARGE**  | Upgrade the charge boost (True / False)                                                                                    |
| **MAX_CHARGE_LEVEL**     | Maximum level of charge boost (eg 5)                                                                                       |
| **APPLY_DAILY_ENERGY**   | Use the daily free energy boost (True / False)                                                                             |
| **APPLY_DAILY_TURBO**    | Use the daily free turbo boost (True / False)                                                                              |
| **RANDOM_CLICKS_COUNT**  | Random number of taps (eg [50,200])                                                                                        |
| **SLEEP_BETWEEN_TAP**    | Random delay between taps in seconds (eg [10,25])                                                                          |
| **USE_PROXY_FROM_FILE**  | Whether to use proxy from the `bot/config/proxies.txt` file (True / False)                                                 |
| **USE_TAP_BOT**          | Use the tap-bot (True / False) (eg [10,25])                                                                                |
| **EMERGENCY_STOP**       | Use an emergency stop (True / False), if True - in case of a stop bot protocol error, so as not to get banned (eg [10,25]) |


## Prerequisites
Before you begin, make sure you have the following installed:
- [Python](https://www.python.org/downloads/) **version 3.10**
- Telegram API_ID and API_HASH (you can get them [here](https://my.telegram.org/auth))

## Obtaining API Keys
1. Go to my.telegram.org and log in using your phone number.
2. Select "API development tools" and fill out the form to register a new application.
3. Record the API_ID and API_HASH provided after registering your application in the .env file.

## Auto Install/Run
- Click on Install.bat to automatically install the required dependencies 
- Then click on START.bat to run the project

## Menual Install/Run
1. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```
2. Please edit the name file .env-example to .env and add your API_ID and API_HASH:
   
## Usage
1. Run the bot:
   ```bash
   python main.py
   ```
 
# Telegram Channel

✅ Channel for information and training on Telegram airdrop bots 🔷 Follow us on Telegram : [SIZIFAIRDROP](https://t.me/sizifairdrop)
   
# Discussion

If you have an question or something you can ask in here : [F.Davoodi](https://t.me/sizifart)

