# OTP Runner

Multi-service OTP / SMS / call flood runner for Termux.

Owner: **@sidzx12**

## Install (Termux)

```bash
pkg update -y && pkg upgrade -y
pkg install python git -y
git clone https://github.com/<YOUR_USER>/<YOUR_REPO>.git
cd <YOUR_REPO>
pip install -r requirements.txt
python otp_spam.py
