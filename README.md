# Server Metrics 2026-03-13 22:44:34 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 146754.8 (40h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4541508
telemt_connections_bad_total 38374
telemt_handshake_timeouts_total 107137
telemt_upstream_connect_attempt_total 30588
telemt_upstream_connect_success_total 30378
telemt_upstream_connect_fail_total 210
telemt_upstream_connect_attempts_per_request{bucket="1"} 30588
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16679
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13555
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 144
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 210
telemt_me_keepalive_timeout_total 6641
telemt_me_reconnect_attempts_total 30856
telemt_me_reconnect_success_total 20732
telemt_me_reader_eof_total 22246
telemt_me_idle_close_by_peer_total 22245
telemt_me_route_drop_no_conn_total 1714846
telemt_me_route_drop_channel_closed_total 23
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4160487
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 16576
telemt_desync_full_logged_total 4462
telemt_desync_suppressed_total 12114
telemt_desync_frames_bucket_total{bucket="1_2"} 4126
telemt_desync_frames_bucket_total{bucket="3_10"} 6340
telemt_desync_frames_bucket_total{bucket="gt_10"} 6110
telemt_pool_swap_total 125
telemt_me_writer_removed_unexpected_total 21349
telemt_me_refill_failed_total 312
telemt_me_writer_restored_same_endpoint_total 20719
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 617
telemt_user_connections_total{user="hello"} 4162618
telemt_user_connections_current{user="hello"} 681
telemt_user_octets_from_client{user="hello"} 61112132636 (56.92 GB)
telemt_user_octets_to_client{user="hello"} 1315245033473 (1.20 TB)
telemt_user_msgs_from_client{user="hello"} 5023
telemt_user_msgs_to_client{user="hello"} 14147
telemt_user_unique_ips_current{user="hello"} 212
telemt_user_unique_ips_recent_window{user="hello"} 78
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 46418.5 (12h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 597022
telemt_connections_bad_total 43108
telemt_handshake_timeouts_total 12482
telemt_upstream_connect_attempt_total 13075
telemt_upstream_connect_success_total 12845
telemt_upstream_connect_fail_total 230
telemt_upstream_connect_attempts_per_request{bucket="1"} 13075
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7419
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5198
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 22
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 206
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 230
telemt_me_keepalive_timeout_total 1912
telemt_me_reconnect_attempts_total 11915
telemt_me_reconnect_success_total 8483
telemt_me_reader_eof_total 8987
telemt_me_idle_close_by_peer_total 8986
telemt_me_route_drop_no_conn_total 217458
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 516351
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
telemt_me_writer_removed_unexpected_total 8711
telemt_me_refill_failed_total 102
telemt_me_writer_restored_same_endpoint_total 8475
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 600
telemt_me_writer_removed_unexpected_minus_restored_total 228
telemt_user_connections_total{user="hello"} 518280
telemt_user_connections_current{user="hello"} 247
telemt_user_octets_from_client{user="hello"} 5718128037 (5.33 GB)
telemt_user_octets_to_client{user="hello"} 168777327672 (157.19 GB)
telemt_user_msgs_from_client{user="hello"} 6384
telemt_user_msgs_to_client{user="hello"} 14733
telemt_user_unique_ips_current{user="hello"} 90
telemt_user_unique_ips_recent_window{user="hello"} 25
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 176375.3 (48h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3298427
telemt_connections_bad_total 31815
telemt_handshake_timeouts_total 221028
telemt_upstream_connect_attempt_total 39072
telemt_upstream_connect_success_total 39051
telemt_upstream_connect_fail_total 21
telemt_upstream_connect_attempts_per_request{bucket="1"} 39072
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20339
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18485
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 220
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 21
telemt_me_keepalive_timeout_total 10301
telemt_me_reconnect_attempts_total 34918
telemt_me_reconnect_success_total 29966
telemt_me_reader_eof_total 31801
telemt_me_idle_close_by_peer_total 31800
telemt_me_route_drop_no_conn_total 1130666
telemt_me_route_drop_channel_closed_total 19
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2738941
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8993
telemt_desync_full_logged_total 3027
telemt_desync_suppressed_total 5966
telemt_desync_frames_bucket_total{bucket="1_2"} 1512
telemt_desync_frames_bucket_total{bucket="3_10"} 3258
telemt_desync_frames_bucket_total{bucket="gt_10"} 4223
telemt_pool_swap_total 163
telemt_me_writer_removed_unexpected_total 30407
telemt_me_refill_failed_total 149
telemt_me_writer_restored_same_endpoint_total 29925
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 441
telemt_user_connections_total{user="hello"} 2738200
telemt_user_connections_current{user="hello"} 326
telemt_user_octets_from_client{user="hello"} 44656169208 (41.59 GB)
telemt_user_octets_to_client{user="hello"} 968528061301 (902.01 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 138
telemt_user_unique_ips_recent_window{user="hello"} 48
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 176377.8 (48h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2160632
telemt_connections_bad_total 22840
telemt_handshake_timeouts_total 222120
telemt_upstream_connect_attempt_total 54930
telemt_upstream_connect_success_total 52481
telemt_upstream_connect_fail_total 2312
telemt_upstream_connect_attempts_per_request{bucket="1"} 54656
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 31469
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20846
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 166
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2311
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 20336
telemt_me_reconnect_attempts_total 45707
telemt_me_reconnect_success_total 36689
telemt_me_reader_eof_total 39339
telemt_me_idle_close_by_peer_total 39332
telemt_me_route_drop_no_conn_total 756514
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1759888
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
telemt_pool_swap_total 153
telemt_me_writer_removed_unexpected_total 37288
telemt_me_refill_failed_total 274
telemt_me_writer_restored_same_endpoint_total 36665
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 599
telemt_user_connections_total{user="hello"} 1765770
telemt_user_connections_current{user="hello"} 203
telemt_user_octets_from_client{user="hello"} 27308902447 (25.43 GB)
telemt_user_octets_to_client{user="hello"} 659363338330 (614.08 GB)
telemt_user_msgs_from_client{user="hello"} 50957
telemt_user_msgs_to_client{user="hello"} 129867
telemt_user_unique_ips_current{user="hello"} 89
telemt_user_unique_ips_recent_window{user="hello"} 32
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 45811.4 (12h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 641735
telemt_connections_bad_total 7781
telemt_handshake_timeouts_total 6600
telemt_upstream_connect_attempt_total 10369
telemt_upstream_connect_success_total 10037
telemt_upstream_connect_fail_total 332
telemt_upstream_connect_attempts_per_request{bucket="1"} 10369
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4802
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5210
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 332
telemt_me_keepalive_timeout_total 1431
telemt_me_reconnect_attempts_total 37463
telemt_me_reconnect_success_total 7747
telemt_me_reader_eof_total 8809
telemt_me_idle_close_by_peer_total 8808
telemt_me_route_drop_no_conn_total 243859
telemt_me_route_drop_channel_closed_total 13
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 598567
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 3
telemt_me_hardswap_pending_ttl_expired_total 9
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1590
telemt_desync_full_logged_total 496
telemt_desync_suppressed_total 1094
telemt_desync_frames_bucket_total{bucket="1_2"} 481
telemt_desync_frames_bucket_total{bucket="3_10"} 621
telemt_desync_frames_bucket_total{bucket="gt_10"} 488
telemt_pool_swap_total 11
telemt_me_writer_removed_unexpected_total 8747
telemt_me_refill_failed_total 925
telemt_me_writer_restored_same_endpoint_total 7742
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 1000
telemt_user_connections_total{user="hello"} 598475
telemt_user_connections_current{user="hello"} 389
telemt_user_octets_from_client{user="hello"} 9047117176 (8.43 GB)
telemt_user_octets_to_client{user="hello"} 196754991828 (183.24 GB)
telemt_user_unique_ips_current{user="hello"} 100
telemt_user_unique_ips_recent_window{user="hello"} 44
```