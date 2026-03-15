# Server Metrics 2026-03-15 10:20:09 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.18

telemt_uptime_seconds 43539.3 (12h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1043562
telemt_connections_bad_total 61505
telemt_handshake_timeouts_total 8076
telemt_upstream_connect_attempt_total 8765
telemt_upstream_connect_success_total 8726
telemt_upstream_connect_fail_total 39
telemt_upstream_connect_attempts_per_request{bucket="1"} 8765
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4602
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4103
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 21
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 39
telemt_me_keepalive_timeout_total 8
telemt_me_reconnect_attempts_total 6578
telemt_me_reconnect_success_total 6538
telemt_me_reader_eof_total 6909
telemt_me_idle_close_by_peer_total 6909
telemt_me_route_drop_no_conn_total 344258
telemt_me_route_drop_channel_closed_total 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 879884
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3174
telemt_desync_full_logged_total 908
telemt_desync_suppressed_total 2266
telemt_desync_frames_bucket_total{bucket="1_2"} 767
telemt_desync_frames_bucket_total{bucket="3_10"} 1239
telemt_desync_frames_bucket_total{bucket="gt_10"} 1168
telemt_pool_swap_total 38
telemt_me_writer_removed_unexpected_total 6630
telemt_me_writer_restored_same_endpoint_total 6527
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 296
telemt_me_writer_removed_unexpected_minus_restored_total 92
telemt_user_connections_total{user="hello"} 879881
telemt_user_connections_current{user="hello"} 2286
telemt_user_octets_from_client{user="hello"} 12681262716 (11.81 GB)
telemt_user_octets_to_client{user="hello"} 340014160556 (316.66 GB)
telemt_user_unique_ips_current{user="hello"} 594
telemt_user_unique_ips_recent_window{user="hello"} 282
```

## server2

```
telemt 3.3.18

telemt_uptime_seconds 43540.2 (12h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 410980
telemt_connections_bad_total 22754
telemt_handshake_timeouts_total 17417
telemt_upstream_connect_attempt_total 11532
telemt_upstream_connect_success_total 11471
telemt_upstream_connect_fail_total 61
telemt_upstream_connect_attempts_per_request{bucket="1"} 11532
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6215
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5159
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 28
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 69
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 61
telemt_me_keepalive_timeout_total 15
telemt_me_reconnect_attempts_total 9014
telemt_me_reconnect_success_total 8957
telemt_me_reader_eof_total 9485
telemt_me_idle_close_by_peer_total 9485
telemt_me_route_drop_no_conn_total 104818
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 324811
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 16
telemt_me_endpoint_quarantine_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1164
telemt_desync_full_logged_total 399
telemt_desync_suppressed_total 765
telemt_desync_frames_bucket_total{bucket="1_2"} 385
telemt_desync_frames_bucket_total{bucket="3_10"} 429
telemt_desync_frames_bucket_total{bucket="gt_10"} 350
telemt_pool_swap_total 40
telemt_me_writer_removed_unexpected_total 9044
telemt_me_writer_restored_same_endpoint_total 8949
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 61
telemt_me_writer_removed_unexpected_minus_restored_total 87
telemt_user_connections_total{user="hello"} 325098
telemt_user_connections_current{user="hello"} 736
telemt_user_octets_from_client{user="hello"} 4751247675 (4.42 GB)
telemt_user_octets_to_client{user="hello"} 122449025196 (114.04 GB)
telemt_user_msgs_from_client{user="hello"} 620
telemt_user_msgs_to_client{user="hello"} 1332
telemt_user_unique_ips_current{user="hello"} 225
telemt_user_unique_ips_recent_window{user="hello"} 111
```

## server3

```
telemt 3.3.18

telemt_uptime_seconds 43540.1 (12h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 766987
telemt_connections_bad_total 25742
telemt_handshake_timeouts_total 77295
telemt_upstream_connect_attempt_total 9668
telemt_upstream_connect_success_total 9626
telemt_upstream_connect_fail_total 42
telemt_upstream_connect_attempts_per_request{bucket="1"} 9668
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5020
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4554
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 52
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 42
telemt_me_reconnect_attempts_total 7472
telemt_me_reconnect_success_total 7423
telemt_me_reader_eof_total 7857
telemt_me_idle_close_by_peer_total 7857
telemt_me_route_drop_no_conn_total 216822
telemt_me_route_drop_channel_closed_total 15
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 569820
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1256
telemt_desync_full_logged_total 464
telemt_desync_suppressed_total 792
telemt_desync_frames_bucket_total{bucket="1_2"} 275
telemt_desync_frames_bucket_total{bucket="3_10"} 456
telemt_desync_frames_bucket_total{bucket="gt_10"} 525
telemt_pool_swap_total 42
telemt_me_writer_removed_unexpected_total 7521
telemt_me_writer_restored_same_endpoint_total 7404
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 242
telemt_me_writer_removed_unexpected_minus_restored_total 98
telemt_user_connections_total{user="hello"} 569244
telemt_user_connections_current{user="hello"} 1078
telemt_user_octets_from_client{user="hello"} 8357581264 (7.78 GB)
telemt_user_octets_to_client{user="hello"} 228651847988 (212.95 GB)
telemt_user_unique_ips_current{user="hello"} 338
telemt_user_unique_ips_recent_window{user="hello"} 180
```

## server4

```
telemt 3.3.18

telemt_uptime_seconds 43540.2 (12h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 428938
telemt_connections_bad_total 55386
telemt_handshake_timeouts_total 25329
telemt_upstream_connect_attempt_total 13194
telemt_upstream_connect_success_total 12869
telemt_upstream_connect_fail_total 325
telemt_upstream_connect_attempts_per_request{bucket="1"} 13194
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6097
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6769
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 325
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 31038
telemt_me_reconnect_success_total 10678
telemt_me_reader_eof_total 11635
telemt_me_idle_close_by_peer_total 11635
telemt_me_seq_mismatch_total 17
telemt_me_route_drop_no_conn_total 119563
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 321852
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 34
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 752
telemt_desync_full_logged_total 188
telemt_desync_suppressed_total 564
telemt_desync_frames_bucket_total{bucket="1_2"} 184
telemt_desync_frames_bucket_total{bucket="3_10"} 306
telemt_desync_frames_bucket_total{bucket="gt_10"} 262
telemt_pool_swap_total 17
telemt_me_writer_removed_unexpected_total 11408
telemt_me_refill_failed_total 636
telemt_me_writer_restored_same_endpoint_total 10646
telemt_me_writer_restored_fallback_total 32
telemt_me_async_recovery_trigger_total 96
telemt_me_writer_removed_unexpected_minus_restored_total 730
telemt_user_connections_total{user="hello"} 321763
telemt_user_connections_current{user="hello"} 527
telemt_user_octets_from_client{user="hello"} 3926339200 (3.66 GB)
telemt_user_octets_to_client{user="hello"} 104018998344 (96.88 GB)
telemt_user_unique_ips_current{user="hello"} 175
telemt_user_unique_ips_recent_window{user="hello"} 99
```

## server5

```
telemt 3.3.18

telemt_uptime_seconds 43541.1 (12h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 427244
telemt_connections_bad_total 5757
telemt_handshake_timeouts_total 6528
telemt_upstream_connect_attempt_total 9691
telemt_upstream_connect_success_total 9646
telemt_upstream_connect_fail_total 45
telemt_upstream_connect_attempts_per_request{bucket="1"} 9691
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4383
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5258
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 45
telemt_me_reconnect_attempts_total 7498
telemt_me_reconnect_success_total 7461
telemt_me_reader_eof_total 7937
telemt_me_idle_close_by_peer_total 7937
telemt_me_route_drop_no_conn_total 111014
telemt_me_route_drop_channel_closed_total 12
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 353495
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1347
telemt_desync_full_logged_total 431
telemt_desync_suppressed_total 916
telemt_desync_frames_bucket_total{bucket="1_2"} 400
telemt_desync_frames_bucket_total{bucket="3_10"} 542
telemt_desync_frames_bucket_total{bucket="gt_10"} 405
telemt_pool_swap_total 42
telemt_me_writer_removed_unexpected_total 7544
telemt_me_writer_restored_same_endpoint_total 7453
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 54
telemt_me_writer_removed_unexpected_minus_restored_total 83
telemt_user_connections_total{user="hello"} 353499
telemt_user_connections_current{user="hello"} 931
telemt_user_octets_from_client{user="hello"} 4333535236 (4.04 GB)
telemt_user_octets_to_client{user="hello"} 130935806252 (121.94 GB)
telemt_user_unique_ips_current{user="hello"} 229
telemt_user_unique_ips_recent_window{user="hello"} 121
```