
**Prometheus Alert [Kubernetes aggregated API server is down]**
```yaml
labels:
  alertname: KubeAggregatedAPIDown
  severity: critical
annotations:
  description: The Kubernetes aggregated API server has been down for more than 5 minutes.
  summary: Kubernetes aggregated API server is down
state: firing
activeAt: '[REDACTED_TIMESTAMP_ISO8601]'
value: '1e+00'
selected: true
```

**Prometheus metric [go_gc_duration_seconds{quantile="0"}]**
```chart
| __name__ | app | cluster_id | component | instance | job | kubernetes_name | kubernetes_namespace | kubernetes_node | quantile | timestamp | value |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| go_gc_duration_seconds | prometheus-tool | [REDACTED_AZURE_API_KEY]d8fa152 | node-exporter | [REDACTED_IP]:9100 | kubernetes-service-endpoints | prometheus-tool-node-exporter | gopaddle-servers | ip-10-0-2-109 | 0 | 1711464784.499 | 0.000020217 |
| go_gc_duration_seconds | localhost:9090 | prometheus | 0 | 1711464784.499 | 0.000041739 |```

**Prometheus metric [go_memstats_buck_hash_sys_bytes]**
```chart
| __name__ | app | cluster_id | component | instance | job | kubernetes_name | kubernetes_namespace | kubernetes_node | timestamp | value |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| go_memstats_buck_hash_sys_bytes | prometheus-tool | [REDACTED_AZURE_API_KEY]d8fa152 | node-exporter | [REDACTED_IP]:9100 | kubernetes-service-endpoints | prometheus-tool-node-exporter | gopaddle-servers | ip-10-0-2-109 | 1711464784.969 | 1496067 |
| go_memstats_buck_hash_sys_bytes | localhost:9090 | prometheus | 1711464784.969 | 1589262 |```

**Prometheus metric [go_gc_duration_seconds{quantile="0.5"}]**
```chart
| __name__ | app | cluster_id | component | instance | job | kubernetes_name | kubernetes_namespace | kubernetes_node | quantile | timestamp | value |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| go_gc_duration_seconds | prometheus-tool | [REDACTED_AZURE_API_KEY]d8fa152 | node-exporter | [REDACTED_IP]:9100 | kubernetes-service-endpoints | prometheus-tool-node-exporter | gopaddle-servers | ip-10-0-2-109 | 0.5 | 1711464784.705 | 0.000040722 |
| go_gc_duration_seconds | localhost:9090 | prometheus | 0.5 | 1711464784.705 | 0.000083159 |```

**Prometheus metric [go_gc_duration_seconds{quantile="1"}]**
```chart
| __name__ | app | cluster_id | component | instance | job | kubernetes_name | kubernetes_namespace | kubernetes_node | quantile | timestamp | value |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| go_gc_duration_seconds | prometheus-tool | [REDACTED_AZURE_API_KEY]d8fa152 | node-exporter | [REDACTED_IP]:9100 | kubernetes-service-endpoints | prometheus-tool-node-exporter | gopaddle-servers | ip-10-0-2-109 | 1 | 1711464784.712 | 0.000069858 |
| go_gc_duration_seconds | localhost:9090 | prometheus | 1 | 1711464784.712 | 0.015931224 |```

**Prometheus metric [go_gc_duration_seconds_sum]**
```chart
| __name__ | app | cluster_id | component | instance | job | kubernetes_name | kubernetes_namespace | kubernetes_node | timestamp | value |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| go_gc_duration_seconds_sum | prometheus-tool | [REDACTED_AZURE_API_KEY]d8fa152 | node-exporter | [REDACTED_IP]:9100 | kubernetes-service-endpoints | prometheus-tool-node-exporter | gopaddle-servers | ip-10-0-2-109 | 1711464784.74 | 0.004585237 |
| go_gc_duration_seconds_sum | localhost:9090 | prometheus | 1711464784.74 | 0.020067791 |```

**Prometheus metric [go_gc_duration_seconds_count]**
```chart
| __name__ | app | cluster_id | component | instance | job | kubernetes_name | kubernetes_namespace | kubernetes_node | timestamp | value |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| go_gc_duration_seconds_count | prometheus-tool | [REDACTED_AZURE_API_KEY]d8fa152 | node-exporter | [REDACTED_IP]:9100 | kubernetes-service-endpoints | prometheus-tool-node-exporter | gopaddle-servers | ip-10-0-2-109 | 1711464784.738 | 108 |
| go_gc_duration_seconds_count | localhost:9090 | prometheus | 1711464784.738 | 45 |```

