# Agno Docs

## Development

Install the [Mintlify CLI](https://www.npmjs.com/package/mintlify) to run documentation site locally:

```
npm i -g mint
```

Run the following command at the root of your documentation (where docs.json is)

```
mint dev
```

## Publishing Changes

Publish changes by pushing to the main branch

```
git add .
git commit -m "update message"
git push
```

## Troubleshooting

- Mintlify dev isn't running - Run `mint update` it'll update dependencies.
- Page loads as a 404 - Make sure you are running in a folder with `docs.json`
