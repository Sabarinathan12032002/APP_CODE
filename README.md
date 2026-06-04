# APP_CODEX

A powerful desktop screenshot and document generation tool for Windows.

## Overview

APP_CODEX is a floating screenshot toolbar application that captures screenshots and automatically generates formatted Word documents. Built with JavaFX, Swing, and Apache POI, it provides a seamless workflow for document creation and management.

## Features

- Floating screenshot toolbar for easy access
- Screenshot capture and processing
- Automatic Word document generation
- Self-contained Windows installer (no Java installation required)
- Cross-platform JavaFX UI with Swing integration

## System Requirements

- Windows 11 or later
- JDK 24 (for development only)
- No Java required for end-users (bundled in installer)

## Installation

Download `APP_CODEX-1.0.exe` from the [Releases](https://github.com/SSUN8TA/APP_CODEX/releases) page and run it. The installer will handle all setup.

## Development Setup

1. Clone the repository
2. Ensure JDK 24 is installed
3. Run `mvn clean package` to build
4. Run `java -jar target\APP_CODEX.jar` to test

## Building the Installer

