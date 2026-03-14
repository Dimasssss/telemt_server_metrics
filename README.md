# Server Metrics 2026-03-14 03:56:24 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 165464.6 (45h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4733503
telemt_connections_bad_total 39890
telemt_handshake_timeouts_total 109296
telemt_upstream_connect_attempt_total 34961
telemt_upstream_connect_success_total 34731
telemt_upstream_connect_fail_total 230
telemt_upstream_connect_attempts_per_request{bucket="1"} 34961
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18932
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15653
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 146
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 230
telemt_me_keepalive_timeout_total 6739
telemt_me_reconnect_attempts_total 34313
telemt_me_reconnect_success_total 24171
telemt_me_reader_eof_total 25919
telemt_me_idle_close_by_peer_total 25918
telemt_me_route_drop_no_conn_total 1795974
telemt_me_route_drop_channel_closed_total 24
telemt_me_route_drop_queue_full_total 6
telemt_me_route_drop_queue_full_profile_total{profile="high"} 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4341730
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 16809
telemt_desync_full_logged_total 4535
telemt_desync_suppressed_total 12274
telemt_desync_frames_bucket_total{bucket="1_2"} 4197
telemt_desync_frames_bucket_total{bucket="3_10"} 6412
telemt_desync_frames_bucket_total{bucket="gt_10"} 6200
telemt_pool_swap_total 143
telemt_me_writer_removed_unexpected_total 24832
telemt_me_refill_failed_total 312
telemt_me_writer_restored_same_endpoint_total 24158
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 661
telemt_user_connections_total{user="hello"} 4343309
telemt_user_connections_current{user="hello"} 711
telemt_user_octets_from_client{user="hello"} 63591153732 (59.22 GB)
telemt_user_octets_to_client{user="hello"} 1370317955473 (1.25 TB)
telemt_user_msgs_from_client{user="hello"} 5023
telemt_user_msgs_to_client{user="hello"} 14147
telemt_user_unique_ips_current{user="hello"} 244
telemt_user_unique_ips_recent_window{user="hello"} 95
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 65128.1 (18h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 719030
telemt_connections_bad_total 52102
telemt_handshake_timeouts_total 13329
telemt_upstream_connect_attempt_total 18076
telemt_upstream_connect_success_total 17818
telemt_upstream_connect_fail_total 258
telemt_upstream_connect_attempts_per_request{bucket="1"} 18076
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9883
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7686
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 30
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 219
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 258
telemt_me_keepalive_timeout_total 2096
telemt_me_reconnect_attempts_total 15980
telemt_me_reconnect_success_total 12531
telemt_me_reader_eof_total 13308
telemt_me_idle_close_by_peer_total 13307
telemt_me_route_drop_no_conn_total 240800
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 576687
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 6
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1714
telemt_desync_full_logged_total 488
telemt_desync_suppressed_total 1226
telemt_desync_frames_bucket_total{bucket="1_2"} 363
telemt_desync_frames_bucket_total{bucket="3_10"} 757
telemt_desync_frames_bucket_total{bucket="gt_10"} 594
telemt_pool_swap_total 56
telemt_me_writer_removed_unexpected_total 12809
telemt_me_refill_failed_total 102
telemt_me_writer_restored_same_endpoint_total 12523
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 600
telemt_me_writer_removed_unexpected_minus_restored_total 278
telemt_user_connections_total{user="hello"} 578642
telemt_user_connections_current{user="hello"} 318
telemt_user_octets_from_client{user="hello"} 6172090209 (5.75 GB)
telemt_user_octets_to_client{user="hello"} 192346633084 (179.14 GB)
telemt_user_msgs_from_client{user="hello"} 6384
telemt_user_msgs_to_client{user="hello"} 14733
telemt_user_unique_ips_current{user="hello"} 108
telemt_user_unique_ips_recent_window{user="hello"} 36
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 195084.8 (54h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3411976
telemt_connections_bad_total 36461
telemt_handshake_timeouts_total 224153
telemt_upstream_connect_attempt_total 44100
telemt_upstream_connect_success_total 44079
telemt_upstream_connect_fail_total 21
telemt_upstream_connect_attempts_per_request{bucket="1"} 44100
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 23196
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20643
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 233
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 21
telemt_me_keepalive_timeout_total 10438
telemt_me_reconnect_attempts_total 39037
telemt_me_reconnect_success_total 34070
telemt_me_reader_eof_total 36188
telemt_me_idle_close_by_peer_total 36187
telemt_me_route_drop_no_conn_total 1167154
telemt_me_route_drop_channel_closed_total 19
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2842242
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 9400
telemt_desync_full_logged_total 3144
telemt_desync_suppressed_total 6256
telemt_desync_frames_bucket_total{bucket="1_2"} 1621
telemt_desync_frames_bucket_total{bucket="3_10"} 3398
telemt_desync_frames_bucket_total{bucket="gt_10"} 4381
telemt_pool_swap_total 184
telemt_me_writer_removed_unexpected_total 34545
telemt_me_refill_failed_total 149
telemt_me_writer_restored_same_endpoint_total 34029
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 475
telemt_user_connections_total{user="hello"} 2841460
telemt_user_connections_current{user="hello"} 382
telemt_user_octets_from_client{user="hello"} 45529658184 (42.40 GB)
telemt_user_octets_to_client{user="hello"} 1019492914337 (949.48 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 150
telemt_user_unique_ips_recent_window{user="hello"} 53
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 195087.5 (54h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2287305
telemt_connections_bad_total 23014
telemt_handshake_timeouts_total 254051
telemt_upstream_connect_attempt_total 61124
telemt_upstream_connect_success_total 58655
telemt_upstream_connect_fail_total 2332
telemt_upstream_connect_attempts_per_request{bucket="1"} 60850
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 35066
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 23423
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 166
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2331
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 20450
telemt_me_reconnect_attempts_total 50969
telemt_me_reconnect_success_total 41934
telemt_me_reader_eof_total 44973
telemt_me_idle_close_by_peer_total 44966
telemt_me_route_drop_no_conn_total 777755
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1817769
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3846
telemt_desync_full_logged_total 1236
telemt_desync_suppressed_total 2610
telemt_desync_frames_bucket_total{bucket="1_2"} 1031
telemt_desync_frames_bucket_total{bucket="3_10"} 1596
telemt_desync_frames_bucket_total{bucket="gt_10"} 1219
telemt_pool_swap_total 172
telemt_me_writer_removed_unexpected_total 42573
telemt_me_refill_failed_total 274
telemt_me_writer_restored_same_endpoint_total 41910
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 639
telemt_user_connections_total{user="hello"} 1823713
telemt_user_connections_current{user="hello"} 256
telemt_user_octets_from_client{user="hello"} 27694929483 (25.79 GB)
telemt_user_octets_to_client{user="hello"} 672042924738 (625.89 GB)
telemt_user_msgs_from_client{user="hello"} 50957
telemt_user_msgs_to_client{user="hello"} 129867
telemt_user_unique_ips_current{user="hello"} 95
telemt_user_unique_ips_recent_window{user="hello"} 32
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 64521.2 (17h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 718808
telemt_connections_bad_total 7961
telemt_handshake_timeouts_total 8709
telemt_upstream_connect_attempt_total 16755
telemt_upstream_connect_success_total 16306
telemt_upstream_connect_fail_total 449
telemt_upstream_connect_attempts_per_request{bucket="1"} 16755
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7738
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8542
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 26
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 449
telemt_me_keepalive_timeout_total 1527
telemt_me_reconnect_attempts_total 51843
telemt_me_reconnect_success_total 13087
telemt_me_reader_eof_total 14609
telemt_me_idle_close_by_peer_total 14608
telemt_me_route_drop_no_conn_total 273814
telemt_me_route_drop_channel_closed_total 13
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 670416
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 3
telemt_me_hardswap_pending_ttl_expired_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1709
telemt_desync_full_logged_total 536
telemt_desync_suppressed_total 1173
telemt_desync_frames_bucket_total{bucket="1_2"} 512
telemt_desync_frames_bucket_total{bucket="3_10"} 663
telemt_desync_frames_bucket_total{bucket="gt_10"} 534
telemt_pool_swap_total 18
telemt_me_writer_removed_unexpected_total 14407
telemt_me_refill_failed_total 1207
telemt_me_writer_restored_same_endpoint_total 13082
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 1320
telemt_user_connections_total{user="hello"} 670288
telemt_user_connections_current{user="hello"} 357
telemt_user_octets_from_client{user="hello"} 12225725740 (11.39 GB)
telemt_user_octets_to_client{user="hello"} 216856736112 (201.96 GB)
telemt_user_unique_ips_current{user="hello"} 120
telemt_user_unique_ips_recent_window{user="hello"} 44
```