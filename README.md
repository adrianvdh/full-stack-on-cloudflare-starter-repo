# cf-services-the-course-playground

## Development

### First-time setup

Before running the dev server, build the shared `@repo/data-ops` package:

```bash
pnpm run build-package
```

### Start the frontend dev server

```bash
pnpm run dev-frontend
pnpm run dev-data-service
```

The app will be available at http://localhost:3000/.

> **Note:** If you see `Cannot find module '@repo/data-ops/...'`, run `pnpm run build-package` first.