# Real-Time Analytics Dashboard

This project demonstrates a real-time analytics dashboard using Rust, Python, and Elixir.

## Project Structure

- **core-engine (Rust)**: Handles data ingestion.
- **data-processing (Python)**: Processes incoming data.
- **web-server (Elixir)**: Serves the web dashboard.

## Setup

### Prerequisites

- Rust
- Python 3
- Elixir

### Running the Core Engine

```bash
cd core-engine
cargo run
```

### Running the Data Processing

```bash
cd data-processing
python app.py
```

### Running the Web Server

```bash
cd web-server
mix deps.get
iex -S mix
```

## Usage

1. Start the Core Engine.
2. Start the Data Processing.
3. Start the Web Server.
