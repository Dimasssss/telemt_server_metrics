# Server Metrics 2026-03-13 15:41:13 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 121355.4 (33h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3785793
telemt_connections_bad_total 37429
telemt_handshake_timeouts_total 79953
telemt_upstream_connect_attempt_total 23599
telemt_upstream_connect_success_total 23464
telemt_upstream_connect_fail_total 135
telemt_upstream_connect_attempts_per_request{bucket="1"} 23599
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12091
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11312
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 61
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 135
telemt_me_keepalive_timeout_total 2196
telemt_me_reconnect_attempts_total 27535
telemt_me_reconnect_success_total 17445
telemt_me_reader_eof_total 18748
telemt_me_idle_close_by_peer_total 18747
telemt_me_route_drop_no_conn_total 1406093
telemt_me_route_drop_channel_closed_total 18
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3467613
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 13998
telemt_desync_full_logged_total 3699
telemt_desync_suppressed_total 10299
telemt_desync_frames_bucket_total{bucket="1_2"} 3512
telemt_desync_frames_bucket_total{bucket="3_10"} 5296
telemt_desync_frames_bucket_total{bucket="gt_10"} 5190
telemt_pool_swap_total 101
telemt_me_writer_removed_unexpected_total 18000
telemt_me_refill_failed_total 312
telemt_me_writer_restored_same_endpoint_total 17432
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 555
telemt_user_connections_total{user="hello"} 3467416
telemt_user_connections_current{user="hello"} 1522
telemt_user_octets_from_client{user="hello"} 47244079220 (44.00 GB)
telemt_user_octets_to_client{user="hello"} 1088510873692 (1013.75 GB)
telemt_user_unique_ips_current{user="hello"} 432
telemt_user_unique_ips_recent_window{user="hello"} 219
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 21019.4 (5h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 301637
telemt_connections_bad_total 15686
telemt_handshake_timeouts_total 8091
telemt_upstream_connect_attempt_total 4959
telemt_upstream_connect_success_total 4873
telemt_upstream_connect_fail_total 86
telemt_upstream_connect_attempts_per_request{bucket="1"} 4959
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2520
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2303
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 13
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 37
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 86
telemt_me_keepalive_timeout_total 99
telemt_me_reconnect_attempts_total 6060
telemt_me_reconnect_success_total 3769
telemt_me_reader_eof_total 4007
telemt_me_idle_close_by_peer_total 4007
telemt_me_route_drop_no_conn_total 109510
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 270000
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 6
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1036
telemt_desync_full_logged_total 264
telemt_desync_suppressed_total 772
telemt_desync_frames_bucket_total{bucket="1_2"} 199
telemt_desync_frames_bucket_total{bucket="3_10"} 500
telemt_desync_frames_bucket_total{bucket="gt_10"} 337
telemt_pool_swap_total 17
telemt_me_writer_removed_unexpected_total 3889
telemt_me_refill_failed_total 69
telemt_me_writer_restored_same_endpoint_total 3762
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 22
telemt_me_writer_removed_unexpected_minus_restored_total 120
telemt_user_connections_total{user="hello"} 270029
telemt_user_connections_current{user="hello"} 550
telemt_user_octets_from_client{user="hello"} 2695287284 (2.51 GB)
telemt_user_octets_to_client{user="hello"} 76965678204 (71.68 GB)
telemt_user_unique_ips_current{user="hello"} 167
telemt_user_unique_ips_recent_window{user="hello"} 93
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 150976.0 (41h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2801877
telemt_connections_bad_total 27794
telemt_handshake_timeouts_total 187040
telemt_upstream_connect_attempt_total 33873
telemt_upstream_connect_success_total 33863
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 33873
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17546
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16187
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 125
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_keepalive_timeout_total 3274
telemt_me_reconnect_attempts_total 28574
telemt_me_reconnect_success_total 26025
telemt_me_reader_eof_total 27600
telemt_me_idle_close_by_peer_total 27599
telemt_me_route_drop_no_conn_total 946284
telemt_me_route_drop_channel_closed_total 17
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2300462
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8178
telemt_desync_full_logged_total 2706
telemt_desync_suppressed_total 5472
telemt_desync_frames_bucket_total{bucket="1_2"} 1306
telemt_desync_frames_bucket_total{bucket="3_10"} 2969
telemt_desync_frames_bucket_total{bucket="gt_10"} 3903
telemt_pool_swap_total 142
telemt_me_writer_removed_unexpected_total 26331
telemt_me_refill_failed_total 75
telemt_me_writer_restored_same_endpoint_total 25984
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 306
telemt_user_connections_total{user="hello"} 2299861
telemt_user_connections_current{user="hello"} 1048
telemt_user_octets_from_client{user="hello"} 38005013748 (35.39 GB)
telemt_user_octets_to_client{user="hello"} 805416382661 (750.10 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 310
telemt_user_unique_ips_recent_window{user="hello"} 164
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 150976.5 (41h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1782418
telemt_connections_bad_total 18137
telemt_handshake_timeouts_total 137757
telemt_upstream_connect_attempt_total 47600
telemt_upstream_connect_success_total 45269
telemt_upstream_connect_fail_total 2194
telemt_upstream_connect_attempts_per_request{bucket="1"} 47326
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 27199
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17979
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 91
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2193
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 11882
telemt_me_reconnect_attempts_total 40882
telemt_me_reconnect_success_total 31909
telemt_me_reader_eof_total 34279
telemt_me_idle_close_by_peer_total 34272
telemt_me_route_drop_no_conn_total 639782
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1487443
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2983
telemt_desync_full_logged_total 967
telemt_desync_suppressed_total 2016
telemt_desync_frames_bucket_total{bucket="1_2"} 803
telemt_desync_frames_bucket_total{bucket="3_10"} 1231
telemt_desync_frames_bucket_total{bucket="gt_10"} 949
telemt_pool_swap_total 131
telemt_me_writer_removed_unexpected_total 32433
telemt_me_refill_failed_total 274
telemt_me_writer_restored_same_endpoint_total 31885
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 524
telemt_user_connections_total{user="hello"} 1492152
telemt_user_connections_current{user="hello"} 557
telemt_user_octets_from_client{user="hello"} 23203100441 (21.61 GB)
telemt_user_octets_to_client{user="hello"} 572184238890 (532.89 GB)
telemt_user_msgs_from_client{user="hello"} 44500
telemt_user_msgs_to_client{user="hello"} 116355
telemt_user_unique_ips_current{user="hello"} 182
telemt_user_unique_ips_recent_window{user="hello"} 109
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 20412.0 (5h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 327768
telemt_connections_bad_total 4005
telemt_handshake_timeouts_total 3037
telemt_upstream_connect_attempt_total 4405
telemt_upstream_connect_success_total 4272
telemt_upstream_connect_fail_total 133
telemt_upstream_connect_attempts_per_request{bucket="1"} 4405
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2019
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2249
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 133
telemt_me_keepalive_timeout_total 84
telemt_me_reconnect_attempts_total 13800
telemt_me_reconnect_success_total 3226
telemt_me_reader_eof_total 3606
telemt_me_idle_close_by_peer_total 3606
telemt_me_route_drop_no_conn_total 130329
telemt_me_route_drop_channel_closed_total 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 307199
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 3
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 953
telemt_desync_full_logged_total 307
telemt_desync_suppressed_total 646
telemt_desync_frames_bucket_total{bucket="1_2"} 332
telemt_desync_frames_bucket_total{bucket="3_10"} 373
telemt_desync_frames_bucket_total{bucket="gt_10"} 248
telemt_pool_swap_total 6
telemt_me_writer_removed_unexpected_total 3574
telemt_me_refill_failed_total 329
telemt_me_writer_restored_same_endpoint_total 3222
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 348
telemt_user_connections_total{user="hello"} 307175
telemt_user_connections_current{user="hello"} 803
telemt_user_octets_from_client{user="hello"} 3611908212 (3.36 GB)
telemt_user_octets_to_client{user="hello"} 96479749480 (89.85 GB)
telemt_user_unique_ips_current{user="hello"} 213
telemt_user_unique_ips_recent_window{user="hello"} 104
```