**Prometheus metric [go_memstats_heap_idle_bytes]**
```chart
| __name__ | app | cluster_id | component | instance | job | kubernetes_name | kubernetes_namespace | kubernetes_node | timestamp | value |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| go_memstats_heap_idle_bytes | prometheus-tool | [REDACTED_AZURE_API_KEY]d8fa152 | node-exporter | [REDACTED_IP]:9100 | kubernetes-service-endpoints | prometheus-tool-node-exporter | gopaddle-servers | ip-10-0-2-109 | 1711464785.261 | 4227072 |
| go_memstats_heap_idle_bytes | localhost:9090 | prometheus | 1711464785.261 | 25894912 |```

**Prometheus metric [go_memstats_gc_sys_bytes]**
```chart
| __name__ | app | cluster_id | component | instance | job | kubernetes_name | kubernetes_namespace | kubernetes_node | timestamp | value |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| go_memstats_gc_sys_bytes | prometheus-tool | [REDACTED_AZURE_API_KEY]d8fa152 | node-exporter | [REDACTED_IP]:9100 | kubernetes-service-endpoints | prometheus-tool-node-exporter | gopaddle-servers | ip-10-0-2-109 | 1711464785.172 | 5297664 |
| go_memstats_gc_sys_bytes | localhost:9090 | prometheus | 1711464785.172 | 8712032 |```

**Prometheus metric [go_gc_duration_seconds{quantile="0.25"}]**
```chart
| __name__ | app | cluster_id | component | instance | job | kubernetes_name | kubernetes_namespace | kubernetes_node | quantile | timestamp | value |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| go_gc_duration_seconds | prometheus-tool | [REDACTED_AZURE_API_KEY]d8fa152 | node-exporter | [REDACTED_IP]:9100 | kubernetes-service-endpoints | prometheus-tool-node-exporter | gopaddle-servers | ip-10-0-2-109 | 0.25 | 1711464784.501 | 0.000039057 |
| go_gc_duration_seconds | localhost:9090 | prometheus | 0.25 | 1711464784.501 | 0.000057255 |```

**Prometheus metric [go_info{version="go1.19.5"}]**
```chart
| __name__ | instance | job | version | timestamp | value |
| --- | --- | --- | --- | --- | --- |
| go_info | localhost:9090 | prometheus | go1.19.5 | 1711464784.943 | 1 |```

**Prometheus metric [go_memstats_alloc_bytes_total]**
```chart
| __name__ | app | cluster_id | component | instance | job | kubernetes_name | kubernetes_namespace | kubernetes_node | timestamp | value |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| go_memstats_alloc_bytes_total | prometheus-tool | [REDACTED_AZURE_API_KEY]d8fa152 | node-exporter | [REDACTED_IP]:9100 | kubernetes-service-endpoints | prometheus-tool-node-exporter | gopaddle-servers | ip-10-0-2-109 | 1711464784.944 | 208385320 |
| go_memstats_alloc_bytes_total | localhost:9090 | prometheus | 1711464784.944 | 1318035152 |```

**Prometheus metric [go_memstats_heap_alloc_bytes]**
```chart
| __name__ | app | cluster_id | component | instance | job | kubernetes_name | kubernetes_namespace | kubernetes_node | timestamp | value |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| go_memstats_heap_alloc_bytes | prometheus-tool | [REDACTED_AZURE_API_KEY]d8fa152 | node-exporter | [REDACTED_IP]:9100 | kubernetes-service-endpoints | prometheus-tool-node-exporter | gopaddle-servers | ip-10-0-2-109 | 1711464785.173 | 2106448 |
| go_memstats_heap_alloc_bytes | localhost:9090 | prometheus | 1711464785.173 | 51389816 |```

