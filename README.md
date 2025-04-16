# yellowstone-grpc-cleint

1. Compile yellowstone

    https://github.com/rpcpool/yellowstone-grpc

2. Create yellowstone config

    see #config/yellow_stone_config.json

3. Start validator-node with plugin

    ```sh
    solana-test-validator --ledger ./test-ledger --bind-address "0.0.0.0" --clone metaqbxxUerdq28cj1RbAWkYQm3ybzjb6a8bt518x1s --clone PwDiXFxQsGra4sFFTT8r1QWRMd4vfumiWC1jfWNfdYT --url <mainnet-node-url> --reset --geyser-plugin-config ./yellow_stone_config.json
    ```

