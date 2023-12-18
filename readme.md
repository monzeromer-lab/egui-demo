# egui-demo

A Rust project using `egui` for testing and demonstration purposes.

## Prerequisites

Before you begin, ensure you have the following installed on your system:

- Rust (stable): [Rust Installation Guide](https://www.rust-lang.org/)
- Cargo: Included with Rust installation
- cargo-deb: Install using `cargo install cargo-deb`

## Building and Running the Demo

To build and run the demo, follow these steps:

1. Clone the repository:

   ```bash
   git clone https://github.com/monzeromer-lab/egui-demo.git
   cd egui-demo
   ```

2. Build using Cargo:

   ```bash
   cargo build --release
   ```

   The executable will be generated in the `target/release/` directory.

3. Create Debian (deb) Executable:

   ```bash
   cargo deb --install
   ```

   This command will build the Debian package and install it on your system. you can igore the installation by removing the `--install` arg

4. Run the Demo:

   ```bash
   ./target/release/egui-demo
   ```

## License

This project is licensed under the MIT license - see the [LICENSE](LICENSE) file for details.
