<h1 align="center">phishrs3mp-neut💀</h1>

<p align="center">
  <b>v2.0</b> · by <b>s3mp4y.cm (Anna-S3mp4y)</b>
</p>

### [√] Description :

***A python phishing script for login phishing, image phishing, video phishing and many more.***
Proyecto educativo (hecho con un amigo) para mostrar cómo funciona el phishing y cómo defenderse.

### [+] Installation

##### Install primary dependencies (git, python)

 - For Debian (Ubuntu, Kali-Linux, Parrot)
    - ```sudo apt install git python3 php openssh-client -y```
 - For Arch (Manjaro)
    - ```sudo pacman -S git python3 php openssh --noconfirm```
 - For Redhat(Fedora)
    - ```sudo dnf install git python3 php openssh -y```
 - For Termux
    - ```pkg install git python3 php openssh -y```

##### Enter the directory
 - ```cd phishrs3mp-neut```

##### Install all modules
 - ```pip3 install -r files/requirements.txt```

##### Run the tool
 - ```python3 phishrs3mp-neut.py```

#### Or, Clone
https://github.com/Anna-S3mp4y/Phisher-s3mp-neut.cm

### Pip
 - `pip3 install phishrs3mp-neut` [For Termux]
 - `sudo pip3 install phishrs3mp-neut` [For Linux]
 - `phishrs3mp-neut`

### [√] License
***MIT License · phishrs3mp-neut v2.0 · © 2026 s3mp4y.cm (Anna-S3mp4y) · Original: KasRoudra/MaxPhisher (MIT)***

### Support

OS         | Support Level
-----------|--------------
Linux      | Excellent
Android    | Excellent
iPhone     | Alpha (Recommended docker)
MacOS      | Alpha (Recommended docker)
Windows    | Unsupported (Use docker/virtual-box/vmware)
BSD        | Never tested

#### Options

usage: phishrs3mp-neut.py -h -p PORT -t TYPE -o OPTION
                     -T TUNNELER -r REGION -S SUBDOMAIN
                     -d DIRECTORY -f FEST -i YTID -u URL
                     -s DURATION -m MODE -e TROUBLESHOOT
                     --nokey --noupdate
options:
  -h, --help            show this help message and exit
  -p PORT, --port PORT  phishrs3mp-neut's server port Default : 8080
  -t TYPE, --type TYPE  phishrs3mp-neut's phishing type index Default : null
  -o OPTION, --option OPTION
                        phishrs3mp-neut's template index  Default : null 
  -T TUNNELER, --tunneler TUNNELER
                        Tunneler to be chosen while url shortening Default : Cloudflared
  -r REGION, --region REGION
                        Region for loclx Default: auto
  -S SUBDOMAIN, --subdomain SUBDOMAIN
                        Subdomain for loclx Pro Account (Default: null)
  -d DIRECTORY, --directory DIRECTORY
                        Directory where media files will be saved Default : /sdcard/Media
  -f FEST, --fest FEST  Festival name for fest template Default: Birthday
  -i YTID, --ytid YTID  Youtube video ID for yttv template Default : 6hHmkInZkMQ
  -u URL, --url URL     Redirection url for ip-tracking or login phishing Default : null
  -s DURATION, --duration DURATION
                        Media duration while capturing Default : 5000(ms)
  -m MODE, --mode MODE  Mode of phishrs3mp-neut Default: normal
  -e TROUBLESHOOT, --troubleshoot TROUBLESHOOT
                        Troubleshoot a tunneler Default: null
  --nokey               Use localtunnel without ssh key Default: False
  --noupdate            Skip update checking Default : False

### Features:

 - Multi platform (Supports most linux)
 - 100+ templates
 - 3 tunneling (Cloudflared, LocalXpose, LocalHostRun)
 - OTP Support
 - Credentials mailing
 - Easy to use
 - Possible error diagnoser
 - Built-in / custom masking of URL
 - URL Shadowing
 - Portable file (Can be run from any directory)
 - Get IP Address and many other details along with login credentials

### Requirements

 - `Python(3)` + `requests` + `rich`
 - `PHP` · `SSH`
 - 900MB storage

### Tested on

 - Termux · Ubuntu · Kali-Linux · Arch · Fedora · Manjaro

## Usage

1. Run the script
2. Choose a Website
3. Wait sometimes for setting up all
4. Send the generated link to victim
5. Wait for victim login. As soon as he/she logs in, credentials will be captured


## Solution of common issues
 - Some secured browsers like Firefox can warn for '@' prefixed links. Use pure links or custom link to avoid it.
 - Termux from play store is not supported. Download termux from fdroid or github.
 - VPN or proxy prevents tunneling. Turn them off if you have issues.
 - Some Android devices require hotspot to start Cloudflared/Loclx. If you face 'tunneling failed', turn hotspot on and keep it on.
 - Untuk mailing credentials you need an app password: visit [here](https://myaccount.google.com/u/0/apppasswords), generate one and put it in `files/email.json` (enable 2FA before).

## [🎭] El logo
La Mona Lisa: nadie sabe si es la verdadera o una copia. Así es el phishing: una página que parece legítima pero es solo una máscara.

## [!] Disclaimer
***Este proyecto es 100% educativo: demuestra cómo funciona el phishing para defenderte de él. Probar solo en entornos propios/laboratorio y con consentimiento. Usarlo contra terceros sin permiso es un delito. El autor no se hace responsable del mal uso de phishrs3mp-neut.***

### [*] Support
#### ¿Te gusta? Cuéntalo y dale una estrella
###### Donate ftf: Con su estrella basta

