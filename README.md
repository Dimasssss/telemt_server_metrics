# Server Metrics 2026-03-12 03:21:33 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 20194.1 (5h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 172091
telemt_connections_bad_total 1354
telemt_handshake_timeouts_total 3332
telemt_upstream_connect_attempt_total 4656
telemt_upstream_connect_success_total 4656
telemt_upstream_connect_attempts_per_request{bucket="1"} 4656
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2451
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2193
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 103
telemt_me_reconnect_attempts_total 3638
telemt_me_reconnect_success_total 3623
telemt_me_reader_eof_total 3827
telemt_me_idle_close_by_peer_total 3827
telemt_me_route_drop_no_conn_total 62365
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 162429
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 332
telemt_desync_full_logged_total 86
telemt_desync_suppressed_total 246
telemt_desync_frames_bucket_total{bucket="1_2"} 116
telemt_desync_frames_bucket_total{bucket="3_10"} 114
telemt_desync_frames_bucket_total{bucket="gt_10"} 102
telemt_pool_swap_total 20
telemt_me_writer_removed_unexpected_total 3662
telemt_me_writer_restored_same_endpoint_total 3607
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 186
telemt_me_writer_removed_unexpected_minus_restored_total 39
telemt_user_connections_total{user="hello"} 162236
telemt_user_connections_current{user="hello"} 490
telemt_user_octets_from_client{user="hello"} 1290068528 (1.20 GB)
telemt_user_octets_to_client{user="hello"} 50590092644 (47.12 GB)
telemt_user_unique_ips_current{user="hello"} 177
telemt_user_unique_ips_recent_window{user="hello"} 72
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 20194.7 (5h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 57259
telemt_connections_bad_total 125
telemt_handshake_timeouts_total 969
telemt_upstream_connect_attempt_total 5778
telemt_upstream_connect_success_total 5775
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 5778
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2880
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2887
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_keepalive_timeout_total 121
telemt_me_reconnect_attempts_total 4575
telemt_me_reconnect_success_total 4546
telemt_me_reader_eof_total 4823
telemt_me_idle_close_by_peer_total 4823
telemt_me_route_drop_no_conn_total 16143
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 53501
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 104
telemt_desync_full_logged_total 52
telemt_desync_suppressed_total 52
telemt_desync_frames_bucket_total{bucket="1_2"} 51
telemt_desync_frames_bucket_total{bucket="3_10"} 30
telemt_desync_frames_bucket_total{bucket="gt_10"} 23
telemt_pool_swap_total 21
telemt_me_writer_removed_unexpected_total 4579
telemt_me_writer_restored_same_endpoint_total 4537
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 33
telemt_user_connections_total{user="hello"} 53680
telemt_user_connections_current{user="hello"} 187
telemt_user_octets_from_client{user="hello"} 951190639 (907.13 MB)
telemt_user_octets_to_client{user="hello"} 18877692854 (17.58 GB)
telemt_user_msgs_from_client{user="hello"} 353
telemt_user_msgs_to_client{user="hello"} 423
telemt_user_unique_ips_current{user="hello"} 66
telemt_user_unique_ips_recent_window{user="hello"} 27
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 20194.5 (5h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 315055
telemt_connections_bad_total 1532
telemt_handshake_timeouts_total 17759
telemt_upstream_connect_attempt_total 6125
telemt_upstream_connect_success_total 6123
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 6125
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3478
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2616
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_timeout_total 103
telemt_me_reconnect_attempts_total 4781
telemt_me_reconnect_success_total 4726
telemt_me_reader_eof_total 4917
telemt_me_idle_close_by_peer_total 4917
telemt_me_route_drop_no_conn_total 31011
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 99678
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 253
telemt_desync_full_logged_total 86
telemt_desync_suppressed_total 167
telemt_desync_frames_bucket_total{bucket="1_2"} 28
telemt_desync_frames_bucket_total{bucket="3_10"} 99
telemt_desync_frames_bucket_total{bucket="gt_10"} 126
telemt_pool_swap_total 20
telemt_me_writer_removed_unexpected_total 4688
telemt_me_refill_failed_total 1
telemt_me_writer_restored_same_endpoint_total 4685
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_user_connections_total{user="hello"} 100007
telemt_user_connections_current{user="hello"} 287
telemt_user_octets_from_client{user="hello"} 853686928 (814.14 MB)
telemt_user_octets_to_client{user="hello"} 30427512441 (28.34 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 121
telemt_user_unique_ips_recent_window{user="hello"} 46
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 20195.1 (5h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 90321
telemt_connections_bad_total 166
telemt_handshake_timeouts_total 4412
telemt_upstream_connect_attempt_total 6064
telemt_upstream_connect_success_total 6036
telemt_upstream_connect_fail_total 28
telemt_upstream_connect_attempts_per_request{bucket="1"} 6064
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3407
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2626
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 28
telemt_me_keepalive_timeout_total 84
telemt_me_reconnect_attempts_total 5016
telemt_me_reconnect_success_total 4998
telemt_me_reader_eof_total 5298
telemt_me_idle_close_by_peer_total 5298
telemt_me_route_drop_no_conn_total 30556
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 84513
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 134
telemt_desync_full_logged_total 42
telemt_desync_suppressed_total 92
telemt_desync_frames_bucket_total{bucket="1_2"} 30
telemt_desync_frames_bucket_total{bucket="3_10"} 58
telemt_desync_frames_bucket_total{bucket="gt_10"} 46
telemt_pool_swap_total 19
telemt_me_writer_removed_unexpected_total 5031
telemt_me_writer_restored_same_endpoint_total 4977
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 108
telemt_me_writer_removed_unexpected_minus_restored_total 33
telemt_user_connections_total{user="hello"} 84501
telemt_user_connections_current{user="hello"} 222
telemt_user_octets_from_client{user="hello"} 558368580 (532.50 MB)
telemt_user_octets_to_client{user="hello"} 21439155468 (19.97 GB)
telemt_user_unique_ips_current{user="hello"} 83
telemt_user_unique_ips_recent_window{user="hello"} 31
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 20194.7 (5h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 108747
telemt_connections_bad_total 70
telemt_handshake_timeouts_total 699
telemt_upstream_connect_attempt_total 7431
telemt_upstream_connect_success_total 7355
telemt_upstream_connect_fail_total 76
telemt_upstream_connect_attempts_per_request{bucket="1"} 7431
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3714
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3601
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 38
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 76
telemt_me_keepalive_timeout_total 112
telemt_me_reconnect_attempts_total 7804
telemt_me_reconnect_success_total 6306
telemt_me_reader_eof_total 6563
telemt_me_idle_close_by_peer_total 6563
telemt_me_seq_mismatch_total 11
telemt_me_route_drop_no_conn_total 28151
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 103698
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 377
telemt_desync_full_logged_total 128
telemt_desync_suppressed_total 249
telemt_desync_frames_bucket_total{bucket="1_2"} 103
telemt_desync_frames_bucket_total{bucket="3_10"} 153
telemt_desync_frames_bucket_total{bucket="gt_10"} 121
telemt_pool_swap_total 12
telemt_me_writer_removed_unexpected_total 6399
telemt_me_refill_failed_total 46
telemt_me_writer_restored_same_endpoint_total 6290
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 93
telemt_user_connections_total{user="hello"} 103674
telemt_user_connections_current{user="hello"} 290
telemt_user_octets_from_client{user="hello"} 625479640 (596.50 MB)
telemt_user_octets_to_client{user="hello"} 22606453148 (21.05 GB)
telemt_user_unique_ips_current{user="hello"} 90
telemt_user_unique_ips_recent_window{user="hello"} 40
```