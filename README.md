# Server Metrics 2026-03-15 05:59:52 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.18

telemt_uptime_seconds 27923.2 (7h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 395796
telemt_connections_bad_total 6426
telemt_handshake_timeouts_total 1981
telemt_upstream_connect_attempt_total 5865
telemt_upstream_connect_success_total 5843
telemt_upstream_connect_fail_total 22
telemt_upstream_connect_attempts_per_request{bucket="1"} 5865
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3085
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2752
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 22
telemt_me_reconnect_attempts_total 4484
telemt_me_reconnect_success_total 4461
telemt_me_reader_eof_total 4716
telemt_me_idle_close_by_peer_total 4716
telemt_me_route_drop_no_conn_total 125621
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 349735
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 891
telemt_desync_full_logged_total 274
telemt_desync_suppressed_total 617
telemt_desync_frames_bucket_total{bucket="1_2"} 195
telemt_desync_frames_bucket_total{bucket="3_10"} 343
telemt_desync_frames_bucket_total{bucket="gt_10"} 353
telemt_pool_swap_total 27
telemt_me_writer_removed_unexpected_total 4512
telemt_me_writer_restored_same_endpoint_total 4450
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 296
telemt_me_writer_removed_unexpected_minus_restored_total 51
telemt_user_connections_total{user="hello"} 349750
telemt_user_connections_current{user="hello"} 1198
telemt_user_octets_from_client{user="hello"} 3964499304 (3.69 GB)
telemt_user_octets_to_client{user="hello"} 126334602580 (117.66 GB)
telemt_user_unique_ips_current{user="hello"} 384
telemt_user_unique_ips_recent_window{user="hello"} 169
```

## server2

```
telemt 3.3.18

telemt_uptime_seconds 27923.9 (7h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 150232
telemt_connections_bad_total 18312
telemt_handshake_timeouts_total 5219
telemt_upstream_connect_attempt_total 8076
telemt_upstream_connect_success_total 8038
telemt_upstream_connect_fail_total 38
telemt_upstream_connect_attempts_per_request{bucket="1"} 8076
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4392
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3587
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 16
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 43
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 38
telemt_me_reconnect_attempts_total 6368
telemt_me_reconnect_success_total 6337
telemt_me_reader_eof_total 6700
telemt_me_idle_close_by_peer_total 6700
telemt_me_route_drop_no_conn_total 35801
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 122820
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 16
telemt_me_endpoint_quarantine_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 321
telemt_desync_full_logged_total 124
telemt_desync_suppressed_total 197
telemt_desync_frames_bucket_total{bucket="1_2"} 93
telemt_desync_frames_bucket_total{bucket="3_10"} 122
telemt_desync_frames_bucket_total{bucket="gt_10"} 106
telemt_pool_swap_total 29
telemt_me_writer_removed_unexpected_total 6356
telemt_me_writer_restored_same_endpoint_total 6329
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 61
telemt_me_writer_removed_unexpected_minus_restored_total 19
telemt_user_connections_total{user="hello"} 123116
telemt_user_connections_current{user="hello"} 434
telemt_user_octets_from_client{user="hello"} 2138720307 (1.99 GB)
telemt_user_octets_to_client{user="hello"} 40936881404 (38.13 GB)
telemt_user_msgs_from_client{user="hello"} 620
telemt_user_msgs_to_client{user="hello"} 1332
telemt_user_unique_ips_current{user="hello"} 163
telemt_user_unique_ips_recent_window{user="hello"} 72
```

## server3

```
telemt 3.3.18

telemt_uptime_seconds 27924.0 (7h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 281022
telemt_connections_bad_total 6458
telemt_handshake_timeouts_total 29099
telemt_upstream_connect_attempt_total 6455
telemt_upstream_connect_success_total 6428
telemt_upstream_connect_fail_total 27
telemt_upstream_connect_attempts_per_request{bucket="1"} 6455
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3443
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2965
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 20
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 27
telemt_me_reconnect_attempts_total 5063
telemt_me_reconnect_success_total 5038
telemt_me_reader_eof_total 5332
telemt_me_idle_close_by_peer_total 5332
telemt_me_route_drop_no_conn_total 69392
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 233600
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 418
telemt_desync_full_logged_total 191
telemt_desync_suppressed_total 227
telemt_desync_frames_bucket_total{bucket="1_2"} 91
telemt_desync_frames_bucket_total{bucket="3_10"} 160
telemt_desync_frames_bucket_total{bucket="gt_10"} 167
telemt_pool_swap_total 29
telemt_me_writer_removed_unexpected_total 5092
telemt_me_writer_restored_same_endpoint_total 5019
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 242
telemt_me_writer_removed_unexpected_minus_restored_total 54
telemt_user_connections_total{user="hello"} 233405
telemt_user_connections_current{user="hello"} 699
telemt_user_octets_from_client{user="hello"} 3887445796 (3.62 GB)
telemt_user_octets_to_client{user="hello"} 96938635432 (90.28 GB)
telemt_user_unique_ips_current{user="hello"} 244
telemt_user_unique_ips_recent_window{user="hello"} 102
```

## server4

```
telemt 3.3.18

telemt_uptime_seconds 27923.8 (7h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 199351
telemt_connections_bad_total 37841
telemt_handshake_timeouts_total 13683
telemt_upstream_connect_attempt_total 9590
telemt_upstream_connect_success_total 9390
telemt_upstream_connect_fail_total 200
telemt_upstream_connect_attempts_per_request{bucket="1"} 9590
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4502
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4885
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 200
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 12812
telemt_me_reconnect_success_total 8004
telemt_me_reader_eof_total 8418
telemt_me_idle_close_by_peer_total 8418
telemt_me_seq_mismatch_total 10
telemt_me_route_drop_no_conn_total 46047
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 143890
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 27
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 236
telemt_desync_full_logged_total 62
telemt_desync_suppressed_total 174
telemt_desync_frames_bucket_total{bucket="1_2"} 70
telemt_desync_frames_bucket_total{bucket="3_10"} 97
telemt_desync_frames_bucket_total{bucket="gt_10"} 69
telemt_pool_swap_total 14
telemt_me_writer_removed_unexpected_total 8216
telemt_me_refill_failed_total 149
telemt_me_writer_restored_same_endpoint_total 7978
telemt_me_writer_restored_fallback_total 26
telemt_me_async_recovery_trigger_total 96
telemt_me_writer_removed_unexpected_minus_restored_total 212
telemt_user_connections_total{user="hello"} 143893
telemt_user_connections_current{user="hello"} 408
telemt_user_octets_from_client{user="hello"} 1229818000 (1.15 GB)
telemt_user_octets_to_client{user="hello"} 50408349236 (46.95 GB)
telemt_user_unique_ips_current{user="hello"} 132
telemt_user_unique_ips_recent_window{user="hello"} 63
```

## server5

```
telemt 3.3.18

telemt_uptime_seconds 27924.7 (7h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 134386
telemt_connections_bad_total 233
telemt_handshake_timeouts_total 1432
telemt_upstream_connect_attempt_total 6332
telemt_upstream_connect_success_total 6305
telemt_upstream_connect_fail_total 27
telemt_upstream_connect_attempts_per_request{bucket="1"} 6332
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2753
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3547
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 27
telemt_me_reconnect_attempts_total 4941
telemt_me_reconnect_success_total 4920
telemt_me_reader_eof_total 5252
telemt_me_idle_close_by_peer_total 5252
telemt_me_route_drop_no_conn_total 37460
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 127923
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 498
telemt_desync_full_logged_total 158
telemt_desync_suppressed_total 340
telemt_desync_frames_bucket_total{bucket="1_2"} 165
telemt_desync_frames_bucket_total{bucket="3_10"} 187
telemt_desync_frames_bucket_total{bucket="gt_10"} 146
telemt_pool_swap_total 30
telemt_me_writer_removed_unexpected_total 4970
telemt_me_writer_restored_same_endpoint_total 4912
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 54
telemt_me_writer_removed_unexpected_minus_restored_total 50
telemt_user_connections_total{user="hello"} 127927
telemt_user_connections_current{user="hello"} 539
telemt_user_octets_from_client{user="hello"} 1202601864 (1.12 GB)
telemt_user_octets_to_client{user="hello"} 43953806516 (40.94 GB)
telemt_user_unique_ips_current{user="hello"} 159
telemt_user_unique_ips_recent_window{user="hello"} 74
```