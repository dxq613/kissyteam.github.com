.. currentmodule:: component

Component.UIBase.Close
===============================

|  关闭。组件扩充类，仅用于 KISSY 内部组件继承，目前不建议外部使用，欢迎 review



Class
---------------------------------

    * :class:`UIBase.Close`
  

Configs
-----------------------------------------------

    * :data:`~UIBase.Close.config.closable`
    * :data:`~UIBase.Close.config.closeAction`
    

    

Class Detail
--------------------------

.. class:: UIBase.Close

    | **UIBase.Close** (config)
    
    :param Object config: 配置项，详细见下方 **Configs Detail** .
    
    
Configs Detail
-----------------------------------------------
    
.. data:: UIBase.Close.config.closable

    {Boolean} - 对话框右上角是否包括关闭按钮
    

.. data:: UIBase.Close.config.closeAction

    {String} - 点击关闭按钮的动作。默认 "hide" 隐藏，也可设置 "destroy" 销毁该组件.
    
Attributes Detail
-----------------------------------------------

.. attribute:: UIBase.Close.prototype.closable

    {Boolean} - 组件是否有关闭按钮.