# GPG Key for CI/CD Signing

Used for signing Maven Central releases. You should verify the artifact signatures using this public key before trusting any published release.

- Key ID: `0xAA2E718DF80DD557`
- Fingerprint: `04E2 72BB 9220 C152 5E89  0A57 AA2E 718D F80D D557`
- UID: `Peak Solution CI Signing Key <ci@peak-solution.de>`
- Keyserver: `keys.openpgp.org`

To import the key:
```
gpg --keyserver keys.openpgp.org --recv-keys 0xAA2E718DF80DD557
```

# GPG Keys of Maintainers

This project publishes signed artifacts (e.g., `.jar.asc`, `.pom.asc`) to Maven Central.
Below is the list of GPG keys used by the maintainers to sign these artifacts.

| Name          | Email                     | Key ID               | Fingerprint                                 | Keyserver             |
|---------------|---------------------------|----------------------|---------------------------------------------|------------------------|
| Markus Renner | m.renner@peak-solution.de | `0x68E9713E911A871C` | `A40F AA78 F7AB D88D 254E D696 68E9 713E 911A 871C` | `keys.openpgp.org` |
|    |            | ``                   | `` | `keys.openpgp.org` |

## Importing the Keys

```
gpg --keyserver hkps://keys.openpgp.org --recv-keys 0x68E9713E911A871C
