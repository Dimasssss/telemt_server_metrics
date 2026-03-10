# Server Metrics 2026-03-10 16:01:31 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 5666.6 (1h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 205607
telemt_connections_bad_total 868
telemt_handshake_timeouts_total 969
telemt_upstream_connect_attempt_total 1141
telemt_upstream_connect_success_total 1135
telemt_upstream_connect_fail_total 6
telemt_upstream_connect_attempts_per_request{bucket="1"} 1141
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 466
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 649
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 20
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 6
telemt_me_keepalive_timeout_total 102
telemt_me_reconnect_attempts_total 6207
telemt_me_reconnect_success_total 791
telemt_me_reader_eof_total 916
telemt_me_idle_close_by_peer_total 916
telemt_me_route_drop_no_conn_total 92349
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 195876
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 686
telemt_desync_full_logged_total 190
telemt_desync_suppressed_total 496
telemt_desync_frames_bucket_total{bucket="1_2"} 158
telemt_desync_frames_bucket_total{bucket="3_10"} 259
telemt_desync_frames_bucket_total{bucket="gt_10"} 269
telemt_me_writer_removed_unexpected_total 949
telemt_me_refill_failed_total 169
telemt_me_writer_restored_same_endpoint_total 785
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 158
telemt_user_connections_total{user="hello"} 195823
telemt_user_connections_current{user="hello"} 1557
telemt_user_octets_from_client{user="hello"} 2493066608 (2.32 GB)
telemt_user_octets_to_client{user="hello"} 56185275720 (52.33 GB)
telemt_user_unique_ips_current{user="hello"} 387
telemt_user_unique_ips_recent_window{user="hello"} 247
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 5723.3 (1h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 81802
telemt_connections_bad_total 1499
telemt_handshake_timeouts_total 6888
telemt_upstream_connect_attempt_total 1283
telemt_upstream_connect_success_total 1275
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 1283
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 681
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 593
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 15
telemt_me_reconnect_attempts_total 942
telemt_me_reconnect_success_total 935
telemt_me_reader_eof_total 944
telemt_me_idle_close_by_peer_total 944
telemt_me_route_drop_no_conn_total 21545
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 68645
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 404
telemt_desync_full_logged_total 103
telemt_desync_suppressed_total 301
telemt_desync_frames_bucket_total{bucket="1_2"} 190
telemt_desync_frames_bucket_total{bucket="3_10"} 122
telemt_desync_frames_bucket_total{bucket="gt_10"} 92
telemt_pool_swap_total 3
telemt_me_writer_removed_unexpected_total 937
telemt_me_writer_restored_same_endpoint_total 914
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 86
telemt_me_writer_removed_unexpected_minus_restored_total 2
telemt_user_connections_total{user="hello"} 68632
telemt_user_connections_current{user="hello"} 565
telemt_user_octets_from_client{user="hello"} 854843900 (815.24 MB)
telemt_user_octets_to_client{user="hello"} 19180695464 (17.86 GB)
telemt_user_unique_ips_current{user="hello"} 168
telemt_user_unique_ips_recent_window{user="hello"} 100
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 5723.2 (1h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 148472
telemt_connections_bad_total 409
telemt_handshake_timeouts_total 11512
telemt_upstream_connect_attempt_total 2430
telemt_upstream_connect_success_total 2385
telemt_upstream_connect_fail_total 45
telemt_upstream_connect_attempts_per_request{bucket="1"} 2430
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1676
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 702
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 45
telemt_me_keepalive_timeout_total 20
telemt_me_reconnect_attempts_total 1036
telemt_me_reconnect_success_total 1012
telemt_me_reader_eof_total 1043
telemt_me_idle_close_by_peer_total 1043
telemt_me_route_drop_no_conn_total 47057
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 121797
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 255
telemt_desync_full_logged_total 81
telemt_desync_suppressed_total 174
telemt_desync_frames_bucket_total{bucket="1_2"} 61
telemt_desync_frames_bucket_total{bucket="3_10"} 89
telemt_desync_frames_bucket_total{bucket="gt_10"} 105
telemt_pool_swap_total 4
telemt_me_writer_removed_unexpected_total 1029
telemt_me_writer_restored_same_endpoint_total 1001
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 17
telemt_user_connections_total{user="hello"} 122792
telemt_user_connections_current{user="hello"} 848
telemt_user_octets_from_client{user="hello"} 1510173769 (1.41 GB)
telemt_user_octets_to_client{user="hello"} 35734856901 (33.28 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 240
telemt_user_unique_ips_recent_window{user="hello"} 144
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 5723.9 (1h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 95059
telemt_connections_bad_total 5681
telemt_handshake_timeouts_total 9604
telemt_upstream_connect_attempt_total 1362
telemt_upstream_connect_success_total 1362
telemt_upstream_connect_attempts_per_request{bucket="1"} 1362
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 756
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 606
telemt_me_keepalive_timeout_total 31
telemt_me_reconnect_attempts_total 1031
telemt_me_reconnect_success_total 1026
telemt_me_reader_eof_total 1029
telemt_me_idle_close_by_peer_total 1029
telemt_me_route_drop_no_conn_total 31534
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 75441
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 238
telemt_desync_full_logged_total 101
telemt_desync_suppressed_total 137
telemt_desync_frames_bucket_total{bucket="1_2"} 89
telemt_desync_frames_bucket_total{bucket="3_10"} 88
telemt_desync_frames_bucket_total{bucket="gt_10"} 61
telemt_pool_swap_total 4
telemt_me_writer_removed_unexpected_total 1024
telemt_me_writer_restored_same_endpoint_total 1015
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 36
telemt_user_connections_total{user="hello"} 75360
telemt_user_connections_current{user="hello"} 557
telemt_user_octets_from_client{user="hello"} 1235142300 (1.15 GB)
telemt_user_octets_to_client{user="hello"} 17851391896 (16.63 GB)
telemt_user_unique_ips_current{user="hello"} 159
telemt_user_unique_ips_recent_window{user="hello"} 105
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 5723.3 (1h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 104811
telemt_connections_bad_total 8
telemt_handshake_timeouts_total 809
telemt_upstream_connect_attempt_total 1644
telemt_upstream_connect_success_total 1638
telemt_upstream_connect_fail_total 6
telemt_upstream_connect_attempts_per_request{bucket="1"} 1644
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 889
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 739
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 6
telemt_me_keepalive_timeout_total 29
telemt_me_reconnect_attempts_total 1298
telemt_me_reconnect_success_total 1289
telemt_me_reader_eof_total 1309
telemt_me_idle_close_by_peer_total 1309
telemt_me_route_drop_no_conn_total 38872
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 97276
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 538
telemt_desync_full_logged_total 176
telemt_desync_suppressed_total 362
telemt_desync_frames_bucket_total{bucket="1_2"} 225
telemt_desync_frames_bucket_total{bucket="3_10"} 233
telemt_desync_frames_bucket_total{bucket="gt_10"} 80
telemt_pool_swap_total 2
telemt_me_writer_removed_unexpected_total 1294
telemt_me_writer_restored_same_endpoint_total 1289
telemt_me_async_recovery_trigger_total 48
telemt_me_writer_removed_unexpected_minus_restored_total 5
telemt_user_connections_total{user="hello"} 97230
telemt_user_connections_current{user="hello"} 587
telemt_user_octets_from_client{user="hello"} 1599976716 (1.49 GB)
telemt_user_octets_to_client{user="hello"} 27745740664 (25.84 GB)
telemt_user_unique_ips_current{user="hello"} 183
telemt_user_unique_ips_recent_window{user="hello"} 122
```