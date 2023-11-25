# Gosub MacOS Client
This is a proof of concept and NOT a functional client.

Think of this as a sandbox as we develop the [Gosub Engine](https://github.com/gosub-browser/gosub-engine) and figure things out.

# Prerequisites
If you plan on building this project from source, you must follow these steps to get started:
1. Clone the engine
    * `git clone git@github.com:gosub-browser/gosub-engine.git`
    * `cd gosub-engine/gosub-bindings`
    * `cargo build`
    * `make bindings`
2. Clone this repo
    * `git clone git@github.com:gosub-browser/gosub-client-macos.git`
    * copy the contents of `gosub-engine/gosub-bindings/include` to `gosub-client-macos/include`
    * copy the contents of `gosub-engine/gosub-bindings/lib` to `gosub-client-macos/lib`
