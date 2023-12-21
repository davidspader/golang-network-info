# Golang Network Info

This Go command-line application is a project created for educational purposes. It demonstrates basic networking concepts by performing IP address and server name lookups on the internet.

## Features

- **IP Address Lookup:** Find IP addresses associated with a given host.

- **Server Name Lookup:** Retrieve the names of servers associated with a given host.

## Getting Started

### Prerequisites

- [Go](https://golang.org/) installed on your machine.

### Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/your-username/golang-network-info.git
    ```

2. Navigate to the project directory:

    ```bash
    cd golang-network-info
    ```

## Usage

### IP Address Lookup

```bash
go run main.go ip --host example.com
```

### Server name Lookup

```bash
go run main.go servers --host example.com
```