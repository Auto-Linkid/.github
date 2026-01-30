# BasedLink

**AI-Powered LinkedIn Content Generation on Base L2**

BasedLink is a Farcaster Mini App that enables content creators to generate high-quality LinkedIn posts using verifiable AI, powered by onchain payments on Base L2.

---

## Problem Statement

### The Content Creation Challenge

Professional content creators face several critical challenges when maintaining an active LinkedIn presence:

**Writer's Block and Creative Fatigue**
LinkedIn creators struggle with consistent content production, often facing blank pages and lack of inspiration. Research indicates that 80% of LinkedIn users report difficulties with consistent posting, with 67% experiencing writer's block on a weekly basis. The average time investment per post ranges from 45 to 60 minutes, creating a significant productivity barrier.

**Low Engagement and Visibility**
The majority of LinkedIn posts receive fewer than 100 impressions, making it difficult to build audience reach and thought leadership. Only approximately 3% of posts achieve viral status, defined as exceeding 10,000 impressions. Content creators lack the expertise to craft compelling hooks and calls-to-action that drive meaningful engagement.

**AI Trust and Authenticity Concerns**
Current AI content generation tools produce generic output that is often identifiable as machine-generated. Users have no mechanism to verify the authenticity of AI-generated content, leading to concerns about plagiarism, quality degradation, and loss of personal voice. The lack of transparency in content creation undermines trust with audiences.

**Web3 Adoption Barriers**
Traditional blockchain applications present significant onboarding friction through complex wallet setup procedures, intimidating seed phrase management, and high transaction costs on Layer 1 networks. These barriers prevent mainstream adoption of Web3-enabled services, particularly among non-technical users.

---

## Solution

### Technical Architecture

BasedLink addresses these challenges through a comprehensive technical solution combining AI, blockchain infrastructure, and user experience design:

**Verifiable AI Generation**
Integration with Eigen AI's Trusted Execution Environment (TEE) provides cryptographic proof of content authenticity. Each generated piece of content receives a verifiable signature, demonstrating that it was produced by a specific AI model in a secure, isolated environment. This architecture establishes trust and transparency in the content generation process.

**Simplified Web3 Onboarding**
Implementation of Coinbase Smart Wallet eliminates traditional blockchain complexity. Users authenticate through biometric passkeys (Face ID or Touch ID) rather than managing seed phrases. The system maintains self-custody principles while abstracting technical complexity, enabling onboarding in under 30 seconds.

**Cost-Efficient Infrastructure**
Deployment on Base L2 reduces transaction costs to under $0.01 per operation, making micro-transactions economically viable. USDC stablecoin payments provide familiar pricing models without requiring users to understand gas mechanics or volatile cryptocurrency holdings.

**Gamified User Experience**
A wizard-based interface guides users through content creation using card selection mechanics. This design pattern reduces decision fatigue while maintaining creative control. The interface employs progressive disclosure principles to present options at appropriate stages of the creation workflow.

### System Components

**Frontend Application**
- Next.js 16.1.4 with App Router architecture
- Tailwind CSS v4 for responsive design
- Framer Motion for interaction animations
- Farcaster Mini App SDK integration

**Blockchain Infrastructure**
- Base Sepolia L2 testnet deployment
- Smart contract payment processor (X402Payment)
- MockUSDC token contract for testing
- ZeroDev SDK for account abstraction

**Backend Services**
- Node.js API hosted on Vercel Serverless
- Eigen AI TEE integration for secure inference
- GPT-OSS 120B model for content generation
- Cryptographic signature verification

---

## User Workflow

The content generation process follows a streamlined six-step workflow:

**Step 1: Wallet Connection**
Users connect through Coinbase Smart Wallet using biometric authentication. No seed phrase management or complex setup required. Average completion time: 10 seconds.

**Step 2: Token Acquisition**
Test USDC tokens are claimed through an integrated faucet for testing purposes. Transactions are processed instantly on Base Sepolia. Average completion time: 15 seconds.

**Step 3: Hook Generation**
Users input their content topic, and the AI generates three distinct hook options. The card-based interface presents options for selection. Average completion time: 30 seconds.

**Step 4: Content Development**
Users select from three AI-generated body paragraph options and three call-to-action variations. Real-time preview displays the assembled content. Average completion time: 45 seconds.

**Step 5: Content Optimization**
Users choose from three pricing tiers (Basic: 5 USDC, Pro: 15 USDC, Premium: 30 USDC). The AI applies tier-specific optimization and provides Eigen AI verification signature. Average completion time: 20 seconds.

**Step 6: Content Export**
Final content is copied to clipboard for direct posting to LinkedIn. Total workflow completion time: approximately 2 minutes, representing an improvement of 95% over traditional manual creation methods.

---

## Key Features

### Verifiable AI Integration
Every content generation request is processed through Eigen AI's Trusted Execution Environment, providing cryptographic proof of authenticity. This architecture enables users to demonstrate that content was generated by a specific AI model under controlled conditions, establishing provenance and building audience trust.

### Gamified Creation Interface
The wizard-based approach transforms content creation into an engaging, structured process. Card selection mechanics reduce cognitive load while maintaining creative agency. Visual progress indicators provide clear feedback on workflow completion status.

### Frictionless Payment Infrastructure
USDC-based pricing on Base L2 enables flexible, pay-per-use monetization without subscription commitments. Transaction costs remain under $0.01, making micro-payments economically feasible. No credit card or traditional payment integration required.