**Prometheus metric [go_memstats_heap_inuse_bytes]**
```chart
| __name__ | app | cluster_id | component | instance | job | kubernetes_name | kubernetes_namespace | kubernetes_node | timestamp | value |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| go_memstats_heap_inuse_bytes | prometheus-tool | [REDACTED_AZURE_API_KEY]d8fa152 | node-exporter | [REDACTED_IP]:9100 | kubernetes-service-endpoints | prometheus-tool-node-exporter | gopaddle-servers | ip-10-0-2-109 | 1711464785.461 | 3768320 |
| go_memstats_heap_inuse_bytes | localhost:9090 | prometheus | 1711464785.461 | 60416000 |```

**Prometheus metric [go_memstats_frees_total]**
```chart
| __name__ | app | cluster_id | component | instance | job | kubernetes_name | kubernetes_namespace | kubernetes_node | timestamp | value |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| go_memstats_frees_total | prometheus-tool | [REDACTED_AZURE_API_KEY]d8fa152 | node-exporter | [REDACTED_IP]:9100 | kubernetes-service-endpoints | prometheus-tool-node-exporter | gopaddle-servers | ip-10-0-2-109 | 1711464784.976 | 2698137 |
| go_memstats_frees_total | localhost:9090 | prometheus | 1711464784.976 | 7379456 |```

**Prometheus metric [go_memstats_heap_released_bytes]**
```chart
| __name__ | app | cluster_id | component | instance | job | kubernetes_name | kubernetes_namespace | kubernetes_node | timestamp | value |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| go_memstats_heap_released_bytes | prometheus-tool | [REDACTED_AZURE_API_KEY]d8fa152 | node-exporter | [REDACTED_IP]:9100 | kubernetes-service-endpoints | prometheus-tool-node-exporter | gopaddle-servers | ip-10-0-2-109 | 1711464785.561 | 3342336 |
| go_memstats_heap_released_bytes | localhost:9090 | prometheus | 1711464785.561 | 835584 |```

**Prometheus metric [go_memstats_heap_objects]**
```chart
| __name__ | app | cluster_id | component | instance | job | kubernetes_name | kubernetes_namespace | kubernetes_node | timestamp | value |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| go_memstats_heap_objects | prometheus-tool | [REDACTED_AZURE_API_KEY]d8fa152 | node-exporter | [REDACTED_IP]:9100 | kubernetes-service-endpoints | prometheus-tool-node-exporter | gopaddle-servers | ip-10-0-2-109 | 1711464785.561 | 16486 |
| go_memstats_heap_objects | localhost:9090 | prometheus | 1711464785.561 | 247021 |```

**Prometheus metric [go_gc_duration_seconds{quantile="0.75"}]**
```chart
| __name__ | app | cluster_id | component | instance | job | kubernetes_name | kubernetes_namespace | kubernetes_node | quantile | timestamp | value |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| go_gc_duration_seconds | prometheus-tool | [REDACTED_AZURE_API_KEY]d8fa152 | node-exporter | [REDACTED_IP]:9100 | kubernetes-service-endpoints | prometheus-tool-node-exporter | gopaddle-servers | ip-10-0-2-109 | 0.75 | 1711464784.733 | 0.000043486 |
| go_gc_duration_seconds | localhost:9090 | prometheus | 0.75 | 1711464784.733 | 0.000127457 |```

**Prometheus metric [go_memstats_heap_sys_bytes]**
```chart
| __name__ | app | cluster_id | component | instance | job | kubernetes_name | kubernetes_namespace | kubernetes_node | timestamp | value |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| go_memstats_heap_sys_bytes | prometheus-tool | [REDACTED_AZURE_API_KEY]d8fa152 | node-exporter | [REDACTED_IP]:9100 | kubernetes-service-endpoints | prometheus-tool-node-exporter | gopaddle-servers | ip-10-0-2-109 | 1711464785.585 | 7995392 |
| go_memstats_heap_sys_bytes | localhost:9090 | prometheus | 1711464785.585 | 86310912 |```

**Prometheus metric [go_memstats_last_gc_time_seconds]**
```chart
| __name__ | app | cluster_id | component | instance | job | kubernetes_name | kubernetes_namespace | kubernetes_node | timestamp | value |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| go_memstats_last_gc_time_seconds | prometheus-tool | [REDACTED_AZURE_API_KEY]d8fa152 | node-exporter | [REDACTED_IP]:9100 | kubernetes-service-endpoints | prometheus-tool-node-exporter | gopaddle-servers | ip-10-0-2-109 | 1711464785.691 | 1711464668.1603122 |
| go_memstats_last_gc_time_seconds | localhost:9090 | prometheus | 1711464785.691 | 1711464696.061844 |```

