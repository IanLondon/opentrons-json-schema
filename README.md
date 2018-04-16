This repo is just to host docs for the proposal, once this is solidified more we'll move this into the Opentrons/opentrons monorepo!

## Build docs

```bash
# install dependencies
yarn install

# build docs
./node_modules/.bin/bootprint json-schema schema.json docs
```
