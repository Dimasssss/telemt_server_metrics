# Server Metrics 2026-03-13 13:23:19 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 113081.3 (31h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3412286
telemt_connections_bad_total 37373
telemt_handshake_timeouts_total 58736
telemt_upstream_connect_attempt_total 22206
telemt_upstream_connect_success_total 22083
telemt_upstream_connect_fail_total 123
telemt_upstream_connect_attempts_per_request{bucket="1"} 22206
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11395
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10630
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 58
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 123
telemt_me_keepalive_timeout_total 2109
telemt_me_reconnect_attempts_total 26541
telemt_me_reconnect_success_total 16457
telemt_me_reader_eof_total 17691
telemt_me_idle_close_by_peer_total 17690
telemt_me_route_drop_no_conn_total 1265454
telemt_me_route_drop_channel_closed_total 16
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3129523
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 13056
telemt_desync_full_logged_total 3409
telemt_desync_suppressed_total 9647
telemt_desync_frames_bucket_total{bucket="1_2"} 3309
telemt_desync_frames_bucket_total{bucket="3_10"} 4941
telemt_desync_frames_bucket_total{bucket="gt_10"} 4806
telemt_pool_swap_total 92
telemt_me_writer_removed_unexpected_total 17002
telemt_me_refill_failed_total 312
telemt_me_writer_restored_same_endpoint_total 16444
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 545
telemt_user_connections_total{user="hello"} 3129412
telemt_user_connections_current{user="hello"} 1837
telemt_user_octets_from_client{user="hello"} 43102866308 (40.14 GB)
telemt_user_octets_to_client{user="hello"} 1002427428084 (933.58 GB)
telemt_user_unique_ips_current{user="hello"} 484
telemt_user_unique_ips_recent_window{user="hello"} 221
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 12745.3 (3h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 175552
telemt_connections_bad_total 9995
telemt_handshake_timeouts_total 4376
telemt_upstream_connect_attempt_total 3072
telemt_upstream_connect_success_total 2997
telemt_upstream_connect_fail_total 75
telemt_upstream_connect_attempts_per_request{bucket="1"} 3072
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1536
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1434
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 10
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 17
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 75
telemt_me_keepalive_timeout_total 67
telemt_me_reconnect_attempts_total 3523
telemt_me_reconnect_success_total 2294
telemt_me_reader_eof_total 2416
telemt_me_idle_close_by_peer_total 2416
telemt_me_route_drop_no_conn_total 63571
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 156811
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 6
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 620
telemt_desync_full_logged_total 139
telemt_desync_suppressed_total 481
telemt_desync_frames_bucket_total{bucket="1_2"} 113
telemt_desync_frames_bucket_total{bucket="3_10"} 330
telemt_desync_frames_bucket_total{bucket="gt_10"} 177
telemt_pool_swap_total 11
telemt_me_writer_removed_unexpected_total 2350
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 2287
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 22
telemt_me_writer_removed_unexpected_minus_restored_total 56
telemt_user_connections_total{user="hello"} 156835
telemt_user_connections_current{user="hello"} 500
telemt_user_octets_from_client{user="hello"} 1584753068 (1.48 GB)
telemt_user_octets_to_client{user="hello"} 43154991608 (40.19 GB)
telemt_user_unique_ips_current{user="hello"} 168
telemt_user_unique_ips_recent_window{user="hello"} 100
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 142702.0 (39h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2568044
telemt_connections_bad_total 26761
telemt_handshake_timeouts_total 169330
telemt_upstream_connect_attempt_total 32368
telemt_upstream_connect_success_total 32358
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 32368
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16854
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15379
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 120
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_keepalive_timeout_total 3197
telemt_me_reconnect_attempts_total 27457
telemt_me_reconnect_success_total 24911
telemt_me_reader_eof_total 26410
telemt_me_idle_close_by_peer_total 26409
telemt_me_route_drop_no_conn_total 861752
telemt_me_route_drop_channel_closed_total 14
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2092402
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7233
telemt_desync_full_logged_total 2371
telemt_desync_suppressed_total 4862
telemt_desync_frames_bucket_total{bucket="1_2"} 1142
telemt_desync_frames_bucket_total{bucket="3_10"} 2635
telemt_desync_frames_bucket_total{bucket="gt_10"} 3456
telemt_pool_swap_total 133
telemt_me_writer_removed_unexpected_total 25199
telemt_me_refill_failed_total 75
telemt_me_writer_restored_same_endpoint_total 24870
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 288
telemt_user_connections_total{user="hello"} 2091827
telemt_user_connections_current{user="hello"} 1097
telemt_user_octets_from_client{user="hello"} 35039317320 (32.63 GB)
telemt_user_octets_to_client{user="hello"} 750526642353 (698.98 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 331
telemt_user_unique_ips_recent_window{user="hello"} 189
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 142702.7 (39h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1637275
telemt_connections_bad_total 17887
telemt_handshake_timeouts_total 115570
telemt_upstream_connect_attempt_total 45735
telemt_upstream_connect_success_total 43415
telemt_upstream_connect_fail_total 2183
telemt_upstream_connect_attempts_per_request{bucket="1"} 45461
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 26180
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17144
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 91
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2182
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 11832
telemt_me_reconnect_attempts_total 39421
telemt_me_reconnect_success_total 30455
telemt_me_reader_eof_total 32747
telemt_me_idle_close_by_peer_total 32740
telemt_me_route_drop_no_conn_total 583062
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1368089
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2748
telemt_desync_full_logged_total 896
telemt_desync_suppressed_total 1852
telemt_desync_frames_bucket_total{bucket="1_2"} 734
telemt_desync_frames_bucket_total{bucket="3_10"} 1139
telemt_desync_frames_bucket_total{bucket="gt_10"} 875
telemt_pool_swap_total 124
telemt_me_writer_removed_unexpected_total 30959
telemt_me_refill_failed_total 274
telemt_me_writer_restored_same_endpoint_total 30431
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 504
telemt_user_connections_total{user="hello"} 1372810
telemt_user_connections_current{user="hello"} 608
telemt_user_octets_from_client{user="hello"} 20760112073 (19.33 GB)
telemt_user_octets_to_client{user="hello"} 535921035554 (499.12 GB)
telemt_user_msgs_from_client{user="hello"} 44500
telemt_user_msgs_to_client{user="hello"} 116355
telemt_user_unique_ips_current{user="hello"} 190
telemt_user_unique_ips_recent_window{user="hello"} 106
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 12138.2 (3h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 189146
telemt_connections_bad_total 3842
telemt_handshake_timeouts_total 1634
telemt_upstream_connect_attempt_total 2464
telemt_upstream_connect_success_total 2380
telemt_upstream_connect_fail_total 84
telemt_upstream_connect_attempts_per_request{bucket="1"} 2464
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1099
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1279
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 84
telemt_me_keepalive_timeout_total 34
telemt_me_reconnect_attempts_total 9802
telemt_me_reconnect_success_total 1728
telemt_me_reader_eof_total 1982
telemt_me_idle_close_by_peer_total 1982
telemt_me_route_drop_no_conn_total 72855
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 177150
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 3
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 610
telemt_desync_full_logged_total 198
telemt_desync_suppressed_total 412
telemt_desync_frames_bucket_total{bucket="1_2"} 260
telemt_desync_frames_bucket_total{bucket="3_10"} 225
telemt_desync_frames_bucket_total{bucket="gt_10"} 125
telemt_pool_swap_total 3
telemt_me_writer_removed_unexpected_total 1978
telemt_me_refill_failed_total 251
telemt_me_writer_restored_same_endpoint_total 1724
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 250
telemt_user_connections_total{user="hello"} 177135
telemt_user_connections_current{user="hello"} 794
telemt_user_octets_from_client{user="hello"} 1906733176 (1.78 GB)
telemt_user_octets_to_client{user="hello"} 54979653728 (51.20 GB)
telemt_user_unique_ips_current{user="hello"} 207
telemt_user_unique_ips_recent_window{user="hello"} 116
```