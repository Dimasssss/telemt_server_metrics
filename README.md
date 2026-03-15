# Server Metrics 2026-03-15 08:07:19 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.18

telemt_uptime_seconds 35568.9 (9h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 683035
telemt_connections_bad_total 27929
telemt_handshake_timeouts_total 4792
telemt_upstream_connect_attempt_total 7391
telemt_upstream_connect_success_total 7363
telemt_upstream_connect_fail_total 28
telemt_upstream_connect_attempts_per_request{bucket="1"} 7391
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3860
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3491
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 12
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 28
telemt_me_reconnect_attempts_total 5608
telemt_me_reconnect_success_total 5580
telemt_me_reader_eof_total 5897
telemt_me_idle_close_by_peer_total 5897
telemt_me_route_drop_no_conn_total 216359
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 575415
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1642
telemt_desync_full_logged_total 513
telemt_desync_suppressed_total 1129
telemt_desync_frames_bucket_total{bucket="1_2"} 360
telemt_desync_frames_bucket_total{bucket="3_10"} 594
telemt_desync_frames_bucket_total{bucket="gt_10"} 688
telemt_pool_swap_total 32
telemt_me_writer_removed_unexpected_total 5653
telemt_me_writer_restored_same_endpoint_total 5569
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 296
telemt_me_writer_removed_unexpected_minus_restored_total 73
telemt_user_connections_total{user="hello"} 575420
telemt_user_connections_current{user="hello"} 1833
telemt_user_octets_from_client{user="hello"} 7243132988 (6.75 GB)
telemt_user_octets_to_client{user="hello"} 215747316836 (200.93 GB)
telemt_user_unique_ips_current{user="hello"} 552
telemt_user_unique_ips_recent_window{user="hello"} 269
```

## server2

```
telemt 3.3.18

telemt_uptime_seconds 35569.7 (9h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 265434
telemt_connections_bad_total 18362
telemt_handshake_timeouts_total 10740
telemt_upstream_connect_attempt_total 9741
telemt_upstream_connect_success_total 9693
telemt_upstream_connect_fail_total 48
telemt_upstream_connect_attempts_per_request{bucket="1"} 9741
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5264
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4352
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 22
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 55
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 48
telemt_me_keepalive_timeout_total 15
telemt_me_reconnect_attempts_total 7633
telemt_me_reconnect_success_total 7587
telemt_me_reader_eof_total 8035
telemt_me_idle_close_by_peer_total 8035
telemt_me_route_drop_no_conn_total 66914
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 210426
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 16
telemt_me_endpoint_quarantine_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 784
telemt_desync_full_logged_total 259
telemt_desync_suppressed_total 525
telemt_desync_frames_bucket_total{bucket="1_2"} 222
telemt_desync_frames_bucket_total{bucket="3_10"} 307
telemt_desync_frames_bucket_total{bucket="gt_10"} 255
telemt_pool_swap_total 36
telemt_me_writer_removed_unexpected_total 7636
telemt_me_writer_restored_same_endpoint_total 7579
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 61
telemt_me_writer_removed_unexpected_minus_restored_total 49
telemt_user_connections_total{user="hello"} 210707
telemt_user_connections_current{user="hello"} 596
telemt_user_octets_from_client{user="hello"} 3166553775 (2.95 GB)
telemt_user_octets_to_client{user="hello"} 77705546928 (72.37 GB)
telemt_user_msgs_from_client{user="hello"} 620
telemt_user_msgs_to_client{user="hello"} 1332
telemt_user_unique_ips_current{user="hello"} 194
telemt_user_unique_ips_recent_window{user="hello"} 103
```

## server3

```
telemt 3.3.18

telemt_uptime_seconds 35569.8 (9h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 460975
telemt_connections_bad_total 13581
telemt_handshake_timeouts_total 41973
telemt_upstream_connect_attempt_total 7979
telemt_upstream_connect_success_total 7944
telemt_upstream_connect_fail_total 35
telemt_upstream_connect_attempts_per_request{bucket="1"} 7979
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4196
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3706
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 42
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 35
telemt_me_reconnect_attempts_total 6189
telemt_me_reconnect_success_total 6152
telemt_me_reader_eof_total 6513
telemt_me_idle_close_by_peer_total 6513
telemt_me_route_drop_no_conn_total 121950
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 373717
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 701
telemt_desync_full_logged_total 276
telemt_desync_suppressed_total 425
telemt_desync_frames_bucket_total{bucket="1_2"} 166
telemt_desync_frames_bucket_total{bucket="3_10"} 246
telemt_desync_frames_bucket_total{bucket="gt_10"} 289
telemt_pool_swap_total 36
telemt_me_writer_removed_unexpected_total 6227
telemt_me_writer_restored_same_endpoint_total 6133
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 242
telemt_me_writer_removed_unexpected_minus_restored_total 75
telemt_user_connections_total{user="hello"} 373485
telemt_user_connections_current{user="hello"} 1060
telemt_user_octets_from_client{user="hello"} 5658480364 (5.27 GB)
telemt_user_octets_to_client{user="hello"} 156498532668 (145.75 GB)
telemt_user_unique_ips_current{user="hello"} 326
telemt_user_unique_ips_recent_window{user="hello"} 174
```

## server4

```
telemt 3.3.18

telemt_uptime_seconds 35569.6 (9h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 294738
telemt_connections_bad_total 46835
telemt_handshake_timeouts_total 20741
telemt_upstream_connect_attempt_total 11443
telemt_upstream_connect_success_total 11181
telemt_upstream_connect_fail_total 262
telemt_upstream_connect_attempts_per_request{bucket="1"} 11443
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5259
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5919
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 262
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 22036
telemt_me_reconnect_success_total 9395
telemt_me_reader_eof_total 10091
telemt_me_idle_close_by_peer_total 10091
telemt_me_seq_mismatch_total 12
telemt_me_route_drop_no_conn_total 75647
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 219666
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 29
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 403
telemt_desync_full_logged_total 105
telemt_desync_suppressed_total 298
telemt_desync_frames_bucket_total{bucket="1_2"} 100
telemt_desync_frames_bucket_total{bucket="3_10"} 175
telemt_desync_frames_bucket_total{bucket="gt_10"} 128
telemt_pool_swap_total 16
telemt_me_writer_removed_unexpected_total 9866
telemt_me_refill_failed_total 394
telemt_me_writer_restored_same_endpoint_total 9368
telemt_me_writer_restored_fallback_total 27
telemt_me_async_recovery_trigger_total 96
telemt_me_writer_removed_unexpected_minus_restored_total 471
telemt_user_connections_total{user="hello"} 219667
telemt_user_connections_current{user="hello"} 495
telemt_user_octets_from_client{user="hello"} 1914033320 (1.78 GB)
telemt_user_octets_to_client{user="hello"} 74040011852 (68.96 GB)
telemt_user_unique_ips_current{user="hello"} 181
telemt_user_unique_ips_recent_window{user="hello"} 116
```

## server5

```
telemt 3.3.18

telemt_uptime_seconds 35570.7 (9h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 244866
telemt_connections_bad_total 2675
telemt_handshake_timeouts_total 2321
telemt_upstream_connect_attempt_total 7869
telemt_upstream_connect_success_total 7837
telemt_upstream_connect_fail_total 32
telemt_upstream_connect_attempts_per_request{bucket="1"} 7869
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3500
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4332
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 32
telemt_me_reconnect_attempts_total 6085
telemt_me_reconnect_success_total 6057
telemt_me_reader_eof_total 6466
telemt_me_idle_close_by_peer_total 6466
telemt_me_route_drop_no_conn_total 71790
telemt_me_route_drop_channel_closed_total 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 220928
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 911
telemt_desync_full_logged_total 289
telemt_desync_suppressed_total 622
telemt_desync_frames_bucket_total{bucket="1_2"} 269
telemt_desync_frames_bucket_total{bucket="3_10"} 382
telemt_desync_frames_bucket_total{bucket="gt_10"} 260
telemt_pool_swap_total 38
telemt_me_writer_removed_unexpected_total 6118
telemt_me_writer_restored_same_endpoint_total 6049
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 54
telemt_me_writer_removed_unexpected_minus_restored_total 61
telemt_user_connections_total{user="hello"} 220947
telemt_user_connections_current{user="hello"} 896
telemt_user_octets_from_client{user="hello"} 2372307800 (2.21 GB)
telemt_user_octets_to_client{user="hello"} 88801923304 (82.70 GB)
telemt_user_unique_ips_current{user="hello"} 216
telemt_user_unique_ips_recent_window{user="hello"} 132
```