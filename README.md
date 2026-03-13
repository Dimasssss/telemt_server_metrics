# Server Metrics 2026-03-13 00:52:33 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 68032.5 (18h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2011696
telemt_connections_bad_total 26115
telemt_handshake_timeouts_total 21492
telemt_upstream_connect_attempt_total 13513
telemt_upstream_connect_success_total 13436
telemt_upstream_connect_fail_total 77
telemt_upstream_connect_attempts_per_request{bucket="1"} 13513
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6937
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6459
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 40
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 77
telemt_me_keepalive_timeout_total 1246
telemt_me_reconnect_attempts_total 18887
telemt_me_reconnect_success_total 10028
telemt_me_reader_eof_total 10847
telemt_me_idle_close_by_peer_total 10846
telemt_me_route_drop_no_conn_total 785447
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1871509
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8668
telemt_desync_full_logged_total 2258
telemt_desync_suppressed_total 6410
telemt_desync_frames_bucket_total{bucket="1_2"} 2288
telemt_desync_frames_bucket_total{bucket="3_10"} 3124
telemt_desync_frames_bucket_total{bucket="gt_10"} 3256
telemt_pool_swap_total 51
telemt_me_writer_removed_unexpected_total 10445
telemt_me_refill_failed_total 275
telemt_me_writer_restored_same_endpoint_total 10015
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 417
telemt_user_connections_total{user="hello"} 1870967
telemt_user_connections_current{user="hello"} 553
telemt_user_octets_from_client{user="hello"} 27557162220 (25.66 GB)
telemt_user_octets_to_client{user="hello"} 656611576820 (611.52 GB)
telemt_user_unique_ips_current{user="hello"} 205
telemt_user_unique_ips_recent_window{user="hello"} 67
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 97652.9 (27h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 828399
telemt_connections_bad_total 11755
telemt_handshake_timeouts_total 31892
telemt_upstream_connect_attempt_total 24874
telemt_upstream_connect_success_total 24845
telemt_upstream_connect_fail_total 29
telemt_upstream_connect_attempts_per_request{bucket="1"} 24874
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12955
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11801
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 89
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 29
telemt_me_keepalive_timeout_total 3439
telemt_me_reconnect_attempts_total 18428
telemt_me_reconnect_success_total 18326
telemt_me_reader_eof_total 19512
telemt_me_idle_close_by_peer_total 19512
telemt_me_route_drop_no_conn_total 268104
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 750255
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3054
telemt_desync_full_logged_total 957
telemt_desync_suppressed_total 2097
telemt_desync_frames_bucket_total{bucket="1_2"} 1235
telemt_desync_frames_bucket_total{bucket="3_10"} 991
telemt_desync_frames_bucket_total{bucket="gt_10"} 828
telemt_pool_swap_total 99
telemt_me_writer_removed_unexpected_total 18505
telemt_me_writer_restored_same_endpoint_total 18317
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 179
telemt_user_connections_total{user="hello"} 752158
telemt_user_connections_current{user="hello"} 169
telemt_user_octets_from_client{user="hello"} 12209326316 (11.37 GB)
telemt_user_octets_to_client{user="hello"} 285547356091 (265.94 GB)
telemt_user_msgs_from_client{user="hello"} 6476
telemt_user_msgs_to_client{user="hello"} 18854
telemt_user_unique_ips_current{user="hello"} 66
telemt_user_unique_ips_recent_window{user="hello"} 24
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 97653.0 (27h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1724007
telemt_connections_bad_total 8785
telemt_handshake_timeouts_total 113770
telemt_upstream_connect_attempt_total 22703
telemt_upstream_connect_success_total 22693
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 22703
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12036
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10569
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 83
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_keepalive_timeout_total 1579
telemt_me_reconnect_attempts_total 18725
telemt_me_reconnect_success_total 17463
telemt_me_reader_eof_total 18499
telemt_me_idle_close_by_peer_total 18498
telemt_me_route_drop_no_conn_total 566437
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1353727
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4994
telemt_desync_full_logged_total 1532
telemt_desync_suppressed_total 3462
telemt_desync_frames_bucket_total{bucket="1_2"} 798
telemt_desync_frames_bucket_total{bucket="3_10"} 1806
telemt_desync_frames_bucket_total{bucket="gt_10"} 2390
telemt_pool_swap_total 91
telemt_me_writer_removed_unexpected_total 17632
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 17422
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 169
telemt_user_connections_total{user="hello"} 1353327
telemt_user_connections_current{user="hello"} 255
telemt_user_octets_from_client{user="hello"} 19982004224 (18.61 GB)
telemt_user_octets_to_client{user="hello"} 492771180709 (458.93 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 111
telemt_user_unique_ips_recent_window{user="hello"} 46
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 97653.1 (27h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1081326
telemt_connections_bad_total 13050
telemt_handshake_timeouts_total 72238
telemt_upstream_connect_attempt_total 34074
telemt_upstream_connect_success_total 31810
telemt_upstream_connect_fail_total 2127
telemt_upstream_connect_attempts_per_request{bucket="1"} 33800
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19685
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12037
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 88
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2126
telemt_me_keepalive_timeout_total 11268
telemt_me_reconnect_attempts_total 28916
telemt_me_reconnect_success_total 21076
telemt_me_reader_eof_total 22813
telemt_me_idle_close_by_peer_total 22806
telemt_me_route_drop_no_conn_total 381684
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 926155
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1895
telemt_desync_full_logged_total 628
telemt_desync_suppressed_total 1267
telemt_desync_frames_bucket_total{bucket="1_2"} 522
telemt_desync_frames_bucket_total{bucket="3_10"} 743
telemt_desync_frames_bucket_total{bucket="gt_10"} 630
telemt_pool_swap_total 84
telemt_me_writer_removed_unexpected_total 21451
telemt_me_refill_failed_total 241
telemt_me_writer_restored_same_endpoint_total 21054
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 2298
telemt_me_writer_removed_unexpected_minus_restored_total 375
telemt_user_connections_total{user="hello"} 931346
telemt_user_connections_current{user="hello"} 216
telemt_user_octets_from_client{user="hello"} 14416362073 (13.43 GB)
telemt_user_octets_to_client{user="hello"} 367543461882 (342.30 GB)
telemt_user_msgs_from_client{user="hello"} 44500
telemt_user_msgs_to_client{user="hello"} 116355
telemt_user_unique_ips_current{user="hello"} 94
telemt_user_unique_ips_recent_window{user="hello"} 43
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 97653.0 (27h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1190284
telemt_connections_bad_total 12579
telemt_handshake_timeouts_total 9357
telemt_upstream_connect_attempt_total 29539
telemt_upstream_connect_success_total 29166
telemt_upstream_connect_fail_total 373
telemt_upstream_connect_attempts_per_request{bucket="1"} 29539
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14853
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14149
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 11
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 153
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 373
telemt_me_keepalive_timeout_total 1832
telemt_me_reconnect_attempts_total 35334
telemt_me_reconnect_success_total 24289
telemt_me_reader_eof_total 25569
telemt_me_idle_close_by_peer_total 25569
telemt_me_seq_mismatch_total 35
telemt_me_route_drop_no_conn_total 446282
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1098988
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 39
telemt_me_hardswap_pending_ttl_expired_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 4119
telemt_desync_full_logged_total 1453
telemt_desync_suppressed_total 2666
telemt_desync_frames_bucket_total{bucket="1_2"} 1216
telemt_desync_frames_bucket_total{bucket="3_10"} 1374
telemt_desync_frames_bucket_total{bucket="gt_10"} 1529
telemt_pool_swap_total 52
telemt_me_writer_removed_unexpected_total 24914
telemt_me_refill_failed_total 342
telemt_me_writer_restored_same_endpoint_total 24243
telemt_me_writer_restored_fallback_total 46
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 625
telemt_user_connections_total{user="hello"} 1098844
telemt_user_connections_current{user="hello"} 257
telemt_user_octets_from_client{user="hello"} 13671499892 (12.73 GB)
telemt_user_octets_to_client{user="hello"} 381496698544 (355.30 GB)
telemt_user_unique_ips_current{user="hello"} 98
telemt_user_unique_ips_recent_window{user="hello"} 46
```