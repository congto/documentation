## Metrics for Corresponding InfluxDB

| Measurement               | Metrics                                                                 |
| :------------------------ | :---------------------------------------------------------------------- |
| 1. Cpu_metrics            | 1.user 2.nice 3.system 4.idle 5.iowait 6.irq 7.softirq 8.steal 9.guest  |
| 2. Disk_metrics           | 1.reads 2.readsMerged 3.sectorsRead 4.readTime 5.writes 6.writesMerged  |
|                           | 7.sectorsWritten 8.writeTime 9.ioInProgress 10.ioTime 11.ioTimeWeighted |
| 3. Iostat                 | 1.avg_queue_size 2.avg_request_size 3.avg_serve_time 4.kB_reads_per_sec |
|                           | 5.kB_writes_per_sec 6.pct_cpu_utilization 7.pct_idle                    |
|                           | 8.pct_involuntary_wait 9.pct_iowait 10.pct_nice_priority 11.pct_system  |
|                           | 12.pct_user 13.reads_avg_serve_time 14.reads_merged_per_sec             |
|                           | 15.reads_per_sec 16.writes_avg_serve_time 17.writes_merged_per_sec      |
|                           | 18.writes_per_sec.                                                      |
| 4. Impi_sensor_metrics    | 1.ddr3_p1_a1_temp 2.ddr3_p1_b1_temp 3.ddr3_p1_c1_temp 4.ddr3_p1_d1_temp |
|                           | 5.ddr3_p1_e1_temp 6. ddr3_p2_e1_temp 7.ddr3_p2_f1_temp                  |
|                           | 8.ddr3_p2_g1_temp 9.ddr3_p2_h1_temp 10.fan1_tach1 11.fan1_tach2         |
|                           | 12.fan2_tach1 13.fan2_tach2 14.fan3_tach1 15.fan3_tach2 16.fan4_tach1   |
|                           | 17.fan4_tach2 18.fan5_tach1 19.fan5_tach2 20.p1_temp_sens               |
|                           | 21.p2_temp_sens 22.pch_temp_sens 23.power_usage                         |
| 5. Vmstat                 | 1.blocks_received 2.blocks_sent 3.buffer_memory_used                    |
|                           | 4.cache_memory_used 5.context_switches_per_second 6.cpu_time_spent_idle |
|                           | 7.free_memory 8.interrupts_per_second 9.memory_swapped_in               |
|                           | 10.memory_swapped_out 11.swapped_memory_used 12.system_time_spent       |
|                           | 13.time_spent_waiting 14.user_time_spent                                |
| 6. Memory_metrics         | 1.cached 2.dirty 3.free 4.freeWOBuffersCaches 5.from 6.swapFree         |
|                           | 7.swapTotal 8.swapUsed 9.swapUsedPercentage 10.total 11.used            |
|                           | 12.usedWOBuffersCaches 13.used_percentage 14.used_without_disk_caching  |
| 7. Switch_network         | 1.bandwidth 2.ifInSpeed 3.ifInUtilization 4.ifOutSpeed                  |
|                           | 5.ifOutUtilization 6.ifStatus                                           |
| 8. Switch_cpu_mem         | 1.CiscoSwitchCPUMemoryFree 2.CiscoSwitchCPUMemoryUsed                   |
|                           | 3.CiscoSwitchCPUTotal1minRev 4.CiscoSwitchCPUUsed_Percentage            |
|                           | 5.cpmCPUMemoryFree 6.cpmCPUMemoryUsed 7.cpmCPUTotal1minRev              |
| 9. Usagetime_metrics      | 1.DiskGB 2.MemoryMB 3.VCPU 4.VMCOUNT                                    |
| 10. ceph_metrics          | 1.numpg 2.numpg_primary 3.numpg_replica 4.numpg_stray 5.stat_bytes      |
|                           | 6.stat_bytes_used 7.stat_bytes_avail 8.op_in_bytes 9.op_out_bytes       |
|                           | 10.op_r 11.op_w 12.Loadavg                                              |
| 11. Swift_metrics         | 1.No.of buckets 2.swiftusage                                            |
| 12. Instance_allocation   | 1.instance_id 2.Project_id 3.Status                                     |
| 13. Instance_mapping      | 1created_at 2.deleted_at 3.event_type 4.instance_id 5.metrics           |
|                           | 6.project_id 7.user_id                                                  |
| 14. Compute_metrics       | 1.hypervisor 2.project_name 3.vm_id 4.vm_name                           |
| 15. Instance_meter        | 1Cpu2.cpu_util 3.disk.ephemeral.size 4.disk.read.bytes                  |
|                           | 5.disk.read.bytes.rate 6disk.read.requests 7.disk.read.requests.rate    |
|                           | 8.disk.root.size 9.disk.write.bytes 10.disk.write.bytes.rate            |
|                           | 11.disk.write.requests 12.disk.write.requests.rate 13.instance          |
|                           | 14.memory 15.network.incoming.bytes 16.network.incoming.bytes.rate      |
|                           | 17.network.incoming.packets 18.network.incoming.packets.rate            |
|                           | 19.network.outgoing.bytes network.outgoing.bytes.rate                   |
|                           | 21.network.outgoing.packets 22.network.outgoing.packets.rate 23.vcpus   |
|                           | 24.instance_id 25.project_id.                                           |
| 16. switch_cpu_mem        | 1.CiscoSwitchCPUMemoryFree 2.CiscoSwitchCPUMemoryUsed                   |
|                           | 3.CiscoSwitchCPUTotal1minRev 4.CiscoSwitchC PUUsed_Percentage           |
|                           | 5.cpmCPUMemoryFree 6.cpmCPUMemoryUsed 7.cpmCPUTotal1minRev              |
| 17. switch_cpu_mem_r3_c17 | 1.CiscoSwitchCPUMemoryFree 2.CiscoSwitchCPUMemoryUsed                   |
|                           | 3.CiscoSwitchCPUTotal1minRev 4.CiscoSwitchCPUUsed_Percentage            |
|                           | 5.cpmCPUMemoryFree 6.cpmCPUMemoryUsed 7.cpmCPUTotal1minRev              |
| 18. switch_network_r3_c17 | 1.Bandwidth 2.ifInSpeed 3.ifInUtilization 4.ifOutSpeed                  |
|                           | 5.ifOutUtilization 6.ifStatus                                           |
| 19.Aggregated_metrics     | 1.#_uninterruptible_processes 2.CiscoSwitchCPUMemoryFree                |
|                           | 3.CiscoSwitchCPUMemoryUsed 4.CiscoSwitchCP UUsed_Percentage 5.avail     |
|                           | 6.avg_queue_size 7.avg_request_size 8.avg_serve_time 9.blocks_received  |
|                           | 10.blocks_sent 11.buffer_memory_used 12.cache_memory_used               |
|                           | 13.context_switches_per_second 14.cpu_time_spent_idle                   |
|                           | 15.ddr3_p1_a1_temp 16.ddr3_p1_b1_t emp 17.ddr3_p1_c1_temp               |
|                           | 18.ddr3_p1_d1_temp 19.ddr3_p2_e1_temp 20.ddr3_p2_f1_temp                |
|                           | 21.ddr3_p2_g1_temp 22.ddr3_p2_h1_temp 23.f an1_tach1 24.fan1_tach2      |
|                           | 25.fan2_tach1 26.fan2_tach2 27.fan3_tach1 28.fan3_tach2 29.fan4_tach1   |
|                           | 30.fan4_tach2 31.fan5_tach1 32.fan5_tach2 33.free 34.free_memory        |
|                           | 35.idle 36.ifInSpeed 37.ifInUtilization 38.ifOutSpeed                   |
|                           | 39.ifOutUtilization 40.interrup ts_per_second 41.ioInProgress 42.ioTime |
|                           | 43.ioTimeWeighted 44.iowait 45.kB_reads_per_sec 46.kB_writes_per_sec    |
|                           | 47.memory_swa pped_in 48.memory_swapped_out 49.p1_temp_sens             |
|                           | 50.p2_temp_sens 51.pch_temp_sens 52.pct_cpu_utilization                 |
|                           | 53.pct_involuntary_w ait 54.pct_iowait 55.pct_nice_priority             |
|                           | 56.pct_system 57.pct_user 58.power_usage 59.readTime 60.reads           |
|                           | 61.readsMerged 62.rea ds_avg_serve_time 63.reads_merged_per_sec         |
|                           | 64.reads_per_sec 65.sectorsRead 66.sectorsWritten 67.swapTotal          |
|                           | 68.swapUsedPercentage 69.swapped_memory_used 70.system                  |
|                           | 71.system_time_spent 72.time_spent_waiting 73.total 74.used             |
|                           | 75.used_percentage 76.user 77.user_time_spent 78.writeTime 79.writes    |
|                           | 80.writesMerged 81.writes_avg_serve_time 82.writes_merged_per_sec       |
|                           | 83.writes_per_sec.                                                      |