**Prometheus metric [go_memstats_lookups_total]**
```chart
| __name__ | app | cluster_id | component | instance | job | kubernetes_name | kubernetes_namespace | kubernetes_node | timestamp | value |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| go_memstats_lookups_total | prometheus-tool | [REDACTED_AZURE_API_KEY]d8fa152 | node-exporter | [REDACTED_IP]:9100 | kubernetes-service-endpoints | prometheus-tool-node-exporter | gopaddle-servers | ip-10-0-2-109 | 1711464785.699 | 0 |
| go_memstats_lookups_total | localhost:9090 | prometheus | 1711464785.699 | 0 |```

**Prometheus metric [go_memstats_mallocs_total]**
```chart
| __name__ | app | cluster_id | component | instance | job | kubernetes_name | kubernetes_namespace | kubernetes_node | timestamp | value |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| go_memstats_mallocs_total | prometheus-tool | [REDACTED_AZURE_API_KEY]d8fa152 | node-exporter | [REDACTED_IP]:9100 | kubernetes-service-endpoints | prometheus-tool-node-exporter | gopaddle-servers | ip-10-0-2-109 | 1711464785.729 | 2714623 |
| go_memstats_mallocs_total | localhost:9090 | prometheus | 1711464785.729 | 7626477 |```

**Prometheus metric [go_memstats_mcache_inuse_bytes]**
```chart
| __name__ | app | cluster_id | component | instance | job | kubernetes_name | kubernetes_namespace | kubernetes_node | timestamp | value |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| go_memstats_mcache_inuse_bytes | prometheus-tool | [REDACTED_AZURE_API_KEY]d8fa152 | node-exporter | [REDACTED_IP]:9100 | kubernetes-service-endpoints | prometheus-tool-node-exporter | gopaddle-servers | ip-10-0-2-109 | 1711464785.797 | 1200 |
| go_memstats_mcache_inuse_bytes | localhost:9090 | prometheus | 1711464785.797 | 4800 |```

**Prometheus metric [go_memstats_mspan_inuse_bytes]**
```chart
| __name__ | app | cluster_id | component | instance | job | kubernetes_name | kubernetes_namespace | kubernetes_node | timestamp | value |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| go_memstats_mspan_inuse_bytes | prometheus-tool | [REDACTED_AZURE_API_KEY]d8fa152 | node-exporter | [REDACTED_IP]:9100 | kubernetes-service-endpoints | prometheus-tool-node-exporter | gopaddle-servers | ip-10-0-2-109 | 1711464785.821 | 57528 |
| go_memstats_mspan_inuse_bytes | localhost:9090 | prometheus | 1711464785.821 | 705168 |```

**Prometheus metric [go_goroutines]**
```chart
| __name__ | app | cluster_id | component | instance | job | kubernetes_name | kubernetes_namespace | kubernetes_node | timestamp | value |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| go_goroutines | prometheus-tool | [REDACTED_AZURE_API_KEY]d8fa152 | node-exporter | [REDACTED_IP]:9100 | kubernetes-service-endpoints | prometheus-tool-node-exporter | gopaddle-servers | ip-10-0-2-109 | 1711464784.742 | 7 |
| go_goroutines | localhost:9090 | prometheus | 1711464784.742 | 107 |```

**Prometheus metric [go_memstats_mspan_sys_bytes]**
```chart
| __name__ | app | cluster_id | component | instance | job | kubernetes_name | kubernetes_namespace | kubernetes_node | timestamp | value |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| go_memstats_mspan_sys_bytes | prometheus-tool | [REDACTED_AZURE_API_KEY]d8fa152 | node-exporter | [REDACTED_IP]:9100 | kubernetes-service-endpoints | prometheus-tool-node-exporter | gopaddle-servers | ip-10-0-2-109 | 1711464785.919 | 81600 |
| go_memstats_mspan_sys_bytes | localhost:9090 | prometheus | 1711464785.919 | 1041408 |```

