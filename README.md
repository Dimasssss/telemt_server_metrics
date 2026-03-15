# Server Metrics 2026-03-15 07:21:21 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.18

telemt_uptime_seconds 32811.4 (9h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 577097
telemt_connections_bad_total 17137
telemt_handshake_timeouts_total 3902
telemt_upstream_connect_attempt_total 6889
telemt_upstream_connect_success_total 6863
telemt_upstream_connect_fail_total 26
telemt_upstream_connect_attempts_per_request{bucket="1"} 6889
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3620
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3234
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 26
telemt_me_reconnect_attempts_total 5241
telemt_me_reconnect_success_total 5214
telemt_me_reader_eof_total 5511
telemt_me_idle_close_by_peer_total 5511
telemt_me_route_drop_no_conn_total 178774
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 487960
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1312
telemt_desync_full_logged_total 416
telemt_desync_suppressed_total 896
telemt_desync_frames_bucket_total{bucket="1_2"} 266
telemt_desync_frames_bucket_total{bucket="3_10"} 481
telemt_desync_frames_bucket_total{bucket="gt_10"} 565
telemt_pool_swap_total 30
telemt_me_writer_removed_unexpected_total 5281
telemt_me_writer_restored_same_endpoint_total 5203
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 296
telemt_me_writer_removed_unexpected_minus_restored_total 67
telemt_user_connections_total{user="hello"} 487971
telemt_user_connections_current{user="hello"} 1567
telemt_user_octets_from_client{user="hello"} 6212525332 (5.79 GB)
telemt_user_octets_to_client{user="hello"} 172982203716 (161.10 GB)
telemt_user_unique_ips_current{user="hello"} 497
telemt_user_unique_ips_recent_window{user="hello"} 276
```

## server2

```
telemt 3.3.18

telemt_uptime_seconds 32812.3 (9h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 210728
telemt_connections_bad_total 18349
telemt_handshake_timeouts_total 6960
telemt_upstream_connect_attempt_total 9138
telemt_upstream_connect_success_total 9092
telemt_upstream_connect_fail_total 46
telemt_upstream_connect_attempts_per_request{bucket="1"} 9138
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4930
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4095
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 18
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 49
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 46
telemt_me_keepalive_timeout_total 15
telemt_me_reconnect_attempts_total 7166
telemt_me_reconnect_success_total 7125
telemt_me_reader_eof_total 7540
telemt_me_idle_close_by_peer_total 7540
telemt_me_route_drop_no_conn_total 54794
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 176358
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 16
telemt_me_endpoint_quarantine_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 639
telemt_desync_full_logged_total 215
telemt_desync_suppressed_total 424
telemt_desync_frames_bucket_total{bucket="1_2"} 168
telemt_desync_frames_bucket_total{bucket="3_10"} 251
telemt_desync_frames_bucket_total{bucket="gt_10"} 220
telemt_pool_swap_total 34
telemt_me_writer_removed_unexpected_total 7158
telemt_me_writer_restored_same_endpoint_total 7117
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 61
telemt_me_writer_removed_unexpected_minus_restored_total 33
telemt_user_connections_total{user="hello"} 176642
telemt_user_connections_current{user="hello"} 542
telemt_user_octets_from_client{user="hello"} 2737575479 (2.55 GB)
telemt_user_octets_to_client{user="hello"} 65079809372 (60.61 GB)
telemt_user_msgs_from_client{user="hello"} 620
telemt_user_msgs_to_client{user="hello"} 1332
telemt_user_unique_ips_current{user="hello"} 187
telemt_user_unique_ips_recent_window{user="hello"} 110
```

## server3

```
telemt 3.3.18

telemt_uptime_seconds 32812.4 (9h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 390195
telemt_connections_bad_total 11142
telemt_handshake_timeouts_total 37677
telemt_upstream_connect_attempt_total 7459
telemt_upstream_connect_success_total 7426
telemt_upstream_connect_fail_total 33
telemt_upstream_connect_attempts_per_request{bucket="1"} 7459
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3933
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3464
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 29
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 33
telemt_me_reconnect_attempts_total 5803
telemt_me_reconnect_success_total 5771
telemt_me_reader_eof_total 6110
telemt_me_idle_close_by_peer_total 6110
telemt_me_route_drop_no_conn_total 100894
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 317663
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 601
telemt_desync_full_logged_total 246
telemt_desync_suppressed_total 355
telemt_desync_frames_bucket_total{bucket="1_2"} 138
telemt_desync_frames_bucket_total{bucket="3_10"} 212
telemt_desync_frames_bucket_total{bucket="gt_10"} 251
telemt_pool_swap_total 34
telemt_me_writer_removed_unexpected_total 5836
telemt_me_writer_restored_same_endpoint_total 5752
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 242
telemt_me_writer_removed_unexpected_minus_restored_total 65
telemt_user_connections_total{user="hello"} 317462
telemt_user_connections_current{user="hello"} 969
telemt_user_octets_from_client{user="hello"} 4872676820 (4.54 GB)
telemt_user_octets_to_client{user="hello"} 130866816080 (121.88 GB)
telemt_user_unique_ips_current{user="hello"} 307
telemt_user_unique_ips_recent_window{user="hello"} 185
```

## server4

```
telemt 3.3.18

telemt_uptime_seconds 32812.2 (9h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 257089
telemt_connections_bad_total 44711
telemt_handshake_timeouts_total 16899
telemt_upstream_connect_attempt_total 10754
telemt_upstream_connect_success_total 10503
telemt_upstream_connect_fail_total 251
telemt_upstream_connect_attempts_per_request{bucket="1"} 10754
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4963
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5537
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 251
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 21490
telemt_me_reconnect_success_total 8854
telemt_me_reader_eof_total 9523
telemt_me_idle_close_by_peer_total 9523
telemt_me_seq_mismatch_total 11
telemt_me_route_drop_no_conn_total 63018
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 189600
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 28
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 299
telemt_desync_full_logged_total 82
telemt_desync_suppressed_total 217
telemt_desync_frames_bucket_total{bucket="1_2"} 83
telemt_desync_frames_bucket_total{bucket="3_10"} 125
telemt_desync_frames_bucket_total{bucket="gt_10"} 91
telemt_pool_swap_total 14
telemt_me_writer_removed_unexpected_total 9322
telemt_me_refill_failed_total 394
telemt_me_writer_restored_same_endpoint_total 8828
telemt_me_writer_restored_fallback_total 26
telemt_me_async_recovery_trigger_total 96
telemt_me_writer_removed_unexpected_minus_restored_total 468
telemt_user_connections_total{user="hello"} 189603
telemt_user_connections_current{user="hello"} 458
telemt_user_octets_from_client{user="hello"} 1659003944 (1.55 GB)
telemt_user_octets_to_client{user="hello"} 64368777416 (59.95 GB)
telemt_user_unique_ips_current{user="hello"} 182
telemt_user_unique_ips_recent_window{user="hello"} 105
```

## server5

```
telemt 3.3.18

telemt_uptime_seconds 32813.0 (9h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 195077
telemt_connections_bad_total 383
telemt_handshake_timeouts_total 1893
telemt_upstream_connect_attempt_total 7304
telemt_upstream_connect_success_total 7274
telemt_upstream_connect_fail_total 30
telemt_upstream_connect_attempts_per_request{bucket="1"} 7304
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3234
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4035
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 30
telemt_me_reconnect_attempts_total 5653
telemt_me_reconnect_success_total 5626
telemt_me_reader_eof_total 6010
telemt_me_idle_close_by_peer_total 6010
telemt_me_route_drop_no_conn_total 59954
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 183337
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 769
telemt_desync_full_logged_total 242
telemt_desync_suppressed_total 527
telemt_desync_frames_bucket_total{bucket="1_2"} 235
telemt_desync_frames_bucket_total{bucket="3_10"} 313
telemt_desync_frames_bucket_total{bucket="gt_10"} 221
telemt_pool_swap_total 36
telemt_me_writer_removed_unexpected_total 5683
telemt_me_writer_restored_same_endpoint_total 5618
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 54
telemt_me_writer_removed_unexpected_minus_restored_total 57
telemt_user_connections_total{user="hello"} 183344
telemt_user_connections_current{user="hello"} 616
telemt_user_octets_from_client{user="hello"} 1909508316 (1.78 GB)
telemt_user_octets_to_client{user="hello"} 70932391308 (66.06 GB)
telemt_user_unique_ips_current{user="hello"} 193
telemt_user_unique_ips_recent_window{user="hello"} 126
```