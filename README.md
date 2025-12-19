# BunnyEraAPI

## Overview
BunnyEra API service for enterprise integration.  
Provides SMS verification, data query, and unified REST/GraphQL endpoints for brand system modules.  
This repository serves as the backend API layer for BunnyEra’s brand matrix.

## Features
- Unified API endpoints (REST/GraphQL)
- SMS verification and code delivery
- Data query services for enterprise modules
- Integration with BunnyEra Console and AccountManager
- Secure authentication and compliance-ready design

## Architecture
- **Core Module**: Verification and data query
- **Integration**: Works with BunnyEra Console, AccountManager, and NotifyCenter
- **Resource Pool**: Phone numbers, emails, and identity modules

## Installation
```bash
git clone https://github.com/BunnyEraOfficial/BunnyEraAPI.git
cd BunnyEraAPI
npm install
