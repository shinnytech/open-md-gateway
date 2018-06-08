Introduction
=================================================
Open Md Gateway 是一套主要用于期货的行情服务器. 它可以接受客户端以 `DIFF协议 (Differential Information Flow for Finance) <https://github.com/shinnytech/diff>`_  接入, 向客户端提供实时行情及历史行情数据.

本项目的服务接入URL为::

  ws://openmd.shinnytech.com


可以通过 `DIFF协议 <https://github.com/shinnytech/diff>`_ 接入本服务的终端产品包括:

* `Shinny Future Android <https://github.com/shinnytech/shinny-futures-android>`_ : 一个开源的 android 平台期货行情交易终端
* `天勤衍生品研究终端 <http://www.tq18.cn>`_ : 一套免费的PC行情交易终端, 支持以 DIFF 协议进行扩展开发.
* `Tianqin Python Sdk <https://github.com/tianqin18/tqsdk-python>`_ : 一套开源的 python 框架, 
