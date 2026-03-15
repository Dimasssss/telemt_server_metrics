# Server Metrics 2026-03-15 16:02:25 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.18

telemt_uptime_seconds 64074.6 (17h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2116897
telemt_connections_bad_total 120071
telemt_handshake_timeouts_total 25505
telemt_upstream_connect_attempt_total 12764
telemt_upstream_connect_success_total 12708
telemt_upstream_connect_fail_total 56
telemt_upstream_connect_attempts_per_request{bucket="1"} 12764
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6608
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6047
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 53
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 56
telemt_me_keepalive_timeout_total 47
telemt_me_reconnect_attempts_total 14369
telemt_me_reconnect_success_total 9474
telemt_me_reader_eof_total 10128
telemt_me_idle_close_by_peer_total 10128
telemt_me_route_drop_no_conn_total 727428
telemt_me_route_drop_channel_closed_total 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1784644
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 6844
telemt_desync_full_logged_total 1888
telemt_desync_suppressed_total 4956
telemt_desync_frames_bucket_total{bucket="1_2"} 1693
telemt_desync_frames_bucket_total{bucket="3_10"} 2617
telemt_desync_frames_bucket_total{bucket="gt_10"} 2534
telemt_pool_swap_total 47
telemt_me_writer_removed_unexpected_total 9782
telemt_me_refill_failed_total 151
telemt_me_writer_restored_same_endpoint_total 9463
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 296
telemt_me_writer_removed_unexpected_minus_restored_total 308
telemt_user_connections_total{user="hello"} 1784152
telemt_user_connections_current{user="hello"} 2470
telemt_user_octets_from_client{user="hello"} 26154506068 (24.36 GB)
telemt_user_octets_to_client{user="hello"} 685102160136 (638.05 GB)
telemt_user_unique_ips_current{user="hello"} 688
telemt_user_unique_ips_recent_window{user="hello"} 349
```

## server2

```
telemt 3.3.18

telemt_uptime_seconds 64075.0 (17h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 835895
telemt_connections_bad_total 44616
telemt_handshake_timeouts_total 59736
telemt_upstream_connect_attempt_total 16091
telemt_upstream_connect_success_total 16014
telemt_upstream_connect_fail_total 77
telemt_upstream_connect_attempts_per_request{bucket="1"} 16091
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8530
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7337
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 37
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 110
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 77
telemt_me_keepalive_timeout_total 59
telemt_me_reconnect_attempts_total 12537
telemt_me_reconnect_success_total 12435
telemt_me_reader_eof_total 13139
telemt_me_idle_close_by_peer_total 13139
telemt_me_route_drop_no_conn_total 212113
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 637918
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 16
telemt_me_endpoint_quarantine_total 17
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2080
telemt_desync_full_logged_total 701
telemt_desync_suppressed_total 1379
telemt_desync_frames_bucket_total{bucket="1_2"} 765
telemt_desync_frames_bucket_total{bucket="3_10"} 763
telemt_desync_frames_bucket_total{bucket="gt_10"} 552
telemt_pool_swap_total 53
telemt_me_writer_removed_unexpected_total 12597
telemt_me_writer_restored_same_endpoint_total 12423
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 61
telemt_me_writer_removed_unexpected_minus_restored_total 162
telemt_user_connections_total{user="hello"} 638159
telemt_user_connections_current{user="hello"} 784
telemt_user_octets_from_client{user="hello"} 8896940759 (8.29 GB)
telemt_user_octets_to_client{user="hello"} 242306466300 (225.67 GB)
telemt_user_msgs_from_client{user="hello"} 620
telemt_user_msgs_to_client{user="hello"} 1332
telemt_user_unique_ips_current{user="hello"} 231
telemt_user_unique_ips_recent_window{user="hello"} 146
```

## server3

```
telemt 3.3.18

telemt_uptime_seconds 64075.1 (17h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1888672
telemt_connections_bad_total 48102
telemt_handshake_timeouts_total 188031
telemt_upstream_connect_attempt_total 13945
telemt_upstream_connect_success_total 13879
telemt_upstream_connect_fail_total 66
telemt_upstream_connect_attempts_per_request{bucket="1"} 13945
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7160
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6652
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 67
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 66
telemt_me_keepalive_timeout_total 45
telemt_me_reconnect_attempts_total 11884
telemt_me_reconnect_success_total 10620
telemt_me_reader_eof_total 11260
telemt_me_idle_close_by_peer_total 11260
telemt_me_route_drop_no_conn_total 488450
telemt_me_route_drop_channel_closed_total 18
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1135089
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2765
telemt_desync_full_logged_total 1015
telemt_desync_suppressed_total 1750
telemt_desync_frames_bucket_total{bucket="1_2"} 645
telemt_desync_frames_bucket_total{bucket="3_10"} 1068
telemt_desync_frames_bucket_total{bucket="gt_10"} 1052
telemt_pool_swap_total 56
telemt_me_writer_removed_unexpected_total 10809
telemt_me_refill_failed_total 37
telemt_me_writer_restored_same_endpoint_total 10601
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 242
telemt_me_writer_removed_unexpected_minus_restored_total 189
telemt_user_connections_total{user="hello"} 1131051
telemt_user_connections_current{user="hello"} 1317
telemt_user_octets_from_client{user="hello"} 16288191724 (15.17 GB)
telemt_user_octets_to_client{user="hello"} 402512457380 (374.87 GB)
telemt_user_unique_ips_current{user="hello"} 426
telemt_user_unique_ips_recent_window{user="hello"} 202
```

## server4

```
telemt 3.3.18

telemt_uptime_seconds 64075.0 (17h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 888455
telemt_connections_bad_total 77555
telemt_handshake_timeouts_total 43313
telemt_upstream_connect_attempt_total 168430
telemt_upstream_connect_success_total 167909
telemt_upstream_connect_fail_total 521
telemt_upstream_connect_attempts_per_request{bucket="1"} 168430
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 155205
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12672
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 32
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 521
telemt_me_keepalive_timeout_total 39
telemt_me_reconnect_attempts_total 53053
telemt_me_reconnect_success_total 12608
telemt_me_reader_eof_total 14224
telemt_me_idle_close_by_peer_total 14224
telemt_me_seq_mismatch_total 24
telemt_me_route_drop_no_conn_total 198341
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 531158
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 41
telemt_me_hardswap_pending_ttl_expired_total 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1452
telemt_desync_full_logged_total 380
telemt_desync_suppressed_total 1072
telemt_desync_frames_bucket_total{bucket="1_2"} 380
telemt_desync_frames_bucket_total{bucket="3_10"} 587
telemt_desync_frames_bucket_total{bucket="gt_10"} 485
telemt_pool_swap_total 19
telemt_me_writer_removed_unexpected_total 13999
telemt_me_refill_failed_total 1265
telemt_me_writer_restored_same_endpoint_total 12573
telemt_me_writer_restored_fallback_total 35
telemt_me_async_recovery_trigger_total 96
telemt_me_writer_removed_unexpected_minus_restored_total 1391
telemt_user_connections_total{user="hello"} 682809
telemt_user_connections_current{user="hello"} 956
telemt_user_octets_from_client{user="hello"} 13355816654 (12.44 GB)
telemt_user_octets_to_client{user="hello"} 240014040157 (223.53 GB)
telemt_user_msgs_from_client{user="hello"} 3034166
telemt_user_msgs_to_client{user="hello"} 10923814
telemt_user_unique_ips_current{user="hello"} 257
telemt_user_unique_ips_recent_window{user="hello"} 135
```

## server5

```
telemt 3.3.18

telemt_uptime_seconds 64076.3 (17h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 895022
telemt_connections_bad_total 9493
telemt_handshake_timeouts_total 19722
telemt_upstream_connect_attempt_total 14307
telemt_upstream_connect_success_total 14227
telemt_upstream_connect_fail_total 80
telemt_upstream_connect_attempts_per_request{bucket="1"} 14307
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6584
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7630
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 13
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 80
telemt_me_keepalive_timeout_total 86
telemt_me_reconnect_attempts_total 14674
telemt_me_reconnect_success_total 10989
telemt_me_reader_eof_total 11719
telemt_me_idle_close_by_peer_total 11719
telemt_me_route_drop_no_conn_total 222992
telemt_me_route_drop_channel_closed_total 24
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 738140
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2565
telemt_desync_full_logged_total 868
telemt_desync_suppressed_total 1697
telemt_desync_frames_bucket_total{bucket="1_2"} 782
telemt_desync_frames_bucket_total{bucket="3_10"} 975
telemt_desync_frames_bucket_total{bucket="gt_10"} 808
telemt_pool_swap_total 52
telemt_me_writer_removed_unexpected_total 11236
telemt_me_refill_failed_total 113
telemt_me_writer_restored_same_endpoint_total 10981
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 54
telemt_me_writer_removed_unexpected_minus_restored_total 247
telemt_user_connections_total{user="hello"} 738181
telemt_user_connections_current{user="hello"} 905
telemt_user_octets_from_client{user="hello"} 9090504472 (8.47 GB)
telemt_user_octets_to_client{user="hello"} 264879770616 (246.69 GB)
telemt_user_unique_ips_current{user="hello"} 238
telemt_user_unique_ips_recent_window{user="hello"} 147
```