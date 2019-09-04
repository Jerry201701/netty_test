# netty-study

```
netty-study  
│ |- 父项目  
├────DelimiterBasedFrameDecoder[博客](http://huan1993.iteye.com/blog/2399359)    
│       |- 使用自定义的分隔符进行消息的编解码    
├────handlerlifecycle     
│       |- 测试handler类中的各个方法的生命周期      
├────protostuff[博客](http://huan1993.iteye.com/blog/2405510)  
│       |- 使用 protostuff 进行序列化消息的传递    
├────tasks（重要） 
│       |- 使用 protostuff 进行序列化消息的传递    
│       |- 实现不同的消息使用不同的类进行处理    
├────time  
│       |- 一个简单的发送时间      
├────websocket[博客](http://huan1993.iteye.com/blog/2433552)  
│       |- 使用webSocket进行消息的发送和接收    
│       |- 实现文本消息和图片消息的传递    
│       |- 实现自定义消息协议  
│       |- 当是二进制的消息时，消息的前4个字节表示消息的类型，此例子中如果是10表示的是图片消息，没有进行区分具体是png还是jpeg类型    
│       |- js 中操作二进制的写法
│       |- 客户端分批次向服务器提交数据，防止websocket一次提交数据过大，丢失数据
├────protobuf[博客](https://huan1993.iteye.com/blog/2437622)    
│       |- 使用protobuf实现消息的序列化    
│       |- 处理多个protobuf协议的消息    
```

