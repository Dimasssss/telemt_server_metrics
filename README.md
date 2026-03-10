# Server Metrics 2026-03-10 16:27:03 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 7199.2 (1h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 254087
telemt_connections_bad_total 1353
telemt_handshake_timeouts_total 1129
telemt_upstream_connect_attempt_total 1296
telemt_upstream_connect_success_total 1288
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 1296
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 549
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 718
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 21
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 123
telemt_me_reconnect_attempts_total 7659
telemt_me_reconnect_success_total 899
telemt_me_reader_eof_total 1064
telemt_me_idle_close_by_peer_total 1064
telemt_me_route_drop_no_conn_total 113176
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 242815
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 920
telemt_desync_full_logged_total 252
telemt_desync_suppressed_total 668
telemt_desync_frames_bucket_total{bucket="1_2"} 229
telemt_desync_frames_bucket_total{bucket="3_10"} 332
telemt_desync_frames_bucket_total{bucket="gt_10"} 359
telemt_me_writer_removed_unexpected_total 1100
telemt_me_refill_failed_total 211
telemt_me_writer_restored_same_endpoint_total 893
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 201
telemt_user_connections_total{user="hello"} 242761
telemt_user_connections_current{user="hello"} 1303
telemt_user_octets_from_client{user="hello"} 2979641532 (2.78 GB)
telemt_user_octets_to_client{user="hello"} 71707310612 (66.78 GB)
telemt_user_unique_ips_current{user="hello"} 355
telemt_user_unique_ips_recent_window{user="hello"} 168
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 7255.8 (2h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 102974
telemt_connections_bad_total 1670
telemt_handshake_timeouts_total 8089
telemt_upstream_connect_attempt_total 1627
telemt_upstream_connect_success_total 1617
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 1627
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 859
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 756
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_keepalive_timeout_total 30
telemt_me_reconnect_attempts_total 1221
telemt_me_reconnect_success_total 1212
telemt_me_reader_eof_total 1239
telemt_me_idle_close_by_peer_total 1239
telemt_me_route_drop_no_conn_total 27876
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 87571
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 491
telemt_desync_full_logged_total 131
telemt_desync_suppressed_total 360
telemt_desync_frames_bucket_total{bucket="1_2"} 197
telemt_desync_frames_bucket_total{bucket="3_10"} 164
telemt_desync_frames_bucket_total{bucket="gt_10"} 130
telemt_pool_swap_total 4
telemt_me_writer_removed_unexpected_total 1215
telemt_me_writer_restored_same_endpoint_total 1191
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 86
telemt_me_writer_removed_unexpected_minus_restored_total 3
telemt_user_connections_total{user="hello"} 87557
telemt_user_connections_current{user="hello"} 529
telemt_user_octets_from_client{user="hello"} 1048648204 (1000.07 MB)
telemt_user_octets_to_client{user="hello"} 24069928380 (22.42 GB)
telemt_user_unique_ips_current{user="hello"} 159
telemt_user_unique_ips_recent_window{user="hello"} 76
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 7256.0 (2h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 183305
telemt_connections_bad_total 508
telemt_handshake_timeouts_total 14964
telemt_upstream_connect_attempt_total 2737
telemt_upstream_connect_success_total 2690
telemt_upstream_connect_fail_total 47
telemt_upstream_connect_attempts_per_request{bucket="1"} 2737
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1842
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 840
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 47
telemt_me_keepalive_timeout_total 31
telemt_me_reconnect_attempts_total 1274
telemt_me_reconnect_success_total 1246
telemt_me_reader_eof_total 1284
telemt_me_idle_close_by_peer_total 1284
telemt_me_route_drop_no_conn_total 60355
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 152972
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 367
telemt_desync_full_logged_total 107
telemt_desync_suppressed_total 260
telemt_desync_frames_bucket_total{bucket="1_2"} 95
telemt_desync_frames_bucket_total{bucket="3_10"} 130
telemt_desync_frames_bucket_total{bucket="gt_10"} 142
telemt_pool_swap_total 4
telemt_me_writer_removed_unexpected_total 1270
telemt_me_writer_restored_same_endpoint_total 1235
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 24
telemt_user_connections_total{user="hello"} 153952
telemt_user_connections_current{user="hello"} 742
telemt_user_octets_from_client{user="hello"} 2022815717 (1.88 GB)
telemt_user_octets_to_client{user="hello"} 45370024361 (42.25 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 216
telemt_user_unique_ips_recent_window{user="hello"} 120
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 7256.2 (2h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 119230
telemt_connections_bad_total 7263
telemt_handshake_timeouts_total 11956
telemt_upstream_connect_attempt_total 1792
telemt_upstream_connect_success_total 1792
telemt_upstream_connect_attempts_per_request{bucket="1"} 1792
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 966
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 826
telemt_me_keepalive_timeout_total 38
telemt_me_reconnect_attempts_total 1397
telemt_me_reconnect_success_total 1390
telemt_me_reader_eof_total 1426
telemt_me_idle_close_by_peer_total 1426
telemt_me_route_drop_no_conn_total 39220
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 94830
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 291
telemt_desync_full_logged_total 114
telemt_desync_suppressed_total 177
telemt_desync_frames_bucket_total{bucket="1_2"} 103
telemt_desync_frames_bucket_total{bucket="3_10"} 104
telemt_desync_frames_bucket_total{bucket="gt_10"} 84
telemt_pool_swap_total 5
telemt_me_writer_removed_unexpected_total 1396
telemt_me_writer_restored_same_endpoint_total 1379
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 6
telemt_user_connections_total{user="hello"} 94705
telemt_user_connections_current{user="hello"} 519
telemt_user_octets_from_client{user="hello"} 1471833528 (1.37 GB)
telemt_user_octets_to_client{user="hello"} 23829291772 (22.19 GB)
telemt_user_unique_ips_current{user="hello"} 133
telemt_user_unique_ips_recent_window{user="hello"} 61
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 7256.0 (2h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 130310
telemt_connections_bad_total 372
telemt_handshake_timeouts_total 866
telemt_upstream_connect_attempt_total 2085
telemt_upstream_connect_success_total 2079
telemt_upstream_connect_fail_total 6
telemt_upstream_connect_attempts_per_request{bucket="1"} 2085
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1090
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 974
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 15
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 6
telemt_me_keepalive_timeout_total 53
telemt_me_reconnect_attempts_total 1681
telemt_me_reconnect_success_total 1670
telemt_me_reader_eof_total 1693
telemt_me_idle_close_by_peer_total 1693
telemt_me_route_drop_no_conn_total 48964
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 121611
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 646
telemt_desync_full_logged_total 218
telemt_desync_suppressed_total 428
telemt_desync_frames_bucket_total{bucket="1_2"} 278
telemt_desync_frames_bucket_total{bucket="3_10"} 273
telemt_desync_frames_bucket_total{bucket="gt_10"} 95
telemt_pool_swap_total 2
telemt_me_writer_removed_unexpected_total 1681
telemt_me_writer_restored_same_endpoint_total 1670
telemt_me_async_recovery_trigger_total 48
telemt_me_writer_removed_unexpected_minus_restored_total 11
telemt_user_connections_total{user="hello"} 121561
telemt_user_connections_current{user="hello"} 591
telemt_user_octets_from_client{user="hello"} 2062763428 (1.92 GB)
telemt_user_octets_to_client{user="hello"} 37609566668 (35.03 GB)
telemt_user_unique_ips_current{user="hello"} 176
telemt_user_unique_ips_recent_window{user="hello"} 95
```