# Voltra — prebuilt binaries

Prebuilt [Voltra](https://github.com/Salaou-Hasan/voltra-releases/releases) engine binaries.

## Download

```
voltra update          # self-update an existing install
```

Or grab the latest binary directly for your platform:

### Windows (PowerShell)

```powershell
iwr https://github.com/Salaou-Hasan/voltra-releases/releases/latest/download/voltra-windows-x86_64.exe -OutFile voltra.exe
```

### Linux (x86_64)

```bash
curl -L https://github.com/Salaou-Hasan/voltra-releases/releases/latest/download/voltra-linux-x86_64 -o voltra
chmod +x voltra
```

### macOS (Apple Silicon / aarch64)

```bash
curl -L https://github.com/Salaou-Hasan/voltra-releases/releases/latest/download/voltra-macos-aarch64 -o voltra
chmod +x voltra
```

### macOS (Intel / x86_64)

```bash
curl -L https://github.com/Salaou-Hasan/voltra-releases/releases/latest/download/voltra-macos-x86_64 -o voltra
chmod +x voltra
```

Game builds are published under the `voltra-game` tag.
