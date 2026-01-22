# GNU Taler Merchant Integration Toolkit

This repository hosts the **GNU Taler Merchant Integration Toolkit**, an open-source, self-hostable toolkit aimed at reducing the practical integration effort required for merchants and service operators to accept payments via GNU Taler.

The project focuses **exclusively on the merchant side** and is intended for self-hosted or independently operated online services.

## Motivation

GNU Taler provides a robust and privacy-preserving payment system. However, integrating its merchant-side components into real-world services often requires significant repeated effort: understanding merchant APIs, designing payment flows, handling error cases, and wiring these elements into existing backends.

This project addresses that recurring integration friction by collecting and structuring common merchant-side integration patterns into a reusable toolkit.

## Scope

The toolkit is designed to:

- Provide reusable merchant-side integration helpers built on top of existing GNU Taler merchant interfaces
- Document and demonstrate common payment flows in realistic merchant environments
- Offer reference integrations and examples for self-hosted services and websites
- Remain deployable without requiring changes to the GNU Taler core or protocol

## Non-Goals

This project explicitly does **not** aim to:

- Implement or modify GNU Taler wallets
- Cover client-side or end-user payment flows
- Act as a general-purpose or multi-payment abstraction layer
- Provide a hosted service or centralized payment platform
- Replace or redesign existing GNU Taler merchant components

## Design Principles

- **Merchant-side only**: focused strictly on merchant and operator needs
- **Bounded and standalone**: useful as-is, without requiring future extensions
- **No abstraction layer**: built directly on existing GNU Taler merchant APIs
- **Self-hostable**: no central operator or third-party dependency

## Project Status

This repository is currently in the **proposal and design phase** as part of an application to the NGI / NLnet GNU Taler funding call.

Initial development will focus on defining a clear integration scope, followed by implementation, reference examples, and documentation.

## License

This project is licensed under the **GNU Affero General Public License v3.0 or later (AGPL-3.0-or-later)**.

