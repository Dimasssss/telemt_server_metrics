# Server Metrics 2026-03-10 21:48:23 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 26479.0 (7h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 709445
telemt_connections_bad_total 8155
telemt_handshake_timeouts_total 8198
telemt_upstream_connect_attempt_total 5742
telemt_upstream_connect_success_total 5733
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 5742
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2838
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2838
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 56
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 353
telemt_me_reconnect_attempts_total 15979
telemt_me_reconnect_success_total 4320
telemt_me_reader_eof_total 4779
telemt_me_idle_close_by_peer_total 4779
telemt_me_route_drop_no_conn_total 295845
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 670691
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3351
telemt_desync_full_logged_total 944
telemt_desync_suppressed_total 2407
telemt_desync_frames_bucket_total{bucket="1_2"} 955
telemt_desync_frames_bucket_total{bucket="3_10"} 1266
telemt_desync_frames_bucket_total{bucket="gt_10"} 1130
telemt_pool_swap_total 9
telemt_me_writer_removed_unexpected_total 4719
telemt_me_refill_failed_total 363
telemt_me_writer_restored_same_endpoint_total 4314
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 399
telemt_user_connections_total{user="hello"} 670496
telemt_user_connections_current{user="hello"} 588
telemt_user_octets_from_client{user="hello"} 9637731704 (8.98 GB)
telemt_user_octets_to_client{user="hello"} 202841823116 (188.91 GB)
telemt_user_unique_ips_current{user="hello"} 205
telemt_user_unique_ips_recent_window{user="hello"} 78
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 26535.7 (7h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 310196
telemt_connections_bad_total 2298
telemt_handshake_timeouts_total 17454
telemt_upstream_connect_attempt_total 12147
telemt_upstream_connect_success_total 9285
telemt_upstream_connect_fail_total 2862
telemt_upstream_connect_attempts_per_request{bucket="1"} 12147
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3880
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3165
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 209
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2031
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2862
telemt_me_keepalive_timeout_total 1369
telemt_me_reconnect_attempts_total 5765
telemt_me_reconnect_success_total 4960
telemt_me_reader_eof_total 5204
telemt_me_idle_close_by_peer_total 5202
telemt_me_route_drop_no_conn_total 163638
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 260634
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1528
telemt_desync_full_logged_total 425
telemt_desync_suppressed_total 1103
telemt_desync_frames_bucket_total{bucket="1_2"} 474
telemt_desync_frames_bucket_total{bucket="3_10"} 539
telemt_desync_frames_bucket_total{bucket="gt_10"} 515
telemt_pool_swap_total 18
telemt_me_writer_removed_unexpected_total 5044
telemt_me_refill_failed_total 22
telemt_me_writer_restored_same_endpoint_total 4939
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 86
telemt_me_writer_removed_unexpected_minus_restored_total 84
telemt_user_connections_total{user="hello"} 262907
telemt_user_connections_current{user="hello"} 160
telemt_user_octets_from_client{user="hello"} 2623108426 (2.44 GB)
telemt_user_octets_to_client{user="hello"} 61699678124 (57.46 GB)
telemt_user_msgs_from_client{user="hello"} 7933
telemt_user_msgs_to_client{user="hello"} 11226
telemt_user_unique_ips_current{user="hello"} 75
telemt_user_unique_ips_recent_window{user="hello"} 27
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 26535.6 (7h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 508337
telemt_connections_bad_total 2913
telemt_handshake_timeouts_total 33582
telemt_upstream_connect_attempt_total 7466
telemt_upstream_connect_success_total 7350
telemt_upstream_connect_fail_total 116
telemt_upstream_connect_attempts_per_request{bucket="1"} 7466
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4317
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2976
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 57
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 116
telemt_me_keepalive_timeout_total 206
telemt_me_reconnect_attempts_total 15950
telemt_me_reconnect_success_total 4902
telemt_me_reader_eof_total 5404
telemt_me_idle_close_by_peer_total 5404
telemt_me_route_drop_no_conn_total 176470
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 443675
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1430
telemt_desync_full_logged_total 398
telemt_desync_suppressed_total 1032
telemt_desync_frames_bucket_total{bucket="1_2"} 325
telemt_desync_frames_bucket_total{bucket="3_10"} 492
telemt_desync_frames_bucket_total{bucket="gt_10"} 613
telemt_pool_swap_total 11
telemt_me_writer_removed_unexpected_total 5325
telemt_me_refill_failed_total 343
telemt_me_writer_restored_same_endpoint_total 4891
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 423
telemt_user_connections_total{user="hello"} 444608
telemt_user_connections_current{user="hello"} 378
telemt_user_octets_from_client{user="hello"} 6526916465 (6.08 GB)
telemt_user_octets_to_client{user="hello"} 144327518909 (134.42 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 138
telemt_user_unique_ips_recent_window{user="hello"} 66
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 26536.0 (7h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 352315
telemt_connections_bad_total 25703
telemt_handshake_timeouts_total 30854
telemt_upstream_connect_attempt_total 7257
telemt_upstream_connect_success_total 7257
telemt_upstream_connect_attempts_per_request{bucket="1"} 7257
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3965
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3291
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 158
telemt_me_reconnect_attempts_total 6904
telemt_me_reconnect_success_total 5882
telemt_me_reader_eof_total 6160
telemt_me_idle_close_by_peer_total 6160
telemt_me_seq_mismatch_total 3
telemt_me_route_drop_no_conn_total 114575
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 283103
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 683
telemt_desync_full_logged_total 277
telemt_desync_suppressed_total 406
telemt_desync_frames_bucket_total{bucket="1_2"} 264
telemt_desync_frames_bucket_total{bucket="3_10"} 243
telemt_desync_frames_bucket_total{bucket="gt_10"} 176
telemt_pool_swap_total 18
telemt_me_writer_removed_unexpected_total 5979
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 5868
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 97
telemt_user_connections_total{user="hello"} 282781
telemt_user_connections_current{user="hello"} 266
telemt_user_octets_from_client{user="hello"} 3986844684 (3.71 GB)
telemt_user_octets_to_client{user="hello"} 85009730044 (79.17 GB)
telemt_user_unique_ips_current{user="hello"} 85
telemt_user_unique_ips_recent_window{user="hello"} 44
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 26535.9 (7h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 371210
telemt_connections_bad_total 1190
telemt_handshake_timeouts_total 2362
telemt_upstream_connect_attempt_total 8165
telemt_upstream_connect_success_total 8132
telemt_upstream_connect_fail_total 33
telemt_upstream_connect_attempts_per_request{bucket="1"} 8165
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4269
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3758
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 103
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 33
telemt_me_keepalive_timeout_total 178
telemt_me_reconnect_attempts_total 10480
telemt_me_reconnect_success_total 6726
telemt_me_reader_eof_total 7046
telemt_me_idle_close_by_peer_total 7046
telemt_me_route_drop_no_conn_total 131675
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 347738
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 2077
telemt_desync_full_logged_total 777
telemt_desync_suppressed_total 1300
telemt_desync_frames_bucket_total{bucket="1_2"} 770
telemt_desync_frames_bucket_total{bucket="3_10"} 886
telemt_desync_frames_bucket_total{bucket="gt_10"} 421
telemt_pool_swap_total 8
telemt_me_writer_removed_unexpected_total 6942
telemt_me_refill_failed_total 116
telemt_me_writer_restored_same_endpoint_total 6726
telemt_me_async_recovery_trigger_total 48
telemt_me_writer_removed_unexpected_minus_restored_total 216
telemt_user_connections_total{user="hello"} 347597
telemt_user_connections_current{user="hello"} 328
telemt_user_octets_from_client{user="hello"} 6353833184 (5.92 GB)
telemt_user_octets_to_client{user="hello"} 126131430748 (117.47 GB)
telemt_user_unique_ips_current{user="hello"} 110
telemt_user_unique_ips_recent_window{user="hello"} 42
```