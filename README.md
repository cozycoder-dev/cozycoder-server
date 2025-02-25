# Cozy Coder Server

Sync and collaboration service for Cozy Coder.

## Prerequisites

- Elixir
- Docker Compose

### Installation

**Recommended:** Use [`mise`](https://mise.jdx.dev) to install Elixir:

```sh
mise install
  ```

## Usage

1. Setup dependencies:

   ```sh
   docker compose up -d
   mix setup
   ```

2. Start the application:

   ```sh
   mix phx.server
   ```

Now you can visit [`localhost:4000`](http://localhost:4000) from your browser.
