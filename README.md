# NestJs 基础环境

包含了 eslint、prettier、SWC

## 调试的配置文件已添加，如果要使用需删除 nest-cli.json 的配置

```json
{
  "$schema": "https://json.schemastore.org/nest-cli",
  "collection": "@nestjs/schematics",
  "sourceRoot": "src",
  "compilerOptions": {
    "deleteOutDir": true,
    - "builder": "swc",
    - "typeCheck": true
  }
}
```
