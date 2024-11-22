---
description: It is time to cook..
---

# ☕ Entry Point

Make sure to have checked out the refresher on the [fundamentals of Blockchain](../../developers-guild/knowledge-base/online-courses/for-beginners.md#what-exactly-is-blockchain) before going forward.

### First,

It is very much essential to first have the [Solana CLI](../../developers-guild/knowledge-base/sdk-overview/base.md) <img src="../../.gitbook/assets/party-terminal (1).gif" alt="" data-size="line"> installed, so that you can debug and manage your Solana Programs and perform network operations.

### What does a typical Solana Project look like?

1. [**Solana Programs (Backend)**](../../developers-guild/knowledge-base/sdk-overview/backend.md): Executes transactions and processes data on the Solana network.
2. [**Client-Side Interface**](../../developers-guild/knowledge-base/sdk-overview/frontend.md)[ **(Frontend)**](../../developers-guild/knowledge-base/sdk-overview/frontend.md): Provides user interaction and displays data.
3. [**Wallet Integration**](../../developers-guild/knowledge-base/sdk-overview/wallet-integration.md): Facilitates user access and transaction approval.

&#x20;<img src="../../.gitbook/assets/typescript (2).png" alt="" data-size="line"> Typescript, our recommendation.

Considering the 36 hours deadline, It would particularly practical to write Solana Programs in Typescript to save time multitasking on multiple languages.



#### <img src="../../.gitbook/assets/anchor.gif" alt="" data-size="line">Anchor (Rust)

Why reinvent the wheel? [Anchor](../../developers-guild/knowledge-base/sdk-overview/backend.md#example-programs) does the heavy lifting for you!.

While you can build and deploy Solana Programs on Rust [natively](../../developers-guild/knowledge-base/sdk-overview/backend.md#rust) and even [C/C++](../../developers-guild/knowledge-base/sdk-overview/backend.md#example-programs-1), it is highly recommended to start with [Anchor](../../developers-guild/knowledge-base/sdk-overview/backend.md#example-programs), a framework for quickly building secure Solana programs. It handles both (de)serialization and security checks for you, so you can spend more time working on what matters **most**, your **product**.



#### <img src="../../.gitbook/assets/advanced_rest_client.png" alt="" data-size="line"> Clients&#x20;

You have options to write your client code in [Rusts](../../developers-guild/knowledge-base/sdk-overview/frontend.md#rust-client-for-solana), [Typescript](../../developers-guild/knowledge-base/sdk-overview/frontend.md#javascript-client-for-solana) as well as [Python](../../developers-guild/knowledge-base/sdk-overview/frontend.md#python-client-for-solana).



💳 Wallets&#x20;

While you can use [Solana's Wallet Adapter](../../developers-guild/knowledge-base/sdk-overview/wallet-integration.md#solana-wallet-adapter) to add wallet connection functionalities, though even easier using [Unified Wallet Kit](../../developers-guild/knowledge-base/sdk-overview/wallet-integration.md#unified-wallet-kit), it would definitely be favourable to have monkey-easy onboarding solutions like [TipLink](../../developers-guild/knowledge-base/sdk-overview/wallet-integration.md#tiplink), or even [Social Logins](../../developers-guild/knowledge-base/sdk-overview/wallet-integration.md#social-logins).



:link: Blinks & Actions

Blockchain links "[Blinks](../../developers-guild/knowledge-base/sdk-overview/frontend.md#blinks)" are awesome to abstract your application and enable seamless actions like  buying tokens or NFTs, staking, and voting on proposals, all without leaving the platform you're using.

{% embed url="https://player.vimeo.com/progressive_redirect/playback/967239233/rendition/1080p/file.mp4?loc=external&signature=8bcd4ecdc41de4bfa3925a3692f01dc302dff9929b8132c36ffca1a3fff1f9b0" %}

Check out

