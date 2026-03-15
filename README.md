# Server Metrics 2026-03-15 07:41:46 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.18

telemt_uptime_seconds 34036.9 (9h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 622686
telemt_connections_bad_total 21758
telemt_handshake_timeouts_total 4240
telemt_upstream_connect_attempt_total 7096
telemt_upstream_connect_success_total 7070
telemt_upstream_connect_fail_total 26
telemt_upstream_connect_attempts_per_request{bucket="1"} 7096
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3720
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3340
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 26
telemt_me_reconnect_attempts_total 5405
telemt_me_reconnect_success_total 5377
telemt_me_reader_eof_total 5687
telemt_me_idle_close_by_peer_total 5687
telemt_me_route_drop_no_conn_total 194802
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 524983
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1459
telemt_desync_full_logged_total 459
telemt_desync_suppressed_total 1000
telemt_desync_frames_bucket_total{bucket="1_2"} 314
telemt_desync_frames_bucket_total{bucket="3_10"} 518
telemt_desync_frames_bucket_total{bucket="gt_10"} 627
telemt_pool_swap_total 31
telemt_me_writer_removed_unexpected_total 5448
telemt_me_writer_restored_same_endpoint_total 5366
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 296
telemt_me_writer_removed_unexpected_minus_restored_total 71
telemt_user_connections_total{user="hello"} 524981
telemt_user_connections_current{user="hello"} 1712
telemt_user_octets_from_client{user="hello"} 6637101216 (6.18 GB)
telemt_user_octets_to_client{user="hello"} 190292172716 (177.22 GB)
telemt_user_unique_ips_current{user="hello"} 506
telemt_user_unique_ips_recent_window{user="hello"} 233
```

## server2

```
telemt 3.3.18

telemt_uptime_seconds 34037.6 (9h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 230224
telemt_connections_bad_total 18359
telemt_handshake_timeouts_total 8985
telemt_upstream_connect_attempt_total 9358
telemt_upstream_connect_success_total 9311
telemt_upstream_connect_fail_total 47
telemt_upstream_connect_attempts_per_request{bucket="1"} 9358
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5052
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4189
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 19
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 51
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 47
telemt_me_keepalive_timeout_total 15
telemt_me_reconnect_attempts_total 7341
telemt_me_reconnect_success_total 7298
telemt_me_reader_eof_total 7728
telemt_me_idle_close_by_peer_total 7728
telemt_me_route_drop_no_conn_total 60171
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 190726
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 16
telemt_me_endpoint_quarantine_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 715
telemt_desync_full_logged_total 239
telemt_desync_suppressed_total 476
telemt_desync_frames_bucket_total{bucket="1_2"} 195
telemt_desync_frames_bucket_total{bucket="3_10"} 282
telemt_desync_frames_bucket_total{bucket="gt_10"} 238
telemt_pool_swap_total 35
telemt_me_writer_removed_unexpected_total 7337
telemt_me_writer_restored_same_endpoint_total 7290
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 61
telemt_me_writer_removed_unexpected_minus_restored_total 39
telemt_user_connections_total{user="hello"} 191007
telemt_user_connections_current{user="hello"} 559
telemt_user_octets_from_client{user="hello"} 2984071807 (2.78 GB)
telemt_user_octets_to_client{user="hello"} 70522599040 (65.68 GB)
telemt_user_msgs_from_client{user="hello"} 620
telemt_user_msgs_to_client{user="hello"} 1332
telemt_user_unique_ips_current{user="hello"} 185
telemt_user_unique_ips_recent_window{user="hello"} 101
```

## server3

```
telemt 3.3.18

telemt_uptime_seconds 34037.7 (9h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 422675
telemt_connections_bad_total 12153
telemt_handshake_timeouts_total 40316
telemt_upstream_connect_attempt_total 7660
telemt_upstream_connect_success_total 7627
telemt_upstream_connect_fail_total 33
telemt_upstream_connect_attempts_per_request{bucket="1"} 7660
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4030
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3562
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 35
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 33
telemt_me_reconnect_attempts_total 5960
telemt_me_reconnect_success_total 5926
telemt_me_reader_eof_total 6276
telemt_me_idle_close_by_peer_total 6276
telemt_me_route_drop_no_conn_total 110192
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 342502
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 665
telemt_desync_full_logged_total 263
telemt_desync_suppressed_total 402
telemt_desync_frames_bucket_total{bucket="1_2"} 157
telemt_desync_frames_bucket_total{bucket="3_10"} 232
telemt_desync_frames_bucket_total{bucket="gt_10"} 276
telemt_pool_swap_total 35
telemt_me_writer_removed_unexpected_total 5995
telemt_me_writer_restored_same_endpoint_total 5907
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 242
telemt_me_writer_removed_unexpected_minus_restored_total 69
telemt_user_connections_total{user="hello"} 342288
telemt_user_connections_current{user="hello"} 994
telemt_user_octets_from_client{user="hello"} 5221463548 (4.86 GB)
telemt_user_octets_to_client{user="hello"} 141279245560 (131.58 GB)
telemt_user_unique_ips_current{user="hello"} 306
telemt_user_unique_ips_recent_window{user="hello"} 165
```

## server4

```
telemt 3.3.18

telemt_uptime_seconds 34037.6 (9h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 274166
telemt_connections_bad_total 45654
telemt_handshake_timeouts_total 18962
telemt_upstream_connect_attempt_total 10961
telemt_upstream_connect_success_total 10706
telemt_upstream_connect_fail_total 255
telemt_upstream_connect_attempts_per_request{bucket="1"} 10961
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5051
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5652
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 255
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 21650
telemt_me_reconnect_success_total 9014
telemt_me_reader_eof_total 9689
telemt_me_idle_close_by_peer_total 9689
telemt_me_seq_mismatch_total 11
telemt_me_route_drop_no_conn_total 68768
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 203398
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 28
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 375
telemt_desync_full_logged_total 96
telemt_desync_suppressed_total 279
telemt_desync_frames_bucket_total{bucket="1_2"} 95
telemt_desync_frames_bucket_total{bucket="3_10"} 159
telemt_desync_frames_bucket_total{bucket="gt_10"} 121
telemt_pool_swap_total 15
telemt_me_writer_removed_unexpected_total 9482
telemt_me_refill_failed_total 394
telemt_me_writer_restored_same_endpoint_total 8988
telemt_me_writer_restored_fallback_total 26
telemt_me_async_recovery_trigger_total 96
telemt_me_writer_removed_unexpected_minus_restored_total 468
telemt_user_connections_total{user="hello"} 203399
telemt_user_connections_current{user="hello"} 474
telemt_user_octets_from_client{user="hello"} 1759277284 (1.64 GB)
telemt_user_octets_to_client{user="hello"} 67780459144 (63.13 GB)
telemt_user_unique_ips_current{user="hello"} 169
telemt_user_unique_ips_recent_window{user="hello"} 78
```

## server5

```
telemt 3.3.18

telemt_uptime_seconds 34038.4 (9h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 212126
telemt_connections_bad_total 452
telemt_handshake_timeouts_total 2049
telemt_upstream_connect_attempt_total 7493
telemt_upstream_connect_success_total 7463
telemt_upstream_connect_fail_total 30
telemt_upstream_connect_attempts_per_request{bucket="1"} 7493
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3329
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4129
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 30
telemt_me_reconnect_attempts_total 5799
telemt_me_reconnect_success_total 5772
telemt_me_reader_eof_total 6164
telemt_me_idle_close_by_peer_total 6164
telemt_me_route_drop_no_conn_total 64521
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 198693
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 841
telemt_desync_full_logged_total 266
telemt_desync_suppressed_total 575
telemt_desync_frames_bucket_total{bucket="1_2"} 247
telemt_desync_frames_bucket_total{bucket="3_10"} 353
telemt_desync_frames_bucket_total{bucket="gt_10"} 241
telemt_pool_swap_total 37
telemt_me_writer_removed_unexpected_total 5830
telemt_me_writer_restored_same_endpoint_total 5764
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 54
telemt_me_writer_removed_unexpected_minus_restored_total 58
telemt_user_connections_total{user="hello"} 198700
telemt_user_connections_current{user="hello"} 630
telemt_user_octets_from_client{user="hello"} 2054121072 (1.91 GB)
telemt_user_octets_to_client{user="hello"} 81536953952 (75.94 GB)
telemt_user_unique_ips_current{user="hello"} 193
telemt_user_unique_ips_recent_window{user="hello"} 86
```