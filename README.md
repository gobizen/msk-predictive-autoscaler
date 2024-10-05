# msk-predictive-autoscaler

MSK autoscaler that leverages predictive analytics and machine learning models to optimize Kafka cluster scaling. This tool analyzes historical Kafka metrics and trends to anticipate workload demands, automatically adjusting disk size, partitions, and broker instances to prevent bottlenecks, optimize resource usage, and improve system reliability.

## Description:
A robust and intelligent MSK (Managed Streaming for Apache Kafka) autoscaler that leverages predictive analytics and machine learning models to optimize Kafka cluster scaling. This tool analyzes historical Kafka metrics and trends to anticipate workload demands, automatically adjusting disk size, partitions, and broker instances to prevent bottlenecks, optimize resource usage, and improve system reliability.

## Key features:

1. **Predictive Scaling**: Forecast future workload demands using machine learning models.
2. **Disk Size Optimization**: Predictive auto-scaling for disk size, exceeding the standard 10% limit when necessary.
3. **Customizable Scaling Policies**: Fine-tuned scaling policies based on Kafka topic, partition traffic, and storage usage.
4. **Real-time Monitoring**: Real-time Kafka cluster metrics analysis using cloud-native observability tools (e.g., Prometheus, Grafana).
5. **Efficient Resource Allocation**: Helps reduce costs by scaling clusters up or down based on actual requirements.
6. **Seamless AWS Integration**: Designed to work natively with AWS MSK, leveraging CloudWatch for metric collection.
