# Server Metrics 2026-03-13 06:24:04 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 87923.8 (24h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2369311
telemt_connections_bad_total 36041
telemt_handshake_timeouts_total 25173
telemt_upstream_connect_attempt_total 17253
telemt_upstream_connect_success_total 17157
telemt_upstream_connect_fail_total 96
telemt_upstream_connect_attempts_per_request{bucket="1"} 17253
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8859
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8252
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 46
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 96
telemt_me_keepalive_timeout_total 1324
telemt_me_reconnect_attempts_total 21657
telemt_me_reconnect_success_total 12788
telemt_me_reader_eof_total 13795
telemt_me_idle_close_by_peer_total 13794
telemt_me_route_drop_no_conn_total 898654
telemt_me_route_drop_channel_closed_total 13
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2180355
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 9796
telemt_desync_full_logged_total 2522
telemt_desync_suppressed_total 7274
telemt_desync_frames_bucket_total{bucket="1_2"} 2525
telemt_desync_frames_bucket_total{bucket="3_10"} 3595
telemt_desync_frames_bucket_total{bucket="gt_10"} 3676
telemt_pool_swap_total 73
telemt_me_writer_removed_unexpected_total 13242
telemt_me_refill_failed_total 275
telemt_me_writer_restored_same_endpoint_total 12775
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 454
telemt_user_connections_total{user="hello"} 2179746
telemt_user_connections_current{user="hello"} 1465
telemt_user_octets_from_client{user="hello"} 31531210520 (29.37 GB)
telemt_user_octets_to_client{user="hello"} 742012508800 (691.05 GB)
telemt_user_unique_ips_current{user="hello"} 395
telemt_user_unique_ips_recent_window{user="hello"} 182
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 117544.3 (32h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 955997
telemt_connections_bad_total 12490
telemt_handshake_timeouts_total 41112
telemt_upstream_connect_attempt_total 29621
telemt_upstream_connect_success_total 29590
telemt_upstream_connect_fail_total 31
telemt_upstream_connect_attempts_per_request{bucket="1"} 29621
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15271
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14229
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 90
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 31
telemt_me_keepalive_timeout_total 3575
telemt_me_reconnect_attempts_total 22225
telemt_me_reconnect_success_total 22106
telemt_me_reader_eof_total 23572
telemt_me_idle_close_by_peer_total 23572
telemt_me_route_drop_no_conn_total 304392
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 863585
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3558
telemt_desync_full_logged_total 1110
telemt_desync_suppressed_total 2448
telemt_desync_frames_bucket_total{bucket="1_2"} 1376
telemt_desync_frames_bucket_total{bucket="3_10"} 1156
telemt_desync_frames_bucket_total{bucket="gt_10"} 1026
telemt_pool_swap_total 121
telemt_me_writer_removed_unexpected_total 22326
telemt_me_writer_restored_same_endpoint_total 22097
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 220
telemt_user_connections_total{user="hello"} 865494
telemt_user_connections_current{user="hello"} 399
telemt_user_octets_from_client{user="hello"} 13590949708 (12.66 GB)
telemt_user_octets_to_client{user="hello"} 329486375463 (306.86 GB)
telemt_user_msgs_from_client{user="hello"} 6476
telemt_user_msgs_to_client{user="hello"} 18854
telemt_user_unique_ips_current{user="hello"} 139
telemt_user_unique_ips_recent_window{user="hello"} 61
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 117544.2 (32h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1974946
telemt_connections_bad_total 22785
telemt_handshake_timeouts_total 132452
telemt_upstream_connect_attempt_total 27226
telemt_upstream_connect_success_total 27215
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 27225
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14278
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12826
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 106
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_keepalive_timeout_total 1683
telemt_me_reconnect_attempts_total 22293
telemt_me_reconnect_success_total 21020
telemt_me_reader_eof_total 22267
telemt_me_idle_close_by_peer_total 22266
telemt_me_route_drop_no_conn_total 632025
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1555422
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5379
telemt_desync_full_logged_total 1631
telemt_desync_suppressed_total 3748
telemt_desync_frames_bucket_total{bucket="1_2"} 889
telemt_desync_frames_bucket_total{bucket="3_10"} 1956
telemt_desync_frames_bucket_total{bucket="gt_10"} 2534
telemt_pool_swap_total 111
telemt_me_writer_removed_unexpected_total 21223
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 20979
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 203
telemt_user_connections_total{user="hello"} 1554919
telemt_user_connections_current{user="hello"} 778
telemt_user_octets_from_client{user="hello"} 26522777168 (24.70 GB)
telemt_user_octets_to_client{user="hello"} 552802974717 (514.84 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 236
telemt_user_unique_ips_recent_window{user="hello"} 122
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 117544.5 (32h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1204979
telemt_connections_bad_total 13996
telemt_handshake_timeouts_total 78056
telemt_upstream_connect_attempt_total 40002
telemt_upstream_connect_success_total 37714
telemt_upstream_connect_fail_total 2151
telemt_upstream_connect_attempts_per_request{bucket="1"} 39728
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 23130
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14493
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 91
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2150
telemt_me_keepalive_timeout_total 11415
telemt_me_reconnect_attempts_total 34940
telemt_me_reconnect_success_total 26005
telemt_me_reader_eof_total 28034
telemt_me_idle_close_by_peer_total 28027
telemt_me_route_drop_no_conn_total 431353
telemt_me_route_drop_channel_closed_total 3
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1035555
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2062
telemt_desync_full_logged_total 667
telemt_desync_suppressed_total 1395
telemt_desync_frames_bucket_total{bucket="1_2"} 567
telemt_desync_frames_bucket_total{bucket="3_10"} 794
telemt_desync_frames_bucket_total{bucket="gt_10"} 701
telemt_pool_swap_total 101
telemt_me_writer_removed_unexpected_total 26462
telemt_me_refill_failed_total 274
telemt_me_writer_restored_same_endpoint_total 25981
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 457
telemt_user_connections_total{user="hello"} 1040476
telemt_user_connections_current{user="hello"} 475
telemt_user_octets_from_client{user="hello"} 15746615489 (14.67 GB)
telemt_user_octets_to_client{user="hello"} 415218933794 (386.70 GB)
telemt_user_msgs_from_client{user="hello"} 44500
telemt_user_msgs_to_client{user="hello"} 116355
telemt_user_unique_ips_current{user="hello"} 152
telemt_user_unique_ips_recent_window{user="hello"} 74
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 117544.3 (32h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1358247
telemt_connections_bad_total 18434
telemt_handshake_timeouts_total 11109
telemt_upstream_connect_attempt_total 37237
telemt_upstream_connect_success_total 36786
telemt_upstream_connect_fail_total 451
telemt_upstream_connect_attempts_per_request{bucket="1"} 37237
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18717
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17873
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 15
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 181
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 451
telemt_me_keepalive_timeout_total 2031
telemt_me_reconnect_attempts_total 44679
telemt_me_reconnect_success_total 30942
telemt_me_reader_eof_total 32494
telemt_me_idle_close_by_peer_total 32494
telemt_me_seq_mismatch_total 42
telemt_me_route_drop_no_conn_total 499494
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1253466
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 46
telemt_me_hardswap_pending_ttl_expired_total 16
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 4481
telemt_desync_full_logged_total 1612
telemt_desync_suppressed_total 2869
telemt_desync_frames_bucket_total{bucket="1_2"} 1360
telemt_desync_frames_bucket_total{bucket="3_10"} 1454
telemt_desync_frames_bucket_total{bucket="gt_10"} 1667
telemt_pool_swap_total 59
telemt_me_writer_removed_unexpected_total 31711
telemt_me_refill_failed_total 425
telemt_me_writer_restored_same_endpoint_total 30888
telemt_me_writer_restored_fallback_total 54
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 769
telemt_user_connections_total{user="hello"} 1253307
telemt_user_connections_current{user="hello"} 723
telemt_user_octets_from_client{user="hello"} 15119238356 (14.08 GB)
telemt_user_octets_to_client{user="hello"} 431307202356 (401.69 GB)
telemt_user_unique_ips_current{user="hello"} 192
telemt_user_unique_ips_recent_window{user="hello"} 89
```