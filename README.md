# BlocksBuddy Knowledge Repository

This repository contains curated blockchain knowledge used by the BlocksBuddy Telegram chatbot to provide accurate, helpful information about the blockchain ecosystem, with a primary focus on Kadena.

## Purpose

We're building a community-maintained knowledge base to:

1. Make blockchain concepts more accessible to newcomers
2. Document Kadena's unique features, contracts, and development resources
3. Provide standardized information about smart contracts, DeFi concepts, and Web3 terminology
4. Create a reliable reference that can be used by BlocksBuddy and other community tools

## How This Repository Is Used

This repository contains structured knowledge (not real-time data) about:

- **Smart contracts**: Addresses, descriptions, interfaces, and documentation
- **Blockchain concepts**: Explanations of key ideas in DeFi, NFTs, and Kadena-specific technologies
- **Development resources**: Tutorials, tools, and getting started guides
- **FAQs**: Common questions and clear answers about Kadena and blockchain
- **Glossary**: Definitions of technical terms

The BlocksBuddy Telegram bot uses this information to answer user questions with accurate, consistent information when discussing blockchain topics.

## Data Structure

The main data file is `blockchain-data.json` with these main sections:

- `contracts`: Information about deployed smart contracts across different blockchains
- `concepts`: Explanations of key ideas in DeFi and Kadena-specific technologies
- `development`: Resources for developers looking to build on Kadena
- `faq`: Common questions and answers about blockchain technology
- `glossary`: Definitions of technical terms

Each section is carefully structured to be machine-readable while maintaining human editability.

## How to Contribute

We welcome contributions from the community! Here's how to help:

### Adding New Knowledge

1. Fork this repository
2. Add your knowledge to the appropriate section of `blockchain-data.json`
3. Submit a pull request with a clear description of what you've added

### Updating Existing Information

1. Fork this repository
2. Update the outdated information
3. Make sure to update the `lastUpdated` field with today's date (YYYY-MM-DD format)
4. Submit a pull request describing what you've updated

### Content Guidelines

When contributing, please ensure:

- **Accuracy**: Information should be factually correct and verifiable
- **Neutrality**: Present information objectively without marketing language
- **Clarity**: Explanations should be understandable to newcomers
- **Conciseness**: Keep entries focused and to the point
- **Structure**: Follow the existing JSON schema

## Scope and Limitations

This repository is for **persistent knowledge**, not real-time data. We do not track:

- Token prices
- Trading volumes
- TVL (Total Value Locked)
- Market capitalizations
- Gas fees

These time-sensitive metrics are handled separately through API integrations in the BlocksBuddy bot.

## Review Process

All contributions will be reviewed by maintainers for:

1. Accuracy and correctness
2. Adherence to the JSON schema
3. Quality of explanations
4. Overall value to the knowledge base

We aim to review PRs within 1-2 weeks.

## License

This repository and all its contents are available under the MIT License. See the LICENSE file for details.

## Contact

If you have questions or suggestions, please open an issue in this repository or reach out to us on [Telegram](https://t.me/BlocksBuddyBot).

---

Built with ❤️ by the Kadena community
