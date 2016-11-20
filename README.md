# Bootstrap

This is simple ansible playbook to setup homebridge with the plugins knx and netatmo on your Raspberry Pi running a fresh Raspbian installation on it.

```bash
# Install Ansible and Git, as you like.
# Clone this repo:
git clone https://github.com/mjoe/ansible-homebridge-knx-pi.git
cd ansible-homebridge-knx-pi/

# Configure IP address in "hosts" and "interfaces" file
# Configure wifi ssid and password in "playbook.yml" file
# Check all other files from templates/

# Execute playbook
./playbook.yml
```