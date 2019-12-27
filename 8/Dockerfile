FROM node:8-slim

RUN npm install -g esdoc esdoc-node esdoc-standard-plugin \
                   esdoc-typescript-plugin eslint eslint-plugin-node \
                   esdoc-lint-plugin esdoc-coverage-plugin esdoc-accessor-plugin \
                   esdoc-type-inference-plugin esdoc-external-ecmascript-plugin \
                   esdoc-brand-plugin esdoc-undocumented-identifier-plugin \
                   esdoc-unexported-identifier-plugin esdoc-integrate-manual-plugin \
                   esdoc-integrate-test-plugin esdoc-publish-html-plugin

RUN npm install -g esdoc-publish-markdown-plugin

WORKDIR /root/app
CMD ["esdoc"]
