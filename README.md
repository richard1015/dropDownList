# dropDownList

# 下拉列表框多选插件

![首页](https://images2017.cnblogs.com/blog/600701/201802/600701-20180204140035201-968483939.png "屏幕截图.png")


/**
 * dorpDownList.js 1.0
 * @version 1.0
 * @author zhuzhida
 * @url https://github.com/richard1015/dropDownList
 *
 * @调用方法
 * $(selector).dropdownlist(option);
 * option里的callback是选择国家后调用
 *
 * -- example --
 * $(selector).dropdownlist({
 *     defaultText: "请选择国家", //默认提示语
 *     selectIds: "",//默认选中国家
 *     callback: function(api) {
 *         console.log('选择下拉选项调用该回调');
 *     }
 * });
 */

