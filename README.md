ors.workspace = true
edition.workspace = true
homepage.workspace = true
license.workspace = true
repository.workspace = true

[dependencies]
ansi_term = "0.12"
anyhow = "1"
cid = "0.10"
forc-tracing = { version = "0.46.1", path = "../forc-tracing" }
forc-util = { version = "0.46.1", path = "../forc-util" }
fuel-abi-types = "0.1"
futures = "0.3"
git2 = { version = "0.17.2", features = [
    "vendored-libgit2",
    "vendored-openssl",
] }
gix-url = { version = "0.16.0", features = ["serde1"] }
hex = "0.4.3"
ipfs-api-backend-hyper = { version = "0.6", features = ["with-builder"] }
petgraph = { version = "0.6", features = ["serde-1"] }
reqwest = "0.11.7"
semver = { version = "1.0", f
