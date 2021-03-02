# tenderly-push-action

GitHub Action to publish contracts to Tenderly.

## Usage

```yaml
- uses: keep-network/tenderly-push-action@v1
  working-directory: solidity
  continue-on-error: true # optional, don't fail the job on step failure
  with:
    tenderly-token: 0123456789AbCdEf
    tenderly-project: thesis/keep-dev
    eth-network-id: "1937"
    github-project-name: keep-core
    version-tag: "1.2.3"
```
