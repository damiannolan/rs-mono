## Overview

The following is an example repository layout for the rust programs and services.

1. Install `evm-prover` gRPC service binary.

    ```shell
    cargo install --path ./crates/evm-prover
    ```

2. Initialise a new service home directory.

    ```shell
    evm-prover init
    ```

3. Run the `evm-prover` gRPC service.

    ```shell
    evm-prover start
    ```