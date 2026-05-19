# Codex Setup Guide for ECC

Everything Claude Code (ECC) is now **fully compatible with Codex CLI**. This guide shows how to set up ECC for Codex from scratch.

## Quick Start (2 minutes)

### Option 1: Plugin Install (Recommended)

```bash
# Add the ECC repository as a marketplace
codex plugin marketplace add affaan-m/ECC

# Install the ECC plugin
codex plugin install ecc

# Verify installation
codex plugin list

# Clone the repo
git clone https://github.com/affaan-m/ECC.git
cd ECC

# Install dependencies
npm install

# Copy Codex config to project (or user-level)
cp .codex/config.toml ~/.codex/config.toml  # Global
# OR keep .codex/config.toml in the project root for local defaults

# Start Codex
codex
