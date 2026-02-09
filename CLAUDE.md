# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

MCP (Model Context Protocol) server for MulmoScript generation. Provides MCP tools for creating MulmoScript content through AI interactions.

## Commands

```bash
yarn build      # Compile TypeScript (tsc)
yarn lint       # Run ESLint on src/ and tests/
yarn format     # Format with Prettier
yarn test       # Run tests (node:test with ts-node)
```

## Architecture

- `src/index.ts` - MCP server entry point
- `src/mulmo_script_generator.ts` - MulmoScript generation logic
- `src/tools.ts` - MCP tool definitions
- `tests/` - Test files (test_*.ts pattern)
