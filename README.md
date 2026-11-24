# Unraid Community Applications

Unraid templates for apps by Alex Stevenson-Price, published through
[Community Applications](https://ca.unraid.net).

| App | Template | Project |
| --- | --- | --- |
| Slipmat | [`templates/slipmat.xml`](templates/slipmat.xml) | [alexjsp/slipmat](https://github.com/alexjsp/slipmat) |
| Tezca | [`templates/tezca.xml`](templates/tezca.xml) | [alexjsp/tezca-obsidian-sync](https://github.com/alexjsp/tezca-obsidian-sync) |

## Installing before an app is listed

Fetch the template for the app you want on the server, then pick it from **Docker → Add Container → Template**:

```sh
wget -O /boot/config/plugins/dockerMan/templates-user/my-Slipmat.xml \
  https://raw.githubusercontent.com/alexjsp/unraid-community-apps/main/templates/slipmat.xml
wget -O /boot/config/plugins/dockerMan/templates-user/my-Tezca.xml \
  https://raw.githubusercontent.com/alexjsp/unraid-community-apps/main/templates/tezca.xml
```

## Support

Open an issue on the app's own repository. Issues with a template itself are welcome here.
