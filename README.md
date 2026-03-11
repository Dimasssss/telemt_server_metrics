# Server Metrics 2026-03-11 19:52:42 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 105936.6 (29h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2689373
telemt_connections_bad_total 49511
telemt_handshake_timeouts_total 59979
telemt_upstream_connect_attempt_total 22380
telemt_upstream_connect_success_total 22368
telemt_upstream_connect_fail_total 12
telemt_upstream_connect_attempts_per_request{bucket="1"} 22380
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11296
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10961
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 110
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 12
telemt_me_keepalive_timeout_total 5398
telemt_me_reconnect_attempts_total 34898
telemt_me_reconnect_success_total 17005
telemt_me_reader_eof_total 18365
telemt_me_idle_close_by_peer_total 18365
telemt_me_route_drop_no_conn_total 1015560
telemt_me_route_drop_channel_closed_total 9
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2455532
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 12430
telemt_desync_full_logged_total 3447
telemt_desync_suppressed_total 8983
telemt_desync_frames_bucket_total{bucket="1_2"} 3053
telemt_desync_frames_bucket_total{bucket="3_10"} 4798
telemt_desync_frames_bucket_total{bucket="gt_10"} 4579
telemt_pool_swap_total 75
telemt_me_writer_removed_unexpected_total 17758
telemt_me_refill_failed_total 555
telemt_me_writer_restored_same_endpoint_total 16999
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 753
telemt_user_connections_total{user="hello"} 2453883
telemt_user_connections_current{user="hello"} 1052
telemt_user_octets_from_client{user="hello"} 36574509224 (34.06 GB)
telemt_user_octets_to_client{user="hello"} 697392270004 (649.50 GB)
telemt_user_unique_ips_current{user="hello"} 308
telemt_user_unique_ips_recent_window{user="hello"} 123
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 105993.2 (29h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 997811
telemt_connections_bad_total 16487
telemt_handshake_timeouts_total 90140
telemt_upstream_connect_attempt_total 32589
telemt_upstream_connect_success_total 29617
telemt_upstream_connect_fail_total 2972
telemt_upstream_connect_attempts_per_request{bucket="1"} 32589
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14005
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13332
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 209
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2071
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2972
telemt_me_keepalive_timeout_total 2867
telemt_me_reconnect_attempts_total 23462
telemt_me_reconnect_success_total 21342
telemt_me_reader_eof_total 22597
telemt_me_idle_close_by_peer_total 22594
telemt_me_route_drop_no_conn_total 377079
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 832462
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3319
telemt_desync_full_logged_total 1075
telemt_desync_suppressed_total 2244
telemt_desync_frames_bucket_total{bucket="1_2"} 1059
telemt_desync_frames_bucket_total{bucket="3_10"} 1180
telemt_desync_frames_bucket_total{bucket="gt_10"} 1080
telemt_pool_swap_total 85
telemt_me_writer_removed_unexpected_total 21654
telemt_me_refill_failed_total 60
telemt_me_writer_restored_same_endpoint_total 21319
telemt_me_writer_restored_fallback_total 23
telemt_me_async_recovery_trigger_total 86
telemt_me_writer_removed_unexpected_minus_restored_total 312
telemt_user_connections_total{user="hello"} 834913
telemt_user_connections_current{user="hello"} 377
telemt_user_octets_from_client{user="hello"} 10035252258 (9.35 GB)
telemt_user_octets_to_client{user="hello"} 242620061220 (225.96 GB)
telemt_user_msgs_from_client{user="hello"} 7933
telemt_user_msgs_to_client{user="hello"} 11226
telemt_user_unique_ips_current{user="hello"} 118
telemt_user_unique_ips_recent_window{user="hello"} 50
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 105993.2 (29h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1723084
telemt_connections_bad_total 10827
telemt_handshake_timeouts_total 134395
telemt_upstream_connect_attempt_total 27168
telemt_upstream_connect_success_total 26828
telemt_upstream_connect_fail_total 340
telemt_upstream_connect_attempts_per_request{bucket="1"} 27168
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14525
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12165
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 137
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 340
telemt_me_keepalive_timeout_total 2011
telemt_me_reconnect_attempts_total 54116
telemt_me_reconnect_success_total 20397
telemt_me_reader_eof_total 22308
telemt_me_idle_close_by_peer_total 22308
telemt_me_route_drop_no_conn_total 627374
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1513182
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4131
telemt_desync_full_logged_total 1219
telemt_desync_suppressed_total 2912
telemt_desync_frames_bucket_total{bucket="1_2"} 967
telemt_desync_frames_bucket_total{bucket="3_10"} 1570
telemt_desync_frames_bucket_total{bucket="gt_10"} 1594
telemt_pool_swap_total 55
telemt_me_writer_removed_unexpected_total 21730
telemt_me_refill_failed_total 1048
telemt_me_writer_restored_same_endpoint_total 20385
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 1333
telemt_user_connections_total{user="hello"} 1512825
telemt_user_connections_current{user="hello"} 677
telemt_user_octets_from_client{user="hello"} 19484533881 (18.15 GB)
telemt_user_octets_to_client{user="hello"} 462449173901 (430.69 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 207
telemt_user_unique_ips_recent_window{user="hello"} 99
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 105993.6 (29h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1230582
telemt_connections_bad_total 78219
telemt_handshake_timeouts_total 110991
telemt_upstream_connect_attempt_total 28594
telemt_upstream_connect_success_total 28594
telemt_upstream_connect_attempts_per_request{bucket="1"} 28594
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15572
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13016
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 1472
telemt_me_reconnect_attempts_total 27913
telemt_me_reconnect_success_total 23298
telemt_me_reader_eof_total 24736
telemt_me_idle_close_by_peer_total 24735
telemt_me_seq_mismatch_total 23
telemt_me_route_drop_no_conn_total 411754
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1005962
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 34
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2164
telemt_desync_full_logged_total 810
telemt_desync_suppressed_total 1354
telemt_desync_frames_bucket_total{bucket="1_2"} 770
telemt_desync_frames_bucket_total{bucket="3_10"} 730
telemt_desync_frames_bucket_total{bucket="gt_10"} 664
telemt_pool_swap_total 86
telemt_me_writer_removed_unexpected_total 23685
telemt_me_refill_failed_total 141
telemt_me_writer_restored_same_endpoint_total 23265
telemt_me_writer_restored_fallback_total 33
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 387
telemt_user_connections_total{user="hello"} 1005174
telemt_user_connections_current{user="hello"} 412
telemt_user_octets_from_client{user="hello"} 11941060160 (11.12 GB)
telemt_user_octets_to_client{user="hello"} 308311883412 (287.14 GB)
telemt_user_unique_ips_current{user="hello"} 129
telemt_user_unique_ips_recent_window{user="hello"} 66
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 10669.6 (2h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 167736
telemt_connections_bad_total 3303
telemt_handshake_timeouts_total 1490
telemt_upstream_connect_attempt_total 3051
telemt_upstream_connect_success_total 3050
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 3051
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1583
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1451
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 16
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 63
telemt_me_reconnect_attempts_total 2495
telemt_me_reconnect_success_total 2469
telemt_me_reader_eof_total 2541
telemt_me_idle_close_by_peer_total 2541
telemt_me_seq_mismatch_total 3
telemt_me_route_drop_no_conn_total 55731
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 148425
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 25
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 340
telemt_desync_full_logged_total 110
telemt_desync_suppressed_total 230
telemt_desync_frames_bucket_total{bucket="1_2"} 79
telemt_desync_frames_bucket_total{bucket="3_10"} 119
telemt_desync_frames_bucket_total{bucket="gt_10"} 142
telemt_pool_swap_total 4
telemt_me_writer_removed_unexpected_total 2496
telemt_me_writer_restored_same_endpoint_total 2444
telemt_me_writer_restored_fallback_total 25
telemt_me_async_recovery_trigger_total 256
telemt_me_writer_removed_unexpected_minus_restored_total 27
telemt_user_connections_total{user="hello"} 148391
telemt_user_connections_current{user="hello"} 466
telemt_user_octets_from_client{user="hello"} 9355026368 (8.71 GB)
telemt_user_octets_to_client{user="hello"} 49760623404 (46.34 GB)
telemt_user_unique_ips_current{user="hello"} 143
telemt_user_unique_ips_recent_window{user="hello"} 64
```