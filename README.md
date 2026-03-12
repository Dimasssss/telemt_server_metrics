# Server Metrics 2026-03-12 12:01:48 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 21789.0 (6h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 740246
telemt_connections_bad_total 1500
telemt_handshake_timeouts_total 4285
telemt_upstream_connect_attempt_total 4327
telemt_upstream_connect_success_total 4299
telemt_upstream_connect_fail_total 28
telemt_upstream_connect_attempts_per_request{bucket="1"} 4327
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2343
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1952
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 28
telemt_me_keepalive_timeout_total 323
telemt_me_reconnect_attempts_total 7052
telemt_me_reconnect_success_total 3159
telemt_me_reader_eof_total 3400
telemt_me_idle_close_by_peer_total 3400
telemt_me_route_drop_no_conn_total 260581
telemt_me_route_drop_channel_closed_total 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 714282
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3619
telemt_desync_full_logged_total 917
telemt_desync_suppressed_total 2702
telemt_desync_frames_bucket_total{bucket="1_2"} 931
telemt_desync_frames_bucket_total{bucket="3_10"} 1309
telemt_desync_frames_bucket_total{bucket="gt_10"} 1379
telemt_pool_swap_total 15
telemt_me_writer_removed_unexpected_total 3314
telemt_me_refill_failed_total 121
telemt_me_writer_restored_same_endpoint_total 3146
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 155
telemt_user_connections_total{user="hello"} 714131
telemt_user_connections_current{user="hello"} 1591
telemt_user_octets_from_client{user="hello"} 12444834948 (11.59 GB)
telemt_user_octets_to_client{user="hello"} 198080248584 (184.48 GB)
telemt_user_unique_ips_current{user="hello"} 429
telemt_user_unique_ips_recent_window{user="hello"} 249
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 51409.5 (14h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 382574
telemt_connections_bad_total 4605
telemt_handshake_timeouts_total 19320
telemt_upstream_connect_attempt_total 12583
telemt_upstream_connect_success_total 12576
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 12583
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6201
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6359
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 16
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_keepalive_timeout_total 1038
telemt_me_reconnect_attempts_total 9860
telemt_me_reconnect_success_total 9803
telemt_me_reader_eof_total 10418
telemt_me_idle_close_by_peer_total 10418
telemt_me_route_drop_no_conn_total 108662
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 337328
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1032
telemt_desync_full_logged_total 349
telemt_desync_suppressed_total 683
telemt_desync_frames_bucket_total{bucket="1_2"} 389
telemt_desync_frames_bucket_total{bucket="3_10"} 358
telemt_desync_frames_bucket_total{bucket="gt_10"} 285
telemt_pool_swap_total 54
telemt_me_writer_removed_unexpected_total 9892
telemt_me_writer_restored_same_endpoint_total 9794
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 89
telemt_user_connections_total{user="hello"} 337792
telemt_user_connections_current{user="hello"} 740
telemt_user_octets_from_client{user="hello"} 4620749099 (4.30 GB)
telemt_user_octets_to_client{user="hello"} 118297050294 (110.17 GB)
telemt_user_msgs_from_client{user="hello"} 353
telemt_user_msgs_to_client{user="hello"} 423
telemt_user_unique_ips_current{user="hello"} 170
telemt_user_unique_ips_recent_window{user="hello"} 101
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 51409.5 (14h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 875637
telemt_connections_bad_total 4929
telemt_handshake_timeouts_total 65556
telemt_upstream_connect_attempt_total 12666
telemt_upstream_connect_success_total 12661
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 12666
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6934
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5672
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 51
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 857
telemt_me_reconnect_attempts_total 9800
telemt_me_reconnect_success_total 9718
telemt_me_reader_eof_total 10213
telemt_me_idle_close_by_peer_total 10213
telemt_me_route_drop_no_conn_total 210748
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 589543
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2730
telemt_desync_full_logged_total 808
telemt_desync_suppressed_total 1922
telemt_desync_frames_bucket_total{bucket="1_2"} 379
telemt_desync_frames_bucket_total{bucket="3_10"} 952
telemt_desync_frames_bucket_total{bucket="gt_10"} 1399
telemt_pool_swap_total 51
telemt_me_writer_removed_unexpected_total 9740
telemt_me_refill_failed_total 1
telemt_me_writer_restored_same_endpoint_total 9677
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 22
telemt_user_connections_total{user="hello"} 589776
telemt_user_connections_current{user="hello"} 966
telemt_user_octets_from_client{user="hello"} 7796448856 (7.26 GB)
telemt_user_octets_to_client{user="hello"} 187267213417 (174.41 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 265
telemt_user_unique_ips_recent_window{user="hello"} 168
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 51409.7 (14h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 486301
telemt_connections_bad_total 7615
telemt_handshake_timeouts_total 46057
telemt_upstream_connect_attempt_total 13720
telemt_upstream_connect_success_total 13664
telemt_upstream_connect_fail_total 56
telemt_upstream_connect_attempts_per_request{bucket="1"} 13720
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7787
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5865
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 12
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 56
telemt_me_keepalive_timeout_total 1262
telemt_me_reconnect_attempts_total 11126
telemt_me_reconnect_success_total 11080
telemt_me_reader_eof_total 11735
telemt_me_idle_close_by_peer_total 11735
telemt_me_route_drop_no_conn_total 158712
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 402723
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 811
telemt_desync_full_logged_total 283
telemt_desync_suppressed_total 528
telemt_desync_frames_bucket_total{bucket="1_2"} 240
telemt_desync_frames_bucket_total{bucket="3_10"} 340
telemt_desync_frames_bucket_total{bucket="gt_10"} 231
telemt_pool_swap_total 48
telemt_me_writer_removed_unexpected_total 11162
telemt_me_writer_restored_same_endpoint_total 11059
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 108
telemt_me_writer_removed_unexpected_minus_restored_total 82
telemt_user_connections_total{user="hello"} 402546
telemt_user_connections_current{user="hello"} 629
telemt_user_octets_from_client{user="hello"} 4577558148 (4.26 GB)
telemt_user_octets_to_client{user="hello"} 151694695032 (141.28 GB)
telemt_user_unique_ips_current{user="hello"} 176
telemt_user_unique_ips_recent_window{user="hello"} 100
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 51409.6 (14h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 543596
telemt_connections_bad_total 1693
telemt_handshake_timeouts_total 4234
telemt_upstream_connect_attempt_total 16813
telemt_upstream_connect_success_total 16613
telemt_upstream_connect_fail_total 199
telemt_upstream_connect_attempts_per_request{bucket="1"} 16812
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8504
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8014
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 89
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 199
telemt_me_keepalive_timeout_total 952
telemt_me_reconnect_attempts_total 17307
telemt_me_reconnect_success_total 14021
telemt_me_reader_eof_total 14597
telemt_me_idle_close_by_peer_total 14597
telemt_me_seq_mismatch_total 22
telemt_me_route_drop_no_conn_total 180077
telemt_me_route_drop_channel_closed_total 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 508643
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 26
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 2127
telemt_desync_full_logged_total 719
telemt_desync_suppressed_total 1408
telemt_desync_frames_bucket_total{bucket="1_2"} 628
telemt_desync_frames_bucket_total{bucket="3_10"} 736
telemt_desync_frames_bucket_total{bucket="gt_10"} 763
telemt_pool_swap_total 26
telemt_me_writer_removed_unexpected_total 14261
telemt_me_refill_failed_total 101
telemt_me_writer_restored_same_endpoint_total 13994
telemt_me_writer_restored_fallback_total 27
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 240
telemt_user_connections_total{user="hello"} 508563
telemt_user_connections_current{user="hello"} 794
telemt_user_octets_from_client{user="hello"} 5930625132 (5.52 GB)
telemt_user_octets_to_client{user="hello"} 126112091552 (117.45 GB)
telemt_user_unique_ips_current{user="hello"} 215
telemt_user_unique_ips_recent_window{user="hello"} 132
```