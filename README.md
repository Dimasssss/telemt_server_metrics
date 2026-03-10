# Server Metrics 2026-03-10 18:34:31 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 14846.6 (4h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 487246
telemt_connections_bad_total 7985
telemt_handshake_timeouts_total 2362
telemt_upstream_connect_attempt_total 2984
telemt_upstream_connect_success_total 2975
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 2984
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1435
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1496
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 43
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 286
telemt_me_reconnect_attempts_total 12617
telemt_me_reconnect_success_total 2159
telemt_me_reader_eof_total 2465
telemt_me_idle_close_by_peer_total 2465
telemt_me_route_drop_no_conn_total 205451
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 459584
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2350
telemt_desync_full_logged_total 638
telemt_desync_suppressed_total 1712
telemt_desync_frames_bucket_total{bucket="1_2"} 630
telemt_desync_frames_bucket_total{bucket="3_10"} 906
telemt_desync_frames_bucket_total{bucket="gt_10"} 814
telemt_pool_swap_total 2
telemt_me_writer_removed_unexpected_total 2493
telemt_me_refill_failed_total 326
telemt_me_writer_restored_same_endpoint_total 2153
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 334
telemt_user_connections_total{user="hello"} 459498
telemt_user_connections_current{user="hello"} 1247
telemt_user_octets_from_client{user="hello"} 6376764556 (5.94 GB)
telemt_user_octets_to_client{user="hello"} 133341615224 (124.18 GB)
telemt_user_unique_ips_current{user="hello"} 339
telemt_user_unique_ips_recent_window{user="hello"} 175
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 14903.5 (4h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 212791
telemt_connections_bad_total 1806
telemt_handshake_timeouts_total 13546
telemt_upstream_connect_attempt_total 8068
telemt_upstream_connect_success_total 5325
telemt_upstream_connect_fail_total 2743
telemt_upstream_connect_attempts_per_request{bucket="1"} 8068
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1687
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1603
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 165
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1870
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2743
telemt_me_keepalive_timeout_total 617
telemt_me_reconnect_attempts_total 2625
telemt_me_reconnect_success_total 2547
telemt_me_reader_eof_total 2652
telemt_me_idle_close_by_peer_total 2650
telemt_me_route_drop_no_conn_total 124571
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 179867
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 705
telemt_desync_full_logged_total 218
telemt_desync_suppressed_total 487
telemt_desync_frames_bucket_total{bucket="1_2"} 256
telemt_desync_frames_bucket_total{bucket="3_10"} 239
telemt_desync_frames_bucket_total{bucket="gt_10"} 210
telemt_pool_swap_total 10
telemt_me_writer_removed_unexpected_total 2577
telemt_me_writer_restored_same_endpoint_total 2526
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 86
telemt_me_writer_removed_unexpected_minus_restored_total 30
telemt_user_connections_total{user="hello"} 181825
telemt_user_connections_current{user="hello"} 425
telemt_user_octets_from_client{user="hello"} 1974212358 (1.84 GB)
telemt_user_octets_to_client{user="hello"} 42683235958 (39.75 GB)
telemt_user_msgs_from_client{user="hello"} 5318
telemt_user_msgs_to_client{user="hello"} 5495
telemt_user_unique_ips_current{user="hello"} 126
telemt_user_unique_ips_recent_window{user="hello"} 78
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 14903.4 (4h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 356575
telemt_connections_bad_total 1071
telemt_handshake_timeouts_total 31787
telemt_upstream_connect_attempt_total 4826
telemt_upstream_connect_success_total 4750
telemt_upstream_connect_fail_total 76
telemt_upstream_connect_attempts_per_request{bucket="1"} 4826
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2863
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1859
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 28
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 76
telemt_me_keepalive_timeout_total 96
telemt_me_reconnect_attempts_total 5003
telemt_me_reconnect_success_total 2902
telemt_me_reader_eof_total 3062
telemt_me_idle_close_by_peer_total 3062
telemt_me_route_drop_no_conn_total 117873
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 299658
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 922
telemt_desync_full_logged_total 264
telemt_desync_suppressed_total 658
telemt_desync_frames_bucket_total{bucket="1_2"} 232
telemt_desync_frames_bucket_total{bucket="3_10"} 311
telemt_desync_frames_bucket_total{bucket="gt_10"} 379
telemt_pool_swap_total 7
telemt_me_writer_removed_unexpected_total 3019
telemt_me_refill_failed_total 64
telemt_me_writer_restored_same_endpoint_total 2891
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 117
telemt_user_connections_total{user="hello"} 300616
telemt_user_connections_current{user="hello"} 838
telemt_user_octets_from_client{user="hello"} 4199353269 (3.91 GB)
telemt_user_octets_to_client{user="hello"} 94643531233 (88.14 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 220
telemt_user_unique_ips_recent_window{user="hello"} 134
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 14903.9 (4h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 231189
telemt_connections_bad_total 14595
telemt_handshake_timeouts_total 20987
telemt_upstream_connect_attempt_total 3838
telemt_upstream_connect_success_total 3838
telemt_upstream_connect_attempts_per_request{bucket="1"} 3838
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2051
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1786
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 68
telemt_me_reconnect_attempts_total 3065
telemt_me_reconnect_success_total 3047
telemt_me_reader_eof_total 3162
telemt_me_idle_close_by_peer_total 3162
telemt_me_seq_mismatch_total 1
telemt_me_route_drop_no_conn_total 76232
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 186031
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 512
telemt_desync_full_logged_total 204
telemt_desync_suppressed_total 308
telemt_desync_frames_bucket_total{bucket="1_2"} 171
telemt_desync_frames_bucket_total{bucket="3_10"} 185
telemt_desync_frames_bucket_total{bucket="gt_10"} 156
telemt_pool_swap_total 10
telemt_me_writer_removed_unexpected_total 3073
telemt_me_writer_restored_same_endpoint_total 3035
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 26
telemt_user_connections_total{user="hello"} 185824
telemt_user_connections_current{user="hello"} 454
telemt_user_octets_from_client{user="hello"} 2784823744 (2.59 GB)
telemt_user_octets_to_client{user="hello"} 51970700932 (48.40 GB)
telemt_user_unique_ips_current{user="hello"} 130
telemt_user_unique_ips_recent_window{user="hello"} 80
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 14903.6 (4h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 244453
telemt_connections_bad_total 800
telemt_handshake_timeouts_total 1749
telemt_upstream_connect_attempt_total 4533
telemt_upstream_connect_success_total 4518
telemt_upstream_connect_fail_total 15
telemt_upstream_connect_attempts_per_request{bucket="1"} 4533
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2326
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2141
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 50
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 15
telemt_me_keepalive_timeout_total 94
telemt_me_reconnect_attempts_total 3736
telemt_me_reconnect_success_total 3706
telemt_me_reader_eof_total 3819
telemt_me_idle_close_by_peer_total 3819
telemt_me_route_drop_no_conn_total 90672
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 230413
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 1289
telemt_desync_full_logged_total 456
telemt_desync_suppressed_total 833
telemt_desync_frames_bucket_total{bucket="1_2"} 526
telemt_desync_frames_bucket_total{bucket="3_10"} 539
telemt_desync_frames_bucket_total{bucket="gt_10"} 224
telemt_pool_swap_total 5
telemt_me_writer_removed_unexpected_total 3752
telemt_me_writer_restored_same_endpoint_total 3706
telemt_me_async_recovery_trigger_total 48
telemt_me_writer_removed_unexpected_minus_restored_total 46
telemt_user_connections_total{user="hello"} 230348
telemt_user_connections_current{user="hello"} 622
telemt_user_octets_from_client{user="hello"} 4920238008 (4.58 GB)
telemt_user_octets_to_client{user="hello"} 73400218804 (68.36 GB)
telemt_user_unique_ips_current{user="hello"} 164
telemt_user_unique_ips_recent_window{user="hello"} 103
```