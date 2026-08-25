# my-scoop-bucket

Automated personal Scoop bucket for custom Windows applications.

## Managed Applications

- **pattn**: PattN (v2rayN fork for Iranian network conditions with Avalonia UI Desktop build)
- **dicodeping**: DicodePing network ping tool and tunnel client
- **activitywatch-beta**: ActivityWatch time tracker (beta builds)

## Automated Updates

This bucket automatically checks for new releases on GitHub every **3 hours** using GitHub Actions (`.github/workflows/checkver.yml`).

## Installation

Add this bucket to Scoop:

```powershell
scoop bucket add my-scoop-bucket https://github.com/SA-Mousavichashmi/my-scoop-bucket
```

Install an app:

```powershell
scoop install pattn
```
