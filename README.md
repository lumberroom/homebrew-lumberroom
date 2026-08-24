# homebrew-lumberroom

The Homebrew tap for [lumberroom](https://lumberroom.cloud), a personal memory control plane.

```bash
brew tap the-cybersapien/lumberroom
brew install lumberroom
lumberroom doctor
```

This installs the command line client. It talks to a lumberroom server you host; it is not one.
[The source repository](https://github.com/the-cybersapien/lumberroom) covers running the server.

The formula carries prebuilt binaries for macOS and Linux, on both arm64 and x86_64, and pins a
sha256 per archive against the release it names. `deploy/homebrew/lumberroom.rb` in the source
repository is where a new version gets prepared before it lands here.
