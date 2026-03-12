# Server Metrics 2026-03-12 05:13:49 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 26929.5 (7h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 280002
telemt_connections_bad_total 1396
telemt_handshake_timeouts_total 4580
telemt_upstream_connect_attempt_total 6034
telemt_upstream_connect_success_total 6034
telemt_upstream_connect_attempts_per_request{bucket="1"} 6034
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3212
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2808
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11
telemt_me_keepalive_timeout_total 125
telemt_me_reconnect_attempts_total 4713
telemt_me_reconnect_success_total 4695
telemt_me_reader_eof_total 4962
telemt_me_idle_close_by_peer_total 4962
telemt_me_route_drop_no_conn_total 100237
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 266746
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 578
telemt_desync_full_logged_total 168
telemt_desync_suppressed_total 410
telemt_desync_frames_bucket_total{bucket="1_2"} 173
telemt_desync_frames_bucket_total{bucket="3_10"} 216
telemt_desync_frames_bucket_total{bucket="gt_10"} 189
telemt_pool_swap_total 27
telemt_me_writer_removed_unexpected_total 4743
telemt_me_writer_restored_same_endpoint_total 4679
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 186
telemt_me_writer_removed_unexpected_minus_restored_total 48
telemt_user_connections_total{user="hello"} 266480
telemt_user_connections_current{user="hello"} 968
telemt_user_octets_from_client{user="hello"} 2582669860 (2.41 GB)
telemt_user_octets_to_client{user="hello"} 81462240132 (75.87 GB)
telemt_user_unique_ips_current{user="hello"} 289
telemt_user_unique_ips_recent_window{user="hello"} 129
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 26930.0 (7h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 92174
telemt_connections_bad_total 658
telemt_handshake_timeouts_total 1759
telemt_upstream_connect_attempt_total 7343
telemt_upstream_connect_success_total 7340
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 7343
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3669
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3662
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_keepalive_timeout_total 135
telemt_me_reconnect_attempts_total 5837
telemt_me_reconnect_success_total 5804
telemt_me_reader_eof_total 6168
telemt_me_idle_close_by_peer_total 6168
telemt_me_route_drop_no_conn_total 27453
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 83549
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 245
telemt_desync_full_logged_total 109
telemt_desync_suppressed_total 136
telemt_desync_frames_bucket_total{bucket="1_2"} 79
telemt_desync_frames_bucket_total{bucket="3_10"} 87
telemt_desync_frames_bucket_total{bucket="gt_10"} 79
telemt_pool_swap_total 28
telemt_me_writer_removed_unexpected_total 5849
telemt_me_writer_restored_same_endpoint_total 5795
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 45
telemt_user_connections_total{user="hello"} 83736
telemt_user_connections_current{user="hello"} 321
telemt_user_octets_from_client{user="hello"} 1362207755 (1.27 GB)
telemt_user_octets_to_client{user="hello"} 32013144662 (29.81 GB)
telemt_user_msgs_from_client{user="hello"} 353
telemt_user_msgs_to_client{user="hello"} 423
telemt_user_unique_ips_current{user="hello"} 112
telemt_user_unique_ips_recent_window{user="hello"} 50
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 26929.9 (7h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 387755
telemt_connections_bad_total 2069
telemt_handshake_timeouts_total 25620
telemt_upstream_connect_attempt_total 7633
telemt_upstream_connect_success_total 7631
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 7633
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4314
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3284
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 29
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_timeout_total 120
telemt_me_reconnect_attempts_total 5984
telemt_me_reconnect_success_total 5922
telemt_me_reader_eof_total 6193
telemt_me_idle_close_by_peer_total 6193
telemt_me_route_drop_no_conn_total 51079
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 156397
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 585
telemt_desync_full_logged_total 206
telemt_desync_suppressed_total 379
telemt_desync_frames_bucket_total{bucket="1_2"} 68
telemt_desync_frames_bucket_total{bucket="3_10"} 209
telemt_desync_frames_bucket_total{bucket="gt_10"} 308
telemt_pool_swap_total 27
telemt_me_writer_removed_unexpected_total 5895
telemt_me_refill_failed_total 1
telemt_me_writer_restored_same_endpoint_total 5881
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_user_connections_total{user="hello"} 156712
telemt_user_connections_current{user="hello"} 487
telemt_user_octets_from_client{user="hello"} 1515291792 (1.41 GB)
telemt_user_octets_to_client{user="hello"} 47916760005 (44.63 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 165
telemt_user_unique_ips_recent_window{user="hello"} 66
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 26930.4 (7h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 133696
telemt_connections_bad_total 1688
telemt_handshake_timeouts_total 8909
telemt_upstream_connect_attempt_total 7871
telemt_upstream_connect_success_total 7836
telemt_upstream_connect_fail_total 35
telemt_upstream_connect_attempts_per_request{bucket="1"} 7871
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4516
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3317
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 35
telemt_me_keepalive_timeout_total 115
telemt_me_reconnect_attempts_total 6510
telemt_me_reconnect_success_total 6488
telemt_me_reader_eof_total 6887
telemt_me_idle_close_by_peer_total 6887
telemt_me_route_drop_no_conn_total 45088
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 121312
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 178
telemt_desync_full_logged_total 57
telemt_desync_suppressed_total 121
telemt_desync_frames_bucket_total{bucket="1_2"} 49
telemt_desync_frames_bucket_total{bucket="3_10"} 74
telemt_desync_frames_bucket_total{bucket="gt_10"} 55
telemt_pool_swap_total 26
telemt_me_writer_removed_unexpected_total 6528
telemt_me_writer_restored_same_endpoint_total 6467
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 108
telemt_me_writer_removed_unexpected_minus_restored_total 40
telemt_user_connections_total{user="hello"} 121291
telemt_user_connections_current{user="hello"} 346
telemt_user_octets_from_client{user="hello"} 1017426300 (970.29 MB)
telemt_user_octets_to_client{user="hello"} 35182014332 (32.77 GB)
telemt_user_unique_ips_current{user="hello"} 110
telemt_user_unique_ips_recent_window{user="hello"} 55
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 26930.2 (7h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 155283
telemt_connections_bad_total 267
telemt_handshake_timeouts_total 919
telemt_upstream_connect_attempt_total 9836
telemt_upstream_connect_success_total 9727
telemt_upstream_connect_fail_total 109
telemt_upstream_connect_attempts_per_request{bucket="1"} 9836
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5076
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4594
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 52
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 109
telemt_me_keepalive_timeout_total 145
telemt_me_reconnect_attempts_total 9873
telemt_me_reconnect_success_total 8368
telemt_me_reader_eof_total 8696
telemt_me_idle_close_by_peer_total 8696
telemt_me_seq_mismatch_total 14
telemt_me_route_drop_no_conn_total 44334
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 148475
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 546
telemt_desync_full_logged_total 191
telemt_desync_suppressed_total 355
telemt_desync_frames_bucket_total{bucket="1_2"} 141
telemt_desync_frames_bucket_total{bucket="3_10"} 210
telemt_desync_frames_bucket_total{bucket="gt_10"} 195
telemt_pool_swap_total 14
telemt_me_writer_removed_unexpected_total 8486
telemt_me_refill_failed_total 46
telemt_me_writer_restored_same_endpoint_total 8349
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 118
telemt_user_connections_total{user="hello"} 148458
telemt_user_connections_current{user="hello"} 421
telemt_user_octets_from_client{user="hello"} 1092340892 (1.02 GB)
telemt_user_octets_to_client{user="hello"} 32875982480 (30.62 GB)
telemt_user_unique_ips_current{user="hello"} 121
telemt_user_unique_ips_recent_window{user="hello"} 54
```