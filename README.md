# Testim

This action makes the testim.io cli available to your workflows

## Inputs

### `token`

**Required** The auth token

### `project`

**Required** The project id to run

### `grid`

**Required** The grid on which to execute the tests. Default `"Testim-Grid"`.

### `suite`

**Required** The test suite to execute.

### `arg`

**Optional** The rest of the cli options

## Example usage

```bash
uses: scolab/testim-cli-gh-action@v0.7.0
with:
  token: ${{ secrets.TESTIM_TOKEN }}
  project: <PROJECT_ID>
  grig: <GRID_NAME>
  suite: <SUITE_ID>
  arg: <OTHER COMMANDLINE OPTIONS>
```
