# IPLookup

This is a simple Node.js script that takes an IP address as an argument and prints some information about its location and service provider.

## Requirements

- Node.js
- An internet connection

## Installation

To install the script, open a terminal and navigate to the folder where the script is located. Then type:

```bash
sudo mv iplookup /usr/local/bin/iplookup
chmod +x /usr/local/bin/iplookup
```

This will move the script to the `/usr/local/bin` directory and make it executable.

## Usage

To run the script, open a terminal and type:

```bash
iplookup <ip_address>
```

Replace `<ip_address>` with the IP address you want to query. For example:

```bash
iplookup 8.8.8.8
```

The script will make a GET request to the [ip-api.com](http://ip-api.com) service and print the following information:

- IP address
- Continent
- Country
- Region
- City
- Timezone
- Currency
- ISP
- Organization
- Mobile
- Proxy
- Hosting

If the IP address is invalid or the service is unavailable, the script will print an error message.

## License

This script is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.