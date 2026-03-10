# Server Metrics 2026-03-10 15:41:06 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 4441.9 (1h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 161313
telemt_connections_bad_total 861
telemt_handshake_timeouts_total 772
telemt_upstream_connect_attempt_total 950
telemt_upstream_connect_success_total 946
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 950
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 373
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 560
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 13
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_keepalive_timeout_total 78
telemt_me_reconnect_attempts_total 3482
telemt_me_reconnect_success_total 691
telemt_me_reader_eof_total 735
telemt_me_idle_close_by_peer_total 735
telemt_me_route_drop_no_conn_total 69685
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 154329
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 481
telemt_desync_full_logged_total 140
telemt_desync_suppressed_total 341
telemt_desync_frames_bucket_total{bucket="1_2"} 112
telemt_desync_frames_bucket_total{bucket="3_10"} 174
telemt_desync_frames_bucket_total{bucket="gt_10"} 195
telemt_me_writer_removed_unexpected_total 765
telemt_me_refill_failed_total 87
telemt_me_writer_restored_same_endpoint_total 685
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 74
telemt_user_connections_total{user="hello"} 154280
telemt_user_connections_current{user="hello"} 1369
telemt_user_octets_from_client{user="hello"} 1979319832 (1.84 GB)
telemt_user_octets_to_client{user="hello"} 42930845844 (39.98 GB)
telemt_user_unique_ips_current{user="hello"} 353
telemt_user_unique_ips_recent_window{user="hello"} 188
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 4498.6 (1h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 65307
telemt_connections_bad_total 1463
telemt_handshake_timeouts_total 6423
telemt_upstream_connect_attempt_total 930
telemt_upstream_connect_success_total 924
telemt_upstream_connect_fail_total 6
telemt_upstream_connect_attempts_per_request{bucket="1"} 930
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 500
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 424
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 6
telemt_me_keepalive_timeout_total 11
telemt_me_reconnect_attempts_total 679
telemt_me_reconnect_success_total 675
telemt_me_reader_eof_total 671
telemt_me_idle_close_by_peer_total 671
telemt_me_route_drop_no_conn_total 16970
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 53630
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 302
telemt_desync_full_logged_total 72
telemt_desync_suppressed_total 230
telemt_desync_frames_bucket_total{bucket="1_2"} 161
telemt_desync_frames_bucket_total{bucket="3_10"} 75
telemt_desync_frames_bucket_total{bucket="gt_10"} 66
telemt_pool_swap_total 2
telemt_me_writer_removed_unexpected_total 674
telemt_me_writer_restored_same_endpoint_total 654
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 86
telemt_user_connections_total{user="hello"} 53617
telemt_user_connections_current{user="hello"} 464
telemt_user_octets_from_client{user="hello"} 720045616 (686.69 MB)
telemt_user_octets_to_client{user="hello"} 15818466048 (14.73 GB)
telemt_user_unique_ips_current{user="hello"} 145
telemt_user_unique_ips_recent_window{user="hello"} 80
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 4498.3 (1h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 114397
telemt_connections_bad_total 399
telemt_handshake_timeouts_total 5497
telemt_upstream_connect_attempt_total 2123
telemt_upstream_connect_success_total 2084
telemt_upstream_connect_fail_total 39
telemt_upstream_connect_attempts_per_request{bucket="1"} 2123
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1518
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 560
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 39
telemt_me_keepalive_timeout_total 15
telemt_me_reconnect_attempts_total 822
telemt_me_reconnect_success_total 802
telemt_me_reader_eof_total 815
telemt_me_idle_close_by_peer_total 815
telemt_me_route_drop_no_conn_total 37237
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 96500
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 209
telemt_desync_full_logged_total 64
telemt_desync_suppressed_total 145
telemt_desync_frames_bucket_total{bucket="1_2"} 47
telemt_desync_frames_bucket_total{bucket="3_10"} 75
telemt_desync_frames_bucket_total{bucket="gt_10"} 87
telemt_pool_swap_total 2
telemt_me_writer_removed_unexpected_total 816
telemt_me_writer_restored_same_endpoint_total 791
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 14
telemt_user_connections_total{user="hello"} 97501
telemt_user_connections_current{user="hello"} 872
telemt_user_octets_from_client{user="hello"} 977953269 (932.65 MB)
telemt_user_octets_to_client{user="hello"} 27793771297 (25.88 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 251
telemt_user_unique_ips_recent_window{user="hello"} 139
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 4498.9 (1h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 75440
telemt_connections_bad_total 4427
telemt_handshake_timeouts_total 7702
telemt_upstream_connect_attempt_total 886
telemt_upstream_connect_success_total 886
telemt_upstream_connect_attempts_per_request{bucket="1"} 886
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 516
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 370
telemt_me_keepalive_timeout_total 10
telemt_me_reconnect_attempts_total 645
telemt_me_reconnect_success_total 641
telemt_me_reader_eof_total 644
telemt_me_idle_close_by_peer_total 644
telemt_me_route_drop_no_conn_total 24639
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 59831
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 181
telemt_desync_full_logged_total 77
telemt_desync_suppressed_total 104
telemt_desync_frames_bucket_total{bucket="1_2"} 67
telemt_desync_frames_bucket_total{bucket="3_10"} 70
telemt_desync_frames_bucket_total{bucket="gt_10"} 44
telemt_pool_swap_total 4
telemt_me_writer_removed_unexpected_total 637
telemt_me_writer_restored_same_endpoint_total 630
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 36
telemt_user_connections_total{user="hello"} 59763
telemt_user_connections_current{user="hello"} 608
telemt_user_octets_from_client{user="hello"} 796309388 (759.42 MB)
telemt_user_octets_to_client{user="hello"} 14679030340 (13.67 GB)
telemt_user_unique_ips_current{user="hello"} 165
telemt_user_unique_ips_recent_window{user="hello"} 99
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 4498.6 (1h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 83799
telemt_connections_bad_total 7
telemt_handshake_timeouts_total 662
telemt_upstream_connect_attempt_total 1331
telemt_upstream_connect_success_total 1326
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 1331
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 715
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 602
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 20
telemt_me_reconnect_attempts_total 1079
telemt_me_reconnect_success_total 1072
telemt_me_reader_eof_total 1082
telemt_me_idle_close_by_peer_total 1082
telemt_me_route_drop_no_conn_total 31775
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 77233
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 441
telemt_desync_full_logged_total 137
telemt_desync_suppressed_total 304
telemt_desync_frames_bucket_total{bucket="1_2"} 180
telemt_desync_frames_bucket_total{bucket="3_10"} 190
telemt_desync_frames_bucket_total{bucket="gt_10"} 71
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 1074
telemt_me_writer_restored_same_endpoint_total 1072
telemt_me_async_recovery_trigger_total 48
telemt_me_writer_removed_unexpected_minus_restored_total 2
telemt_user_connections_total{user="hello"} 77191
telemt_user_connections_current{user="hello"} 639
telemt_user_octets_from_client{user="hello"} 1421747816 (1.32 GB)
telemt_user_octets_to_client{user="hello"} 20968516264 (19.53 GB)
telemt_user_unique_ips_current{user="hello"} 180
telemt_user_unique_ips_recent_window{user="hello"} 86
```