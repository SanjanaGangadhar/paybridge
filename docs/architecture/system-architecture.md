# PayBridge System Architecture

## High-Level Flow

User / Merchant
→ Payment API / Sandbox
→ Transaction Verification
→ AI Financial Analytics
→ Verifiable Financial Credential
→ Blockchain Proof
→ User Consent
→ Institution Verification

## Architecture Principle

PayBridge separates sensitive financial data from independently verifiable proof.

### Off-Chain

- Personal information
- Detailed transaction data
- Financial analytics data

### On-Chain

- Cryptographic proofs
- Credential references
- Consent-event references
- Verification records

## Payment Integration

The proposed payment layer will use Drunix / NPCI APIs or sandbox infrastructure provided through the challenge, subject to access and availability.
