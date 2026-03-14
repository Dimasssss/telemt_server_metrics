# Server Metrics 2026-03-14 13:29:30 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.17

telemt_uptime_seconds 710.7 (0h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 30759
telemt_connections_bad_total 29
telemt_handshake_timeouts_total 463
telemt_upstream_connect_attempt_total 104
telemt_upstream_connect_success_total 103
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 104
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 58
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 45
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 37
telemt_me_reconnect_success_total 36
telemt_me_reader_eof_total 14
telemt_me_idle_close_by_peer_total 14
telemt_me_route_drop_no_conn_total 10650
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 29063
telemt_me_writer_pick_total{mode="p2c",result="full"} 12
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 9
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_desync_total 70
telemt_desync_full_logged_total 25
telemt_desync_suppressed_total 45
telemt_desync_frames_bucket_total{bucket="1_2"} 22
telemt_desync_frames_bucket_total{bucket="3_10"} 24
telemt_desync_frames_bucket_total{bucket="gt_10"} 24
telemt_me_writer_removed_unexpected_total 36
telemt_me_writer_restored_same_endpoint_total 27
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 484
telemt_user_connections_total{user="hello"} 29068
telemt_user_connections_current{user="hello"} 1644
telemt_user_octets_from_client{user="hello"} 331094324 (315.76 MB)
telemt_user_octets_to_client{user="hello"} 5718292368 (5.33 GB)
telemt_user_unique_ips_current{user="hello"} 473
telemt_user_unique_ips_recent_window{user="hello"} 224
```

## server2

```
telemt 3.3.17

telemt_uptime_seconds 715.8 (0h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 14038
telemt_connections_bad_total 624
telemt_handshake_timeouts_total 586
telemt_upstream_connect_attempt_total 166
telemt_upstream_connect_success_total 165
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 166
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 103
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 59
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 5
telemt_me_reconnect_attempts_total 100
telemt_me_reconnect_success_total 99
telemt_me_reader_eof_total 70
telemt_me_idle_close_by_peer_total 70
telemt_me_seq_mismatch_total 1
telemt_me_route_drop_no_conn_total 3478
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 10817
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 16
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_desync_total 20
telemt_desync_full_logged_total 8
telemt_desync_suppressed_total 12
telemt_desync_frames_bucket_total{bucket="1_2"} 5
telemt_desync_frames_bucket_total{bucket="3_10"} 10
telemt_desync_frames_bucket_total{bucket="gt_10"} 5
telemt_me_writer_removed_unexpected_total 91
telemt_me_writer_restored_same_endpoint_total 88
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 38
telemt_user_connections_total{user="hello"} 10784
telemt_user_connections_current{user="hello"} 663
telemt_user_octets_from_client{user="hello"} 174800972 (166.70 MB)
telemt_user_octets_to_client{user="hello"} 3495577692 (3.26 GB)
telemt_user_unique_ips_current{user="hello"} 193
telemt_user_unique_ips_recent_window{user="hello"} 116
```

## server3

```
telemt 3.3.17

telemt_uptime_seconds 578.8 (0h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 16536
telemt_connections_bad_total 128
telemt_handshake_timeouts_total 1727
telemt_upstream_connect_attempt_total 116
telemt_upstream_connect_success_total 115
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 116
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 70
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 45
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 50
telemt_me_reconnect_success_total 49
telemt_me_reader_eof_total 11
telemt_me_idle_close_by_peer_total 11
telemt_me_route_drop_no_conn_total 3588
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 13496
telemt_me_writer_pick_total{mode="p2c",result="full"} 14
telemt_me_writer_pick_total{mode="p2c",result="closed"} 30
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_desync_total 27
telemt_desync_full_logged_total 5
telemt_desync_suppressed_total 22
telemt_desync_frames_bucket_total{bucket="1_2"} 5
telemt_desync_frames_bucket_total{bucket="3_10"} 16
telemt_desync_frames_bucket_total{bucket="gt_10"} 6
telemt_me_writer_removed_unexpected_total 33
telemt_me_writer_restored_same_endpoint_total 16
telemt_me_writer_restored_fallback_total 33
telemt_me_async_recovery_trigger_total 1168
telemt_user_connections_total{user="hello"} 13475
telemt_user_connections_current{user="hello"} 992
telemt_user_octets_from_client{user="hello"} 137631560 (131.26 MB)
telemt_user_octets_to_client{user="hello"} 3662878052 (3.41 GB)
telemt_user_unique_ips_current{user="hello"} 270
telemt_user_unique_ips_recent_window{user="hello"} 161
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 229473.1 (63h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2694752
telemt_connections_bad_total 23540
telemt_handshake_timeouts_total 359240
telemt_upstream_connect_attempt_total 70448
telemt_upstream_connect_success_total 67938
telemt_upstream_connect_fail_total 2373
telemt_upstream_connect_attempts_per_request{bucket="1"} 70174
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 40366
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 27406
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 166
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2372
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 21026
telemt_me_reconnect_attempts_total 62291
telemt_me_reconnect_success_total 49498
telemt_me_reader_eof_total 53016
telemt_me_idle_close_by_peer_total 53008
telemt_me_route_drop_no_conn_total 888299
telemt_me_route_drop_channel_closed_total 7
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2097287
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4124
telemt_desync_full_logged_total 1356
telemt_desync_suppressed_total 2768
telemt_desync_frames_bucket_total{bucket="1_2"} 1173
telemt_desync_frames_bucket_total{bucket="3_10"} 1688
telemt_desync_frames_bucket_total{bucket="gt_10"} 1263
telemt_pool_swap_total 196
telemt_me_writer_removed_unexpected_total 50329
telemt_me_refill_failed_total 389
telemt_me_writer_restored_same_endpoint_total 49473
telemt_me_writer_restored_fallback_total 25
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 831
telemt_user_connections_total{user="hello"} 2104030
telemt_user_connections_current{user="hello"} 516
telemt_user_octets_from_client{user="hello"} 31001169019 (28.87 GB)
telemt_user_octets_to_client{user="hello"} 746546335130 (695.28 GB)
telemt_user_msgs_from_client{user="hello"} 50957
telemt_user_msgs_to_client{user="hello"} 129867
telemt_user_unique_ips_current{user="hello"} 130
telemt_user_unique_ips_recent_window{user="hello"} 58
```

## server5

```
telemt 3.3.17

telemt_uptime_seconds 728.7 (0h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 12276
telemt_connections_bad_total 24
telemt_handshake_timeouts_total 63
telemt_upstream_connect_attempt_total 131
telemt_upstream_connect_success_total 128
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 131
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 72
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 53
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_keepalive_timeout_total 6
telemt_me_reconnect_attempts_total 65
telemt_me_reconnect_success_total 64
telemt_me_reader_eof_total 42
telemt_me_idle_close_by_peer_total 42
telemt_me_route_drop_no_conn_total 3788
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 11094
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_desync_total 68
telemt_desync_full_logged_total 23
telemt_desync_suppressed_total 45
telemt_desync_frames_bucket_total{bucket="1_2"} 17
telemt_desync_frames_bucket_total{bucket="3_10"} 23
telemt_desync_frames_bucket_total{bucket="gt_10"} 28
telemt_me_writer_removed_unexpected_total 65
telemt_me_writer_restored_same_endpoint_total 46
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 205
telemt_me_writer_removed_unexpected_minus_restored_total 1
telemt_user_connections_total{user="hello"} 11094
telemt_user_connections_current{user="hello"} 749
telemt_user_octets_from_client{user="hello"} 176919764 (168.72 MB)
telemt_user_octets_to_client{user="hello"} 5282308916 (4.92 GB)
telemt_user_unique_ips_current{user="hello"} 214
telemt_user_unique_ips_recent_window{user="hello"} 109
```