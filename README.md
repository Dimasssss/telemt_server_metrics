# Server Metrics 2026-03-12 00:58:46 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 11626.9 (3h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 97063
telemt_connections_bad_total 1339
telemt_handshake_timeouts_total 263
telemt_upstream_connect_attempt_total 2705
telemt_upstream_connect_success_total 2705
telemt_upstream_connect_attempts_per_request{bucket="1"} 2705
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1408
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1288
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_me_keepalive_timeout_total 50
telemt_me_reconnect_attempts_total 2118
telemt_me_reconnect_success_total 2111
telemt_me_reader_eof_total 2216
telemt_me_idle_close_by_peer_total 2216
telemt_me_route_drop_no_conn_total 35740
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 92074
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 199
telemt_desync_full_logged_total 61
telemt_desync_suppressed_total 138
telemt_desync_frames_bucket_total{bucket="1_2"} 84
telemt_desync_frames_bucket_total{bucket="3_10"} 59
telemt_desync_frames_bucket_total{bucket="gt_10"} 56
telemt_pool_swap_total 10
telemt_me_writer_removed_unexpected_total 2138
telemt_me_writer_restored_same_endpoint_total 2095
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 186
telemt_me_writer_removed_unexpected_minus_restored_total 27
telemt_user_connections_total{user="hello"} 91977
telemt_user_connections_current{user="hello"} 400
telemt_user_octets_from_client{user="hello"} 654182608 (623.88 MB)
telemt_user_octets_to_client{user="hello"} 27336224744 (25.46 GB)
telemt_user_unique_ips_current{user="hello"} 162
telemt_user_unique_ips_recent_window{user="hello"} 49
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 11627.6 (3h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 33416
telemt_connections_bad_total 96
telemt_handshake_timeouts_total 390
telemt_upstream_connect_attempt_total 3465
telemt_upstream_connect_success_total 3462
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 3465
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1747
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1707
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_keepalive_timeout_total 63
telemt_me_reconnect_attempts_total 2693
telemt_me_reconnect_success_total 2671
telemt_me_reader_eof_total 2815
telemt_me_idle_close_by_peer_total 2815
telemt_me_route_drop_no_conn_total 9177
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 31599
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 38
telemt_desync_full_logged_total 22
telemt_desync_suppressed_total 16
telemt_desync_frames_bucket_total{bucket="1_2"} 29
telemt_desync_frames_bucket_total{bucket="3_10"} 8
telemt_desync_frames_bucket_total{bucket="gt_10"} 1
telemt_pool_swap_total 11
telemt_me_writer_removed_unexpected_total 2689
telemt_me_writer_restored_same_endpoint_total 2662
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 18
telemt_user_connections_total{user="hello"} 31778
telemt_user_connections_current{user="hello"} 168
telemt_user_octets_from_client{user="hello"} 604527967 (576.52 MB)
telemt_user_octets_to_client{user="hello"} 11273437646 (10.50 GB)
telemt_user_msgs_from_client{user="hello"} 353
telemt_user_msgs_to_client{user="hello"} 423
telemt_user_unique_ips_current{user="hello"} 59
telemt_user_unique_ips_recent_window{user="hello"} 22
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 11627.3 (3h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 105960
telemt_connections_bad_total 815
telemt_handshake_timeouts_total 9126
telemt_upstream_connect_attempt_total 3800
telemt_upstream_connect_success_total 3798
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 3800
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2209
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1567
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 18
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_timeout_total 56
telemt_me_reconnect_attempts_total 2886
telemt_me_reconnect_success_total 2838
telemt_me_reader_eof_total 2890
telemt_me_idle_close_by_peer_total 2890
telemt_me_route_drop_no_conn_total 17799
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 55786
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 94
telemt_desync_full_logged_total 26
telemt_desync_suppressed_total 68
telemt_desync_frames_bucket_total{bucket="1_2"} 11
telemt_desync_frames_bucket_total{bucket="3_10"} 37
telemt_desync_frames_bucket_total{bucket="gt_10"} 46
telemt_pool_swap_total 10
telemt_me_writer_removed_unexpected_total 2777
telemt_me_refill_failed_total 1
telemt_me_writer_restored_same_endpoint_total 2797
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_user_connections_total{user="hello"} 56130
telemt_user_connections_current{user="hello"} 194
telemt_user_octets_from_client{user="hello"} 580149340 (553.27 MB)
telemt_user_octets_to_client{user="hello"} 22469759989 (20.93 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 85
telemt_user_unique_ips_recent_window{user="hello"} 33
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 11627.6 (3h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 52526
telemt_connections_bad_total 122
telemt_handshake_timeouts_total 854
telemt_upstream_connect_attempt_total 3494
telemt_upstream_connect_success_total 3478
telemt_upstream_connect_fail_total 16
telemt_upstream_connect_attempts_per_request{bucket="1"} 3494
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1989
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1487
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 16
telemt_me_keepalive_timeout_total 39
telemt_me_reconnect_attempts_total 2888
telemt_me_reconnect_success_total 2878
telemt_me_reader_eof_total 3020
telemt_me_idle_close_by_peer_total 3020
telemt_me_route_drop_no_conn_total 17660
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 50829
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 91
telemt_desync_full_logged_total 31
telemt_desync_suppressed_total 60
telemt_desync_frames_bucket_total{bucket="1_2"} 23
telemt_desync_frames_bucket_total{bucket="3_10"} 34
telemt_desync_frames_bucket_total{bucket="gt_10"} 34
telemt_pool_swap_total 9
telemt_me_writer_removed_unexpected_total 2896
telemt_me_writer_restored_same_endpoint_total 2857
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 108
telemt_me_writer_removed_unexpected_minus_restored_total 18
telemt_user_connections_total{user="hello"} 50825
telemt_user_connections_current{user="hello"} 149
telemt_user_octets_from_client{user="hello"} 261670200 (249.55 MB)
telemt_user_octets_to_client{user="hello"} 12469121788 (11.61 GB)
telemt_user_unique_ips_current{user="hello"} 60
telemt_user_unique_ips_recent_window{user="hello"} 20
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 11627.4 (3h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 66740
telemt_connections_bad_total 52
telemt_handshake_timeouts_total 546
telemt_upstream_connect_attempt_total 4817
telemt_upstream_connect_success_total 4779
telemt_upstream_connect_fail_total 38
telemt_upstream_connect_attempts_per_request{bucket="1"} 4817
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2371
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2378
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 29
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 38
telemt_me_keepalive_timeout_total 73
telemt_me_reconnect_attempts_total 5659
telemt_me_reconnect_success_total 4168
telemt_me_reader_eof_total 4301
telemt_me_idle_close_by_peer_total 4301
telemt_me_seq_mismatch_total 5
telemt_me_route_drop_no_conn_total 16191
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 62833
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 9
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 157
telemt_desync_full_logged_total 56
telemt_desync_suppressed_total 101
telemt_desync_frames_bucket_total{bucket="1_2"} 38
telemt_desync_frames_bucket_total{bucket="3_10"} 74
telemt_desync_frames_bucket_total{bucket="gt_10"} 45
telemt_pool_swap_total 4
telemt_me_writer_removed_unexpected_total 4238
telemt_me_refill_failed_total 46
telemt_me_writer_restored_same_endpoint_total 4160
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 70
telemt_user_connections_total{user="hello"} 62815
telemt_user_connections_current{user="hello"} 221
telemt_user_octets_from_client{user="hello"} 298412100 (284.59 MB)
telemt_user_octets_to_client{user="hello"} 14634648704 (13.63 GB)
telemt_user_unique_ips_current{user="hello"} 83
telemt_user_unique_ips_recent_window{user="hello"} 32
```