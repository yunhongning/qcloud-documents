## 1. 实例相关接口
| 接口功能 | Action ID | 功能描述
|---------|---------|---------|
| 查看实例列表 | [DescribeInstances](http://www.qcloud.com/doc/api/229/%E6%9F%A5%E7%9C%8B%E5%AE%9E%E4%BE%8B%E5%88%97%E8%A1%A8) |  用于获取一个或多个实例的详细信息。
| 创建实例（包年包月） | [RunInstances](http://www.qcloud.com/doc/api/229/%E5%88%9B%E5%BB%BA%E5%AE%9E%E4%BE%8B%EF%BC%88%E5%8C%85%E5%B9%B4%E5%8C%85%E6%9C%88%EF%BC%89) | 用于创建一台或多台指定配置的实例(包年包月)。
| 创建实例（按量计费） | [RunInstancesHour](http://www.qcloud.com/doc/api/229/%E5%88%9B%E5%BB%BA%E5%AE%9E%E4%BE%8B%EF%BC%88%E6%8C%89%E9%87%8F%E8%AE%A1%E8%B4%B9%EF%BC%89) | 用于创建一个或多个指定配置的实例(按量计费)。
| 启动实例 | [StartInstances](http://www.qcloud.com/doc/api/229/%E5%90%AF%E5%8A%A8%E5%AE%9E%E4%BE%8B) | 用于启动一个或者多个实例。
| 关闭实例 | [StopInstances](http://www.qcloud.com/doc/api/229/%E5%85%B3%E9%97%AD%E5%AE%9E%E4%BE%8B) | 用于关闭一个或者多个实例。
| 重启实例 | [RestartInstances](http://www.qcloud.com/doc/api/229/%E9%87%8D%E5%90%AF%E5%AE%9E%E4%BE%8B) | 用于重启一个或者多个实例。
| 重装系统 | [ResetInstances](http://www.qcloud.com/doc/api/229/%E9%87%8D%E8%A3%85%E7%B3%BB%E7%BB%9F) | 用于将重装指定实例上的操作系统。
| 修改实例属性 | [ModifyInstanceAttributes](http://www.qcloud.com/doc/api/229/%E4%BF%AE%E6%94%B9%E5%AE%9E%E4%BE%8B%E5%90%8D%E7%A7%B0) |  用于修改实例的属性（如实例名称等）。
| 重置密码 | [ResetInstancePassword](http://www.qcloud.com/doc/api/229/%E9%87%8D%E7%BD%AE%E5%AF%86%E7%A0%81) | 用于将实例操作系统的密码重置为用户指定的值
| 查询实例价格（包年包月） | [InquiryInstancePrice](http://www.qcloud.com/doc/api/229/%E6%9F%A5%E8%AF%A2%E5%AE%9E%E4%BE%8B%E4%BB%B7%E6%A0%BC%EF%BC%88%E5%8C%85%E5%B9%B4%E5%8C%85%E6%9C%88%EF%BC%89) | 用于获取实例价格(包年包月)。
| 查询实例价格（按量计费） | [InquiryInstancePriceHour](http://www.qcloud.com/doc/api/229/%E6%9F%A5%E8%AF%A2%E5%AE%9E%E4%BE%8B%E4%BB%B7%E6%A0%BC%EF%BC%88%E6%8C%89%E9%87%8F%E8%AE%A1%E8%B4%B9%EF%BC%89) | 用于获取实例价格(按量计费)。
| 调整配置（包年包月） | [ResizeInstance](http://www.qcloud.com/doc/api/229/%E8%B0%83%E6%95%B4%E5%AE%9E%E4%BE%8B%E9%85%8D%E7%BD%AE%EF%BC%88%E5%8C%85%E5%B9%B4%E5%8C%85%E6%9C%88%EF%BC%89) | 用于支持升级或降级指定实例的配置，包括CPU、内存、数据盘。
| 调整配置（按量计费） | [ResizeInstanceHour](http://www.qcloud.com/doc/api/229/%E8%B0%83%E6%95%B4%E5%AE%9E%E4%BE%8B%E9%85%8D%E7%BD%AE%EF%BC%88%E6%8C%89%E9%87%8F%E8%AE%A1%E8%B4%B9%EF%BC%89) |  用于支持升级或降级指定实例的配置，包括CPU、内存、数据盘。
| 续费实例（包年包月） | [RenewInstance](http://www.qcloud.com/doc/api/229/%E7%BB%AD%E8%B4%B9%E5%AE%9E%E4%BE%8B%EF%BC%88%E5%8C%85%E5%B9%B4%E5%8C%85%E6%9C%88%EF%BC%89) | 用于包年包月实例续费。
| 退还实例（按量计费） | [ReturnInstance](http://www.qcloud.com/doc/api/229/%E9%80%80%E8%BF%98%E5%AE%9E%E4%BE%8B%EF%BC%88%E6%8C%89%E9%87%8F%E8%AE%A1%E8%B4%B9%EF%BC%89) | 用于主动退还实例。
| 修改实例所属项目 | [ModifyInstanceProject](http://www.qcloud.com/doc/api/229/%E4%BF%AE%E6%94%B9%E5%AE%9E%E4%BE%8B%E6%89%80%E5%B1%9E%E9%A1%B9%E7%9B%AE) | 用于修改实例所属项目。
| 设置实例自动续费 | [SetAutoRenew](http://www.qcloud.com/doc/api/229/%E8%AE%BE%E7%BD%AE%E4%BA%91%E6%9C%8D%E5%8A%A1%E5%99%A8%E8%87%AA%E5%8A%A8%E7%BB%AD%E8%B4%B9) | 用于设置实例的续费策略。

## 2. 镜像相关接口
| 接口功能 | Action ID | 功能描述
|---------|---------|---------|
| 查看可用的镜像列表 | [DescribeImages](http://www.qcloud.com/doc/api/229/%E6%9F%A5%E8%AF%A2%E5%8F%AF%E7%94%A8%E7%9A%84%E9%95%9C%E5%83%8F%E5%88%97%E8%A1%A8) | 用于获取本账户能够使用的镜像，用户可以使用这些镜像来创建CVM实例。
| 创建自定义镜像 | [CreateImage](http://www.qcloud.com/doc/api/229/%E5%88%9B%E5%BB%BA%E8%87%AA%E5%AE%9A%E4%B9%89%E9%95%9C%E5%83%8F) | 用于将实例系统盘的当前状态制作成全新的镜像，使用此镜像可以快速创建实例。
| 删除镜像 | [DeleteImages](http://www.qcloud.com/doc/api/229/%E5%88%A0%E9%99%A4%E9%95%9C%E5%83%8F) | 用于删除一个或者多个镜像。
| 修改镜像属性 | [ModifyImageAttributes](http://www.qcloud.com/doc/api/229/%E4%BF%AE%E6%94%B9%E9%95%9C%E5%83%8F%E5%B1%9E%E6%80%A7) | 用于修改镜像的名称和描述等信息。
| 复制镜像 | [SyncCvmImage](http://www.qcloud.com/doc/api/229/%E5%A4%8D%E5%88%B6%E9%95%9C%E5%83%8F) | 用于将自定义镜像复制（同步）到其它地区。
| 共享镜像 | [ShareImage](http://www.qcloud.com/doc/api/229/%E5%85%B1%E4%BA%AB%E9%95%9C%E5%83%8F) | 用于共享镜像。
| 取消共享镜像 | [CancelShareImage](http://www.qcloud.com/doc/api/229/%E5%8F%96%E6%B6%88%E5%85%B1%E4%BA%AB%E9%95%9C%E5%83%8F) | 用于取消共享镜像。
| 查询镜像共享的账号列表 | [GetImageShareUinInfo](http://www.qcloud.com/doc/api/229/%E6%9F%A5%E8%AF%A2%E9%95%9C%E5%83%8F%E5%85%B1%E4%BA%AB%E7%9A%84QQ%E8%B4%A6%E5%8F%B7%E4%BF%A1%E6%81%AF) | 用于查询本账户的镜像共享情况，包括共享的账户列表。

## 3. 网络相关接口
| 接口功能 | Action ID | 功能描述
|---------|---------|---------|
| 调整包年包月实例带宽 | [UpdateInstanceBandwidth](http://www.qcloud.com/doc/api/229/%E8%B0%83%E6%95%B4%E5%8C%85%E5%B9%B4%E5%8C%85%E6%9C%88%E6%8C%89%E5%B8%A6%E5%AE%BD%E8%AE%A1%E8%B4%B9%E5%AE%9E%E4%BE%8B%E5%B8%A6%E5%AE%BD) |  用于调整包年包月实例的公网带宽。
| 调整按量计费实例带宽 | [UpdateInstanceBandwidthHour](http://www.qcloud.com/doc/api/229/%E8%B0%83%E6%95%B4%E6%8C%89%E9%87%8F%E8%AE%A1%E8%B4%B9%E5%AE%9E%E4%BE%8B%E5%B8%A6%E5%AE%BD) | 用于调整按量计费实例的公网带宽。

## 4. 安全组相关接口
| 接口功能 | Action ID | 功能描述
|---------|---------|---------|
| 查询安全组列表 | [DescribeSecurityGroups](http://www.qcloud.com/doc/api/229/%E6%9F%A5%E8%AF%A2%E5%AE%89%E5%85%A8%E7%BB%84%E5%88%97%E8%A1%A8) | 用于查询已经存在的安全组的规则。
| 创建安全组 | [CreateSecurityGroup](http://www.qcloud.com/doc/api/229/%E5%88%9B%E5%BB%BA%E5%AE%89%E5%85%A8%E7%BB%84) | 用于创建新的安全组。
| 删除安全组 | [DeleteSecurityGroup](http://www.qcloud.com/doc/api/229/%E5%88%A0%E9%99%A4%E5%AE%89%E5%85%A8%E7%BB%84) | 用于删除新的安全组。
| 修改安全组名称 | [ModifySecurityGroupAttributes](http://www.qcloud.com/doc/api/229/%E4%BF%AE%E6%94%B9%E5%AE%89%E5%85%A8%E7%BB%84%E5%90%8D%E7%A7%B0) | 用于修改已经存在的安全组的属性信息，包括名称和描述。
| 查询安全组规则 | [DescribeSecurityGroupPolicy](http://www.qcloud.com/doc/api/229/%E6%9F%A5%E8%AF%A2%E5%AE%89%E5%85%A8%E7%BB%84%E8%A7%84%E5%88%99) | 用于查询已经存在的安全组的规则。
| 修改安全组规则 | [ModifySecurityGroupPolicy](http://www.qcloud.com/doc/api/229/%E4%BF%AE%E6%94%B9%E5%AE%89%E5%85%A8%E7%BB%84%E8%A7%84%E5%88%99) | 用于修改已经存在的安全组的规则。
| 查询安全组关联的实例列表 | [DescribeInstancesOfSecurityGroup](http://www.qcloud.com/doc/api/229/%E6%9F%A5%E8%AF%A2%E5%AE%89%E5%85%A8%E7%BB%84%E5%85%B3%E8%81%94%E7%9A%84%E4%BA%91%E4%B8%BB%E6%9C%BA%E5%88%97%E8%A1%A8) | 用于查询已关联指定的安全组的云服务器。
| 修改实例关联的安全组 | [ModifySecurityGroupsOfInstance](http://www.qcloud.com/doc/api/229/%E4%BF%AE%E6%94%B9%E4%BA%91%E4%B8%BB%E6%9C%BA%E5%85%B3%E8%81%94%E7%9A%84%E5%AE%89%E5%85%A8%E7%BB%84) | 用于修改指定云服务器关联的安全组。
| 查询关联的安全组列表 | [DescribeAssociateSecurityGroups](http://www.qcloud.com/doc/api/229/%E6%9F%A5%E8%AF%A2%E4%B8%8E%E5%AE%89%E5%85%A8%E7%BB%84%E5%85%B3%E8%81%94%E7%9A%84%E5%AE%89%E5%85%A8%E7%BB%84%E5%88%97%E8%A1%A8) | 查询有哪些安全组的出站或入站规则中包含了输入的安全组ID。

## 5. 弹性IP相关接口
| 接口功能 | Action ID | 功能描述
|---------|---------|---------|
| 查询弹性公网IP列表 | [DescribeEip](http://www.qcloud.com/doc/api/229/%E6%9F%A5%E8%AF%A2%E5%BC%B9%E6%80%A7%E5%85%AC%E7%BD%91IP%E5%88%97%E8%A1%A8) | 查询弹性公网IP。
| 查询弹性公网IP配额 | [DescribeEipQuota](http://www.qcloud.com/doc/api/229/%E6%9F%A5%E8%AF%A2%E5%BC%B9%E6%80%A7%E5%85%AC%E7%BD%91IP%E9%85%8D%E9%A2%9D) | 查询指定地域弹性公网IP配额。
| 修改弹性公网IP名称 | [ModifyEipAttributes](http://www.qcloud.com/doc/api/229/%E4%BF%AE%E6%94%B9%E5%BC%B9%E6%80%A7%E5%85%AC%E7%BD%91IP%E5%90%8D%E7%A7%B0) | 修改弹性公网IP名称。
| 创建弹性公网IP | [CreateEip](http://www.qcloud.com/doc/api/229/%E5%88%9B%E5%BB%BA%E5%BC%B9%E6%80%A7%E5%85%AC%E7%BD%91IP) | 创建弹性公网IP（EIP），弹性公网IP是专为动态云计算设计的静态IP地址。借助弹性公网IP，您可以快速将EIP重新映射到您的另一个实例上，从而屏蔽实例故障。
| 释放弹性公网IP | [DeleteEip](http://www.qcloud.com/doc/api/229/%E9%87%8A%E6%94%BE%E5%BC%B9%E6%80%A7%E5%85%AC%E7%BD%91IP) | 释放弹性公网IP。
| 绑定弹性公网IP | [EipBindInstance](http://www.qcloud.com/doc/api/229/%E7%BB%91%E5%AE%9A%E5%BC%B9%E6%80%A7%E5%85%AC%E7%BD%91IP) | 弹性公网IP与服务器绑定。
| 解绑弹性公网IP | [EipUnBindInstance](http://www.qcloud.com/doc/api/229/%E8%A7%A3%E7%BB%91%E5%BC%B9%E6%80%A7%E5%85%AC%E7%BD%91IP) | 弹性公网IP与服务器解绑。
| 普通公网IP转弹性公网IP | [TransformWanIpToEip](http://www.qcloud.com/doc/api/229/%E6%99%AE%E9%80%9A%E5%85%AC%E7%BD%91IP%E8%BD%AC%E5%BC%B9%E6%80%A7%E5%85%AC%E7%BD%91IP) | 普通公网IP转弹性公网IP，将服务器当前绑定的普通公网IP转换成弹性公网IP，转换后随着服务器的释放，该弹性公网IP将会保留。

## 6. 密钥相关接口
| 接口功能 | Action ID | 功能描述
|---------|---------|---------|
| 查询密钥 | [DescribeKeyPairs](http://www.qcloud.com/doc/api/229/查询密钥) | 用于查询密钥。
| 创建密钥 | [CreateKeyPair](http://www.qcloud.com/doc/api/229/创建密钥) | 用于创建密钥。
| 修改密钥 | [ModifyKeyPair](http://www.qcloud.com/doc/api/229/修改密钥) | 用于修改密钥名称。
| 删除密钥 | [DeleteKeyPair](http://www.qcloud.com/doc/api/229/删除密钥) | 用于删除密钥。
| 导入密钥 | [ImportKeyPair](http://www.qcloud.com/doc/api/229/导入密钥) | 用于导入密钥。
| 绑定密钥 | [BindInstanceKey](http://www.qcloud.com/doc/api/229/绑定密钥) | 用于将密钥绑定到CVM实例上。
| 解绑密钥 | [unBindInstanceKey](http://www.qcloud.com/doc/api/229/解绑密钥) | 用于解除CVM的密钥绑定关系。


