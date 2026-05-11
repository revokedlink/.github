<div align="center">
  <img src="/assets/logo-dark.png" alt="revoked" width="120" />
  <h1>revoked</h1>
  <p>Self-host freely. Build on top. Don't sell it.</p>

  [![License: ELv2](https://img.shields.io/badge/License-Elastic_v2-blue.svg)](https://www.elastic.co/licensing/elastic-license)
  [![API Docs](https://img.shields.io/badge/docs-revoked.link%2Fdocs-green)](https://revokedlink.github.io/docs)
  [![Status: Experimental](https://img.shields.io/badge/status-experimental-yellow)](https://github.com/revokedlink/api)
</div>
 
---

> [!WARNING]
> **Project Status:** `revoked` is currently in active development. It is **not ready for production use**, and backwards compatibility is not guaranteed until the v1.0.0 release.

## The Vision

**revoked** is a self-hosted digital identity hub designed to transform how individuals and organizations manage personal information. Currently, the web relies on "data silos"—centralized databases where you surrender static copies of your identity. 

**revoked** flips this paradigm. You maintain a private, secure Vault and provide services with dynamic, revocable pointers to your information. This ensures you remain the sole owner of your digital footprint.

## Philosophy

* **Sovereignty by Design:** Your identity belongs to you. By utilizing a "Bring Your Own Hub" (BYOH) architecture, we ensure your data lives on infrastructure you control—eliminating reliance on third-party providers.
* **Access over Static Copies:** Instead of filling out forms with static data that immediately goes stale, you grant services a "window" into your Vault. When your information changes, it updates for everyone you’ve shared it with automatically.
* **The Power to Revoke:** Trust is not a one-time transaction. Every share is a live connection that can be monitored, limited by view count/time, or severed instantly. When you revoke a link, you reclaim your privacy.

## Repositories

| Repo | Description |
|------|-------------|
| [api](https://github.com/revokedlink/api) | Go/PocketBase backend API |
| [docs](https://github.com/revokedlink/docs) | OpenAPI spec + documentation site |

## Getting Started

To spin up your own instance of the core API:

```bash
git clone https://github.com/revokedlink/api
cd api
go run main.go
