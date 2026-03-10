# Server Metrics 2026-03-10 23:35:10 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 32885.8 (9h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 763704
telemt_connections_bad_total 8949
telemt_handshake_timeouts_total 8514
telemt_upstream_connect_attempt_total 7125
telemt_upstream_connect_success_total 7116
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 7125
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3552
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3506
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 57
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 370
telemt_me_reconnect_attempts_total 17058
telemt_me_reconnect_success_total 5396
telemt_me_reader_eof_total 5933
telemt_me_idle_close_by_peer_total 5933
telemt_me_route_drop_no_conn_total 316258
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 723002
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3513
telemt_desync_full_logged_total 980
telemt_desync_suppressed_total 2533
telemt_desync_frames_bucket_total{bucket="1_2"} 1013
telemt_desync_frames_bucket_total{bucket="3_10"} 1313
telemt_desync_frames_bucket_total{bucket="gt_10"} 1187
telemt_pool_swap_total 16
telemt_me_writer_removed_unexpected_total 5804
telemt_me_refill_failed_total 363
telemt_me_writer_restored_same_endpoint_total 5390
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 408
telemt_user_connections_total{user="hello"} 722791
telemt_user_connections_current{user="hello"} 394
telemt_user_octets_from_client{user="hello"} 10123404692 (9.43 GB)
telemt_user_octets_to_client{user="hello"} 216680168416 (201.80 GB)
telemt_user_unique_ips_current{user="hello"} 148
telemt_user_unique_ips_recent_window{user="hello"} 50
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 32942.5 (9h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 331240
telemt_connections_bad_total 2374
telemt_handshake_timeouts_total 17605
telemt_upstream_connect_attempt_total 13949
telemt_upstream_connect_success_total 11075
telemt_upstream_connect_fail_total 2874
telemt_upstream_connect_attempts_per_request{bucket="1"} 13949
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4719
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4116
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 209
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2031
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2874
telemt_me_keepalive_timeout_total 1389
telemt_me_reconnect_attempts_total 7251
telemt_me_reconnect_success_total 6440
telemt_me_reader_eof_total 6779
telemt_me_idle_close_by_peer_total 6777
telemt_me_route_drop_no_conn_total 169899
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 280960
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1706
telemt_desync_full_logged_total 472
telemt_desync_suppressed_total 1234
telemt_desync_frames_bucket_total{bucket="1_2"} 523
telemt_desync_frames_bucket_total{bucket="3_10"} 603
telemt_desync_frames_bucket_total{bucket="gt_10"} 580
telemt_pool_swap_total 24
telemt_me_writer_removed_unexpected_total 6532
telemt_me_refill_failed_total 22
telemt_me_writer_restored_same_endpoint_total 6419
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 86
telemt_me_writer_removed_unexpected_minus_restored_total 92
telemt_user_connections_total{user="hello"} 283229
telemt_user_connections_current{user="hello"} 150
telemt_user_octets_from_client{user="hello"} 2767656154 (2.58 GB)
telemt_user_octets_to_client{user="hello"} 69001881768 (64.26 GB)
telemt_user_msgs_from_client{user="hello"} 7933
telemt_user_msgs_to_client{user="hello"} 11226
telemt_user_unique_ips_current{user="hello"} 62
telemt_user_unique_ips_recent_window{user="hello"} 22
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 32942.3 (9h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 548739
telemt_connections_bad_total 3676
telemt_handshake_timeouts_total 33967
telemt_upstream_connect_attempt_total 8939
telemt_upstream_connect_success_total 8814
telemt_upstream_connect_fail_total 125
telemt_upstream_connect_attempts_per_request{bucket="1"} 8939
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5027
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3724
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 63
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 125
telemt_me_keepalive_timeout_total 229
telemt_me_reconnect_attempts_total 17112
telemt_me_reconnect_success_total 6055
telemt_me_reader_eof_total 6641
telemt_me_idle_close_by_peer_total 6641
telemt_me_route_drop_no_conn_total 189893
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 482655
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1520
telemt_desync_full_logged_total 433
telemt_desync_suppressed_total 1087
telemt_desync_frames_bucket_total{bucket="1_2"} 342
telemt_desync_frames_bucket_total{bucket="3_10"} 523
telemt_desync_frames_bucket_total{bucket="gt_10"} 655
telemt_pool_swap_total 18
telemt_me_writer_removed_unexpected_total 6493
telemt_me_refill_failed_total 343
telemt_me_writer_restored_same_endpoint_total 6044
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 438
telemt_user_connections_total{user="hello"} 483580
telemt_user_connections_current{user="hello"} 203
telemt_user_octets_from_client{user="hello"} 6742210301 (6.28 GB)
telemt_user_octets_to_client{user="hello"} 151830566077 (141.40 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 87
telemt_user_unique_ips_recent_window{user="hello"} 32
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 32942.7 (9h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 393398
telemt_connections_bad_total 31520
telemt_handshake_timeouts_total 36181
telemt_upstream_connect_attempt_total 9217
telemt_upstream_connect_success_total 9217
telemt_upstream_connect_attempts_per_request{bucket="1"} 9217
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5166
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4050
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 195
telemt_me_reconnect_attempts_total 8558
telemt_me_reconnect_success_total 7531
telemt_me_reader_eof_total 7939
telemt_me_idle_close_by_peer_total 7939
telemt_me_seq_mismatch_total 4
telemt_me_route_drop_no_conn_total 123690
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 312738
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 697
telemt_desync_full_logged_total 282
telemt_desync_suppressed_total 415
telemt_desync_frames_bucket_total{bucket="1_2"} 269
telemt_desync_frames_bucket_total{bucket="3_10"} 245
telemt_desync_frames_bucket_total{bucket="gt_10"} 183
telemt_pool_swap_total 25
telemt_me_writer_removed_unexpected_total 7644
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 7516
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 113
telemt_user_connections_total{user="hello"} 312413
telemt_user_connections_current{user="hello"} 134
telemt_user_octets_from_client{user="hello"} 4095014460 (3.81 GB)
telemt_user_octets_to_client{user="hello"} 88759983460 (82.66 GB)
telemt_user_unique_ips_current{user="hello"} 48
telemt_user_unique_ips_recent_window{user="hello"} 20
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 32942.3 (9h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 416458
telemt_connections_bad_total 3195
telemt_handshake_timeouts_total 2684
telemt_upstream_connect_attempt_total 10073
telemt_upstream_connect_success_total 10034
telemt_upstream_connect_fail_total 39
telemt_upstream_connect_attempts_per_request{bucket="1"} 10073
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5255
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4669
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 108
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 39
telemt_me_keepalive_timeout_total 206
telemt_me_reconnect_attempts_total 12075
telemt_me_reconnect_success_total 8314
telemt_me_reader_eof_total 8727
telemt_me_idle_close_by_peer_total 8727
telemt_me_route_drop_no_conn_total 141981
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 386134
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 2221
telemt_desync_full_logged_total 857
telemt_desync_suppressed_total 1364
telemt_desync_frames_bucket_total{bucket="1_2"} 818
telemt_desync_frames_bucket_total{bucket="3_10"} 954
telemt_desync_frames_bucket_total{bucket="gt_10"} 449
telemt_pool_swap_total 13
telemt_me_writer_removed_unexpected_total 8543
telemt_me_refill_failed_total 116
telemt_me_writer_restored_same_endpoint_total 8314
telemt_me_async_recovery_trigger_total 48
telemt_me_writer_removed_unexpected_minus_restored_total 229
telemt_user_connections_total{user="hello"} 385919
telemt_user_connections_current{user="hello"} 265
telemt_user_octets_from_client{user="hello"} 6514709188 (6.07 GB)
telemt_user_octets_to_client{user="hello"} 142211176864 (132.44 GB)
telemt_user_unique_ips_current{user="hello"} 87
telemt_user_unique_ips_recent_window{user="hello"} 33
```