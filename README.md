# Server Metrics 2026-03-12 16:47:36 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 38935.7 (10h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1407881
telemt_connections_bad_total 20252
telemt_handshake_timeouts_total 13391
telemt_upstream_connect_attempt_total 7854
telemt_upstream_connect_success_total 7809
telemt_upstream_connect_fail_total 45
telemt_upstream_connect_attempts_per_request{bucket="1"} 7854
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4108
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3679
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 22
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 45
telemt_me_keepalive_timeout_total 469
telemt_me_reconnect_attempts_total 12159
telemt_me_reconnect_success_total 5812
telemt_me_reader_eof_total 6246
telemt_me_idle_close_by_peer_total 6245
telemt_me_route_drop_no_conn_total 514211
telemt_me_route_drop_channel_closed_total 9
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1319818
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 6767
telemt_desync_full_logged_total 1697
telemt_desync_suppressed_total 5070
telemt_desync_frames_bucket_total{bucket="1_2"} 1750
telemt_desync_frames_bucket_total{bucket="3_10"} 2445
telemt_desync_frames_bucket_total{bucket="gt_10"} 2572
telemt_pool_swap_total 24
telemt_me_writer_removed_unexpected_total 6086
telemt_me_refill_failed_total 197
telemt_me_writer_restored_same_endpoint_total 5799
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 274
telemt_user_connections_total{user="hello"} 1319490
telemt_user_connections_current{user="hello"} 1832
telemt_user_octets_from_client{user="hello"} 20106559524 (18.73 GB)
telemt_user_octets_to_client{user="hello"} 383787092548 (357.43 GB)
telemt_user_unique_ips_current{user="hello"} 461
telemt_user_unique_ips_recent_window{user="hello"} 208
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 68556.2 (19h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 617174
telemt_connections_bad_total 8083
telemt_handshake_timeouts_total 28634
telemt_upstream_connect_attempt_total 16427
telemt_upstream_connect_success_total 16420
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 16427
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8182
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8221
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 17
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_keepalive_timeout_total 1283
telemt_me_reconnect_attempts_total 12865
telemt_me_reconnect_success_total 12792
telemt_me_reader_eof_total 13591
telemt_me_idle_close_by_peer_total 13591
telemt_me_route_drop_no_conn_total 188550
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 553248
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2241
telemt_desync_full_logged_total 705
telemt_desync_suppressed_total 1536
telemt_desync_frames_bucket_total{bucket="1_2"} 984
telemt_desync_frames_bucket_total{bucket="3_10"} 718
telemt_desync_frames_bucket_total{bucket="gt_10"} 539
telemt_pool_swap_total 68
telemt_me_writer_removed_unexpected_total 12919
telemt_me_writer_restored_same_endpoint_total 12783
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 127
telemt_user_connections_total{user="hello"} 553767
telemt_user_connections_current{user="hello"} 588
telemt_user_octets_from_client{user="hello"} 8526662039 (7.94 GB)
telemt_user_octets_to_client{user="hello"} 195633879350 (182.20 GB)
telemt_user_msgs_from_client{user="hello"} 353
telemt_user_msgs_to_client{user="hello"} 423
telemt_user_unique_ips_current{user="hello"} 183
telemt_user_unique_ips_recent_window{user="hello"} 78
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 68556.3 (19h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1297351
telemt_connections_bad_total 6411
telemt_handshake_timeouts_total 94510
telemt_upstream_connect_attempt_total 16362
telemt_upstream_connect_success_total 16357
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 16362
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8833
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7457
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 63
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 1080
telemt_me_reconnect_attempts_total 13780
telemt_me_reconnect_success_total 12547
telemt_me_reader_eof_total 13232
telemt_me_idle_close_by_peer_total 13231
telemt_me_route_drop_no_conn_total 362745
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 969148
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4162
telemt_desync_full_logged_total 1278
telemt_desync_suppressed_total 2884
telemt_desync_frames_bucket_total{bucket="1_2"} 650
telemt_desync_frames_bucket_total{bucket="3_10"} 1502
telemt_desync_frames_bucket_total{bucket="gt_10"} 2010
telemt_pool_swap_total 63
telemt_me_writer_removed_unexpected_total 12641
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 12506
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 94
telemt_user_connections_total{user="hello"} 969304
telemt_user_connections_current{user="hello"} 1250
telemt_user_octets_from_client{user="hello"} 14659013964 (13.65 GB)
telemt_user_octets_to_client{user="hello"} 308722794529 (287.52 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 318
telemt_user_unique_ips_recent_window{user="hello"} 142
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 68556.8 (19h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 778764
telemt_connections_bad_total 7733
telemt_handshake_timeouts_total 61201
telemt_upstream_connect_attempt_total 17923
telemt_upstream_connect_success_total 17852
telemt_upstream_connect_fail_total 71
telemt_upstream_connect_attempts_per_request{bucket="1"} 17923
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10104
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7735
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 13
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 71
telemt_me_keepalive_timeout_total 1519
telemt_me_reconnect_attempts_total 19649
telemt_me_reconnect_success_total 14399
telemt_me_reader_eof_total 15343
telemt_me_idle_close_by_peer_total 15343
telemt_me_route_drop_no_conn_total 269256
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 673748
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1404
telemt_desync_full_logged_total 474
telemt_desync_suppressed_total 930
telemt_desync_frames_bucket_total{bucket="1_2"} 385
telemt_desync_frames_bucket_total{bucket="3_10"} 557
telemt_desync_frames_bucket_total{bucket="gt_10"} 462
telemt_pool_swap_total 57
telemt_me_writer_removed_unexpected_total 14673
telemt_me_refill_failed_total 162
telemt_me_writer_restored_same_endpoint_total 14378
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 108
telemt_me_writer_removed_unexpected_minus_restored_total 274
telemt_user_connections_total{user="hello"} 673186
telemt_user_connections_current{user="hello"} 706
telemt_user_octets_from_client{user="hello"} 8311515256 (7.74 GB)
telemt_user_octets_to_client{user="hello"} 261979872064 (243.99 GB)
telemt_user_unique_ips_current{user="hello"} 191
telemt_user_unique_ips_recent_window{user="hello"} 97
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 68556.5 (19h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 880020
telemt_connections_bad_total 11390
telemt_handshake_timeouts_total 7208
telemt_upstream_connect_attempt_total 21630
telemt_upstream_connect_success_total 21365
telemt_upstream_connect_fail_total 264
telemt_upstream_connect_attempts_per_request{bucket="1"} 21629
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10917
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10332
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 108
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 264
telemt_me_keepalive_timeout_total 1240
telemt_me_reconnect_attempts_total 25159
telemt_me_reconnect_success_total 17912
telemt_me_reader_eof_total 18739
telemt_me_idle_close_by_peer_total 18739
telemt_me_seq_mismatch_total 33
telemt_me_route_drop_no_conn_total 314712
telemt_me_route_drop_channel_closed_total 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 808223
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 37
telemt_me_hardswap_pending_ttl_expired_total 9
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 3184
telemt_desync_full_logged_total 1082
telemt_desync_suppressed_total 2102
telemt_desync_frames_bucket_total{bucket="1_2"} 867
telemt_desync_frames_bucket_total{bucket="3_10"} 1085
telemt_desync_frames_bucket_total{bucket="gt_10"} 1232
telemt_pool_swap_total 32
telemt_me_writer_removed_unexpected_total 18333
telemt_me_refill_failed_total 224
telemt_me_writer_restored_same_endpoint_total 17868
telemt_me_writer_restored_fallback_total 44
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 421
telemt_user_connections_total{user="hello"} 808111
telemt_user_connections_current{user="hello"} 979
telemt_user_octets_from_client{user="hello"} 9984523860 (9.30 GB)
telemt_user_octets_to_client{user="hello"} 231716227104 (215.80 GB)
telemt_user_unique_ips_current{user="hello"} 239
telemt_user_unique_ips_recent_window{user="hello"} 104
```