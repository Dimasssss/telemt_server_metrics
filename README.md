# Server Metrics 2026-03-11 13:09:22 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 81736.5 (22h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1914605
telemt_connections_bad_total 27772
telemt_handshake_timeouts_total 49263
telemt_upstream_connect_attempt_total 16918
telemt_upstream_connect_success_total 16909
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 16918
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8544
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8293
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 71
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 876
telemt_me_reconnect_attempts_total 25619
telemt_me_reconnect_success_total 12789
telemt_me_reader_eof_total 13825
telemt_me_idle_close_by_peer_total 13825
telemt_me_route_drop_no_conn_total 705497
telemt_me_route_drop_channel_closed_total 7
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1747960
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 9144
telemt_desync_full_logged_total 2472
telemt_desync_suppressed_total 6672
telemt_desync_frames_bucket_total{bucket="1_2"} 2274
telemt_desync_frames_bucket_total{bucket="3_10"} 3511
telemt_desync_frames_bucket_total{bucket="gt_10"} 3359
telemt_pool_swap_total 63
telemt_me_writer_removed_unexpected_total 13326
telemt_me_refill_failed_total 398
telemt_me_writer_restored_same_endpoint_total 12783
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 537
telemt_user_connections_total{user="hello"} 1746483
telemt_user_connections_current{user="hello"} 1509
telemt_user_octets_from_client{user="hello"} 23399273248 (21.79 GB)
telemt_user_octets_to_client{user="hello"} 494577564852 (460.61 GB)
telemt_user_unique_ips_current{user="hello"} 367
telemt_user_unique_ips_recent_window{user="hello"} 192
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 81793.1 (22h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 727927
telemt_connections_bad_total 13031
telemt_handshake_timeouts_total 50581
telemt_upstream_connect_attempt_total 26364
telemt_upstream_connect_success_total 23420
telemt_upstream_connect_fail_total 2944
telemt_upstream_connect_attempts_per_request{bucket="1"} 26364
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10784
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10388
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 209
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2039
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2944
telemt_me_keepalive_timeout_total 2440
telemt_me_reconnect_attempts_total 17248
telemt_me_reconnect_success_total 16386
telemt_me_reader_eof_total 17341
telemt_me_idle_close_by_peer_total 17338
telemt_me_route_drop_no_conn_total 285050
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 612254
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2687
telemt_desync_full_logged_total 851
telemt_desync_suppressed_total 1836
telemt_desync_frames_bucket_total{bucket="1_2"} 849
telemt_desync_frames_bucket_total{bucket="3_10"} 976
telemt_desync_frames_bucket_total{bucket="gt_10"} 862
telemt_pool_swap_total 68
telemt_me_writer_removed_unexpected_total 16594
telemt_me_refill_failed_total 22
telemt_me_writer_restored_same_endpoint_total 16363
telemt_me_writer_restored_fallback_total 23
telemt_me_async_recovery_trigger_total 86
telemt_me_writer_removed_unexpected_minus_restored_total 208
telemt_user_connections_total{user="hello"} 614647
telemt_user_connections_current{user="hello"} 518
telemt_user_octets_from_client{user="hello"} 6587038750 (6.13 GB)
telemt_user_octets_to_client{user="hello"} 175704006120 (163.64 GB)
telemt_user_msgs_from_client{user="hello"} 7933
telemt_user_msgs_to_client{user="hello"} 11226
telemt_user_unique_ips_current{user="hello"} 137
telemt_user_unique_ips_recent_window{user="hello"} 64
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 81793.0 (22h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1250868
telemt_connections_bad_total 8148
telemt_handshake_timeouts_total 116116
telemt_upstream_connect_attempt_total 21843
telemt_upstream_connect_success_total 21576
telemt_upstream_connect_fail_total 267
telemt_upstream_connect_attempts_per_request{bucket="1"} 21843
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11693
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9779
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 104
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 267
telemt_me_keepalive_timeout_total 877
telemt_me_reconnect_attempts_total 32497
telemt_me_reconnect_success_total 16396
telemt_me_reader_eof_total 17640
telemt_me_idle_close_by_peer_total 17640
telemt_me_route_drop_no_conn_total 432575
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1080084
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2909
telemt_desync_full_logged_total 867
telemt_desync_suppressed_total 2042
telemt_desync_frames_bucket_total{bucket="1_2"} 703
telemt_desync_frames_bucket_total{bucket="3_10"} 1094
telemt_desync_frames_bucket_total{bucket="gt_10"} 1112
telemt_pool_swap_total 50
telemt_me_writer_removed_unexpected_total 17114
telemt_me_refill_failed_total 499
telemt_me_writer_restored_same_endpoint_total 16385
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 718
telemt_user_connections_total{user="hello"} 1080471
telemt_user_connections_current{user="hello"} 854
telemt_user_octets_from_client{user="hello"} 12797973477 (11.92 GB)
telemt_user_octets_to_client{user="hello"} 324131572309 (301.87 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 248
telemt_user_unique_ips_recent_window{user="hello"} 132
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 81793.5 (22h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 904571
telemt_connections_bad_total 76804
telemt_handshake_timeouts_total 85607
telemt_upstream_connect_attempt_total 22299
telemt_upstream_connect_success_total 22299
telemt_upstream_connect_attempts_per_request{bucket="1"} 22299
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12217
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10078
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_me_keepalive_timeout_total 901
telemt_me_reconnect_attempts_total 19292
telemt_me_reconnect_success_total 18224
telemt_me_reader_eof_total 19316
telemt_me_idle_close_by_peer_total 19315
telemt_me_seq_mismatch_total 16
telemt_me_route_drop_no_conn_total 290043
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 717310
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 27
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1519
telemt_desync_full_logged_total 595
telemt_desync_suppressed_total 924
telemt_desync_frames_bucket_total{bucket="1_2"} 551
telemt_desync_frames_bucket_total{bucket="3_10"} 542
telemt_desync_frames_bucket_total{bucket="gt_10"} 426
telemt_pool_swap_total 71
telemt_me_writer_removed_unexpected_total 18448
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 18197
telemt_me_writer_restored_fallback_total 27
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 224
telemt_user_connections_total{user="hello"} 716668
telemt_user_connections_current{user="hello"} 518
telemt_user_octets_from_client{user="hello"} 8298532500 (7.73 GB)
telemt_user_octets_to_client{user="hello"} 206745969252 (192.55 GB)
telemt_user_unique_ips_current{user="hello"} 153
telemt_user_unique_ips_recent_window{user="hello"} 93
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 81793.1 (22h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 982188
telemt_connections_bad_total 6808
telemt_handshake_timeouts_total 9054
telemt_upstream_connect_attempt_total 22270
telemt_upstream_connect_success_total 22174
telemt_upstream_connect_fail_total 96
telemt_upstream_connect_attempts_per_request{bucket="1"} 22270
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11387
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10601
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 182
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 96
telemt_me_keepalive_timeout_total 932
telemt_me_reconnect_attempts_total 22043
telemt_me_reconnect_success_total 17972
telemt_me_reader_eof_total 18958
telemt_me_idle_close_by_peer_total 18958
telemt_me_route_drop_no_conn_total 346132
telemt_me_route_drop_channel_closed_total 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 891988
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 3590
telemt_desync_full_logged_total 1329
telemt_desync_suppressed_total 2261
telemt_desync_frames_bucket_total{bucket="1_2"} 1250
telemt_desync_frames_bucket_total{bucket="3_10"} 1369
telemt_desync_frames_bucket_total{bucket="gt_10"} 971
telemt_pool_swap_total 55
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 18329
telemt_me_refill_failed_total 124
telemt_me_writer_restored_same_endpoint_total 17972
telemt_me_async_recovery_trigger_total 48
telemt_me_writer_removed_unexpected_minus_restored_total 357
telemt_user_connections_total{user="hello"} 891737
telemt_user_connections_current{user="hello"} 866
telemt_user_octets_from_client{user="hello"} 13046094731 (12.15 GB)
telemt_user_octets_to_client{user="hello"} 319196030874 (297.27 GB)
telemt_user_msgs_from_client{user="hello"} 122
telemt_user_msgs_to_client{user="hello"} 215
telemt_user_unique_ips_current{user="hello"} 209
telemt_user_unique_ips_recent_window{user="hello"} 132
```