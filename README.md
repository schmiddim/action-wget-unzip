[![.github/workflows/main.yaml](https://github.com/schmiddim/action-wget-unzip/actions/workflows/main.yaml/badge.svg?branch=master)](https://github.com/schmiddim/action-wget-unzip/actions/workflows/main.yaml)

# Download Zip file and extract it action

This action downloads a zip file and extracts it to a certain folder

## Inputs

## `url`

**Required** What to download.
## `destination`

**Required**  Where to extract

## Example usage
```yaml
uses: schmiddim/action-wget-unzip@v2
with:
  url: 'https://github.com/hpool-dev/chia-miner/releases/download/1.5.6/HPool-Miner-chia-og-v1.5.6-1-linux.zip'
  destination: arm-release
```
