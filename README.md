# ⚠️ WIP

Uncomment a line that includes the desired endpoint configuration:

```sh
(docker stack config --compose-file ./compose.template.yaml \
    # --compose-file ./compose.http.yaml \
    # --compose-file ./compose.lets-encrypt.yaml \
    # --compose-file ./compose.custom-tls.yaml \
) | docker stack deploy --compose-file - op-connect
```
