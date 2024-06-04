# Gumdrop 

See the [Metaplex Docs](https://docs.metaplex.com/airdrops/create-gumdrop) and the
[Example Deployment](https://gumdrop.metaplex.com/) for more information. The Gumdrop Program Rust code can be here: [MPL](https://github.com/metaplex-foundation/metaplex-program-library/tree/master/gumdrop).

## Setup

Be sure to be running Node v14.17.6 and yarn version 1.22.10.

`yarn bootstrap`

Then run:

`yarn start`

You may have to rebuild your package more than one time to secure a
running environment.

## ⚠️ Warning

Any content produced by Metaplex, or developer resources that Metaplex provides, are for educational and inspiration purposes only. Metaplex does not encourage, induce or sanction the deployment of any such applications in violation of applicable laws or regulations.

## To Create Airdrop

Example
```
ts-node gumdrop-cli.ts create -e ${environment} --keypair ${your_secret.json} --distribution-list ${your_list.json} --claim-integration transfer --transfer-mint ${token_account} --distribution-method wallets
```

