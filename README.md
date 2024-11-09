# catalog
This project implements a simplified Shamir's Secret Sharing in C++. It decodes each share's encoded value, constructs points on a polynomial, and uses Lagrange interpolation to find the constant term (secret). Input is parsed from JSON, and each share’s value is decoded from various bases, allowing secret reconstruction from encoded parts.

# Shamir's Secret Sharing

A simplified implementation of Shamir's Secret Sharing in C++. This program decodes secret shares and reconstructs the original polynomial's constant term using Lagrange interpolation.

## Requirements

- C++ compiler (g++ recommended)
- `nlohmann/json.hpp` for JSON parsing

## Setup

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/shamir-secret-sharing.git
   cd shamir-secret-sharing
