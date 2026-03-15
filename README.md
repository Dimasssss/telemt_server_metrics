# Server Metrics 2026-03-15 15:21:33 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.18

telemt_uptime_seconds 61623.2 (17h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1975354
telemt_connections_bad_total 105852
telemt_handshake_timeouts_total 22442
telemt_upstream_connect_attempt_total 12311
telemt_upstream_connect_success_total 12259
telemt_upstream_connect_fail_total 52
telemt_upstream_connect_attempts_per_request{bucket="1"} 12311
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6384
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5828
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 47
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 52
telemt_me_keepalive_timeout_total 47
telemt_me_reconnect_attempts_total 14051
telemt_me_reconnect_success_total 9158
telemt_me_reader_eof_total 9794
telemt_me_idle_close_by_peer_total 9794
telemt_me_route_drop_no_conn_total 680129
telemt_me_route_drop_channel_closed_total 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1674238
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 6393
telemt_desync_full_logged_total 1769
telemt_desync_suppressed_total 4624
telemt_desync_frames_bucket_total{bucket="1_2"} 1579
telemt_desync_frames_bucket_total{bucket="3_10"} 2461
telemt_desync_frames_bucket_total{bucket="gt_10"} 2353
telemt_pool_swap_total 45
telemt_me_writer_removed_unexpected_total 9459
telemt_me_refill_failed_total 151
telemt_me_writer_restored_same_endpoint_total 9147
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 296
telemt_me_writer_removed_unexpected_minus_restored_total 301
telemt_user_connections_total{user="hello"} 1673746
telemt_user_connections_current{user="hello"} 2392
telemt_user_octets_from_client{user="hello"} 24602932488 (22.91 GB)
telemt_user_octets_to_client{user="hello"} 648291040932 (603.77 GB)
telemt_user_unique_ips_current{user="hello"} 685
telemt_user_unique_ips_recent_window{user="hello"} 298
```

## server2

```
telemt 3.3.18

telemt_uptime_seconds 61624.0 (17h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 789933
telemt_connections_bad_total 42368
telemt_handshake_timeouts_total 58982
telemt_upstream_connect_attempt_total 15605
telemt_upstream_connect_success_total 15530
telemt_upstream_connect_fail_total 75
telemt_upstream_connect_attempts_per_request{bucket="1"} 15605
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8287
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7100
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 37
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 106
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 75
telemt_me_keepalive_timeout_total 59
telemt_me_reconnect_attempts_total 12187
telemt_me_reconnect_success_total 12089
telemt_me_reader_eof_total 12777
telemt_me_idle_close_by_peer_total 12777
telemt_me_route_drop_no_conn_total 198396
telemt_me_route_drop_channel_closed_total 3
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 600026
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 16
telemt_me_endpoint_quarantine_total 17
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2006
telemt_desync_full_logged_total 693
telemt_desync_suppressed_total 1313
telemt_desync_frames_bucket_total{bucket="1_2"} 741
telemt_desync_frames_bucket_total{bucket="3_10"} 738
telemt_desync_frames_bucket_total{bucket="gt_10"} 527
telemt_pool_swap_total 51
telemt_me_writer_removed_unexpected_total 12246
telemt_me_writer_restored_same_endpoint_total 12077
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 61
telemt_me_writer_removed_unexpected_minus_restored_total 157
telemt_user_connections_total{user="hello"} 600277
telemt_user_connections_current{user="hello"} 749
telemt_user_octets_from_client{user="hello"} 8382041063 (7.81 GB)
telemt_user_octets_to_client{user="hello"} 226550535764 (210.99 GB)
telemt_user_msgs_from_client{user="hello"} 620
telemt_user_msgs_to_client{user="hello"} 1332
telemt_user_unique_ips_current{user="hello"} 219
telemt_user_unique_ips_recent_window{user="hello"} 116
```

## server3

```
telemt 3.3.18

telemt_uptime_seconds 61623.9 (17h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1768859
telemt_connections_bad_total 47332
telemt_handshake_timeouts_total 177025
telemt_upstream_connect_attempt_total 13525
telemt_upstream_connect_success_total 13461
telemt_upstream_connect_fail_total 64
telemt_upstream_connect_attempts_per_request{bucket="1"} 13525
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6937
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6460
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 64
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 64
telemt_me_keepalive_timeout_total 45
telemt_me_reconnect_attempts_total 11597
telemt_me_reconnect_success_total 10335
telemt_me_reader_eof_total 10954
telemt_me_idle_close_by_peer_total 10954
telemt_me_route_drop_no_conn_total 464276
telemt_me_route_drop_channel_closed_total 18
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1065423
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2641
telemt_desync_full_logged_total 969
telemt_desync_suppressed_total 1672
telemt_desync_frames_bucket_total{bucket="1_2"} 615
telemt_desync_frames_bucket_total{bucket="3_10"} 1023
telemt_desync_frames_bucket_total{bucket="gt_10"} 1003
telemt_pool_swap_total 53
telemt_me_writer_removed_unexpected_total 10519
telemt_me_refill_failed_total 37
telemt_me_writer_restored_same_endpoint_total 10316
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 242
telemt_me_writer_removed_unexpected_minus_restored_total 184
telemt_user_connections_total{user="hello"} 1061421
telemt_user_connections_current{user="hello"} 1321
telemt_user_octets_from_client{user="hello"} 15324137172 (14.27 GB)
telemt_user_octets_to_client{user="hello"} 381467773436 (355.27 GB)
telemt_user_unique_ips_current{user="hello"} 419
telemt_user_unique_ips_recent_window{user="hello"} 191
```

## server4

```
telemt 3.3.18

telemt_uptime_seconds 61624.0 (17h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 834650
telemt_connections_bad_total 75305
telemt_handshake_timeouts_total 42051
telemt_upstream_connect_attempt_total 167849
telemt_upstream_connect_success_total 167344
telemt_upstream_connect_fail_total 505
telemt_upstream_connect_attempts_per_request{bucket="1"} 167849
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 154912
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12400
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 32
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 505
telemt_me_keepalive_timeout_total 39
telemt_me_reconnect_attempts_total 52617
telemt_me_reconnect_success_total 12177
telemt_me_reader_eof_total 13775
telemt_me_idle_close_by_peer_total 13775
telemt_me_seq_mismatch_total 23
telemt_me_route_drop_no_conn_total 183705
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 489288
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 40
telemt_me_hardswap_pending_ttl_expired_total 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1326
telemt_desync_full_logged_total 346
telemt_desync_suppressed_total 980
telemt_desync_frames_bucket_total{bucket="1_2"} 356
telemt_desync_frames_bucket_total{bucket="3_10"} 531
telemt_desync_frames_bucket_total{bucket="gt_10"} 439
telemt_pool_swap_total 18
telemt_me_writer_removed_unexpected_total 13560
telemt_me_refill_failed_total 1265
telemt_me_writer_restored_same_endpoint_total 12143
telemt_me_writer_restored_fallback_total 34
telemt_me_async_recovery_trigger_total 96
telemt_me_writer_removed_unexpected_minus_restored_total 1383
telemt_user_connections_total{user="hello"} 640981
telemt_user_connections_current{user="hello"} 938
telemt_user_octets_from_client{user="hello"} 12775309062 (11.90 GB)
telemt_user_octets_to_client{user="hello"} 221967438309 (206.72 GB)
telemt_user_msgs_from_client{user="hello"} 3034166
telemt_user_msgs_to_client{user="hello"} 10923814
telemt_user_unique_ips_current{user="hello"} 243
telemt_user_unique_ips_recent_window{user="hello"} 130
```

## server5

```
telemt 3.3.18

telemt_uptime_seconds 61625.0 (17h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 845758
telemt_connections_bad_total 9431
telemt_handshake_timeouts_total 18159
telemt_upstream_connect_attempt_total 13687
telemt_upstream_connect_success_total 13610
telemt_upstream_connect_fail_total 77
telemt_upstream_connect_attempts_per_request{bucket="1"} 13687
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6300
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7299
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 77
telemt_me_keepalive_timeout_total 86
telemt_me_reconnect_attempts_total 14191
telemt_me_reconnect_success_total 10509
telemt_me_reader_eof_total 11214
telemt_me_idle_close_by_peer_total 11214
telemt_me_route_drop_no_conn_total 210317
telemt_me_route_drop_channel_closed_total 24
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 694746
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2426
telemt_desync_full_logged_total 820
telemt_desync_suppressed_total 1606
telemt_desync_frames_bucket_total{bucket="1_2"} 733
telemt_desync_frames_bucket_total{bucket="3_10"} 936
telemt_desync_frames_bucket_total{bucket="gt_10"} 757
telemt_pool_swap_total 51
telemt_me_writer_removed_unexpected_total 10748
telemt_me_refill_failed_total 113
telemt_me_writer_restored_same_endpoint_total 10501
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 54
telemt_me_writer_removed_unexpected_minus_restored_total 239
telemt_user_connections_total{user="hello"} 694788
telemt_user_connections_current{user="hello"} 819
telemt_user_octets_from_client{user="hello"} 8646500436 (8.05 GB)
telemt_user_octets_to_client{user="hello"} 253450933460 (236.04 GB)
telemt_user_unique_ips_current{user="hello"} 245
telemt_user_unique_ips_recent_window{user="hello"} 117
```