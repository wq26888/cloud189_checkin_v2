# Cloud189 Check-in Script

> 这个仓库已经停止单独维护。最新版本已合并到
> [wq268-ql-scripts/cloud189](https://github.com/wq26888/wq268-ql-scripts/tree/main/cloud189)。

_Last updated: 2026-05-27_

A small Python script for daily Cloud189 check-in, mainly intended for personal automation environments such as QingLong.

## Requirements

- Python 3
- `requests`
- `rsa`

Install dependencies if needed:

```bash
pip install requests rsa
```

## Environment Variables

### Required

#### `TY_USERNAME`

Cloud189 usernames. Use new lines for multiple accounts.

#### `TY_PASSWORD`

Cloud189 passwords. Use new lines for multiple accounts. The order must match `TY_USERNAME`.

### Optional

#### `RANDOM_SIGNIN`

Enable random delay before running. Default: `true`.

#### `MAX_RANDOM_DELAY`

Maximum random delay in seconds. Default: `3600`.

#### `TY_DEBUG`

Enable detailed debug logs. Default: `false`.

## Notification

If you need notifications, place `notify.py` in the same directory as the script.

## Notes

This script is for personal use only. Use it with your own account and at your own risk.
