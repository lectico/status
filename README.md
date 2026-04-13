# Lectico Status

Real-time uptime and incident history for the [Lectico](https://lectico.com) platform. Powered by [Upptime](https://upptime.js.org).

- **Live status**: https://status.lectico.com
- **Checks**: every 5 minutes
- **History**: commits to this repo (full audit trail)

## Monitored endpoints

| Service | URL |
|---------|-----|
| API | `https://api.lectico.com/v1/health` |
| Widget CDN | `https://cdn.lectico.com/widget/v1/widget.js` |
| Admin Panel | `https://app.lectico.com` |
| Marketing | `https://lectico.com` |
| Documentation | `https://docs.lectico.com` |
| Supabase REST | `https://byoxaihkwsjhrwbltjzb.supabase.co/rest/v1/` |

## Setup (post-creation)

1. In the repo settings, enable **GitHub Pages** from the `gh-pages` branch (Upptime creates it automatically after the first run).
2. Add a repository secret `GH_PAT` with a personal access token with `repo` + `workflow` scope.
3. Add a CNAME DNS record: `status.lectico.com → lectico.github.io`.
4. Trigger the first run manually: **Actions** → **Uptime CI** → **Run workflow**.

## License

MIT © Contenfo LLC (Lectico)
