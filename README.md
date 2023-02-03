# Wolf Game Interface

Wolf Game UI

Aptos testnet: https://test.wolfgameaptos.xyz/
Aptos mainnet: https://wolfgameaptos.xyz/

## How to deploy

1. `git clone https://github.com/Plor3r/wolfgame-interface`
2. if test on testnet, edit `.env.local`:

    ```env
    NEXT_PUBLIC_APTOS_NODE_URL=https://fullnode.testnet.aptoslabs.com/v1/
    NEXT_PUBLIC_APTOS_FAUCET_URL=https://faucet.testnet.aptoslabs.com/v1/
    NEXT_PUBLIC_APTOS_NETWORK=testnet
    ```

3. `yarn`
4. `yarn dev` for development
5. `yarn build` for production
