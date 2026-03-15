# Server Metrics 2026-03-15 07:26:27 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.18

telemt_uptime_seconds 33117.6 (9h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 587876
telemt_connections_bad_total 18357
telemt_handshake_timeouts_total 3961
telemt_upstream_connect_attempt_total 6939
telemt_upstream_connect_success_total 6913
telemt_upstream_connect_fail_total 26
telemt_upstream_connect_attempts_per_request{bucket="1"} 6939
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3639
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3265
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 26
telemt_me_reconnect_attempts_total 5291
telemt_me_reconnect_success_total 5264
telemt_me_reader_eof_total 5561
telemt_me_idle_close_by_peer_total 5561
telemt_me_route_drop_no_conn_total 183250
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 497080
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1340
telemt_desync_full_logged_total 425
telemt_desync_suppressed_total 915
telemt_desync_frames_bucket_total{bucket="1_2"} 275
telemt_desync_frames_bucket_total{bucket="3_10"} 487
telemt_desync_frames_bucket_total{bucket="gt_10"} 578
telemt_pool_swap_total 30
telemt_me_writer_removed_unexpected_total 5331
telemt_me_writer_restored_same_endpoint_total 5253
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 296
telemt_me_writer_removed_unexpected_minus_restored_total 67
telemt_user_connections_total{user="hello"} 497080
telemt_user_connections_current{user="hello"} 1672
telemt_user_octets_from_client{user="hello"} 6306976320 (5.87 GB)
telemt_user_octets_to_client{user="hello"} 177986071112 (165.76 GB)
telemt_user_unique_ips_current{user="hello"} 512
telemt_user_unique_ips_recent_window{user="hello"} 230
```

## server2

```
telemt 3.3.18

telemt_uptime_seconds 33118.6 (9h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 215556
telemt_connections_bad_total 18350
telemt_handshake_timeouts_total 7365
telemt_upstream_connect_attempt_total 9176
telemt_upstream_connect_success_total 9130
telemt_upstream_connect_fail_total 46
telemt_upstream_connect_attempts_per_request{bucket="1"} 9176
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4951
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4112
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 18
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 49
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 46
telemt_me_keepalive_timeout_total 15
telemt_me_reconnect_attempts_total 7204
telemt_me_reconnect_success_total 7163
telemt_me_reader_eof_total 7580
telemt_me_idle_close_by_peer_total 7580
telemt_me_route_drop_no_conn_total 56277
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 179876
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 16
telemt_me_endpoint_quarantine_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 659
telemt_desync_full_logged_total 221
telemt_desync_suppressed_total 438
telemt_desync_frames_bucket_total{bucket="1_2"} 176
telemt_desync_frames_bucket_total{bucket="3_10"} 257
telemt_desync_frames_bucket_total{bucket="gt_10"} 226
telemt_pool_swap_total 34
telemt_me_writer_removed_unexpected_total 7198
telemt_me_writer_restored_same_endpoint_total 7155
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 61
telemt_me_writer_removed_unexpected_minus_restored_total 35
telemt_user_connections_total{user="hello"} 180157
telemt_user_connections_current{user="hello"} 529
telemt_user_octets_from_client{user="hello"} 2763870919 (2.57 GB)
telemt_user_octets_to_client{user="hello"} 66617139656 (62.04 GB)
telemt_user_msgs_from_client{user="hello"} 620
telemt_user_msgs_to_client{user="hello"} 1332
telemt_user_unique_ips_current{user="hello"} 183
telemt_user_unique_ips_recent_window{user="hello"} 90
```

## server3

```
telemt 3.3.18

telemt_uptime_seconds 33118.7 (9h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 398419
telemt_connections_bad_total 11402
telemt_handshake_timeouts_total 38793
telemt_upstream_connect_attempt_total 7493
telemt_upstream_connect_success_total 7460
telemt_upstream_connect_fail_total 33
telemt_upstream_connect_attempts_per_request{bucket="1"} 7493
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3948
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3482
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 30
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 33
telemt_me_reconnect_attempts_total 5837
telemt_me_reconnect_success_total 5804
telemt_me_reader_eof_total 6145
telemt_me_idle_close_by_peer_total 6145
telemt_me_route_drop_no_conn_total 103641
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 323841
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 604
telemt_desync_full_logged_total 249
telemt_desync_suppressed_total 355
telemt_desync_frames_bucket_total{bucket="1_2"} 139
telemt_desync_frames_bucket_total{bucket="3_10"} 213
telemt_desync_frames_bucket_total{bucket="gt_10"} 252
telemt_pool_swap_total 34
telemt_me_writer_removed_unexpected_total 5871
telemt_me_writer_restored_same_endpoint_total 5785
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 242
telemt_me_writer_removed_unexpected_minus_restored_total 67
telemt_user_connections_total{user="hello"} 323641
telemt_user_connections_current{user="hello"} 968
telemt_user_octets_from_client{user="hello"} 4925276432 (4.59 GB)
telemt_user_octets_to_client{user="hello"} 133694224616 (124.51 GB)
telemt_user_unique_ips_current{user="hello"} 298
telemt_user_unique_ips_recent_window{user="hello"} 140
```

## server4

```
telemt 3.3.18

telemt_uptime_seconds 33118.4 (9h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 261439
telemt_connections_bad_total 44951
telemt_handshake_timeouts_total 17511
telemt_upstream_connect_attempt_total 10775
telemt_upstream_connect_success_total 10524
telemt_upstream_connect_fail_total 251
telemt_upstream_connect_attempts_per_request{bucket="1"} 10775
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4969
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5552
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 251
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 21511
telemt_me_reconnect_success_total 8875
telemt_me_reader_eof_total 9544
telemt_me_idle_close_by_peer_total 9544
telemt_me_seq_mismatch_total 11
telemt_me_route_drop_no_conn_total 64214
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 192976
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 28
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 316
telemt_desync_full_logged_total 85
telemt_desync_suppressed_total 231
telemt_desync_frames_bucket_total{bucket="1_2"} 85
telemt_desync_frames_bucket_total{bucket="3_10"} 130
telemt_desync_frames_bucket_total{bucket="gt_10"} 101
telemt_pool_swap_total 14
telemt_me_writer_removed_unexpected_total 9343
telemt_me_refill_failed_total 394
telemt_me_writer_restored_same_endpoint_total 8849
telemt_me_writer_restored_fallback_total 26
telemt_me_async_recovery_trigger_total 96
telemt_me_writer_removed_unexpected_minus_restored_total 468
telemt_user_connections_total{user="hello"} 192978
telemt_user_connections_current{user="hello"} 503
telemt_user_octets_from_client{user="hello"} 1684334792 (1.57 GB)
telemt_user_octets_to_client{user="hello"} 65173886748 (60.70 GB)
telemt_user_unique_ips_current{user="hello"} 175
telemt_user_unique_ips_recent_window{user="hello"} 81
```

## server5

```
telemt 3.3.18

telemt_uptime_seconds 33119.3 (9h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 198864
telemt_connections_bad_total 400
telemt_handshake_timeouts_total 1897
telemt_upstream_connect_attempt_total 7334
telemt_upstream_connect_success_total 7304
telemt_upstream_connect_fail_total 30
telemt_upstream_connect_attempts_per_request{bucket="1"} 7334
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3252
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4047
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 30
telemt_me_reconnect_attempts_total 5683
telemt_me_reconnect_success_total 5656
telemt_me_reader_eof_total 6040
telemt_me_idle_close_by_peer_total 6040
telemt_me_route_drop_no_conn_total 61282
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 186965
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 810
telemt_desync_full_logged_total 251
telemt_desync_suppressed_total 559
telemt_desync_frames_bucket_total{bucket="1_2"} 238
telemt_desync_frames_bucket_total{bucket="3_10"} 340
telemt_desync_frames_bucket_total{bucket="gt_10"} 232
telemt_pool_swap_total 36
telemt_me_writer_removed_unexpected_total 5713
telemt_me_writer_restored_same_endpoint_total 5648
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 54
telemt_me_writer_removed_unexpected_minus_restored_total 57
telemt_user_connections_total{user="hello"} 186972
telemt_user_connections_current{user="hello"} 714
telemt_user_octets_from_client{user="hello"} 1930090628 (1.80 GB)
telemt_user_octets_to_client{user="hello"} 71656084188 (66.73 GB)
telemt_user_unique_ips_current{user="hello"} 198
telemt_user_unique_ips_recent_window{user="hello"} 91
```