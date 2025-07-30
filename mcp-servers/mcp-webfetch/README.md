# Web Scraper MCP Server

A powerful Model Context Protocol (MCP) server that provides web scraping capabilities with screenshot functionality. Built with Rust using the `rmcp` library and `chromiumoxide` for browser automation.

## Features

- **Smart URL Handling**: Accepts various URL formats (full URLs, domain names, or simple names like "google")
- **Content Extraction**: Intelligently extracts main content from web pages, falling back to body text
- **Screenshot Capture**: Takes full-page screenshots and saves them locally
- **File Management**: Automatically saves content and screenshots with timestamped filenames
- **Dual Transport Support**: Works with both stdio (for MCP clients) and HTTP transports
- **Cross-Platform**: Automatically detects and uses Chrome, Chromium, or Edge browsers