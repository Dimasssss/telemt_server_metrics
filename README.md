# Server Metrics 2026-03-12 20:06:51 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 50890.5 (14h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1769053
telemt_connections_bad_total 20721
telemt_handshake_timeouts_total 18804
telemt_upstream_connect_attempt_total 9942
telemt_upstream_connect_success_total 9885
telemt_upstream_connect_fail_total 57
telemt_upstream_connect_attempts_per_request{bucket="1"} 9942
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5150
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4700
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 35
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 57
telemt_me_keepalive_timeout_total 579
telemt_me_reconnect_attempts_total 16155
telemt_me_reconnect_success_total 7307
telemt_me_reader_eof_total 7910
telemt_me_idle_close_by_peer_total 7909
telemt_me_route_drop_no_conn_total 697132
telemt_me_route_drop_channel_closed_total 10
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1651681
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8159
telemt_desync_full_logged_total 2098
telemt_desync_suppressed_total 6061
telemt_desync_frames_bucket_total{bucket="1_2"} 2138
telemt_desync_frames_bucket_total{bucket="3_10"} 2941
telemt_desync_frames_bucket_total{bucket="gt_10"} 3080
telemt_pool_swap_total 33
telemt_me_writer_removed_unexpected_total 7688
telemt_me_refill_failed_total 275
telemt_me_writer_restored_same_endpoint_total 7294
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 381
telemt_user_connections_total{user="hello"} 1651169
telemt_user_connections_current{user="hello"} 1178
telemt_user_octets_from_client{user="hello"} 25537390668 (23.78 GB)
telemt_user_octets_to_client{user="hello"} 569432137676 (530.33 GB)
telemt_user_unique_ips_current{user="hello"} 344
telemt_user_unique_ips_recent_window{user="hello"} 150
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 80511.2 (22h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 748606
telemt_connections_bad_total 10525
telemt_handshake_timeouts_total 30177
telemt_upstream_connect_attempt_total 20412
telemt_upstream_connect_success_total 20383
telemt_upstream_connect_fail_total 29
telemt_upstream_connect_attempts_per_request{bucket="1"} 20412
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10776
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9522
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 85
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 29
telemt_me_keepalive_timeout_total 3378
telemt_me_reconnect_attempts_total 14787
telemt_me_reconnect_success_total 14698
telemt_me_reader_eof_total 15628
telemt_me_idle_close_by_peer_total 15628
telemt_me_route_drop_no_conn_total 240327
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 675110
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2918
telemt_desync_full_logged_total 894
telemt_desync_suppressed_total 2024
telemt_desync_frames_bucket_total{bucket="1_2"} 1128
telemt_desync_frames_bucket_total{bucket="3_10"} 969
telemt_desync_frames_bucket_total{bucket="gt_10"} 821
telemt_pool_swap_total 80
telemt_me_writer_removed_unexpected_total 14850
telemt_me_writer_restored_same_endpoint_total 14689
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 152
telemt_user_connections_total{user="hello"} 676989
telemt_user_connections_current{user="hello"} 417
telemt_user_octets_from_client{user="hello"} 11513499864 (10.72 GB)
telemt_user_octets_to_client{user="hello"} 255945019087 (238.37 GB)
telemt_user_msgs_from_client{user="hello"} 6476
telemt_user_msgs_to_client{user="hello"} 18854
telemt_user_unique_ips_current{user="hello"} 123
telemt_user_unique_ips_recent_window{user="hello"} 56
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 80511.0 (22h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1546817
telemt_connections_bad_total 7278
telemt_handshake_timeouts_total 105597
telemt_upstream_connect_attempt_total 18961
telemt_upstream_connect_success_total 18955
telemt_upstream_connect_fail_total 6
telemt_upstream_connect_attempts_per_request{bucket="1"} 18961
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10199
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8683
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 68
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 6
telemt_me_keepalive_timeout_total 1199
telemt_me_reconnect_attempts_total 15803
telemt_me_reconnect_success_total 14556
telemt_me_reader_eof_total 15361
telemt_me_idle_close_by_peer_total 15360
telemt_me_route_drop_no_conn_total 511580
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1190562
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4791
telemt_desync_full_logged_total 1478
telemt_desync_suppressed_total 3313
telemt_desync_frames_bucket_total{bucket="1_2"} 759
telemt_desync_frames_bucket_total{bucket="3_10"} 1736
telemt_desync_frames_bucket_total{bucket="gt_10"} 2296
telemt_pool_swap_total 72
telemt_me_writer_removed_unexpected_total 14691
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 14515
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 135
telemt_user_connections_total{user="hello"} 1190172
telemt_user_connections_current{user="hello"} 693
telemt_user_octets_from_client{user="hello"} 18567055188 (17.29 GB)
telemt_user_octets_to_client{user="hello"} 443653817837 (413.18 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 215
telemt_user_unique_ips_recent_window{user="hello"} 107
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 80511.6 (22h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 948770
telemt_connections_bad_total 12967
telemt_handshake_timeouts_total 70418
telemt_upstream_connect_attempt_total 20604
telemt_upstream_connect_success_total 20523
telemt_upstream_connect_fail_total 81
telemt_upstream_connect_attempts_per_request{bucket="1"} 20604
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11497
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9012
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 14
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 81
telemt_me_keepalive_timeout_total 1664
telemt_me_reconnect_attempts_total 24215
telemt_me_reconnect_success_total 16490
telemt_me_reader_eof_total 17617
telemt_me_idle_close_by_peer_total 17617
telemt_me_route_drop_no_conn_total 337742
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 822118
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1749
telemt_desync_full_logged_total 586
telemt_desync_suppressed_total 1163
telemt_desync_frames_bucket_total{bucket="1_2"} 491
telemt_desync_frames_bucket_total{bucket="3_10"} 677
telemt_desync_frames_bucket_total{bucket="gt_10"} 581
telemt_pool_swap_total 66
telemt_me_writer_removed_unexpected_total 16865
telemt_me_refill_failed_total 239
telemt_me_writer_restored_same_endpoint_total 16469
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 108
telemt_me_writer_removed_unexpected_minus_restored_total 375
telemt_user_connections_total{user="hello"} 821469
telemt_user_connections_current{user="hello"} 458
telemt_user_octets_from_client{user="hello"} 12819368848 (11.94 GB)
telemt_user_octets_to_client{user="hello"} 336348144024 (313.25 GB)
telemt_user_unique_ips_current{user="hello"} 145
telemt_user_unique_ips_recent_window{user="hello"} 86
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 80511.5 (22h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1066800
telemt_connections_bad_total 12364
telemt_handshake_timeouts_total 8807
telemt_upstream_connect_attempt_total 25072
telemt_upstream_connect_success_total 24764
telemt_upstream_connect_fail_total 308
telemt_upstream_connect_attempts_per_request{bucket="1"} 25072
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12645
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11986
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 125
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 308
telemt_me_keepalive_timeout_total 1417
telemt_me_reconnect_attempts_total 31750
telemt_me_reconnect_success_total 20712
telemt_me_reader_eof_total 21749
telemt_me_idle_close_by_peer_total 21749
telemt_me_seq_mismatch_total 33
telemt_me_route_drop_no_conn_total 399295
telemt_me_route_drop_channel_closed_total 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 978646
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 37
telemt_me_hardswap_pending_ttl_expired_total 10
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 3678
telemt_desync_full_logged_total 1285
telemt_desync_suppressed_total 2393
telemt_desync_frames_bucket_total{bucket="1_2"} 1045
telemt_desync_frames_bucket_total{bucket="3_10"} 1221
telemt_desync_frames_bucket_total{bucket="gt_10"} 1412
telemt_pool_swap_total 37
telemt_me_writer_removed_unexpected_total 21294
telemt_me_refill_failed_total 342
telemt_me_writer_restored_same_endpoint_total 20668
telemt_me_writer_restored_fallback_total 44
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 582
telemt_user_connections_total{user="hello"} 978516
telemt_user_connections_current{user="hello"} 650
telemt_user_octets_from_client{user="hello"} 12160637772 (11.33 GB)
telemt_user_octets_to_client{user="hello"} 339304830880 (316.00 GB)
telemt_user_unique_ips_current{user="hello"} 180
telemt_user_unique_ips_recent_window{user="hello"} 78
```