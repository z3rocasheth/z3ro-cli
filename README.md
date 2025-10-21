# Z3ro CLI

Privacy-First Terminal Wallet powered by zero-knowledge technology.

```
███████╗ ██████╗ ██████╗  ██████╗ 
╚════██║ ╚════██╗██╔══██╗██╔═══██╗
  ███╔═╝  █████╔╝██████╔╝██║   ██║
 ██╔══╝   ╚═══██╗██╔══██╗██║   ██║
███████╗ ██████╔╝██║  ██║╚██████╔╝
╚══════╝ ╚═════╝ ╚═╝  ╚═╝ ╚═════╝ 
                                   
 ██████╗ █████╗ ███████╗██╗  ██╗  
██╔════╝██╔══██╗██╔════╝██║  ██║  
██║     ███████║███████╗███████║  
██║     ██╔══██║╚════██║██╔══██║  
╚██████╗██║  ██║███████║██║  ██║  
 ╚═════╝╚═╝  ╚═╝╚══════╝╚═╝  ╚═╝  
```

🔐 **Z3ro Cash** - Privacy-First DeFi Terminal Wallet

## Features

- 🛡️ **Zero-Knowledge Privacy** - Fully private transactions
- 🔄 **Multi-Chain Support** - Ethereum, Polygon, BSC, Arbitrum
- 💱 **Private Swaps** - Trade without revealing your holdings
- 🎯 **Shield & Unshield** - Move between public and private balances
- ⚡ **Lightning Fast** - Optimized CLI interface
- 🔓 **Open Source** - Fully auditable code

## Quick Start

### Install via NPM (Recommended)

```bash
npm install -g z3ro-cli
z3ro-cli
```

### Download Binary

**Linux:**
```bash
wget https://github.com/z3rocash/z3ro-cli/releases/latest/download/z3ro-cli-linux.tar.gz
tar -xzf z3ro-cli-linux.tar.gz
./z3ro-cli
```

**macOS:**
```bash
curl -LO https://github.com/z3rocash/z3ro-cli/releases/latest/download/z3ro-cli-macos.tar.gz
tar -xzf z3ro-cli-macos.tar.gz
./z3ro-cli
```

**Windows:**
Download from [Releases](https://github.com/z3rocash/z3ro-cli/releases/latest)

## Requirements

- Node.js 20.x or higher
- Rust (for building from source)

## Development

### Install Dependencies

```bash
npm install --legacy-peer-deps
```

### Run from Source

```bash
# Build the project
npm run build

# Start the wallet
npm run start
```

### Build Executable

```bash
# Install Rust dependencies
cargo install nj-cli

# Build executable
npm run ship

# Run executable
cd build
./z3ro-cli
```

## Security

### Verify Releases

Each release includes SHA256 checksums and GPG signatures.

```bash
# Verify checksum
sha256sum --check SHA256SUMS.sha

# Verify GPG signature
gpg --import PUBLICSIGNER.asc
gpg --verify SHA256SUMS.sha.sig SHA256SUMS.sha
```

## Documentation

- 📖 [User Guide](https://z3ro.cash/docs)
- 🔧 [Developer Docs](https://z3ro.cash/developers)
- 💬 [Community](https://z3ro.cash/community)

## Links

- 🌐 Website: [z3ro.cash](https://z3ro.cash)
- 📦 NPM: [npmjs.com/package/z3ro-cli](https://npmjs.com/package/z3ro-cli)
- 🐙 GitHub: [github.com/z3rocash/z3ro-cli](https://github.com/z3rocash/z3ro-cli)

## License

LGPL-3.0-or-later

## Support

- 📧 Email: support@z3ro.cash
- 🐛 Issues: [GitHub Issues](https://github.com/z3rocash/z3ro-cli/issues)

---

**Built with privacy in mind.** 🔐
