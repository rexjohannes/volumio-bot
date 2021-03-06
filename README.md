# volumio-bot

Discord Bot Control
for [Volumio](https://volumio.org/)

Features:

![](https://screen.rexum.space/ypNAy2ZJYo.png?key=nt4CDbujrfXrPo)

### Requirements:

- Volumio
- DiscordBot-Token

### Setup:

Goto [volumio.local/dev](http://volumio.local/dev/) and Enable SSH.

Then open [Putty](https://putty.org/) and connect to `volumio.local` and type `volumio` as username and password.

![](https://screen.rexjohannes.space/W1kMjsTkeD.png?key=YnET6duo5HttuE)

Run `sudo apt update -y && sudo apt install python3-pip python3 git screen libopus-dev nano libffi-dev libsodium-dev build-essential -y && wget https://raw.githubusercontent.com/rexjohannes/volumio-bot/main/pyinstall.sh && chmod +x pyinstall.sh && sudo bash pyinstall.sh && git clone https://github.com/rexjohannes/volumio-bot.git && cd volumio-bot && sudo python3.6 -m pip install --upgrade -r requirements.txt && chmod +x run.sh && nano ./config/token.txt` in your Putty. Enter `volumio` as password.

Paste your Token and press Str. + X 

![](https://screen.rexjohannes.space/tcXC6LQskP.png?key=0Ybkr2jj6lqrtv)

To run the Bot type `bash run.sh` and press Str. + A + D
