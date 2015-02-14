# pagelist
分页组件

这是基于JS的分页组件,通过构造函数PageList并且传入参数构造属性配置.
  @pageContentID 渲染分页的DIV元素
  @curPage 当前开始页
  @totalCount 总数量
  @pageRows 每页显示数量
  @callback 显示数据的回调函数

使用方法:
var pagetest = new PageList("pageDIV",{
        curPage:1,
        totalCount:100,
        pageRows:9,
        callback:callbackFuc   //用户自定义的回调函数
});

pagetest.init();

