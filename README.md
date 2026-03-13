# Server Metrics 2026-03-13 10:55:02 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 104185.0 (28h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3037093
telemt_connections_bad_total 36458
telemt_handshake_timeouts_total 54427
telemt_upstream_connect_attempt_total 20541
telemt_upstream_connect_success_total 20430
telemt_upstream_connect_fail_total 111
telemt_upstream_connect_attempts_per_request{bucket="1"} 20541
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10498
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9878
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 54
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 111
telemt_me_keepalive_timeout_total 1453
telemt_me_reconnect_attempts_total 25326
telemt_me_reconnect_success_total 15253
telemt_me_reader_eof_total 16418
telemt_me_idle_close_by_peer_total 16417
telemt_me_route_drop_no_conn_total 1120757
telemt_me_route_drop_channel_closed_total 16
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2773219
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 12042
telemt_desync_full_logged_total 3104
telemt_desync_suppressed_total 8938
telemt_desync_frames_bucket_total{bucket="1_2"} 3076
telemt_desync_frames_bucket_total{bucket="3_10"} 4514
telemt_desync_frames_bucket_total{bucket="gt_10"} 4452
telemt_pool_swap_total 85
telemt_me_writer_removed_unexpected_total 15778
telemt_me_refill_failed_total 312
telemt_me_writer_restored_same_endpoint_total 15240
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 525
telemt_user_connections_total{user="hello"} 2773155
telemt_user_connections_current{user="hello"} 1774
telemt_user_octets_from_client{user="hello"} 38138045772 (35.52 GB)
telemt_user_octets_to_client{user="hello"} 900186799108 (838.36 GB)
telemt_user_unique_ips_current{user="hello"} 458
telemt_user_unique_ips_recent_window{user="hello"} 221
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 3848.9 (1h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 43562
telemt_connections_bad_total 3615
telemt_handshake_timeouts_total 1024
telemt_upstream_connect_attempt_total 1065
telemt_upstream_connect_success_total 997
telemt_upstream_connect_fail_total 68
telemt_upstream_connect_attempts_per_request{bucket="1"} 1065
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 489
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 503
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 68
telemt_me_keepalive_timeout_total 8
telemt_me_reconnect_attempts_total 809
telemt_me_reconnect_success_total 739
telemt_me_reader_eof_total 728
telemt_me_idle_close_by_peer_total 728
telemt_me_route_drop_no_conn_total 14684
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 37901
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 122
telemt_desync_full_logged_total 36
telemt_desync_suppressed_total 86
telemt_desync_frames_bucket_total{bucket="1_2"} 26
telemt_desync_frames_bucket_total{bucket="3_10"} 38
telemt_desync_frames_bucket_total{bucket="gt_10"} 58
telemt_pool_swap_total 2
telemt_me_writer_removed_unexpected_total 735
telemt_me_writer_restored_same_endpoint_total 732
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 22
telemt_user_connections_total{user="hello"} 37900
telemt_user_connections_current{user="hello"} 543
telemt_user_octets_from_client{user="hello"} 452811724 (431.83 MB)
telemt_user_octets_to_client{user="hello"} 8789896240 (8.19 GB)
telemt_user_unique_ips_current{user="hello"} 159
telemt_user_unique_ips_recent_window{user="hello"} 72
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 133805.5 (37h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2343340
telemt_connections_bad_total 25111
telemt_handshake_timeouts_total 158271
telemt_upstream_connect_attempt_total 30475
telemt_upstream_connect_success_total 30465
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 30475
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15957
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14387
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 116
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_keepalive_timeout_total 1903
telemt_me_reconnect_attempts_total 24754
telemt_me_reconnect_success_total 23463
telemt_me_reader_eof_total 24858
telemt_me_idle_close_by_peer_total 24857
telemt_me_route_drop_no_conn_total 770134
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1886332
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 6212
telemt_desync_full_logged_total 1983
telemt_desync_suppressed_total 4229
telemt_desync_frames_bucket_total{bucket="1_2"} 1001
telemt_desync_frames_bucket_total{bucket="3_10"} 2265
telemt_desync_frames_bucket_total{bucket="gt_10"} 2946
telemt_pool_swap_total 126
telemt_me_writer_removed_unexpected_total 23697
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 23422
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 234
telemt_user_connections_total{user="hello"} 1885757
telemt_user_connections_current{user="hello"} 943
telemt_user_octets_from_client{user="hello"} 32356889328 (30.13 GB)
telemt_user_octets_to_client{user="hello"} 677268879793 (630.76 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 292
telemt_user_unique_ips_recent_window{user="hello"} 133
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 133805.9 (37h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1481014
telemt_connections_bad_total 14245
telemt_handshake_timeouts_total 94164
telemt_upstream_connect_attempt_total 43544
telemt_upstream_connect_success_total 41231
telemt_upstream_connect_fail_total 2176
telemt_upstream_connect_attempts_per_request{bucket="1"} 43270
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 25017
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16123
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 91
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2175
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 11513
telemt_me_reconnect_attempts_total 37673
telemt_me_reconnect_success_total 28720
telemt_me_reader_eof_total 30906
telemt_me_idle_close_by_peer_total 30899
telemt_me_route_drop_no_conn_total 525006
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1238985
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2312
telemt_desync_full_logged_total 770
telemt_desync_suppressed_total 1542
telemt_desync_frames_bucket_total{bucket="1_2"} 645
telemt_desync_frames_bucket_total{bucket="3_10"} 877
telemt_desync_frames_bucket_total{bucket="gt_10"} 790
telemt_pool_swap_total 116
telemt_me_writer_removed_unexpected_total 29209
telemt_me_refill_failed_total 274
telemt_me_writer_restored_same_endpoint_total 28696
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 489
telemt_user_connections_total{user="hello"} 1243713
telemt_user_connections_current{user="hello"} 582
telemt_user_octets_from_client{user="hello"} 18822469897 (17.53 GB)
telemt_user_octets_to_client{user="hello"} 490872348542 (457.16 GB)
telemt_user_msgs_from_client{user="hello"} 44500
telemt_user_msgs_to_client{user="hello"} 116355
telemt_user_unique_ips_current{user="hello"} 186
telemt_user_unique_ips_recent_window{user="hello"} 99
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 3241.8 (0h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 39829
telemt_connections_bad_total 12
telemt_handshake_timeouts_total 210
telemt_upstream_connect_attempt_total 875
telemt_upstream_connect_success_total 850
telemt_upstream_connect_fail_total 25
telemt_upstream_connect_attempts_per_request{bucket="1"} 875
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 364
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 486
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 25
telemt_me_keepalive_timeout_total 11
telemt_me_reconnect_attempts_total 1866
telemt_me_reconnect_success_total 643
telemt_me_reader_eof_total 652
telemt_me_idle_close_by_peer_total 652
telemt_me_route_drop_no_conn_total 13334
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 38100
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 157
telemt_desync_full_logged_total 53
telemt_desync_suppressed_total 104
telemt_desync_frames_bucket_total{bucket="1_2"} 67
telemt_desync_frames_bucket_total{bucket="3_10"} 53
telemt_desync_frames_bucket_total{bucket="gt_10"} 37
telemt_me_writer_removed_unexpected_total 673
telemt_me_refill_failed_total 38
telemt_me_writer_restored_same_endpoint_total 640
telemt_me_writer_restored_fallback_total 3
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 30
telemt_user_connections_total{user="hello"} 38093
telemt_user_connections_current{user="hello"} 788
telemt_user_octets_from_client{user="hello"} 356039012 (339.55 MB)
telemt_user_octets_to_client{user="hello"} 14507362316 (13.51 GB)
telemt_user_unique_ips_current{user="hello"} 200
telemt_user_unique_ips_recent_window{user="hello"} 114
```