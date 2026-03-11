# Server Metrics 2026-03-11 22:35:57 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 3058.3 (0h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 32217
telemt_connections_bad_total 2
telemt_handshake_timeouts_total 137
telemt_upstream_connect_attempt_total 650
telemt_upstream_connect_success_total 650
telemt_upstream_connect_attempts_per_request{bucket="1"} 650
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 359
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 290
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 6
telemt_me_reconnect_attempts_total 452
telemt_me_reconnect_success_total 451
telemt_me_reader_eof_total 444
telemt_me_idle_close_by_peer_total 444
telemt_me_route_drop_no_conn_total 10719
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 29707
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 88
telemt_desync_full_logged_total 23
telemt_desync_suppressed_total 65
telemt_desync_frames_bucket_total{bucket="1_2"} 44
telemt_desync_frames_bucket_total{bucket="3_10"} 23
telemt_desync_frames_bucket_total{bucket="gt_10"} 21
telemt_pool_swap_total 2
telemt_me_writer_removed_unexpected_total 457
telemt_me_writer_restored_same_endpoint_total 435
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 186
telemt_me_writer_removed_unexpected_minus_restored_total 6
telemt_user_connections_total{user="hello"} 29699
telemt_user_connections_current{user="hello"} 466
telemt_user_octets_from_client{user="hello"} 194099700 (185.11 MB)
telemt_user_octets_to_client{user="hello"} 8619319420 (8.03 GB)
telemt_user_unique_ips_current{user="hello"} 175
telemt_user_unique_ips_recent_window{user="hello"} 45
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 3059.1 (0h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11782
telemt_connections_bad_total 4
telemt_handshake_timeouts_total 83
telemt_upstream_connect_attempt_total 949
telemt_upstream_connect_success_total 949
telemt_upstream_connect_attempts_per_request{bucket="1"} 949
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 469
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 480
telemt_me_keepalive_timeout_total 8
telemt_me_reconnect_attempts_total 747
telemt_me_reconnect_success_total 740
telemt_me_reader_eof_total 755
telemt_me_idle_close_by_peer_total 755
telemt_me_route_drop_no_conn_total 3082
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 11228
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 16
telemt_desync_full_logged_total 9
telemt_desync_suppressed_total 7
telemt_desync_frames_bucket_total{bucket="1_2"} 14
telemt_desync_frames_bucket_total{bucket="3_10"} 2
telemt_pool_swap_total 2
telemt_me_writer_removed_unexpected_total 741
telemt_me_writer_restored_same_endpoint_total 731
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 1
telemt_user_connections_total{user="hello"} 11226
telemt_user_connections_current{user="hello"} 212
telemt_user_octets_from_client{user="hello"} 469964404 (448.19 MB)
telemt_user_octets_to_client{user="hello"} 6133251508 (5.71 GB)
telemt_user_unique_ips_current{user="hello"} 68
telemt_user_unique_ips_recent_window{user="hello"} 25
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 3058.8 (0h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 23933
telemt_connections_bad_total 279
telemt_handshake_timeouts_total 2704
telemt_upstream_connect_attempt_total 1500
telemt_upstream_connect_success_total 1500
telemt_upstream_connect_attempts_per_request{bucket="1"} 1500
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 971
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 522
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 20
telemt_me_reconnect_attempts_total 977
telemt_me_reconnect_success_total 938
telemt_me_reader_eof_total 871
telemt_me_idle_close_by_peer_total 871
telemt_me_route_drop_no_conn_total 5478
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 19591
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 31
telemt_desync_full_logged_total 7
telemt_desync_suppressed_total 24
telemt_desync_frames_bucket_total{bucket="1_2"} 7
telemt_desync_frames_bucket_total{bucket="3_10"} 10
telemt_desync_frames_bucket_total{bucket="gt_10"} 14
telemt_pool_swap_total 2
telemt_me_writer_removed_unexpected_total 853
telemt_me_refill_failed_total 1
telemt_me_writer_restored_same_endpoint_total 897
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_user_connections_total{user="hello"} 19945
telemt_user_connections_current{user="hello"} 249
telemt_user_octets_from_client{user="hello"} 159237700 (151.86 MB)
telemt_user_octets_to_client{user="hello"} 8717422449 (8.12 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 113
telemt_user_unique_ips_recent_window{user="hello"} 33
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 3059.1 (0h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 16970
telemt_connections_bad_total 57
telemt_handshake_timeouts_total 302
telemt_upstream_connect_attempt_total 1026
telemt_upstream_connect_success_total 1019
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 1026
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 663
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 356
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_keepalive_timeout_total 14
telemt_me_reconnect_attempts_total 818
telemt_me_reconnect_success_total 812
telemt_me_reader_eof_total 815
telemt_me_idle_close_by_peer_total 815
telemt_me_route_drop_no_conn_total 4643
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 16337
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 6
telemt_desync_full_logged_total 3
telemt_desync_suppressed_total 3
telemt_desync_frames_bucket_total{bucket="1_2"} 2
telemt_desync_frames_bucket_total{bucket="3_10"} 2
telemt_desync_frames_bucket_total{bucket="gt_10"} 2
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 811
telemt_me_writer_restored_same_endpoint_total 791
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 108
telemt_user_connections_total{user="hello"} 16340
telemt_user_connections_current{user="hello"} 233
telemt_user_octets_from_client{user="hello"} 104455940 (99.62 MB)
telemt_user_octets_to_client{user="hello"} 6587283396 (6.13 GB)
telemt_user_unique_ips_current{user="hello"} 81
telemt_user_unique_ips_recent_window{user="hello"} 27
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 3058.9 (0h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 20131
telemt_connections_bad_total 4
telemt_handshake_timeouts_total 252
telemt_upstream_connect_attempt_total 1037
telemt_upstream_connect_success_total 1024
telemt_upstream_connect_fail_total 13
telemt_upstream_connect_attempts_per_request{bucket="1"} 1037
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 521
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 496
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 13
telemt_me_keepalive_timeout_total 14
telemt_me_reconnect_attempts_total 824
telemt_me_reconnect_success_total 816
telemt_me_reader_eof_total 785
telemt_me_idle_close_by_peer_total 785
telemt_me_seq_mismatch_total 2
telemt_me_route_drop_no_conn_total 4830
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 19007
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 23
telemt_desync_full_logged_total 10
telemt_desync_suppressed_total 13
telemt_desync_frames_bucket_total{bucket="1_2"} 4
telemt_desync_frames_bucket_total{bucket="3_10"} 9
telemt_desync_frames_bucket_total{bucket="gt_10"} 10
telemt_me_writer_removed_unexpected_total 809
telemt_me_writer_restored_same_endpoint_total 812
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 142
telemt_user_connections_total{user="hello"} 19003
telemt_user_connections_current{user="hello"} 285
telemt_user_octets_from_client{user="hello"} 124593176 (118.82 MB)
telemt_user_octets_to_client{user="hello"} 5820065816 (5.42 GB)
telemt_user_unique_ips_current{user="hello"} 87
telemt_user_unique_ips_recent_window{user="hello"} 34
```