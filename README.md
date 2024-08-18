# Tomarket auto start and claim bot

Auto start and claim tomarket ( Send notification on your telegram bot )
If have any question or update chat me on https://t.me/rynalfan

# Installation bot

Follow step by step below to install and run the bot:

| Step                                    | Command                                                                |
|-------------------------------------------|-------------------------------------------------------------------------------------------|
| **1. Clone the repository and get in to bot folder** | 
|                                             | `git clone https://github.com/vainzew/tomarket.git`                                      |
|                                             | `cd tomarket`                                                                            |
| **2. Create and activate virtual environment** | 
|                                             | For **Termux** or **VPS**:                                                           |
|                                             | `python -m venv tomarket`                                                                |
|                                             | `source tomarket/bin/activate`                                                           |
|                                             | For **VPS** with Python 3.x or **Windows**:                                        |
|                                             | `python3 -m venv tomarket`                                                               |
|                                             | `source tomarket/bin/activate`                                                           |
| **3. Install the requirements**                  | 
|                                             | `pip install -r requirements.txt`                                                        |
| **4. Edit Token in `tokens.txt`**          | 
|                                             | `nano tokens.txt`                                                                       |
|                                             | Paste your token, if you want run multiple account, add on new line.<br> Save with `CTRL + X`, choose `Y`, and then `ENTER`. |
| **5. Run bot**                       | 
|                                             | For **Termux**:                                                                       |
|                                             | `python main.py`                                                                        |
|                                             | For **VPS** or **Windows**:                                                          |
|                                             | `python3 main.py`                                                                       |
| **Note**                               | **Make sure you change bot toke telegram and chat id on `main.py`** If you want get notification on your personal bot. |

Bot ready start and claiming!
