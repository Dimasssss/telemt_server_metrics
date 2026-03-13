# Server Metrics 2026-03-13 20:36:53 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 139096.0 (38h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4417294
telemt_connections_bad_total 37959
telemt_handshake_timeouts_total 106106
telemt_upstream_connect_attempt_total 29092
telemt_upstream_connect_success_total 28893
telemt_upstream_connect_fail_total 199
telemt_upstream_connect_attempts_per_request{bucket="1"} 29092
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15910
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12843
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 140
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 199
telemt_me_keepalive_timeout_total 6556
telemt_me_reconnect_attempts_total 29734
telemt_me_reconnect_success_total 19617
telemt_me_reader_eof_total 21052
telemt_me_idle_close_by_peer_total 21051
telemt_me_route_drop_no_conn_total 1663759
telemt_me_route_drop_channel_closed_total 23
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4043939
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 16085
telemt_desync_full_logged_total 4286
telemt_desync_suppressed_total 11799
telemt_desync_frames_bucket_total{bucket="1_2"} 4014
telemt_desync_frames_bucket_total{bucket="3_10"} 6131
telemt_desync_frames_bucket_total{bucket="gt_10"} 5940
telemt_pool_swap_total 118
telemt_me_writer_removed_unexpected_total 20214
telemt_me_refill_failed_total 312
telemt_me_writer_restored_same_endpoint_total 19604
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 597
telemt_user_connections_total{user="hello"} 4046077
telemt_user_connections_current{user="hello"} 1160
telemt_user_octets_from_client{user="hello"} 59690235272 (55.59 GB)
telemt_user_octets_to_client{user="hello"} 1277204694445 (1.16 TB)
telemt_user_msgs_from_client{user="hello"} 5023
telemt_user_msgs_to_client{user="hello"} 14147
telemt_user_unique_ips_current{user="hello"} 331
telemt_user_unique_ips_recent_window{user="hello"} 143
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 38759.8 (10h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 547696
telemt_connections_bad_total 41389
telemt_handshake_timeouts_total 12137
telemt_upstream_connect_attempt_total 11062
telemt_upstream_connect_success_total 10845
telemt_upstream_connect_fail_total 217
telemt_upstream_connect_attempts_per_request{bucket="1"} 11062
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6348
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4282
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 21
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 194
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 217
telemt_me_keepalive_timeout_total 1881
telemt_me_reconnect_attempts_total 10285
telemt_me_reconnect_success_total 6866
telemt_me_reader_eof_total 7262
telemt_me_idle_close_by_peer_total 7261
telemt_me_route_drop_no_conn_total 202793
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 475093
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 6
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1607
telemt_desync_full_logged_total 429
telemt_desync_suppressed_total 1178
telemt_desync_frames_bucket_total{bucket="1_2"} 343
telemt_desync_frames_bucket_total{bucket="3_10"} 699
telemt_desync_frames_bucket_total{bucket="gt_10"} 565
telemt_pool_swap_total 29
telemt_me_writer_removed_unexpected_total 7071
telemt_me_refill_failed_total 102
telemt_me_writer_restored_same_endpoint_total 6858
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 600
telemt_me_writer_removed_unexpected_minus_restored_total 205
telemt_user_connections_total{user="hello"} 477022
telemt_user_connections_current{user="hello"} 433
telemt_user_octets_from_client{user="hello"} 5125746025 (4.77 GB)
telemt_user_octets_to_client{user="hello"} 150927831800 (140.56 GB)
telemt_user_msgs_from_client{user="hello"} 6384
telemt_user_msgs_to_client{user="hello"} 14733
telemt_user_unique_ips_current{user="hello"} 137
telemt_user_unique_ips_recent_window{user="hello"} 64
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 168716.4 (46h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3215705
telemt_connections_bad_total 29697
telemt_handshake_timeouts_total 214486
telemt_upstream_connect_attempt_total 37546
telemt_upstream_connect_success_total 37526
telemt_upstream_connect_fail_total 20
telemt_upstream_connect_attempts_per_request{bucket="1"} 37546
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19505
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17816
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 199
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 20
telemt_me_keepalive_timeout_total 10222
telemt_me_reconnect_attempts_total 32429
telemt_me_reconnect_success_total 28798
telemt_me_reader_eof_total 30525
telemt_me_idle_close_by_peer_total 30524
telemt_me_route_drop_no_conn_total 1101802
telemt_me_route_drop_channel_closed_total 19
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2665835
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8810
telemt_desync_full_logged_total 2944
telemt_desync_suppressed_total 5866
telemt_desync_frames_bucket_total{bucket="1_2"} 1461
telemt_desync_frames_bucket_total{bucket="3_10"} 3219
telemt_desync_frames_bucket_total{bucket="gt_10"} 4130
telemt_pool_swap_total 156
telemt_me_writer_removed_unexpected_total 29180
telemt_me_refill_failed_total 108
telemt_me_writer_restored_same_endpoint_total 28757
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 382
telemt_user_connections_total{user="hello"} 2665117
telemt_user_connections_current{user="hello"} 654
telemt_user_octets_from_client{user="hello"} 43860370960 (40.85 GB)
telemt_user_octets_to_client{user="hello"} 937414154393 (873.03 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 207
telemt_user_unique_ips_recent_window{user="hello"} 91
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 168717.0 (46h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2086943
telemt_connections_bad_total 22697
telemt_handshake_timeouts_total 199469
telemt_upstream_connect_attempt_total 52643
telemt_upstream_connect_success_total 50204
telemt_upstream_connect_fail_total 2302
telemt_upstream_connect_attempts_per_request{bucket="1"} 52369
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 30188
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19852
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 164
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2301
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 20219
telemt_me_reconnect_attempts_total 43784
telemt_me_reconnect_success_total 34773
telemt_me_reader_eof_total 37330
telemt_me_idle_close_by_peer_total 37323
telemt_me_route_drop_no_conn_total 736931
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1718228
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3686
telemt_desync_full_logged_total 1179
telemt_desync_suppressed_total 2507
telemt_desync_frames_bucket_total{bucket="1_2"} 973
telemt_desync_frames_bucket_total{bucket="3_10"} 1530
telemt_desync_frames_bucket_total{bucket="gt_10"} 1183
telemt_pool_swap_total 148
telemt_me_writer_removed_unexpected_total 35350
telemt_me_refill_failed_total 274
telemt_me_writer_restored_same_endpoint_total 34749
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 577
telemt_user_connections_total{user="hello"} 1724100
telemt_user_connections_current{user="hello"} 394
telemt_user_octets_from_client{user="hello"} 26774724451 (24.94 GB)
telemt_user_octets_to_client{user="hello"} 645354304982 (601.03 GB)
telemt_user_msgs_from_client{user="hello"} 50957
telemt_user_msgs_to_client{user="hello"} 129867
telemt_user_unique_ips_current{user="hello"} 122
telemt_user_unique_ips_recent_window{user="hello"} 54
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 38152.4 (10h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 585794
telemt_connections_bad_total 5785
telemt_handshake_timeouts_total 5555
telemt_upstream_connect_attempt_total 8459
telemt_upstream_connect_success_total 8188
telemt_upstream_connect_fail_total 271
telemt_upstream_connect_attempts_per_request{bucket="1"} 8459
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3915
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4253
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 20
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 271
telemt_me_keepalive_timeout_total 969
telemt_me_reconnect_attempts_total 29499
telemt_me_reconnect_success_total 6255
telemt_me_reader_eof_total 7102
telemt_me_idle_close_by_peer_total 7101
telemt_me_route_drop_no_conn_total 221839
telemt_me_route_drop_channel_closed_total 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 549729
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 3
telemt_me_hardswap_pending_ttl_expired_total 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1482
telemt_desync_full_logged_total 459
telemt_desync_suppressed_total 1023
telemt_desync_frames_bucket_total{bucket="1_2"} 445
telemt_desync_frames_bucket_total{bucket="3_10"} 592
telemt_desync_frames_bucket_total{bucket="gt_10"} 445
telemt_pool_swap_total 10
telemt_me_writer_removed_unexpected_total 7038
telemt_me_refill_failed_total 724
telemt_me_writer_restored_same_endpoint_total 6251
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 783
telemt_user_connections_total{user="hello"} 549667
telemt_user_connections_current{user="hello"} 483
telemt_user_octets_from_client{user="hello"} 7819166652 (7.28 GB)
telemt_user_octets_to_client{user="hello"} 175050936060 (163.03 GB)
telemt_user_unique_ips_current{user="hello"} 141
telemt_user_unique_ips_recent_window{user="hello"} 60
```