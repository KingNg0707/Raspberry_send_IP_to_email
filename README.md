# Raspberry_send_IP_to_email
## What is it?
This project is to set up a Raspberry Pi that can send its own IP address to an email address.

## What can it do?
When the Raspberry Pi boots up, it will detect the current SSID its connected to and the IP address it has. It will then send an email to the email address you specify with the IP address and SSID.

## How to use it
You will need to set up a Raspberry Pi with a network connection and an email address. Then, you can clone this repository and run the script.

## Setting up
1. Clone the repository to your Raspberry Pi
```
git clone https://github.com/KingNg0707/Raspberry_send_IP_to_email.git
```
2. Edit the `send_ip.py` file. Find the line for `email_add` and replace it with your own email address.
3. Run the script
```
python send_ip.py
```
4. You will receive an email with the IP address of your Raspberry Pi and the SSID it is connected to.

## Resources
- [Raspberry Pi Documentation](https://www.raspberrypi.org/documentation/)
- [Python Documentation](https://docs.python.org/3/)
- [GitHub Documentation](https://help.github.com/)
