# Server Metrics 2026-03-11 18:00:29 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 99203.4 (27h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2511009
telemt_connections_bad_total 47969
telemt_handshake_timeouts_total 55992
telemt_upstream_connect_attempt_total 20918
telemt_upstream_connect_success_total 20906
telemt_upstream_connect_fail_total 12
telemt_upstream_connect_attempts_per_request{bucket="1"} 20918
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10564
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10240
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 101
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 12
telemt_me_keepalive_timeout_total 5240
telemt_me_reconnect_attempts_total 33746
telemt_me_reconnect_success_total 15866
telemt_me_reader_eof_total 17168
telemt_me_idle_close_by_peer_total 17168
telemt_me_route_drop_no_conn_total 934836
telemt_me_route_drop_channel_closed_total 8
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2296347
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 11778
telemt_desync_full_logged_total 3239
telemt_desync_suppressed_total 8539
telemt_desync_frames_bucket_total{bucket="1_2"} 2909
telemt_desync_frames_bucket_total{bucket="3_10"} 4552
telemt_desync_frames_bucket_total{bucket="gt_10"} 4317
telemt_pool_swap_total 71
telemt_me_writer_removed_unexpected_total 16604
telemt_me_refill_failed_total 555
telemt_me_writer_restored_same_endpoint_total 15860
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 738
telemt_user_connections_total{user="hello"} 2294791
telemt_user_connections_current{user="hello"} 1296
telemt_user_octets_from_client{user="hello"} 31402563176 (29.25 GB)
telemt_user_octets_to_client{user="hello"} 648683227228 (604.13 GB)
telemt_user_unique_ips_current{user="hello"} 346
telemt_user_unique_ips_recent_window{user="hello"} 221
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 99260.0 (27h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 943361
telemt_connections_bad_total 16343
telemt_handshake_timeouts_total 84001
telemt_upstream_connect_attempt_total 31045
telemt_upstream_connect_success_total 28079
telemt_upstream_connect_fail_total 2966
telemt_upstream_connect_attempts_per_request{bucket="1"} 31045
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13230
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12600
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 209
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2040
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2966
telemt_me_keepalive_timeout_total 2762
telemt_me_reconnect_attempts_total 22231
telemt_me_reconnect_success_total 20121
telemt_me_reader_eof_total 21296
telemt_me_idle_close_by_peer_total 21293
telemt_me_route_drop_no_conn_total 356180
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 785900
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3092
telemt_desync_full_logged_total 991
telemt_desync_suppressed_total 2101
telemt_desync_frames_bucket_total{bucket="1_2"} 947
telemt_desync_frames_bucket_total{bucket="3_10"} 1106
telemt_desync_frames_bucket_total{bucket="gt_10"} 1039
telemt_pool_swap_total 80
telemt_me_writer_removed_unexpected_total 20401
telemt_me_refill_failed_total 60
telemt_me_writer_restored_same_endpoint_total 20098
telemt_me_writer_restored_fallback_total 23
telemt_me_async_recovery_trigger_total 86
telemt_me_writer_removed_unexpected_minus_restored_total 280
telemt_user_connections_total{user="hello"} 788362
telemt_user_connections_current{user="hello"} 513
telemt_user_octets_from_client{user="hello"} 9524984890 (8.87 GB)
telemt_user_octets_to_client{user="hello"} 223191842844 (207.86 GB)
telemt_user_msgs_from_client{user="hello"} 7933
telemt_user_msgs_to_client{user="hello"} 11226
telemt_user_unique_ips_current{user="hello"} 149
telemt_user_unique_ips_recent_window{user="hello"} 85
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 99260.0 (27h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1610883
telemt_connections_bad_total 9991
telemt_handshake_timeouts_total 130044
telemt_upstream_connect_attempt_total 25716
telemt_upstream_connect_success_total 25392
telemt_upstream_connect_fail_total 324
telemt_upstream_connect_attempts_per_request{bucket="1"} 25716
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13659
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11605
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 127
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 324
telemt_me_keepalive_timeout_total 1896
telemt_me_reconnect_attempts_total 45294
telemt_me_reconnect_success_total 19289
telemt_me_reader_eof_total 20948
telemt_me_idle_close_by_peer_total 20948
telemt_me_route_drop_no_conn_total 586642
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1409265
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 10
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3810
telemt_desync_full_logged_total 1111
telemt_desync_suppressed_total 2699
telemt_desync_frames_bucket_total{bucket="1_2"} 907
telemt_desync_frames_bucket_total{bucket="3_10"} 1453
telemt_desync_frames_bucket_total{bucket="gt_10"} 1450
telemt_pool_swap_total 55
telemt_me_writer_removed_unexpected_total 20367
telemt_me_refill_failed_total 807
telemt_me_writer_restored_same_endpoint_total 19277
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 1078
telemt_user_connections_total{user="hello"} 1408951
telemt_user_connections_current{user="hello"} 880
telemt_user_octets_from_client{user="hello"} 17410378505 (16.21 GB)
telemt_user_octets_to_client{user="hello"} 429056736321 (399.59 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 226
telemt_user_unique_ips_recent_window{user="hello"} 149
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 99260.5 (27h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1150157
telemt_connections_bad_total 77991
telemt_handshake_timeouts_total 107511
telemt_upstream_connect_attempt_total 26827
telemt_upstream_connect_success_total 26827
telemt_upstream_connect_attempts_per_request{bucket="1"} 26827
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14633
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12188
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 1277
telemt_me_reconnect_attempts_total 26453
telemt_me_reconnect_success_total 21848
telemt_me_reader_eof_total 23211
telemt_me_idle_close_by_peer_total 23210
telemt_me_seq_mismatch_total 23
telemt_me_route_drop_no_conn_total 381993
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 930723
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 34
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1957
telemt_desync_full_logged_total 749
telemt_desync_suppressed_total 1208
telemt_desync_frames_bucket_total{bucket="1_2"} 699
telemt_desync_frames_bucket_total{bucket="3_10"} 681
telemt_desync_frames_bucket_total{bucket="gt_10"} 577
telemt_pool_swap_total 81
telemt_me_writer_removed_unexpected_total 22224
telemt_me_refill_failed_total 141
telemt_me_writer_restored_same_endpoint_total 21815
telemt_me_writer_restored_fallback_total 33
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 376
telemt_user_connections_total{user="hello"} 930000
telemt_user_connections_current{user="hello"} 538
telemt_user_octets_from_client{user="hello"} 11188738592 (10.42 GB)
telemt_user_octets_to_client{user="hello"} 283033781740 (263.60 GB)
telemt_user_unique_ips_current{user="hello"} 154
telemt_user_unique_ips_recent_window{user="hello"} 111
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 3936.5 (1h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 70131
telemt_connections_bad_total 315
telemt_handshake_timeouts_total 409
telemt_upstream_connect_attempt_total 1235
telemt_upstream_connect_success_total 1235
telemt_upstream_connect_attempts_per_request{bucket="1"} 1235
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 708
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 515
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 12
telemt_me_keepalive_timeout_total 17
telemt_me_reconnect_attempts_total 989
telemt_me_reconnect_success_total 981
telemt_me_reader_eof_total 989
telemt_me_idle_close_by_peer_total 989
telemt_me_route_drop_no_conn_total 23418
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 65845
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 158
telemt_desync_full_logged_total 50
telemt_desync_suppressed_total 108
telemt_desync_frames_bucket_total{bucket="1_2"} 38
telemt_desync_frames_bucket_total{bucket="3_10"} 52
telemt_desync_frames_bucket_total{bucket="gt_10"} 68
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 987
telemt_me_writer_restored_same_endpoint_total 959
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 256
telemt_me_writer_removed_unexpected_minus_restored_total 6
telemt_user_connections_total{user="hello"} 65840
telemt_user_connections_current{user="hello"} 803
telemt_user_octets_from_client{user="hello"} 5966865916 (5.56 GB)
telemt_user_octets_to_client{user="hello"} 24459642444 (22.78 GB)
telemt_user_unique_ips_current{user="hello"} 189
telemt_user_unique_ips_recent_window{user="hello"} 139
```