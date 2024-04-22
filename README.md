![SwiftGateway Logo](https://www.logo.wine/a/logo/Gateway%2C_Inc./Gateway%2C_Inc.-Logo.wine.svg)

# SwiftGateway

SwiftGateway is a lightweight and fast proxy server designed for transferring players between different Minecraft Bedrock Edition servers using the BDSX software. It provides features such as fast transfer, security enhancements, failover support, dynamic configuration reload, connection pooling, logging, rate limiting, and more.

## Features

- **Fast Transfer:** SwiftGateway enables fast and seamless transfer of players between Minecraft Bedrock Edition servers.
- **Security Enhancements:** Implements authentication and encryption mechanisms to enhance security.
- **Failover Support:** Supports automatic failover to backup servers in case of connection failures.
- **Dynamic Configuration Reload:** Allows reloading configuration dynamically without restarting the server.
- **Connection Pooling:** Optimizes resource usage by managing connections efficiently with connection pooling.
- **Logging:** Provides detailed logging functionality for monitoring and troubleshooting.
- **Rate Limiting:** Implements rate limiting to prevent abuse and ensure fair usage of resources.

## How It Works

SwiftGateway acts as a middleman between Minecraft Bedrock Edition servers, intercepting player connection requests and redirecting them to the appropriate destination server based on predefined rules in the configuration file. It handles authentication, encryption, failover, dynamic configuration reload, connection pooling, logging, and rate limiting to ensure smooth and secure transfer of players.

## Installation

1. Clone the repository:
git clone https://github.com/jusztpandaa/swiftgateway.git

2. Install dependencies:
npm i OR npm install

3. Configure SwiftGateway by editing the `config.json` file.

4. Start the server:
npm start


## Configuration

The `config.json` file contains the configuration settings for SwiftGateway. You can define server addresses, ports, proxy settings, security options, failover settings, dynamic reload options, connection pool settings, and more in this file.

## Contributing

Contributions are welcome! If you have ideas for new features, enhancements, bug fixes, or documentation improvements, feel free to open an issue or submit a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.






