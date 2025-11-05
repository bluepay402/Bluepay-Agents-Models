# Bluepay-Agents-Models
BluePay x402 API – production-ready Express server for verified on-chain payments. Supports BluePay Pay-per-Access, Top-Up, Agents, and Subscriptions with signed X-PAYMENT headers. Fully x402 &amp; EIP-3009 compliant, Base-ready, and integrates with the official BluePay/x402 client for seamless Web3 micropayments.

## 💠 BluePay x402 Payment Models

The BluePay x402 API supports four verified payment models for flexible Web3 monetization.  
Each model is protected by the **x402 protocol** and requires a valid `X-PAYMENT` header for authorization.

---

### 💳 1. Pay-per-Access
Unlock gated resources or premium content through one-time verified micropayments.  
Perfect for **premium data**, **analytics dashboards**, or **exclusive reports**.  
**Example endpoint:** `/pay-per-access/content`

---

### 💰 2. Pay-to-Top-Up
Purchase reusable **credit packages** that can be spent across services.  
Supports **bonus credits** and verified **EIP-3009 transferWithAuthorization** settlements.  
**Example endpoint:** `/pay-to-topup/topup`

---

### 🤖 3. Pay-Agents
Enable **metered AI agent calls** where each request carries a verified x402 payment proof.  
Ideal for **LLM**, **RAG**, or **premium reasoning** agents.  
**Example endpoints:** `/pay-agents/llm-premium`, `/pay-agents/research-agent`

---

### 🔄 4. Pay-Subscription
Activate recurring **subscription plans** with full on-chain payment verification.  
Returns `activatedAt`, `expiresAt`, and decoded authorization payloads for tracking.  
**Example endpoint:** `/pay-subscription/subscribe`

---

Each model provides modular integration options for Web3 applications, enabling **instant verification**, **on-chain accounting**, and **seamless payment UX**.
