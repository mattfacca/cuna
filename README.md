# Cuna

Cuna is an AI-powered tool that transforms natural language descriptions into fully functional network topologies. Designed for cybersecurity professionals, network engineers, educators, and students, Cuna bridges the gap between human intention and technical implementation—instantly generating topologies compatible with tools like GNS3, Cisco Packet Tracer, and other network simulation environments.

## Features

- Transform natural language into network topologies
- Export configurations compatible with popular simulation tools
- Intuitive interface for quick topology creation
- Support for complex network scenarios and security configurations

## Installation

```bash
pip install cuna
```

## Usage

```python
from cuna import TopologyGenerator

# Create a generator
generator = TopologyGenerator()

# Generate a topology from natural language description
description = "Create a network with three subnets, a firewall, and a DMZ."
topology = generator.generate(description)

# Export the topology to your preferred format
topology.export("my_network.gns3")
```

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the LICENSE file for details.

