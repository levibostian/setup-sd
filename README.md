# setup-sd

This action sets up [chmln/sd](https://github.com/chmln/sd).

## Usage

```yaml
jobs:
  test:
    runs-on: ubuntu-latest
    steps:
      - name: Check out repository
        uses: actions/checkout@v3

      - name: Set up sd
        uses: kenji-miyake/setup-sd@v1

      - name: Run sd
        run: |
          sd before after
```

## Action inputs and outputs

Refer to [action.yaml](./action.yaml).
