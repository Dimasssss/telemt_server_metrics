# Server Metrics 2026-03-14 22:11:33 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.17

telemt_uptime_seconds 32034.0 (8h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1123985
telemt_connections_bad_total 42953
telemt_handshake_timeouts_total 14982
telemt_upstream_connect_attempt_total 5837
telemt_upstream_connect_success_total 5814
telemt_upstream_connect_fail_total 23
telemt_upstream_connect_attempts_per_request{bucket="1"} 5837
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2922
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2847
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 45
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 23
telemt_me_keepalive_timeout_total 120
telemt_me_reconnect_attempts_total 4987
telemt_me_reconnect_success_total 4178
telemt_me_reader_eof_total 4413
telemt_me_idle_close_by_peer_total 4413
telemt_me_route_drop_no_conn_total 428204
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1003351
telemt_me_writer_pick_total{mode="p2c",result="full"} 12
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 9
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3317
telemt_desync_full_logged_total 973
telemt_desync_suppressed_total 2344
telemt_desync_frames_bucket_total{bucket="1_2"} 782
telemt_desync_frames_bucket_total{bucket="3_10"} 1262
telemt_desync_frames_bucket_total{bucket="gt_10"} 1273
telemt_pool_swap_total 26
telemt_me_writer_removed_unexpected_total 4271
telemt_me_refill_failed_total 24
telemt_me_writer_restored_same_endpoint_total 4169
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 484
telemt_me_writer_removed_unexpected_minus_restored_total 93
telemt_user_connections_total{user="hello"} 1003318
telemt_user_connections_current{user="hello"} 1056
telemt_user_octets_from_client{user="hello"} 21251585012 (19.79 GB)
telemt_user_octets_to_client{user="hello"} 337732420728 (314.54 GB)
telemt_user_unique_ips_current{user="hello"} 325
telemt_user_unique_ips_recent_window{user="hello"} 108
```

## server2

```
telemt 3.3.17

telemt_uptime_seconds 32039.1 (8h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 446090
telemt_connections_bad_total 35815
telemt_handshake_timeouts_total 13686
telemt_upstream_connect_attempt_total 6947
telemt_upstream_connect_success_total 6878
telemt_upstream_connect_fail_total 69
telemt_upstream_connect_attempts_per_request{bucket="1"} 6947
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3614
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3136
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 13
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 115
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 69
telemt_me_keepalive_timeout_total 528
telemt_me_reconnect_attempts_total 6045
telemt_me_reconnect_success_total 5235
telemt_me_reader_eof_total 5482
telemt_me_idle_close_by_peer_total 5482
telemt_me_seq_mismatch_total 7
telemt_me_route_drop_no_conn_total 129550
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 372196
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1885
telemt_desync_full_logged_total 498
telemt_desync_suppressed_total 1387
telemt_desync_frames_bucket_total{bucket="1_2"} 751
telemt_desync_frames_bucket_total{bucket="3_10"} 666
telemt_desync_frames_bucket_total{bucket="gt_10"} 468
telemt_pool_swap_total 22
telemt_me_writer_removed_unexpected_total 5369
telemt_me_refill_failed_total 23
telemt_me_writer_restored_same_endpoint_total 5212
telemt_me_writer_restored_fallback_total 23
telemt_me_async_recovery_trigger_total 38
telemt_me_writer_removed_unexpected_minus_restored_total 134
telemt_user_connections_total{user="hello"} 372139
telemt_user_connections_current{user="hello"} 345
telemt_user_octets_from_client{user="hello"} 5908758864 (5.50 GB)
telemt_user_octets_to_client{user="hello"} 130310307648 (121.36 GB)
telemt_user_unique_ips_current{user="hello"} 113
telemt_user_unique_ips_recent_window{user="hello"} 45
```

## server3

```
telemt 3.3.17

telemt_uptime_seconds 31901.9 (8h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 972656
telemt_connections_bad_total 4353
telemt_handshake_timeouts_total 250067
telemt_upstream_connect_attempt_total 6263
telemt_upstream_connect_success_total 6243
telemt_upstream_connect_fail_total 20
telemt_upstream_connect_attempts_per_request{bucket="1"} 6263
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3219
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3008
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 16
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 20
telemt_me_keepalive_timeout_total 126
telemt_me_reconnect_attempts_total 8533
telemt_me_reconnect_success_total 4618
telemt_me_reader_eof_total 4945
telemt_me_idle_close_by_peer_total 4945
telemt_me_route_drop_no_conn_total 213389
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 617027
telemt_me_writer_pick_total{mode="p2c",result="full"} 14
telemt_me_writer_pick_total{mode="p2c",result="closed"} 30
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2260
telemt_desync_full_logged_total 862
telemt_desync_suppressed_total 1398
telemt_desync_frames_bucket_total{bucket="1_2"} 349
telemt_desync_frames_bucket_total{bucket="3_10"} 783
telemt_desync_frames_bucket_total{bucket="gt_10"} 1128
telemt_pool_swap_total 28
telemt_me_writer_removed_unexpected_total 4793
telemt_me_refill_failed_total 121
telemt_me_writer_restored_same_endpoint_total 4585
telemt_me_writer_restored_fallback_total 33
telemt_me_async_recovery_trigger_total 1168
telemt_me_writer_removed_unexpected_minus_restored_total 175
telemt_user_connections_total{user="hello"} 616849
telemt_user_connections_current{user="hello"} 562
telemt_user_octets_from_client{user="hello"} 9921122860 (9.24 GB)
telemt_user_octets_to_client{user="hello"} 229076960544 (213.34 GB)
telemt_user_unique_ips_current{user="hello"} 178
telemt_user_unique_ips_recent_window{user="hello"} 71
```

## server4

```
telemt 3.3.17

telemt_uptime_seconds 31756.5 (8h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 510483
telemt_connections_bad_total 103323
telemt_handshake_timeouts_total 56745
telemt_upstream_connect_attempt_total 7307
telemt_upstream_connect_success_total 7306
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 7307
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3676
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3546
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 84
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 225
telemt_me_reconnect_attempts_total 6614
telemt_me_reconnect_success_total 5689
telemt_me_reader_eof_total 5974
telemt_me_idle_close_by_peer_total 5974
telemt_me_seq_mismatch_total 13
telemt_me_route_drop_no_conn_total 119929
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 341985
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 743
telemt_desync_full_logged_total 263
telemt_desync_suppressed_total 480
telemt_desync_frames_bucket_total{bucket="1_2"} 250
telemt_desync_frames_bucket_total{bucket="3_10"} 250
telemt_desync_frames_bucket_total{bucket="gt_10"} 243
telemt_pool_swap_total 26
telemt_me_writer_removed_unexpected_total 5782
telemt_me_refill_failed_total 28
telemt_me_writer_restored_same_endpoint_total 5675
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 20
telemt_me_writer_removed_unexpected_minus_restored_total 93
telemt_user_connections_total{user="hello"} 341899
telemt_user_connections_current{user="hello"} 247
telemt_user_octets_from_client{user="hello"} 4656586692 (4.34 GB)
telemt_user_octets_to_client{user="hello"} 105624706424 (98.37 GB)
telemt_user_unique_ips_current{user="hello"} 97
telemt_user_unique_ips_recent_window{user="hello"} 49
```

## server5

```
telemt 3.3.17

telemt_uptime_seconds 32052.0 (8h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 429052
telemt_connections_bad_total 1407
telemt_handshake_timeouts_total 4225
telemt_upstream_connect_attempt_total 6762
telemt_upstream_connect_success_total 6632
telemt_upstream_connect_fail_total 130
telemt_upstream_connect_attempts_per_request{bucket="1"} 6762
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3201
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3383
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 48
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 130
telemt_me_keepalive_timeout_total 156
telemt_me_reconnect_attempts_total 5694
telemt_me_reconnect_success_total 5015
telemt_me_reader_eof_total 5302
telemt_me_idle_close_by_peer_total 5302
telemt_me_route_drop_no_conn_total 134079
telemt_me_route_drop_channel_closed_total 23
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 398605
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1238
telemt_desync_full_logged_total 434
telemt_desync_suppressed_total 804
telemt_desync_frames_bucket_total{bucket="1_2"} 382
telemt_desync_frames_bucket_total{bucket="3_10"} 403
telemt_desync_frames_bucket_total{bucket="gt_10"} 453
telemt_pool_swap_total 25
telemt_me_writer_removed_unexpected_total 5122
telemt_me_refill_failed_total 20
telemt_me_writer_restored_same_endpoint_total 4997
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 205
telemt_me_writer_removed_unexpected_minus_restored_total 107
telemt_user_connections_total{user="hello"} 398570
telemt_user_connections_current{user="hello"} 396
telemt_user_octets_from_client{user="hello"} 6689345228 (6.23 GB)
telemt_user_octets_to_client{user="hello"} 165752319296 (154.37 GB)
telemt_user_unique_ips_current{user="hello"} 127
telemt_user_unique_ips_recent_window{user="hello"} 47
```