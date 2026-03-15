# Server Metrics 2026-03-15 01:45:16 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.18

telemt_uptime_seconds 12646.8 (3h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 156889
telemt_connections_bad_total 1773
telemt_handshake_timeouts_total 528
telemt_upstream_connect_attempt_total 2648
telemt_upstream_connect_success_total 2639
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 2648
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1362
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1275
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_reconnect_attempts_total 2003
telemt_me_reconnect_success_total 1992
telemt_me_reader_eof_total 2093
telemt_me_idle_close_by_peer_total 2093
telemt_me_route_drop_no_conn_total 49047
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 137647
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 352
telemt_desync_full_logged_total 99
telemt_desync_suppressed_total 253
telemt_desync_frames_bucket_total{bucket="1_2"} 90
telemt_desync_frames_bucket_total{bucket="3_10"} 138
telemt_desync_frames_bucket_total{bucket="gt_10"} 124
telemt_pool_swap_total 12
telemt_me_writer_removed_unexpected_total 2018
telemt_me_writer_restored_same_endpoint_total 1981
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 296
telemt_me_writer_removed_unexpected_minus_restored_total 26
telemt_user_connections_total{user="hello"} 137633
telemt_user_connections_current{user="hello"} 690
telemt_user_octets_from_client{user="hello"} 1506891812 (1.40 GB)
telemt_user_octets_to_client{user="hello"} 46534408900 (43.34 GB)
telemt_user_unique_ips_current{user="hello"} 245
telemt_user_unique_ips_recent_window{user="hello"} 80
```

## server2

```
telemt 3.3.18

telemt_uptime_seconds 12647.3 (3h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 65626
telemt_connections_bad_total 11649
telemt_handshake_timeouts_total 3029
telemt_upstream_connect_attempt_total 3743
telemt_upstream_connect_success_total 3725
telemt_upstream_connect_fail_total 18
telemt_upstream_connect_attempts_per_request{bucket="1"} 3743
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2045
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1652
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 18
telemt_me_reconnect_attempts_total 2779
telemt_me_reconnect_success_total 2763
telemt_me_reader_eof_total 2879
telemt_me_idle_close_by_peer_total 2879
telemt_me_route_drop_no_conn_total 12667
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 49109
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 16
telemt_me_endpoint_quarantine_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 108
telemt_desync_full_logged_total 25
telemt_desync_suppressed_total 83
telemt_desync_frames_bucket_total{bucket="1_2"} 45
telemt_desync_frames_bucket_total{bucket="3_10"} 32
telemt_desync_frames_bucket_total{bucket="gt_10"} 31
telemt_pool_swap_total 13
telemt_me_writer_removed_unexpected_total 2737
telemt_me_writer_restored_same_endpoint_total 2755
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 61
telemt_user_connections_total{user="hello"} 49405
telemt_user_connections_current{user="hello"} 191
telemt_user_octets_from_client{user="hello"} 1494874103 (1.39 GB)
telemt_user_octets_to_client{user="hello"} 12996754784 (12.10 GB)
telemt_user_msgs_from_client{user="hello"} 620
telemt_user_msgs_to_client{user="hello"} 1332
telemt_user_unique_ips_current{user="hello"} 79
telemt_user_unique_ips_recent_window{user="hello"} 35
```

## server3

```
telemt 3.3.18

telemt_uptime_seconds 12647.6 (3h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 105182
telemt_connections_bad_total 2198
telemt_handshake_timeouts_total 8745
telemt_upstream_connect_attempt_total 2898
telemt_upstream_connect_success_total 2884
telemt_upstream_connect_fail_total 14
telemt_upstream_connect_attempts_per_request{bucket="1"} 2898
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1556
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1318
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 14
telemt_me_reconnect_attempts_total 2243
telemt_me_reconnect_success_total 2235
telemt_me_reader_eof_total 2346
telemt_me_idle_close_by_peer_total 2346
telemt_me_route_drop_no_conn_total 23415
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 92330
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 214
telemt_desync_full_logged_total 101
telemt_desync_suppressed_total 113
telemt_desync_frames_bucket_total{bucket="1_2"} 40
telemt_desync_frames_bucket_total{bucket="3_10"} 81
telemt_desync_frames_bucket_total{bucket="gt_10"} 93
telemt_pool_swap_total 13
telemt_me_writer_removed_unexpected_total 2258
telemt_me_writer_restored_same_endpoint_total 2216
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 242
telemt_me_writer_removed_unexpected_minus_restored_total 23
telemt_user_connections_total{user="hello"} 92246
telemt_user_connections_current{user="hello"} 358
telemt_user_octets_from_client{user="hello"} 903134860 (861.30 MB)
telemt_user_octets_to_client{user="hello"} 31737874784 (29.56 GB)
telemt_user_unique_ips_current{user="hello"} 134
telemt_user_unique_ips_recent_window{user="hello"} 46
```

## server4

```
telemt 3.3.18

telemt_uptime_seconds 12647.4 (3h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 94064
telemt_connections_bad_total 25713
telemt_handshake_timeouts_total 2570
telemt_upstream_connect_attempt_total 4790
telemt_upstream_connect_success_total 4683
telemt_upstream_connect_fail_total 106
telemt_upstream_connect_attempts_per_request{bucket="1"} 4789
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2208
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2473
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 106
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 6401
telemt_me_reconnect_success_total 4038
telemt_me_reader_eof_total 4195
telemt_me_idle_close_by_peer_total 4195
telemt_me_seq_mismatch_total 6
telemt_me_route_drop_no_conn_total 17248
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 64259
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 110
telemt_desync_full_logged_total 28
telemt_desync_suppressed_total 82
telemt_desync_frames_bucket_total{bucket="1_2"} 48
telemt_desync_frames_bucket_total{bucket="3_10"} 43
telemt_desync_frames_bucket_total{bucket="gt_10"} 19
telemt_pool_swap_total 3
telemt_me_writer_removed_unexpected_total 4147
telemt_me_refill_failed_total 73
telemt_me_writer_restored_same_endpoint_total 4020
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 96
telemt_me_writer_removed_unexpected_minus_restored_total 109
telemt_user_connections_total{user="hello"} 64261
telemt_user_connections_current{user="hello"} 206
telemt_user_octets_from_client{user="hello"} 381419300 (363.75 MB)
telemt_user_octets_to_client{user="hello"} 12102397732 (11.27 GB)
telemt_user_unique_ips_current{user="hello"} 92
telemt_user_unique_ips_recent_window{user="hello"} 36
```

## server5

```
telemt 3.3.18

telemt_uptime_seconds 12648.3 (3h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 54903
telemt_connections_bad_total 63
telemt_handshake_timeouts_total 698
telemt_upstream_connect_attempt_total 2808
telemt_upstream_connect_success_total 2794
telemt_upstream_connect_fail_total 13
telemt_upstream_connect_attempts_per_request{bucket="1"} 2807
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1135
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1655
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 13
telemt_me_reconnect_attempts_total 2156
telemt_me_reconnect_success_total 2147
telemt_me_reader_eof_total 2260
telemt_me_idle_close_by_peer_total 2260
telemt_me_route_drop_no_conn_total 13643
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 52640
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 200
telemt_desync_full_logged_total 56
telemt_desync_suppressed_total 144
telemt_desync_frames_bucket_total{bucket="1_2"} 64
telemt_desync_frames_bucket_total{bucket="3_10"} 85
telemt_desync_frames_bucket_total{bucket="gt_10"} 51
telemt_pool_swap_total 13
telemt_me_writer_removed_unexpected_total 2165
telemt_me_writer_restored_same_endpoint_total 2139
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 54
telemt_me_writer_removed_unexpected_minus_restored_total 18
telemt_user_connections_total{user="hello"} 52640
telemt_user_connections_current{user="hello"} 235
telemt_user_octets_from_client{user="hello"} 491554104 (468.78 MB)
telemt_user_octets_to_client{user="hello"} 19082835068 (17.77 GB)
telemt_user_unique_ips_current{user="hello"} 93
telemt_user_unique_ips_recent_window{user="hello"} 24
```