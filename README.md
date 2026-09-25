<p align="center">
  <img src="https://raw.githubusercontent.com/Coccinella-Labs/course/main/.github/assets/thumbnail.png" alt="course" width="100%">
</p>

Swift SystemManager package (macOS 14+, Swift 6.1) for observing and controlling macOS processes, with a Python bridge via PythonKit.

## Run

```bash
swift build -c release
.build/release/course --help
```

## Layout

- `Sources/Core` - protocols and shared types
- `Sources/SystemInterfaces` - system interface layer
- `Sources/SystemObservation` - observation layer
- `Sources/ControlPlane` - control plane
- `Sources/CLI`, `Sources/UI` - command line and UI frontends
- `Tests/` - test suite (`swift test`)