# Server Metrics 2026-03-11 00:41:12 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 36847.7 (10h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 791194
telemt_connections_bad_total 9523
telemt_handshake_timeouts_total 9027
telemt_upstream_connect_attempt_total 7998
telemt_upstream_connect_success_total 7989
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 7998
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3981
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3949
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 58
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 476
telemt_me_reconnect_attempts_total 17759
telemt_me_reconnect_success_total 6094
telemt_me_reader_eof_total 6679
telemt_me_idle_close_by_peer_total 6679
telemt_me_route_drop_no_conn_total 325969
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 748955
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3556
telemt_desync_full_logged_total 994
telemt_desync_suppressed_total 2562
telemt_desync_frames_bucket_total{bucket="1_2"} 1035
telemt_desync_frames_bucket_total{bucket="3_10"} 1319
telemt_desync_frames_bucket_total{bucket="gt_10"} 1202
telemt_pool_swap_total 20
telemt_me_writer_removed_unexpected_total 6507
telemt_me_refill_failed_total 363
telemt_me_writer_restored_same_endpoint_total 6088
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 413
telemt_user_connections_total{user="hello"} 748732
telemt_user_connections_current{user="hello"} 427
telemt_user_octets_from_client{user="hello"} 10435452764 (9.72 GB)
telemt_user_octets_to_client{user="hello"} 223823113692 (208.45 GB)
telemt_user_unique_ips_current{user="hello"} 155
telemt_user_unique_ips_recent_window{user="hello"} 54
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 36904.3 (10h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 341677
telemt_connections_bad_total 2384
telemt_handshake_timeouts_total 17643
telemt_upstream_connect_attempt_total 15022
telemt_upstream_connect_success_total 12143
telemt_upstream_connect_fail_total 2879
telemt_upstream_connect_attempts_per_request{bucket="1"} 15022
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5242
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4661
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 209
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2031
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2879
telemt_me_keepalive_timeout_total 1706
telemt_me_reconnect_attempts_total 8147
telemt_me_reconnect_success_total 7333
telemt_me_reader_eof_total 7732
telemt_me_idle_close_by_peer_total 7730
telemt_me_route_drop_no_conn_total 172523
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 291088
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1760
telemt_desync_full_logged_total 497
telemt_desync_suppressed_total 1263
telemt_desync_frames_bucket_total{bucket="1_2"} 540
telemt_desync_frames_bucket_total{bucket="3_10"} 622
telemt_desync_frames_bucket_total{bucket="gt_10"} 598
telemt_pool_swap_total 28
telemt_me_writer_removed_unexpected_total 7434
telemt_me_refill_failed_total 22
telemt_me_writer_restored_same_endpoint_total 7312
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 86
telemt_me_writer_removed_unexpected_minus_restored_total 101
telemt_user_connections_total{user="hello"} 293357
telemt_user_connections_current{user="hello"} 173
telemt_user_octets_from_client{user="hello"} 2836352830 (2.64 GB)
telemt_user_octets_to_client{user="hello"} 70239902540 (65.42 GB)
telemt_user_msgs_from_client{user="hello"} 7933
telemt_user_msgs_to_client{user="hello"} 11226
telemt_user_unique_ips_current{user="hello"} 69
telemt_user_unique_ips_recent_window{user="hello"} 25
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 36904.1 (10h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 567705
telemt_connections_bad_total 3887
telemt_handshake_timeouts_total 34095
telemt_upstream_connect_attempt_total 10095
telemt_upstream_connect_success_total 9956
telemt_upstream_connect_fail_total 139
telemt_upstream_connect_attempts_per_request{bucket="1"} 10095
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5606
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4285
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 65
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 139
telemt_me_keepalive_timeout_total 508
telemt_me_reconnect_attempts_total 18080
telemt_me_reconnect_success_total 7019
telemt_me_reader_eof_total 7654
telemt_me_idle_close_by_peer_total 7654
telemt_me_route_drop_no_conn_total 195042
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 501188
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
telemt_pool_swap_total 21
telemt_me_writer_removed_unexpected_total 7460
telemt_me_refill_failed_total 343
telemt_me_writer_restored_same_endpoint_total 7008
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 441
telemt_user_connections_total{user="hello"} 502112
telemt_user_connections_current{user="hello"} 219
telemt_user_octets_from_client{user="hello"} 6821368669 (6.35 GB)
telemt_user_octets_to_client{user="hello"} 154301490069 (143.70 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 89
telemt_user_unique_ips_recent_window{user="hello"} 36
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 36904.6 (10h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 414882
telemt_connections_bad_total 35134
telemt_handshake_timeouts_total 38908
telemt_upstream_connect_attempt_total 10500
telemt_upstream_connect_success_total 10500
telemt_upstream_connect_attempts_per_request{bucket="1"} 10500
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5921
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4578
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 403
telemt_me_reconnect_attempts_total 9669
telemt_me_reconnect_success_total 8637
telemt_me_reader_eof_total 9120
telemt_me_idle_close_by_peer_total 9120
telemt_me_seq_mismatch_total 5
telemt_me_route_drop_no_conn_total 127860
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 327813
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 716
telemt_desync_full_logged_total 288
telemt_desync_suppressed_total 428
telemt_desync_frames_bucket_total{bucket="1_2"} 276
telemt_desync_frames_bucket_total{bucket="3_10"} 249
telemt_desync_frames_bucket_total{bucket="gt_10"} 191
telemt_pool_swap_total 29
telemt_me_writer_removed_unexpected_total 8752
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 8621
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 115
telemt_user_connections_total{user="hello"} 327489
telemt_user_connections_current{user="hello"} 140
telemt_user_octets_from_client{user="hello"} 4197480952 (3.91 GB)
telemt_user_octets_to_client{user="hello"} 90580070024 (84.36 GB)
telemt_user_unique_ips_current{user="hello"} 54
telemt_user_unique_ips_recent_window{user="hello"} 31
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 36904.2 (10h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 439251
telemt_connections_bad_total 4402
telemt_handshake_timeouts_total 2762
telemt_upstream_connect_attempt_total 11108
telemt_upstream_connect_success_total 11063
telemt_upstream_connect_fail_total 45
telemt_upstream_connect_attempts_per_request{bucket="1"} 11108
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5766
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5184
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 111
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 45
telemt_me_keepalive_timeout_total 502
telemt_me_reconnect_attempts_total 12932
telemt_me_reconnect_success_total 9165
telemt_me_reader_eof_total 9636
telemt_me_idle_close_by_peer_total 9636
telemt_me_route_drop_no_conn_total 146789
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 404685
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 2270
telemt_desync_full_logged_total 878
telemt_desync_suppressed_total 1392
telemt_desync_frames_bucket_total{bucket="1_2"} 834
telemt_desync_frames_bucket_total{bucket="3_10"} 971
telemt_desync_frames_bucket_total{bucket="gt_10"} 465
telemt_pool_swap_total 17
telemt_me_writer_removed_unexpected_total 9401
telemt_me_refill_failed_total 116
telemt_me_writer_restored_same_endpoint_total 9165
telemt_me_async_recovery_trigger_total 48
telemt_me_writer_removed_unexpected_minus_restored_total 236
telemt_user_connections_total{user="hello"} 404419
telemt_user_connections_current{user="hello"} 196
telemt_user_octets_from_client{user="hello"} 8352630864 (7.78 GB)
telemt_user_octets_to_client{user="hello"} 146027610192 (136.00 GB)
telemt_user_unique_ips_current{user="hello"} 74
telemt_user_unique_ips_recent_window{user="hello"} 32
```