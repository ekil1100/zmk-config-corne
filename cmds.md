```shell
west build -s zmk/app -b "nice_nano_v2" -- -DZMK_CONFIG="${GITHUB_WORKSPACE}/config" -DSHIELD="corne_left nice_view_adapter nice_view"
```

```shell
west build -s zmk/app -b "nice_nano_v2" -- -DZMK_CONFIG="${GITHUB_WORKSPACE}/config" -DSHIELD="corne_right nice_view_adapter nice_view"
```
