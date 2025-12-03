This is a Next.js project bootstrapped with [`create-plasmic-app`](https://www.npmjs.com/package/create-plasmic-app).

## Getting Started

First, run the development server:

```bash
npm run dev
```

Open your browser to see the result.

You can start editing your project in Plasmic Studio. The page auto-updates as you edit the project.

## Branch previews on GitHub Pages

Every push or pull request triggers the `Build and deploy branch preview` workflow to produce a static export and publish it to GitHub Pages.

- Previews are built with a branch-specific base path so assets resolve correctly when hosted under `https://<owner>.github.io/<repo>`.
- Each branch is deployed to the `gh-pages` branch under `previews/<branch>`, producing preview URLs such as `https://<owner>.github.io/<repo>/previews/<branch>/`.
- Builds always run, and deployments are skipped automatically for pull requests from forks that do not have permission to push to `gh-pages`.
- Set the `NEXT_PUBLIC_BASE_PATH` environment variable when building locally to mirror the GitHub Pages path, e.g. `NEXT_PUBLIC_BASE_PATH=/plasmic/previews/my-branch npm run build`.

## Learn More

With Plasmic, you can enable non-developers on your team to publish pages and content into your website or app.

To learn more about Plasmic, take a look at the following resources:

- [Plasmic Website](https://www.plasmic.app/)
- [Plasmic Documentation](https://docs.plasmic.app/learn/)
- [Plasmic Community Forum](https://forum.plasmic.app/)

You can check out [the Plasmic GitHub repository](https://github.com/plasmicapp/plasmic) - your feedback and contributions are welcome!
