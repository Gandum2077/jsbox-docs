# 基础接口

这一部分内容我们主要介绍 JSBox 里面最最基本的接口，按理说这些部分是构成一个扩展程序十分必要的部分。

主要会包括 `app/设备/缓存/网络` 等琐事。

# $device

和设备本身相关的接口会放在这里。

# $app

和应用本身相关的接口被组织在这里。

# $system

这里会放置和系统有关的各种接口。

# $http

通过这个来实现各种网络请求，比如 `GET`/`POST`。

# $cache

当你需要缓存扩展产生的数据的时候，用这个工具。

# $thread

当你需要确保 Native 代码被执行在主线程/子线程的时候，这是一个很好的方式。