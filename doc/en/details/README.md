# § Details

It would be better for you to understand the structure of this Datatable before the details.

The source tree [`lib/`](https://github.com/OneWayTech/vue2-datatable/tree/master/lib) is shown as below:

```
lib/
 ├─ HeaderSettings/
 │   ├─ ColumnGroup.vue
 │   └─ index.vue
 ├── MainTable
 │   ├─ _SCROLLBAR_WIDTH.js
 │   ├─ _syncScroll.js
 │   ├─ HeadSort.vue
 │   ├─ index.vue
 │   ├─ MultiSelect.vue
 │   ├─ TableBody.vue
 │   ├─ TableFooter.vue
 │   ├─ TableFrame.vue
 │   └─ TableHeader.vue
 ├─ index.vue
 ├─ LimitSelect.vue
 ├─ Pagination.vue
 └─ props.mixin.js
```

Here is the illustration for the tree above, which is captured from the advanced example (source: [`examples/src/Advanced/index.vue`](https://github.com/OneWayTech/vue2-datatable/blob/master/examples/src/Advanced/index.vue), demo: [examples#advanced](https://OneWayTech.github.io/vue2-datatable/examples/dist#advanced)):

<a href="_images/structure.png" target="_blank" title="Click to enlarge">
  <img src="_images/structure.png" alt="Structure">
</a>