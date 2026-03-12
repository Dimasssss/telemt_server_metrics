# Server Metrics 2026-03-12 14:34:50 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 30970.6 (8h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1103025
telemt_connections_bad_total 14918
telemt_handshake_timeouts_total 11600
telemt_upstream_connect_attempt_total 6125
telemt_upstream_connect_success_total 6091
telemt_upstream_connect_fail_total 34
telemt_upstream_connect_attempts_per_request{bucket="1"} 6125
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3246
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2835
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 34
telemt_me_keepalive_timeout_total 405
telemt_me_reconnect_attempts_total 8402
telemt_me_reconnect_success_total 4500
telemt_me_reader_eof_total 4804
telemt_me_idle_close_by_peer_total 4803
telemt_me_route_drop_no_conn_total 390266
telemt_me_route_drop_channel_closed_total 8
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1041535
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5597
telemt_desync_full_logged_total 1406
telemt_desync_suppressed_total 4191
telemt_desync_frames_bucket_total{bucket="1_2"} 1432
telemt_desync_frames_bucket_total{bucket="3_10"} 2009
telemt_desync_frames_bucket_total{bucket="gt_10"} 2156
telemt_pool_swap_total 21
telemt_me_writer_removed_unexpected_total 4674
telemt_me_refill_failed_total 121
telemt_me_writer_restored_same_endpoint_total 4487
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 174
telemt_user_connections_total{user="hello"} 1041273
telemt_user_connections_current{user="hello"} 1464
telemt_user_octets_from_client{user="hello"} 16621645752 (15.48 GB)
telemt_user_octets_to_client{user="hello"} 303292216496 (282.46 GB)
telemt_user_unique_ips_current{user="hello"} 407
telemt_user_unique_ips_recent_window{user="hello"} 200
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 60591.0 (16h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 512908
telemt_connections_bad_total 5358
telemt_handshake_timeouts_total 26147
telemt_upstream_connect_attempt_total 14464
telemt_upstream_connect_success_total 14457
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 14464
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7164
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7277
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 16
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_keepalive_timeout_total 1161
telemt_me_reconnect_attempts_total 11300
telemt_me_reconnect_success_total 11236
telemt_me_reader_eof_total 11945
telemt_me_idle_close_by_peer_total 11945
telemt_me_route_drop_no_conn_total 148961
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 456789
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1712
telemt_desync_full_logged_total 540
telemt_desync_suppressed_total 1172
telemt_desync_frames_bucket_total{bucket="1_2"} 721
telemt_desync_frames_bucket_total{bucket="3_10"} 564
telemt_desync_frames_bucket_total{bucket="gt_10"} 427
telemt_pool_swap_total 62
telemt_me_writer_removed_unexpected_total 11339
telemt_me_writer_restored_same_endpoint_total 11227
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 103
telemt_user_connections_total{user="hello"} 457289
telemt_user_connections_current{user="hello"} 676
telemt_user_octets_from_client{user="hello"} 6994275087 (6.51 GB)
telemt_user_octets_to_client{user="hello"} 162320996478 (151.17 GB)
telemt_user_msgs_from_client{user="hello"} 353
telemt_user_msgs_to_client{user="hello"} 423
telemt_user_unique_ips_current{user="hello"} 177
telemt_user_unique_ips_recent_window{user="hello"} 106
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 60590.8 (16h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1104873
telemt_connections_bad_total 6011
telemt_handshake_timeouts_total 79384
telemt_upstream_connect_attempt_total 14568
telemt_upstream_connect_success_total 14563
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 14568
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7911
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6592
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 56
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 943
telemt_me_reconnect_attempts_total 12385
telemt_me_reconnect_success_total 11164
telemt_me_reader_eof_total 11780
telemt_me_idle_close_by_peer_total 11780
telemt_me_route_drop_no_conn_total 290219
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 797268
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3333
telemt_desync_full_logged_total 1022
telemt_desync_suppressed_total 2311
telemt_desync_frames_bucket_total{bucket="1_2"} 492
telemt_desync_frames_bucket_total{bucket="3_10"} 1207
telemt_desync_frames_bucket_total{bucket="gt_10"} 1634
telemt_pool_swap_total 58
telemt_me_writer_removed_unexpected_total 11243
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 11123
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 79
telemt_user_connections_total{user="hello"} 797456
telemt_user_connections_current{user="hello"} 893
telemt_user_octets_from_client{user="hello"} 10466691672 (9.75 GB)
telemt_user_octets_to_client{user="hello"} 253891359289 (236.45 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 255
telemt_user_unique_ips_recent_window{user="hello"} 146
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 60591.3 (16h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 646016
telemt_connections_bad_total 7691
telemt_handshake_timeouts_total 56551
telemt_upstream_connect_attempt_total 16079
telemt_upstream_connect_success_total 16014
telemt_upstream_connect_fail_total 65
telemt_upstream_connect_attempts_per_request{bucket="1"} 16079
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9084
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6917
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 13
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 65
telemt_me_keepalive_timeout_total 1345
telemt_me_reconnect_attempts_total 14210
telemt_me_reconnect_success_total 12974
telemt_me_reader_eof_total 13745
telemt_me_idle_close_by_peer_total 13745
telemt_me_route_drop_no_conn_total 217991
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 549071
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1092
telemt_desync_full_logged_total 381
telemt_desync_suppressed_total 711
telemt_desync_frames_bucket_total{bucket="1_2"} 304
telemt_desync_frames_bucket_total{bucket="3_10"} 446
telemt_desync_frames_bucket_total{bucket="gt_10"} 342
telemt_pool_swap_total 53
telemt_me_writer_removed_unexpected_total 13111
telemt_me_refill_failed_total 37
telemt_me_writer_restored_same_endpoint_total 12953
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 108
telemt_me_writer_removed_unexpected_minus_restored_total 137
telemt_user_connections_total{user="hello"} 548574
telemt_user_connections_current{user="hello"} 720
telemt_user_octets_from_client{user="hello"} 6020050284 (5.61 GB)
telemt_user_octets_to_client{user="hello"} 220877121436 (205.71 GB)
telemt_user_unique_ips_current{user="hello"} 195
telemt_user_unique_ips_recent_window{user="hello"} 103
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 60591.3 (16h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 727758
telemt_connections_bad_total 4771
telemt_handshake_timeouts_total 5817
telemt_upstream_connect_attempt_total 18934
telemt_upstream_connect_success_total 18705
telemt_upstream_connect_fail_total 229
telemt_upstream_connect_attempts_per_request{bucket="1"} 18934
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9480
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9124
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 94
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 229
telemt_me_keepalive_timeout_total 1071
telemt_me_reconnect_attempts_total 22894
telemt_me_reconnect_success_total 15665
telemt_me_reader_eof_total 16423
telemt_me_idle_close_by_peer_total 16423
telemt_me_seq_mismatch_total 27
telemt_me_route_drop_no_conn_total 251041
telemt_me_route_drop_channel_closed_total 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 674115
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 31
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 2753
telemt_desync_full_logged_total 928
telemt_desync_suppressed_total 1825
telemt_desync_frames_bucket_total{bucket="1_2"} 786
telemt_desync_frames_bucket_total{bucket="3_10"} 954
telemt_desync_frames_bucket_total{bucket="gt_10"} 1013
telemt_pool_swap_total 30
telemt_me_writer_removed_unexpected_total 16051
telemt_me_refill_failed_total 224
telemt_me_writer_restored_same_endpoint_total 15631
telemt_me_writer_restored_fallback_total 34
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 386
telemt_user_connections_total{user="hello"} 674016
telemt_user_connections_current{user="hello"} 753
telemt_user_octets_from_client{user="hello"} 7853628388 (7.31 GB)
telemt_user_octets_to_client{user="hello"} 183506305488 (170.90 GB)
telemt_user_unique_ips_current{user="hello"} 229
telemt_user_unique_ips_recent_window{user="hello"} 122
```