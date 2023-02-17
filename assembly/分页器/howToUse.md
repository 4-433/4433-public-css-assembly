使用

```vue
        <pagination v-show="total>0" :total="total" :page.sync="param.page" :limit.sync="param.limit" @pagination="getList" />

```

data

```vue
 total: 10,
      param: {
        page: 1,
        limit: 10
      },
```

method

获取数据时，total（总条数）从接口获取，page（当前页）、limit（一页几条）是data里固定的