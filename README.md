# oj-fronted

 vue-cli脚手架

```shell
node -v 
# 18.16.0
```

```shell
npm -v  
# 9.5.1
```

```shell
npm install -g @vue/cli
```

```shell
vue create oj-fronted
```

```lang
npm install --save-dev @arco-design/web-vue
```

## Project setup

```
npm install
```

### Compiles and hot-reloads for development

```
npm run serve
```

### Compiles and minifies for production

```
npm run build
```

### Lints and fixes files

```
npm run lint
```

选项

Manually select features

babel  typescript router vuex linter/formatter (空格选择)

3.x

No Yes Yes Eslint + Prettier   Lint on save

In dedicated config file No

```shell
npm install openapi-typescript-codegen --save-dev
openapi --input http://localhost:8080/api/v2/api-docs --output ./generated --client axios
```
