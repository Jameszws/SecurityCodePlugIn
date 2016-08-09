# SecurityCodePlugIn

该插件是JS安全码插件，可用于安全码、密码框等等场景。


缺点说明：
由于IOS对text的focus事件响应不同于PC和Android，所以该插件在IOS中有兼容性问题（代码没问题，只是操作不便）

缺点改善：
仿照支付宝，通过虚拟键实现，已经实现在JsPlugIn_SecurityCode仓储中，单独的虚拟键代码在JsPlugIn_VirtualKey仓储中
