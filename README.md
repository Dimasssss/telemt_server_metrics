# Server Metrics 2026-03-15 09:18:47 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.18

telemt_uptime_seconds 39858.0 (11h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 869394
telemt_connections_bad_total 43426
telemt_handshake_timeouts_total 6334
telemt_upstream_connect_attempt_total 8065
telemt_upstream_connect_success_total 8030
telemt_upstream_connect_fail_total 35
telemt_upstream_connect_attempts_per_request{bucket="1"} 8065
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4206
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3808
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 16
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 35
telemt_me_keepalive_timeout_total 8
telemt_me_reconnect_attempts_total 6059
telemt_me_reconnect_success_total 6027
telemt_me_reader_eof_total 6378
telemt_me_idle_close_by_peer_total 6378
telemt_me_route_drop_no_conn_total 284420
telemt_me_route_drop_channel_closed_total 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 734118
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2427
telemt_desync_full_logged_total 740
telemt_desync_suppressed_total 1687
telemt_desync_frames_bucket_total{bucket="1_2"} 571
telemt_desync_frames_bucket_total{bucket="3_10"} 895
telemt_desync_frames_bucket_total{bucket="gt_10"} 961
telemt_pool_swap_total 36
telemt_me_writer_removed_unexpected_total 6112
telemt_me_writer_restored_same_endpoint_total 6016
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 296
telemt_me_writer_removed_unexpected_minus_restored_total 85
telemt_user_connections_total{user="hello"} 734106
telemt_user_connections_current{user="hello"} 1967
telemt_user_octets_from_client{user="hello"} 10256521956 (9.55 GB)
telemt_user_octets_to_client{user="hello"} 278096849008 (259.00 GB)
telemt_user_unique_ips_current{user="hello"} 564
telemt_user_unique_ips_recent_window{user="hello"} 283
```

## server2

```
telemt 3.3.18

telemt_uptime_seconds 39858.6 (11h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 343070
telemt_connections_bad_total 19061
telemt_handshake_timeouts_total 13307
telemt_upstream_connect_attempt_total 10650
telemt_upstream_connect_success_total 10596
telemt_upstream_connect_fail_total 54
telemt_upstream_connect_attempts_per_request{bucket="1"} 10650
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5767
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4741
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 26
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 62
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 54
telemt_me_keepalive_timeout_total 15
telemt_me_reconnect_attempts_total 8317
telemt_me_reconnect_success_total 8265
telemt_me_reader_eof_total 8761
telemt_me_idle_close_by_peer_total 8761
telemt_me_route_drop_no_conn_total 86883
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 271636
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 16
telemt_me_endpoint_quarantine_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 982
telemt_desync_full_logged_total 337
telemt_desync_suppressed_total 645
telemt_desync_frames_bucket_total{bucket="1_2"} 311
telemt_desync_frames_bucket_total{bucket="3_10"} 368
telemt_desync_frames_bucket_total{bucket="gt_10"} 303
telemt_pool_swap_total 39
telemt_me_writer_removed_unexpected_total 8334
telemt_me_writer_restored_same_endpoint_total 8257
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 61
telemt_me_writer_removed_unexpected_minus_restored_total 69
telemt_user_connections_total{user="hello"} 271910
telemt_user_connections_current{user="hello"} 660
telemt_user_octets_from_client{user="hello"} 3918023127 (3.65 GB)
telemt_user_octets_to_client{user="hello"} 102375821620 (95.34 GB)
telemt_user_msgs_from_client{user="hello"} 620
telemt_user_msgs_to_client{user="hello"} 1332
telemt_user_unique_ips_current{user="hello"} 221
telemt_user_unique_ips_recent_window{user="hello"} 120
```

## server3

```
telemt 3.3.18

telemt_uptime_seconds 39858.8 (11h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 604552
telemt_connections_bad_total 19943
telemt_handshake_timeouts_total 58761
telemt_upstream_connect_attempt_total 8886
telemt_upstream_connect_success_total 8848
telemt_upstream_connect_fail_total 38
telemt_upstream_connect_attempts_per_request{bucket="1"} 8886
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4632
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4165
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 51
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 38
telemt_me_reconnect_attempts_total 6873
telemt_me_reconnect_success_total 6827
telemt_me_reader_eof_total 7223
telemt_me_idle_close_by_peer_total 7223
telemt_me_route_drop_no_conn_total 179350
telemt_me_route_drop_channel_closed_total 15
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 477183
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 969
telemt_desync_full_logged_total 371
telemt_desync_suppressed_total 598
telemt_desync_frames_bucket_total{bucket="1_2"} 209
telemt_desync_frames_bucket_total{bucket="3_10"} 350
telemt_desync_frames_bucket_total{bucket="gt_10"} 410
telemt_pool_swap_total 39
telemt_me_writer_removed_unexpected_total 6911
telemt_me_writer_restored_same_endpoint_total 6808
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 242
telemt_me_writer_removed_unexpected_minus_restored_total 84
telemt_user_connections_total{user="hello"} 476701
telemt_user_connections_current{user="hello"} 1084
telemt_user_octets_from_client{user="hello"} 7176599212 (6.68 GB)
telemt_user_octets_to_client{user="hello"} 193204667748 (179.94 GB)
telemt_user_unique_ips_current{user="hello"} 322
telemt_user_unique_ips_recent_window{user="hello"} 181
```

## server4

```
telemt 3.3.18

telemt_uptime_seconds 39858.5 (11h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 365973
telemt_connections_bad_total 51990
telemt_handshake_timeouts_total 23754
telemt_upstream_connect_attempt_total 12639
telemt_upstream_connect_success_total 12337
telemt_upstream_connect_fail_total 302
telemt_upstream_connect_attempts_per_request{bucket="1"} 12639
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5754
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6580
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 302
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 26668
telemt_me_reconnect_success_total 10327
telemt_me_reader_eof_total 11149
telemt_me_idle_close_by_peer_total 11149
telemt_me_seq_mismatch_total 15
telemt_me_route_drop_no_conn_total 98112
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 272866
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 32
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 657
telemt_desync_full_logged_total 161
telemt_desync_suppressed_total 496
telemt_desync_frames_bucket_total{bucket="1_2"} 153
telemt_desync_frames_bucket_total{bucket="3_10"} 276
telemt_desync_frames_bucket_total{bucket="gt_10"} 228
telemt_pool_swap_total 16
telemt_me_writer_removed_unexpected_total 10927
telemt_me_refill_failed_total 510
telemt_me_writer_restored_same_endpoint_total 10297
telemt_me_writer_restored_fallback_total 30
telemt_me_async_recovery_trigger_total 96
telemt_me_writer_removed_unexpected_minus_restored_total 600
telemt_user_connections_total{user="hello"} 272868
telemt_user_connections_current{user="hello"} 594
telemt_user_octets_from_client{user="hello"} 2611106068 (2.43 GB)
telemt_user_octets_to_client{user="hello"} 88246888488 (82.19 GB)
telemt_user_unique_ips_current{user="hello"} 206
telemt_user_unique_ips_recent_window{user="hello"} 118
```

## server5

```
telemt 3.3.18

telemt_uptime_seconds 39859.4 (11h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 339049
telemt_connections_bad_total 3832
telemt_handshake_timeouts_total 3693
telemt_upstream_connect_attempt_total 8936
telemt_upstream_connect_success_total 8897
telemt_upstream_connect_fail_total 39
telemt_upstream_connect_attempts_per_request{bucket="1"} 8936
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4039
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4853
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 39
telemt_me_reconnect_attempts_total 6923
telemt_me_reconnect_success_total 6891
telemt_me_reader_eof_total 7337
telemt_me_idle_close_by_peer_total 7337
telemt_me_route_drop_no_conn_total 92807
telemt_me_route_drop_channel_closed_total 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 287791
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1166
telemt_desync_full_logged_total 371
telemt_desync_suppressed_total 795
telemt_desync_frames_bucket_total{bucket="1_2"} 339
telemt_desync_frames_bucket_total{bucket="3_10"} 484
telemt_desync_frames_bucket_total{bucket="gt_10"} 343
telemt_pool_swap_total 40
telemt_me_writer_removed_unexpected_total 6959
telemt_me_writer_restored_same_endpoint_total 6883
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 54
telemt_me_writer_removed_unexpected_minus_restored_total 68
telemt_user_connections_total{user="hello"} 287796
telemt_user_connections_current{user="hello"} 686
telemt_user_octets_from_client{user="hello"} 3366956952 (3.14 GB)
telemt_user_octets_to_client{user="hello"} 108308428016 (100.87 GB)
telemt_user_unique_ips_current{user="hello"} 203
telemt_user_unique_ips_recent_window{user="hello"} 107
```