# VLESS Cloudflare Worker - Rebuilt & Enhanced

A high-performance VLESS proxy implementation for Cloudflare Workers with enhanced reliability, better error handling, and improved features.

## 🚀 Features

- ✅ **Full VLESS Protocol Support** - Complete implementation with proper header parsing
- ✅ **WebSocket Transport** - Efficient WebSocket-based communication with early data support
- ✅ **TCP & UDP Support** - Handle both TCP connections and UDP DNS queries
- ✅ **DNS over HTTPS** - Integrated DoH support using Cloudflare's 1.1.1.1
- ✅ **Automatic Retry** - Smart connection retry mechanism for improved reliability
- ✅ **Multi-Address Support** - IPv4, IPv6, and domain name resolution
- ✅ **Enhanced Logging** - Comprehensive logging for debugging and monitoring
- ✅ **Status Dashboard** - Built-in web interface for monitoring worker status
- ✅ **Health Checks** - Dedicated health check endpoint for monitoring
- ✅ **Proxy IP Support** - Configurable proxy IP via URL path

## 📋 Quick Start

### 1. Prerequisites

```bash
# Install Wrangler CLI
npm install -g wrangler

# Login to Cloudflare
wrangler login
```
