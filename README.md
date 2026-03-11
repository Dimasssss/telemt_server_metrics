# Server Metrics 2026-03-11 04:45:02 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 51477.0 (14h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 997682
telemt_connections_bad_total 10080
telemt_handshake_timeouts_total 30413
telemt_upstream_connect_attempt_total 11072
telemt_upstream_connect_success_total 11063
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 11072
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5556
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5446
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 60
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 534
telemt_me_reconnect_attempts_total 20098
telemt_me_reconnect_success_total 8424
telemt_me_reader_eof_total 9181
telemt_me_idle_close_by_peer_total 9181
telemt_me_route_drop_no_conn_total 373692
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 899384
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4068
telemt_desync_full_logged_total 1143
telemt_desync_suppressed_total 2925
telemt_desync_frames_bucket_total{bucket="1_2"} 1145
telemt_desync_frames_bucket_total{bucket="3_10"} 1532
telemt_desync_frames_bucket_total{bucket="gt_10"} 1391
telemt_pool_swap_total 37
telemt_me_writer_removed_unexpected_total 8864
telemt_me_refill_failed_total 363
telemt_me_writer_restored_same_endpoint_total 8418
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 440
telemt_user_connections_total{user="hello"} 899102
telemt_user_connections_current{user="hello"} 768
telemt_user_octets_from_client{user="hello"} 11758428092 (10.95 GB)
telemt_user_octets_to_client{user="hello"} 264737050340 (246.56 GB)
telemt_user_unique_ips_current{user="hello"} 233
telemt_user_unique_ips_recent_window{user="hello"} 94
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 51533.8 (14h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 392579
telemt_connections_bad_total 2532
telemt_handshake_timeouts_total 19045
telemt_upstream_connect_attempt_total 19389
telemt_upstream_connect_success_total 16488
telemt_upstream_connect_fail_total 2901
telemt_upstream_connect_attempts_per_request{bucket="1"} 19389
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7328
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6918
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 209
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2033
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2901
telemt_me_keepalive_timeout_total 1777
telemt_me_reconnect_attempts_total 11752
telemt_me_reconnect_success_total 10933
telemt_me_reader_eof_total 11559
telemt_me_idle_close_by_peer_total 11557
telemt_me_route_drop_no_conn_total 186877
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 337270
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1851
telemt_desync_full_logged_total 551
telemt_desync_suppressed_total 1300
telemt_desync_frames_bucket_total{bucket="1_2"} 575
telemt_desync_frames_bucket_total{bucket="3_10"} 665
telemt_desync_frames_bucket_total{bucket="gt_10"} 611
telemt_pool_swap_total 42
telemt_me_writer_removed_unexpected_total 11063
telemt_me_refill_failed_total 22
telemt_me_writer_restored_same_endpoint_total 10912
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 86
telemt_me_writer_removed_unexpected_minus_restored_total 130
telemt_user_connections_total{user="hello"} 339542
telemt_user_connections_current{user="hello"} 227
telemt_user_octets_from_client{user="hello"} 3249728274 (3.03 GB)
telemt_user_octets_to_client{user="hello"} 81115880448 (75.55 GB)
telemt_user_msgs_from_client{user="hello"} 7933
telemt_user_msgs_to_client{user="hello"} 11226
telemt_user_unique_ips_current{user="hello"} 83
telemt_user_unique_ips_recent_window{user="hello"} 33
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 51533.6 (14h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 664134
telemt_connections_bad_total 5591
telemt_handshake_timeouts_total 36452
telemt_upstream_connect_attempt_total 14005
telemt_upstream_connect_success_total 13822
telemt_upstream_connect_fail_total 183
telemt_upstream_connect_attempts_per_request{bucket="1"} 14005
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7541
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6202
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 79
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 183
telemt_me_keepalive_timeout_total 561
telemt_me_reconnect_attempts_total 21210
telemt_me_reconnect_success_total 10140
telemt_me_reader_eof_total 10971
telemt_me_idle_close_by_peer_total 10971
telemt_me_route_drop_no_conn_total 223678
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 592014
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1633
telemt_desync_full_logged_total 484
telemt_desync_suppressed_total 1149
telemt_desync_frames_bucket_total{bucket="1_2"} 356
telemt_desync_frames_bucket_total{bucket="3_10"} 574
telemt_desync_frames_bucket_total{bucket="gt_10"} 703
telemt_pool_swap_total 35
telemt_me_writer_removed_unexpected_total 10618
telemt_me_refill_failed_total 343
telemt_me_writer_restored_same_endpoint_total 10129
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 478
telemt_user_connections_total{user="hello"} 592882
telemt_user_connections_current{user="hello"} 431
telemt_user_octets_from_client{user="hello"} 7350904349 (6.85 GB)
telemt_user_octets_to_client{user="hello"} 178691406009 (166.42 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 145
telemt_user_unique_ips_recent_window{user="hello"} 67
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 51534.1 (14h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 507443
telemt_connections_bad_total 48500
telemt_handshake_timeouts_total 53350
telemt_upstream_connect_attempt_total 14924
telemt_upstream_connect_success_total 14924
telemt_upstream_connect_attempts_per_request{bucket="1"} 14924
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8410
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6511
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_me_keepalive_timeout_total 488
telemt_me_reconnect_attempts_total 13360
telemt_me_reconnect_success_total 12318
telemt_me_reader_eof_total 13083
telemt_me_idle_close_by_peer_total 13083
telemt_me_seq_mismatch_total 9
telemt_me_route_drop_no_conn_total 150543
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 391392
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 828
telemt_desync_full_logged_total 336
telemt_desync_suppressed_total 492
telemt_desync_frames_bucket_total{bucket="1_2"} 305
telemt_desync_frames_bucket_total{bucket="3_10"} 296
telemt_desync_frames_bucket_total{bucket="gt_10"} 227
telemt_pool_swap_total 46
telemt_me_writer_removed_unexpected_total 12461
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 12298
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 143
telemt_user_connections_total{user="hello"} 391050
telemt_user_connections_current{user="hello"} 303
telemt_user_octets_from_client{user="hello"} 4749070432 (4.42 GB)
telemt_user_octets_to_client{user="hello"} 107089058348 (99.73 GB)
telemt_user_unique_ips_current{user="hello"} 98
telemt_user_unique_ips_recent_window{user="hello"} 50
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 51533.6 (14h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 529801
telemt_connections_bad_total 5828
telemt_handshake_timeouts_total 3419
telemt_upstream_connect_attempt_total 14924
telemt_upstream_connect_success_total 14862
telemt_upstream_connect_fail_total 62
telemt_upstream_connect_attempts_per_request{bucket="1"} 14924
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7594
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7141
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 125
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 62
telemt_me_keepalive_timeout_total 555
telemt_me_reconnect_attempts_total 15996
telemt_me_reconnect_success_total 12214
telemt_me_reader_eof_total 12897
telemt_me_idle_close_by_peer_total 12897
telemt_me_route_drop_no_conn_total 171535
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 482708
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 2407
telemt_desync_full_logged_total 940
telemt_desync_suppressed_total 1467
telemt_desync_frames_bucket_total{bucket="1_2"} 887
telemt_desync_frames_bucket_total{bucket="3_10"} 1019
telemt_desync_frames_bucket_total{bucket="gt_10"} 501
telemt_pool_swap_total 33
telemt_me_writer_removed_unexpected_total 12489
telemt_me_refill_failed_total 116
telemt_me_writer_restored_same_endpoint_total 12214
telemt_me_async_recovery_trigger_total 48
telemt_me_writer_removed_unexpected_minus_restored_total 275
telemt_user_connections_total{user="hello"} 482325
telemt_user_connections_current{user="hello"} 420
telemt_user_octets_from_client{user="hello"} 8853924912 (8.25 GB)
telemt_user_octets_to_client{user="hello"} 171224685488 (159.47 GB)
telemt_user_unique_ips_current{user="hello"} 140
telemt_user_unique_ips_recent_window{user="hello"} 67
```