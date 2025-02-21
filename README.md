# RessoMusic
<h2 align="center">
    ──「 ᴍᴏᴏɴ 🌙 ᴍᴜsɪᴄ 」──

    ## 🚀 Deploy on Heroku 
[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://dashboard.heroku.com/new?template=https://github.com/NKMODNK1/heruko-)
---

### 🔧 Quick Setup

1. **Upgrade & Update:**
   ```bash
   sudo apt-get update && sudo apt-get upgrade -y
   ```

2. **Install Required Packages:**
   ```bash
   sudo apt-get install python3-pip ffmpeg -y
   ```
3. **Setting up PIP**
   ```bash
   sudo pip3 install -U pip
   ```
4. **Installing Node**
   ```bash
   curl -fssL https://deb.nodesource.com/setup_19.x | sudo -E bash - && sudo apt-get install nodejs -y && npm i -g npm
   ```
5. **Clone the Repository**
   ```bash
   git clone https://github.com/MOON-CODES/leharmusic && cd leharmusic
   ```
6. **Install Requirements**
   ```bash
   pip3 install -U -r requirements.txt
   ```
7. **Create .env  with sample.env**
   ```bash
   vi sample.env
   ```
   - Edit .env with your vars
8. **Editing Vars:**
   ```bash
   mv sample.env .env
   ```
   - Edit .env with your values.
   - Press `I` button on keyboard to start editing.
   - Press `Ctrl + C`  once you are done with editing vars and type `:wq` to save .env or `:qa` to exit editing.
9. **Installing tmux**
    ```bash
    sudo apt install tmux && tmux
    ```
10. **Run the Bot**
    ```bash
    bash start
    ```
    