**Prometheus metric [go_memstats_next_gc_bytes]**
```chart
| __name__ | app | cluster_id | component | instance | job | kubernetes_name | kubernetes_namespace | kubernetes_node | timestamp | value |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| go_memstats_next_gc_bytes | prometheus-tool | [REDACTED_AZURE_API_KEY]d8fa152 | node-exporter | [REDACTED_IP]:9100 | kubernetes-service-endpoints | prometheus-tool-node-exporter | gopaddle-servers | ip-10-0-2-109 | 1711464785.94 | 4194304 |
| go_memstats_next_gc_bytes | localhost:9090 | prometheus | 1711464785.94 | 82039744 |```

**Prometheus metric [go_memstats_stack_inuse_bytes]**
```chart
| __name__ | app | cluster_id | component | instance | job | kubernetes_name | kubernetes_namespace | kubernetes_node | timestamp | value |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| go_memstats_stack_inuse_bytes | prometheus-tool | [REDACTED_AZURE_API_KEY]d8fa152 | node-exporter | [REDACTED_IP]:9100 | kubernetes-service-endpoints | prometheus-tool-node-exporter | gopaddle-servers | ip-10-0-2-109 | 1711464786.031 | 393216 |
| go_memstats_stack_inuse_bytes | localhost:9090 | prometheus | 1711464786.031 | 1769472 |```

**Prometheus metric [go_memstats_stack_sys_bytes]**
```chart
| __name__ | app | cluster_id | component | instance | job | kubernetes_name | kubernetes_namespace | kubernetes_node | timestamp | value |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| go_memstats_stack_sys_bytes | prometheus-tool | [REDACTED_AZURE_API_KEY]d8fa152 | node-exporter | [REDACTED_IP]:9100 | kubernetes-service-endpoints | prometheus-tool-node-exporter | gopaddle-servers | ip-10-0-2-109 | 1711464786.032 | 393216 |
| go_memstats_stack_sys_bytes | localhost:9090 | prometheus | 1711464786.032 | 1769472 |```

**Prometheus metric [go_threads]**
```chart
| __name__ | app | cluster_id | component | instance | job | kubernetes_name | kubernetes_namespace | kubernetes_node | timestamp | value |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| go_threads | prometheus-tool | [REDACTED_AZURE_API_KEY]d8fa152 | node-exporter | [REDACTED_IP]:9100 | kubernetes-service-endpoints | prometheus-tool-node-exporter | gopaddle-servers | ip-10-0-2-109 | 1711464786.146 | 5 |
| go_threads | localhost:9090 | prometheus | 1711464786.146 | 10 |```

**Prometheus metric [go_memstats_mcache_sys_bytes]**
```chart
| __name__ | app | cluster_id | component | instance | job | kubernetes_name | kubernetes_namespace | kubernetes_node | timestamp | value |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| go_memstats_mcache_sys_bytes | prometheus-tool | [REDACTED_AZURE_API_KEY]d8fa152 | node-exporter | [REDACTED_IP]:9100 | kubernetes-service-endpoints | prometheus-tool-node-exporter | gopaddle-servers | ip-10-0-2-109 | 1711464785.796 | 15600 |
| go_memstats_mcache_sys_bytes | localhost:9090 | prometheus | 1711464785.796 | 15600 |```

**Prometheus metric [go_memstats_other_sys_bytes]**
```chart
| __name__ | app | cluster_id | component | instance | job | kubernetes_name | kubernetes_namespace | kubernetes_node | timestamp | value |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| go_memstats_other_sys_bytes | prometheus-tool | [REDACTED_AZURE_API_KEY]d8fa152 | node-exporter | [REDACTED_IP]:9100 | kubernetes-service-endpoints | prometheus-tool-node-exporter | gopaddle-servers | ip-10-0-2-109 | 1711464785.978 | 544597 |
| go_memstats_other_sys_bytes | localhost:9090 | prometheus | 1711464785.978 | 995514 |```

**Prometheus metric [go_memstats_sys_bytes]**
```chart
| __name__ | app | cluster_id | component | instance | job | kubernetes_name | kubernetes_namespace | kubernetes_node | timestamp | value |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| go_memstats_sys_bytes | prometheus-tool | [REDACTED_AZURE_API_KEY]d8fa152 | node-exporter | [REDACTED_IP]:9100 | kubernetes-service-endpoints | prometheus-tool-node-exporter | gopaddle-servers | ip-10-0-2-109 | 1711464786.057 | 15824136 |
| go_memstats_sys_bytes | localhost:9090 | prometheus | 1711464786.057 | 100434200 |```
