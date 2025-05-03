# khushalHelloWorldGrpcStarter

A simple Hello World gRPC service implementation using Python and Bazel.

## Project Structure

```
.
├── protos/          # Protocol buffer definitions
├── src/
│   ├── client/     # gRPC client implementation
│   └── server/     # gRPC server implementation
├── WORKSPACE        # Bazel workspace file
├── requirements.txt # Python dependencies
└── README.md       # This file
```

## Prerequisites

- Python 3.11 or later
- Bazel 8.0 or later
- gRPC tools

## Building

To build the project:

```bash
bazel build //...
```

## Running

(Server and client run instructions will be added once implemented)

## License

MIT License 