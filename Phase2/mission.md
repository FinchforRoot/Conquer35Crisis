#### **架构期（6-12个月）目标：掌握云原生核心能力**

1. **Kubernetes实战**：
   - 概念：Pod/Deployment/Service/Ingress
   - 实操：Minikube部署SpringBoot集群
   - 进阶：HPA自动扩缩容、RBAC权限控制
2. **分布式系统**：
   - 事务：Seata AT模式实践（先于Saga模式）
   - 缓存：Redis分布式锁实现库存扣减
   - 消息：RocketMQ事务消息实战
3. **稳定性建设**：
   - 使用ChaosBlade模拟CPU满载
   - 搭建Prometheus+Grafana监控体系
   - SkyWalking追踪跨服务调用链

**实践项目选择**：

- 用K8s部署微服务电商系统（商品/订单/支付服务分离）
- 实现分布式场景下的超卖解决方案

#### **Architecture Phase (6-12 Months) Goal: Mastering Core Cloud-Native Capabilities**

1. **Kubernetes in Practice**:

   - Concepts

     :

     - Pod, Deployment, Service, Ingress

   - Hands-on

     :

     - Deploy a Spring Boot cluster using Minikube

   - Advanced Topics

     :

     - Horizontal Pod Autoscaling (HPA)
     - Role-Based Access Control (RBAC)

2. **Distributed Systems**:

   - Transactions

     :

     - Implement Seata AT mode (preceding Saga mode)

   - Caching

     :

     - Implement distributed locks with Redis for inventory deduction

   - Messaging

     :

     - Use RocketMQ for transactional messaging

3. **Stability Construction**:

   - Simulate CPU overload using ChaosBlade
   - Set up a monitoring system with Prometheus and Grafana
   - Use SkyWalking to trace cross-service call chains

**Project Selection for Practical Application**:

- Deploy a microservices-based e-commerce system on K8s (separate services for product, order, and payment)
- Implement an overselling solution in a distributed environment