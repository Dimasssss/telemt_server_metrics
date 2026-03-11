# Server Metrics 2026-03-11 01:01:31 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 38066.8 (10h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 800843
telemt_connections_bad_total 9523
telemt_handshake_timeouts_total 9094
telemt_upstream_connect_attempt_total 8298
telemt_upstream_connect_success_total 8289
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 8298
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4146
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4084
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 58
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 480
telemt_me_reconnect_attempts_total 17973
telemt_me_reconnect_success_total 6308
telemt_me_reader_eof_total 6915
telemt_me_idle_close_by_peer_total 6915
telemt_me_route_drop_no_conn_total 328515
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 758410
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3575
telemt_desync_full_logged_total 1001
telemt_desync_suppressed_total 2574
telemt_desync_frames_bucket_total{bucket="1_2"} 1043
telemt_desync_frames_bucket_total{bucket="3_10"} 1328
telemt_desync_frames_bucket_total{bucket="gt_10"} 1204
telemt_pool_swap_total 22
telemt_me_writer_removed_unexpected_total 6725
telemt_me_refill_failed_total 363
telemt_me_writer_restored_same_endpoint_total 6302
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 417
telemt_user_connections_total{user="hello"} 758177
telemt_user_connections_current{user="hello"} 429
telemt_user_octets_from_client{user="hello"} 10516882120 (9.79 GB)
telemt_user_octets_to_client{user="hello"} 230005929504 (214.21 GB)
telemt_user_unique_ips_current{user="hello"} 157
telemt_user_unique_ips_recent_window{user="hello"} 53
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 38123.3 (10h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 344960
telemt_connections_bad_total 2392
telemt_handshake_timeouts_total 17675
telemt_upstream_connect_attempt_total 15450
telemt_upstream_connect_success_total 12568
telemt_upstream_connect_fail_total 2882
telemt_upstream_connect_attempts_per_request{bucket="1"} 15450
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5458
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4870
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 209
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2031
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2882
telemt_me_keepalive_timeout_total 1711
telemt_me_reconnect_attempts_total 8484
telemt_me_reconnect_success_total 7669
telemt_me_reader_eof_total 8100
telemt_me_idle_close_by_peer_total 8098
telemt_me_route_drop_no_conn_total 173293
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 294277
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1774
telemt_desync_full_logged_total 506
telemt_desync_suppressed_total 1268
telemt_desync_frames_bucket_total{bucket="1_2"} 543
telemt_desync_frames_bucket_total{bucket="3_10"} 630
telemt_desync_frames_bucket_total{bucket="gt_10"} 601
telemt_pool_swap_total 30
telemt_me_writer_removed_unexpected_total 7773
telemt_me_refill_failed_total 22
telemt_me_writer_restored_same_endpoint_total 7648
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 86
telemt_me_writer_removed_unexpected_minus_restored_total 104
telemt_user_connections_total{user="hello"} 296546
telemt_user_connections_current{user="hello"} 149
telemt_user_octets_from_client{user="hello"} 2849887574 (2.65 GB)
telemt_user_octets_to_client{user="hello"} 70581066544 (65.73 GB)
telemt_user_msgs_from_client{user="hello"} 7933
telemt_user_msgs_to_client{user="hello"} 11226
telemt_user_unique_ips_current{user="hello"} 61
telemt_user_unique_ips_recent_window{user="hello"} 27
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 38123.1 (10h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 573825
telemt_connections_bad_total 4106
telemt_handshake_timeouts_total 34173
telemt_upstream_connect_attempt_total 10458
telemt_upstream_connect_success_total 10313
telemt_upstream_connect_fail_total 145
telemt_upstream_connect_attempts_per_request{bucket="1"} 10458
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5797
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4450
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 66
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 145
telemt_me_keepalive_timeout_total 510
telemt_me_reconnect_attempts_total 18351
telemt_me_reconnect_success_total 7289
telemt_me_reader_eof_total 7950
telemt_me_idle_close_by_peer_total 7950
telemt_me_route_drop_no_conn_total 196715
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 506991
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1522
telemt_desync_full_logged_total 435
telemt_desync_suppressed_total 1087
telemt_desync_frames_bucket_total{bucket="1_2"} 344
telemt_desync_frames_bucket_total{bucket="3_10"} 523
telemt_desync_frames_bucket_total{bucket="gt_10"} 655
telemt_pool_swap_total 23
telemt_me_writer_removed_unexpected_total 7734
telemt_me_refill_failed_total 343
telemt_me_writer_restored_same_endpoint_total 7278
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 445
telemt_user_connections_total{user="hello"} 507910
telemt_user_connections_current{user="hello"} 152
telemt_user_octets_from_client{user="hello"} 6852164441 (6.38 GB)
telemt_user_octets_to_client{user="hello"} 155273575153 (144.61 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 83
telemt_user_unique_ips_recent_window{user="hello"} 35
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 38123.7 (10h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 421603
telemt_connections_bad_total 36238
telemt_handshake_timeouts_total 39833
telemt_upstream_connect_attempt_total 10918
telemt_upstream_connect_success_total 10918
telemt_upstream_connect_attempts_per_request{bucket="1"} 10918
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6140
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4776
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_timeout_total 409
telemt_me_reconnect_attempts_total 10001
telemt_me_reconnect_success_total 8968
telemt_me_reader_eof_total 9488
telemt_me_idle_close_by_peer_total 9488
telemt_me_seq_mismatch_total 5
telemt_me_route_drop_no_conn_total 129266
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 332487
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 720
telemt_desync_full_logged_total 289
telemt_desync_suppressed_total 431
telemt_desync_frames_bucket_total{bucket="1_2"} 278
telemt_desync_frames_bucket_total{bucket="3_10"} 250
telemt_desync_frames_bucket_total{bucket="gt_10"} 192
telemt_pool_swap_total 31
telemt_me_writer_removed_unexpected_total 9085
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 8952
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 117
telemt_user_connections_total{user="hello"} 332163
telemt_user_connections_current{user="hello"} 164
telemt_user_octets_from_client{user="hello"} 4220607184 (3.93 GB)
telemt_user_octets_to_client{user="hello"} 91150863316 (84.89 GB)
telemt_user_unique_ips_current{user="hello"} 62
telemt_user_unique_ips_recent_window{user="hello"} 33
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 38123.4 (10h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 445879
telemt_connections_bad_total 4917
telemt_handshake_timeouts_total 2844
telemt_upstream_connect_attempt_total 11499
telemt_upstream_connect_success_total 11450
telemt_upstream_connect_fail_total 49
telemt_upstream_connect_attempts_per_request{bucket="1"} 11499
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5944
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5393
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 111
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 49
telemt_me_keepalive_timeout_total 506
telemt_me_reconnect_attempts_total 13232
telemt_me_reconnect_success_total 9465
telemt_me_reader_eof_total 9959
telemt_me_idle_close_by_peer_total 9959
telemt_me_route_drop_no_conn_total 148103
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 409840
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 2275
telemt_desync_full_logged_total 880
telemt_desync_suppressed_total 1395
telemt_desync_frames_bucket_total{bucket="1_2"} 839
telemt_desync_frames_bucket_total{bucket="3_10"} 971
telemt_desync_frames_bucket_total{bucket="gt_10"} 465
telemt_pool_swap_total 19
telemt_me_writer_removed_unexpected_total 9704
telemt_me_refill_failed_total 116
telemt_me_writer_restored_same_endpoint_total 9465
telemt_me_async_recovery_trigger_total 48
telemt_me_writer_removed_unexpected_minus_restored_total 239
telemt_user_connections_total{user="hello"} 409559
telemt_user_connections_current{user="hello"} 256
telemt_user_octets_from_client{user="hello"} 8371239308 (7.80 GB)
telemt_user_octets_to_client{user="hello"} 147131586648 (137.03 GB)
telemt_user_unique_ips_current{user="hello"} 84
telemt_user_unique_ips_recent_window{user="hello"} 42
```