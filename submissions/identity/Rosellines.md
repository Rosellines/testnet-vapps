# vApp Submission: CrossChain ID Verifier

## Verification
```yaml
github_username: "Rosellines"
discord_id: "1289133727443582988"
timestamp: "2025-08-22"
```

## Developer
- **Name**: Nanang Sudrajat
- **GitHub**: Rosellines
- **Discord**: 1289133727443582988
- **Experience**: I am a fresh graduate and beginner in Web3, currently learning about identity and ZK systems. However, I have been actively participating in Web3 for over a year through testnet projects and airdrops.

## Project

### Name & Category
- **Project**: Proof-of-Discord Identity
- **Category**: identity

### Description
A simple vApp that allows users to prove they are a member of a Discord server without exposing their full account details.
Communities and DAOs can use this to gate events, airdrops, or private chats while preserving user privacy.

### SL Integration
Soundness Layer is used to verify zero-knowledge proofs of Discord membership.
The proof is generated off-chain after login and verified on-chain via SL smart contracts, ensuring privacy and trustlessness.

## Technical

### Architecture
Off-chain: User logs in with Discord → system generates proof of membership.
On-chain: SL contract verifies the proof and issues a credential.
DApps: Consume the credential to decide access.

### Stack
- **Frontend**: Simple web form (React/Next.js)
- **Backend**: Node.js (Discord OAuth + proof generation)
- **Blockchain**: Soundness Layer smart contract
- **Storage**: Minimal (no sensitive data stored)

### Features
1. Private proof of community membership
2. One credential usable across multiple dApps
3. Easy integration for DAOs and event organizers

## Timeline

### PoC (3 weeks)
- [ ] Basic frontend form with Discord login
- [ ] Generate placeholder proof
- [ ] Demo credential check

### MVP (6 weeks)
- [ ] SL contract verification of proof
- [ ] Reusable credential for multiple apps
- [ ] Demo integration with one sample dApp

## Innovation
Unlike typical OAuth logins, this system provides privacy-preserving verification using ZK.
Users maintain their anonymity, while apps can still trust their community credentials.

## Contact
Discord: 1289133727443582988
GitHub: Rosellines

## Example : Dummy
https://github.com/Rosellines/my-discord-proof-soundness
