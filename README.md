# Server Metrics 2026-03-10 21:28:02 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 25257.1 (7h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 695075
telemt_connections_bad_total 8152
telemt_handshake_timeouts_total 8100
telemt_upstream_connect_attempt_total 5471
telemt_upstream_connect_success_total 5462
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 5471
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2689
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2716
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 56
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 351
telemt_me_reconnect_attempts_total 15782
telemt_me_reconnect_success_total 4124
telemt_me_reader_eof_total 4563
telemt_me_idle_close_by_peer_total 4563
telemt_me_route_drop_no_conn_total 289854
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 656724
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3312
telemt_desync_full_logged_total 922
telemt_desync_suppressed_total 2390
telemt_desync_frames_bucket_total{bucket="1_2"} 936
telemt_desync_frames_bucket_total{bucket="3_10"} 1248
telemt_desync_frames_bucket_total{bucket="gt_10"} 1128
telemt_pool_swap_total 7
telemt_me_writer_removed_unexpected_total 4518
telemt_me_refill_failed_total 363
telemt_me_writer_restored_same_endpoint_total 4118
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 394
telemt_user_connections_total{user="hello"} 656529
telemt_user_connections_current{user="hello"} 684
telemt_user_octets_from_client{user="hello"} 9504473592 (8.85 GB)
telemt_user_octets_to_client{user="hello"} 199488817052 (185.79 GB)
telemt_user_unique_ips_current{user="hello"} 220
telemt_user_unique_ips_recent_window{user="hello"} 78
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 25313.8 (7h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 304381
telemt_connections_bad_total 1888
telemt_handshake_timeouts_total 17222
telemt_upstream_connect_attempt_total 11849
telemt_upstream_connect_success_total 8987
telemt_upstream_connect_fail_total 2862
telemt_upstream_connect_attempts_per_request{bucket="1"} 11849
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3746
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3001
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 209
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2031
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2862
telemt_me_keepalive_timeout_total 1365
telemt_me_reconnect_attempts_total 5510
telemt_me_reconnect_success_total 4707
telemt_me_reader_eof_total 4927
telemt_me_idle_close_by_peer_total 4925
telemt_me_route_drop_no_conn_total 162197
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 255614
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1483
telemt_desync_full_logged_total 411
telemt_desync_suppressed_total 1072
telemt_desync_frames_bucket_total{bucket="1_2"} 458
telemt_desync_frames_bucket_total{bucket="3_10"} 529
telemt_desync_frames_bucket_total{bucket="gt_10"} 496
telemt_pool_swap_total 17
telemt_me_writer_removed_unexpected_total 4789
telemt_me_refill_failed_total 22
telemt_me_writer_restored_same_endpoint_total 4686
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 86
telemt_me_writer_removed_unexpected_minus_restored_total 82
telemt_user_connections_total{user="hello"} 257887
telemt_user_connections_current{user="hello"} 200
telemt_user_octets_from_client{user="hello"} 2602400938 (2.42 GB)
telemt_user_octets_to_client{user="hello"} 61059374172 (56.87 GB)
telemt_user_msgs_from_client{user="hello"} 7933
telemt_user_msgs_to_client{user="hello"} 11226
telemt_user_unique_ips_current{user="hello"} 79
telemt_user_unique_ips_recent_window{user="hello"} 27
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 25313.7 (7h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 495806
telemt_connections_bad_total 2813
telemt_handshake_timeouts_total 33525
telemt_upstream_connect_attempt_total 7183
telemt_upstream_connect_success_total 7069
telemt_upstream_connect_fail_total 114
telemt_upstream_connect_attempts_per_request{bucket="1"} 7183
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4179
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2835
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 55
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 114
telemt_me_keepalive_timeout_total 200
telemt_me_reconnect_attempts_total 15712
telemt_me_reconnect_success_total 4666
telemt_me_reader_eof_total 5143
telemt_me_idle_close_by_peer_total 5143
telemt_me_route_drop_no_conn_total 172309
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 432461
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1411
telemt_desync_full_logged_total 392
telemt_desync_suppressed_total 1019
telemt_desync_frames_bucket_total{bucket="1_2"} 322
telemt_desync_frames_bucket_total{bucket="3_10"} 482
telemt_desync_frames_bucket_total{bucket="gt_10"} 607
telemt_pool_swap_total 10
telemt_me_writer_removed_unexpected_total 5087
telemt_me_refill_failed_total 343
telemt_me_writer_restored_same_endpoint_total 4655
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 421
telemt_user_connections_total{user="hello"} 433397
telemt_user_connections_current{user="hello"} 279
telemt_user_octets_from_client{user="hello"} 6328186833 (5.89 GB)
telemt_user_octets_to_client{user="hello"} 140183681657 (130.56 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 112
telemt_user_unique_ips_recent_window{user="hello"} 54
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 25314.1 (7h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 342401
telemt_connections_bad_total 24595
telemt_handshake_timeouts_total 29749
telemt_upstream_connect_attempt_total 6773
telemt_upstream_connect_success_total 6773
telemt_upstream_connect_attempts_per_request{bucket="1"} 6773
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3636
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3136
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 152
telemt_me_reconnect_attempts_total 6464
telemt_me_reconnect_success_total 5443
telemt_me_reader_eof_total 5714
telemt_me_idle_close_by_peer_total 5714
telemt_me_seq_mismatch_total 2
telemt_me_route_drop_no_conn_total 112235
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 275496
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 675
telemt_desync_full_logged_total 276
telemt_desync_suppressed_total 399
telemt_desync_frames_bucket_total{bucket="1_2"} 262
telemt_desync_frames_bucket_total{bucket="3_10"} 241
telemt_desync_frames_bucket_total{bucket="gt_10"} 172
telemt_pool_swap_total 18
telemt_me_writer_removed_unexpected_total 5532
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 5430
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 89
telemt_user_connections_total{user="hello"} 275174
telemt_user_connections_current{user="hello"} 284
telemt_user_octets_from_client{user="hello"} 3961407352 (3.69 GB)
telemt_user_octets_to_client{user="hello"} 84091490944 (78.32 GB)
telemt_user_unique_ips_current{user="hello"} 82
telemt_user_unique_ips_recent_window{user="hello"} 40
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 25313.9 (7h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 361596
telemt_connections_bad_total 1106
telemt_handshake_timeouts_total 2297
telemt_upstream_connect_attempt_total 7841
telemt_upstream_connect_success_total 7811
telemt_upstream_connect_fail_total 30
telemt_upstream_connect_attempts_per_request{bucket="1"} 7841
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4096
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3611
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 102
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 30
telemt_me_keepalive_timeout_total 176
telemt_me_reconnect_attempts_total 10205
telemt_me_reconnect_success_total 6451
telemt_me_reader_eof_total 6748
telemt_me_idle_close_by_peer_total 6748
telemt_me_route_drop_no_conn_total 128996
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 339203
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 2014
telemt_desync_full_logged_total 752
telemt_desync_suppressed_total 1262
telemt_desync_frames_bucket_total{bucket="1_2"} 756
telemt_desync_frames_bucket_total{bucket="3_10"} 859
telemt_desync_frames_bucket_total{bucket="gt_10"} 399
telemt_pool_swap_total 8
telemt_me_writer_removed_unexpected_total 6661
telemt_me_refill_failed_total 116
telemt_me_writer_restored_same_endpoint_total 6451
telemt_me_async_recovery_trigger_total 48
telemt_me_writer_removed_unexpected_minus_restored_total 210
telemt_user_connections_total{user="hello"} 339075
telemt_user_connections_current{user="hello"} 386
telemt_user_octets_from_client{user="hello"} 6303255984 (5.87 GB)
telemt_user_octets_to_client{user="hello"} 116773717284 (108.75 GB)
telemt_user_unique_ips_current{user="hello"} 119
telemt_user_unique_ips_recent_window{user="hello"} 55
```