# Personal web deployment

Source: ZayGym-source-2026-10-14.zip in the public test release.
Existing production dist-web build, served under /ZayGym/app/.
Manifest: ZayGym name, pt-BR, relative start/scope, existing 192/512 icons.
Static public config: guest access only, no backend or financial service.
Four absolute licensed-video URLs in the compiled main module use /ZayGym/app/zaygym-videos/ instead of /zaygym-videos/.
Service worker cache names and deletion are scoped to zaygym-public- to preserve other sites' caches.
No database, account data, key, or runtime state is hosted.
