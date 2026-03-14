# Server Metrics 2026-03-14 06:40:09 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 175289.3 (48h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4934969
telemt_connections_bad_total 40202
telemt_handshake_timeouts_total 112893
telemt_upstream_connect_attempt_total 36794
telemt_upstream_connect_success_total 36555
telemt_upstream_connect_fail_total 239
telemt_upstream_connect_attempts_per_request{bucket="1"} 36794
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19866
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16541
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 148
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 239
telemt_me_keepalive_timeout_total 7327
telemt_me_reconnect_attempts_total 35662
telemt_me_reconnect_success_total 25512
telemt_me_reader_eof_total 27379
telemt_me_idle_close_by_peer_total 27378
telemt_me_route_drop_no_conn_total 1869208
telemt_me_route_drop_channel_closed_total 25
telemt_me_route_drop_queue_full_total 6
telemt_me_route_drop_queue_full_profile_total{profile="high"} 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4529130
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 17372
telemt_desync_full_logged_total 4704
telemt_desync_suppressed_total 12668
telemt_desync_frames_bucket_total{bucket="1_2"} 4334
telemt_desync_frames_bucket_total{bucket="3_10"} 6618
telemt_desync_frames_bucket_total{bucket="gt_10"} 6420
telemt_pool_swap_total 154
telemt_me_writer_removed_unexpected_total 26194
telemt_me_refill_failed_total 312
telemt_me_writer_restored_same_endpoint_total 25499
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 682
telemt_user_connections_total{user="hello"} 4530629
telemt_user_connections_current{user="hello"} 1341
telemt_user_octets_from_client{user="hello"} 66334934640 (61.78 GB)
telemt_user_octets_to_client{user="hello"} 1427861847909 (1.30 TB)
telemt_user_msgs_from_client{user="hello"} 5023
telemt_user_msgs_to_client{user="hello"} 14147
telemt_user_unique_ips_current{user="hello"} 405
telemt_user_unique_ips_recent_window{user="hello"} 168
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 74953.1 (20h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 816081
telemt_connections_bad_total 53807
telemt_handshake_timeouts_total 14928
telemt_upstream_connect_attempt_total 20361
telemt_upstream_connect_success_total 20090
telemt_upstream_connect_fail_total 271
telemt_upstream_connect_attempts_per_request{bucket="1"} 20361
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11044
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8781
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 33
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 232
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 271
telemt_me_keepalive_timeout_total 2142
telemt_me_reconnect_attempts_total 17779
telemt_me_reconnect_success_total 14315
telemt_me_reader_eof_total 15218
telemt_me_idle_close_by_peer_total 15217
telemt_me_route_drop_no_conn_total 267557
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 648429
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 6
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1876
telemt_desync_full_logged_total 569
telemt_desync_suppressed_total 1307
telemt_desync_frames_bucket_total{bucket="1_2"} 386
telemt_desync_frames_bucket_total{bucket="3_10"} 848
telemt_desync_frames_bucket_total{bucket="gt_10"} 642
telemt_pool_swap_total 66
telemt_me_writer_removed_unexpected_total 14627
telemt_me_refill_failed_total 102
telemt_me_writer_restored_same_endpoint_total 14307
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 600
telemt_me_writer_removed_unexpected_minus_restored_total 312
telemt_user_connections_total{user="hello"} 650346
telemt_user_connections_current{user="hello"} 551
telemt_user_octets_from_client{user="hello"} 6824655185 (6.36 GB)
telemt_user_octets_to_client{user="hello"} 219779975064 (204.69 GB)
telemt_user_msgs_from_client{user="hello"} 6384
telemt_user_msgs_to_client{user="hello"} 14733
telemt_user_unique_ips_current{user="hello"} 179
telemt_user_unique_ips_recent_window{user="hello"} 81
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 204909.6 (56h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3545276
telemt_connections_bad_total 41686
telemt_handshake_timeouts_total 233062
telemt_upstream_connect_attempt_total 46310
telemt_upstream_connect_success_total 46289
telemt_upstream_connect_fail_total 21
telemt_upstream_connect_attempts_per_request{bucket="1"} 46310
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 24407
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21634
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 241
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 21
telemt_me_keepalive_timeout_total 10664
telemt_me_reconnect_attempts_total 40766
telemt_me_reconnect_success_total 35791
telemt_me_reader_eof_total 38019
telemt_me_idle_close_by_peer_total 38018
telemt_me_route_drop_no_conn_total 1212327
telemt_me_route_drop_channel_closed_total 20
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2955567
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 9760
telemt_desync_full_logged_total 3273
telemt_desync_suppressed_total 6487
telemt_desync_frames_bucket_total{bucket="1_2"} 1699
telemt_desync_frames_bucket_total{bucket="3_10"} 3525
telemt_desync_frames_bucket_total{bucket="gt_10"} 4536
telemt_pool_swap_total 194
telemt_me_writer_removed_unexpected_total 36289
telemt_me_refill_failed_total 149
telemt_me_writer_restored_same_endpoint_total 35750
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 498
telemt_user_connections_total{user="hello"} 2954719
telemt_user_connections_current{user="hello"} 634
telemt_user_octets_from_client{user="hello"} 49123045884 (45.75 GB)
telemt_user_octets_to_client{user="hello"} 1056271052173 (983.73 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 216
telemt_user_unique_ips_recent_window{user="hello"} 112
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 204912.5 (56h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2366106
telemt_connections_bad_total 23292
telemt_handshake_timeouts_total 279314
telemt_upstream_connect_attempt_total 63859
telemt_upstream_connect_success_total 61370
telemt_upstream_connect_fail_total 2352
telemt_upstream_connect_attempts_per_request{bucket="1"} 63585
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 36640
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 24564
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 166
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2351
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 20513
telemt_me_reconnect_attempts_total 53208
telemt_me_reconnect_success_total 44162
telemt_me_reader_eof_total 47347
telemt_me_idle_close_by_peer_total 47340
telemt_me_route_drop_no_conn_total 797727
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1866879
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3906
telemt_desync_full_logged_total 1266
telemt_desync_suppressed_total 2640
telemt_desync_frames_bucket_total{bucket="1_2"} 1063
telemt_desync_frames_bucket_total{bucket="3_10"} 1617
telemt_desync_frames_bucket_total{bucket="gt_10"} 1226
telemt_pool_swap_total 182
telemt_me_writer_removed_unexpected_total 44828
telemt_me_refill_failed_total 274
telemt_me_writer_restored_same_endpoint_total 44138
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 666
telemt_user_connections_total{user="hello"} 1872928
telemt_user_connections_current{user="hello"} 314
telemt_user_octets_from_client{user="hello"} 28243274931 (26.30 GB)
telemt_user_octets_to_client{user="hello"} 689266413330 (641.93 GB)
telemt_user_msgs_from_client{user="hello"} 50957
telemt_user_msgs_to_client{user="hello"} 129867
telemt_user_unique_ips_current{user="hello"} 121
telemt_user_unique_ips_recent_window{user="hello"} 54
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 74345.8 (20h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 789107
telemt_connections_bad_total 8102
telemt_handshake_timeouts_total 9300
telemt_upstream_connect_attempt_total 18928
telemt_upstream_connect_success_total 18420
telemt_upstream_connect_fail_total 508
telemt_upstream_connect_attempts_per_request{bucket="1"} 18928
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8769
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9625
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 26
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 508
telemt_me_keepalive_timeout_total 1572
telemt_me_reconnect_attempts_total 60020
telemt_me_reconnect_success_total 14715
telemt_me_reader_eof_total 16494
telemt_me_idle_close_by_peer_total 16493
telemt_me_route_drop_no_conn_total 303926
telemt_me_route_drop_channel_closed_total 13
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 737086
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 3
telemt_me_hardswap_pending_ttl_expired_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1784
telemt_desync_full_logged_total 572
telemt_desync_suppressed_total 1212
telemt_desync_frames_bucket_total{bucket="1_2"} 532
telemt_desync_frames_bucket_total{bucket="3_10"} 691
telemt_desync_frames_bucket_total{bucket="gt_10"} 561
telemt_pool_swap_total 22
telemt_me_writer_removed_unexpected_total 16256
telemt_me_refill_failed_total 1411
telemt_me_writer_restored_same_endpoint_total 14710
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 1541
telemt_user_connections_total{user="hello"} 736949
telemt_user_connections_current{user="hello"} 561
telemt_user_octets_from_client{user="hello"} 13080264504 (12.18 GB)
telemt_user_octets_to_client{user="hello"} 247577205896 (230.57 GB)
telemt_user_unique_ips_current{user="hello"} 175
telemt_user_unique_ips_recent_window{user="hello"} 70
```