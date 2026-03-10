# Server Metrics 2026-03-10 18:24:19 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 14235.1 (3h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 470413
telemt_connections_bad_total 7985
telemt_handshake_timeouts_total 2261
telemt_upstream_connect_attempt_total 2840
telemt_upstream_connect_success_total 2831
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 2840
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1354
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1437
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 39
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 284
telemt_me_reconnect_attempts_total 11334
telemt_me_reconnect_success_total 2061
telemt_me_reader_eof_total 2330
telemt_me_idle_close_by_peer_total 2330
telemt_me_route_drop_no_conn_total 198096
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 443430
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2266
telemt_desync_full_logged_total 612
telemt_desync_suppressed_total 1654
telemt_desync_frames_bucket_total{bucket="1_2"} 607
telemt_desync_frames_bucket_total{bucket="3_10"} 871
telemt_desync_frames_bucket_total{bucket="gt_10"} 788
telemt_pool_swap_total 2
telemt_me_writer_removed_unexpected_total 2358
telemt_me_refill_failed_total 289
telemt_me_writer_restored_same_endpoint_total 2055
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 297
telemt_user_connections_total{user="hello"} 443350
telemt_user_connections_current{user="hello"} 1224
telemt_user_octets_from_client{user="hello"} 5850589280 (5.45 GB)
telemt_user_octets_to_client{user="hello"} 129097826300 (120.23 GB)
telemt_user_unique_ips_current{user="hello"} 322
telemt_user_unique_ips_recent_window{user="hello"} 184
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 14291.7 (3h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 179990
telemt_connections_bad_total 1703
telemt_handshake_timeouts_total 12728
telemt_upstream_connect_attempt_total 3246
telemt_upstream_connect_success_total 3231
telemt_upstream_connect_fail_total 15
telemt_upstream_connect_attempts_per_request{bucket="1"} 3246
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1636
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1586
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 15
telemt_me_keepalive_timeout_total 52
telemt_me_reconnect_attempts_total 2507
telemt_me_reconnect_success_total 2487
telemt_me_reader_eof_total 2588
telemt_me_idle_close_by_peer_total 2588
telemt_me_route_drop_no_conn_total 53905
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 156263
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 697
telemt_desync_full_logged_total 214
telemt_desync_suppressed_total 483
telemt_desync_frames_bucket_total{bucket="1_2"} 252
telemt_desync_frames_bucket_total{bucket="3_10"} 237
telemt_desync_frames_bucket_total{bucket="gt_10"} 208
telemt_pool_swap_total 10
telemt_me_writer_removed_unexpected_total 2504
telemt_me_writer_restored_same_endpoint_total 2466
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 86
telemt_me_writer_removed_unexpected_minus_restored_total 17
telemt_user_connections_total{user="hello"} 156226
telemt_user_connections_current{user="hello"} 546
telemt_user_octets_from_client{user="hello"} 1921492408 (1.79 GB)
telemt_user_octets_to_client{user="hello"} 42092880240 (39.20 GB)
telemt_user_unique_ips_current{user="hello"} 153
telemt_user_unique_ips_recent_window{user="hello"} 79
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 14291.6 (3h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 345159
telemt_connections_bad_total 1054
telemt_handshake_timeouts_total 31712
telemt_upstream_connect_attempt_total 4656
telemt_upstream_connect_success_total 4585
telemt_upstream_connect_fail_total 71
telemt_upstream_connect_attempts_per_request{bucket="1"} 4656
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2769
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1788
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 28
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 71
telemt_me_keepalive_timeout_total 85
telemt_me_reconnect_attempts_total 3988
telemt_me_reconnect_success_total 2784
telemt_me_reader_eof_total 2916
telemt_me_idle_close_by_peer_total 2916
telemt_me_route_drop_no_conn_total 113464
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 288578
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 915
telemt_desync_full_logged_total 261
telemt_desync_suppressed_total 654
telemt_desync_frames_bucket_total{bucket="1_2"} 228
telemt_desync_frames_bucket_total{bucket="3_10"} 311
telemt_desync_frames_bucket_total{bucket="gt_10"} 376
telemt_pool_swap_total 7
telemt_me_writer_removed_unexpected_total 2872
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 2773
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 88
telemt_user_connections_total{user="hello"} 289539
telemt_user_connections_current{user="hello"} 799
telemt_user_octets_from_client{user="hello"} 4109899013 (3.83 GB)
telemt_user_octets_to_client{user="hello"} 91597500181 (85.31 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 226
telemt_user_unique_ips_recent_window{user="hello"} 141
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 14292.1 (3h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 223478
telemt_connections_bad_total 13957
telemt_handshake_timeouts_total 20519
telemt_upstream_connect_attempt_total 3623
telemt_upstream_connect_success_total 3623
telemt_upstream_connect_attempts_per_request{bucket="1"} 3623
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1934
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1688
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 64
telemt_me_reconnect_attempts_total 2896
telemt_me_reconnect_success_total 2878
telemt_me_reader_eof_total 2993
telemt_me_idle_close_by_peer_total 2993
telemt_me_seq_mismatch_total 1
telemt_me_route_drop_no_conn_total 73546
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 179789
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 506
telemt_desync_full_logged_total 201
telemt_desync_suppressed_total 305
telemt_desync_frames_bucket_total{bucket="1_2"} 167
telemt_desync_frames_bucket_total{bucket="3_10"} 185
telemt_desync_frames_bucket_total{bucket="gt_10"} 154
telemt_pool_swap_total 10
telemt_me_writer_removed_unexpected_total 2904
telemt_me_writer_restored_same_endpoint_total 2866
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 26
telemt_user_connections_total{user="hello"} 179582
telemt_user_connections_current{user="hello"} 503
telemt_user_octets_from_client{user="hello"} 2737323696 (2.55 GB)
telemt_user_octets_to_client{user="hello"} 50162652380 (46.72 GB)
telemt_user_unique_ips_current{user="hello"} 132
telemt_user_unique_ips_recent_window{user="hello"} 87
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 14291.9 (3h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 236636
telemt_connections_bad_total 799
telemt_handshake_timeouts_total 1729
telemt_upstream_connect_attempt_total 4347
telemt_upstream_connect_success_total 4334
telemt_upstream_connect_fail_total 13
telemt_upstream_connect_attempts_per_request{bucket="1"} 4347
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2230
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2057
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 46
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 13
telemt_me_keepalive_timeout_total 90
telemt_me_reconnect_attempts_total 3595
telemt_me_reconnect_success_total 3569
telemt_me_reader_eof_total 3662
telemt_me_idle_close_by_peer_total 3662
telemt_me_route_drop_no_conn_total 87456
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 222844
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 1205
telemt_desync_full_logged_total 431
telemt_desync_suppressed_total 774
telemt_desync_frames_bucket_total{bucket="1_2"} 498
telemt_desync_frames_bucket_total{bucket="3_10"} 504
telemt_desync_frames_bucket_total{bucket="gt_10"} 203
telemt_pool_swap_total 4
telemt_me_writer_removed_unexpected_total 3611
telemt_me_writer_restored_same_endpoint_total 3569
telemt_me_async_recovery_trigger_total 48
telemt_me_writer_removed_unexpected_minus_restored_total 42
telemt_user_connections_total{user="hello"} 222779
telemt_user_connections_current{user="hello"} 711
telemt_user_octets_from_client{user="hello"} 4836118760 (4.50 GB)
telemt_user_octets_to_client{user="hello"} 69111745604 (64.37 GB)
telemt_user_unique_ips_current{user="hello"} 189
telemt_user_unique_ips_recent_window{user="hello"} 124
```