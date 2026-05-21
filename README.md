# AImage SaaS

Built with [Wasp](https://wasp.sh), based on the [Open SaaS](https://opensaas.sh) template.

## 🚀 Deploy to Railway

This project automatically deploys to Railway on every push to the main branch via GitHub Actions.

## Development

### Running locally

- Make sure you have the .env.client and .env.server files with correct dev values in the root of the project.
- Run the database with wasp start db and leave it running.
- Run wasp start and leave it running.
- [OPTIONAL]: If this is the first time starting the app, or you've just made changes to your entities/prisma schema, also run wasp db migrate-dev.

See the [Open SaaS docs](https://docs.opensaas.sh) for more details.