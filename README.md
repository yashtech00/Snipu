# Snipu - Bitcoin Script VM in Cairo

**Revolutionizing Code Sharing in Web3 with Blockchain-Powered Collaboration**
![Snipu Logo](https://raw.githubusercontent.com/SudiptaPaul-31/Snipu/refs/heads/main/images/logo.jpg)


<p align="center">
  <a href="https://github.com/SudiptaPaul-31/Snipu"><img src="https://img.shields.io/badge/BUILD-PASSING-brightgreen?style=for-the-badge&logo=github&logoColor=white&labelColor=black" alt="BUILD"></a>
  <a href="https://bitcoin.org/"><img src="https://img.shields.io/badge/BITCOIN-000000?style=for-the-badge&logo=bitcoin&logoColor=white" alt="BITCOIN"></a>
  <a href="https://www.cairo-lang.org/"><img src="https://img.shields.io/badge/CAIRO-1a1a1a?style=for-the-badge&logo=cairo&logoColor=white" alt="CAIRO"></a>
  <a href="https://reactjs.org/"><img src="https://img.shields.io/badge/REACT-61DAFB?style=for-the-badge&logo=react&logoColor=black" alt="REACT"></a>
</p>

<p align="center">
  <a href="https://github.com/SudiptaPaul-31"><img src="https://img.shields.io/badge/EXPLORATION_TEAM-212121?style=for-the-badge" alt="EXPLORATION TEAM"></a>
  <a href="https://t.me/bitcoinwildlife"><img src="https://img.shields.io/badge/TELEGRAM-26A5E4?style=for-the-badge&logo=telegram&logoColor=white" alt="TELEGRAM"></a>
</p>

## Overview

Snipu is an innovative Bitcoin Script Virtual Machine implemented in Cairo, designed to bring Bitcoin's scripting capabilities to Layer 2 solutions. This project enables developers to execute and verify Bitcoin scripts within the Cairo environment, facilitating advanced interoperability between Bitcoin and other blockchain platforms.

## Website Workflow

The Snipu platform offers a streamlined experience for developers looking to work with Bitcoin scripts in Cairo:

1. **Home Page**: Users are greeted with an overview of Snipu's capabilities and key features.

2. **Script Editor**:
   - Write custom Bitcoin scripts directly in the browser
   - Access a library of template scripts for common use cases
   - Syntax highlighting and error checking in real-time

3. **Compiler Interface**:
   - Compile Bitcoin scripts into Cairo-compatible format
   - View detailed compilation logs and debugging information
   - Export compiled scripts for integration with other projects

4. **Testing Environment**:
   - Execute compiled scripts in a sandboxed environment
   - Provide custom inputs and witness data for script execution
   - View execution results and stack states

5. **Documentation Center**:
   - Access comprehensive guides on using Snipu
   - Reference materials for Bitcoin Script opcodes and their Cairo implementations
   - Step-by-step tutorials for common development scenarios

6. **Community Hub**:
   - Connect with other developers using Snipu
   - Share custom scripts and implementations
   - Discuss best practices and technical challenges

## Features

### Core VM Implementation
- Full implementation of Bitcoin Script opcodes in Cairo
- Stack-based execution environment matching Bitcoin's processing model
- Accurate handling of Bitcoin's execution constraints and edge cases

### Script Compilation
- Bitcoin Script to Cairo transpilation with optimization
- Support for both legacy and SegWit script formats
- Preservation of script semantics across languages

### Verification Tools
- Zero-knowledge proof generation for script execution
- On-chain verification of Bitcoin script execution on Layer 2
- Cryptographic linking between Bitcoin and Cairo execution environments

### Developer Tools
- Comprehensive API for integrating Snipu into existing applications
- CLI tools for batch processing and automation
- Detailed execution logs for debugging complex scripts

### Interoperability Features
- Cross-chain messaging capabilities using Bitcoin scripts
- Bitcoin transaction verification on Layer 2 platforms
- Bridge mechanisms for Bitcoin-based assets

### Security Components
- Formal verification of core VM components
- Comprehensive test suite covering edge cases
- Security audit-ready architecture

## Technologies Used

### Core Technologies
- **Cairo Language** (v1.0.0): Zero-knowledge friendly programming language for VM implementation
- **Bitcoin Script**: Native Bitcoin scripting language supported by the VM
- **React** (v18.2.0): Frontend framework for the web interface
- **TypeScript** (v4.9.5): Type-safe language for frontend development
- **Node.js** (v16.20.0): Runtime environment for development tools

### Backend Stack
- **Rust** (v1.70.0): Performance-critical components and optimization
- **Scarb** (v0.7.0): Cairo package manager
- **StarkNet** (v0.13.0): Layer 2 integration for on-chain verification

### Frontend Libraries
- **Redux** (v8.1.0): State management for the application
- **Material UI** (v5.13.0): Component library for consistent UI
- **Monaco Editor** (v0.40.0): Code editor for script writing
- **Web3.js** (v1.10.0): Blockchain interaction library
- **D3.js** (v7.8.5): Data visualization for script execution

### Development Tools
- **Docker** (v24.0.5): Containerization for consistent development and deployment
- **GitHub Actions**: CI/CD pipeline for automated testing and deployment
- **Jest** (v29.5.0): Testing framework for frontend components
- **Starknet.js** (v5.14.1): Client library for StarkNet integration
- **ESLint** (v8.40.0): Code quality and style enforcement

### Security Tools
- **Slither**: Smart contract static analyzer
- **Cairo-Test**: Cairo-specific testing framework
- **OpenZeppelin Contracts**: Secure, reusable smart contract components

## Getting Started

### Prerequisites
- Node.js (v18 or higher)
- Rust (v1.70 or higher)
- Starknet wallet (ArgentX or Braavos)
- Yarn/NPM/PNPM/Bun

### Installation

1. Clone the repository:
```bash
git clone https://github.com/SudiptaPaul-31/Snipu.git
cd Snipu

## 🚀 Getting Started

1. Clone the repository:
```bash
git clone https://github.com/yourusername/snipu.git
```
2. Install dependencies :
```bash
npm install
# or
yarn
# or
pnpm install
# or
bun install
```
3. Running locally:
```bash
npm run dev
# or
yarn dev
# or
pnpm dev
# or
bun dev
```
