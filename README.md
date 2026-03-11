# Server Metrics 2026-03-11 00:15:48 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 35323.8 (9h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 780938
telemt_connections_bad_total 9521
telemt_handshake_timeouts_total 8951
telemt_upstream_connect_attempt_total 7682
telemt_upstream_connect_success_total 7673
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 7682
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3838
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3777
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 57
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 468
telemt_me_reconnect_attempts_total 17486
telemt_me_reconnect_success_total 5823
telemt_me_reader_eof_total 6396
telemt_me_idle_close_by_peer_total 6396
telemt_me_route_drop_no_conn_total 322163
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 738935
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3550
telemt_desync_full_logged_total 992
telemt_desync_suppressed_total 2558
telemt_desync_frames_bucket_total{bucket="1_2"} 1030
telemt_desync_frames_bucket_total{bucket="3_10"} 1319
telemt_desync_frames_bucket_total{bucket="gt_10"} 1201
telemt_pool_swap_total 19
telemt_me_writer_removed_unexpected_total 6236
telemt_me_refill_failed_total 363
telemt_me_writer_restored_same_endpoint_total 5817
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 413
telemt_user_connections_total{user="hello"} 738720
telemt_user_connections_current{user="hello"} 404
telemt_user_octets_from_client{user="hello"} 10194127808 (9.49 GB)
telemt_user_octets_to_client{user="hello"} 220137374892 (205.02 GB)
telemt_user_unique_ips_current{user="hello"} 146
telemt_user_unique_ips_recent_window{user="hello"} 45
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 35380.7 (9h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 336990
telemt_connections_bad_total 2383
telemt_handshake_timeouts_total 17628
telemt_upstream_connect_attempt_total 14646
telemt_upstream_connect_success_total 11768
telemt_upstream_connect_fail_total 2878
telemt_upstream_connect_attempts_per_request{bucket="1"} 14646
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5068
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4460
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 209
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2031
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2878
telemt_me_keepalive_timeout_total 1703
telemt_me_reconnect_attempts_total 7815
telemt_me_reconnect_success_total 7003
telemt_me_reader_eof_total 7388
telemt_me_idle_close_by_peer_total 7386
telemt_me_route_drop_no_conn_total 171497
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 286516
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
telemt_pool_swap_total 27
telemt_me_writer_removed_unexpected_total 7101
telemt_me_refill_failed_total 22
telemt_me_writer_restored_same_endpoint_total 6982
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 86
telemt_me_writer_removed_unexpected_minus_restored_total 98
telemt_user_connections_total{user="hello"} 288785
telemt_user_connections_current{user="hello"} 169
telemt_user_octets_from_client{user="hello"} 2791794510 (2.60 GB)
telemt_user_octets_to_client{user="hello"} 69494287976 (64.72 GB)
telemt_user_msgs_from_client{user="hello"} 7933
telemt_user_msgs_to_client{user="hello"} 11226
telemt_user_unique_ips_current{user="hello"} 73
telemt_user_unique_ips_recent_window{user="hello"} 35
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 35380.3 (9h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 560462
telemt_connections_bad_total 3862
telemt_handshake_timeouts_total 34033
telemt_upstream_connect_attempt_total 9714
telemt_upstream_connect_success_total 9579
telemt_upstream_connect_fail_total 135
telemt_upstream_connect_attempts_per_request{bucket="1"} 9714
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5421
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4094
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 64
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 135
telemt_me_keepalive_timeout_total 504
telemt_me_reconnect_attempts_total 17746
telemt_me_reconnect_success_total 6687
telemt_me_reader_eof_total 7310
telemt_me_idle_close_by_peer_total 7310
telemt_me_route_drop_no_conn_total 193071
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 494071
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
telemt_pool_swap_total 20
telemt_me_writer_removed_unexpected_total 7128
telemt_me_refill_failed_total 343
telemt_me_writer_restored_same_endpoint_total 6676
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 441
telemt_user_connections_total{user="hello"} 494996
telemt_user_connections_current{user="hello"} 224
telemt_user_octets_from_client{user="hello"} 6789551917 (6.32 GB)
telemt_user_octets_to_client{user="hello"} 152901298785 (142.40 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 91
telemt_user_unique_ips_recent_window{user="hello"} 34
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 35380.8 (9h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 406611
telemt_connections_bad_total 33734
telemt_handshake_timeouts_total 37726
telemt_upstream_connect_attempt_total 10010
telemt_upstream_connect_success_total 10010
telemt_upstream_connect_attempts_per_request{bucket="1"} 10010
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5656
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4353
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 394
telemt_me_reconnect_attempts_total 9222
telemt_me_reconnect_success_total 8192
telemt_me_reader_eof_total 8650
telemt_me_idle_close_by_peer_total 8650
telemt_me_seq_mismatch_total 4
telemt_me_route_drop_no_conn_total 126550
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 322177
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
telemt_pool_swap_total 28
telemt_me_writer_removed_unexpected_total 8305
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 8177
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 113
telemt_user_connections_total{user="hello"} 321852
telemt_user_connections_current{user="hello"} 188
telemt_user_octets_from_client{user="hello"} 4168285068 (3.88 GB)
telemt_user_octets_to_client{user="hello"} 90013829248 (83.83 GB)
telemt_user_unique_ips_current{user="hello"} 60
telemt_user_unique_ips_recent_window{user="hello"} 34
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 35380.4 (9h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 430293
telemt_connections_bad_total 3374
telemt_handshake_timeouts_total 2730
telemt_upstream_connect_attempt_total 10748
telemt_upstream_connect_success_total 10705
telemt_upstream_connect_fail_total 43
telemt_upstream_connect_attempts_per_request{bucket="1"} 10748
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5577
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5017
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 109
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 43
telemt_me_keepalive_timeout_total 500
telemt_me_reconnect_attempts_total 12618
telemt_me_reconnect_success_total 8853
telemt_me_reader_eof_total 9310
telemt_me_idle_close_by_peer_total 9310
telemt_me_route_drop_no_conn_total 145167
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 397940
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 2256
telemt_desync_full_logged_total 869
telemt_desync_suppressed_total 1387
telemt_desync_frames_bucket_total{bucket="1_2"} 829
telemt_desync_frames_bucket_total{bucket="3_10"} 969
telemt_desync_frames_bucket_total{bucket="gt_10"} 458
telemt_pool_swap_total 16
telemt_me_writer_removed_unexpected_total 9087
telemt_me_refill_failed_total 116
telemt_me_writer_restored_same_endpoint_total 8853
telemt_me_async_recovery_trigger_total 48
telemt_me_writer_removed_unexpected_minus_restored_total 234
telemt_user_connections_total{user="hello"} 397693
telemt_user_connections_current{user="hello"} 198
telemt_user_octets_from_client{user="hello"} 8305762908 (7.74 GB)
telemt_user_octets_to_client{user="hello"} 145244103596 (135.27 GB)
telemt_user_unique_ips_current{user="hello"} 70
telemt_user_unique_ips_recent_window{user="hello"} 31
```