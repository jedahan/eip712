This was vendored out from [parity-ethereum][] until [10092][] is resolved.

    git clone https://github.com/paritytech/parity-ethereum
    cd parity-ethereum
    git filter-branch --subdirectory-filter util/EIP-712
    cargo test
    git remote add jedahan https://github.com/jedahan/eip712
    hub create jedahan/eip712
    git push

[parity-ethereum]: https://github.com/paritytech/parity-ethereum
[10092]: https://github.com/paritytech/parity-ethereum/issues/10092
