# Server Metrics 2026-03-11 11:22:09 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 75303.3 (20h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1688162
telemt_connections_bad_total 25368
telemt_handshake_timeouts_total 44158
telemt_upstream_connect_attempt_total 15750
telemt_upstream_connect_success_total 15741
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 15750
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7916
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7757
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 67
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 808
telemt_me_reconnect_attempts_total 24757
telemt_me_reconnect_success_total 11938
telemt_me_reader_eof_total 12913
telemt_me_idle_close_by_peer_total 12913
telemt_me_route_drop_no_conn_total 622219
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1535279
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8058
telemt_desync_full_logged_total 2174
telemt_desync_suppressed_total 5884
telemt_desync_frames_bucket_total{bucket="1_2"} 2049
telemt_desync_frames_bucket_total{bucket="3_10"} 3069
telemt_desync_frames_bucket_total{bucket="gt_10"} 2940
telemt_pool_swap_total 57
telemt_me_writer_removed_unexpected_total 12459
telemt_me_refill_failed_total 398
telemt_me_writer_restored_same_endpoint_total 11932
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 521
telemt_user_connections_total{user="hello"} 1533854
telemt_user_connections_current{user="hello"} 1367
telemt_user_octets_from_client{user="hello"} 19936350160 (18.57 GB)
telemt_user_octets_to_client{user="hello"} 436737293064 (406.74 GB)
telemt_user_unique_ips_current{user="hello"} 329
telemt_user_unique_ips_recent_window{user="hello"} 178
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 75359.9 (20h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 641621
telemt_connections_bad_total 11040
telemt_handshake_timeouts_total 39926
telemt_upstream_connect_attempt_total 24704
telemt_upstream_connect_success_total 21769
telemt_upstream_connect_fail_total 2935
telemt_upstream_connect_attempts_per_request{bucket="1"} 24704
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9966
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9560
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 209
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2034
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2935
telemt_me_keepalive_timeout_total 2184
telemt_me_reconnect_attempts_total 15904
telemt_me_reconnect_success_total 15056
telemt_me_reader_eof_total 15947
telemt_me_idle_close_by_peer_total 15945
telemt_me_route_drop_no_conn_total 260868
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 543916
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2486
telemt_desync_full_logged_total 781
telemt_desync_suppressed_total 1705
telemt_desync_frames_bucket_total{bucket="1_2"} 811
telemt_desync_frames_bucket_total{bucket="3_10"} 895
telemt_desync_frames_bucket_total{bucket="gt_10"} 780
telemt_pool_swap_total 64
telemt_me_writer_removed_unexpected_total 15243
telemt_me_refill_failed_total 22
telemt_me_writer_restored_same_endpoint_total 15034
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 86
telemt_me_writer_removed_unexpected_minus_restored_total 187
telemt_user_connections_total{user="hello"} 546136
telemt_user_connections_current{user="hello"} 496
telemt_user_octets_from_client{user="hello"} 5622833302 (5.24 GB)
telemt_user_octets_to_client{user="hello"} 152767944956 (142.28 GB)
telemt_user_msgs_from_client{user="hello"} 7933
telemt_user_msgs_to_client{user="hello"} 11226
telemt_user_unique_ips_current{user="hello"} 134
telemt_user_unique_ips_recent_window{user="hello"} 64
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 75359.7 (20h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1115205
telemt_connections_bad_total 7814
telemt_handshake_timeouts_total 106327
telemt_upstream_connect_attempt_total 20401
telemt_upstream_connect_success_total 20152
telemt_upstream_connect_fail_total 249
telemt_upstream_connect_attempts_per_request{bucket="1"} 20401
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10989
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9065
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 98
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 249
telemt_me_keepalive_timeout_total 823
telemt_me_reconnect_attempts_total 28925
telemt_me_reconnect_success_total 15299
telemt_me_reader_eof_total 16418
telemt_me_idle_close_by_peer_total 16418
telemt_me_route_drop_no_conn_total 374180
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 959966
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2637
telemt_desync_full_logged_total 783
telemt_desync_suppressed_total 1854
telemt_desync_frames_bucket_total{bucket="1_2"} 624
telemt_desync_frames_bucket_total{bucket="3_10"} 987
telemt_desync_frames_bucket_total{bucket="gt_10"} 1026
telemt_pool_swap_total 47
telemt_me_writer_removed_unexpected_total 15926
telemt_me_refill_failed_total 422
telemt_me_writer_restored_same_endpoint_total 15288
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 627
telemt_user_connections_total{user="hello"} 960712
telemt_user_connections_current{user="hello"} 653
telemt_user_octets_from_client{user="hello"} 11200480005 (10.43 GB)
telemt_user_octets_to_client{user="hello"} 292187489633 (272.12 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 204
telemt_user_unique_ips_recent_window{user="hello"} 114
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 75360.3 (20h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 808917
telemt_connections_bad_total 70803
telemt_handshake_timeouts_total 75583
telemt_upstream_connect_attempt_total 20450
telemt_upstream_connect_success_total 20450
telemt_upstream_connect_attempts_per_request{bucket="1"} 20450
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11255
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9191
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_me_keepalive_timeout_total 814
telemt_me_reconnect_attempts_total 17753
telemt_me_reconnect_success_total 16692
telemt_me_reader_eof_total 17723
telemt_me_idle_close_by_peer_total 17722
telemt_me_seq_mismatch_total 15
telemt_me_route_drop_no_conn_total 256507
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 639347
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 26
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1395
telemt_desync_full_logged_total 537
telemt_desync_suppressed_total 858
telemt_desync_frames_bucket_total{bucket="1_2"} 496
telemt_desync_frames_bucket_total{bucket="3_10"} 509
telemt_desync_frames_bucket_total{bucket="gt_10"} 390
telemt_pool_swap_total 68
telemt_me_writer_removed_unexpected_total 16893
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 16666
telemt_me_writer_restored_fallback_total 26
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 201
telemt_user_connections_total{user="hello"} 638714
telemt_user_connections_current{user="hello"} 477
telemt_user_octets_from_client{user="hello"} 7377752676 (6.87 GB)
telemt_user_octets_to_client{user="hello"} 182282998496 (169.76 GB)
telemt_user_unique_ips_current{user="hello"} 143
telemt_user_unique_ips_recent_window{user="hello"} 72
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 75360.0 (20h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 868332
telemt_connections_bad_total 6094
telemt_handshake_timeouts_total 8390
telemt_upstream_connect_attempt_total 20510
telemt_upstream_connect_success_total 20420
telemt_upstream_connect_fail_total 90
telemt_upstream_connect_attempts_per_request{bucket="1"} 20510
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10462
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9786
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 168
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 90
telemt_me_keepalive_timeout_total 880
telemt_me_reconnect_attempts_total 20346
telemt_me_reconnect_success_total 16544
telemt_me_reader_eof_total 17452
telemt_me_idle_close_by_peer_total 17452
telemt_me_route_drop_no_conn_total 304461
telemt_me_route_drop_channel_closed_total 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 788209
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 3266
telemt_desync_full_logged_total 1205
telemt_desync_suppressed_total 2061
telemt_desync_frames_bucket_total{bucket="1_2"} 1115
telemt_desync_frames_bucket_total{bucket="3_10"} 1294
telemt_desync_frames_bucket_total{bucket="gt_10"} 857
telemt_pool_swap_total 52
telemt_me_writer_removed_unexpected_total 16875
telemt_me_refill_failed_total 116
telemt_me_writer_restored_same_endpoint_total 16544
telemt_me_async_recovery_trigger_total 48
telemt_me_writer_removed_unexpected_minus_restored_total 331
telemt_user_connections_total{user="hello"} 787984
telemt_user_connections_current{user="hello"} 732
telemt_user_octets_from_client{user="hello"} 11837501491 (11.02 GB)
telemt_user_octets_to_client{user="hello"} 286132464286 (266.48 GB)
telemt_user_msgs_from_client{user="hello"} 122
telemt_user_msgs_to_client{user="hello"} 215
telemt_user_unique_ips_current{user="hello"} 195
telemt_user_unique_ips_recent_window{user="hello"} 101
```