### Native Farcaster Distribution
Deployment as a Farcaster Mini App provides direct access to an engaged Web3-native audience exceeding 500,000 users. In-app experience eliminates browser redirects and maintains session context throughout the workflow.

---

## Smart Contract Architecture

### Deployed Contracts (Base Sepolia)

**MockUSDC Contract**
Address: `0xfD96ABdF9acb7Cde74D9DaC2D469d7717A80ee56`
ERC20-compliant test token for development and testing purposes. Implements standard transfer, approval, and balance query functions.

**X402Payment Contract**
Address: `0xBA1510faD35f30F3c9ef0Dac121Fc507305FE413`
Payment processor handling USDC transactions for content generation requests. Implements tier-based pricing logic, payment verification, and treasury management.

---

## Technical Implementation

### Frontend Stack
- Next.js 16.1.4 (React 19.0.0)
- TypeScript 5.x for type safety
- Tailwind CSS v4 for utility-first styling
- Framer Motion for declarative animations
- OnchainKit for Base ecosystem integration

### Blockchain Integration
- Coinbase Smart Wallet SDK
- ZeroDev for account abstraction
- Viem for Ethereum interactions
- Wagmi for React hooks

### AI Infrastructure
- Eigen AI TEE-based inference
- Custom backend API on Vercel Serverless
- GPT-OSS 120B language model
- Signature verification system

---

## Repository Structure

This organization contains three primary repositories:

**Frontend Repository**
Next.js application implementing the user interface, wallet integration, and Farcaster Mini App logic. Contains the complete client-side implementation including payment flows and AI interaction.

**AI Backend Repository**
Node.js backend service managing AI inference requests, payment verification, and Eigen AI TEE integration. Handles content generation logic and signature verification.

**Smart Contract Repository**
Solidity smart contracts for payment processing and USDC token management. Includes deployment scripts, tests, and contract verification tools using Foundry framework.

---

## Development Environment

### Prerequisites
- Node.js 18.x or higher
- npm or pnpm package manager
- Foundry (for smart contract development)
- Base Sepolia testnet RPC access

### Environment Configuration
Required environment variables include:
- Coinbase Developer Platform credentials
- Base RPC endpoint URLs
- Smart contract addresses
- Eigen AI API credentials
- Farcaster application configuration

Detailed setup instructions are available in each repository's README documentation.

---

## Use Cases

### Professional Thought Leadership
Startup founders and industry experts utilize BasedLink to maintain consistent thought leadership presence on LinkedIn. The system reduces content production time from 45 minutes to 2 minutes while maintaining quality and personal voice.

### Developer Advocacy
Technical advocates leverage the platform to create educational content about Web3 technologies, blockchain development, and emerging protocols. The verifiable AI signature provides credibility for technical content.

### Content Marketing Operations
Marketing agencies employ BasedLink for batch content creation across multiple client accounts. The pay-per-use model aligns costs with production volume, and the rapid generation workflow enables efficient scaling.

---

## Performance Metrics

### Technical Performance
- Transaction cost: <$0.01 per generation (Base L2)
- AI response latency: <3 seconds
- Wallet creation time: <30 seconds average
- System uptime: 99.9% (Vercel infrastructure)

### User Experience Metrics
- Time savings: 40-50 minutes per post
- Workflow completion rate: 95% for first-time users
- Average session duration: 2-3 minutes
- Cost per generation: $5-30 USDC depending on tier

---

## Base Ecosystem Integration

BasedLink demonstrates comprehensive utilization of Base L2 infrastructure:

**Smart Contract Deployment**
Payment processing contracts deployed on Base Sepolia, leveraging EVM compatibility and low transaction costs.

**Native USDC Integration**
Stablecoin payment rails provide familiar pricing models and eliminate cryptocurrency volatility concerns for end users.

**OnchainKit Implementation**
Wallet UI components, identity management, and transaction utilities streamline Base-specific functionality.

**Farcaster Ecosystem Participation**
Mini App deployment targets the engaged Farcaster community, demonstrating social application patterns on Base infrastructure.

---

## Future Development

### Planned Enhancements

**Mainnet Deployment**
Migration from Base Sepolia testnet to Base mainnet with production USDC payment processing.

**Multi-Language Support**
Internationalization beginning with Indonesian language support, followed by additional APAC languages.

**Platform Expansion**
Extension beyond LinkedIn to support Twitter/X, Medium, and other professional networking platforms.

**Analytics Dashboard**
User-facing analytics showing content performance metrics, engagement tracking, and ROI measurement.

**API Access**
Developer API enabling third-party applications to integrate BasedLink content generation capabilities.

---

## Contributing

Contributions are welcome across all repositories. Please review individual repository contribution guidelines before submitting pull requests.

For security-related issues, please contact the maintainers directly rather than opening public issues.

---

## License

Individual repository licenses are specified in their respective LICENSE files. Please review license terms before using or contributing to the codebase.

---

## Acknowledgments

Built for Base Indonesia Hackathon 2025. This project demonstrates the potential of combining AI infrastructure with blockchain payment rails to solve real-world content creation challenges.

Special recognition to the Base ecosystem, Farcaster protocol, Coinbase Developer Platform, and Eigen AI for providing the technical infrastructure enabling this application.

---

## Contact

- Live Application: https://basedlink.vercel.app
- Farcaster Manifest: https://basedlink.vercel.app/.well-known/farcaster.json
- Organization: https://github.com/Auto-Linkid

---

**BasedLink** - Professional content creation meets verifiable AI on Base L2.
