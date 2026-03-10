# Server Metrics 2026-03-10 16:06:38 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 5973.3 (1h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 216975
telemt_connections_bad_total 917
telemt_handshake_timeouts_total 1009
telemt_upstream_connect_attempt_total 1164
telemt_upstream_connect_success_total 1158
telemt_upstream_connect_fail_total 6
telemt_upstream_connect_attempts_per_request{bucket="1"} 1164
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 479
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 659
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 20
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 6
telemt_me_keepalive_timeout_total 102
telemt_me_reconnect_attempts_total 6230
telemt_me_reconnect_success_total 814
telemt_me_reader_eof_total 939
telemt_me_idle_close_by_peer_total 939
telemt_me_route_drop_no_conn_total 97663
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 206963
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 757
telemt_desync_full_logged_total 208
telemt_desync_suppressed_total 549
telemt_desync_frames_bucket_total{bucket="1_2"} 177
telemt_desync_frames_bucket_total{bucket="3_10"} 281
telemt_desync_frames_bucket_total{bucket="gt_10"} 299
telemt_me_writer_removed_unexpected_total 972
telemt_me_refill_failed_total 169
telemt_me_writer_restored_same_endpoint_total 808
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 158
telemt_user_connections_total{user="hello"} 206908
telemt_user_connections_current{user="hello"} 1345
telemt_user_octets_from_client{user="hello"} 2602955784 (2.42 GB)
telemt_user_octets_to_client{user="hello"} 60294147040 (56.15 GB)
telemt_user_unique_ips_current{user="hello"} 345
telemt_user_unique_ips_recent_window{user="hello"} 162
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 6030.0 (1h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 86204
telemt_connections_bad_total 1510
telemt_handshake_timeouts_total 7065
telemt_upstream_connect_attempt_total 1356
telemt_upstream_connect_success_total 1348
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 1356
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 715
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 631
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 15
telemt_me_reconnect_attempts_total 1015
telemt_me_reconnect_success_total 1008
telemt_me_reader_eof_total 1017
telemt_me_idle_close_by_peer_total 1017
telemt_me_route_drop_no_conn_total 23053
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 72631
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 438
telemt_desync_full_logged_total 114
telemt_desync_suppressed_total 324
telemt_desync_frames_bucket_total{bucket="1_2"} 196
telemt_desync_frames_bucket_total{bucket="3_10"} 133
telemt_desync_frames_bucket_total{bucket="gt_10"} 109
telemt_pool_swap_total 3
telemt_me_writer_removed_unexpected_total 1010
telemt_me_writer_restored_same_endpoint_total 987
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 86
telemt_me_writer_removed_unexpected_minus_restored_total 2
telemt_user_connections_total{user="hello"} 72618
telemt_user_connections_current{user="hello"} 568
telemt_user_octets_from_client{user="hello"} 889983280 (848.75 MB)
telemt_user_octets_to_client{user="hello"} 20192131284 (18.81 GB)
telemt_user_unique_ips_current{user="hello"} 160
telemt_user_unique_ips_recent_window{user="hello"} 90
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 6029.8 (1h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 155709
telemt_connections_bad_total 410
telemt_handshake_timeouts_total 12779
telemt_upstream_connect_attempt_total 2456
telemt_upstream_connect_success_total 2411
telemt_upstream_connect_fail_total 45
telemt_upstream_connect_attempts_per_request{bucket="1"} 2456
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1689
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 715
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 45
telemt_me_keepalive_timeout_total 28
telemt_me_reconnect_attempts_total 1062
telemt_me_reconnect_success_total 1038
telemt_me_reader_eof_total 1071
telemt_me_idle_close_by_peer_total 1071
telemt_me_route_drop_no_conn_total 50295
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 128126
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 279
telemt_desync_full_logged_total 90
telemt_desync_suppressed_total 189
telemt_desync_frames_bucket_total{bucket="1_2"} 72
telemt_desync_frames_bucket_total{bucket="3_10"} 99
telemt_desync_frames_bucket_total{bucket="gt_10"} 108
telemt_pool_swap_total 4
telemt_me_writer_removed_unexpected_total 1057
telemt_me_writer_restored_same_endpoint_total 1027
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 19
telemt_user_connections_total{user="hello"} 129112
telemt_user_connections_current{user="hello"} 849
telemt_user_octets_from_client{user="hello"} 1651904329 (1.54 GB)
telemt_user_octets_to_client{user="hello"} 37872373517 (35.27 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 243
telemt_user_unique_ips_recent_window{user="hello"} 142
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 6030.4 (1h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 100691
telemt_connections_bad_total 5995
telemt_handshake_timeouts_total 10265
telemt_upstream_connect_attempt_total 1477
telemt_upstream_connect_success_total 1477
telemt_upstream_connect_attempts_per_request{bucket="1"} 1477
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 813
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 664
telemt_me_keepalive_timeout_total 32
telemt_me_reconnect_attempts_total 1146
telemt_me_reconnect_success_total 1140
telemt_me_reader_eof_total 1145
telemt_me_idle_close_by_peer_total 1145
telemt_me_route_drop_no_conn_total 33483
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 79841
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 255
telemt_desync_full_logged_total 104
telemt_desync_suppressed_total 151
telemt_desync_frames_bucket_total{bucket="1_2"} 90
telemt_desync_frames_bucket_total{bucket="3_10"} 94
telemt_desync_frames_bucket_total{bucket="gt_10"} 71
telemt_pool_swap_total 4
telemt_me_writer_removed_unexpected_total 1140
telemt_me_writer_restored_same_endpoint_total 1129
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 36
telemt_user_connections_total{user="hello"} 79744
telemt_user_connections_current{user="hello"} 599
telemt_user_octets_from_client{user="hello"} 1275315132 (1.19 GB)
telemt_user_octets_to_client{user="hello"} 18964298192 (17.66 GB)
telemt_user_unique_ips_current{user="hello"} 144
telemt_user_unique_ips_recent_window{user="hello"} 91
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 6029.9 (1h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 110982
telemt_connections_bad_total 8
telemt_handshake_timeouts_total 817
telemt_upstream_connect_attempt_total 1701
telemt_upstream_connect_success_total 1695
telemt_upstream_connect_fail_total 6
telemt_upstream_connect_attempts_per_request{bucket="1"} 1701
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 914
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 771
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 6
telemt_me_keepalive_timeout_total 31
telemt_me_reconnect_attempts_total 1355
telemt_me_reconnect_success_total 1346
telemt_me_reader_eof_total 1366
telemt_me_idle_close_by_peer_total 1366
telemt_me_route_drop_no_conn_total 41299
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 103178
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 559
telemt_desync_full_logged_total 184
telemt_desync_suppressed_total 375
telemt_desync_frames_bucket_total{bucket="1_2"} 235
telemt_desync_frames_bucket_total{bucket="3_10"} 243
telemt_desync_frames_bucket_total{bucket="gt_10"} 81
telemt_pool_swap_total 2
telemt_me_writer_removed_unexpected_total 1351
telemt_me_writer_restored_same_endpoint_total 1346
telemt_me_async_recovery_trigger_total 48
telemt_me_writer_removed_unexpected_minus_restored_total 5
telemt_user_connections_total{user="hello"} 103130
telemt_user_connections_current{user="hello"} 633
telemt_user_octets_from_client{user="hello"} 1787999316 (1.67 GB)
telemt_user_octets_to_client{user="hello"} 29985750620 (27.93 GB)
telemt_user_unique_ips_current{user="hello"} 185
telemt_user_unique_ips_recent_window{user="hello"} 109
```