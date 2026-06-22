# Changelog

## 0.1.1 - 2026-06-22

- Change the ScriptCat schedule from every 3 hours to every 2 hours after the 3-hour interval did not keep the WebVPN session renewed reliably.

## 0.1.0 - 2026-06-21

- Initial ScriptCat scheduled script for Hebei Medical University WebVPN session keepalive.
- Uses a verified protected WebVPN library URL as the keepalive probe.
- Keeps permissions minimal: `GM_xmlhttpRequest` plus `@connect webvpn.hebmu.edu.cn`.
