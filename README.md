# solana-client

basic solana native program and client

## run

`solana logs | grep "48K4Hy8wpKdk6p3LH2YYXyxjzG8r1wQTqxymEMs7peBn invoke" -A 3`

`npm run start`

## program: config - build - deploy

`solana-keygen new --no-bip39-passphrase`

`solana config set --keypair /root/.config/solana/id.json`

`solana config set --url http://api.devnet.solana.com`

`cargo init program --lib`

`cargo add solana-program`

`cargo-build-sbf --arch bpf `

`solana program deploy target/deploy/solana_client.so`

## Program Id: HGPydrVpNajDC2BjepAeMyM6PQPoVUnxj1jbN54SfLLp

`solana program show --programs`

## client: config - build - deploy

`npm install`

`npm run build:program` -> create new build file in dist via cargo

`solana program deploy dist/program/program.so`
