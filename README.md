# Server Metrics 2026-03-11 05:30:46 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 54220.9 (15h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1056345
telemt_connections_bad_total 12018
telemt_handshake_timeouts_total 36715
telemt_upstream_connect_attempt_total 11576
telemt_upstream_connect_success_total 11567
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 11576
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5810
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5696
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 60
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 545
telemt_me_reconnect_attempts_total 20472
telemt_me_reconnect_success_total 8793
telemt_me_reader_eof_total 9576
telemt_me_idle_close_by_peer_total 9576
telemt_me_route_drop_no_conn_total 390314
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 948055
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4302
telemt_desync_full_logged_total 1223
telemt_desync_suppressed_total 3079
telemt_desync_frames_bucket_total{bucket="1_2"} 1200
telemt_desync_frames_bucket_total{bucket="3_10"} 1615
telemt_desync_frames_bucket_total{bucket="gt_10"} 1487
telemt_pool_swap_total 40
telemt_me_writer_removed_unexpected_total 9239
telemt_me_refill_failed_total 363
telemt_me_writer_restored_same_endpoint_total 8787
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 446
telemt_user_connections_total{user="hello"} 947760
telemt_user_connections_current{user="hello"} 998
telemt_user_octets_from_client{user="hello"} 12796167956 (11.92 GB)
telemt_user_octets_to_client{user="hello"} 276111503500 (257.15 GB)
telemt_user_unique_ips_current{user="hello"} 272
telemt_user_unique_ips_recent_window{user="hello"} 148
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 54277.8 (15h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 408604
telemt_connections_bad_total 2819
telemt_handshake_timeouts_total 19429
telemt_upstream_connect_attempt_total 20122
telemt_upstream_connect_success_total 17214
telemt_upstream_connect_fail_total 2907
telemt_upstream_connect_attempts_per_request{bucket="1"} 20121
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7702
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7269
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 209
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2034
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2907
telemt_me_keepalive_timeout_total 1791
telemt_me_reconnect_attempts_total 12349
telemt_me_reconnect_success_total 11527
telemt_me_reader_eof_total 12184
telemt_me_idle_close_by_peer_total 12182
telemt_me_route_drop_no_conn_total 191818
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 351596
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1871
telemt_desync_full_logged_total 561
telemt_desync_suppressed_total 1310
telemt_desync_frames_bucket_total{bucket="1_2"} 589
telemt_desync_frames_bucket_total{bucket="3_10"} 671
telemt_desync_frames_bucket_total{bucket="gt_10"} 611
telemt_pool_swap_total 44
telemt_me_writer_removed_unexpected_total 11663
telemt_me_refill_failed_total 22
telemt_me_writer_restored_same_endpoint_total 11506
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 86
telemt_me_writer_removed_unexpected_minus_restored_total 136
telemt_user_connections_total{user="hello"} 353866
telemt_user_connections_current{user="hello"} 293
telemt_user_octets_from_client{user="hello"} 3378494462 (3.15 GB)
telemt_user_octets_to_client{user="hello"} 86810510836 (80.85 GB)
telemt_user_msgs_from_client{user="hello"} 7933
telemt_user_msgs_to_client{user="hello"} 11226
telemt_user_unique_ips_current{user="hello"} 91
telemt_user_unique_ips_recent_window{user="hello"} 56
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 54277.6 (15h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 698628
telemt_connections_bad_total 5978
telemt_handshake_timeouts_total 38164
telemt_upstream_connect_attempt_total 14694
telemt_upstream_connect_success_total 14499
telemt_upstream_connect_fail_total 195
telemt_upstream_connect_attempts_per_request{bucket="1"} 14694
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7899
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6518
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 82
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 195
telemt_me_keepalive_timeout_total 572
telemt_me_reconnect_attempts_total 21758
telemt_me_reconnect_success_total 10686
telemt_me_reader_eof_total 11547
telemt_me_idle_close_by_peer_total 11547
telemt_me_route_drop_no_conn_total 235309
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 623745
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1727
telemt_desync_full_logged_total 514
telemt_desync_suppressed_total 1213
telemt_desync_frames_bucket_total{bucket="1_2"} 385
telemt_desync_frames_bucket_total{bucket="3_10"} 607
telemt_desync_frames_bucket_total{bucket="gt_10"} 735
telemt_pool_swap_total 37
telemt_me_writer_removed_unexpected_total 11173
telemt_me_refill_failed_total 343
telemt_me_writer_restored_same_endpoint_total 10675
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 487
telemt_user_connections_total{user="hello"} 624604
telemt_user_connections_current{user="hello"} 480
telemt_user_octets_from_client{user="hello"} 7593390297 (7.07 GB)
telemt_user_octets_to_client{user="hello"} 186292516441 (173.50 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 168
telemt_user_unique_ips_recent_window{user="hello"} 84
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 54278.0 (15h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 532088
telemt_connections_bad_total 50998
telemt_handshake_timeouts_total 55413
telemt_upstream_connect_attempt_total 15603
telemt_upstream_connect_success_total 15603
telemt_upstream_connect_attempts_per_request{bucket="1"} 15603
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8757
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6843
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_me_keepalive_timeout_total 494
telemt_me_reconnect_attempts_total 13908
telemt_me_reconnect_success_total 12865
telemt_me_reader_eof_total 13650
telemt_me_idle_close_by_peer_total 13650
telemt_me_seq_mismatch_total 11
telemt_me_route_drop_no_conn_total 157102
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 411098
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 875
telemt_desync_full_logged_total 360
telemt_desync_suppressed_total 515
telemt_desync_frames_bucket_total{bucket="1_2"} 324
telemt_desync_frames_bucket_total{bucket="3_10"} 317
telemt_desync_frames_bucket_total{bucket="gt_10"} 234
telemt_pool_swap_total 48
telemt_me_writer_removed_unexpected_total 13013
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 12843
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 148
telemt_user_connections_total{user="hello"} 410737
telemt_user_connections_current{user="hello"} 397
telemt_user_octets_from_client{user="hello"} 5004347272 (4.66 GB)
telemt_user_octets_to_client{user="hello"} 112713850244 (104.97 GB)
telemt_user_unique_ips_current{user="hello"} 119
telemt_user_unique_ips_recent_window{user="hello"} 70
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 54277.7 (15h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 555876
telemt_connections_bad_total 5954
telemt_handshake_timeouts_total 3744
telemt_upstream_connect_attempt_total 15544
telemt_upstream_connect_success_total 15479
telemt_upstream_connect_fail_total 65
telemt_upstream_connect_attempts_per_request{bucket="1"} 15544
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7907
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7443
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 127
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 65
telemt_me_keepalive_timeout_total 563
telemt_me_reconnect_attempts_total 16481
telemt_me_reconnect_success_total 12699
telemt_me_reader_eof_total 13401
telemt_me_idle_close_by_peer_total 13401
telemt_me_route_drop_no_conn_total 181383
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 507451
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 2467
telemt_desync_full_logged_total 964
telemt_desync_suppressed_total 1503
telemt_desync_frames_bucket_total{bucket="1_2"} 904
telemt_desync_frames_bucket_total{bucket="3_10"} 1050
telemt_desync_frames_bucket_total{bucket="gt_10"} 513
telemt_pool_swap_total 35
telemt_me_writer_removed_unexpected_total 12978
telemt_me_refill_failed_total 116
telemt_me_writer_restored_same_endpoint_total 12699
telemt_me_async_recovery_trigger_total 48
telemt_me_writer_removed_unexpected_minus_restored_total 279
telemt_user_connections_total{user="hello"} 507072
telemt_user_connections_current{user="hello"} 414
telemt_user_octets_from_client{user="hello"} 9088614092 (8.46 GB)
telemt_user_octets_to_client{user="hello"} 178267427096 (166.02 GB)
telemt_user_unique_ips_current{user="hello"} 148
telemt_user_unique_ips_recent_window{user="hello"} 70
```