# Server Metrics 2026-03-15 00:03:31 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.18

telemt_uptime_seconds 6542.8 (1h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 88548
telemt_connections_bad_total 1069
telemt_handshake_timeouts_total 398
telemt_upstream_connect_attempt_total 1409
telemt_upstream_connect_success_total 1403
telemt_upstream_connect_fail_total 6
telemt_upstream_connect_attempts_per_request{bucket="1"} 1409
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 725
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 677
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 6
telemt_me_reconnect_attempts_total 1039
telemt_me_reconnect_success_total 1034
telemt_me_reader_eof_total 1075
telemt_me_idle_close_by_peer_total 1075
telemt_me_route_drop_no_conn_total 28447
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 80691
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 242
telemt_desync_full_logged_total 66
telemt_desync_suppressed_total 176
telemt_desync_frames_bucket_total{bucket="1_2"} 72
telemt_desync_frames_bucket_total{bucket="3_10"} 85
telemt_desync_frames_bucket_total{bucket="gt_10"} 85
telemt_pool_swap_total 6
telemt_me_writer_removed_unexpected_total 1048
telemt_me_writer_restored_same_endpoint_total 1023
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 296
telemt_me_writer_removed_unexpected_minus_restored_total 14
telemt_user_connections_total{user="hello"} 80683
telemt_user_connections_current{user="hello"} 781
telemt_user_octets_from_client{user="hello"} 932330064 (889.14 MB)
telemt_user_octets_to_client{user="hello"} 30228612764 (28.15 GB)
telemt_user_unique_ips_current{user="hello"} 266
telemt_user_unique_ips_recent_window{user="hello"} 92
```

## server2

```
telemt 3.3.18

telemt_uptime_seconds 6543.4 (1h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 35008
telemt_connections_bad_total 5189
telemt_handshake_timeouts_total 1927
telemt_upstream_connect_attempt_total 2178
telemt_upstream_connect_success_total 2164
telemt_upstream_connect_fail_total 14
telemt_upstream_connect_attempts_per_request{bucket="1"} 2178
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1247
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 889
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 14
telemt_me_reconnect_attempts_total 1495
telemt_me_reconnect_success_total 1482
telemt_me_reader_eof_total 1519
telemt_me_idle_close_by_peer_total 1519
telemt_me_route_drop_no_conn_total 7134
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 26557
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 16
telemt_me_endpoint_quarantine_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 82
telemt_desync_full_logged_total 19
telemt_desync_suppressed_total 63
telemt_desync_frames_bucket_total{bucket="1_2"} 38
telemt_desync_frames_bucket_total{bucket="3_10"} 23
telemt_desync_frames_bucket_total{bucket="gt_10"} 21
telemt_pool_swap_total 7
telemt_me_writer_removed_unexpected_total 1449
telemt_me_writer_restored_same_endpoint_total 1474
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 61
telemt_user_connections_total{user="hello"} 26853
telemt_user_connections_current{user="hello"} 202
telemt_user_octets_from_client{user="hello"} 1291201075 (1.20 GB)
telemt_user_octets_to_client{user="hello"} 6414484416 (5.97 GB)
telemt_user_msgs_from_client{user="hello"} 620
telemt_user_msgs_to_client{user="hello"} 1332
telemt_user_unique_ips_current{user="hello"} 86
telemt_user_unique_ips_recent_window{user="hello"} 34
```

## server3

```
telemt 3.3.18

telemt_uptime_seconds 6543.7 (1h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 58287
telemt_connections_bad_total 1030
telemt_handshake_timeouts_total 3798
telemt_upstream_connect_attempt_total 1474
telemt_upstream_connect_success_total 1465
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 1474
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 838
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 619
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_reconnect_attempts_total 1097
telemt_me_reconnect_success_total 1094
telemt_me_reader_eof_total 1137
telemt_me_idle_close_by_peer_total 1137
telemt_me_route_drop_no_conn_total 14322
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 52266
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 96
telemt_desync_full_logged_total 32
telemt_desync_suppressed_total 64
telemt_desync_frames_bucket_total{bucket="1_2"} 23
telemt_desync_frames_bucket_total{bucket="3_10"} 40
telemt_desync_frames_bucket_total{bucket="gt_10"} 33
telemt_pool_swap_total 7
telemt_me_writer_removed_unexpected_total 1103
telemt_me_writer_restored_same_endpoint_total 1075
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 242
telemt_me_writer_removed_unexpected_minus_restored_total 9
telemt_user_connections_total{user="hello"} 52186
telemt_user_connections_current{user="hello"} 291
telemt_user_octets_from_client{user="hello"} 677879732 (646.48 MB)
telemt_user_octets_to_client{user="hello"} 15374127880 (14.32 GB)
telemt_user_unique_ips_current{user="hello"} 121
telemt_user_unique_ips_recent_window{user="hello"} 46
```

## server4

```
telemt 3.3.18

telemt_uptime_seconds 6543.6 (1h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 45762
telemt_connections_bad_total 7608
telemt_handshake_timeouts_total 894
telemt_upstream_connect_attempt_total 2286
telemt_upstream_connect_success_total 2220
telemt_upstream_connect_fail_total 66
telemt_upstream_connect_attempts_per_request{bucket="1"} 2286
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 988
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1231
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 66
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 3147
telemt_me_reconnect_success_total 1844
telemt_me_reader_eof_total 1916
telemt_me_idle_close_by_peer_total 1916
telemt_me_seq_mismatch_total 1
telemt_me_route_drop_no_conn_total 8788
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 36298
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 63
telemt_desync_full_logged_total 15
telemt_desync_suppressed_total 48
telemt_desync_frames_bucket_total{bucket="1_2"} 33
telemt_desync_frames_bucket_total{bucket="3_10"} 28
telemt_desync_frames_bucket_total{bucket="gt_10"} 2
telemt_pool_swap_total 2
telemt_me_writer_removed_unexpected_total 1896
telemt_me_refill_failed_total 40
telemt_me_writer_restored_same_endpoint_total 1831
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 96
telemt_me_writer_removed_unexpected_minus_restored_total 52
telemt_user_connections_total{user="hello"} 36301
telemt_user_connections_current{user="hello"} 285
telemt_user_octets_from_client{user="hello"} 262206164 (250.06 MB)
telemt_user_octets_to_client{user="hello"} 9455050704 (8.81 GB)
telemt_user_unique_ips_current{user="hello"} 98
telemt_user_unique_ips_recent_window{user="hello"} 43
```

## server5

```
telemt 3.3.18

telemt_uptime_seconds 6544.1 (1h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 32069
telemt_connections_bad_total 22
telemt_handshake_timeouts_total 538
telemt_upstream_connect_attempt_total 1375
telemt_upstream_connect_success_total 1370
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 1375
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 561
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 805
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_reconnect_attempts_total 1005
telemt_me_reconnect_success_total 1000
telemt_me_reader_eof_total 1043
telemt_me_idle_close_by_peer_total 1043
telemt_me_route_drop_no_conn_total 7790
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 30765
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 143
telemt_desync_full_logged_total 40
telemt_desync_suppressed_total 103
telemt_desync_frames_bucket_total{bucket="1_2"} 52
telemt_desync_frames_bucket_total{bucket="3_10"} 63
telemt_desync_frames_bucket_total{bucket="gt_10"} 28
telemt_pool_swap_total 7
telemt_me_writer_removed_unexpected_total 1011
telemt_me_writer_restored_same_endpoint_total 992
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 54
telemt_me_writer_removed_unexpected_minus_restored_total 11
telemt_user_connections_total{user="hello"} 30765
telemt_user_connections_current{user="hello"} 260
telemt_user_octets_from_client{user="hello"} 248125812 (236.63 MB)
telemt_user_octets_to_client{user="hello"} 14594334112 (13.59 GB)
telemt_user_unique_ips_current{user="hello"} 98
telemt_user_unique_ips_recent_window{user="hello"} 33
```