# go-quay/swagger

```console
$ curl -sSL https://quay.io/api/v1/discovery | python3 -c 'import sys,json;print(json.dumps(json.load(sys.stdin),indent=2))' > quay.json

# or use `jq`
$ curl -sSL 'https://quay.io/api/v1/discovery' | jq '' > quay.json
```
