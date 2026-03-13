# Server Metrics 2026-03-13 15:46:19 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 121661.2 (33h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3800682
telemt_connections_bad_total 37429
telemt_handshake_timeouts_total 82974
telemt_upstream_connect_attempt_total 23686
telemt_upstream_connect_success_total 23551
telemt_upstream_connect_fail_total 135
telemt_upstream_connect_attempts_per_request{bucket="1"} 23686
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12143
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11346
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 62
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 135
telemt_me_keepalive_timeout_total 2196
telemt_me_reconnect_attempts_total 27579
telemt_me_reconnect_success_total 17490
telemt_me_reader_eof_total 18800
telemt_me_idle_close_by_peer_total 18799
telemt_me_route_drop_no_conn_total 1410072
telemt_me_route_drop_channel_closed_total 18
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3479220
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 14019
telemt_desync_full_logged_total 3704
telemt_desync_suppressed_total 10315
telemt_desync_frames_bucket_total{bucket="1_2"} 3514
telemt_desync_frames_bucket_total{bucket="3_10"} 5302
telemt_desync_frames_bucket_total{bucket="gt_10"} 5203
telemt_pool_swap_total 102
telemt_me_writer_removed_unexpected_total 18044
telemt_me_refill_failed_total 312
telemt_me_writer_restored_same_endpoint_total 17477
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 554
telemt_user_connections_total{user="hello"} 3479022
telemt_user_connections_current{user="hello"} 1614
telemt_user_octets_from_client{user="hello"} 47350963652 (44.10 GB)
telemt_user_octets_to_client{user="hello"} 1092201269480 (1017.19 GB)
telemt_user_unique_ips_current{user="hello"} 430
telemt_user_unique_ips_recent_window{user="hello"} 223
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 21325.0 (5h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 307232
telemt_connections_bad_total 16131
telemt_handshake_timeouts_total 8546
telemt_upstream_connect_attempt_total 4988
telemt_upstream_connect_success_total 4902
telemt_upstream_connect_fail_total 86
telemt_upstream_connect_attempts_per_request{bucket="1"} 4988
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2530
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2321
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 14
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 37
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 86
telemt_me_keepalive_timeout_total 102
telemt_me_reconnect_attempts_total 6089
telemt_me_reconnect_success_total 3798
telemt_me_reader_eof_total 4037
telemt_me_idle_close_by_peer_total 4037
telemt_me_route_drop_no_conn_total 111246
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 274659
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 6
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1049
telemt_desync_full_logged_total 269
telemt_desync_suppressed_total 780
telemt_desync_frames_bucket_total{bucket="1_2"} 199
telemt_desync_frames_bucket_total{bucket="3_10"} 506
telemt_desync_frames_bucket_total{bucket="gt_10"} 344
telemt_pool_swap_total 17
telemt_me_writer_removed_unexpected_total 3919
telemt_me_refill_failed_total 69
telemt_me_writer_restored_same_endpoint_total 3791
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 22
telemt_me_writer_removed_unexpected_minus_restored_total 121
telemt_user_connections_total{user="hello"} 274687
telemt_user_connections_current{user="hello"} 565
telemt_user_octets_from_client{user="hello"} 2740051928 (2.55 GB)
telemt_user_octets_to_client{user="hello"} 78165545156 (72.80 GB)
telemt_user_unique_ips_current{user="hello"} 181
telemt_user_unique_ips_recent_window{user="hello"} 98
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 151281.8 (42h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2810387
telemt_connections_bad_total 27797
telemt_handshake_timeouts_total 187118
telemt_upstream_connect_attempt_total 33927
telemt_upstream_connect_success_total 33917
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 33927
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17571
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16216
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 125
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_keepalive_timeout_total 3274
telemt_me_reconnect_attempts_total 28593
telemt_me_reconnect_success_total 26044
telemt_me_reader_eof_total 27619
telemt_me_idle_close_by_peer_total 27618
telemt_me_route_drop_no_conn_total 949889
telemt_me_route_drop_channel_closed_total 17
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2308630
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8203
telemt_desync_full_logged_total 2712
telemt_desync_suppressed_total 5491
telemt_desync_frames_bucket_total{bucket="1_2"} 1311
telemt_desync_frames_bucket_total{bucket="3_10"} 2981
telemt_desync_frames_bucket_total{bucket="gt_10"} 3911
telemt_pool_swap_total 142
telemt_me_writer_removed_unexpected_total 26350
telemt_me_refill_failed_total 75
telemt_me_writer_restored_same_endpoint_total 26003
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 306
telemt_user_connections_total{user="hello"} 2308026
telemt_user_connections_current{user="hello"} 1184
telemt_user_octets_from_client{user="hello"} 38096140476 (35.48 GB)
telemt_user_octets_to_client{user="hello"} 807548844913 (752.09 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 312
telemt_user_unique_ips_recent_window{user="hello"} 207
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 151282.1 (42h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1788501
telemt_connections_bad_total 18142
telemt_handshake_timeouts_total 139192
telemt_upstream_connect_attempt_total 47668
telemt_upstream_connect_success_total 45337
telemt_upstream_connect_fail_total 2194
telemt_upstream_connect_attempts_per_request{bucket="1"} 47394
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 27235
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18011
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 91
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2193
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 11883
telemt_me_reconnect_attempts_total 40921
telemt_me_reconnect_success_total 31948
telemt_me_reader_eof_total 34320
telemt_me_idle_close_by_peer_total 34313
telemt_me_route_drop_no_conn_total 641588
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1491709
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3001
telemt_desync_full_logged_total 970
telemt_desync_suppressed_total 2031
telemt_desync_frames_bucket_total{bucket="1_2"} 803
telemt_desync_frames_bucket_total{bucket="3_10"} 1239
telemt_desync_frames_bucket_total{bucket="gt_10"} 959
telemt_pool_swap_total 131
telemt_me_writer_removed_unexpected_total 32474
telemt_me_refill_failed_total 274
telemt_me_writer_restored_same_endpoint_total 31924
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 526
telemt_user_connections_total{user="hello"} 1496418
telemt_user_connections_current{user="hello"} 650
telemt_user_octets_from_client{user="hello"} 23247199813 (21.65 GB)
telemt_user_octets_to_client{user="hello"} 573050845078 (533.70 GB)
telemt_user_msgs_from_client{user="hello"} 44500
telemt_user_msgs_to_client{user="hello"} 116355
telemt_user_unique_ips_current{user="hello"} 202
telemt_user_unique_ips_recent_window{user="hello"} 139
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 20717.9 (5h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 333030
telemt_connections_bad_total 4015
telemt_handshake_timeouts_total 3053
telemt_upstream_connect_attempt_total 4464
telemt_upstream_connect_success_total 4331
telemt_upstream_connect_fail_total 133
telemt_upstream_connect_attempts_per_request{bucket="1"} 4464
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2035
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2292
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 133
telemt_me_keepalive_timeout_total 90
telemt_me_reconnect_attempts_total 13859
telemt_me_reconnect_success_total 3285
telemt_me_reader_eof_total 3665
telemt_me_idle_close_by_peer_total 3665
telemt_me_route_drop_no_conn_total 132095
telemt_me_route_drop_channel_closed_total 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 312182
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 3
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 998
telemt_desync_full_logged_total 320
telemt_desync_suppressed_total 678
telemt_desync_frames_bucket_total{bucket="1_2"} 339
telemt_desync_frames_bucket_total{bucket="3_10"} 395
telemt_desync_frames_bucket_total{bucket="gt_10"} 264
telemt_pool_swap_total 6
telemt_me_writer_removed_unexpected_total 3633
telemt_me_refill_failed_total 329
telemt_me_writer_restored_same_endpoint_total 3281
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 348
telemt_user_connections_total{user="hello"} 312157
telemt_user_connections_current{user="hello"} 811
telemt_user_octets_from_client{user="hello"} 3645797072 (3.40 GB)
telemt_user_octets_to_client{user="hello"} 98901494232 (92.11 GB)
telemt_user_unique_ips_current{user="hello"} 209
telemt_user_unique_ips_recent_window{user="hello"} 121
```