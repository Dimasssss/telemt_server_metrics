# Server Metrics 2026-03-11 03:59:18 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 48733.4 (13h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 932312
telemt_connections_bad_total 10072
telemt_handshake_timeouts_total 25864
telemt_upstream_connect_attempt_total 10521
telemt_upstream_connect_success_total 10512
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 10521
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5268
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5184
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 59
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 526
telemt_me_reconnect_attempts_total 19677
telemt_me_reconnect_success_total 8005
telemt_me_reader_eof_total 8732
telemt_me_idle_close_by_peer_total 8732
telemt_me_route_drop_no_conn_total 359176
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 856151
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3922
telemt_desync_full_logged_total 1093
telemt_desync_suppressed_total 2829
telemt_desync_frames_bucket_total{bucket="1_2"} 1114
telemt_desync_frames_bucket_total{bucket="3_10"} 1471
telemt_desync_frames_bucket_total{bucket="gt_10"} 1337
telemt_pool_swap_total 34
telemt_me_writer_removed_unexpected_total 8442
telemt_me_refill_failed_total 363
telemt_me_writer_restored_same_endpoint_total 7999
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 437
telemt_user_connections_total{user="hello"} 855874
telemt_user_connections_current{user="hello"} 556
telemt_user_octets_from_client{user="hello"} 11337734928 (10.56 GB)
telemt_user_octets_to_client{user="hello"} 253064293884 (235.68 GB)
telemt_user_unique_ips_current{user="hello"} 211
telemt_user_unique_ips_recent_window{user="hello"} 85
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 48790.0 (13h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 379261
telemt_connections_bad_total 2530
telemt_handshake_timeouts_total 18769
telemt_upstream_connect_attempt_total 18648
telemt_upstream_connect_success_total 15753
telemt_upstream_connect_fail_total 2895
telemt_upstream_connect_attempts_per_request{bucket="1"} 18648
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6975
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6536
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 209
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2033
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2895
telemt_me_keepalive_timeout_total 1768
telemt_me_reconnect_attempts_total 11148
telemt_me_reconnect_success_total 10330
telemt_me_reader_eof_total 10919
telemt_me_idle_close_by_peer_total 10917
telemt_me_route_drop_no_conn_total 182372
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 325038
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1831
telemt_desync_full_logged_total 538
telemt_desync_suppressed_total 1293
telemt_desync_frames_bucket_total{bucket="1_2"} 560
telemt_desync_frames_bucket_total{bucket="3_10"} 660
telemt_desync_frames_bucket_total{bucket="gt_10"} 611
telemt_pool_swap_total 40
telemt_me_writer_removed_unexpected_total 10451
telemt_me_refill_failed_total 22
telemt_me_writer_restored_same_endpoint_total 10309
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 86
telemt_me_writer_removed_unexpected_minus_restored_total 121
telemt_user_connections_total{user="hello"} 327304
telemt_user_connections_current{user="hello"} 276
telemt_user_octets_from_client{user="hello"} 3106886886 (2.89 GB)
telemt_user_octets_to_client{user="hello"} 76959331688 (71.67 GB)
telemt_user_msgs_from_client{user="hello"} 7933
telemt_user_msgs_to_client{user="hello"} 11226
telemt_user_unique_ips_current{user="hello"} 81
telemt_user_unique_ips_recent_window{user="hello"} 38
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 48789.9 (13h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 636975
telemt_connections_bad_total 5364
telemt_handshake_timeouts_total 35442
telemt_upstream_connect_attempt_total 13169
telemt_upstream_connect_success_total 12996
telemt_upstream_connect_fail_total 172
telemt_upstream_connect_attempts_per_request{bucket="1"} 13168
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7100
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5820
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 76
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 172
telemt_me_keepalive_timeout_total 554
telemt_me_reconnect_attempts_total 20515
telemt_me_reconnect_success_total 9445
telemt_me_reader_eof_total 10240
telemt_me_idle_close_by_peer_total 10240
telemt_me_route_drop_no_conn_total 215442
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 566865
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1628
telemt_desync_full_logged_total 480
telemt_desync_suppressed_total 1148
telemt_desync_frames_bucket_total{bucket="1_2"} 354
telemt_desync_frames_bucket_total{bucket="3_10"} 572
telemt_desync_frames_bucket_total{bucket="gt_10"} 702
telemt_pool_swap_total 33
telemt_me_writer_removed_unexpected_total 9918
telemt_me_refill_failed_total 343
telemt_me_writer_restored_same_endpoint_total 9434
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 473
telemt_user_connections_total{user="hello"} 567756
telemt_user_connections_current{user="hello"} 288
telemt_user_octets_from_client{user="hello"} 7196589017 (6.70 GB)
telemt_user_octets_to_client{user="hello"} 171282884429 (159.52 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 114
telemt_user_unique_ips_recent_window{user="hello"} 61
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 48790.3 (13h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 482584
telemt_connections_bad_total 46004
telemt_handshake_timeouts_total 48684
telemt_upstream_connect_attempt_total 14221
telemt_upstream_connect_success_total 14221
telemt_upstream_connect_attempts_per_request{bucket="1"} 14221
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8028
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6190
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_me_keepalive_timeout_total 478
telemt_me_reconnect_attempts_total 12788
telemt_me_reconnect_success_total 11749
telemt_me_reader_eof_total 12483
telemt_me_idle_close_by_peer_total 12483
telemt_me_seq_mismatch_total 8
telemt_me_route_drop_no_conn_total 143796
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 373877
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 808
telemt_desync_full_logged_total 321
telemt_desync_suppressed_total 487
telemt_desync_frames_bucket_total{bucket="1_2"} 298
telemt_desync_frames_bucket_total{bucket="3_10"} 285
telemt_desync_frames_bucket_total{bucket="gt_10"} 225
telemt_pool_swap_total 43
telemt_me_writer_removed_unexpected_total 11887
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 11730
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 138
telemt_user_connections_total{user="hello"} 373547
telemt_user_connections_current{user="hello"} 223
telemt_user_octets_from_client{user="hello"} 4533427624 (4.22 GB)
telemt_user_octets_to_client{user="hello"} 100172683724 (93.29 GB)
telemt_user_unique_ips_current{user="hello"} 73
telemt_user_unique_ips_recent_window{user="hello"} 42
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 48790.0 (13h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 509013
telemt_connections_bad_total 5824
telemt_handshake_timeouts_total 3163
telemt_upstream_connect_attempt_total 14238
telemt_upstream_connect_success_total 14180
telemt_upstream_connect_fail_total 58
telemt_upstream_connect_attempts_per_request{bucket="1"} 14238
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7282
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6775
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 121
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 58
telemt_me_keepalive_timeout_total 547
telemt_me_reconnect_attempts_total 15444
telemt_me_reconnect_success_total 11664
telemt_me_reader_eof_total 12319
telemt_me_idle_close_by_peer_total 12319
telemt_me_route_drop_no_conn_total 163366
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 463010
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 2375
telemt_desync_full_logged_total 926
telemt_desync_suppressed_total 1449
telemt_desync_frames_bucket_total{bucket="1_2"} 878
telemt_desync_frames_bucket_total{bucket="3_10"} 1006
telemt_desync_frames_bucket_total{bucket="gt_10"} 491
telemt_pool_swap_total 31
telemt_me_writer_removed_unexpected_total 11930
telemt_me_refill_failed_total 116
telemt_me_writer_restored_same_endpoint_total 11664
telemt_me_async_recovery_trigger_total 48
telemt_me_writer_removed_unexpected_minus_restored_total 266
telemt_user_connections_total{user="hello"} 462645
telemt_user_connections_current{user="hello"} 303
telemt_user_octets_from_client{user="hello"} 8682312656 (8.09 GB)
telemt_user_octets_to_client{user="hello"} 164470119100 (153.17 GB)
telemt_user_unique_ips_current{user="hello"} 95
telemt_user_unique_ips_recent_window{user="hello"} 36
```