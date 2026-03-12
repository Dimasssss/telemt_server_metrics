# Server Metrics 2026-03-12 21:33:36 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 56095.5 (15h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1874953
telemt_connections_bad_total 26052
telemt_handshake_timeouts_total 20543
telemt_upstream_connect_attempt_total 10944
telemt_upstream_connect_success_total 10882
telemt_upstream_connect_fail_total 62
telemt_upstream_connect_attempts_per_request{bucket="1"} 10944
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5656
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5190
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 36
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 62
telemt_me_keepalive_timeout_total 591
telemt_me_reconnect_attempts_total 16894
telemt_me_reconnect_success_total 8041
telemt_me_reader_eof_total 8702
telemt_me_idle_close_by_peer_total 8701
telemt_me_route_drop_no_conn_total 734032
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1745085
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8421
telemt_desync_full_logged_total 2183
telemt_desync_suppressed_total 6238
telemt_desync_frames_bucket_total{bucket="1_2"} 2213
telemt_desync_frames_bucket_total{bucket="3_10"} 3031
telemt_desync_frames_bucket_total{bucket="gt_10"} 3177
telemt_pool_swap_total 39
telemt_me_writer_removed_unexpected_total 8435
telemt_me_refill_failed_total 275
telemt_me_writer_restored_same_endpoint_total 8028
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 394
telemt_user_connections_total{user="hello"} 1744569
telemt_user_connections_current{user="hello"} 970
telemt_user_octets_from_client{user="hello"} 26617074796 (24.79 GB)
telemt_user_octets_to_client{user="hello"} 615331711952 (573.07 GB)
telemt_user_unique_ips_current{user="hello"} 299
telemt_user_unique_ips_recent_window{user="hello"} 108
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 85716.3 (23h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 780775
telemt_connections_bad_total 11663
telemt_handshake_timeouts_total 31016
telemt_upstream_connect_attempt_total 21654
telemt_upstream_connect_success_total 21625
telemt_upstream_connect_fail_total 29
telemt_upstream_connect_attempts_per_request{bucket="1"} 21654
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11414
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10123
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 88
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 29
telemt_me_keepalive_timeout_total 3396
telemt_me_reconnect_attempts_total 15770
telemt_me_reconnect_success_total 15678
telemt_me_reader_eof_total 16680
telemt_me_idle_close_by_peer_total 16680
telemt_me_route_drop_no_conn_total 252301
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 704489
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2979
telemt_desync_full_logged_total 922
telemt_desync_suppressed_total 2057
telemt_desync_frames_bucket_total{bucket="1_2"} 1171
telemt_desync_frames_bucket_total{bucket="3_10"} 981
telemt_desync_frames_bucket_total{bucket="gt_10"} 827
telemt_pool_swap_total 86
telemt_me_writer_removed_unexpected_total 15838
telemt_me_writer_restored_same_endpoint_total 15669
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 160
telemt_user_connections_total{user="hello"} 706366
telemt_user_connections_current{user="hello"} 275
telemt_user_octets_from_client{user="hello"} 11975184876 (11.15 GB)
telemt_user_octets_to_client{user="hello"} 271070429415 (252.45 GB)
telemt_user_msgs_from_client{user="hello"} 6476
telemt_user_msgs_to_client{user="hello"} 18854
telemt_user_unique_ips_current{user="hello"} 93
telemt_user_unique_ips_recent_window{user="hello"} 51
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 85716.0 (23h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1616820
telemt_connections_bad_total 7726
telemt_handshake_timeouts_total 112055
telemt_upstream_connect_attempt_total 20077
telemt_upstream_connect_success_total 20071
telemt_upstream_connect_fail_total 6
telemt_upstream_connect_attempts_per_request{bucket="1"} 20077
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10760
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9235
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 71
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 6
telemt_me_keepalive_timeout_total 1213
telemt_me_reconnect_attempts_total 16660
telemt_me_reconnect_success_total 15413
telemt_me_reader_eof_total 16281
telemt_me_idle_close_by_peer_total 16280
telemt_me_route_drop_no_conn_total 533852
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1252490
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4922
telemt_desync_full_logged_total 1513
telemt_desync_suppressed_total 3409
telemt_desync_frames_bucket_total{bucket="1_2"} 784
telemt_desync_frames_bucket_total{bucket="3_10"} 1779
telemt_desync_frames_bucket_total{bucket="gt_10"} 2359
telemt_pool_swap_total 78
telemt_me_writer_removed_unexpected_total 15557
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 15372
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 144
telemt_user_connections_total{user="hello"} 1252096
telemt_user_connections_current{user="hello"} 491
telemt_user_octets_from_client{user="hello"} 19495377128 (18.16 GB)
telemt_user_octets_to_client{user="hello"} 465666760481 (433.69 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 167
telemt_user_unique_ips_recent_window{user="hello"} 72
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 85716.5 (23h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 995254
telemt_connections_bad_total 12984
telemt_handshake_timeouts_total 71076
telemt_upstream_connect_attempt_total 21845
telemt_upstream_connect_success_total 21756
telemt_upstream_connect_fail_total 89
telemt_upstream_connect_attempts_per_request{bucket="1"} 21845
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12226
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9516
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 14
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 89
telemt_me_keepalive_timeout_total 1678
telemt_me_reconnect_attempts_total 25188
telemt_me_reconnect_success_total 17459
telemt_me_reader_eof_total 18654
telemt_me_idle_close_by_peer_total 18654
telemt_me_route_drop_no_conn_total 356001
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 866506
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1843
telemt_desync_full_logged_total 612
telemt_desync_suppressed_total 1231
telemt_desync_frames_bucket_total{bucket="1_2"} 513
telemt_desync_frames_bucket_total{bucket="3_10"} 715
telemt_desync_frames_bucket_total{bucket="gt_10"} 615
telemt_pool_swap_total 72
telemt_me_writer_removed_unexpected_total 17841
telemt_me_refill_failed_total 239
telemt_me_writer_restored_same_endpoint_total 17438
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 108
telemt_me_writer_removed_unexpected_minus_restored_total 382
telemt_user_connections_total{user="hello"} 865855
telemt_user_connections_current{user="hello"} 333
telemt_user_octets_from_client{user="hello"} 13685453392 (12.75 GB)
telemt_user_octets_to_client{user="hello"} 349139292744 (325.16 GB)
telemt_user_unique_ips_current{user="hello"} 113
telemt_user_unique_ips_recent_window{user="hello"} 60
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 85716.3 (23h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1115122
telemt_connections_bad_total 12515
telemt_handshake_timeouts_total 9052
telemt_upstream_connect_attempt_total 26446
telemt_upstream_connect_success_total 26121
telemt_upstream_connect_fail_total 325
telemt_upstream_connect_attempts_per_request{bucket="1"} 26446
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13368
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12609
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 10
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 134
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 325
telemt_me_keepalive_timeout_total 1433
telemt_me_reconnect_attempts_total 32849
telemt_me_reconnect_success_total 21811
telemt_me_reader_eof_total 22930
telemt_me_idle_close_by_peer_total 22930
telemt_me_seq_mismatch_total 33
telemt_me_route_drop_no_conn_total 418139
telemt_me_route_drop_channel_closed_total 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1025309
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 37
telemt_me_hardswap_pending_ttl_expired_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 3877
telemt_desync_full_logged_total 1350
telemt_desync_suppressed_total 2527
telemt_desync_frames_bucket_total{bucket="1_2"} 1142
telemt_desync_frames_bucket_total{bucket="3_10"} 1277
telemt_desync_frames_bucket_total{bucket="gt_10"} 1458
telemt_pool_swap_total 42
telemt_me_writer_removed_unexpected_total 22405
telemt_me_refill_failed_total 342
telemt_me_writer_restored_same_endpoint_total 21767
telemt_me_writer_restored_fallback_total 44
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 594
telemt_user_connections_total{user="hello"} 1025169
telemt_user_connections_current{user="hello"} 411
telemt_user_octets_from_client{user="hello"} 12719609528 (11.85 GB)
telemt_user_octets_to_client{user="hello"} 361750895964 (336.91 GB)
telemt_user_unique_ips_current{user="hello"} 124
telemt_user_unique_ips_recent_window{user="hello"} 63
```