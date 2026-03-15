# Server Metrics 2026-03-15 10:04:48 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.18

telemt_uptime_seconds 42617.8 (11h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 995819
telemt_connections_bad_total 54084
telemt_handshake_timeouts_total 7755
telemt_upstream_connect_attempt_total 8541
telemt_upstream_connect_success_total 8503
telemt_upstream_connect_fail_total 38
telemt_upstream_connect_attempts_per_request{bucket="1"} 8541
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4475
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4009
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 19
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 38
telemt_me_keepalive_timeout_total 8
telemt_me_reconnect_attempts_total 6401
telemt_me_reconnect_success_total 6363
telemt_me_reader_eof_total 6733
telemt_me_idle_close_by_peer_total 6733
telemt_me_route_drop_no_conn_total 329305
telemt_me_route_drop_channel_closed_total 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 841607
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3062
telemt_desync_full_logged_total 876
telemt_desync_suppressed_total 2186
telemt_desync_frames_bucket_total{bucket="1_2"} 726
telemt_desync_frames_bucket_total{bucket="3_10"} 1204
telemt_desync_frames_bucket_total{bucket="gt_10"} 1132
telemt_pool_swap_total 38
telemt_me_writer_removed_unexpected_total 6454
telemt_me_writer_restored_same_endpoint_total 6352
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 296
telemt_me_writer_removed_unexpected_minus_restored_total 91
telemt_user_connections_total{user="hello"} 841612
telemt_user_connections_current{user="hello"} 2186
telemt_user_octets_from_client{user="hello"} 12181968252 (11.35 GB)
telemt_user_octets_to_client{user="hello"} 324425223176 (302.14 GB)
telemt_user_unique_ips_current{user="hello"} 598
telemt_user_unique_ips_recent_window{user="hello"} 313
```

## server2

```
telemt 3.3.18

telemt_uptime_seconds 42618.9 (11h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 392959
telemt_connections_bad_total 21873
telemt_handshake_timeouts_total 15465
telemt_upstream_connect_attempt_total 11349
telemt_upstream_connect_success_total 11289
telemt_upstream_connect_fail_total 59
telemt_upstream_connect_attempts_per_request{bucket="1"} 11348
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6113
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5082
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 28
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 66
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 59
telemt_me_keepalive_timeout_total 15
telemt_me_reconnect_attempts_total 8877
telemt_me_reconnect_success_total 8820
telemt_me_reader_eof_total 9346
telemt_me_idle_close_by_peer_total 9346
telemt_me_route_drop_no_conn_total 100231
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 311154
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 16
telemt_me_endpoint_quarantine_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1111
telemt_desync_full_logged_total 384
telemt_desync_suppressed_total 727
telemt_desync_frames_bucket_total{bucket="1_2"} 370
telemt_desync_frames_bucket_total{bucket="3_10"} 409
telemt_desync_frames_bucket_total{bucket="gt_10"} 332
telemt_pool_swap_total 40
telemt_me_writer_removed_unexpected_total 8904
telemt_me_writer_restored_same_endpoint_total 8812
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 61
telemt_me_writer_removed_unexpected_minus_restored_total 84
telemt_user_connections_total{user="hello"} 311440
telemt_user_connections_current{user="hello"} 678
telemt_user_octets_from_client{user="hello"} 4541455267 (4.23 GB)
telemt_user_octets_to_client{user="hello"} 117959560556 (109.86 GB)
telemt_user_msgs_from_client{user="hello"} 620
telemt_user_msgs_to_client{user="hello"} 1332
telemt_user_unique_ips_current{user="hello"} 221
telemt_user_unique_ips_recent_window{user="hello"} 125
```

## server3

```
telemt 3.3.18

telemt_uptime_seconds 42618.8 (11h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 722270
telemt_connections_bad_total 24286
telemt_handshake_timeouts_total 72495
telemt_upstream_connect_attempt_total 9453
telemt_upstream_connect_success_total 9413
telemt_upstream_connect_fail_total 40
telemt_upstream_connect_attempts_per_request{bucket="1"} 9453
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4918
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4444
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 51
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 40
telemt_me_reconnect_attempts_total 7305
telemt_me_reconnect_success_total 7259
telemt_me_reader_eof_total 7686
telemt_me_idle_close_by_peer_total 7686
telemt_me_route_drop_no_conn_total 208151
telemt_me_route_drop_channel_closed_total 15
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 545841
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1193
telemt_desync_full_logged_total 445
telemt_desync_suppressed_total 748
telemt_desync_frames_bucket_total{bucket="1_2"} 263
telemt_desync_frames_bucket_total{bucket="3_10"} 434
telemt_desync_frames_bucket_total{bucket="gt_10"} 496
telemt_pool_swap_total 42
telemt_me_writer_removed_unexpected_total 7351
telemt_me_writer_restored_same_endpoint_total 7240
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 242
telemt_me_writer_removed_unexpected_minus_restored_total 92
telemt_user_connections_total{user="hello"} 545267
telemt_user_connections_current{user="hello"} 1299
telemt_user_octets_from_client{user="hello"} 8124676944 (7.57 GB)
telemt_user_octets_to_client{user="hello"} 217816774084 (202.86 GB)
telemt_user_unique_ips_current{user="hello"} 363
telemt_user_unique_ips_recent_window{user="hello"} 205
```

## server4

```
telemt 3.3.18

telemt_uptime_seconds 42618.7 (11h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 413267
telemt_connections_bad_total 54484
telemt_handshake_timeouts_total 24905
telemt_upstream_connect_attempt_total 13039
telemt_upstream_connect_success_total 12717
telemt_upstream_connect_fail_total 322
telemt_upstream_connect_attempts_per_request{bucket="1"} 13039
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6003
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6711
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 322
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 30929
telemt_me_reconnect_success_total 10570
telemt_me_reader_eof_total 11520
telemt_me_idle_close_by_peer_total 11520
telemt_me_seq_mismatch_total 16
telemt_me_route_drop_no_conn_total 114226
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 309805
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 33
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 738
telemt_desync_full_logged_total 182
telemt_desync_suppressed_total 556
telemt_desync_frames_bucket_total{bucket="1_2"} 176
telemt_desync_frames_bucket_total{bucket="3_10"} 303
telemt_desync_frames_bucket_total{bucket="gt_10"} 259
telemt_pool_swap_total 16
telemt_me_writer_removed_unexpected_total 11299
telemt_me_refill_failed_total 636
telemt_me_writer_restored_same_endpoint_total 10540
telemt_me_writer_restored_fallback_total 30
telemt_me_async_recovery_trigger_total 96
telemt_me_writer_removed_unexpected_minus_restored_total 729
telemt_user_connections_total{user="hello"} 309717
telemt_user_connections_current{user="hello"} 604
telemt_user_octets_from_client{user="hello"} 3683464204 (3.43 GB)
telemt_user_octets_to_client{user="hello"} 99688569328 (92.84 GB)
telemt_user_unique_ips_current{user="hello"} 205
telemt_user_unique_ips_recent_window{user="hello"} 109
```

## server5

```
telemt 3.3.18

telemt_uptime_seconds 42619.5 (11h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 404309
telemt_connections_bad_total 4688
telemt_handshake_timeouts_total 5569
telemt_upstream_connect_attempt_total 9550
telemt_upstream_connect_success_total 9505
telemt_upstream_connect_fail_total 45
telemt_upstream_connect_attempts_per_request{bucket="1"} 9550
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4322
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5178
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 45
telemt_me_reconnect_attempts_total 7400
telemt_me_reconnect_success_total 7364
telemt_me_reader_eof_total 7836
telemt_me_idle_close_by_peer_total 7836
telemt_me_route_drop_no_conn_total 106530
telemt_me_route_drop_channel_closed_total 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 336080
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1276
telemt_desync_full_logged_total 410
telemt_desync_suppressed_total 866
telemt_desync_frames_bucket_total{bucket="1_2"} 380
telemt_desync_frames_bucket_total{bucket="3_10"} 522
telemt_desync_frames_bucket_total{bucket="gt_10"} 374
telemt_pool_swap_total 41
telemt_me_writer_removed_unexpected_total 7445
telemt_me_writer_restored_same_endpoint_total 7356
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 54
telemt_me_writer_removed_unexpected_minus_restored_total 81
telemt_user_connections_total{user="hello"} 336083
telemt_user_connections_current{user="hello"} 918
telemt_user_octets_from_client{user="hello"} 4110120996 (3.83 GB)
telemt_user_octets_to_client{user="hello"} 123911592120 (115.40 GB)
telemt_user_unique_ips_current{user="hello"} 215
telemt_user_unique_ips_recent_window{user="hello"} 123
```