# Server Metrics 2026-03-14 07:46:38 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 179278.4 (49h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5062763
telemt_connections_bad_total 40351
telemt_handshake_timeouts_total 115752
telemt_upstream_connect_attempt_total 37721
telemt_upstream_connect_success_total 37476
telemt_upstream_connect_fail_total 245
telemt_upstream_connect_attempts_per_request{bucket="1"} 37721
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20336
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16990
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 150
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 245
telemt_me_keepalive_timeout_total 7365
telemt_me_reconnect_attempts_total 36941
telemt_me_reconnect_success_total 26211
telemt_me_reader_eof_total 28120
telemt_me_idle_close_by_peer_total 28119
telemt_me_route_drop_no_conn_total 1915147
telemt_me_route_drop_channel_closed_total 26
telemt_me_route_drop_queue_full_total 6
telemt_me_route_drop_queue_full_profile_total{profile="high"} 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4641583
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 17686
telemt_desync_full_logged_total 4810
telemt_desync_suppressed_total 12876
telemt_desync_frames_bucket_total{bucket="1_2"} 4407
telemt_desync_frames_bucket_total{bucket="3_10"} 6726
telemt_desync_frames_bucket_total{bucket="gt_10"} 6553
telemt_pool_swap_total 156
telemt_me_writer_removed_unexpected_total 26925
telemt_me_refill_failed_total 330
telemt_me_writer_restored_same_endpoint_total 26198
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 714
telemt_user_connections_total{user="hello"} 4643051
telemt_user_connections_current{user="hello"} 1357
telemt_user_octets_from_client{user="hello"} 70998983100 (66.12 GB)
telemt_user_octets_to_client{user="hello"} 1482753343565 (1.35 TB)
telemt_user_msgs_from_client{user="hello"} 5023
telemt_user_msgs_to_client{user="hello"} 14147
telemt_user_unique_ips_current{user="hello"} 428
telemt_user_unique_ips_recent_window{user="hello"} 177
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 78942.3 (21h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 862948
telemt_connections_bad_total 53906
telemt_handshake_timeouts_total 15670
telemt_upstream_connect_attempt_total 21200
telemt_upstream_connect_success_total 20926
telemt_upstream_connect_fail_total 274
telemt_upstream_connect_attempts_per_request{bucket="1"} 21200
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11423
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9228
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 36
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 239
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 274
telemt_me_keepalive_timeout_total 2147
telemt_me_reconnect_attempts_total 18443
telemt_me_reconnect_success_total 14977
telemt_me_reader_eof_total 15920
telemt_me_idle_close_by_peer_total 15919
telemt_me_route_drop_no_conn_total 284726
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 693032
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 6
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2067
telemt_desync_full_logged_total 642
telemt_desync_suppressed_total 1425
telemt_desync_frames_bucket_total{bucket="1_2"} 432
telemt_desync_frames_bucket_total{bucket="3_10"} 912
telemt_desync_frames_bucket_total{bucket="gt_10"} 723
telemt_pool_swap_total 70
telemt_me_writer_removed_unexpected_total 15299
telemt_me_refill_failed_total 102
telemt_me_writer_restored_same_endpoint_total 14969
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 600
telemt_me_writer_removed_unexpected_minus_restored_total 322
telemt_user_connections_total{user="hello"} 694941
telemt_user_connections_current{user="hello"} 530
telemt_user_octets_from_client{user="hello"} 7278396977 (6.78 GB)
telemt_user_octets_to_client{user="hello"} 240282551468 (223.78 GB)
telemt_user_msgs_from_client{user="hello"} 6384
telemt_user_msgs_to_client{user="hello"} 14733
telemt_user_unique_ips_current{user="hello"} 165
telemt_user_unique_ips_recent_window{user="hello"} 86
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 208898.9 (58h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3621856
telemt_connections_bad_total 42663
telemt_handshake_timeouts_total 237836
telemt_upstream_connect_attempt_total 47133
telemt_upstream_connect_success_total 47112
telemt_upstream_connect_fail_total 21
telemt_upstream_connect_attempts_per_request{bucket="1"} 47133
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 24859
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 22004
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 242
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 21
telemt_me_keepalive_timeout_total 10710
telemt_me_reconnect_attempts_total 41383
telemt_me_reconnect_success_total 36404
telemt_me_reader_eof_total 38660
telemt_me_idle_close_by_peer_total 38659
telemt_me_route_drop_no_conn_total 1240280
telemt_me_route_drop_channel_closed_total 20
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3021996
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 9953
telemt_desync_full_logged_total 3346
telemt_desync_suppressed_total 6607
telemt_desync_frames_bucket_total{bucket="1_2"} 1754
telemt_desync_frames_bucket_total{bucket="3_10"} 3599
telemt_desync_frames_bucket_total{bucket="gt_10"} 4600
telemt_pool_swap_total 197
telemt_me_writer_removed_unexpected_total 36909
telemt_me_refill_failed_total 149
telemt_me_writer_restored_same_endpoint_total 36363
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 505
telemt_user_connections_total{user="hello"} 3021134
telemt_user_connections_current{user="hello"} 796
telemt_user_octets_from_client{user="hello"} 50603042124 (47.13 GB)
telemt_user_octets_to_client{user="hello"} 1079352260253 (1005.23 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 251
telemt_user_unique_ips_recent_window{user="hello"} 116
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 208901.4 (58h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2410123
telemt_connections_bad_total 23311
telemt_handshake_timeouts_total 290719
telemt_upstream_connect_attempt_total 65139
telemt_upstream_connect_success_total 62646
telemt_upstream_connect_fail_total 2356
telemt_upstream_connect_attempts_per_request{bucket="1"} 64865
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 37397
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 25083
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 166
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2355
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 20541
telemt_me_reconnect_attempts_total 54305
telemt_me_reconnect_success_total 45224
telemt_me_reader_eof_total 48457
telemt_me_idle_close_by_peer_total 48450
telemt_me_route_drop_no_conn_total 810516
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1897220
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3928
telemt_desync_full_logged_total 1278
telemt_desync_suppressed_total 2650
telemt_desync_frames_bucket_total{bucket="1_2"} 1079
telemt_desync_frames_bucket_total{bucket="3_10"} 1618
telemt_desync_frames_bucket_total{bucket="gt_10"} 1231
telemt_pool_swap_total 184
telemt_me_writer_removed_unexpected_total 45895
telemt_me_refill_failed_total 275
telemt_me_writer_restored_same_endpoint_total 45200
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 671
telemt_user_connections_total{user="hello"} 1903322
telemt_user_connections_current{user="hello"} 458
telemt_user_octets_from_client{user="hello"} 28575062799 (26.61 GB)
telemt_user_octets_to_client{user="hello"} 695879491534 (648.09 GB)
telemt_user_msgs_from_client{user="hello"} 50957
telemt_user_msgs_to_client{user="hello"} 129867
telemt_user_unique_ips_current{user="hello"} 134
telemt_user_unique_ips_recent_window{user="hello"} 73
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 78335.1 (21h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 835949
telemt_connections_bad_total 8339
telemt_handshake_timeouts_total 9889
telemt_upstream_connect_attempt_total 19978
telemt_upstream_connect_success_total 19444
telemt_upstream_connect_fail_total 534
telemt_upstream_connect_attempts_per_request{bucket="1"} 19978
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9307
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10111
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 26
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 534
telemt_me_keepalive_timeout_total 1591
telemt_me_reconnect_attempts_total 63455
telemt_me_reconnect_success_total 15554
telemt_me_reader_eof_total 17423
telemt_me_idle_close_by_peer_total 17422
telemt_me_route_drop_no_conn_total 322189
telemt_me_route_drop_channel_closed_total 13
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 781198
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 3
telemt_me_hardswap_pending_ttl_expired_total 16
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1951
telemt_desync_full_logged_total 621
telemt_desync_suppressed_total 1330
telemt_desync_frames_bucket_total{bucket="1_2"} 609
telemt_desync_frames_bucket_total{bucket="3_10"} 741
telemt_desync_frames_bucket_total{bucket="gt_10"} 601
telemt_pool_swap_total 22
telemt_me_writer_removed_unexpected_total 17185
telemt_me_refill_failed_total 1492
telemt_me_writer_restored_same_endpoint_total 15549
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 1631
telemt_user_connections_total{user="hello"} 781057
telemt_user_connections_current{user="hello"} 656
telemt_user_octets_from_client{user="hello"} 13853368680 (12.90 GB)
telemt_user_octets_to_client{user="hello"} 263244522600 (245.17 GB)
telemt_user_unique_ips_current{user="hello"} 173
telemt_user_unique_ips_recent_window{user="hello"} 76
```