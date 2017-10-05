# UNL-VPN

UNL's VPN service makes it possible to connect and initiate a remote desktop session with a computer on campus from your home network. You can read more about their service features and tunneling options [here](https://its.unl.edu/services/vpn).

![tunneling](https://github.com/Infinite-Actuary/UNL-VPN/blob/master/images/tunnel-options.PNG)

* To begin, navigate to [unl.vpn.edu](https://vpn.unl.edu/+CSCOE+/logon.html)
* This will prompt you to install the [Cisco AnyConnect Secure Mobility Client](https://www.cisco.com/c/en/us/products/security/anyconnect-secure-mobility-client/index.html)

![anyconnect](https://github.com/Infinite-Actuary/UNL-VPN/blob/master/images/anyconnect-web.PNG)

* Once the client is installed, launch it and connect to `vpn.unl.edu`

![anyconnect-launch](https://github.com/Infinite-Actuary/UNL-VPN/blob/master/images/anyconnect-launch.PNG)

* Connecting requires your My.UNL (Canvas/Blackboard) credentials

![anyconnect-login](https://github.com/Infinite-Actuary/UNL-VPN/blob/master/images/anyconnect-login.PNG)

* Once the connection is established, we can connect to a specific device by launching the `Remote Desktop Connection` app

![remote-desktop](https://github.com/Infinite-Actuary/UNL-VPN/blob/master/images/remote-desktop.PNG)

* This requires the fully qualified computer name `{system_name}.unl.edu` and the full domain name for the user `unl-ad\{user_name}`
* The `System Name` can be found by launching the `System Information` app
