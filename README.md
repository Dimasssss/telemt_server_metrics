# Server Metrics 2026-03-15 02:46:25 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.18

telemt_uptime_seconds 16316.5 (4h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 198194
telemt_connections_bad_total 2659
telemt_handshake_timeouts_total 611
telemt_upstream_connect_attempt_total 3468
telemt_upstream_connect_success_total 3456
telemt_upstream_connect_fail_total 12
telemt_upstream_connect_attempts_per_request{bucket="1"} 3468
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1801
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1652
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 12
telemt_me_reconnect_attempts_total 2618
telemt_me_reconnect_success_total 2605
telemt_me_reader_eof_total 2745
telemt_me_idle_close_by_peer_total 2745
telemt_me_route_drop_no_conn_total 61445
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 174998
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 477
telemt_desync_full_logged_total 134
telemt_desync_suppressed_total 343
telemt_desync_frames_bucket_total{bucket="1_2"} 106
telemt_desync_frames_bucket_total{bucket="3_10"} 189
telemt_desync_frames_bucket_total{bucket="gt_10"} 182
telemt_pool_swap_total 17
telemt_me_writer_removed_unexpected_total 2634
telemt_me_writer_restored_same_endpoint_total 2594
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 296
telemt_me_writer_removed_unexpected_minus_restored_total 29
telemt_user_connections_total{user="hello"} 174978
telemt_user_connections_current{user="hello"} 680
telemt_user_octets_from_client{user="hello"} 1912481300 (1.78 GB)
telemt_user_octets_to_client{user="hello"} 62659928916 (58.36 GB)
telemt_user_unique_ips_current{user="hello"} 248
telemt_user_unique_ips_recent_window{user="hello"} 81
```

## server2

```
telemt 3.3.18

telemt_uptime_seconds 16317.1 (4h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 81963
telemt_connections_bad_total 14301
telemt_handshake_timeouts_total 3670
telemt_upstream_connect_attempt_total 4827
telemt_upstream_connect_success_total 4805
telemt_upstream_connect_fail_total 22
telemt_upstream_connect_attempts_per_request{bucket="1"} 4827
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2598
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2173
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 27
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 22
telemt_me_reconnect_attempts_total 3662
telemt_me_reconnect_success_total 3642
telemt_me_reader_eof_total 3820
telemt_me_idle_close_by_peer_total 3820
telemt_me_route_drop_no_conn_total 15759
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 61919
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
telemt_pool_swap_total 18
telemt_me_writer_removed_unexpected_total 3624
telemt_me_writer_restored_same_endpoint_total 3634
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 61
telemt_user_connections_total{user="hello"} 62215
telemt_user_connections_current{user="hello"} 198
telemt_user_octets_from_client{user="hello"} 1577673539 (1.47 GB)
telemt_user_octets_to_client{user="hello"} 18831700700 (17.54 GB)
telemt_user_msgs_from_client{user="hello"} 620
telemt_user_msgs_to_client{user="hello"} 1332
telemt_user_unique_ips_current{user="hello"} 78
telemt_user_unique_ips_recent_window{user="hello"} 32
```

## server3

```
telemt 3.3.18

telemt_uptime_seconds 16317.4 (4h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 136233
telemt_connections_bad_total 2823
telemt_handshake_timeouts_total 12778
telemt_upstream_connect_attempt_total 3834
telemt_upstream_connect_success_total 3816
telemt_upstream_connect_fail_total 18
telemt_upstream_connect_attempts_per_request{bucket="1"} 3834
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2014
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1789
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 13
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 18
telemt_me_reconnect_attempts_total 2975
telemt_me_reconnect_success_total 2964
telemt_me_reader_eof_total 3127
telemt_me_idle_close_by_peer_total 3127
telemt_me_route_drop_no_conn_total 29296
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 117970
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 258
telemt_desync_full_logged_total 134
telemt_desync_suppressed_total 124
telemt_desync_frames_bucket_total{bucket="1_2"} 51
telemt_desync_frames_bucket_total{bucket="3_10"} 97
telemt_desync_frames_bucket_total{bucket="gt_10"} 110
telemt_pool_swap_total 18
telemt_me_writer_removed_unexpected_total 2994
telemt_me_writer_restored_same_endpoint_total 2945
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 242
telemt_me_writer_removed_unexpected_minus_restored_total 30
telemt_user_connections_total{user="hello"} 117880
telemt_user_connections_current{user="hello"} 321
telemt_user_octets_from_client{user="hello"} 1077576028 (1.00 GB)
telemt_user_octets_to_client{user="hello"} 37579458772 (35.00 GB)
telemt_user_unique_ips_current{user="hello"} 141
telemt_user_unique_ips_recent_window{user="hello"} 55
```

## server4

```
telemt 3.3.18

telemt_uptime_seconds 16317.1 (4h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 113126
telemt_connections_bad_total 28533
telemt_handshake_timeouts_total 2890
telemt_upstream_connect_attempt_total 5957
telemt_upstream_connect_success_total 5829
telemt_upstream_connect_fail_total 128
telemt_upstream_connect_attempts_per_request{bucket="1"} 5957
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2796
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3031
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 128
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 8523
telemt_me_reconnect_success_total 4973
telemt_me_reader_eof_total 5231
telemt_me_idle_close_by_peer_total 5231
telemt_me_seq_mismatch_total 7
telemt_me_route_drop_no_conn_total 21753
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 79979
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 132
telemt_desync_full_logged_total 32
telemt_desync_suppressed_total 100
telemt_desync_frames_bucket_total{bucket="1_2"} 56
telemt_desync_frames_bucket_total{bucket="3_10"} 53
telemt_desync_frames_bucket_total{bucket="gt_10"} 23
telemt_pool_swap_total 7
telemt_me_writer_removed_unexpected_total 5126
telemt_me_refill_failed_total 110
telemt_me_writer_restored_same_endpoint_total 4954
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 96
telemt_me_writer_removed_unexpected_minus_restored_total 153
telemt_user_connections_total{user="hello"} 79990
telemt_user_connections_current{user="hello"} 268
telemt_user_octets_from_client{user="hello"} 469288408 (447.55 MB)
telemt_user_octets_to_client{user="hello"} 20363917976 (18.97 GB)
telemt_user_unique_ips_current{user="hello"} 93
telemt_user_unique_ips_recent_window{user="hello"} 49
```

## server5

```
telemt 3.3.18

telemt_uptime_seconds 16317.9 (4h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 67881
telemt_connections_bad_total 132
telemt_handshake_timeouts_total 762
telemt_upstream_connect_attempt_total 3743
telemt_upstream_connect_success_total 3726
telemt_upstream_connect_fail_total 17
telemt_upstream_connect_attempts_per_request{bucket="1"} 3743
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1543
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2179
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17
telemt_me_reconnect_attempts_total 2883
telemt_me_reconnect_success_total 2871
telemt_me_reader_eof_total 3049
telemt_me_idle_close_by_peer_total 3049
telemt_me_route_drop_no_conn_total 17459
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 65045
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 225
telemt_desync_full_logged_total 63
telemt_desync_suppressed_total 162
telemt_desync_frames_bucket_total{bucket="1_2"} 76
telemt_desync_frames_bucket_total{bucket="3_10"} 90
telemt_desync_frames_bucket_total{bucket="gt_10"} 59
telemt_pool_swap_total 18
telemt_me_writer_removed_unexpected_total 2896
telemt_me_writer_restored_same_endpoint_total 2863
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 54
telemt_me_writer_removed_unexpected_minus_restored_total 25
telemt_user_connections_total{user="hello"} 65044
telemt_user_connections_current{user="hello"} 268
telemt_user_octets_from_client{user="hello"} 569732888 (543.34 MB)
telemt_user_octets_to_client{user="hello"} 21319795956 (19.86 GB)
telemt_user_unique_ips_current{user="hello"} 100
telemt_user_unique_ips_recent_window{user="hello"} 39
```