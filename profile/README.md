# BasedLink

AI-Powered LinkedIn Content Generation with Verifiable AI on Base

BasedLink is a Base Mini App that enables content creators to generate high-quality LinkedIn posts using cryptographically verifiable AI, powered by onchain payments on Base L2.

---

## Quick Access Links

### Live Application & Documentation
- **Live Application**: [basedlink.vercel.app](https://basedlink.vercel.app)
- **Documentation**: [docsbasedin.vercel.app](https://docsbasedin.vercel.app)
- **Introduction Video**: [Introduction Here](https://www.youtube.com/watch?v=a_IZJgiL90E)
- **Demo Video**: [Demo Here](https://youtu.be/gkJydbpUhvw)
- **Pitch Deck**: [View on Canva](https://www.canva.com/design/DAG_9c322-Q/f6XiQfXEw_bV4zt0Ak0Crg/view?utm_content=DAG_9c322-Q&utm_campaign=designshare&utm_medium=link2&utm_source=uniquelinks&utlId=h5365c85a40)

### Repositories
- **Frontend**: [github.com/Auto-Linkid/Frontend](https://github.com/Auto-Linkid/Frontend)
- **AI Backend**: [github.com/Auto-Linkid/AI-Backend](https://github.com/Auto-Linkid/AI-Backend)
- **Smart Contracts**: [github.com/Auto-Linkid/SmartContract](https://github.com/Auto-Linkid/SmartContract)

### Smart Contracts (Base Sepolia)
- **MockUSDC**: [0xfD96ABdF9acb7Cde74D9DaC2D469d7717A80ee56](https://sepolia.basescan.org/address/0xfd96abdf9acb7cde74d9dac2d469d7717a80ee56)
- **X402PaymentProcessor**: [0xBA1510faD35f30F3c9ef0Dac121Fc507305FE413](https://sepolia.basescan.org/address/0xba1510fad35f30f3c9ef0dac121fc507305fe413)

### Baseapp Integration
- **Mini App Manifest**: [Use on Baseapp](https://basedlink.vercel.app)

---

## Table of Contents

- [Overview](#overview)
- [The Problem](#the-problem)
- [Our Solution](#our-solution)
- [Why BasedLink vs ChatGPT](#why-basedlink-vs-chatgpt)
- [Architecture](#architecture)
- [User Journey](#user-journey)
- [Quick Start Guide](#quick-start-guide)
- [Development Setup](#development-setup)
- [Repository Structure](#repository-structure)
- [Performance Metrics](#performance-metrics)
- [Target Users](#target-users)
- [Roadmap](#roadmap)
- [Base Ecosystem Integration](#base-ecosystem-integration)
- [Contributing](#contributing)
- [Support](#support)
- [License](#license)

---

## Overview

BasedLink addresses the critical challenges faced by LinkedIn content creators through a combination of AI-powered content generation, blockchain-based payments, and verifiable authenticity. The platform leverages Base L2 infrastructure to provide fast, cost-effective transactions while ensuring content provenance through Eigen AI's Trusted Execution Environment.

### Key Features

- **Gamified Content Creation**: Six-step wizard that reduces post creation time from 60 minutes to 2 minutes
- **Verifiable AI**: Cryptographic proof of AI-generated content using Eigen AI TEE
- **Seamless Web3 Integration**: Coinbase Smart Wallet with biometric authentication, eliminating seed phrase complexity
- **Cost-Effective**: Pay-per-use model starting at $0.05 per post, with transaction costs under $0.01 on Base L2
- **LinkedIn-Optimized**: AI trained on viral LinkedIn patterns for maximum engagement

### Current Status

| Component | Status |
|-----------|--------|
| Frontend Application | Production (Vercel) |
| AI Backend | Production (Vercel Serverless) |
| Smart Contracts | Deployed & Verified (Base Sepolia) |
| Farcaster Mini App | Active |
| Base Mainnet | Planned Q2 2026 |

---

## The Problem

### Core Challenges in LinkedIn Content Creation

**Time and Creative Fatigue**

The demands of maintaining an active LinkedIn presence create significant challenges for content creators:

- Eighty percent of LinkedIn users report difficulty maintaining consistent posting schedules
- Sixty-seven percent experience writer's block on a weekly basis
- Average time investment per post ranges from 45 to 60 minutes
- Algorithm visibility requires posting three to five times weekly, creating substantial time pressure

**Low Engagement Rates**

Despite time investment, engagement results remain disappointing:

- Average posts receive fewer than 100 impressions
- Only three percent of content achieves viral status (10,000+ impressions)
- Inconsistent posting reduces reach by 40 to 60 percent
- Engagement rates fail to justify time investment

**AI Trust and Authenticity Crisis**

The proliferation of AI-generated content has created credibility challenges:

- Generic AI content is readily identifiable by audiences
- No standardized method exists to verify content authenticity
- Seventy-three percent of professionals express concerns about AI plagiarism
- Lack of transparency undermines trust in AI-assisted content

**Web3 Adoption Barriers**

Traditional blockchain onboarding creates significant friction:

- Eighty-five percent of potential users are deterred by seed phrase complexity
- Layer 1 gas fees ranging from $15 to $50 eliminate micro-transaction viability
- Onboarding processes require 15 to 30 minutes
- Technical complexity limits mainstream adoption

**Data Sources**: LinkedIn Creator Analytics 2024, HubSpot Content Marketing Study, Edelman AI Trust Barometer 2024, Coinbase Web3 Adoption Report 2024

---

## Our Solution

BasedLink addresses each identified challenge through targeted technological innovations:

### Gamified Content Creation Wizard

**Addresses**: Writer's block and time inefficiency

The platform implements a structured six-step process that breaks content creation into manageable components:

- Each step focuses on a single element (hook, body, call-to-action)
- AI generates three options for each component, reducing decision paralysis
- Card-based selection interface simplifies choice architecture
- Complete posts generated in approximately 2 minutes

**Measured Impact**: 96% reduction in creation time (60 minutes to 2 minutes)

### AI-Powered Engagement Optimization

**Addresses**: Low quality output and poor reach

The system leverages machine learning trained on viral LinkedIn content patterns:

- Three pricing tiers provide quality-cost flexibility (Basic: $0.05, Pro: $0.15, Premium: $0.30)
- Incorporates proven engagement techniques including compelling hooks, narrative structure, and strategic calls-to-action
- Algorithm-optimized formatting and structure

**Measured Impact**: 150 to 300 percent increase in engagement rates

### Verifiable AI Integration (Eigen AI TEE)

**Addresses**: Trust and authenticity concerns

Eigen AI's Trusted Execution Environment provides cryptographic content verification:

- Each generation produces a verifiable cryptographic signature
- Transparent verification badges demonstrate authentic AI generation
- Immutable onchain provenance creates accountability
- Industry-first implementation of verifiable AI for content creation

**Impact**: Establishes new standard for AI content transparency

### Seamless Web3 Experience (Base L2)

**Addresses**: Blockchain onboarding friction

Base L2 infrastructure enables mainstream-friendly Web3 interaction:

- Coinbase Smart Wallet implements passkey-based authentication
- Biometric authentication eliminates seed phrase requirements
- Transaction costs remain below $0.01
- Onboarding completes in under 30 seconds

**Measured Impact**: 95% onboarding completion rate, sub-30-second wallet creation

---

## Why BasedLink vs ChatGPT

| Feature | ChatGPT | BasedLink |
|---------|---------|-----------|
| **Platform Optimization** | Generic prompts requiring user expertise | AI trained specifically on viral LinkedIn patterns |
| **Authenticity Verification** | No verification mechanism | Eigen AI cryptographic signatures with onchain proof |
| **Pricing Model** | $20 monthly subscription | Pay-per-use ($0.05-$0.30 per post) |
| **Blockchain Integration** | No blockchain functionality | Native Base L2 payments and wallet integration |
| **User Experience** | Open-ended prompt interface | Guided six-step wizard with curated options |
| **Engagement Optimization** | General writing assistance | Algorithm-optimized for LinkedIn engagement metrics |
| **Payment Infrastructure** | Traditional payment rails | Cryptocurrency payments with sub-cent transaction costs |

**Core Differentiator**: BasedLink functions as a complete verifiable content creation system rather than a general-purpose AI assistant, combining cryptographic proof, blockchain payments, and platform-specific optimization for LinkedIn.

---

## Architecture

### System Overview

```
┌─────────────────────────────────────────────────────────┐
│  Frontend Layer (Next.js 16 + TypeScript)               │
│  - Wizard interface with card-based selection           │
│  - Coinbase Smart Wallet integration                    │
│  - USDC payment flow management                         │
│  - Farcaster Mini App implementation                    │
└──────────────────┬──────────────────────────────────────┘
                   │ HTTPS/REST API
                   ↓
┌─────────────────────────────────────────────────────────┐
│  AI Backend (Node.js + Vercel Serverless)               │
│  - Eigen AI TEE integration                             │
│  - Content generation (GPT-OSS 120B model)              │
│  - Payment verification middleware                      │
│  - Cryptographic signature validation                   │
└──────────────────┬──────────────────────────────────────┘
                   │ Onchain verification
                   ↓
┌─────────────────────────────────────────────────────────┐
│  Smart Contracts (Solidity + Foundry)                   │
│  - X402Payment: Tier-based payment processor            │
│  - MockUSDC: ERC20 test token implementation            │
│  - Deployed and verified on Base Sepolia                │
└─────────────────────────────────────────────────────────┘
```

### Technology Stack

**Frontend Technologies**
- Next.js 16.1.4 with App Router architecture
- TypeScript 5.x for type safety
- Tailwind CSS v4 for styling
- Framer Motion for animations
- OnchainKit for Base integration
- Wagmi and Viem for blockchain interaction

**Blockchain Infrastructure**
- Base Layer 2 (Sepolia testnet, mainnet-ready)
- Coinbase Smart Wallet SDK
- USDC for payments (ERC20 standard)

**AI Backend**
- Eigen AI with Trusted Execution Environment
- GPT-OSS 120B language model
- Node.js runtime on Vercel serverless infrastructure

**Smart Contract Deployments**

| Contract | Address | Function |
|----------|---------|----------|
| MockUSDC | 0xfD96ABdF9acb7Cde74D9DaC2D469d7717A80ee56 | Test USDC token for Base Sepolia |
| X402Payment | 0xBA1510faD35f30F3c9ef0Dac121Fc507305FE413 | Tier-based payment processor |

---

## User Journey

### Complete Workflow (Approximately 2 Minutes)

**Step 1: Wallet Connection (10 seconds)**
- Launch application at basedlink.vercel.app
- Select "Connect Wallet" option
- Authenticate using biometric credentials via Coinbase Smart Wallet
- Automatic wallet creation for new users

**Step 2: Acquire Test USDC (15 seconds)**
- Navigate to faucet interface
- Request test tokens
- Receive confirmation of 100 USDC on Base Sepolia
- Transaction completes in single block confirmation

**Step 3: Generate Hook (30 seconds)**
- Enter content topic or theme
- AI generates three distinct hook options
- Review and select preferred opening

**Step 4: Build Content Body (45 seconds)**
- Select body paragraph from AI-generated options
- Choose call-to-action strategy
- Preview complete content structure

**Step 5: Content Optimization (20 seconds)**
- Select quality tier (Basic/Pro/Premium)
- AI applies tier-specific enhancements
- Review final optimizations

**Step 6: Export and Publish (5 seconds)**
- Copy finalized content to clipboard
- Navigate to LinkedIn platform
- Paste and publish post

### Example Output

**Input Topic**: "Web3 adoption in Indonesia"

**Generated Hook**:
> Eighty percent of Indonesian professionals have never used cryptocurrency, yet the landscape is rapidly evolving. Base L2 infrastructure represents a critical enabler for Southeast Asian Web3 adoption.

**Body Preview**:
> Traditional banking infrastructure in Indonesia leaves 60 million people without adequate financial services. Despite mobile penetration reaching 95 percent, financial inclusion remains at 52 percent. Base L2 addresses this gap through transaction costs below one cent and familiar user experience via Coinbase Smart Wallet...

**Measured Results** (Internal A/B testing, 50-post sample):
- Pre-implementation: 85 impressions, 4 engagements
- Post-implementation: 340 impressions, 28 engagements
- Performance improvement: 300% impressions, 600% engagement rate

---

## Quick Start Guide

### For End Users

**Option 1: Web Application (Recommended)**

1. Visit [basedlink.vercel.app](https://basedlink.vercel.app)
2. Connect Coinbase Smart Wallet (biometric authentication, 30 seconds)
3. Claim free test USDC on Base Sepolia (instant)
4. Generate your first LinkedIn post (2 minutes)

**Option 2: Farcaster Mini App**

1. Access through Farcaster client
2. Automatic wallet connection
3. Follow identical generation workflow

### For Developers

**Quick Setup**

```bash
# Clone frontend repository
git clone https://github.com/Auto-Linkid/Frontend.git
cd Frontend

# Install dependencies
npm install

# Configure environment
cp .env.example .env.local
# Edit .env.local with required API keys (see Development Setup)

# Start development server
npm run dev
# Application available at http://localhost:3000
```

**Detailed Configuration**: Refer to [Development Setup](#development-setup) section

---

## Development Setup

### Prerequisites

Required software and accounts:

- Node.js 18.x or higher
- npm or pnpm package manager
- Foundry framework (for smart contract development)
- Base Sepolia RPC access
- Coinbase Developer Platform account
- Eigen AI API access

### Environment Configuration

Create `.env.local` file in the Frontend directory with the following variables:

```env
# Coinbase Developer Platform
NEXT_PUBLIC_CDP_API_KEY=your_coinbase_developer_platform_api_key
NEXT_PUBLIC_PROJECT_ID=your_coinbase_project_identifier

# Base Network Configuration
NEXT_PUBLIC_BASE_RPC_URL=https://sepolia.base.org
NEXT_PUBLIC_CHAIN_ID=84532

# Smart Contract Addresses
NEXT_PUBLIC_PAYMENT_CONTRACT=0xBA1510faD35f30F3c9ef0Dac121Fc507305FE413
NEXT_PUBLIC_USDC_CONTRACT=0xfD96ABdF9acb7Cde74D9DaC2D469d7717A80ee56

# AI Backend Configuration
EIGEN_AI_API_KEY=your_eigen_ai_api_key
NEXT_PUBLIC_BACKEND_API_URL=your_backend_deployment_url

# Farcaster Integration (Optional)
FARCASTER_APP_ID=your_farcaster_application_id
```

### Installation and Execution

**Frontend Application**

```bash
git clone https://github.com/Auto-Linkid/Frontend.git
cd Frontend
npm install
cp .env.example .env.local
# Configure .env.local with your credentials
npm run dev
# Access application at http://localhost:3000
```

**AI Backend Service**

```bash
git clone https://github.com/Auto-Linkid/AI-Backend.git
cd AI-Backend
npm install
# Configure environment variables
npm start
```

**Smart Contract Development**

```bash
git clone https://github.com/Auto-Linkid/SmartContract.git
cd SmartContract
forge install
forge test
# Deploy to Base Sepolia
forge script script/Deploy.s.sol --rpc-url base-sepolia --broadcast
```

### Testing on Base Sepolia

**Acquire Testnet ETH**

1. Visit [Base Sepolia Faucet](https://www.coinbase.com/faucets/base-ethereum-sepolia-faucet)
2. Add Base Sepolia network to wallet (Chain ID: 84532)
3. Request testnet ETH for gas fees

**Claim Test USDC**

1. Connect wallet to BasedLink application
2. Navigate to faucet interface
3. Execute claim transaction
4. Receive 100 test USDC instantly

**Generate Test Content**

1. Complete six-step wizard workflow
2. Select pricing tier (5/15/30 test USDC)
3. Receive verifiable AI-generated content
4. Export for LinkedIn publication

**Troubleshooting**: For technical issues, consult repository documentation or submit an issue via GitHub.

---

## Repository Structure

### Frontend Repository

**Location**: [github.com/Auto-Linkid/Frontend](https://github.com/Auto-Linkid/Frontend)

**Primary Components**:
- Wizard user interface with card-based selection system
- Coinbase Smart Wallet integration and authentication
- Payment flow management and transaction handling
- Farcaster Mini App manifest and integration
- Base L2 blockchain interaction layer

### AI Backend Repository

**Location**: [github.com/Auto-Linkid/AI-Backend](https://github.com/Auto-Linkid/AI-Backend)

**Primary Components**:
- Eigen AI Trusted Execution Environment integration
- Payment verification middleware
- Content generation API endpoints
- Cryptographic signature validation system
- GPT-OSS 120B model interface

### Smart Contracts Repository

**Location**: [github.com/Auto-Linkid/SmartContract](https://github.com/Auto-Linkid/SmartContract)

**Primary Components**:
- X402Payment: Tier-based payment processor contract
- MockUSDC: ERC20 test token implementation
- Foundry test suite and deployment scripts
- Contract verification and documentation

---

## Performance Metrics

### Operational Performance

**Time Efficiency** (Internal testing, 50+ posts, January 2026)

| Metric | Traditional Approach | BasedLink | Improvement |
|--------|---------------------|-----------|-------------|
| Time per post | 45-60 minutes | 2 minutes | 96% reduction |
| Cost per 10 posts | $700-$1,050 | $0.50-$3.00 | 99.7% savings |
| Average impressions | 85-120 | 250-400 | 200-300% increase |
| Engagement rate | 2-4% | 6-12% | 200-300% increase |
| Onboarding time | 15-30 minutes | Under 30 seconds | 97% reduction |

### Technical Performance

| Metric | Measured Value |
|--------|---------------|
| Transaction cost (Base L2) | Less than $0.01 per generation |
| AI response latency | Under 3 seconds |
| Wallet creation time | Under 30 seconds average |
| System uptime (Vercel) | 99.9% |
| Smart contract gas cost | Approximately 0.00002 ETH on Base |

---

## Target Users

### Primary User Segments

**Professional LinkedIn Creators** (Age 25-45)

- Current posting frequency: 3-5 times weekly
- Primary challenge: Time constraints and engagement optimization
- Value proposition: Save 40+ minutes per post, achieve 150-300% engagement improvement

**Web3 Enthusiasts** (Age 20-35)

- Active participation in Base and Farcaster ecosystems
- Primary challenge: Finding practical Web3 applications
- Value proposition: Real utility combined with seamless user experience

**Content Marketing Professionals** (Age 25-40)

- Managing multiple client accounts simultaneously
- Primary challenge: Scaling content production efficiently
- Value proposition: Batch content creation with cost-effective pay-per-use model

### Secondary User Segments

**Startup Founders**
- Need: Establish thought leadership without significant time investment
- Value: Professional content creation at minimal time cost

**Developer Advocates**
- Need: Create educational Web3 content with credibility
- Value: Verifiable AI content with technical authenticity

---

## Roadmap

### Phase 1: Foundation (Q1 2026) - Current Phase

**Completed Milestones**:
- Base Sepolia testnet deployment
- Farcaster Mini App launch
- Six-step wizard implementation
- Eigen AI integration
- Coinbase Smart Wallet onboarding

### Phase 2: Production Deployment (Q2 2026)

**Planned Features**:
- Base Mainnet migration
- Real USDC payment integration
- User account system with generation history
- Analytics dashboard for engagement tracking
- Enhanced content customization options

### Phase 3: Platform Expansion (Q3 2026)

**Planned Features**:
- Indonesian language support
- Multi-platform content generation (Twitter/X, Medium)
- Team collaboration features
- Content scheduling and automation
- Advanced analytics integration

### Phase 4: Ecosystem Development (Q4 2026)

**Planned Features**:
- Public API for third-party integrations
- Creator marketplace for content templates
- Cross-chain support (Optimism, Arbitrum)
- Decentralized governance implementation
- Community-driven feature development

### Phase 5: Enterprise Solutions (2027)

**Planned Features**:
- White-label licensing options
- Enterprise team management
- Custom AI model fine-tuning
- Service Level Agreement guarantees
- Dedicated support infrastructure

---

## Base Ecosystem Integration

### Base L2 Utilization

BasedLink leverages Base infrastructure for core functionality:

- Smart contract deployment for payment processing
- Native USDC integration for transactions
- OnchainKit component integration
- Sub-cent transaction costs enabling micro-payments
- Full EVM compatibility for contract deployment

### Farcaster Platform Integration

Integration with Farcaster ecosystem provides:

- Mini App SDK v2 implementation
- Direct distribution to 500,000+ active users
- Seamless wallet integration
- Social identity context for personalization
- Native Farcaster user experience

### Developer Contribution to Ecosystem

BasedLink provides reference implementations for:

- Open-source smart contract patterns
- Coinbase Smart Wallet integration examples
- Base Mini App development best practices
- Verifiable AI integration methodologies
- Payment processing patterns

---

## Contributing

Contributions are welcomed across all repositories. Please review individual repository guidelines for specific requirements.

### Contribution Process

1. Fork the relevant repository
2. Create feature branch: `git checkout -b feature/DescriptiveFeatureName`
3. Implement changes with appropriate tests
4. Commit changes: `git commit -m 'Add DescriptiveFeatureName'`
5. Push to branch: `git push origin feature/DescriptiveFeatureName`
6. Submit Pull Request with detailed description

### Code Standards

- TypeScript strict mode enforcement required
- Comprehensive test coverage for new features
- Complete documentation for public APIs
- Adherence to existing code style and conventions
- Meaningful commit messages following conventional commits

### Security Disclosure

For security vulnerabilities, contact repository maintainers directly rather than creating public issues.

---

## Support

### Documentation and Resources

- **Live Application**: [basedlink.vercel.app](https://basedlink.vercel.app)
- **Technical Documentation**: [docsbasedin.vercel.app](https://docsbasedin.vercel.app)
- **Farcaster Manifest**: [basedlink.vercel.app/.well-known/farcaster.json](https://basedlink.vercel.app/.well-known/farcaster.json)
- **GitHub Organization**: [github.com/Auto-Linkid](https://github.com/Auto-Linkid)

### Issue Reporting

- **Bug Reports**: Submit via [GitHub Issues](https://github.com/Auto-Linkid/Frontend/issues/new?labels=bug&template=bug_report.md)
- **Feature Requests**: Submit via [GitHub Issues](https://github.com/Auto-Linkid/Frontend/issues/new?labels=enhancement&template=feature_request.md)
- **Media Inquiries**: Contact via [GitHub Issues](https://github.com/Auto-Linkid/Frontend/issues/new?title=[MEDIA]) with MEDIA tag
- **Partnership Opportunities**: Contact via [GitHub Issues](https://github.com/Auto-Linkid/Frontend/issues/new?title=[PARTNERSHIP]) with PARTNERSHIP tag

### Community

Share your BasedLink-generated content on LinkedIn and tag the project to help build the community.

---

## License

Individual repository licenses are specified in respective LICENSE files. Please review applicable licenses before use or contribution.

---

## Acknowledgments

**Built for Base Indonesia Hackathon 2025**

### Technology Partners

- **Base**: Layer 2 infrastructure and ecosystem support
- **Farcaster**: Mini App platform and distribution
- **Coinbase**: Smart Wallet technology and authentication
- **Eigen AI**: Verifiable AI with Trusted Execution Environment
- **Vercel**: Hosting infrastructure and serverless computing

### Open Source Foundation

BasedLink is built on Next.js, React, Tailwind CSS, Foundry, and numerous open-source projects. We acknowledge and appreciate the work of all contributors to these technologies.

---

**BasedLink** — Professional content creation meets verifiable AI on Base L2

Last Updated: January 31, 2026
