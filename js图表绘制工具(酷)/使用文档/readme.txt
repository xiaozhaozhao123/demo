插件描述：Jquery滑动日期输入控件，手机使用效果最佳
主要是PluginDatetime.js文件的调用，封装好了一些mobiscroll的属性。用户在使用的时候非常翻遍，插件内部的具体属性也有相对应的参数：参数如下

具体参数定义如下
{
    preset: 'date', //日期类型--data,时间类型--time,日期时间混合类型--datetime
    theme: 'ios', //皮肤其他参数【android-ics light】【android-ics】【ios】【jqm】【sense-ui】【sense-ui】【sense-ui】
    //【wp light】【wp】
    mode: "scroller",//操作方式【scroller】【clickpick】【mixed】
    display: 'bubble', //显示方【modal】【inline】【bubble】【top】【bottom】
    dateFormat: 'yyyy-mm-dd', // 日期格式
    setText: '确定', //确认按钮名称
    cancelText: '清空',//取消按钮名籍我
    dateOrder: 'yymmdd', //面板中日期排列格
    dayText: '日', 
    monthText: '月',
    yearText: '年', //面板中年月日文字
    startYear: (new Date()).getFullYear(), //开始年份
    endYear: (new Date()).getFullYear() + 9, //结束年份
    showNow: true,
    nowText: "明天",  //
    showOnFocus: false,
    height: 45,
    width: 90,
    rows: 3
}