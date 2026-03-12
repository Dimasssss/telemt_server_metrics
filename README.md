# Server Metrics 2026-03-12 04:07:28 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 22948.7 (6h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 208156
telemt_connections_bad_total 1368
telemt_handshake_timeouts_total 3548
telemt_upstream_connect_attempt_total 5274
telemt_upstream_connect_success_total 5273
telemt_upstream_connect_attempts_per_request{bucket="1"} 5273
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2784
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2476
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_me_keepalive_timeout_total 111
telemt_me_reconnect_attempts_total 4125
telemt_me_reconnect_success_total 4107
telemt_me_reader_eof_total 4343
telemt_me_idle_close_by_peer_total 4343
telemt_me_route_drop_no_conn_total 74717
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 197572
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 401
telemt_desync_full_logged_total 107
telemt_desync_suppressed_total 294
telemt_desync_frames_bucket_total{bucket="1_2"} 136
telemt_desync_frames_bucket_total{bucket="3_10"} 138
telemt_desync_frames_bucket_total{bucket="gt_10"} 127
telemt_pool_swap_total 23
telemt_me_writer_removed_unexpected_total 4152
telemt_me_writer_restored_same_endpoint_total 4091
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 186
telemt_me_writer_removed_unexpected_minus_restored_total 45
telemt_user_connections_total{user="hello"} 197347
telemt_user_connections_current{user="hello"} 694
telemt_user_octets_from_client{user="hello"} 1819601180 (1.69 GB)
telemt_user_octets_to_client{user="hello"} 60942623424 (56.76 GB)
telemt_user_unique_ips_current{user="hello"} 244
telemt_user_unique_ips_recent_window{user="hello"} 105
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 22949.5 (6h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 70195
telemt_connections_bad_total 128
telemt_handshake_timeouts_total 1338
telemt_upstream_connect_attempt_total 6443
telemt_upstream_connect_success_total 6440
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 6443
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3206
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3225
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_keepalive_timeout_total 126
telemt_me_reconnect_attempts_total 5109
telemt_me_reconnect_success_total 5077
telemt_me_reader_eof_total 5391
telemt_me_idle_close_by_peer_total 5391
telemt_me_route_drop_no_conn_total 20469
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 64668
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 178
telemt_desync_full_logged_total 88
telemt_desync_suppressed_total 90
telemt_desync_frames_bucket_total{bucket="1_2"} 69
telemt_desync_frames_bucket_total{bucket="3_10"} 56
telemt_desync_frames_bucket_total{bucket="gt_10"} 53
telemt_pool_swap_total 24
telemt_me_writer_removed_unexpected_total 5116
telemt_me_writer_restored_same_endpoint_total 5068
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 39
telemt_user_connections_total{user="hello"} 64856
telemt_user_connections_current{user="hello"} 273
telemt_user_octets_from_client{user="hello"} 1064115067 (1014.82 MB)
telemt_user_octets_to_client{user="hello"} 22025444598 (20.51 GB)
telemt_user_msgs_from_client{user="hello"} 353
telemt_user_msgs_to_client{user="hello"} 423
telemt_user_unique_ips_current{user="hello"} 87
telemt_user_unique_ips_recent_window{user="hello"} 41
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 22949.1 (6h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 341762
telemt_connections_bad_total 1754
telemt_handshake_timeouts_total 20978
telemt_upstream_connect_attempt_total 6792
telemt_upstream_connect_success_total 6790
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 6792
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3843
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2916
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 27
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_timeout_total 111
telemt_me_reconnect_attempts_total 5315
telemt_me_reconnect_success_total 5259
telemt_me_reader_eof_total 5483
telemt_me_idle_close_by_peer_total 5483
telemt_me_route_drop_no_conn_total 37772
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 119631
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 376
telemt_desync_full_logged_total 135
telemt_desync_suppressed_total 241
telemt_desync_frames_bucket_total{bucket="1_2"} 38
telemt_desync_frames_bucket_total{bucket="3_10"} 143
telemt_desync_frames_bucket_total{bucket="gt_10"} 195
telemt_pool_swap_total 23
telemt_me_writer_removed_unexpected_total 5225
telemt_me_refill_failed_total 1
telemt_me_writer_restored_same_endpoint_total 5218
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_user_connections_total{user="hello"} 119946
telemt_user_connections_current{user="hello"} 390
telemt_user_octets_from_client{user="hello"} 1093050552 (1.02 GB)
telemt_user_octets_to_client{user="hello"} 36905207117 (34.37 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 135
telemt_user_unique_ips_recent_window{user="hello"} 56
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 22949.6 (6h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 106464
telemt_connections_bad_total 187
telemt_handshake_timeouts_total 6003
telemt_upstream_connect_attempt_total 6847
telemt_upstream_connect_success_total 6816
telemt_upstream_connect_fail_total 31
telemt_upstream_connect_attempts_per_request{bucket="1"} 6847
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3895
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2918
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 31
telemt_me_keepalive_timeout_total 97
telemt_me_reconnect_attempts_total 5664
telemt_me_reconnect_success_total 5644
telemt_me_reader_eof_total 5989
telemt_me_idle_close_by_peer_total 5989
telemt_me_route_drop_no_conn_total 36035
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 98839
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 151
telemt_desync_full_logged_total 47
telemt_desync_suppressed_total 104
telemt_desync_frames_bucket_total{bucket="1_2"} 34
telemt_desync_frames_bucket_total{bucket="3_10"} 68
telemt_desync_frames_bucket_total{bucket="gt_10"} 49
telemt_pool_swap_total 22
telemt_me_writer_removed_unexpected_total 5680
telemt_me_writer_restored_same_endpoint_total 5623
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 108
telemt_me_writer_removed_unexpected_minus_restored_total 36
telemt_user_connections_total{user="hello"} 98825
telemt_user_connections_current{user="hello"} 327
telemt_user_octets_from_client{user="hello"} 778090948 (742.05 MB)
telemt_user_octets_to_client{user="hello"} 27918544664 (26.00 GB)
telemt_user_unique_ips_current{user="hello"} 113
telemt_user_unique_ips_recent_window{user="hello"} 49
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 22949.4 (6h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 125877
telemt_connections_bad_total 74
telemt_handshake_timeouts_total 752
telemt_upstream_connect_attempt_total 8605
telemt_upstream_connect_success_total 8516
telemt_upstream_connect_fail_total 89
telemt_upstream_connect_attempts_per_request{bucket="1"} 8605
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4370
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4100
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 43
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 89
telemt_me_keepalive_timeout_total 126
telemt_me_reconnect_attempts_total 8833
telemt_me_reconnect_success_total 7332
telemt_me_reader_eof_total 7599
telemt_me_idle_close_by_peer_total 7599
telemt_me_seq_mismatch_total 12
telemt_me_route_drop_no_conn_total 34075
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 120272
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 452
telemt_desync_full_logged_total 157
telemt_desync_suppressed_total 295
telemt_desync_frames_bucket_total{bucket="1_2"} 122
telemt_desync_frames_bucket_total{bucket="3_10"} 179
telemt_desync_frames_bucket_total{bucket="gt_10"} 151
telemt_pool_swap_total 12
telemt_me_writer_removed_unexpected_total 7436
telemt_me_refill_failed_total 46
telemt_me_writer_restored_same_endpoint_total 7315
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 104
telemt_user_connections_total{user="hello"} 120247
telemt_user_connections_current{user="hello"} 331
telemt_user_octets_from_client{user="hello"} 775101840 (739.19 MB)
telemt_user_octets_to_client{user="hello"} 26299122672 (24.49 GB)
telemt_user_unique_ips_current{user="hello"} 110
telemt_user_unique_ips_recent_window{user="hello"} 55
```