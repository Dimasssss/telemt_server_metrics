# Server Metrics 2026-03-11 00:31:03 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 36238.1 (10h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 786937
telemt_connections_bad_total 9521
telemt_handshake_timeouts_total 8995
telemt_upstream_connect_attempt_total 7901
telemt_upstream_connect_success_total 7892
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 7901
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3937
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3897
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 57
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 474
telemt_me_reconnect_attempts_total 17662
telemt_me_reconnect_success_total 5997
telemt_me_reader_eof_total 6582
telemt_me_idle_close_by_peer_total 6582
telemt_me_route_drop_no_conn_total 324392
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 744788
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
telemt_me_writer_removed_unexpected_total 6410
telemt_me_refill_failed_total 363
telemt_me_writer_restored_same_endpoint_total 5991
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 413
telemt_user_connections_total{user="hello"} 744565
telemt_user_connections_current{user="hello"} 413
telemt_user_octets_from_client{user="hello"} 10349342464 (9.64 GB)
telemt_user_octets_to_client{user="hello"} 221961163608 (206.72 GB)
telemt_user_unique_ips_current{user="hello"} 159
telemt_user_unique_ips_recent_window{user="hello"} 55
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 36295.0 (10h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 339609
telemt_connections_bad_total 2384
telemt_handshake_timeouts_total 17631
telemt_upstream_connect_attempt_total 14890
telemt_upstream_connect_success_total 12011
telemt_upstream_connect_fail_total 2879
telemt_upstream_connect_attempts_per_request{bucket="1"} 14890
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5186
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4585
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 209
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2031
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2879
telemt_me_keepalive_timeout_total 1705
telemt_me_reconnect_attempts_total 8015
telemt_me_reconnect_success_total 7202
telemt_me_reader_eof_total 7599
telemt_me_idle_close_by_peer_total 7597
telemt_me_route_drop_no_conn_total 172120
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 289077
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1752
telemt_desync_full_logged_total 492
telemt_desync_suppressed_total 1260
telemt_desync_frames_bucket_total{bucket="1_2"} 539
telemt_desync_frames_bucket_total{bucket="3_10"} 618
telemt_desync_frames_bucket_total{bucket="gt_10"} 595
telemt_pool_swap_total 28
telemt_me_writer_removed_unexpected_total 7301
telemt_me_refill_failed_total 22
telemt_me_writer_restored_same_endpoint_total 7181
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 86
telemt_me_writer_removed_unexpected_minus_restored_total 99
telemt_user_connections_total{user="hello"} 291346
telemt_user_connections_current{user="hello"} 145
telemt_user_octets_from_client{user="hello"} 2827792822 (2.63 GB)
telemt_user_octets_to_client{user="hello"} 70029354604 (65.22 GB)
telemt_user_msgs_from_client{user="hello"} 7933
telemt_user_msgs_to_client{user="hello"} 11226
telemt_user_unique_ips_current{user="hello"} 63
telemt_user_unique_ips_recent_window{user="hello"} 29
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 36294.7 (10h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 564641
telemt_connections_bad_total 3885
telemt_handshake_timeouts_total 34067
telemt_upstream_connect_attempt_total 9966
telemt_upstream_connect_success_total 9827
telemt_upstream_connect_fail_total 139
telemt_upstream_connect_attempts_per_request{bucket="1"} 9966
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5541
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4221
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 65
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 139
telemt_me_keepalive_timeout_total 508
telemt_me_reconnect_attempts_total 17951
telemt_me_reconnect_success_total 6891
telemt_me_reader_eof_total 7526
telemt_me_idle_close_by_peer_total 7526
telemt_me_route_drop_no_conn_total 194265
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 498182
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1521
telemt_desync_full_logged_total 434
telemt_desync_suppressed_total 1087
telemt_desync_frames_bucket_total{bucket="1_2"} 343
telemt_desync_frames_bucket_total{bucket="3_10"} 523
telemt_desync_frames_bucket_total{bucket="gt_10"} 655
telemt_pool_swap_total 21
telemt_me_writer_removed_unexpected_total 7332
telemt_me_refill_failed_total 343
telemt_me_writer_restored_same_endpoint_total 6880
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 441
telemt_user_connections_total{user="hello"} 499107
telemt_user_connections_current{user="hello"} 194
telemt_user_octets_from_client{user="hello"} 6814065737 (6.35 GB)
telemt_user_octets_to_client{user="hello"} 153879290733 (143.31 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 97
telemt_user_unique_ips_recent_window{user="hello"} 37
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 36295.1 (10h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 411659
telemt_connections_bad_total 34577
telemt_handshake_timeouts_total 38517
telemt_upstream_connect_attempt_total 10336
telemt_upstream_connect_success_total 10336
telemt_upstream_connect_attempts_per_request{bucket="1"} 10336
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5829
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4506
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 400
telemt_me_reconnect_attempts_total 9505
telemt_me_reconnect_success_total 8474
telemt_me_reader_eof_total 8955
telemt_me_idle_close_by_peer_total 8955
telemt_me_seq_mismatch_total 5
telemt_me_route_drop_no_conn_total 127231
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 325563
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 705
telemt_desync_full_logged_total 286
telemt_desync_suppressed_total 419
telemt_desync_frames_bucket_total{bucket="1_2"} 272
telemt_desync_frames_bucket_total{bucket="3_10"} 247
telemt_desync_frames_bucket_total{bucket="gt_10"} 186
telemt_pool_swap_total 29
telemt_me_writer_removed_unexpected_total 8587
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 8458
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 113
telemt_user_connections_total{user="hello"} 325238
telemt_user_connections_current{user="hello"} 164
telemt_user_octets_from_client{user="hello"} 4185860800 (3.90 GB)
telemt_user_octets_to_client{user="hello"} 90499382912 (84.28 GB)
telemt_user_unique_ips_current{user="hello"} 56
telemt_user_unique_ips_recent_window{user="hello"} 27
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 36294.8 (10h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 435498
telemt_connections_bad_total 4014
telemt_handshake_timeouts_total 2749
telemt_upstream_connect_attempt_total 10998
telemt_upstream_connect_success_total 10953
telemt_upstream_connect_fail_total 45
telemt_upstream_connect_attempts_per_request{bucket="1"} 10998
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5705
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5135
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 111
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 45
telemt_me_keepalive_timeout_total 502
telemt_me_reconnect_attempts_total 12822
telemt_me_reconnect_success_total 9056
telemt_me_reader_eof_total 9526
telemt_me_idle_close_by_peer_total 9526
telemt_me_route_drop_no_conn_total 145940
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 401797
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 2264
telemt_desync_full_logged_total 875
telemt_desync_suppressed_total 1389
telemt_desync_frames_bucket_total{bucket="1_2"} 832
telemt_desync_frames_bucket_total{bucket="3_10"} 970
telemt_desync_frames_bucket_total{bucket="gt_10"} 462
telemt_pool_swap_total 17
telemt_me_writer_removed_unexpected_total 9291
telemt_me_refill_failed_total 116
telemt_me_writer_restored_same_endpoint_total 9056
telemt_me_async_recovery_trigger_total 48
telemt_me_writer_removed_unexpected_minus_restored_total 235
telemt_user_connections_total{user="hello"} 401539
telemt_user_connections_current{user="hello"} 197
telemt_user_octets_from_client{user="hello"} 8345267428 (7.77 GB)
telemt_user_octets_to_client{user="hello"} 145825899784 (135.81 GB)
telemt_user_unique_ips_current{user="hello"} 72
telemt_user_unique_ips_recent_window{user="hello"} 32
```