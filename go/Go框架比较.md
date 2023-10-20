
# pitaya
    引入了etcd,NATS
        RPC可以用gRPC或者NATS
    实现了服务器之间rpc,但是route不是很灵活
    在nano的基础上做了一些封装
    看着挺齐全，感觉有点臃肿
    (etcd做服务发现)
    代码结构看起来最好

# leaf
    比较简单

# nano
    以service为单位
    service可以分布到不同服务器    
    session可以绑定服务器到某个地址  
    RPC用gRPC 
    (可以定义service的处理在那个线程执行)

# origin
    提供了Node,Service,Module三层抽象
    能比较灵活的在节点服务器配置不同的Service
    使用者不用关心service分布
    自定义的RPC
    代码质量看起来不如nano

# protoactor
    actor模式的实现，代码比较清晰



# todo
    https://github.com/bobohume/gonet


