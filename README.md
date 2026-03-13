# Server Metrics 2026-03-13 22:54:47 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 147368.1 (40h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4548826
telemt_connections_bad_total 38380
telemt_handshake_timeouts_total 107371
telemt_upstream_connect_attempt_total 30805
telemt_upstream_connect_success_total 30595
telemt_upstream_connect_fail_total 210
telemt_upstream_connect_attempts_per_request{bucket="1"} 30805
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16797
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13654
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 144
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 210
telemt_me_keepalive_timeout_total 6642
telemt_me_reconnect_attempts_total 31047
telemt_me_reconnect_success_total 20922
telemt_me_reader_eof_total 22438
telemt_me_idle_close_by_peer_total 22437
telemt_me_route_drop_no_conn_total 1717415
telemt_me_route_drop_channel_closed_total 23
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4167339
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 16585
telemt_desync_full_logged_total 4466
telemt_desync_suppressed_total 12119
telemt_desync_frames_bucket_total{bucket="1_2"} 4130
telemt_desync_frames_bucket_total{bucket="3_10"} 6341
telemt_desync_frames_bucket_total{bucket="gt_10"} 6114
telemt_pool_swap_total 125
telemt_me_writer_removed_unexpected_total 21541
telemt_me_refill_failed_total 312
telemt_me_writer_restored_same_endpoint_total 20909
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 619
telemt_user_connections_total{user="hello"} 4169463
telemt_user_connections_current{user="hello"} 706
telemt_user_octets_from_client{user="hello"} 61161544456 (56.96 GB)
telemt_user_octets_to_client{user="hello"} 1316863388161 (1.20 TB)
telemt_user_msgs_from_client{user="hello"} 5023
telemt_user_msgs_to_client{user="hello"} 14147
telemt_user_unique_ips_current{user="hello"} 230
telemt_user_unique_ips_recent_window{user="hello"} 83
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 47031.9 (13h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 600595
telemt_connections_bad_total 43592
telemt_handshake_timeouts_total 12517
telemt_upstream_connect_attempt_total 13281
telemt_upstream_connect_success_total 13048
telemt_upstream_connect_fail_total 233
telemt_upstream_connect_attempts_per_request{bucket="1"} 13281
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7534
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5284
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 23
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 207
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 233
telemt_me_keepalive_timeout_total 1913
telemt_me_reconnect_attempts_total 12074
telemt_me_reconnect_success_total 8642
telemt_me_reader_eof_total 9149
telemt_me_idle_close_by_peer_total 9148
telemt_me_route_drop_no_conn_total 218275
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 519034
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 6
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1643
telemt_desync_full_logged_total 444
telemt_desync_suppressed_total 1199
telemt_desync_frames_bucket_total{bucket="1_2"} 348
telemt_desync_frames_bucket_total{bucket="3_10"} 712
telemt_desync_frames_bucket_total{bucket="gt_10"} 583
telemt_pool_swap_total 37
telemt_me_writer_removed_unexpected_total 8873
telemt_me_refill_failed_total 102
telemt_me_writer_restored_same_endpoint_total 8634
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 600
telemt_me_writer_removed_unexpected_minus_restored_total 231
telemt_user_connections_total{user="hello"} 520967
telemt_user_connections_current{user="hello"} 248
telemt_user_octets_from_client{user="hello"} 5755364049 (5.36 GB)
telemt_user_octets_to_client{user="hello"} 169449577560 (157.81 GB)
telemt_user_msgs_from_client{user="hello"} 6384
telemt_user_msgs_to_client{user="hello"} 14733
telemt_user_unique_ips_current{user="hello"} 92
telemt_user_unique_ips_recent_window{user="hello"} 42
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 176988.5 (49h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3301884
telemt_connections_bad_total 31829
telemt_handshake_timeouts_total 221066
telemt_upstream_connect_attempt_total 39264
telemt_upstream_connect_success_total 39243
telemt_upstream_connect_fail_total 21
telemt_upstream_connect_attempts_per_request{bucket="1"} 39264
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20455
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18561
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 220
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 21
telemt_me_keepalive_timeout_total 10304
telemt_me_reconnect_attempts_total 35066
telemt_me_reconnect_success_total 30114
telemt_me_reader_eof_total 31958
telemt_me_idle_close_by_peer_total 31957
telemt_me_route_drop_no_conn_total 1132403
telemt_me_route_drop_channel_closed_total 19
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2742320
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8998
telemt_desync_full_logged_total 3028
telemt_desync_suppressed_total 5970
telemt_desync_frames_bucket_total{bucket="1_2"} 1512
telemt_desync_frames_bucket_total{bucket="3_10"} 3260
telemt_desync_frames_bucket_total{bucket="gt_10"} 4226
telemt_pool_swap_total 164
telemt_me_writer_removed_unexpected_total 30555
telemt_me_refill_failed_total 149
telemt_me_writer_restored_same_endpoint_total 30073
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 441
telemt_user_connections_total{user="hello"} 2741579
telemt_user_connections_current{user="hello"} 366
telemt_user_octets_from_client{user="hello"} 44669912748 (41.60 GB)
telemt_user_octets_to_client{user="hello"} 969503324461 (902.92 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 134
telemt_user_unique_ips_recent_window{user="hello"} 58
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 176991.2 (49h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2165618
telemt_connections_bad_total 22843
telemt_handshake_timeouts_total 224003
telemt_upstream_connect_attempt_total 55163
telemt_upstream_connect_success_total 52714
telemt_upstream_connect_fail_total 2312
telemt_upstream_connect_attempts_per_request{bucket="1"} 54889
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 31602
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20946
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 166
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2311
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 20344
telemt_me_reconnect_attempts_total 45897
telemt_me_reconnect_success_total 36877
telemt_me_reader_eof_total 39555
telemt_me_idle_close_by_peer_total 39548
telemt_me_route_drop_no_conn_total 757782
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1762097
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3795
telemt_desync_full_logged_total 1216
telemt_desync_suppressed_total 2579
telemt_desync_frames_bucket_total{bucket="1_2"} 1002
telemt_desync_frames_bucket_total{bucket="3_10"} 1587
telemt_desync_frames_bucket_total{bucket="gt_10"} 1206
telemt_pool_swap_total 154
telemt_me_writer_removed_unexpected_total 37478
telemt_me_refill_failed_total 274
telemt_me_writer_restored_same_endpoint_total 36853
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 601
telemt_user_connections_total{user="hello"} 1767980
telemt_user_connections_current{user="hello"} 192
telemt_user_octets_from_client{user="hello"} 27318280191 (25.44 GB)
telemt_user_octets_to_client{user="hello"} 660596311110 (615.23 GB)
telemt_user_msgs_from_client{user="hello"} 50957
telemt_user_msgs_to_client{user="hello"} 129867
telemt_user_unique_ips_current{user="hello"} 91
telemt_user_unique_ips_recent_window{user="hello"} 36
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 46424.9 (12h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 645813
telemt_connections_bad_total 7841
telemt_handshake_timeouts_total 6642
telemt_upstream_connect_attempt_total 10542
telemt_upstream_connect_success_total 10207
telemt_upstream_connect_fail_total 335
telemt_upstream_connect_attempts_per_request{bucket="1"} 10542
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4882
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5300
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 335
telemt_me_keepalive_timeout_total 1432
telemt_me_reconnect_attempts_total 37590
telemt_me_reconnect_success_total 7873
telemt_me_reader_eof_total 8947
telemt_me_idle_close_by_peer_total 8946
telemt_me_route_drop_no_conn_total 245207
telemt_me_route_drop_channel_closed_total 13
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 601996
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 3
telemt_me_hardswap_pending_ttl_expired_total 10
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1598
telemt_desync_full_logged_total 500
telemt_desync_suppressed_total 1098
telemt_desync_frames_bucket_total{bucket="1_2"} 484
telemt_desync_frames_bucket_total{bucket="3_10"} 624
telemt_desync_frames_bucket_total{bucket="gt_10"} 490
telemt_pool_swap_total 12
telemt_me_writer_removed_unexpected_total 8873
telemt_me_refill_failed_total 925
telemt_me_writer_restored_same_endpoint_total 7868
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 1000
telemt_user_connections_total{user="hello"} 601902
telemt_user_connections_current{user="hello"} 347
telemt_user_octets_from_client{user="hello"} 9581659904 (8.92 GB)
telemt_user_octets_to_client{user="hello"} 197657762432 (184.08 GB)
telemt_user_unique_ips_current{user="hello"} 104
telemt_user_unique_ips_recent_window{user="hello"} 50
```