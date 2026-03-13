# Server Metrics 2026-03-13 13:28:25 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 113387.6 (31h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3426438
telemt_connections_bad_total 37373
telemt_handshake_timeouts_total 58856
telemt_upstream_connect_attempt_total 22227
telemt_upstream_connect_success_total 22104
telemt_upstream_connect_fail_total 123
telemt_upstream_connect_attempts_per_request{bucket="1"} 22227
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11407
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10639
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 58
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 123
telemt_me_keepalive_timeout_total 2109
telemt_me_reconnect_attempts_total 26562
telemt_me_reconnect_success_total 16478
telemt_me_reader_eof_total 17712
telemt_me_idle_close_by_peer_total 17711
telemt_me_route_drop_no_conn_total 1270993
telemt_me_route_drop_channel_closed_total 16
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3142987
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 13071
telemt_desync_full_logged_total 3416
telemt_desync_suppressed_total 9655
telemt_desync_frames_bucket_total{bucket="1_2"} 3312
telemt_desync_frames_bucket_total{bucket="3_10"} 4946
telemt_desync_frames_bucket_total{bucket="gt_10"} 4813
telemt_pool_swap_total 92
telemt_me_writer_removed_unexpected_total 17023
telemt_me_refill_failed_total 312
telemt_me_writer_restored_same_endpoint_total 16465
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 545
telemt_user_connections_total{user="hello"} 3142875
telemt_user_connections_current{user="hello"} 1974
telemt_user_octets_from_client{user="hello"} 43313916760 (40.34 GB)
telemt_user_octets_to_client{user="hello"} 1005518842288 (936.46 GB)
telemt_user_unique_ips_current{user="hello"} 512
telemt_user_unique_ips_recent_window{user="hello"} 344
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 13051.4 (3h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 181453
telemt_connections_bad_total 10249
telemt_handshake_timeouts_total 4638
telemt_upstream_connect_attempt_total 3133
telemt_upstream_connect_success_total 3057
telemt_upstream_connect_fail_total 76
telemt_upstream_connect_attempts_per_request{bucket="1"} 3133
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1566
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1462
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 10
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 19
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 76
telemt_me_keepalive_timeout_total 68
telemt_me_reconnect_attempts_total 3584
telemt_me_reconnect_success_total 2354
telemt_me_reader_eof_total 2481
telemt_me_idle_close_by_peer_total 2481
telemt_me_route_drop_no_conn_total 65587
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 162015
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 6
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 622
telemt_desync_full_logged_total 140
telemt_desync_suppressed_total 482
telemt_desync_frames_bucket_total{bucket="1_2"} 113
telemt_desync_frames_bucket_total{bucket="3_10"} 332
telemt_desync_frames_bucket_total{bucket="gt_10"} 177
telemt_pool_swap_total 11
telemt_me_writer_removed_unexpected_total 2412
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 2347
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 22
telemt_me_writer_removed_unexpected_minus_restored_total 58
telemt_user_connections_total{user="hello"} 162039
telemt_user_connections_current{user="hello"} 605
telemt_user_octets_from_client{user="hello"} 1630606524 (1.52 GB)
telemt_user_octets_to_client{user="hello"} 44640395092 (41.57 GB)
telemt_user_unique_ips_current{user="hello"} 197
telemt_user_unique_ips_recent_window{user="hello"} 149
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 143008.0 (39h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2578044
telemt_connections_bad_total 26826
telemt_handshake_timeouts_total 170996
telemt_upstream_connect_attempt_total 32398
telemt_upstream_connect_success_total 32388
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 32398
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16867
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15396
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 120
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_keepalive_timeout_total 3202
telemt_me_reconnect_attempts_total 27487
telemt_me_reconnect_success_total 24941
telemt_me_reader_eof_total 26442
telemt_me_idle_close_by_peer_total 26441
telemt_me_route_drop_no_conn_total 865553
telemt_me_route_drop_channel_closed_total 14
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2100435
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7294
telemt_desync_full_logged_total 2384
telemt_desync_suppressed_total 4910
telemt_desync_frames_bucket_total{bucket="1_2"} 1147
telemt_desync_frames_bucket_total{bucket="3_10"} 2664
telemt_desync_frames_bucket_total{bucket="gt_10"} 3483
telemt_pool_swap_total 133
telemt_me_writer_removed_unexpected_total 25231
telemt_me_refill_failed_total 75
telemt_me_writer_restored_same_endpoint_total 24900
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 290
telemt_user_connections_total{user="hello"} 2099860
telemt_user_connections_current{user="hello"} 1093
telemt_user_octets_from_client{user="hello"} 35135907828 (32.72 GB)
telemt_user_octets_to_client{user="hello"} 752387472325 (700.72 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 313
telemt_user_unique_ips_recent_window{user="hello"} 212
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 143008.5 (39h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1643645
telemt_connections_bad_total 17887
telemt_handshake_timeouts_total 116087
telemt_upstream_connect_attempt_total 45775
telemt_upstream_connect_success_total 43455
telemt_upstream_connect_fail_total 2183
telemt_upstream_connect_attempts_per_request{bucket="1"} 45501
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 26203
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17161
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 91
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2182
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 11832
telemt_me_reconnect_attempts_total 39461
telemt_me_reconnect_success_total 30495
telemt_me_reader_eof_total 32787
telemt_me_idle_close_by_peer_total 32780
telemt_me_route_drop_no_conn_total 585581
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1373728
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2754
telemt_desync_full_logged_total 899
telemt_desync_suppressed_total 1855
telemt_desync_frames_bucket_total{bucket="1_2"} 740
telemt_desync_frames_bucket_total{bucket="3_10"} 1139
telemt_desync_frames_bucket_total{bucket="gt_10"} 875
telemt_pool_swap_total 124
telemt_me_writer_removed_unexpected_total 30999
telemt_me_refill_failed_total 274
telemt_me_writer_restored_same_endpoint_total 30471
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 504
telemt_user_connections_total{user="hello"} 1378449
telemt_user_connections_current{user="hello"} 718
telemt_user_octets_from_client{user="hello"} 20973584505 (19.53 GB)
telemt_user_octets_to_client{user="hello"} 537080791442 (500.20 GB)
telemt_user_msgs_from_client{user="hello"} 44500
telemt_user_msgs_to_client{user="hello"} 116355
telemt_user_unique_ips_current{user="hello"} 214
telemt_user_unique_ips_recent_window{user="hello"} 117
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 12444.2 (3h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 195215
telemt_connections_bad_total 3846
telemt_handshake_timeouts_total 1683
telemt_upstream_connect_attempt_total 2510
telemt_upstream_connect_success_total 2426
telemt_upstream_connect_fail_total 84
telemt_upstream_connect_attempts_per_request{bucket="1"} 2510
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1127
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1297
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 84
telemt_me_keepalive_timeout_total 35
telemt_me_reconnect_attempts_total 9848
telemt_me_reconnect_success_total 1773
telemt_me_reader_eof_total 2029
telemt_me_idle_close_by_peer_total 2029
telemt_me_route_drop_no_conn_total 75514
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 182836
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 3
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 645
telemt_desync_full_logged_total 204
telemt_desync_suppressed_total 441
telemt_desync_frames_bucket_total{bucket="1_2"} 273
telemt_desync_frames_bucket_total{bucket="3_10"} 240
telemt_desync_frames_bucket_total{bucket="gt_10"} 132
telemt_pool_swap_total 3
telemt_me_writer_removed_unexpected_total 2025
telemt_me_refill_failed_total 251
telemt_me_writer_restored_same_endpoint_total 1769
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 252
telemt_user_connections_total{user="hello"} 182820
telemt_user_connections_current{user="hello"} 874
telemt_user_octets_from_client{user="hello"} 1934285840 (1.80 GB)
telemt_user_octets_to_client{user="hello"} 56132331500 (52.28 GB)
telemt_user_unique_ips_current{user="hello"} 217
telemt_user_unique_ips_recent_window{user="hello"} 170
```