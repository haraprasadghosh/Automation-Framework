![image](https://github.com/mytechnotalent/Automation-Framework/blob/main/Automation%20Framework.png?raw=true)

# Automation Framework
An open-source Automation Framework.

## Installation
```bash
git clone https://github.com/mytechnotalent/af.git
```

## Enable SSH (Managed Host)
[Instructions](https://www.raspberrypi.org/documentation/remote-access/ssh)

## Setup Environment (Control Host)
```bash
python3 -m venv venv
source venv/bin/activate
pip install -r requirements.txt
ssh-keygen
ssh-copy-id pi@192.168.x.x
ssh pi@192.168.x.x
sudo visudo
  %sudo  ALL=(ALL:ALL) NOPASSWD: ALL
```

## Setup Environment (Managed Host)
```bash
sudo apt-get install chromium-chromedriver
```

## Run
```bash
python af_cli.py
```

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.

## License
[GNU General Public License v3.0](https://www.gnu.org/licenses/gpl-3.0.en.html)
