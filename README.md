# solana-client

basic solana native program and client

## config - build - deploy

`solana-keygen new --no-bip39-passphrase`

`solana config set --keypair /root/.config/solana/id.json`

`solana config set --url http://api.devnet.solana.com`

`cargo init program --lib`

`cargo add solana-program`

`cargo-build-sbf --arch bpf `

`solana program deploy target/deploy/solana_client.so`

## Program Id: HGPydrVpNajDC2BjepAeMyM6PQPoVUnxj1jbN54SfLLp

`solana program show --programs`
