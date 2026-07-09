# PolyCop OpenAPI docs

This repository contains the Mintlify documentation site for PolyCop OpenAPI.

## Contents

- Guide pages in MDX
- Navigation and theme settings in `docs.json`
- API reference pages generated from `openapi.third-party.yaml`

## Local preview

Install the [Mintlify CLI](https://www.npmjs.com/package/mint):

```bash
npm i -g mint
```

Run the preview from this directory:

```bash
mint dev
```

The local site runs at `http://localhost:3000`.

## Publishing changes

Mintlify deploys the site after changes are pushed to the default branch.

## Troubleshooting

- If the local preview does not start, run `mint update` and retry.
- If a page returns 404, confirm that you are running `mint dev` from the directory that contains `docs.json`.

## Resources

- [Mintlify documentation](https://mintlify.com/docs)
