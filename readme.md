# 注意  不修改原作者的任何功能，仅增加了指定按钮位置的功能, 配置参数，demo及文档请参考原作者git: @[Vue-Float-Action-Button]https://github.com/a62527776a/vue-floating-action-button)

# 指定按钮位置(请先阅读原作者git), 传入right参数，格式与CSS格式一致，如right="40px"：
``` Javascript
<vue-fab
    right="40px"
    :mainBtnColor="mainBtnColor"
    @clickMainBtn="clickMainBtn">
    <fab-item 
      v-for="(item, idx) in menu"
      :idx="idx"
      :title="item.title"
      :color="item.color"
      :icon="item.icon"
      @clickItem="clickItem" />
```

# Vue Floating Action Button

## LICENSE
MIT
