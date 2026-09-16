# Fikir Defteri

Kişisel, simbiyotik fikir defteri. PWA — Android telefonda yakalama, Windows'ta genel bakış ve düzenleme. Tam kapsam için [idea_app_implementation_plan.md](./idea_app_implementation_plan.md) dosyasına bakın.

## Geliştirme

```bash
npm install
npm run dev
```

Prod derlemesini yerelde offline/PWA davranışıyla test etmek için:

```bash
npm run build
npm run preview
```

## Yığın

Vite + React + TypeScript · `vite-plugin-pwa` (offline, manifest) · Dexie (IndexedDB) · i18next (TR/EN) · `@dnd-kit` (sekans) · `cytoscape` (bağlantı haritası).

## Yayın

`main` dalına her push, GitHub Actions ile derleyip GitHub Pages'e yayınlar (bkz. `.github/workflows/deploy.yml`). Kurulum adımları için proje sahibine iletilen mesaja bakın.
