# Server Metrics 2026-03-13 06:44:30 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 89149.0 (24h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2408996
telemt_connections_bad_total 36046
telemt_handshake_timeouts_total 25682
telemt_upstream_connect_attempt_total 17448
telemt_upstream_connect_success_total 17351
telemt_upstream_connect_fail_total 97
telemt_upstream_connect_attempts_per_request{bucket="1"} 17448
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8966
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8338
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 47
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 97
telemt_me_keepalive_timeout_total 1326
telemt_me_reconnect_attempts_total 21792
telemt_me_reconnect_success_total 12921
telemt_me_reader_eof_total 13936
telemt_me_idle_close_by_peer_total 13935
telemt_me_route_drop_no_conn_total 912627
telemt_me_route_drop_channel_closed_total 13
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2217073
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 9978
telemt_desync_full_logged_total 2568
telemt_desync_suppressed_total 7410
telemt_desync_frames_bucket_total{bucket="1_2"} 2554
telemt_desync_frames_bucket_total{bucket="3_10"} 3669
telemt_desync_frames_bucket_total{bucket="gt_10"} 3755
telemt_pool_swap_total 74
telemt_me_writer_removed_unexpected_total 13379
telemt_me_refill_failed_total 275
telemt_me_writer_restored_same_endpoint_total 12908
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 458
telemt_user_connections_total{user="hello"} 2216554
telemt_user_connections_current{user="hello"} 1433
telemt_user_octets_from_client{user="hello"} 32007807876 (29.81 GB)
telemt_user_octets_to_client{user="hello"} 751724931860 (700.10 GB)
telemt_user_unique_ips_current{user="hello"} 393
telemt_user_unique_ips_recent_window{user="hello"} 188
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 118769.4 (32h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 968122
telemt_connections_bad_total 12538
telemt_handshake_timeouts_total 41489
telemt_upstream_connect_attempt_total 29837
telemt_upstream_connect_success_total 29806
telemt_upstream_connect_fail_total 31
telemt_upstream_connect_attempts_per_request{bucket="1"} 29837
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15381
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14335
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 90
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 31
telemt_me_keepalive_timeout_total 3577
telemt_me_reconnect_attempts_total 22397
telemt_me_reconnect_success_total 22278
telemt_me_reader_eof_total 23755
telemt_me_idle_close_by_peer_total 23755
telemt_me_route_drop_no_conn_total 308595
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 874952
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3659
telemt_desync_full_logged_total 1137
telemt_desync_suppressed_total 2522
telemt_desync_frames_bucket_total{bucket="1_2"} 1406
telemt_desync_frames_bucket_total{bucket="3_10"} 1183
telemt_desync_frames_bucket_total{bucket="gt_10"} 1070
telemt_pool_swap_total 122
telemt_me_writer_removed_unexpected_total 22499
telemt_me_writer_restored_same_endpoint_total 22269
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 221
telemt_user_connections_total{user="hello"} 876867
telemt_user_connections_current{user="hello"} 462
telemt_user_octets_from_client{user="hello"} 13692464172 (12.75 GB)
telemt_user_octets_to_client{user="hello"} 331904167683 (309.11 GB)
telemt_user_msgs_from_client{user="hello"} 6476
telemt_user_msgs_to_client{user="hello"} 18854
telemt_user_unique_ips_current{user="hello"} 142
telemt_user_unique_ips_recent_window{user="hello"} 59
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 118769.3 (32h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1997330
telemt_connections_bad_total 22828
telemt_handshake_timeouts_total 134015
telemt_upstream_connect_attempt_total 27437
telemt_upstream_connect_success_total 27427
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 27437
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14379
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12936
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 107
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_keepalive_timeout_total 1685
telemt_me_reconnect_attempts_total 22460
telemt_me_reconnect_success_total 21186
telemt_me_reader_eof_total 22441
telemt_me_idle_close_by_peer_total 22440
telemt_me_route_drop_no_conn_total 639343
telemt_me_route_drop_channel_closed_total 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1575755
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5427
telemt_desync_full_logged_total 1649
telemt_desync_suppressed_total 3778
telemt_desync_frames_bucket_total{bucket="1_2"} 892
telemt_desync_frames_bucket_total{bucket="3_10"} 1973
telemt_desync_frames_bucket_total{bucket="gt_10"} 2562
telemt_pool_swap_total 112
telemt_me_writer_removed_unexpected_total 21390
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 21145
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 204
telemt_user_connections_total{user="hello"} 1575250
telemt_user_connections_current{user="hello"} 790
telemt_user_octets_from_client{user="hello"} 26749021664 (24.91 GB)
telemt_user_octets_to_client{user="hello"} 559279821697 (520.87 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 250
telemt_user_unique_ips_recent_window{user="hello"} 130
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 118769.6 (32h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1218300
telemt_connections_bad_total 14000
telemt_handshake_timeouts_total 78641
telemt_upstream_connect_attempt_total 40239
telemt_upstream_connect_success_total 37949
telemt_upstream_connect_fail_total 2153
telemt_upstream_connect_attempts_per_request{bucket="1"} 39965
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 23250
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14608
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 91
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2152
telemt_me_keepalive_timeout_total 11422
telemt_me_reconnect_attempts_total 35131
telemt_me_reconnect_success_total 26195
telemt_me_reader_eof_total 28235
telemt_me_idle_close_by_peer_total 28228
telemt_me_route_drop_no_conn_total 436314
telemt_me_route_drop_channel_closed_total 3
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1047939
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2076
telemt_desync_full_logged_total 672
telemt_desync_suppressed_total 1404
telemt_desync_frames_bucket_total{bucket="1_2"} 571
telemt_desync_frames_bucket_total{bucket="3_10"} 800
telemt_desync_frames_bucket_total{bucket="gt_10"} 705
telemt_pool_swap_total 102
telemt_me_writer_removed_unexpected_total 26656
telemt_me_refill_failed_total 274
telemt_me_writer_restored_same_endpoint_total 26171
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 461
telemt_user_connections_total{user="hello"} 1052858
telemt_user_connections_current{user="hello"} 532
telemt_user_octets_from_client{user="hello"} 16219318381 (15.11 GB)
telemt_user_octets_to_client{user="hello"} 419202597358 (390.41 GB)
telemt_user_msgs_from_client{user="hello"} 44500
telemt_user_msgs_to_client{user="hello"} 116355
telemt_user_unique_ips_current{user="hello"} 155
telemt_user_unique_ips_recent_window{user="hello"} 79
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 118769.3 (32h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1375864
telemt_connections_bad_total 20337
telemt_handshake_timeouts_total 11295
telemt_upstream_connect_attempt_total 37553
telemt_upstream_connect_success_total 37097
telemt_upstream_connect_fail_total 456
telemt_upstream_connect_attempts_per_request{bucket="1"} 37553
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18850
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18050
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 15
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 182
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 456
telemt_me_keepalive_timeout_total 2036
telemt_me_reconnect_attempts_total 44947
telemt_me_reconnect_success_total 31210
telemt_me_reader_eof_total 32763
telemt_me_idle_close_by_peer_total 32763
telemt_me_seq_mismatch_total 42
telemt_me_route_drop_no_conn_total 505228
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1268344
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 46
telemt_me_hardswap_pending_ttl_expired_total 16
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 4532
telemt_desync_full_logged_total 1629
telemt_desync_suppressed_total 2903
telemt_desync_frames_bucket_total{bucket="1_2"} 1372
telemt_desync_frames_bucket_total{bucket="3_10"} 1475
telemt_desync_frames_bucket_total{bucket="gt_10"} 1685
telemt_pool_swap_total 59
telemt_me_writer_removed_unexpected_total 31980
telemt_me_refill_failed_total 425
telemt_me_writer_restored_same_endpoint_total 31156
telemt_me_writer_restored_fallback_total 54
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 770
telemt_user_connections_total{user="hello"} 1268183
telemt_user_connections_current{user="hello"} 667
telemt_user_octets_from_client{user="hello"} 15648585996 (14.57 GB)
telemt_user_octets_to_client{user="hello"} 436480305776 (406.50 GB)
telemt_user_unique_ips_current{user="hello"} 184
telemt_user_unique_ips_recent_window{user="hello"} 93
```