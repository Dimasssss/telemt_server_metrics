# Server Metrics 2026-03-14 21:15:19 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.17

telemt_uptime_seconds 28660.3 (7h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1059130
telemt_connections_bad_total 42384
telemt_handshake_timeouts_total 14763
telemt_upstream_connect_attempt_total 5204
telemt_upstream_connect_success_total 5181
telemt_upstream_connect_fail_total 23
telemt_upstream_connect_attempts_per_request{bucket="1"} 5204
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2579
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2559
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 43
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 23
telemt_me_keepalive_timeout_total 116
telemt_me_reconnect_attempts_total 4526
telemt_me_reconnect_success_total 3718
telemt_me_reader_eof_total 3923
telemt_me_idle_close_by_peer_total 3923
telemt_me_route_drop_no_conn_total 404702
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 943201
telemt_me_writer_pick_total{mode="p2c",result="full"} 12
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 9
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3154
telemt_desync_full_logged_total 912
telemt_desync_suppressed_total 2242
telemt_desync_frames_bucket_total{bucket="1_2"} 744
telemt_desync_frames_bucket_total{bucket="3_10"} 1173
telemt_desync_frames_bucket_total{bucket="gt_10"} 1237
telemt_pool_swap_total 22
telemt_me_writer_removed_unexpected_total 3803
telemt_me_refill_failed_total 24
telemt_me_writer_restored_same_endpoint_total 3709
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 484
telemt_me_writer_removed_unexpected_minus_restored_total 85
telemt_user_connections_total{user="hello"} 943149
telemt_user_connections_current{user="hello"} 1176
telemt_user_octets_from_client{user="hello"} 16801763040 (15.65 GB)
telemt_user_octets_to_client{user="hello"} 316722911564 (294.97 GB)
telemt_user_unique_ips_current{user="hello"} 364
telemt_user_unique_ips_recent_window{user="hello"} 146
```

## server2

```
telemt 3.3.17

telemt_uptime_seconds 28665.6 (7h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 417370
telemt_connections_bad_total 31752
telemt_handshake_timeouts_total 12967
telemt_upstream_connect_attempt_total 6126
telemt_upstream_connect_success_total 6066
telemt_upstream_connect_fail_total 60
telemt_upstream_connect_attempts_per_request{bucket="1"} 6126
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3155
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2797
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 13
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 101
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 60
telemt_me_keepalive_timeout_total 481
telemt_me_reconnect_attempts_total 5402
telemt_me_reconnect_success_total 4604
telemt_me_reader_eof_total 4816
telemt_me_idle_close_by_peer_total 4816
telemt_me_seq_mismatch_total 7
telemt_me_route_drop_no_conn_total 122296
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 349067
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1719
telemt_desync_full_logged_total 451
telemt_desync_suppressed_total 1268
telemt_desync_frames_bucket_total{bucket="1_2"} 710
telemt_desync_frames_bucket_total{bucket="3_10"} 594
telemt_desync_frames_bucket_total{bucket="gt_10"} 415
telemt_pool_swap_total 19
telemt_me_writer_removed_unexpected_total 4723
telemt_me_refill_failed_total 23
telemt_me_writer_restored_same_endpoint_total 4581
telemt_me_writer_restored_fallback_total 23
telemt_me_async_recovery_trigger_total 38
telemt_me_writer_removed_unexpected_minus_restored_total 119
telemt_user_connections_total{user="hello"} 349011
telemt_user_connections_current{user="hello"} 441
telemt_user_octets_from_client{user="hello"} 5519978456 (5.14 GB)
telemt_user_octets_to_client{user="hello"} 120979461440 (112.67 GB)
telemt_user_unique_ips_current{user="hello"} 135
telemt_user_unique_ips_recent_window{user="hello"} 58
```

## server3

```
telemt 3.3.17

telemt_uptime_seconds 28528.2 (7h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 903658
telemt_connections_bad_total 3730
telemt_handshake_timeouts_total 223718
telemt_upstream_connect_attempt_total 5541
telemt_upstream_connect_success_total 5524
telemt_upstream_connect_fail_total 17
telemt_upstream_connect_attempts_per_request{bucket="1"} 5541
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2839
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2671
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 14
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17
telemt_me_keepalive_timeout_total 116
telemt_me_reconnect_attempts_total 7988
telemt_me_reconnect_success_total 4075
telemt_me_reader_eof_total 4367
telemt_me_idle_close_by_peer_total 4367
telemt_me_route_drop_no_conn_total 203513
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 578973
telemt_me_writer_pick_total{mode="p2c",result="full"} 14
telemt_me_writer_pick_total{mode="p2c",result="closed"} 30
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2175
telemt_desync_full_logged_total 830
telemt_desync_suppressed_total 1345
telemt_desync_frames_bucket_total{bucket="1_2"} 324
telemt_desync_frames_bucket_total{bucket="3_10"} 759
telemt_desync_frames_bucket_total{bucket="gt_10"} 1092
telemt_pool_swap_total 24
telemt_me_writer_removed_unexpected_total 4243
telemt_me_refill_failed_total 121
telemt_me_writer_restored_same_endpoint_total 4042
telemt_me_writer_restored_fallback_total 33
telemt_me_async_recovery_trigger_total 1168
telemt_me_writer_removed_unexpected_minus_restored_total 168
telemt_user_connections_total{user="hello"} 578800
telemt_user_connections_current{user="hello"} 675
telemt_user_octets_from_client{user="hello"} 8958247848 (8.34 GB)
telemt_user_octets_to_client{user="hello"} 216884915848 (201.99 GB)
telemt_user_unique_ips_current{user="hello"} 193
telemt_user_unique_ips_recent_window{user="hello"} 84
```

## server4

```
telemt 3.3.17

telemt_uptime_seconds 28382.9 (7h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 481355
telemt_connections_bad_total 100641
telemt_handshake_timeouts_total 55064
telemt_upstream_connect_attempt_total 6536
telemt_upstream_connect_success_total 6535
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 6536
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3288
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3165
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 82
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 215
telemt_me_reconnect_attempts_total 6016
telemt_me_reconnect_success_total 5093
telemt_me_reader_eof_total 5345
telemt_me_idle_close_by_peer_total 5345
telemt_me_seq_mismatch_total 11
telemt_me_route_drop_no_conn_total 111466
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 317537
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 12
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 704
telemt_desync_full_logged_total 246
telemt_desync_suppressed_total 458
telemt_desync_frames_bucket_total{bucket="1_2"} 243
telemt_desync_frames_bucket_total{bucket="3_10"} 232
telemt_desync_frames_bucket_total{bucket="gt_10"} 229
telemt_pool_swap_total 23
telemt_me_writer_removed_unexpected_total 5181
telemt_me_refill_failed_total 28
telemt_me_writer_restored_same_endpoint_total 5081
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 20
telemt_me_writer_removed_unexpected_minus_restored_total 88
telemt_user_connections_total{user="hello"} 317451
telemt_user_connections_current{user="hello"} 401
telemt_user_octets_from_client{user="hello"} 4482816912 (4.17 GB)
telemt_user_octets_to_client{user="hello"} 97319217424 (90.64 GB)
telemt_user_unique_ips_current{user="hello"} 132
telemt_user_unique_ips_recent_window{user="hello"} 56
```

## server5

```
telemt 3.3.17

telemt_uptime_seconds 28678.2 (7h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 403529
telemt_connections_bad_total 1392
telemt_handshake_timeouts_total 4000
telemt_upstream_connect_attempt_total 6062
telemt_upstream_connect_success_total 5943
telemt_upstream_connect_fail_total 119
telemt_upstream_connect_attempts_per_request{bucket="1"} 6062
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2887
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3008
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 48
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 119
telemt_me_keepalive_timeout_total 146
telemt_me_reconnect_attempts_total 5177
telemt_me_reconnect_success_total 4500
telemt_me_reader_eof_total 4752
telemt_me_idle_close_by_peer_total 4752
telemt_me_route_drop_no_conn_total 127089
telemt_me_route_drop_channel_closed_total 23
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 374760
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1043
telemt_desync_full_logged_total 365
telemt_desync_suppressed_total 678
telemt_desync_frames_bucket_total{bucket="1_2"} 338
telemt_desync_frames_bucket_total{bucket="3_10"} 330
telemt_desync_frames_bucket_total{bucket="gt_10"} 375
telemt_pool_swap_total 21
telemt_me_writer_removed_unexpected_total 4602
telemt_me_refill_failed_total 20
telemt_me_writer_restored_same_endpoint_total 4482
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 205
telemt_me_writer_removed_unexpected_minus_restored_total 102
telemt_user_connections_total{user="hello"} 374724
telemt_user_connections_current{user="hello"} 447
telemt_user_octets_from_client{user="hello"} 5954246584 (5.55 GB)
telemt_user_octets_to_client{user="hello"} 154977757416 (144.33 GB)
telemt_user_unique_ips_current{user="hello"} 148
telemt_user_unique_ips_recent_window{user="hello"} 49
```