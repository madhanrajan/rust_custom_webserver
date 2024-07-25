# Custom Rust Webserver

This project is a basic, simple, and multithreaded webserver built using the Rust programming language. It is designed to be lightweight, efficient, and easy to use.

## Features

- **Basic:** Minimal functionality to get started quickly.
- **Simple:** Easy to understand and extend.
- **Multithreaded:** Utilizes Rust's concurrency features for handling multiple connections efficiently.
- **Lightweight:** Minimal dependencies and efficient code.
- **Asynchronous:** Utilizes async/await for handling multiple connections concurrently.
- **Customizable:** Easily extendable to fit various needs.
- **Secure:** Includes basic security features such as HTTPS support.

## Requirements

- Rust (latest stable version)
- Cargo (Rust package manager)

## Installation

1. **Clone the repository:**

    ```sh
    git clone https://github.com/your-username/custom-rust-webserver.git
    cd custom-rust-webserver
    ```

2. **Build the project:**

    ```sh
    cargo build --release
    ```

3. **Run the server:**

    ```sh
    cargo run --release
    ```

## Configuration

The server can be configured using a `config.toml` file located in the root directory of the project. The available configuration options include:

```toml
[server]
port = 8080
host = "127.0.0.1"
use_https = true
cert_path = "path/to/cert.pem"
key_path = "path/to/key.pem"
