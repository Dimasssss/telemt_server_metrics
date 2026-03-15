# Server Metrics 2026-03-15 08:58:23 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.18

telemt_uptime_seconds 38629.4 (10h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 810394
telemt_connections_bad_total 34950
telemt_handshake_timeouts_total 5968
telemt_upstream_connect_attempt_total 7835
telemt_upstream_connect_success_total 7802
telemt_upstream_connect_fail_total 33
telemt_upstream_connect_attempts_per_request{bucket="1"} 7835
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4084
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3703
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 15
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 33
telemt_me_keepalive_timeout_total 8
telemt_me_reconnect_attempts_total 5918
telemt_me_reconnect_success_total 5887
telemt_me_reader_eof_total 6229
telemt_me_idle_close_by_peer_total 6229
telemt_me_route_drop_no_conn_total 263388
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 687153
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2176
telemt_desync_full_logged_total 672
telemt_desync_suppressed_total 1504
telemt_desync_frames_bucket_total{bucket="1_2"} 492
telemt_desync_frames_bucket_total{bucket="3_10"} 795
telemt_desync_frames_bucket_total{bucket="gt_10"} 889
telemt_pool_swap_total 35
telemt_me_writer_removed_unexpected_total 5967
telemt_me_writer_restored_same_endpoint_total 5876
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 296
telemt_me_writer_removed_unexpected_minus_restored_total 80
telemt_user_connections_total{user="hello"} 687137
telemt_user_connections_current{user="hello"} 2016
telemt_user_octets_from_client{user="hello"} 9242965812 (8.61 GB)
telemt_user_octets_to_client{user="hello"} 258409252112 (240.66 GB)
telemt_user_unique_ips_current{user="hello"} 558
telemt_user_unique_ips_recent_window{user="hello"} 242
```

## server2

```
telemt 3.3.18

telemt_uptime_seconds 38635.9 (10h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 320180
telemt_connections_bad_total 18570
telemt_handshake_timeouts_total 12850
telemt_upstream_connect_attempt_total 10359
telemt_upstream_connect_success_total 10308
telemt_upstream_connect_fail_total 51
telemt_upstream_connect_attempts_per_request{bucket="1"} 10359
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5605
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4617
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 25
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 61
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 51
telemt_me_keepalive_timeout_total 15
telemt_me_reconnect_attempts_total 8116
telemt_me_reconnect_success_total 8067
telemt_me_reader_eof_total 8539
telemt_me_idle_close_by_peer_total 8539
telemt_me_route_drop_no_conn_total 80635
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 253260
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 16
telemt_me_endpoint_quarantine_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 938
telemt_desync_full_logged_total 316
telemt_desync_suppressed_total 622
telemt_desync_frames_bucket_total{bucket="1_2"} 287
telemt_desync_frames_bucket_total{bucket="3_10"} 355
telemt_desync_frames_bucket_total{bucket="gt_10"} 296
telemt_pool_swap_total 37
telemt_me_writer_removed_unexpected_total 8133
telemt_me_writer_restored_same_endpoint_total 8059
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 61
telemt_me_writer_removed_unexpected_minus_restored_total 66
telemt_user_connections_total{user="hello"} 253534
telemt_user_connections_current{user="hello"} 671
telemt_user_octets_from_client{user="hello"} 3677519391 (3.42 GB)
telemt_user_octets_to_client{user="hello"} 95760688720 (89.18 GB)
telemt_user_msgs_from_client{user="hello"} 620
telemt_user_msgs_to_client{user="hello"} 1332
telemt_user_unique_ips_current{user="hello"} 208
telemt_user_unique_ips_recent_window{user="hello"} 109
```

## server3

```
telemt 3.3.18

telemt_uptime_seconds 38630.4 (10h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 553101
telemt_connections_bad_total 17798
telemt_handshake_timeouts_total 49629
telemt_upstream_connect_attempt_total 8544
telemt_upstream_connect_success_total 8507
telemt_upstream_connect_fail_total 37
telemt_upstream_connect_attempts_per_request{bucket="1"} 8544
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4469
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3989
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 49
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 37
telemt_me_reconnect_attempts_total 6622
telemt_me_reconnect_success_total 6579
telemt_me_reader_eof_total 6973
telemt_me_idle_close_by_peer_total 6973
telemt_me_route_drop_no_conn_total 154068
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 443366
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 923
telemt_desync_full_logged_total 352
telemt_desync_suppressed_total 571
telemt_desync_frames_bucket_total{bucket="1_2"} 204
telemt_desync_frames_bucket_total{bucket="3_10"} 329
telemt_desync_frames_bucket_total{bucket="gt_10"} 390
telemt_pool_swap_total 39
telemt_me_writer_removed_unexpected_total 6661
telemt_me_writer_restored_same_endpoint_total 6560
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 242
telemt_me_writer_removed_unexpected_minus_restored_total 82
telemt_user_connections_total{user="hello"} 442899
telemt_user_connections_current{user="hello"} 1149
telemt_user_octets_from_client{user="hello"} 6584159624 (6.13 GB)
telemt_user_octets_to_client{user="hello"} 181748663996 (169.27 GB)
telemt_user_unique_ips_current{user="hello"} 346
telemt_user_unique_ips_recent_window{user="hello"} 179
```

## server4

```
telemt 3.3.18

telemt_uptime_seconds 38630.1 (10h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 344896
telemt_connections_bad_total 51033
telemt_handshake_timeouts_total 23011
telemt_upstream_connect_attempt_total 12344
telemt_upstream_connect_success_total 12059
telemt_upstream_connect_fail_total 285
telemt_upstream_connect_attempts_per_request{bucket="1"} 12344
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5619
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6437
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 285
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 23966
telemt_me_reconnect_success_total 10138
telemt_me_reader_eof_total 10877
telemt_me_idle_close_by_peer_total 10877
telemt_me_seq_mismatch_total 14
telemt_me_route_drop_no_conn_total 91429
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 256437
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 31
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 613
telemt_desync_full_logged_total 155
telemt_desync_suppressed_total 458
telemt_desync_frames_bucket_total{bucket="1_2"} 144
telemt_desync_frames_bucket_total{bucket="3_10"} 264
telemt_desync_frames_bucket_total{bucket="gt_10"} 205
telemt_pool_swap_total 16
telemt_me_writer_removed_unexpected_total 10654
telemt_me_refill_failed_total 431
telemt_me_writer_restored_same_endpoint_total 10108
telemt_me_writer_restored_fallback_total 30
telemt_me_async_recovery_trigger_total 96
telemt_me_writer_removed_unexpected_minus_restored_total 516
telemt_user_connections_total{user="hello"} 256440
telemt_user_connections_current{user="hello"} 485
telemt_user_octets_from_client{user="hello"} 2377719688 (2.21 GB)
telemt_user_octets_to_client{user="hello"} 83346817444 (77.62 GB)
telemt_user_unique_ips_current{user="hello"} 173
telemt_user_unique_ips_recent_window{user="hello"} 95
```

## server5

```
telemt 3.3.18

telemt_uptime_seconds 38631.0 (10h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 311480
telemt_connections_bad_total 3820
telemt_handshake_timeouts_total 3543
telemt_upstream_connect_attempt_total 8547
telemt_upstream_connect_success_total 8511
telemt_upstream_connect_fail_total 36
telemt_upstream_connect_attempts_per_request{bucket="1"} 8547
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3857
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4649
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 36
telemt_me_reconnect_attempts_total 6628
telemt_me_reconnect_success_total 6598
telemt_me_reader_eof_total 7026
telemt_me_idle_close_by_peer_total 7026
telemt_me_route_drop_no_conn_total 86276
telemt_me_route_drop_channel_closed_total 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 267591
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1053
telemt_desync_full_logged_total 345
telemt_desync_suppressed_total 708
telemt_desync_frames_bucket_total{bucket="1_2"} 315
telemt_desync_frames_bucket_total{bucket="3_10"} 435
telemt_desync_frames_bucket_total{bucket="gt_10"} 303
telemt_pool_swap_total 39
telemt_me_writer_removed_unexpected_total 6663
telemt_me_writer_restored_same_endpoint_total 6590
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 54
telemt_me_writer_removed_unexpected_minus_restored_total 65
telemt_user_connections_total{user="hello"} 267596
telemt_user_connections_current{user="hello"} 718
telemt_user_octets_from_client{user="hello"} 3046348848 (2.84 GB)
telemt_user_octets_to_client{user="hello"} 102246834832 (95.22 GB)
telemt_user_unique_ips_current{user="hello"} 198
telemt_user_unique_ips_recent_window{user="hello"} 96
```