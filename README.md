# Server Metrics 2026-03-10 18:29:25 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 14540.7 (4h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 478743
telemt_connections_bad_total 7985
telemt_handshake_timeouts_total 2325
telemt_upstream_connect_attempt_total 2936
telemt_upstream_connect_success_total 2927
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 2936
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1409
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1475
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 42
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 285
telemt_me_reconnect_attempts_total 11481
telemt_me_reconnect_success_total 2112
telemt_me_reader_eof_total 2384
telemt_me_idle_close_by_peer_total 2384
telemt_me_route_drop_no_conn_total 201857
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 451365
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2309
telemt_desync_full_logged_total 625
telemt_desync_suppressed_total 1684
telemt_desync_frames_bucket_total{bucket="1_2"} 622
telemt_desync_frames_bucket_total{bucket="3_10"} 887
telemt_desync_frames_bucket_total{bucket="gt_10"} 800
telemt_pool_swap_total 2
telemt_me_writer_removed_unexpected_total 2412
telemt_me_refill_failed_total 292
telemt_me_writer_restored_same_endpoint_total 2106
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 300
telemt_user_connections_total{user="hello"} 451283
telemt_user_connections_current{user="hello"} 1276
telemt_user_octets_from_client{user="hello"} 5979327268 (5.57 GB)
telemt_user_octets_to_client{user="hello"} 131021227816 (122.02 GB)
telemt_user_unique_ips_current{user="hello"} 326
telemt_user_unique_ips_recent_window{user="hello"} 149
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 14597.4 (4h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 201671
telemt_connections_bad_total 1806
telemt_handshake_timeouts_total 13007
telemt_upstream_connect_attempt_total 6708
telemt_upstream_connect_success_total 4650
telemt_upstream_connect_fail_total 2057
telemt_upstream_connect_attempts_per_request{bucket="1"} 6707
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1636
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1586
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 111
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1317
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2057
telemt_me_keepalive_timeout_total 108
telemt_me_reconnect_attempts_total 2551
telemt_me_reconnect_success_total 2502
telemt_me_reader_eof_total 2607
telemt_me_idle_close_by_peer_total 2605
telemt_me_route_drop_no_conn_total 81131
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 171734
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 705
telemt_desync_full_logged_total 218
telemt_desync_suppressed_total 487
telemt_desync_frames_bucket_total{bucket="1_2"} 256
telemt_desync_frames_bucket_total{bucket="3_10"} 239
telemt_desync_frames_bucket_total{bucket="gt_10"} 210
telemt_pool_swap_total 10
telemt_me_writer_removed_unexpected_total 2526
telemt_me_writer_restored_same_endpoint_total 2481
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 86
telemt_me_writer_removed_unexpected_minus_restored_total 24
telemt_user_connections_total{user="hello"} 173094
telemt_user_connections_current{user="hello"} 276
telemt_user_octets_from_client{user="hello"} 1945067728 (1.81 GB)
telemt_user_octets_to_client{user="hello"} 42113526303 (39.22 GB)
telemt_user_msgs_from_client{user="hello"} 4339
telemt_user_msgs_to_client{user="hello"} 3434
telemt_user_unique_ips_current{user="hello"} 104
telemt_user_unique_ips_recent_window{user="hello"} 129
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 14597.2 (4h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 350718
telemt_connections_bad_total 1071
telemt_handshake_timeouts_total 31774
telemt_upstream_connect_attempt_total 4766
telemt_upstream_connect_success_total 4690
telemt_upstream_connect_fail_total 76
telemt_upstream_connect_attempts_per_request{bucket="1"} 4766
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2831
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1831
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 28
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 76
telemt_me_keepalive_timeout_total 95
telemt_me_reconnect_attempts_total 4495
telemt_me_reconnect_success_total 2842
telemt_me_reader_eof_total 2988
telemt_me_idle_close_by_peer_total 2988
telemt_me_route_drop_no_conn_total 115564
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 293902
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 916
telemt_desync_full_logged_total 262
telemt_desync_suppressed_total 654
telemt_desync_frames_bucket_total{bucket="1_2"} 228
telemt_desync_frames_bucket_total{bucket="3_10"} 311
telemt_desync_frames_bucket_total{bucket="gt_10"} 377
telemt_pool_swap_total 7
telemt_me_writer_removed_unexpected_total 2945
telemt_me_refill_failed_total 50
telemt_me_writer_restored_same_endpoint_total 2831
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 103
telemt_user_connections_total{user="hello"} 294863
telemt_user_connections_current{user="hello"} 781
telemt_user_octets_from_client{user="hello"} 4151773865 (3.87 GB)
telemt_user_octets_to_client{user="hello"} 93302247329 (86.89 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 210
telemt_user_unique_ips_recent_window{user="hello"} 128
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 14597.9 (4h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 227447
telemt_connections_bad_total 14275
telemt_handshake_timeouts_total 20727
telemt_upstream_connect_attempt_total 3738
telemt_upstream_connect_success_total 3737
telemt_upstream_connect_attempts_per_request{bucket="1"} 3737
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1998
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1738
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 66
telemt_me_reconnect_attempts_total 2965
telemt_me_reconnect_success_total 2946
telemt_me_reader_eof_total 3062
telemt_me_idle_close_by_peer_total 3062
telemt_me_seq_mismatch_total 1
telemt_me_route_drop_no_conn_total 74897
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 183063
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 510
telemt_desync_full_logged_total 203
telemt_desync_suppressed_total 307
telemt_desync_frames_bucket_total{bucket="1_2"} 169
telemt_desync_frames_bucket_total{bucket="3_10"} 185
telemt_desync_frames_bucket_total{bucket="gt_10"} 156
telemt_pool_swap_total 10
telemt_me_writer_removed_unexpected_total 2973
telemt_me_writer_restored_same_endpoint_total 2934
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 27
telemt_user_connections_total{user="hello"} 182857
telemt_user_connections_current{user="hello"} 484
telemt_user_octets_from_client{user="hello"} 2755713552 (2.57 GB)
telemt_user_octets_to_client{user="hello"} 51093402296 (47.58 GB)
telemt_user_unique_ips_current{user="hello"} 139
telemt_user_unique_ips_recent_window{user="hello"} 81
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 14597.6 (4h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 240787
telemt_connections_bad_total 799
telemt_handshake_timeouts_total 1746
telemt_upstream_connect_attempt_total 4475
telemt_upstream_connect_success_total 4460
telemt_upstream_connect_fail_total 15
telemt_upstream_connect_attempts_per_request{bucket="1"} 4475
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2299
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2111
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 49
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 15
telemt_me_keepalive_timeout_total 91
telemt_me_reconnect_attempts_total 3678
telemt_me_reconnect_success_total 3649
telemt_me_reader_eof_total 3760
telemt_me_idle_close_by_peer_total 3760
telemt_me_route_drop_no_conn_total 89086
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 226854
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 1242
telemt_desync_full_logged_total 441
telemt_desync_suppressed_total 801
telemt_desync_frames_bucket_total{bucket="1_2"} 513
telemt_desync_frames_bucket_total{bucket="3_10"} 514
telemt_desync_frames_bucket_total{bucket="gt_10"} 215
telemt_pool_swap_total 5
telemt_me_writer_removed_unexpected_total 3693
telemt_me_writer_restored_same_endpoint_total 3649
telemt_me_async_recovery_trigger_total 48
telemt_me_writer_removed_unexpected_minus_restored_total 44
telemt_user_connections_total{user="hello"} 226789
telemt_user_connections_current{user="hello"} 721
telemt_user_octets_from_client{user="hello"} 4874994372 (4.54 GB)
telemt_user_octets_to_client{user="hello"} 71139565572 (66.25 GB)
telemt_user_unique_ips_current{user="hello"} 184
telemt_user_unique_ips_recent_window{user="hello"} 97
```