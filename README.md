# Server Metrics 2026-03-15 14:45:47 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.18

telemt_uptime_seconds 59477.5 (16h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1860118
telemt_connections_bad_total 100840
telemt_handshake_timeouts_total 20987
telemt_upstream_connect_attempt_total 11812
telemt_upstream_connect_success_total 11763
telemt_upstream_connect_fail_total 49
telemt_upstream_connect_attempts_per_request{bucket="1"} 11812
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6150
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5571
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 42
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 49
telemt_me_keepalive_timeout_total 47
telemt_me_reconnect_attempts_total 13665
telemt_me_reconnect_success_total 8774
telemt_me_reader_eof_total 9394
telemt_me_idle_close_by_peer_total 9394
telemt_me_route_drop_no_conn_total 638129
telemt_me_route_drop_channel_closed_total 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1574343
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5980
telemt_desync_full_logged_total 1662
telemt_desync_suppressed_total 4318
telemt_desync_frames_bucket_total{bucket="1_2"} 1497
telemt_desync_frames_bucket_total{bucket="3_10"} 2305
telemt_desync_frames_bucket_total{bucket="gt_10"} 2178
telemt_pool_swap_total 44
telemt_me_writer_removed_unexpected_total 9070
telemt_me_refill_failed_total 151
telemt_me_writer_restored_same_endpoint_total 8763
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 296
telemt_me_writer_removed_unexpected_minus_restored_total 296
telemt_user_connections_total{user="hello"} 1573940
telemt_user_connections_current{user="hello"} 2235
telemt_user_octets_from_client{user="hello"} 22428441520 (20.89 GB)
telemt_user_octets_to_client{user="hello"} 616392865716 (574.06 GB)
telemt_user_unique_ips_current{user="hello"} 664
telemt_user_unique_ips_recent_window{user="hello"} 288
```

## server2

```
telemt 3.3.18

telemt_uptime_seconds 59477.8 (16h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 752903
telemt_connections_bad_total 40559
telemt_handshake_timeouts_total 58224
telemt_upstream_connect_attempt_total 15020
telemt_upstream_connect_success_total 14947
telemt_upstream_connect_fail_total 73
telemt_upstream_connect_attempts_per_request{bucket="1"} 15020
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7985
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6825
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 35
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 102
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 73
telemt_me_keepalive_timeout_total 59
telemt_me_reconnect_attempts_total 11719
telemt_me_reconnect_success_total 11624
telemt_me_reader_eof_total 12289
telemt_me_idle_close_by_peer_total 12289
telemt_me_route_drop_no_conn_total 187723
telemt_me_route_drop_channel_closed_total 3
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 568404
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 16
telemt_me_endpoint_quarantine_total 17
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1994
telemt_desync_full_logged_total 690
telemt_desync_suppressed_total 1304
telemt_desync_frames_bucket_total{bucket="1_2"} 739
telemt_desync_frames_bucket_total{bucket="3_10"} 731
telemt_desync_frames_bucket_total{bucket="gt_10"} 524
telemt_pool_swap_total 50
telemt_me_writer_removed_unexpected_total 11770
telemt_me_writer_restored_same_endpoint_total 11612
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 61
telemt_me_writer_removed_unexpected_minus_restored_total 146
telemt_user_connections_total{user="hello"} 568653
telemt_user_connections_current{user="hello"} 792
telemt_user_octets_from_client{user="hello"} 7910191507 (7.37 GB)
telemt_user_octets_to_client{user="hello"} 213507839272 (198.84 GB)
telemt_user_msgs_from_client{user="hello"} 620
telemt_user_msgs_to_client{user="hello"} 1332
telemt_user_unique_ips_current{user="hello"} 246
telemt_user_unique_ips_recent_window{user="hello"} 121
```

## server3

```
telemt 3.3.18

telemt_uptime_seconds 59477.9 (16h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1631973
telemt_connections_bad_total 46883
telemt_handshake_timeouts_total 166000
telemt_upstream_connect_attempt_total 13053
telemt_upstream_connect_success_total 12991
telemt_upstream_connect_fail_total 62
telemt_upstream_connect_attempts_per_request{bucket="1"} 13053
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6705
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6222
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 64
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 62
telemt_me_keepalive_timeout_total 45
telemt_me_reconnect_attempts_total 11236
telemt_me_reconnect_success_total 9982
telemt_me_reader_eof_total 10576
telemt_me_idle_close_by_peer_total 10576
telemt_me_route_drop_no_conn_total 440711
telemt_me_route_drop_channel_closed_total 17
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1004019
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2503
telemt_desync_full_logged_total 926
telemt_desync_suppressed_total 1577
telemt_desync_frames_bucket_total{bucket="1_2"} 576
telemt_desync_frames_bucket_total{bucket="3_10"} 967
telemt_desync_frames_bucket_total{bucket="gt_10"} 960
telemt_pool_swap_total 51
telemt_me_writer_removed_unexpected_total 10155
telemt_me_refill_failed_total 37
telemt_me_writer_restored_same_endpoint_total 9963
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 242
telemt_me_writer_removed_unexpected_minus_restored_total 173
telemt_user_connections_total{user="hello"} 1000062
telemt_user_connections_current{user="hello"} 1317
telemt_user_octets_from_client{user="hello"} 14524583388 (13.53 GB)
telemt_user_octets_to_client{user="hello"} 360257691528 (335.52 GB)
telemt_user_unique_ips_current{user="hello"} 399
telemt_user_unique_ips_recent_window{user="hello"} 196
```

## server4

```
telemt 3.3.18

telemt_uptime_seconds 59477.8 (16h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 786456
telemt_connections_bad_total 73258
telemt_handshake_timeouts_total 40920
telemt_upstream_connect_attempt_total 167238
telemt_upstream_connect_success_total 166741
telemt_upstream_connect_fail_total 497
telemt_upstream_connect_attempts_per_request{bucket="1"} 167238
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 154543
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12166
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 32
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 497
telemt_me_keepalive_timeout_total 39
telemt_me_reconnect_attempts_total 52232
telemt_me_reconnect_success_total 11799
telemt_me_reader_eof_total 13393
telemt_me_idle_close_by_peer_total 13393
telemt_me_seq_mismatch_total 20
telemt_me_route_drop_no_conn_total 171377
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 448648
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 37
telemt_me_hardswap_pending_ttl_expired_total 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1175
telemt_desync_full_logged_total 299
telemt_desync_suppressed_total 876
telemt_desync_frames_bucket_total{bucket="1_2"} 324
telemt_desync_frames_bucket_total{bucket="3_10"} 476
telemt_desync_frames_bucket_total{bucket="gt_10"} 375
telemt_pool_swap_total 17
telemt_me_writer_removed_unexpected_total 13174
telemt_me_refill_failed_total 1265
telemt_me_writer_restored_same_endpoint_total 11767
telemt_me_writer_restored_fallback_total 32
telemt_me_async_recovery_trigger_total 96
telemt_me_writer_removed_unexpected_minus_restored_total 1375
telemt_user_connections_total{user="hello"} 600474
telemt_user_connections_current{user="hello"} 987
telemt_user_octets_from_client{user="hello"} 11318013915 (10.54 GB)
telemt_user_octets_to_client{user="hello"} 202062194279 (188.19 GB)
telemt_user_msgs_from_client{user="hello"} 3031946
telemt_user_msgs_to_client{user="hello"} 10919823
telemt_user_unique_ips_current{user="hello"} 216
telemt_user_unique_ips_recent_window{user="hello"} 151
```

## server5

```
telemt 3.3.18

telemt_uptime_seconds 59478.6 (16h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 799385
telemt_connections_bad_total 9414
telemt_handshake_timeouts_total 16811
telemt_upstream_connect_attempt_total 13135
telemt_upstream_connect_success_total 13063
telemt_upstream_connect_fail_total 71
telemt_upstream_connect_attempts_per_request{bucket="1"} 13134
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6034
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7018
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 71
telemt_me_keepalive_timeout_total 86
telemt_me_reconnect_attempts_total 13747
telemt_me_reconnect_success_total 10067
telemt_me_reader_eof_total 10756
telemt_me_idle_close_by_peer_total 10756
telemt_me_route_drop_no_conn_total 198764
telemt_me_route_drop_channel_closed_total 24
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 652574
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2329
telemt_desync_full_logged_total 787
telemt_desync_suppressed_total 1542
telemt_desync_frames_bucket_total{bucket="1_2"} 702
telemt_desync_frames_bucket_total{bucket="3_10"} 898
telemt_desync_frames_bucket_total{bucket="gt_10"} 729
telemt_pool_swap_total 50
telemt_me_writer_removed_unexpected_total 10300
telemt_me_refill_failed_total 113
telemt_me_writer_restored_same_endpoint_total 10059
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 54
telemt_me_writer_removed_unexpected_minus_restored_total 233
telemt_user_connections_total{user="hello"} 652618
telemt_user_connections_current{user="hello"} 814
telemt_user_octets_from_client{user="hello"} 8202889148 (7.64 GB)
telemt_user_octets_to_client{user="hello"} 243090621100 (226.40 GB)
telemt_user_unique_ips_current{user="hello"} 247
telemt_user_unique_ips_recent_window{user="hello"} 125
```