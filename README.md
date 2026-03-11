# Server Metrics 2026-03-11 01:42:09 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 40504.7 (11h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 819109
telemt_connections_bad_total 9529
telemt_handshake_timeouts_total 10602
telemt_upstream_connect_attempt_total 8781
telemt_upstream_connect_success_total 8772
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 8781
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4388
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4325
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 58
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 487
telemt_me_reconnect_attempts_total 18369
telemt_me_reconnect_success_total 6702
telemt_me_reader_eof_total 7332
telemt_me_idle_close_by_peer_total 7332
telemt_me_route_drop_no_conn_total 334066
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 774893
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3623
telemt_desync_full_logged_total 1020
telemt_desync_suppressed_total 2603
telemt_desync_frames_bucket_total{bucket="1_2"} 1057
telemt_desync_frames_bucket_total{bucket="3_10"} 1352
telemt_desync_frames_bucket_total{bucket="gt_10"} 1214
telemt_pool_swap_total 24
telemt_me_writer_removed_unexpected_total 7122
telemt_me_refill_failed_total 363
telemt_me_writer_restored_same_endpoint_total 6696
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 420
telemt_user_connections_total{user="hello"} 774651
telemt_user_connections_current{user="hello"} 409
telemt_user_octets_from_client{user="hello"} 10627338760 (9.90 GB)
telemt_user_octets_to_client{user="hello"} 235190070424 (219.04 GB)
telemt_user_unique_ips_current{user="hello"} 158
telemt_user_unique_ips_recent_window{user="hello"} 52
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 40561.5 (11h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 352002
telemt_connections_bad_total 2407
telemt_handshake_timeouts_total 17971
telemt_upstream_connect_attempt_total 16078
telemt_upstream_connect_success_total 13192
telemt_upstream_connect_fail_total 2886
telemt_upstream_connect_attempts_per_request{bucket="1"} 16078
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5743
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5208
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 209
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2032
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2886
telemt_me_keepalive_timeout_total 1721
telemt_me_reconnect_attempts_total 9002
telemt_me_reconnect_success_total 8186
telemt_me_reader_eof_total 8642
telemt_me_idle_close_by_peer_total 8640
telemt_me_route_drop_no_conn_total 174865
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 300854
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1787
telemt_desync_full_logged_total 513
telemt_desync_suppressed_total 1274
telemt_desync_frames_bucket_total{bucket="1_2"} 547
telemt_desync_frames_bucket_total{bucket="3_10"} 637
telemt_desync_frames_bucket_total{bucket="gt_10"} 603
telemt_pool_swap_total 32
telemt_me_writer_removed_unexpected_total 8295
telemt_me_refill_failed_total 22
telemt_me_writer_restored_same_endpoint_total 8165
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 86
telemt_me_writer_removed_unexpected_minus_restored_total 109
telemt_user_connections_total{user="hello"} 303123
telemt_user_connections_current{user="hello"} 179
telemt_user_octets_from_client{user="hello"} 2870202194 (2.67 GB)
telemt_user_octets_to_client{user="hello"} 71790773700 (66.86 GB)
telemt_user_msgs_from_client{user="hello"} 7933
telemt_user_msgs_to_client{user="hello"} 11226
telemt_user_unique_ips_current{user="hello"} 68
telemt_user_unique_ips_recent_window{user="hello"} 25
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 40561.3 (11h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 585408
telemt_connections_bad_total 4227
telemt_handshake_timeouts_total 34309
telemt_upstream_connect_attempt_total 11016
telemt_upstream_connect_success_total 10862
telemt_upstream_connect_fail_total 154
telemt_upstream_connect_attempts_per_request{bucket="1"} 11016
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6072
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4721
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 69
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 154
telemt_me_keepalive_timeout_total 519
telemt_me_reconnect_attempts_total 18799
telemt_me_reconnect_success_total 7736
telemt_me_reader_eof_total 8420
telemt_me_idle_close_by_peer_total 8420
telemt_me_route_drop_no_conn_total 200022
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 518198
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1522
telemt_desync_full_logged_total 435
telemt_desync_suppressed_total 1087
telemt_desync_frames_bucket_total{bucket="1_2"} 344
telemt_desync_frames_bucket_total{bucket="3_10"} 523
telemt_desync_frames_bucket_total{bucket="gt_10"} 655
telemt_pool_swap_total 25
telemt_me_writer_removed_unexpected_total 8187
telemt_me_refill_failed_total 343
telemt_me_writer_restored_same_endpoint_total 7725
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 451
telemt_user_connections_total{user="hello"} 519112
telemt_user_connections_current{user="hello"} 211
telemt_user_octets_from_client{user="hello"} 6936002305 (6.46 GB)
telemt_user_octets_to_client{user="hello"} 159056277057 (148.13 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 88
telemt_user_unique_ips_recent_window{user="hello"} 32
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 40561.6 (11h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 434650
telemt_connections_bad_total 38500
telemt_handshake_timeouts_total 41494
telemt_upstream_connect_attempt_total 11721
telemt_upstream_connect_success_total 11721
telemt_upstream_connect_attempts_per_request{bucket="1"} 11721
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6589
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5130
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_timeout_total 424
telemt_me_reconnect_attempts_total 10695
telemt_me_reconnect_success_total 9660
telemt_me_reader_eof_total 10221
telemt_me_idle_close_by_peer_total 10221
telemt_me_seq_mismatch_total 7
telemt_me_route_drop_no_conn_total 131402
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 341152
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 732
telemt_desync_full_logged_total 292
telemt_desync_suppressed_total 440
telemt_desync_frames_bucket_total{bucket="1_2"} 279
telemt_desync_frames_bucket_total{bucket="3_10"} 253
telemt_desync_frames_bucket_total{bucket="gt_10"} 200
telemt_pool_swap_total 33
telemt_me_writer_removed_unexpected_total 9780
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 9642
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 120
telemt_user_connections_total{user="hello"} 340823
telemt_user_connections_current{user="hello"} 153
telemt_user_octets_from_client{user="hello"} 4258195188 (3.97 GB)
telemt_user_octets_to_client{user="hello"} 92470052468 (86.12 GB)
telemt_user_unique_ips_current{user="hello"} 59
telemt_user_unique_ips_recent_window{user="hello"} 28
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 40561.3 (11h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 458885
telemt_connections_bad_total 5338
telemt_handshake_timeouts_total 2955
telemt_upstream_connect_attempt_total 12091
telemt_upstream_connect_success_total 12041
telemt_upstream_connect_fail_total 50
telemt_upstream_connect_attempts_per_request{bucket="1"} 12091
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6218
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5707
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 114
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 50
telemt_me_keepalive_timeout_total 516
telemt_me_reconnect_attempts_total 13714
telemt_me_reconnect_success_total 9944
telemt_me_reader_eof_total 10465
telemt_me_idle_close_by_peer_total 10465
telemt_me_route_drop_no_conn_total 150672
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 420171
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 2293
telemt_desync_full_logged_total 890
telemt_desync_suppressed_total 1403
telemt_desync_frames_bucket_total{bucket="1_2"} 849
telemt_desync_frames_bucket_total{bucket="3_10"} 974
telemt_desync_frames_bucket_total{bucket="gt_10"} 470
telemt_pool_swap_total 21
telemt_me_writer_removed_unexpected_total 10190
telemt_me_refill_failed_total 116
telemt_me_writer_restored_same_endpoint_total 9944
telemt_me_async_recovery_trigger_total 48
telemt_me_writer_removed_unexpected_minus_restored_total 246
telemt_user_connections_total{user="hello"} 419864
telemt_user_connections_current{user="hello"} 201
telemt_user_octets_from_client{user="hello"} 8413614936 (7.84 GB)
telemt_user_octets_to_client{user="hello"} 149696050892 (139.42 GB)
telemt_user_unique_ips_current{user="hello"} 83
telemt_user_unique_ips_recent_window{user="hello"} 23
```