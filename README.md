# Setup

- `git submodule init; git submodule update`
- generate enclave signing key: `openssl genrsa -out enclave/enclave_private.pem -3 3072`
- import `solution.sln` into visual studio
- use configuration `Simulation`
- use debugger `Intel SGX`
- set as startup project `application`