# Server Metrics 2026-03-11 13:19:35 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 82349.3 (22h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1936402
telemt_connections_bad_total 27774
telemt_handshake_timeouts_total 49762
telemt_upstream_connect_attempt_total 17104
telemt_upstream_connect_success_total 17095
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 17104
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8651
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8372
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 71
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 883
telemt_me_reconnect_attempts_total 25761
telemt_me_reconnect_success_total 12930
telemt_me_reader_eof_total 13965
telemt_me_idle_close_by_peer_total 13965
telemt_me_route_drop_no_conn_total 713075
telemt_me_route_drop_channel_closed_total 7
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1768688
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 9272
telemt_desync_full_logged_total 2513
telemt_desync_suppressed_total 6759
telemt_desync_frames_bucket_total{bucket="1_2"} 2305
telemt_desync_frames_bucket_total{bucket="3_10"} 3563
telemt_desync_frames_bucket_total{bucket="gt_10"} 3404
telemt_pool_swap_total 63
telemt_me_writer_removed_unexpected_total 13467
telemt_me_refill_failed_total 398
telemt_me_writer_restored_same_endpoint_total 12924
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 537
telemt_user_connections_total{user="hello"} 1767207
telemt_user_connections_current{user="hello"} 1568
telemt_user_octets_from_client{user="hello"} 23606490876 (21.99 GB)
telemt_user_octets_to_client{user="hello"} 501252755224 (466.83 GB)
telemt_user_unique_ips_current{user="hello"} 395
telemt_user_unique_ips_recent_window{user="hello"} 237
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 82406.0 (22h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 735423
telemt_connections_bad_total 13032
telemt_handshake_timeouts_total 51005
telemt_upstream_connect_attempt_total 26519
telemt_upstream_connect_success_total 23574
telemt_upstream_connect_fail_total 2945
telemt_upstream_connect_attempts_per_request{bucket="1"} 26519
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10868
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10458
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 209
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2039
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2945
telemt_me_keepalive_timeout_total 2443
telemt_me_reconnect_attempts_total 17358
telemt_me_reconnect_success_total 16494
telemt_me_reader_eof_total 17460
telemt_me_idle_close_by_peer_total 17457
telemt_me_route_drop_no_conn_total 287655
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 619098
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2714
telemt_desync_full_logged_total 859
telemt_desync_suppressed_total 1855
telemt_desync_frames_bucket_total{bucket="1_2"} 853
telemt_desync_frames_bucket_total{bucket="3_10"} 989
telemt_desync_frames_bucket_total{bucket="gt_10"} 872
telemt_pool_swap_total 69
telemt_me_writer_removed_unexpected_total 16703
telemt_me_refill_failed_total 22
telemt_me_writer_restored_same_endpoint_total 16471
telemt_me_writer_restored_fallback_total 23
telemt_me_async_recovery_trigger_total 86
telemt_me_writer_removed_unexpected_minus_restored_total 209
telemt_user_connections_total{user="hello"} 621553
telemt_user_connections_current{user="hello"} 644
telemt_user_octets_from_client{user="hello"} 6629745334 (6.17 GB)
telemt_user_octets_to_client{user="hello"} 177379983988 (165.20 GB)
telemt_user_msgs_from_client{user="hello"} 7933
telemt_user_msgs_to_client{user="hello"} 11226
telemt_user_unique_ips_current{user="hello"} 156
telemt_user_unique_ips_recent_window{user="hello"} 107
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 82405.9 (22h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1264465
telemt_connections_bad_total 8292
telemt_handshake_timeouts_total 116545
telemt_upstream_connect_attempt_total 21993
telemt_upstream_connect_success_total 21726
telemt_upstream_connect_fail_total 267
telemt_upstream_connect_attempts_per_request{bucket="1"} 21993
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11769
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9853
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 104
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 267
telemt_me_keepalive_timeout_total 890
telemt_me_reconnect_attempts_total 32603
telemt_me_reconnect_success_total 16500
telemt_me_reader_eof_total 17757
telemt_me_idle_close_by_peer_total 17757
telemt_me_route_drop_no_conn_total 438023
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1092194
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2926
telemt_desync_full_logged_total 874
telemt_desync_suppressed_total 2052
telemt_desync_frames_bucket_total{bucket="1_2"} 708
telemt_desync_frames_bucket_total{bucket="3_10"} 1102
telemt_desync_frames_bucket_total{bucket="gt_10"} 1116
telemt_pool_swap_total 51
telemt_me_writer_removed_unexpected_total 17221
telemt_me_refill_failed_total 499
telemt_me_writer_restored_same_endpoint_total 16489
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 721
telemt_user_connections_total{user="hello"} 1092575
telemt_user_connections_current{user="hello"} 788
telemt_user_octets_from_client{user="hello"} 12983873377 (12.09 GB)
telemt_user_octets_to_client{user="hello"} 327449588269 (304.96 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 241
telemt_user_unique_ips_recent_window{user="hello"} 152
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 82406.2 (22h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 913713
telemt_connections_bad_total 77212
telemt_handshake_timeouts_total 86624
telemt_upstream_connect_attempt_total 22490
telemt_upstream_connect_success_total 22490
telemt_upstream_connect_attempts_per_request{bucket="1"} 22490
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12323
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10163
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_me_keepalive_timeout_total 908
telemt_me_reconnect_attempts_total 19439
telemt_me_reconnect_success_total 18370
telemt_me_reader_eof_total 19482
telemt_me_idle_close_by_peer_total 19481
telemt_me_seq_mismatch_total 17
telemt_me_route_drop_no_conn_total 293544
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 724610
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 28
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1541
telemt_desync_full_logged_total 606
telemt_desync_suppressed_total 935
telemt_desync_frames_bucket_total{bucket="1_2"} 558
telemt_desync_frames_bucket_total{bucket="3_10"} 546
telemt_desync_frames_bucket_total{bucket="gt_10"} 437
telemt_pool_swap_total 72
telemt_me_writer_removed_unexpected_total 18596
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 18342
telemt_me_writer_restored_fallback_total 28
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 226
telemt_user_connections_total{user="hello"} 723973
telemt_user_connections_current{user="hello"} 520
telemt_user_octets_from_client{user="hello"} 8372696720 (7.80 GB)
telemt_user_octets_to_client{user="hello"} 210471459636 (196.02 GB)
telemt_user_unique_ips_current{user="hello"} 156
telemt_user_unique_ips_recent_window{user="hello"} 101
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 82406.0 (22h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 993780
telemt_connections_bad_total 6812
telemt_handshake_timeouts_total 9201
telemt_upstream_connect_attempt_total 22493
telemt_upstream_connect_success_total 22396
telemt_upstream_connect_fail_total 97
telemt_upstream_connect_attempts_per_request{bucket="1"} 22493
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11503
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10706
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 183
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 97
telemt_me_keepalive_timeout_total 937
telemt_me_reconnect_attempts_total 22220
telemt_me_reconnect_success_total 18149
telemt_me_reader_eof_total 19135
telemt_me_idle_close_by_peer_total 19135
telemt_me_route_drop_no_conn_total 350696
telemt_me_route_drop_channel_closed_total 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 902319
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 3649
telemt_desync_full_logged_total 1346
telemt_desync_suppressed_total 2303
telemt_desync_frames_bucket_total{bucket="1_2"} 1282
telemt_desync_frames_bucket_total{bucket="3_10"} 1381
telemt_desync_frames_bucket_total{bucket="gt_10"} 986
telemt_pool_swap_total 55
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 18506
telemt_me_refill_failed_total 124
telemt_me_writer_restored_same_endpoint_total 18149
telemt_me_async_recovery_trigger_total 48
telemt_me_writer_removed_unexpected_minus_restored_total 357
telemt_user_connections_total{user="hello"} 902063
telemt_user_connections_current{user="hello"} 689
telemt_user_octets_from_client{user="hello"} 13144569291 (12.24 GB)
telemt_user_octets_to_client{user="hello"} 322275765194 (300.14 GB)
telemt_user_msgs_from_client{user="hello"} 122
telemt_user_msgs_to_client{user="hello"} 215
telemt_user_unique_ips_current{user="hello"} 195
telemt_user_unique_ips_recent_window{user="hello"} 142
```