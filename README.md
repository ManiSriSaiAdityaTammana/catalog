# catalog
This project implements a simplified Shamir's Secret Sharing in C++. It decodes each share's encoded value, constructs points on a polynomial, and uses Lagrange interpolation to find the constant term (secret). Input is parsed from JSON, and each share’s value is decoded from various bases, allowing secret reconstruction from encoded parts.
