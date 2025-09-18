# compromised-packagelock-scanner

Small python script with no dependencies to search `package-lock.json` files on disk and scan comprised NPM packages from there.

Requires Python 3.6+.

## Execute

```bash
python3 compromised-packagelock-scanner.py
```

## Sources

Static list of packages were extracted from the following websites:
- https://www.koi.security/blog/shai-hulud-npm-supply-chain-attack-crowdstrike-tinycolor
- https://orca.security/resources/blog/qix-npm-attack/

