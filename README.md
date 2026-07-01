# Voltra — prebuilt binaries

Prebuilt [Voltra](https://github.com/Salaou-Hasan/voltra-releases/releases) engine binaries.

## Download

```
voltra update          # self-update an existing install
```

Or install fresh for your platform — this downloads the binary and puts it on
your PATH in one step (open a **new** terminal afterward for PATH to take
effect):

### Windows (PowerShell)

```powershell
iwr https://github.com/Salaou-Hasan/voltra-releases/releases/latest/download/voltra-windows-x86_64.exe -OutFile voltra.exe; .\voltra.exe install
```

### Linux (x86_64)

```bash
curl -L https://github.com/Salaou-Hasan/voltra-releases/releases/latest/download/voltra-linux-x86_64 -o voltra && chmod +x voltra && ./voltra install
```

### macOS (Apple Silicon / aarch64)

```bash
curl -L https://github.com/Salaou-Hasan/voltra-releases/releases/latest/download/voltra-macos-aarch64 -o voltra && chmod +x voltra && ./voltra install
```

### macOS (Intel / x86_64)

```bash
curl -L https://github.com/Salaou-Hasan/voltra-releases/releases/latest/download/voltra-macos-x86_64 -o voltra && chmod +x voltra && ./voltra install
```

Just want the binary without touching PATH — for CI, Docker, or dropping it
next to a project — drop the `install` step and run it as `./voltra` /
`.\voltra.exe` directly from wherever you downloaded it.

Game builds are published under the `voltra-game` tag.
