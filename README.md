# Server Metrics 2026-03-12 08:58:15 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 10775.7 (2h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 333595
telemt_connections_bad_total 1323
telemt_handshake_timeouts_total 2279
telemt_upstream_connect_attempt_total 2027
telemt_upstream_connect_success_total 2016
telemt_upstream_connect_fail_total 11
telemt_upstream_connect_attempts_per_request{bucket="1"} 2027
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1083
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 932
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 11
telemt_me_keepalive_timeout_total 24
telemt_me_reconnect_attempts_total 1472
telemt_me_reconnect_success_total 1462
telemt_me_reader_eof_total 1517
telemt_me_idle_close_by_peer_total 1517
telemt_me_route_drop_no_conn_total 110630
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 322019
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1500
telemt_desync_full_logged_total 375
telemt_desync_suppressed_total 1125
telemt_desync_frames_bucket_total{bucket="1_2"} 374
telemt_desync_frames_bucket_total{bucket="3_10"} 545
telemt_desync_frames_bucket_total{bucket="gt_10"} 581
telemt_pool_swap_total 9
telemt_me_writer_removed_unexpected_total 1474
telemt_me_writer_restored_same_endpoint_total 1449
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 12
telemt_user_connections_total{user="hello"} 321906
telemt_user_connections_current{user="hello"} 1373
telemt_user_octets_from_client{user="hello"} 4965730068 (4.62 GB)
telemt_user_octets_to_client{user="hello"} 88637300488 (82.55 GB)
telemt_user_unique_ips_current{user="hello"} 383
telemt_user_unique_ips_recent_window{user="hello"} 230
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 40396.0 (11h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 227698
telemt_connections_bad_total 2798
telemt_handshake_timeouts_total 7582
telemt_upstream_connect_attempt_total 10336
telemt_upstream_connect_success_total 10330
telemt_upstream_connect_fail_total 6
telemt_upstream_connect_attempts_per_request{bucket="1"} 10336
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5069
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5246
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 15
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 6
telemt_me_keepalive_timeout_total 613
telemt_me_reconnect_attempts_total 8181
telemt_me_reconnect_success_total 8138
telemt_me_reader_eof_total 8643
telemt_me_idle_close_by_peer_total 8643
telemt_me_route_drop_no_conn_total 65257
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 200072
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 455
telemt_desync_full_logged_total 187
telemt_desync_suppressed_total 268
telemt_desync_frames_bucket_total{bucket="1_2"} 130
telemt_desync_frames_bucket_total{bucket="3_10"} 167
telemt_desync_frames_bucket_total{bucket="gt_10"} 158
telemt_pool_swap_total 42
telemt_me_writer_removed_unexpected_total 8200
telemt_me_writer_restored_same_endpoint_total 8129
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 62
telemt_user_connections_total{user="hello"} 200464
telemt_user_connections_current{user="hello"} 591
telemt_user_octets_from_client{user="hello"} 2992194007 (2.79 GB)
telemt_user_octets_to_client{user="hello"} 76335166770 (71.09 GB)
telemt_user_msgs_from_client{user="hello"} 353
telemt_user_msgs_to_client{user="hello"} 423
telemt_user_unique_ips_current{user="hello"} 141
telemt_user_unique_ips_recent_window{user="hello"} 94
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 40395.9 (11h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 632435
telemt_connections_bad_total 2891
telemt_handshake_timeouts_total 46766
telemt_upstream_connect_attempt_total 10402
telemt_upstream_connect_success_total 10397
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 10402
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5800
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4549
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 44
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 525
telemt_me_reconnect_attempts_total 8104
telemt_me_reconnect_success_total 8033
telemt_me_reader_eof_total 8437
telemt_me_idle_close_by_peer_total 8437
telemt_me_route_drop_no_conn_total 129052
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 371852
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1687
telemt_desync_full_logged_total 509
telemt_desync_suppressed_total 1178
telemt_desync_frames_bucket_total{bucket="1_2"} 224
telemt_desync_frames_bucket_total{bucket="3_10"} 581
telemt_desync_frames_bucket_total{bucket="gt_10"} 882
telemt_pool_swap_total 41
telemt_me_writer_removed_unexpected_total 8031
telemt_me_refill_failed_total 1
telemt_me_writer_restored_same_endpoint_total 7992
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_user_connections_total{user="hello"} 372120
telemt_user_connections_current{user="hello"} 832
telemt_user_octets_from_client{user="hello"} 4371068004 (4.07 GB)
telemt_user_octets_to_client{user="hello"} 125855068873 (117.21 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 231
telemt_user_unique_ips_recent_window{user="hello"} 138
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 40396.4 (11h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 305645
telemt_connections_bad_total 1814
telemt_handshake_timeouts_total 21064
telemt_upstream_connect_attempt_total 11129
telemt_upstream_connect_success_total 11085
telemt_upstream_connect_fail_total 44
telemt_upstream_connect_attempts_per_request{bucket="1"} 11129
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6327
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4749
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 44
telemt_me_keepalive_timeout_total 788
telemt_me_reconnect_attempts_total 9105
telemt_me_reconnect_success_total 9072
telemt_me_reader_eof_total 9618
telemt_me_idle_close_by_peer_total 9618
telemt_me_route_drop_no_conn_total 103130
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 255648
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 490
telemt_desync_full_logged_total 180
telemt_desync_suppressed_total 310
telemt_desync_frames_bucket_total{bucket="1_2"} 159
telemt_desync_frames_bucket_total{bucket="3_10"} 196
telemt_desync_frames_bucket_total{bucket="gt_10"} 135
telemt_pool_swap_total 39
telemt_me_writer_removed_unexpected_total 9129
telemt_me_writer_restored_same_endpoint_total 9051
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 108
telemt_me_writer_removed_unexpected_minus_restored_total 57
telemt_user_connections_total{user="hello"} 255471
telemt_user_connections_current{user="hello"} 607
telemt_user_octets_from_client{user="hello"} 2970955724 (2.77 GB)
telemt_user_octets_to_client{user="hello"} 91561132396 (85.27 GB)
telemt_user_unique_ips_current{user="hello"} 164
telemt_user_unique_ips_recent_window{user="hello"} 114
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 40396.5 (11h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 341103
telemt_connections_bad_total 375
telemt_handshake_timeouts_total 2564
telemt_upstream_connect_attempt_total 13257
telemt_upstream_connect_success_total 13103
telemt_upstream_connect_fail_total 154
telemt_upstream_connect_attempts_per_request{bucket="1"} 13257
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6749
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6278
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 71
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 154
telemt_me_keepalive_timeout_total 572
telemt_me_reconnect_attempts_total 12601
telemt_me_reconnect_success_total 11087
telemt_me_reader_eof_total 11551
telemt_me_idle_close_by_peer_total 11551
telemt_me_seq_mismatch_total 17
telemt_me_route_drop_no_conn_total 109313
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 322237
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 1355
telemt_desync_full_logged_total 448
telemt_desync_suppressed_total 907
telemt_desync_frames_bucket_total{bucket="1_2"} 381
telemt_desync_frames_bucket_total{bucket="3_10"} 474
telemt_desync_frames_bucket_total{bucket="gt_10"} 500
telemt_pool_swap_total 24
telemt_me_writer_removed_unexpected_total 11233
telemt_me_refill_failed_total 46
telemt_me_writer_restored_same_endpoint_total 11065
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 146
telemt_user_connections_total{user="hello"} 322179
telemt_user_connections_current{user="hello"} 770
telemt_user_octets_from_client{user="hello"} 3507830512 (3.27 GB)
telemt_user_octets_to_client{user="hello"} 78409545160 (73.02 GB)
telemt_user_unique_ips_current{user="hello"} 184
telemt_user_unique_ips_recent_window{user="hello"} 124
```