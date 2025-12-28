# ChatSphere

## Overview

ChatSphere is a versatile, cross-platform chat application designed to facilitate real-time communication between users. Built with modern technologies, it supports both command-line interface (CLI) and graphical user interface (GUI) modes, enabling seamless messaging, file sharing, and integrated gaming features.

## Key Features

- **Real-Time Messaging**: Instant text-based communication via secure socket connections.
- **Multi-Platform Support**: Runs on Windows, macOS, Linux, and other operating systems.
- **CLI and GUI Modes**: Choose between a lightweight command-line client or a full-featured graphical interface.
- **File Sharing**: Easily send and receive files during chats.
- **In-App Games**: Play simple games directly within the chat environment to enhance user interaction.
- **Extensible Architecture**: Modular design allows for easy addition of new features like voice chat or video calls.

## Development

### Coding Standards

ChatSphere follows universal C++ coding standards enforced by clang-format and clang-tidy. The project uses LLVM-based formatting rules and a comprehensive set of static analysis checks.

- **Formatting**: Code is automatically formatted using clang-format with the provided `.clang-format` configuration.
- **Linting**: clang-tidy checks for code quality, performance, and best practices.
- **CI Enforcement**: All pull requests must pass clang-format and clang-tidy checks.

### VS Code Configuration

The `.vscode/settings.json` file configures VS Code to use the project's clang-format and clang-tidy settings for consistent development experience.

## Getting Started

### Installation

Download the latest release from the [GitHub Releases](https://github.com/amaraoussama94/ChatSphere/releases) page. Choose the appropriate version for your operating system.

### Running the Application

1. **Server Setup**: Launch the server component to host chat sessions.
2. **Client Connection**: Use the CLI or GUI client to connect to the server and start chatting.
3. **Joining Chats**: Enter the server address and port to join existing conversations.

### Basic Usage

- **Sending Messages**: Type your message and press Enter (CLI) or click Send (GUI).
- **File Sharing**: Select files to share from the interface.
- **Playing Games**: Access the games menu to start multiplayer games with other users.

## Architecture

ChatSphere uses a client-server model:
- **Server**: Manages connections, broadcasts messages, and coordinates game sessions.
- **Clients**: Connect to the server for messaging and feature access.

The application leverages socket-based communication for reliability and low latency.

## Documentation

- [Architecture](docs/ARCHITECTURE.md): Technical overview of the system design.
- [Contributing](CONTRIBUTING.md): Guidelines for contributors.
