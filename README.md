# Server Metrics 2026-03-11 19:06:50 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 103182.8 (28h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2620473
telemt_connections_bad_total 48620
telemt_handshake_timeouts_total 57418
telemt_upstream_connect_attempt_total 21756
telemt_upstream_connect_success_total 21744
telemt_upstream_connect_fail_total 12
telemt_upstream_connect_attempts_per_request{bucket="1"} 21756
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10997
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10637
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 109
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 12
telemt_me_keepalive_timeout_total 5327
telemt_me_reconnect_attempts_total 34408
telemt_me_reconnect_success_total 16521
telemt_me_reader_eof_total 17859
telemt_me_idle_close_by_peer_total 17859
telemt_me_route_drop_no_conn_total 988218
telemt_me_route_drop_channel_closed_total 9
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2396128
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 12133
telemt_desync_full_logged_total 3360
telemt_desync_suppressed_total 8773
telemt_desync_frames_bucket_total{bucket="1_2"} 2978
telemt_desync_frames_bucket_total{bucket="3_10"} 4682
telemt_desync_frames_bucket_total{bucket="gt_10"} 4473
telemt_pool_swap_total 74
telemt_me_writer_removed_unexpected_total 17265
telemt_me_refill_failed_total 555
telemt_me_writer_restored_same_endpoint_total 16515
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 744
telemt_user_connections_total{user="hello"} 2394479
telemt_user_connections_current{user="hello"} 1220
telemt_user_octets_from_client{user="hello"} 35692448028 (33.24 GB)
telemt_user_octets_to_client{user="hello"} 679397688544 (632.74 GB)
telemt_user_unique_ips_current{user="hello"} 331
telemt_user_unique_ips_recent_window{user="hello"} 172
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 103239.4 (28h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 978049
telemt_connections_bad_total 16429
telemt_handshake_timeouts_total 87903
telemt_upstream_connect_attempt_total 31960
telemt_upstream_connect_success_total 28991
telemt_upstream_connect_fail_total 2969
telemt_upstream_connect_attempts_per_request{bucket="1"} 31960
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13685
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13049
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 209
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2048
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2969
telemt_me_keepalive_timeout_total 2845
telemt_me_reconnect_attempts_total 22967
telemt_me_reconnect_success_total 20852
telemt_me_reader_eof_total 22072
telemt_me_idle_close_by_peer_total 22069
telemt_me_route_drop_no_conn_total 369541
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 815637
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3230
telemt_desync_full_logged_total 1048
telemt_desync_suppressed_total 2182
telemt_desync_frames_bucket_total{bucket="1_2"} 1021
telemt_desync_frames_bucket_total{bucket="3_10"} 1153
telemt_desync_frames_bucket_total{bucket="gt_10"} 1056
telemt_pool_swap_total 83
telemt_me_writer_removed_unexpected_total 21142
telemt_me_refill_failed_total 60
telemt_me_writer_restored_same_endpoint_total 20829
telemt_me_writer_restored_fallback_total 23
telemt_me_async_recovery_trigger_total 86
telemt_me_writer_removed_unexpected_minus_restored_total 290
telemt_user_connections_total{user="hello"} 818084
telemt_user_connections_current{user="hello"} 416
telemt_user_octets_from_client{user="hello"} 9819011370 (9.14 GB)
telemt_user_octets_to_client{user="hello"} 236264702756 (220.04 GB)
telemt_user_msgs_from_client{user="hello"} 7933
telemt_user_msgs_to_client{user="hello"} 11226
telemt_user_unique_ips_current{user="hello"} 124
telemt_user_unique_ips_recent_window{user="hello"} 59
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 103239.4 (28h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1682260
telemt_connections_bad_total 10484
telemt_handshake_timeouts_total 133561
telemt_upstream_connect_attempt_total 26732
telemt_upstream_connect_success_total 26396
telemt_upstream_connect_fail_total 336
telemt_upstream_connect_attempts_per_request{bucket="1"} 26732
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14244
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12018
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 133
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 336
telemt_me_keepalive_timeout_total 1975
telemt_me_reconnect_attempts_total 49764
telemt_me_reconnect_success_total 20109
telemt_me_reader_eof_total 21895
telemt_me_idle_close_by_peer_total 21895
telemt_me_route_drop_no_conn_total 613173
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1474547
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4089
telemt_desync_full_logged_total 1200
telemt_desync_suppressed_total 2889
telemt_desync_frames_bucket_total{bucket="1_2"} 952
telemt_desync_frames_bucket_total{bucket="3_10"} 1549
telemt_desync_frames_bucket_total{bucket="gt_10"} 1588
telemt_pool_swap_total 55
telemt_me_writer_removed_unexpected_total 21315
telemt_me_refill_failed_total 921
telemt_me_writer_restored_same_endpoint_total 20097
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 1206
telemt_user_connections_total{user="hello"} 1474214
telemt_user_connections_current{user="hello"} 674
telemt_user_octets_from_client{user="hello"} 19072131425 (17.76 GB)
telemt_user_octets_to_client{user="hello"} 449226393361 (418.37 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 222
telemt_user_unique_ips_recent_window{user="hello"} 102
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 103240.9 (28h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1201889
telemt_connections_bad_total 78200
telemt_handshake_timeouts_total 110443
telemt_upstream_connect_attempt_total 27886
telemt_upstream_connect_success_total 27885
telemt_upstream_connect_attempts_per_request{bucket="1"} 27885
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15202
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12677
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 1433
telemt_me_reconnect_attempts_total 27336
telemt_me_reconnect_success_total 22724
telemt_me_reader_eof_total 24116
telemt_me_idle_close_by_peer_total 24115
telemt_me_seq_mismatch_total 23
telemt_me_route_drop_no_conn_total 401455
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 978437
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 34
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2051
telemt_desync_full_logged_total 783
telemt_desync_suppressed_total 1268
telemt_desync_frames_bucket_total{bucket="1_2"} 752
telemt_desync_frames_bucket_total{bucket="3_10"} 701
telemt_desync_frames_bucket_total{bucket="gt_10"} 598
telemt_pool_swap_total 83
telemt_me_writer_removed_unexpected_total 23109
telemt_me_refill_failed_total 141
telemt_me_writer_restored_same_endpoint_total 22691
telemt_me_writer_restored_fallback_total 33
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 385
telemt_user_connections_total{user="hello"} 977698
telemt_user_connections_current{user="hello"} 504
telemt_user_octets_from_client{user="hello"} 11618935848 (10.82 GB)
telemt_user_octets_to_client{user="hello"} 296837190740 (276.45 GB)
telemt_user_unique_ips_current{user="hello"} 140
telemt_user_unique_ips_recent_window{user="hello"} 81
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 7916.0 (2h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 127153
telemt_connections_bad_total 640
telemt_handshake_timeouts_total 766
telemt_upstream_connect_attempt_total 2245
telemt_upstream_connect_success_total 2244
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 2245
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1184
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1046
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 14
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 52
telemt_me_reconnect_attempts_total 1821
telemt_me_reconnect_success_total 1802
telemt_me_reader_eof_total 1837
telemt_me_idle_close_by_peer_total 1837
telemt_me_seq_mismatch_total 2
telemt_me_route_drop_no_conn_total 44674
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 117184
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 231
telemt_desync_full_logged_total 75
telemt_desync_suppressed_total 156
telemt_desync_frames_bucket_total{bucket="1_2"} 61
telemt_desync_frames_bucket_total{bucket="3_10"} 80
telemt_desync_frames_bucket_total{bucket="gt_10"} 90
telemt_pool_swap_total 2
telemt_me_writer_removed_unexpected_total 1825
telemt_me_writer_restored_same_endpoint_total 1778
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 256
telemt_me_writer_removed_unexpected_minus_restored_total 23
telemt_user_connections_total{user="hello"} 117152
telemt_user_connections_current{user="hello"} 585
telemt_user_octets_from_client{user="hello"} 6522657436 (6.07 GB)
telemt_user_octets_to_client{user="hello"} 40246082620 (37.48 GB)
telemt_user_unique_ips_current{user="hello"} 157
telemt_user_unique_ips_recent_window{user="hello"} 83
```