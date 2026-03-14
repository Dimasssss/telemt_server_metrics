# Server Metrics 2026-03-14 01:33:15 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 156876.7 (43h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4637118
telemt_connections_bad_total 39797
telemt_handshake_timeouts_total 108137
telemt_upstream_connect_attempt_total 33176
telemt_upstream_connect_success_total 32955
telemt_upstream_connect_fail_total 221
telemt_upstream_connect_attempts_per_request{bucket="1"} 33176
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18006
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14804
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 145
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 221
telemt_me_keepalive_timeout_total 6701
telemt_me_reconnect_attempts_total 32926
telemt_me_reconnect_success_total 22789
telemt_me_reader_eof_total 24441
telemt_me_idle_close_by_peer_total 24440
telemt_me_route_drop_no_conn_total 1755487
telemt_me_route_drop_channel_closed_total 24
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4250784
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 16707
telemt_desync_full_logged_total 4504
telemt_desync_suppressed_total 12203
telemt_desync_frames_bucket_total{bucket="1_2"} 4173
telemt_desync_frames_bucket_total{bucket="3_10"} 6379
telemt_desync_frames_bucket_total{bucket="gt_10"} 6155
telemt_pool_swap_total 134
telemt_me_writer_removed_unexpected_total 23433
telemt_me_refill_failed_total 312
telemt_me_writer_restored_same_endpoint_total 22776
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 644
telemt_user_connections_total{user="hello"} 4252641
telemt_user_connections_current{user="hello"} 516
telemt_user_octets_from_client{user="hello"} 62631957136 (58.33 GB)
telemt_user_octets_to_client{user="hello"} 1343934252145 (1.22 TB)
telemt_user_msgs_from_client{user="hello"} 5023
telemt_user_msgs_to_client{user="hello"} 14147
telemt_user_unique_ips_current{user="hello"} 198
telemt_user_unique_ips_recent_window{user="hello"} 59
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 56540.1 (15h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 680710
telemt_connections_bad_total 50958
telemt_handshake_timeouts_total 12996
telemt_upstream_connect_attempt_total 15766
telemt_upstream_connect_success_total 15518
telemt_upstream_connect_fail_total 248
telemt_upstream_connect_attempts_per_request{bucket="1"} 15766
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8706
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6577
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 25
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 210
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 248
telemt_me_keepalive_timeout_total 2053
telemt_me_reconnect_attempts_total 14113
telemt_me_reconnect_success_total 10670
telemt_me_reader_eof_total 11321
telemt_me_idle_close_by_peer_total 11320
telemt_me_route_drop_no_conn_total 230243
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 547812
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 6
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1650
telemt_desync_full_logged_total 448
telemt_desync_suppressed_total 1202
telemt_desync_frames_bucket_total{bucket="1_2"} 351
telemt_desync_frames_bucket_total{bucket="3_10"} 716
telemt_desync_frames_bucket_total{bucket="gt_10"} 583
telemt_pool_swap_total 47
telemt_me_writer_removed_unexpected_total 10927
telemt_me_refill_failed_total 102
telemt_me_writer_restored_same_endpoint_total 10662
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 600
telemt_me_writer_removed_unexpected_minus_restored_total 257
telemt_user_connections_total{user="hello"} 549763
telemt_user_connections_current{user="hello"} 187
telemt_user_octets_from_client{user="hello"} 5929326801 (5.52 GB)
telemt_user_octets_to_client{user="hello"} 177698892164 (165.49 GB)
telemt_user_msgs_from_client{user="hello"} 6384
telemt_user_msgs_to_client{user="hello"} 14733
telemt_user_unique_ips_current{user="hello"} 70
telemt_user_unique_ips_recent_window{user="hello"} 24
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 186497.0 (51h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3356188
telemt_connections_bad_total 34430
telemt_handshake_timeouts_total 222898
telemt_upstream_connect_attempt_total 41914
telemt_upstream_connect_success_total 41893
telemt_upstream_connect_fail_total 21
telemt_upstream_connect_attempts_per_request{bucket="1"} 41914
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21975
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19683
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 228
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 21
telemt_me_keepalive_timeout_total 10404
telemt_me_reconnect_attempts_total 37238
telemt_me_reconnect_success_total 32279
telemt_me_reader_eof_total 34275
telemt_me_idle_close_by_peer_total 34274
telemt_me_route_drop_no_conn_total 1151335
telemt_me_route_drop_channel_closed_total 19
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2791000
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 9192
telemt_desync_full_logged_total 3084
telemt_desync_suppressed_total 6108
telemt_desync_frames_bucket_total{bucket="1_2"} 1559
telemt_desync_frames_bucket_total{bucket="3_10"} 3327
telemt_desync_frames_bucket_total{bucket="gt_10"} 4306
telemt_pool_swap_total 175
telemt_me_writer_removed_unexpected_total 32734
telemt_me_refill_failed_total 149
telemt_me_writer_restored_same_endpoint_total 32238
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 455
telemt_user_connections_total{user="hello"} 2790238
telemt_user_connections_current{user="hello"} 361
telemt_user_octets_from_client{user="hello"} 45003640120 (41.91 GB)
telemt_user_octets_to_client{user="hello"} 994919962009 (926.59 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 120
telemt_user_unique_ips_recent_window{user="hello"} 49
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 186499.5 (51h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2235478
telemt_connections_bad_total 22936
telemt_handshake_timeouts_total 242104
telemt_upstream_connect_attempt_total 58220
telemt_upstream_connect_success_total 55761
telemt_upstream_connect_fail_total 2322
telemt_upstream_connect_attempts_per_request{bucket="1"} 57946
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 33373
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 22222
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 166
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2321
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 20396
telemt_me_reconnect_attempts_total 48468
telemt_me_reconnect_success_total 39440
telemt_me_reader_eof_total 42295
telemt_me_idle_close_by_peer_total 42288
telemt_me_route_drop_no_conn_total 768308
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1790310
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3801
telemt_desync_full_logged_total 1221
telemt_desync_suppressed_total 2580
telemt_desync_frames_bucket_total{bucket="1_2"} 1007
telemt_desync_frames_bucket_total{bucket="3_10"} 1588
telemt_desync_frames_bucket_total{bucket="gt_10"} 1206
telemt_pool_swap_total 163
telemt_me_writer_removed_unexpected_total 40065
telemt_me_refill_failed_total 274
telemt_me_writer_restored_same_endpoint_total 39416
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 625
telemt_user_connections_total{user="hello"} 1796225
telemt_user_connections_current{user="hello"} 173
telemt_user_octets_from_client{user="hello"} 27423358771 (25.54 GB)
telemt_user_octets_to_client{user="hello"} 664593541594 (618.95 GB)
telemt_user_msgs_from_client{user="hello"} 50957
telemt_user_msgs_to_client{user="hello"} 129867
telemt_user_unique_ips_current{user="hello"} 76
telemt_user_unique_ips_recent_window{user="hello"} 18
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 55933.0 (15h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 685658
telemt_connections_bad_total 7890
telemt_handshake_timeouts_total 8631
telemt_upstream_connect_attempt_total 13948
telemt_upstream_connect_success_total 13553
telemt_upstream_connect_fail_total 395
telemt_upstream_connect_attempts_per_request{bucket="1"} 13948
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6526
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7002
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 395
telemt_me_keepalive_timeout_total 1487
telemt_me_reconnect_attempts_total 42889
telemt_me_reconnect_success_total 10730
telemt_me_reader_eof_total 11990
telemt_me_idle_close_by_peer_total 11989
telemt_me_route_drop_no_conn_total 259788
telemt_me_route_drop_channel_closed_total 13
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 638059
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 3
telemt_me_hardswap_pending_ttl_expired_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1640
telemt_desync_full_logged_total 514
telemt_desync_suppressed_total 1126
telemt_desync_frames_bucket_total{bucket="1_2"} 493
telemt_desync_frames_bucket_total{bucket="3_10"} 642
telemt_desync_frames_bucket_total{bucket="gt_10"} 505
telemt_pool_swap_total 16
telemt_me_writer_removed_unexpected_total 11827
telemt_me_refill_failed_total 1001
telemt_me_writer_restored_same_endpoint_total 10725
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 1097
telemt_user_connections_total{user="hello"} 637952
telemt_user_connections_current{user="hello"} 234
telemt_user_octets_from_client{user="hello"} 10577521344 (9.85 GB)
telemt_user_octets_to_client{user="hello"} 208361883144 (194.05 GB)
telemt_user_unique_ips_current{user="hello"} 82
telemt_user_unique_ips_recent_window{user="hello"} 29
```