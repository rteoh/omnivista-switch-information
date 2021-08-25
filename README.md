# OmniVista Alcatel Lucent Switch Information
Get Basic Information of Alcatel Lucent Network Switches using the OmniVista API. Switch information can easily be outputted into a .txt file for future comparisons. Switch information includes IP, MAC address, switch name, device DNS, location, status, version, chassis name, changes, running from, last uptime, serial number, and number of cor licenses. This is perfect for network admins who want all of their Alcatel Lucent switch information into one place.

## How to use:

Get switch information on 10.0.0.1:
<code>python switchdata.py 10.0.0.1</code>


Get switch information on 10.0.0.1 along with its output:
<code>python switchdata.py 10.0.0.1 -output</code>


Get switch information on a list of IP addresses from a .txt file:
<code>python switchdata.py ip_list.txt</code>


Get switch information on a list of IP addresses with its output:
<code>python switchdata.py ip_list.txt -output</code>

*<b>.txt files must have one IP address per a line</b>*
