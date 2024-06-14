# ⚠️ WIP

Uncomment a line that includes the desired endpoint configuration:

```sh

cmd=(
    docker stack config --compose-file ./compose.template.yaml
    # --compose-file ./compose.http.yaml
    # --compose-file ./compose.lets-encrypt.yaml
    # --compose-file ./compose.custom-tls.yaml
) && "${cmd[@]}" | docker stack deploy --compose-file - op-connect
```
