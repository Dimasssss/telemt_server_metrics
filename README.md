# Server Metrics 2026-03-12 13:48:54 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 28214.5 (7h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 990496
telemt_connections_bad_total 10345
telemt_handshake_timeouts_total 9639
telemt_upstream_connect_attempt_total 5601
telemt_upstream_connect_success_total 5567
telemt_upstream_connect_fail_total 34
telemt_upstream_connect_attempts_per_request{bucket="1"} 5601
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2998
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2561
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 34
telemt_me_keepalive_timeout_total 359
telemt_me_reconnect_attempts_total 8011
telemt_me_reconnect_success_total 4112
telemt_me_reader_eof_total 4395
telemt_me_idle_close_by_peer_total 4394
telemt_me_route_drop_no_conn_total 349622
telemt_me_route_drop_channel_closed_total 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 940712
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4993
telemt_desync_full_logged_total 1262
telemt_desync_suppressed_total 3731
telemt_desync_frames_bucket_total{bucket="1_2"} 1247
telemt_desync_frames_bucket_total{bucket="3_10"} 1806
telemt_desync_frames_bucket_total{bucket="gt_10"} 1940
telemt_pool_swap_total 19
telemt_me_writer_removed_unexpected_total 4279
telemt_me_refill_failed_total 121
telemt_me_writer_restored_same_endpoint_total 4099
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 167
telemt_user_connections_total{user="hello"} 940529
telemt_user_connections_current{user="hello"} 1591
telemt_user_octets_from_client{user="hello"} 15617750964 (14.55 GB)
telemt_user_octets_to_client{user="hello"} 279323143384 (260.14 GB)
telemt_user_unique_ips_current{user="hello"} 429
telemt_user_unique_ips_recent_window{user="hello"} 217
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 57834.9 (16h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 475574
telemt_connections_bad_total 5313
telemt_handshake_timeouts_total 24969
telemt_upstream_connect_attempt_total 13929
telemt_upstream_connect_success_total 13922
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 13929
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6865
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7041
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 16
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_keepalive_timeout_total 1112
telemt_me_reconnect_attempts_total 10899
telemt_me_reconnect_success_total 10839
telemt_me_reader_eof_total 11531
telemt_me_idle_close_by_peer_total 11531
telemt_me_route_drop_no_conn_total 137104
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 421575
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1450
telemt_desync_full_logged_total 466
telemt_desync_suppressed_total 984
telemt_desync_frames_bucket_total{bucket="1_2"} 609
telemt_desync_frames_bucket_total{bucket="3_10"} 492
telemt_desync_frames_bucket_total{bucket="gt_10"} 349
telemt_pool_swap_total 60
telemt_me_writer_removed_unexpected_total 10938
telemt_me_writer_restored_same_endpoint_total 10830
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 99
telemt_user_connections_total{user="hello"} 422043
telemt_user_connections_current{user="hello"} 608
telemt_user_octets_from_client{user="hello"} 6517981315 (6.07 GB)
telemt_user_octets_to_client{user="hello"} 152677496706 (142.19 GB)
telemt_user_msgs_from_client{user="hello"} 353
telemt_user_msgs_to_client{user="hello"} 423
telemt_user_unique_ips_current{user="hello"} 170
telemt_user_unique_ips_recent_window{user="hello"} 80
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 57834.9 (16h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1036605
telemt_connections_bad_total 5511
telemt_handshake_timeouts_total 76477
telemt_upstream_connect_attempt_total 13885
telemt_upstream_connect_success_total 13880
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 13885
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7558
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6264
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 54
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 923
telemt_me_reconnect_attempts_total 10716
telemt_me_reconnect_success_total 10619
telemt_me_reader_eof_total 11191
telemt_me_idle_close_by_peer_total 11191
telemt_me_route_drop_no_conn_total 266945
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 735984
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3167
telemt_desync_full_logged_total 962
telemt_desync_suppressed_total 2205
telemt_desync_frames_bucket_total{bucket="1_2"} 458
telemt_desync_frames_bucket_total{bucket="3_10"} 1150
telemt_desync_frames_bucket_total{bucket="gt_10"} 1559
telemt_pool_swap_total 58
telemt_me_writer_removed_unexpected_total 10654
telemt_me_refill_failed_total 1
telemt_me_writer_restored_same_endpoint_total 10578
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 35
telemt_user_connections_total{user="hello"} 736183
telemt_user_connections_current{user="hello"} 995
telemt_user_octets_from_client{user="hello"} 9810457824 (9.14 GB)
telemt_user_octets_to_client{user="hello"} 238400498369 (222.03 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 291
telemt_user_unique_ips_recent_window{user="hello"} 159
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 57835.3 (16h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 596012
telemt_connections_bad_total 7677
telemt_handshake_timeouts_total 54835
telemt_upstream_connect_attempt_total 15411
telemt_upstream_connect_success_total 15349
telemt_upstream_connect_fail_total 62
telemt_upstream_connect_attempts_per_request{bucket="1"} 15411
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8712
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6624
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 13
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 62
telemt_me_keepalive_timeout_total 1311
telemt_me_reconnect_attempts_total 13677
telemt_me_reconnect_success_total 12443
telemt_me_reader_eof_total 13202
telemt_me_idle_close_by_peer_total 13202
telemt_me_route_drop_no_conn_total 200582
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 502301
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1013
telemt_desync_full_logged_total 356
telemt_desync_suppressed_total 657
telemt_desync_frames_bucket_total{bucket="1_2"} 286
telemt_desync_frames_bucket_total{bucket="3_10"} 420
telemt_desync_frames_bucket_total{bucket="gt_10"} 307
telemt_pool_swap_total 52
telemt_me_writer_removed_unexpected_total 12578
telemt_me_refill_failed_total 37
telemt_me_writer_restored_same_endpoint_total 12422
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 108
telemt_me_writer_removed_unexpected_minus_restored_total 135
telemt_user_connections_total{user="hello"} 501807
telemt_user_connections_current{user="hello"} 675
telemt_user_octets_from_client{user="hello"} 5545042448 (5.16 GB)
telemt_user_octets_to_client{user="hello"} 202890009748 (188.96 GB)
telemt_user_unique_ips_current{user="hello"} 187
telemt_user_unique_ips_recent_window{user="hello"} 94
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 57835.0 (16h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 672119
telemt_connections_bad_total 1749
telemt_handshake_timeouts_total 5433
telemt_upstream_connect_attempt_total 18310
telemt_upstream_connect_success_total 18088
telemt_upstream_connect_fail_total 222
telemt_upstream_connect_attempts_per_request{bucket="1"} 18310
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9203
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8785
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 93
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 222
telemt_me_keepalive_timeout_total 1025
telemt_me_reconnect_attempts_total 22408
telemt_me_reconnect_success_total 15181
telemt_me_reader_eof_total 15923
telemt_me_idle_close_by_peer_total 15923
telemt_me_seq_mismatch_total 24
telemt_me_route_drop_no_conn_total 229490
telemt_me_route_drop_channel_closed_total 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 625714
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 28
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 2597
telemt_desync_full_logged_total 871
telemt_desync_suppressed_total 1726
telemt_desync_frames_bucket_total{bucket="1_2"} 722
telemt_desync_frames_bucket_total{bucket="3_10"} 914
telemt_desync_frames_bucket_total{bucket="gt_10"} 961
telemt_pool_swap_total 29
telemt_me_writer_removed_unexpected_total 15557
telemt_me_refill_failed_total 224
telemt_me_writer_restored_same_endpoint_total 15152
telemt_me_writer_restored_fallback_total 29
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 376
telemt_user_connections_total{user="hello"} 625618
telemt_user_connections_current{user="hello"} 847
telemt_user_octets_from_client{user="hello"} 7207778732 (6.71 GB)
telemt_user_octets_to_client{user="hello"} 170043737220 (158.37 GB)
telemt_user_unique_ips_current{user="hello"} 234
telemt_user_unique_ips_recent_window{user="hello"} 126
```