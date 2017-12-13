# ixNetwork Shell Library for Quali TestShell

A wrapper library dll of [ixNetwork Controller Shell](https://github.com/QualiSystems/Ixia-IxNetworkController-Shell), to be used for Quali TeshShell Studio tests. This simplifies the deployment as it uses the CloudShell Automation API behind the scenes to call the commands on that shell rather than making direct Ixia API requests.

The library provides the following fucntions:
- Load Configuration
- Start Traffic
- Get Statistics
- Stop Traffic
- Start Protocols
- Send Arp

To use it, add IXN.dll as a new library in TeshShell Studio. 