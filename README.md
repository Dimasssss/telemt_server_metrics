# Server Metrics 2026-03-14 23:33:00 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.18

telemt_uptime_seconds 4711.5 (1h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 69619
telemt_connections_bad_total 775
telemt_handshake_timeouts_total 315
telemt_upstream_connect_attempt_total 1023
telemt_upstream_connect_success_total 1019
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 1023
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 529
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 489
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_reconnect_attempts_total 741
telemt_me_reconnect_success_total 738
telemt_me_reader_eof_total 760
telemt_me_idle_close_by_peer_total 760
telemt_me_route_drop_no_conn_total 22219
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 63672
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 220
telemt_desync_full_logged_total 52
telemt_desync_suppressed_total 168
telemt_desync_frames_bucket_total{bucket="1_2"} 60
telemt_desync_frames_bucket_total{bucket="3_10"} 79
telemt_desync_frames_bucket_total{bucket="gt_10"} 81
telemt_pool_swap_total 4
telemt_me_writer_removed_unexpected_total 749
telemt_me_writer_restored_same_endpoint_total 727
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 296
telemt_me_writer_removed_unexpected_minus_restored_total 11
telemt_user_connections_total{user="hello"} 63667
telemt_user_connections_current{user="hello"} 749
telemt_user_octets_from_client{user="hello"} 804796516 (767.51 MB)
telemt_user_octets_to_client{user="hello"} 24788779028 (23.09 GB)
telemt_user_unique_ips_current{user="hello"} 254
telemt_user_unique_ips_recent_window{user="hello"} 73
```

## server2

```
telemt 3.3.18

telemt_uptime_seconds 4711.9 (1h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 27739
telemt_connections_bad_total 3854
telemt_handshake_timeouts_total 1814
telemt_upstream_connect_attempt_total 1668
telemt_upstream_connect_success_total 1656
telemt_upstream_connect_fail_total 12
telemt_upstream_connect_attempts_per_request{bucket="1"} 1668
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 967
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 661
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 12
telemt_me_reconnect_attempts_total 1073
telemt_me_reconnect_success_total 1063
telemt_me_reader_eof_total 1072
telemt_me_idle_close_by_peer_total 1072
telemt_me_route_drop_no_conn_total 5392
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 21000
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 16
telemt_me_endpoint_quarantine_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 44
telemt_desync_full_logged_total 11
telemt_desync_suppressed_total 33
telemt_desync_frames_bucket_total{bucket="1_2"} 18
telemt_desync_frames_bucket_total{bucket="3_10"} 8
telemt_desync_frames_bucket_total{bucket="gt_10"} 18
telemt_pool_swap_total 5
telemt_me_writer_removed_unexpected_total 1027
telemt_me_writer_restored_same_endpoint_total 1055
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 61
telemt_user_connections_total{user="hello"} 21295
telemt_user_connections_current{user="hello"} 239
telemt_user_octets_from_client{user="hello"} 1249676723 (1.16 GB)
telemt_user_octets_to_client{user="hello"} 5351100336 (4.98 GB)
telemt_user_msgs_from_client{user="hello"} 620
telemt_user_msgs_to_client{user="hello"} 1332
telemt_user_unique_ips_current{user="hello"} 91
telemt_user_unique_ips_recent_window{user="hello"} 34
```

## server3

```
telemt 3.3.18

telemt_uptime_seconds 4712.1 (1h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 44754
telemt_connections_bad_total 995
telemt_handshake_timeouts_total 2647
telemt_upstream_connect_attempt_total 1046
telemt_upstream_connect_success_total 1038
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 1046
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 596
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 435
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_reconnect_attempts_total 756
telemt_me_reconnect_success_total 754
telemt_me_reader_eof_total 776
telemt_me_idle_close_by_peer_total 776
telemt_me_route_drop_no_conn_total 11160
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 40556
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 60
telemt_desync_full_logged_total 23
telemt_desync_suppressed_total 37
telemt_desync_frames_bucket_total{bucket="1_2"} 9
telemt_desync_frames_bucket_total{bucket="3_10"} 27
telemt_desync_frames_bucket_total{bucket="gt_10"} 24
telemt_pool_swap_total 5
telemt_me_writer_removed_unexpected_total 760
telemt_me_writer_restored_same_endpoint_total 735
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 242
telemt_me_writer_removed_unexpected_minus_restored_total 6
telemt_user_connections_total{user="hello"} 40478
telemt_user_connections_current{user="hello"} 360
telemt_user_octets_from_client{user="hello"} 627669952 (598.59 MB)
telemt_user_octets_to_client{user="hello"} 13445797488 (12.52 GB)
telemt_user_unique_ips_current{user="hello"} 143
telemt_user_unique_ips_recent_window{user="hello"} 45
```

## server4

```
telemt 3.3.18

telemt_uptime_seconds 4712.0 (1h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 31445
telemt_connections_bad_total 4102
telemt_handshake_timeouts_total 780
telemt_upstream_connect_attempt_total 1540
telemt_upstream_connect_success_total 1482
telemt_upstream_connect_fail_total 58
telemt_upstream_connect_attempts_per_request{bucket="1"} 1540
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 651
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 830
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 58
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 1215
telemt_me_reconnect_success_total 1194
telemt_me_reader_eof_total 1199
telemt_me_idle_close_by_peer_total 1199
telemt_me_seq_mismatch_total 1
telemt_me_route_drop_no_conn_total 6624
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 26053
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 14
telemt_desync_full_logged_total 4
telemt_desync_suppressed_total 10
telemt_desync_frames_bucket_total{bucket="1_2"} 9
telemt_desync_frames_bucket_total{bucket="3_10"} 4
telemt_desync_frames_bucket_total{bucket="gt_10"} 1
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 1201
telemt_me_writer_restored_same_endpoint_total 1181
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 96
telemt_me_writer_removed_unexpected_minus_restored_total 7
telemt_user_connections_total{user="hello"} 26055
telemt_user_connections_current{user="hello"} 260
telemt_user_octets_from_client{user="hello"} 203866456 (194.42 MB)
telemt_user_octets_to_client{user="hello"} 6941645444 (6.46 GB)
telemt_user_unique_ips_current{user="hello"} 88
telemt_user_unique_ips_recent_window{user="hello"} 42
```

## server5

```
telemt 3.3.18

telemt_uptime_seconds 4712.6 (1h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 24515
telemt_connections_bad_total 21
telemt_handshake_timeouts_total 518
telemt_upstream_connect_attempt_total 955
telemt_upstream_connect_success_total 951
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 955
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 403
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 544
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_reconnect_attempts_total 672
telemt_me_reconnect_success_total 668
telemt_me_reader_eof_total 687
telemt_me_idle_close_by_peer_total 687
telemt_me_route_drop_no_conn_total 5675
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 23409
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 125
telemt_desync_full_logged_total 37
telemt_desync_suppressed_total 88
telemt_desync_frames_bucket_total{bucket="1_2"} 40
telemt_desync_frames_bucket_total{bucket="3_10"} 57
telemt_desync_frames_bucket_total{bucket="gt_10"} 28
telemt_pool_swap_total 5
telemt_me_writer_removed_unexpected_total 675
telemt_me_writer_restored_same_endpoint_total 660
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 54
telemt_me_writer_removed_unexpected_minus_restored_total 7
telemt_user_connections_total{user="hello"} 23409
telemt_user_connections_current{user="hello"} 257
telemt_user_octets_from_client{user="hello"} 184142180 (175.61 MB)
telemt_user_octets_to_client{user="hello"} 12675932776 (11.81 GB)
telemt_user_unique_ips_current{user="hello"} 90
telemt_user_unique_ips_recent_window{user="hello"} 33
```