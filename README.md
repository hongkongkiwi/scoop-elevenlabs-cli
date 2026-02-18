<h1 align="center">Scoop Bucket: ElevenLabs CLI</h1>

<p align="center">
  Install <code>elevenlabs-cli</code> on Windows with Scoop.
</p>

<p align="center">
  <a href="https://github.com/hongkongkiwi/elevenlabs-cli/releases">
    <img src="https://img.shields.io/github/v/release/hongkongkiwi/elevenlabs-cli?style=for-the-badge&logo=github&label=upstream%20release" alt="Upstream Release" />
  </a>
  <a href="https://github.com/hongkongkiwi/scoop-elevenlabs-cli/blob/main/elevenlabs-cli.json">
    <img src="https://img.shields.io/badge/scoop-manifest-4A89DC?style=for-the-badge" alt="Scoop Manifest" />
  </a>
  <a href="https://opensource.org/licenses/MIT">
    <img src="https://img.shields.io/badge/license-MIT-3DA639?style=for-the-badge" alt="MIT License" />
  </a>
</p>

> [!WARNING]
> ElevenLabs CLI is community-built and not an official ElevenLabs release.

## Install

```powershell
scoop bucket add elevenlabs-cli https://github.com/hongkongkiwi/scoop-elevenlabs-cli
scoop install elevenlabs-cli
```

## Upgrade

```powershell
scoop update
scoop update elevenlabs-cli
```

## Verify

```powershell
elevenlabs-cli --version
```

## Quick Test

```powershell
$env:ELEVENLABS_API_KEY = "your-api-key"
elevenlabs-cli tts "Scoop install is working" --output hello.mp3
```

## What You Get

- Windows-native package installs via Scoop
- Automated manifest updates from upstream GitHub releases
- Same CLI features and flags as the main project

## Related Repositories

| Repository | Purpose | README |
| --- | --- | --- |
| [hongkongkiwi/elevenlabs-cli](https://github.com/hongkongkiwi/elevenlabs-cli) | Main CLI source and release pipeline | [Open](https://github.com/hongkongkiwi/elevenlabs-cli/blob/main/README.md) |
| [hongkongkiwi/homebrew-elevenlabs-cli](https://github.com/hongkongkiwi/homebrew-elevenlabs-cli) | macOS/Linux Homebrew tap | [Open](https://github.com/hongkongkiwi/homebrew-elevenlabs-cli/blob/main/README.md) |
| [hongkongkiwi/action-elevenlabs-cli](https://github.com/hongkongkiwi/action-elevenlabs-cli) | GitHub Actions integration | [Open](https://github.com/hongkongkiwi/action-elevenlabs-cli/blob/main/README.md) |
| [hongkongkiwi/elevenlabs-cli-skill](https://github.com/hongkongkiwi/elevenlabs-cli-skill) | AI-agent skill package | [Open](https://github.com/hongkongkiwi/elevenlabs-cli-skill/blob/main/README.md) |

## License

MIT.
