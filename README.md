# @sugaz/echarts

## Echarts版本: 5.3.3

**[Echarts中文官网](https://echarts.apache.org/zh/index.html)**

[![Latest npm release](https://img.shields.io/npm/v/echarts?color=91cc75)](https://www.npmjs.com/package/echarts)
## Docs

+ [Get Started](https://echarts.apache.org/handbook)
+ [API](https://echarts.apache.org/api.html)
+ [Option Manual](https://echarts.apache.org/option.html)
+ [Examples](https://echarts.apache.org/examples)


## Get Help

+ [GitHub Issues](https://github.com/apache/echarts/issues) for bug report and feature requests
+ Email [dev@echarts.apache.org](mailto:dev@echarts.apache.org) for general questions
+ Subscribe to the [mailing list](https://echarts.apache.org/maillist.html) to get updated with the project

## Build

Build echarts source code:

Execute the instructions in the root directory of the echarts:
([Node.js](https://nodejs.org) is required)

```shell
# Install the dependencies from NPM:
npm install

# Rebuild source code immediately in watch mode when changing the source code.
npm run dev

# Check correctness of TypeScript code.
npm run checktype

# If intending to build and get all types of the "production" files:
npm run release
```

Then the "production" files are generated in the `dist` directory.

## 更新记录

## 1.0.0:
  - 添加了legend旋转功能，legend.rotate和legend.scrollRotate
