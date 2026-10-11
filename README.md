# Matas Zostautas Portfolio

Static personal portfolio site for graduate software engineering, networking/infrastructure and cybersecurity applications.

## Local preview

Open `dist/index.html` in a browser, or serve the `dist` folder with any static server.

## Recommended deployment

Use Vercel first. It is free, quick to update from GitHub, and gives a professional URL immediately.

1. Create a new GitHub repository for this portfolio.
2. Push the contents of this `portfolio-site` folder.
3. In Vercel, import the GitHub repository.
4. Use these settings:
   - Framework preset: Other
   - Build command: leave empty
   - Output directory: `dist`
5. Deploy and use the generated Vercel URL on applications while deciding on a custom domain.

## Domain choices

- **Free Vercel URL:** best starting point. A URL like `matas-zostautas.vercel.app` is free and acceptable for applications.
- **`.xyz` domain:** best polished CV option. `mataszostautas.xyz` is clearer and more professional than a shortened name; `mataszos.xyz` is shorter and easier to type.
- **GitHub Pages:** free alternative, but Vercel is simpler for future Next.js or React projects if the portfolio grows.

If buying a `.xyz` domain, connect it to Vercel by adding the DNS records Vercel provides. Keep the Vercel URL as a fallback.

## Project screenshots

Screenshots are not included yet. Recommended additions:

- RoadGuardian: dashboard, emergency flow, live map or maintenance view.
- Assetra: manager dashboard, request workflow or stock table.
- SmartCAN-IDS: prototype dashboard once the FastAPI/React build exists.

## CV

The current CV is included at `dist/assets/Matas-Zostautas-CV.pdf`. Replace that file whenever the CV changes so the download link stays current.
