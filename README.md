# 原生JS实现本地图片预览

1、 利用URL.createObjectURL实现预览

2、 利用new FileReader().readAsDataURL实现预览

**注意：以上两种图片预览方法兼容到IE10+；IE9不支持客户端预览，需要先上传到服务端，等待返回图片服务地址，再实现图片预览。**