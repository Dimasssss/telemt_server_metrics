# Server Metrics 2026-03-10 23:19:56 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 31972.0 (8h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 757432
telemt_connections_bad_total 8946
telemt_handshake_timeouts_total 8468
telemt_upstream_connect_attempt_total 6916
telemt_upstream_connect_success_total 6907
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 6916
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3446
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3404
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 56
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 366
telemt_me_reconnect_attempts_total 16893
telemt_me_reconnect_success_total 5231
telemt_me_reader_eof_total 5757
telemt_me_idle_close_by_peer_total 5757
telemt_me_route_drop_no_conn_total 313987
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 716885
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3487
telemt_desync_full_logged_total 974
telemt_desync_suppressed_total 2513
telemt_desync_frames_bucket_total{bucket="1_2"} 1009
telemt_desync_frames_bucket_total{bucket="3_10"} 1303
telemt_desync_frames_bucket_total{bucket="gt_10"} 1175
telemt_pool_swap_total 15
telemt_me_writer_removed_unexpected_total 5639
telemt_me_refill_failed_total 363
telemt_me_writer_restored_same_endpoint_total 5225
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 408
telemt_user_connections_total{user="hello"} 716674
telemt_user_connections_current{user="hello"} 380
telemt_user_octets_from_client{user="hello"} 10104793928 (9.41 GB)
telemt_user_octets_to_client{user="hello"} 215686009808 (200.87 GB)
telemt_user_unique_ips_current{user="hello"} 145
telemt_user_unique_ips_recent_window{user="hello"} 45
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 32028.6 (8h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 328723
telemt_connections_bad_total 2373
telemt_handshake_timeouts_total 17599
telemt_upstream_connect_attempt_total 13709
telemt_upstream_connect_success_total 10836
telemt_upstream_connect_fail_total 2873
telemt_upstream_connect_attempts_per_request{bucket="1"} 13709
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4611
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3985
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 209
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2031
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2873
telemt_me_keepalive_timeout_total 1387
telemt_me_reconnect_attempts_total 7055
telemt_me_reconnect_success_total 6245
telemt_me_reader_eof_total 6568
telemt_me_idle_close_by_peer_total 6566
telemt_me_route_drop_no_conn_total 169329
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 278518
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1702
telemt_desync_full_logged_total 470
telemt_desync_suppressed_total 1232
telemt_desync_frames_bucket_total{bucket="1_2"} 523
telemt_desync_frames_bucket_total{bucket="3_10"} 601
telemt_desync_frames_bucket_total{bucket="gt_10"} 578
telemt_pool_swap_total 23
telemt_me_writer_removed_unexpected_total 6336
telemt_me_refill_failed_total 22
telemt_me_writer_restored_same_endpoint_total 6224
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 86
telemt_me_writer_removed_unexpected_minus_restored_total 91
telemt_user_connections_total{user="hello"} 280787
telemt_user_connections_current{user="hello"} 162
telemt_user_octets_from_client{user="hello"} 2754688982 (2.57 GB)
telemt_user_octets_to_client{user="hello"} 67918116744 (63.25 GB)
telemt_user_msgs_from_client{user="hello"} 7933
telemt_user_msgs_to_client{user="hello"} 11226
telemt_user_unique_ips_current{user="hello"} 58
telemt_user_unique_ips_recent_window{user="hello"} 29
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 32028.5 (8h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 543780
telemt_connections_bad_total 3510
telemt_handshake_timeouts_total 33940
telemt_upstream_connect_attempt_total 8720
telemt_upstream_connect_success_total 8598
telemt_upstream_connect_fail_total 122
telemt_upstream_connect_attempts_per_request{bucket="1"} 8720
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4920
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3616
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 62
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 122
telemt_me_keepalive_timeout_total 224
telemt_me_reconnect_attempts_total 16939
telemt_me_reconnect_success_total 5882
telemt_me_reader_eof_total 6453
telemt_me_idle_close_by_peer_total 6453
telemt_me_route_drop_no_conn_total 188021
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 477923
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1517
telemt_desync_full_logged_total 432
telemt_desync_suppressed_total 1085
telemt_desync_frames_bucket_total{bucket="1_2"} 339
telemt_desync_frames_bucket_total{bucket="3_10"} 523
telemt_desync_frames_bucket_total{bucket="gt_10"} 655
telemt_pool_swap_total 17
telemt_me_writer_removed_unexpected_total 6316
telemt_me_refill_failed_total 343
telemt_me_writer_restored_same_endpoint_total 5871
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 434
telemt_user_connections_total{user="hello"} 478855
telemt_user_connections_current{user="hello"} 195
telemt_user_octets_from_client{user="hello"} 6717875989 (6.26 GB)
telemt_user_octets_to_client{user="hello"} 150819148325 (140.46 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 89
telemt_user_unique_ips_recent_window{user="hello"} 32
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 32028.8 (8h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 388614
telemt_connections_bad_total 30690
telemt_handshake_timeouts_total 35382
telemt_upstream_connect_attempt_total 8933
telemt_upstream_connect_success_total 8933
telemt_upstream_connect_attempts_per_request{bucket="1"} 8933
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4989
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3943
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 187
telemt_me_reconnect_attempts_total 8317
telemt_me_reconnect_success_total 7291
telemt_me_reader_eof_total 7677
telemt_me_idle_close_by_peer_total 7677
telemt_me_seq_mismatch_total 3
telemt_me_route_drop_no_conn_total 122908
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 309598
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 697
telemt_desync_full_logged_total 282
telemt_desync_suppressed_total 415
telemt_desync_frames_bucket_total{bucket="1_2"} 269
telemt_desync_frames_bucket_total{bucket="3_10"} 245
telemt_desync_frames_bucket_total{bucket="gt_10"} 183
telemt_pool_swap_total 24
telemt_me_writer_removed_unexpected_total 7397
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 7277
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 106
telemt_user_connections_total{user="hello"} 309273
telemt_user_connections_current{user="hello"} 149
telemt_user_octets_from_client{user="hello"} 4086738644 (3.81 GB)
telemt_user_octets_to_client{user="hello"} 88495188996 (82.42 GB)
telemt_user_unique_ips_current{user="hello"} 58
telemt_user_unique_ips_recent_window{user="hello"} 28
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 32028.6 (8h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 410751
telemt_connections_bad_total 3192
telemt_handshake_timeouts_total 2663
telemt_upstream_connect_attempt_total 9827
telemt_upstream_connect_success_total 9788
telemt_upstream_connect_fail_total 39
telemt_upstream_connect_attempts_per_request{bucket="1"} 9827
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5138
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4541
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 107
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 39
telemt_me_keepalive_timeout_total 205
telemt_me_reconnect_attempts_total 11872
telemt_me_reconnect_success_total 8112
telemt_me_reader_eof_total 8512
telemt_me_idle_close_by_peer_total 8512
telemt_me_route_drop_no_conn_total 140738
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 381071
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 2213
telemt_desync_full_logged_total 855
telemt_desync_suppressed_total 1358
telemt_desync_frames_bucket_total{bucket="1_2"} 812
telemt_desync_frames_bucket_total{bucket="3_10"} 953
telemt_desync_frames_bucket_total{bucket="gt_10"} 448
telemt_pool_swap_total 12
telemt_me_writer_removed_unexpected_total 8340
telemt_me_refill_failed_total 116
telemt_me_writer_restored_same_endpoint_total 8112
telemt_me_async_recovery_trigger_total 48
telemt_me_writer_removed_unexpected_minus_restored_total 228
telemt_user_connections_total{user="hello"} 380868
telemt_user_connections_current{user="hello"} 264
telemt_user_octets_from_client{user="hello"} 6487960420 (6.04 GB)
telemt_user_octets_to_client{user="hello"} 140821898012 (131.15 GB)
telemt_user_unique_ips_current{user="hello"} 81
telemt_user_unique_ips_recent_window{user="hello"} 35
```