# 🛡️ Security Concepts

## Shared Responsibility Model
In cloud environments, security is shared between the provider and the customer.

### The customer always keeps responsibility for:
- data
- identities and access
- endpoints
- security configuration choices

### The provider typically handles:
- physical datacenter
- physical hosts
- core platform services

## AI Shared Responsibility
For AI-enabled solutions, responsibility also depends on the layer:
- AI platform
- AI application
- AI usage

Even when the provider secures the AI platform, the organization remains responsible for how AI is configured, what data is exposed, and who can use it.

## Defense in Depth
Defense in depth uses multiple security layers instead of trusting one boundary.

Typical layers:
- Physical security
- Identity and access
- Perimeter
- Network
- Compute
- Application
- Data

## CIA Triad
- Confidentiality: keep data secret
- Integrity: keep data accurate and untampered
- Availability: keep data accessible when needed

## Zero Trust
Zero Trust assumes the environment is already untrusted.

### Three principles:
- Verify explicitly
- Use least privilege access
- Assume breach

### Six foundational pillars:
- Identities
- Devices
- Applications
- Data
- Infrastructure
- Networks
