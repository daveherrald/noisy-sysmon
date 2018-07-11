# Noisy Sysmon Config
Here is a purposefully noisy Microsoft Sysmon configuration file which includes rule name metadata in every event. This should be useful for lab testing; in fact I created it specifically for testing the Splunk Technology Add-on for Sysmon. It uses version 4.1 of the Sysmon configuration
schema and obviously requires [Sysmon v8.0](https://docs.microsoft.com/en-us/sysinternals/downloads/sysmon) or above. 

This config IS NOT appropriate for production use. Use [Swift on Security's Config](https://github.com/SwiftOnSecurity/sysmon-config) (or a derivative of it) for that. Also, I borrowed comments from the SwiftOnSecurity config for use as the rule name metadata here.

Bring the noise!
