# Server Metrics 2026-03-14 01:43:29 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 157489.8 (43h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4642543
telemt_connections_bad_total 39797
telemt_handshake_timeouts_total 108204
telemt_upstream_connect_attempt_total 33243
telemt_upstream_connect_success_total 33022
telemt_upstream_connect_fail_total 221
telemt_upstream_connect_attempts_per_request{bucket="1"} 33243
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18036
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14841
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 145
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 221
telemt_me_keepalive_timeout_total 6704
telemt_me_reconnect_attempts_total 32993
telemt_me_reconnect_success_total 22856
telemt_me_reader_eof_total 24510
telemt_me_idle_close_by_peer_total 24509
telemt_me_route_drop_no_conn_total 1757821
telemt_me_route_drop_channel_closed_total 24
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4255931
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
telemt_me_writer_removed_unexpected_total 23502
telemt_me_refill_failed_total 312
telemt_me_writer_restored_same_endpoint_total 22843
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 646
telemt_user_connections_total{user="hello"} 4257788
telemt_user_connections_current{user="hello"} 549
telemt_user_octets_from_client{user="hello"} 62675039352 (58.37 GB)
telemt_user_octets_to_client{user="hello"} 1344850430181 (1.22 TB)
telemt_user_msgs_from_client{user="hello"} 5023
telemt_user_msgs_to_client{user="hello"} 14147
telemt_user_unique_ips_current{user="hello"} 206
telemt_user_unique_ips_recent_window{user="hello"} 70
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 57153.5 (15h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 682994
telemt_connections_bad_total 50959
telemt_handshake_timeouts_total 13005
telemt_upstream_connect_attempt_total 15931
telemt_upstream_connect_success_total 15682
telemt_upstream_connect_fail_total 249
telemt_upstream_connect_attempts_per_request{bucket="1"} 15931
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8784
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6661
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 26
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 211
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 249
telemt_me_keepalive_timeout_total 2053
telemt_me_reconnect_attempts_total 14234
telemt_me_reconnect_success_total 10791
telemt_me_reader_eof_total 11455
telemt_me_idle_close_by_peer_total 11454
telemt_me_route_drop_no_conn_total 230883
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 549735
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 6
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1651
telemt_desync_full_logged_total 449
telemt_desync_suppressed_total 1202
telemt_desync_frames_bucket_total{bucket="1_2"} 351
telemt_desync_frames_bucket_total{bucket="3_10"} 717
telemt_desync_frames_bucket_total{bucket="gt_10"} 583
telemt_pool_swap_total 48
telemt_me_writer_removed_unexpected_total 11051
telemt_me_refill_failed_total 102
telemt_me_writer_restored_same_endpoint_total 10783
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 600
telemt_me_writer_removed_unexpected_minus_restored_total 260
telemt_user_connections_total{user="hello"} 551686
telemt_user_connections_current{user="hello"} 155
telemt_user_octets_from_client{user="hello"} 5933852237 (5.53 GB)
telemt_user_octets_to_client{user="hello"} 177896601288 (165.68 GB)
telemt_user_msgs_from_client{user="hello"} 6384
telemt_user_msgs_to_client{user="hello"} 14733
telemt_user_unique_ips_current{user="hello"} 69
telemt_user_unique_ips_recent_window{user="hello"} 16
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 187110.2 (51h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3359544
telemt_connections_bad_total 34430
telemt_handshake_timeouts_total 223009
telemt_upstream_connect_attempt_total 42037
telemt_upstream_connect_success_total 42016
telemt_upstream_connect_fail_total 21
telemt_upstream_connect_attempts_per_request{bucket="1"} 42037
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 22050
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19731
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 228
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 21
telemt_me_keepalive_timeout_total 10407
telemt_me_reconnect_attempts_total 37361
telemt_me_reconnect_success_total 32401
telemt_me_reader_eof_total 34398
telemt_me_idle_close_by_peer_total 34397
telemt_me_route_drop_no_conn_total 1152380
telemt_me_route_drop_channel_closed_total 19
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2794230
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 9210
telemt_desync_full_logged_total 3090
telemt_desync_suppressed_total 6120
telemt_desync_frames_bucket_total{bucket="1_2"} 1562
telemt_desync_frames_bucket_total{bucket="3_10"} 3337
telemt_desync_frames_bucket_total{bucket="gt_10"} 4311
telemt_pool_swap_total 175
telemt_me_writer_removed_unexpected_total 32857
telemt_me_refill_failed_total 149
telemt_me_writer_restored_same_endpoint_total 32360
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 456
telemt_user_connections_total{user="hello"} 2793467
telemt_user_connections_current{user="hello"} 287
telemt_user_octets_from_client{user="hello"} 45035652876 (41.94 GB)
telemt_user_octets_to_client{user="hello"} 997209664365 (928.72 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 107
telemt_user_unique_ips_recent_window{user="hello"} 33
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 187112.9 (51h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2239768
telemt_connections_bad_total 22936
telemt_handshake_timeouts_total 242767
telemt_upstream_connect_attempt_total 58494
telemt_upstream_connect_success_total 56035
telemt_upstream_connect_fail_total 2322
telemt_upstream_connect_attempts_per_request{bucket="1"} 58220
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 33525
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 22344
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 166
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2321
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 20403
telemt_me_reconnect_attempts_total 48742
telemt_me_reconnect_success_total 39713
telemt_me_reader_eof_total 42567
telemt_me_idle_close_by_peer_total 42560
telemt_me_route_drop_no_conn_total 768809
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1791981
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3806
telemt_desync_full_logged_total 1223
telemt_desync_suppressed_total 2583
telemt_desync_frames_bucket_total{bucket="1_2"} 1012
telemt_desync_frames_bucket_total{bucket="3_10"} 1588
telemt_desync_frames_bucket_total{bucket="gt_10"} 1206
telemt_pool_swap_total 163
telemt_me_writer_removed_unexpected_total 40338
telemt_me_refill_failed_total 274
telemt_me_writer_restored_same_endpoint_total 39689
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 625
telemt_user_connections_total{user="hello"} 1797901
telemt_user_connections_current{user="hello"} 172
telemt_user_octets_from_client{user="hello"} 27456055203 (25.57 GB)
telemt_user_octets_to_client{user="hello"} 664832462746 (619.17 GB)
telemt_user_msgs_from_client{user="hello"} 50957
telemt_user_msgs_to_client{user="hello"} 129867
telemt_user_unique_ips_current{user="hello"} 79
telemt_user_unique_ips_recent_window{user="hello"} 25
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 56546.3 (15h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 687732
telemt_connections_bad_total 7890
telemt_handshake_timeouts_total 8636
telemt_upstream_connect_attempt_total 14166
telemt_upstream_connect_success_total 13771
telemt_upstream_connect_fail_total 395
telemt_upstream_connect_attempts_per_request{bucket="1"} 14166
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6633
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7113
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 395
telemt_me_keepalive_timeout_total 1491
telemt_me_reconnect_attempts_total 43107
telemt_me_reconnect_success_total 10948
telemt_me_reader_eof_total 12210
telemt_me_idle_close_by_peer_total 12209
telemt_me_route_drop_no_conn_total 260764
telemt_me_route_drop_channel_closed_total 13
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 640071
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
telemt_me_writer_removed_unexpected_total 12047
telemt_me_refill_failed_total 1001
telemt_me_writer_restored_same_endpoint_total 10943
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 1099
telemt_user_connections_total{user="hello"} 639964
telemt_user_connections_current{user="hello"} 252
telemt_user_octets_from_client{user="hello"} 10586109428 (9.86 GB)
telemt_user_octets_to_client{user="hello"} 209440677256 (195.06 GB)
telemt_user_unique_ips_current{user="hello"} 87
telemt_user_unique_ips_recent_window{user="hello"} 24
```