# dokcer-esdoc-converter

## use base container

- [node](https://hub.docker.com/_/node)
    ![](https://img.shields.io/badge/node_slim_-8.15-21cb00.svg)

## use package

- [esdoc](https://www.npmjs.com/package/esdoc)
- [esdoc-accessor-plugin](https://www.npmjs.com/package/esdoc-accessor-plugin)
- [esdoc-brand-plugin](https://www.npmjs.com/package/esdoc-brand-plugin)
- [esdoc-coverage-plugin ](https://www.npmjs.com/package/esdoc-coverage-plugin )
- [esdoc-external-ecmascript-plugin](https://www.npmjs.com/package/esdoc-external-ecmascript-plugin)
- [esdoc-integrate-manual-plugin](https://www.npmjs.com/package/esdoc-integrate-manual-plugin)
- [esdoc-integrate-test-plugin](https://www.npmjs.com/package/esdoc-integrate-test-plugin)
- [esdoc-lint-plugin](https://www.npmjs.com/package/esdoc-lint-plugin)
- [esdoc-node](https://www.npmjs.com/package/esdoc-node)
- [esdoc-publish-html-plugin](https://www.npmjs.com/package/esdoc-publish-html-plugin)
- [esdoc-publish-markdown-plugin](https://www.npmjs.com/package/esdoc-publish-markdown-plugin)
- [esdoc-standard-plugin](https://www.npmjs.com/package/esdoc-standard-plugin)
- [esdoc-type-inference-plugin](https://www.npmjs.com/package/esdoc-type-inference-plugin)
- [esdoc-typescript-plugin](https://www.npmjs.com/package/esdoc-typescript-plugin)
- [esdoc-undocumented-identifier-plugin](https://www.npmjs.com/package/esdoc-undocumented-identifier-plugin)
- [esdoc-unexported-identifier-plugin](https://www.npmjs.com/package/esdoc-unexported-identifier-plugin)
- [eslint](https://www.npmjs.com/package/eslint)
- [eslint-plugin-node](https://www.npmjs.com/package/eslint-plugin-node)

## Usage

```bash
# build
docker build -t esdoc-converter:8.15 ./8

# run container
docker run -v $PWD:/root/app --rm esdoc-converter:8.15
```
