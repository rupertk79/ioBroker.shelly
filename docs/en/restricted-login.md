![Logo](../../admin/shelly.png)

# ioBroker.shelly

## Restricted login

To protect your Shelly devices with a restricted login, choose a username and a password in the ioBroker configuration on the *general settings* tab.

![iobroker_general_restrict_login](./img/iobroker_general_restrict_login.png)

Activate the login restriction on all your Shelly devices.

**Generation 2 devices don't provide a username option. If you use Gen 1 and Gen 2 devices, use the same password on all devices.**

### Warnings

If a device password was configured in the ioBroker configuration, the adapter will raise warnings in the log when some Shelly devices are unprotected!

To avoid those warnings, you can

- remove the password from the ioBroker configuration (= no password required) or
- enable the restricted login on all Shelly devices with the configured password

### Generation 1 devices

1. Open the Shelly web configuration in your webbrowser (not in the Shelly App!)
2. Go to ```Internet & Security settings -> Restricted Login```
3. Activate the checkbox and enter the previously configured username and password
4. Save the configuration - the Shelly will reboot automatically
5. Ensure to configure the same username and password on all your Shelly devices

![shelly gen 1](./img/shelly_restrict_login-gen1.png)

### Generation 2 devices (Plus and Pro)

1. Open the Shelly web configuration in your webbrowser (not in the Shelly App!)
2. Go to ```Device -> Authentication```
3. Enable the authentication feature and enter the previously configured password
4. Save the configuration

![shelly gen 2](./img/shelly_restrict_login-gen2.png)