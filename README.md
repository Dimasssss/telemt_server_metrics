# Server Metrics 2026-03-13 12:37:27 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 110329.4 (30h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3290443
telemt_connections_bad_total 37018
telemt_handshake_timeouts_total 57367
telemt_upstream_connect_attempt_total 21787
telemt_upstream_connect_success_total 21667
telemt_upstream_connect_fail_total 120
telemt_upstream_connect_attempts_per_request{bucket="1"} 21787
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11160
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10450
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 57
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 120
telemt_me_keepalive_timeout_total 2101
telemt_me_reconnect_attempts_total 26254
telemt_me_reconnect_success_total 16172
telemt_me_reader_eof_total 17386
telemt_me_idle_close_by_peer_total 17385
telemt_me_route_drop_no_conn_total 1219652
telemt_me_route_drop_channel_closed_total 16
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3015590
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 12743
telemt_desync_full_logged_total 3306
telemt_desync_suppressed_total 9437
telemt_desync_frames_bucket_total{bucket="1_2"} 3252
telemt_desync_frames_bucket_total{bucket="3_10"} 4804
telemt_desync_frames_bucket_total{bucket="gt_10"} 4687
telemt_pool_swap_total 89
telemt_me_writer_removed_unexpected_total 16711
telemt_me_refill_failed_total 312
telemt_me_writer_restored_same_endpoint_total 16159
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 539
telemt_user_connections_total{user="hello"} 3015498
telemt_user_connections_current{user="hello"} 1690
telemt_user_octets_from_client{user="hello"} 41878275112 (39.00 GB)
telemt_user_octets_to_client{user="hello"} 972673634352 (905.87 GB)
telemt_user_unique_ips_current{user="hello"} 451
telemt_user_unique_ips_recent_window{user="hello"} 256
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 9993.2 (2h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 136411
telemt_connections_bad_total 7872
telemt_handshake_timeouts_total 3205
telemt_upstream_connect_attempt_total 2488
telemt_upstream_connect_success_total 2414
telemt_upstream_connect_fail_total 74
telemt_upstream_connect_attempts_per_request{bucket="1"} 2488
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1237
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1158
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 74
telemt_me_keepalive_timeout_total 60
telemt_me_reconnect_attempts_total 3069
telemt_me_reconnect_success_total 1843
telemt_me_reader_eof_total 1928
telemt_me_idle_close_by_peer_total 1928
telemt_me_route_drop_no_conn_total 48462
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 121916
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 6
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 300
telemt_desync_full_logged_total 79
telemt_desync_suppressed_total 221
telemt_desync_frames_bucket_total{bucket="1_2"} 59
telemt_desync_frames_bucket_total{bucket="3_10"} 140
telemt_desync_frames_bucket_total{bucket="gt_10"} 101
telemt_pool_swap_total 7
telemt_me_writer_removed_unexpected_total 1893
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 1836
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 22
telemt_me_writer_removed_unexpected_minus_restored_total 50
telemt_user_connections_total{user="hello"} 121940
telemt_user_connections_current{user="hello"} 593
telemt_user_octets_from_client{user="hello"} 1195925816 (1.11 GB)
telemt_user_octets_to_client{user="hello"} 32913994284 (30.65 GB)
telemt_user_unique_ips_current{user="hello"} 186
telemt_user_unique_ips_recent_window{user="hello"} 101
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 139949.9 (38h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2495357
telemt_connections_bad_total 26318
telemt_handshake_timeouts_total 164507
telemt_upstream_connect_attempt_total 31875
telemt_upstream_connect_success_total 31865
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 31875
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16629
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15111
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 120
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_keepalive_timeout_total 3179
telemt_me_reconnect_attempts_total 27093
telemt_me_reconnect_success_total 24547
telemt_me_reader_eof_total 26022
telemt_me_idle_close_by_peer_total 26021
telemt_me_route_drop_no_conn_total 833599
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2026348
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 6793
telemt_desync_full_logged_total 2193
telemt_desync_suppressed_total 4600
telemt_desync_frames_bucket_total{bucket="1_2"} 1066
telemt_desync_frames_bucket_total{bucket="3_10"} 2487
telemt_desync_frames_bucket_total{bucket="gt_10"} 3240
telemt_pool_swap_total 130
telemt_me_writer_removed_unexpected_total 24829
telemt_me_refill_failed_total 75
telemt_me_writer_restored_same_endpoint_total 24506
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 282
telemt_user_connections_total{user="hello"} 2025762
telemt_user_connections_current{user="hello"} 1089
telemt_user_octets_from_client{user="hello"} 34278360792 (31.92 GB)
telemt_user_octets_to_client{user="hello"} 728107091113 (678.10 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 291
telemt_user_unique_ips_recent_window{user="hello"} 175
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 139950.2 (38h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1590572
telemt_connections_bad_total 17869
telemt_handshake_timeouts_total 111556
telemt_upstream_connect_attempt_total 45199
telemt_upstream_connect_success_total 42879
telemt_upstream_connect_fail_total 2183
telemt_upstream_connect_attempts_per_request{bucket="1"} 44925
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 25893
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16895
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 91
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2182
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 11826
telemt_me_reconnect_attempts_total 39014
telemt_me_reconnect_success_total 30049
telemt_me_reader_eof_total 32315
telemt_me_idle_close_by_peer_total 32308
telemt_me_route_drop_no_conn_total 564965
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1326137
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2570
telemt_desync_full_logged_total 846
telemt_desync_suppressed_total 1724
telemt_desync_frames_bucket_total{bucket="1_2"} 692
telemt_desync_frames_bucket_total{bucket="3_10"} 1019
telemt_desync_frames_bucket_total{bucket="gt_10"} 859
telemt_pool_swap_total 121
telemt_me_writer_removed_unexpected_total 30550
telemt_me_refill_failed_total 274
telemt_me_writer_restored_same_endpoint_total 30025
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 501
telemt_user_connections_total{user="hello"} 1330860
telemt_user_connections_current{user="hello"} 638
telemt_user_octets_from_client{user="hello"} 19820791353 (18.46 GB)
telemt_user_octets_to_client{user="hello"} 518977164782 (483.34 GB)
telemt_user_msgs_from_client{user="hello"} 44500
telemt_user_msgs_to_client{user="hello"} 116355
telemt_user_unique_ips_current{user="hello"} 190
telemt_user_unique_ips_recent_window{user="hello"} 104
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 9386.2 (2h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 137765
telemt_connections_bad_total 1102
telemt_handshake_timeouts_total 1157
telemt_upstream_connect_attempt_total 1907
telemt_upstream_connect_success_total 1835
telemt_upstream_connect_fail_total 72
telemt_upstream_connect_attempts_per_request{bucket="1"} 1907
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 811
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1024
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 72
telemt_me_keepalive_timeout_total 27
telemt_me_reconnect_attempts_total 9386
telemt_me_reconnect_success_total 1315
telemt_me_reader_eof_total 1545
telemt_me_idle_close_by_peer_total 1545
telemt_me_route_drop_no_conn_total 54214
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 130849
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 3
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 492
telemt_desync_full_logged_total 163
telemt_desync_suppressed_total 329
telemt_desync_frames_bucket_total{bucket="1_2"} 235
telemt_desync_frames_bucket_total{bucket="3_10"} 164
telemt_desync_frames_bucket_total{bucket="gt_10"} 93
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 1561
telemt_me_refill_failed_total 251
telemt_me_writer_restored_same_endpoint_total 1311
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 246
telemt_user_connections_total{user="hello"} 130844
telemt_user_connections_current{user="hello"} 842
telemt_user_octets_from_client{user="hello"} 1466070212 (1.37 GB)
telemt_user_octets_to_client{user="hello"} 42721542144 (39.79 GB)
telemt_user_unique_ips_current{user="hello"} 220
telemt_user_unique_ips_recent_window{user="hello"} 126
```