# Prysm Network
Prysm Network is an ICS hub for L1 and L2 applications. Providing security, infrastructure, cross-chain communication, and unified liquidity.  

## Devnet

- `make testnet` *IBC testnet from chain <-> local cosmos-hub*
- `make sh-testnet` *Single node, no IBC. quick iteration*

## Local Images

- `make install`      *Builds the chain's binary*
- `make local-image`  *Builds the chain's docker image*

## Testing

- `go test ./... -v` *Unit test*
- `make ictest-*`  *E2E testing*
