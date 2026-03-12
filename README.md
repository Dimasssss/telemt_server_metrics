# Server Metrics 2026-03-12 11:31:12 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 19952.2 (5h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 676232
telemt_connections_bad_total 1492
telemt_handshake_timeouts_total 3889
telemt_upstream_connect_attempt_total 3797
telemt_upstream_connect_success_total 3771
telemt_upstream_connect_fail_total 26
telemt_upstream_connect_attempts_per_request{bucket="1"} 3797
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2085
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1683
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 26
telemt_me_keepalive_timeout_total 314
telemt_me_reconnect_attempts_total 6611
telemt_me_reconnect_success_total 2721
telemt_me_reader_eof_total 2940
telemt_me_idle_close_by_peer_total 2940
telemt_me_route_drop_no_conn_total 235314
telemt_me_route_drop_channel_closed_total 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 651920
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3236
telemt_desync_full_logged_total 820
telemt_desync_suppressed_total 2416
telemt_desync_frames_bucket_total{bucket="1_2"} 825
telemt_desync_frames_bucket_total{bucket="3_10"} 1188
telemt_desync_frames_bucket_total{bucket="gt_10"} 1223
telemt_pool_swap_total 14
telemt_me_writer_removed_unexpected_total 2869
telemt_me_refill_failed_total 121
telemt_me_writer_restored_same_endpoint_total 2708
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 148
telemt_user_connections_total{user="hello"} 651773
telemt_user_connections_current{user="hello"} 1330
telemt_user_octets_from_client{user="hello"} 11512807364 (10.72 GB)
telemt_user_octets_to_client{user="hello"} 180857877528 (168.44 GB)
telemt_user_unique_ips_current{user="hello"} 391
telemt_user_unique_ips_recent_window{user="hello"} 209
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 49572.7 (13h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 355065
telemt_connections_bad_total 4097
telemt_handshake_timeouts_total 13889
telemt_upstream_connect_attempt_total 12237
telemt_upstream_connect_success_total 12231
telemt_upstream_connect_fail_total 6
telemt_upstream_connect_attempts_per_request{bucket="1"} 12237
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6010
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6206
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 15
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 6
telemt_me_keepalive_timeout_total 820
telemt_me_reconnect_attempts_total 9612
telemt_me_reconnect_success_total 9558
telemt_me_reader_eof_total 10158
telemt_me_idle_close_by_peer_total 10158
telemt_me_route_drop_no_conn_total 101501
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 316441
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 821
telemt_desync_full_logged_total 292
telemt_desync_suppressed_total 529
telemt_desync_frames_bucket_total{bucket="1_2"} 294
telemt_desync_frames_bucket_total{bucket="3_10"} 283
telemt_desync_frames_bucket_total{bucket="gt_10"} 244
telemt_pool_swap_total 51
telemt_me_writer_removed_unexpected_total 9642
telemt_me_writer_restored_same_endpoint_total 9549
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 84
telemt_user_connections_total{user="hello"} 316912
telemt_user_connections_current{user="hello"} 620
telemt_user_octets_from_client{user="hello"} 4332602935 (4.04 GB)
telemt_user_octets_to_client{user="hello"} 111945595070 (104.26 GB)
telemt_user_msgs_from_client{user="hello"} 353
telemt_user_msgs_to_client{user="hello"} 423
telemt_user_unique_ips_current{user="hello"} 152
telemt_user_unique_ips_recent_window{user="hello"} 76
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 49572.7 (13h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 834387
telemt_connections_bad_total 4183
telemt_handshake_timeouts_total 61638
telemt_upstream_connect_attempt_total 12215
telemt_upstream_connect_success_total 12210
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 12215
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6714
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5442
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 50
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 701
telemt_me_reconnect_attempts_total 9457
telemt_me_reconnect_success_total 9378
telemt_me_reader_eof_total 9864
telemt_me_idle_close_by_peer_total 9864
telemt_me_route_drop_no_conn_total 196407
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 553639
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2506
telemt_desync_full_logged_total 741
telemt_desync_suppressed_total 1765
telemt_desync_frames_bucket_total{bucket="1_2"} 318
telemt_desync_frames_bucket_total{bucket="3_10"} 877
telemt_desync_frames_bucket_total{bucket="gt_10"} 1311
telemt_pool_swap_total 49
telemt_me_writer_removed_unexpected_total 9398
telemt_me_refill_failed_total 1
telemt_me_writer_restored_same_endpoint_total 9337
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 20
telemt_user_connections_total{user="hello"} 553884
telemt_user_connections_current{user="hello"} 898
telemt_user_octets_from_client{user="hello"} 7493490096 (6.98 GB)
telemt_user_octets_to_client{user="hello"} 176071140945 (163.98 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 260
telemt_user_unique_ips_recent_window{user="hello"} 139
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 49573.0 (13h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 448921
telemt_connections_bad_total 2492
telemt_handshake_timeouts_total 40714
telemt_upstream_connect_attempt_total 13213
telemt_upstream_connect_success_total 13161
telemt_upstream_connect_fail_total 52
telemt_upstream_connect_attempts_per_request{bucket="1"} 13213
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7481
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5671
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 52
telemt_me_keepalive_timeout_total 990
telemt_me_reconnect_attempts_total 10721
telemt_me_reconnect_success_total 10678
telemt_me_reader_eof_total 11320
telemt_me_idle_close_by_peer_total 11320
telemt_me_route_drop_no_conn_total 148944
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 375762
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 759
telemt_desync_full_logged_total 267
telemt_desync_suppressed_total 492
telemt_desync_frames_bucket_total{bucket="1_2"} 231
telemt_desync_frames_bucket_total{bucket="3_10"} 318
telemt_desync_frames_bucket_total{bucket="gt_10"} 210
telemt_pool_swap_total 47
telemt_me_writer_removed_unexpected_total 10755
telemt_me_writer_restored_same_endpoint_total 10657
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 108
telemt_me_writer_removed_unexpected_minus_restored_total 77
telemt_user_connections_total{user="hello"} 375587
telemt_user_connections_current{user="hello"} 618
telemt_user_octets_from_client{user="hello"} 4334805732 (4.04 GB)
telemt_user_octets_to_client{user="hello"} 141377639600 (131.67 GB)
telemt_user_unique_ips_current{user="hello"} 183
telemt_user_unique_ips_recent_window{user="hello"} 101
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 49572.8 (13h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 509729
telemt_connections_bad_total 1665
telemt_handshake_timeouts_total 3891
telemt_upstream_connect_attempt_total 16083
telemt_upstream_connect_success_total 15893
telemt_upstream_connect_fail_total 190
telemt_upstream_connect_attempts_per_request{bucket="1"} 16083
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8213
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7593
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 81
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 190
telemt_me_keepalive_timeout_total 772
telemt_me_reconnect_attempts_total 14935
telemt_me_reconnect_success_total 13410
telemt_me_reader_eof_total 13928
telemt_me_idle_close_by_peer_total 13928
telemt_me_seq_mismatch_total 21
telemt_me_route_drop_no_conn_total 166633
telemt_me_route_drop_channel_closed_total 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 477332
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 25
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 1991
telemt_desync_full_logged_total 660
telemt_desync_suppressed_total 1331
telemt_desync_frames_bucket_total{bucket="1_2"} 591
telemt_desync_frames_bucket_total{bucket="3_10"} 695
telemt_desync_frames_bucket_total{bucket="gt_10"} 705
telemt_pool_swap_total 26
telemt_me_writer_removed_unexpected_total 13588
telemt_me_refill_failed_total 46
telemt_me_writer_restored_same_endpoint_total 13384
telemt_me_writer_restored_fallback_total 26
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 178
telemt_user_connections_total{user="hello"} 477257
telemt_user_connections_current{user="hello"} 761
telemt_user_octets_from_client{user="hello"} 5395334604 (5.02 GB)
telemt_user_octets_to_client{user="hello"} 116844174864 (108.82 GB)
telemt_user_unique_ips_current{user="hello"} 213
telemt_user_unique_ips_recent_window{user="hello"} 109
```