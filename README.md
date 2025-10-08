# Introduction to Computer Networks

This repository contains the full course material for an introduction to **Computer Networks**. The course is designed to cover the foundational principles and protocols that govern how data is transmitted across networks, from the physical layer to the application layer.

The material is structured to help students understand the architecture of the Internet, the TCP/IP and OSI models, and the core functionalities of protocols like IP, TCP, and HTTP. Code examples and lab assignments will focus on network programming fundamentals (e.g., sockets).

## Table of Contents

* [Overview](#-introduction-to-computer-networks)
* [Repository Structure](#repository-structure)
* [Getting Started](#getting-started)
* [Contributing](#contributing)
* [License](#license)

## Repository Structure

The course is organized into weekly modules. Each module folder contains theoretical lecture materials, practical exercises, and sample code, which may include network simulation scripts or socket programming examples (likely in Python or C).

| Folder | Description |
| :--- | :--- |
| `Week 01 - Introduction` | Covers the definition of a network, network topologies, the basics of the OSI and TCP/IP models, and a historical overview of the Internet. |
| `LICENSE` | The MIT License for this project. |
| ... | *More weekly modules will cover topics like the Physical Layer, Data Link Layer, Network Layer (IP/Routing), Transport Layer (TCP/UDP), and the Application Layer (HTTP/DNS).* |

## Getting Started

To work with the practical code examples (e.g., socket programming) in this course, you will need a basic development environment capable of running compiled languages and/or scripting languages.

### Prerequisites

* **C or Python:** The primary languages for networking examples.
* **Basic Command-Line Tools:** Familiarity with tools like `ping`, `traceroute`, `netstat`, and `ifconfig` (or `ip` on modern Linux systems).
* **Network Access:** A working internet connection or local network setup is required for some labs.

### Running the Code

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/vmarkos-mc/networks-introduction.git](https://github.com/vmarkos-mc/networks-introduction.git)
    cd networks-introduction
    ```

2.  **Executing Python Sockets:**
    Navigate to the relevant week and run the Python script:
    ```bash
    python Week\ 05\ -\ Transport\ Layer/tcp_server.py
    ```
    (Note: Specific file names and locations will vary by week.)

3.  **Executing C Programs:**
    If C examples are provided (e.g., for raw socket manipulation), they will need to be compiled:
    ```bash
    gcc -o client client_socket.c
    ./client
    ```

## Contributing

Contributions are greatly appreciated. If you find errors in the theoretical explanations, have cleaner code examples, or want to suggest new lab assignments, please follow the standard contribution procedure.

1.  **Fork** the repository.
2.  **Create** your feature branch (`git checkout -b feature/better-http-lab`).
3.  **Commit** your changes (`git commit -m 'Improved Lab 7 HTTP request handling'`).
4.  **Push** to the branch (`git push origin feature/better-http-lab`).
5.  **Open a Pull Request**.

## License

This project is licensed under the **MIT License** - see the [LICENSE](LICENSE) file for details.
