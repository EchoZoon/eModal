# eModal
>> 自己封装的弹窗组件

#使用方法
>> 在页面中引入css和js：

    <link rel="stylesheet" href="js/lib/eModal/css/modal.css"/>
    <script src="js/lib/eModal/eModal.js"></script>
    
    
>> 使用方法与alert等一样：

    eModal.alert("kkk")
    eModal.confirm("kkk")
    eModal.confirm("确定要点击我吗？", function(){
            }, function(){}, {shade: true});
            
    eModal.confirm("确定要点击我吗？", function(){
            }, function(){}, {shade: false});
            
    eModal.alert("3333333",{shade: false});
    
    
