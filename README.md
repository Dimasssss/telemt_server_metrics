# Server Metrics 2026-03-11 00:10:43 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 35018.7 (9h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 778843
telemt_connections_bad_total 9521
telemt_handshake_timeouts_total 8933
telemt_upstream_connect_attempt_total 7583
telemt_upstream_connect_success_total 7574
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 7583
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3781
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3735
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 57
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 468
telemt_me_reconnect_attempts_total 17430
telemt_me_reconnect_success_total 5767
telemt_me_reader_eof_total 6331
telemt_me_idle_close_by_peer_total 6331
telemt_me_route_drop_no_conn_total 321499
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 736893
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3541
telemt_desync_full_logged_total 990
telemt_desync_suppressed_total 2551
telemt_desync_frames_bucket_total{bucket="1_2"} 1026
telemt_desync_frames_bucket_total{bucket="3_10"} 1319
telemt_desync_frames_bucket_total{bucket="gt_10"} 1196
telemt_pool_swap_total 18
telemt_me_writer_removed_unexpected_total 6180
telemt_me_refill_failed_total 363
telemt_me_writer_restored_same_endpoint_total 5761
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 413
telemt_user_connections_total{user="hello"} 736678
telemt_user_connections_current{user="hello"} 395
telemt_user_octets_from_client{user="hello"} 10187628344 (9.49 GB)
telemt_user_octets_to_client{user="hello"} 219407422516 (204.34 GB)
telemt_user_unique_ips_current{user="hello"} 145
telemt_user_unique_ips_recent_window{user="hello"} 67
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 35075.4 (9h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 336199
telemt_connections_bad_total 2383
telemt_handshake_timeouts_total 17626
telemt_upstream_connect_attempt_total 14521
telemt_upstream_connect_success_total 11643
telemt_upstream_connect_fail_total 2878
telemt_upstream_connect_attempts_per_request{bucket="1"} 14521
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4998
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4405
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 209
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2031
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2878
telemt_me_keepalive_timeout_total 1703
telemt_me_reconnect_attempts_total 7733
telemt_me_reconnect_success_total 6921
telemt_me_reader_eof_total 7291
telemt_me_idle_close_by_peer_total 7289
telemt_me_route_drop_no_conn_total 171302
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 285746
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1736
telemt_desync_full_logged_total 484
telemt_desync_suppressed_total 1252
telemt_desync_frames_bucket_total{bucket="1_2"} 527
telemt_desync_frames_bucket_total{bucket="3_10"} 615
telemt_desync_frames_bucket_total{bucket="gt_10"} 594
telemt_pool_swap_total 26
telemt_me_writer_removed_unexpected_total 7019
telemt_me_refill_failed_total 22
telemt_me_writer_restored_same_endpoint_total 6900
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 86
telemt_me_writer_removed_unexpected_minus_restored_total 98
telemt_user_connections_total{user="hello"} 288015
telemt_user_connections_current{user="hello"} 151
telemt_user_octets_from_client{user="hello"} 2788724938 (2.60 GB)
telemt_user_octets_to_client{user="hello"} 69408642304 (64.64 GB)
telemt_user_msgs_from_client{user="hello"} 7933
telemt_user_msgs_to_client{user="hello"} 11226
telemt_user_unique_ips_current{user="hello"} 65
telemt_user_unique_ips_recent_window{user="hello"} 35
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 35075.2 (9h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 558977
telemt_connections_bad_total 3861
telemt_handshake_timeouts_total 34023
telemt_upstream_connect_attempt_total 9579
telemt_upstream_connect_success_total 9445
telemt_upstream_connect_fail_total 134
telemt_upstream_connect_attempts_per_request{bucket="1"} 9579
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5342
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4039
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 64
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 134
telemt_me_keepalive_timeout_total 501
telemt_me_reconnect_attempts_total 17656
telemt_me_reconnect_success_total 6597
telemt_me_reader_eof_total 7197
telemt_me_idle_close_by_peer_total 7197
telemt_me_route_drop_no_conn_total 192645
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 492607
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1521
telemt_desync_full_logged_total 434
telemt_desync_suppressed_total 1087
telemt_desync_frames_bucket_total{bucket="1_2"} 343
telemt_desync_frames_bucket_total{bucket="3_10"} 523
telemt_desync_frames_bucket_total{bucket="gt_10"} 655
telemt_pool_swap_total 19
telemt_me_writer_removed_unexpected_total 7038
telemt_me_refill_failed_total 343
telemt_me_writer_restored_same_endpoint_total 6586
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 441
telemt_user_connections_total{user="hello"} 493532
telemt_user_connections_current{user="hello"} 180
telemt_user_octets_from_client{user="hello"} 6775697821 (6.31 GB)
telemt_user_octets_to_client{user="hello"} 152795136937 (142.30 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 89
telemt_user_unique_ips_recent_window{user="hello"} 43
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 35075.7 (9h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 404978
telemt_connections_bad_total 33457
telemt_handshake_timeouts_total 37529
telemt_upstream_connect_attempt_total 9864
telemt_upstream_connect_success_total 9864
telemt_upstream_connect_attempts_per_request{bucket="1"} 9864
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5570
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4293
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 394
telemt_me_reconnect_attempts_total 9119
telemt_me_reconnect_success_total 8089
telemt_me_reader_eof_total 8525
telemt_me_idle_close_by_peer_total 8525
telemt_me_seq_mismatch_total 4
telemt_me_route_drop_no_conn_total 125921
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 321019
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 698
telemt_desync_full_logged_total 283
telemt_desync_suppressed_total 415
telemt_desync_frames_bucket_total{bucket="1_2"} 269
telemt_desync_frames_bucket_total{bucket="3_10"} 246
telemt_desync_frames_bucket_total{bucket="gt_10"} 183
telemt_pool_swap_total 27
telemt_me_writer_removed_unexpected_total 8202
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 8074
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 113
telemt_user_connections_total{user="hello"} 320694
telemt_user_connections_current{user="hello"} 173
telemt_user_octets_from_client{user="hello"} 4124571376 (3.84 GB)
telemt_user_octets_to_client{user="hello"} 89842705652 (83.67 GB)
telemt_user_unique_ips_current{user="hello"} 64
telemt_user_unique_ips_recent_window{user="hello"} 38
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 35075.3 (9h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 428559
telemt_connections_bad_total 3357
telemt_handshake_timeouts_total 2723
telemt_upstream_connect_attempt_total 10622
telemt_upstream_connect_success_total 10581
telemt_upstream_connect_fail_total 41
telemt_upstream_connect_attempts_per_request{bucket="1"} 10622
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5515
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4955
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 109
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 41
telemt_me_keepalive_timeout_total 500
telemt_me_reconnect_attempts_total 12537
telemt_me_reconnect_success_total 8772
telemt_me_reader_eof_total 9217
telemt_me_idle_close_by_peer_total 9217
telemt_me_route_drop_no_conn_total 144708
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 396480
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 2252
telemt_desync_full_logged_total 868
telemt_desync_suppressed_total 1384
telemt_desync_frames_bucket_total{bucket="1_2"} 829
telemt_desync_frames_bucket_total{bucket="3_10"} 966
telemt_desync_frames_bucket_total{bucket="gt_10"} 457
telemt_pool_swap_total 15
telemt_me_writer_removed_unexpected_total 9006
telemt_me_refill_failed_total 116
telemt_me_writer_restored_same_endpoint_total 8772
telemt_me_async_recovery_trigger_total 48
telemt_me_writer_removed_unexpected_minus_restored_total 234
telemt_user_connections_total{user="hello"} 396237
telemt_user_connections_current{user="hello"} 199
telemt_user_octets_from_client{user="hello"} 8302101036 (7.73 GB)
telemt_user_octets_to_client{user="hello"} 144898972144 (134.95 GB)
telemt_user_unique_ips_current{user="hello"} 77
telemt_user_unique_ips_recent_window{user="hello"} 40
```