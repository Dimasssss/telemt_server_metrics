# Server Metrics 2026-03-13 23:30:34 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 149515.0 (41h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4571692
telemt_connections_bad_total 38388
telemt_handshake_timeouts_total 107701
telemt_upstream_connect_attempt_total 31423
telemt_upstream_connect_success_total 31208
telemt_upstream_connect_fail_total 215
telemt_upstream_connect_attempts_per_request{bucket="1"} 31423
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17140
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13923
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 145
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 215
telemt_me_keepalive_timeout_total 6650
telemt_me_reconnect_attempts_total 31528
telemt_me_reconnect_success_total 21398
telemt_me_reader_eof_total 22939
telemt_me_idle_close_by_peer_total 22938
telemt_me_route_drop_no_conn_total 1727977
telemt_me_route_drop_channel_closed_total 23
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4189327
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 16595
telemt_desync_full_logged_total 4469
telemt_desync_suppressed_total 12126
telemt_desync_frames_bucket_total{bucket="1_2"} 4131
telemt_desync_frames_bucket_total{bucket="3_10"} 6349
telemt_desync_frames_bucket_total{bucket="gt_10"} 6115
telemt_pool_swap_total 127
telemt_me_writer_removed_unexpected_total 22024
telemt_me_refill_failed_total 312
telemt_me_writer_restored_same_endpoint_total 21385
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 626
telemt_user_connections_total{user="hello"} 4191251
telemt_user_connections_current{user="hello"} 622
telemt_user_octets_from_client{user="hello"} 61450727992 (57.23 GB)
telemt_user_octets_to_client{user="hello"} 1325525414525 (1.21 TB)
telemt_user_msgs_from_client{user="hello"} 5023
telemt_user_msgs_to_client{user="hello"} 14147
telemt_user_unique_ips_current{user="hello"} 204
telemt_user_unique_ips_recent_window{user="hello"} 74
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 49178.6 (13h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 611039
telemt_connections_bad_total 45285
telemt_handshake_timeouts_total 12583
telemt_upstream_connect_attempt_total 13914
telemt_upstream_connect_success_total 13676
telemt_upstream_connect_fail_total 238
telemt_upstream_connect_attempts_per_request{bucket="1"} 13914
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7835
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5607
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 24
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 210
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 238
telemt_me_keepalive_timeout_total 1923
telemt_me_reconnect_attempts_total 12617
telemt_me_reconnect_success_total 9179
telemt_me_reader_eof_total 9732
telemt_me_idle_close_by_peer_total 9731
telemt_me_route_drop_no_conn_total 221287
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 525830
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
telemt_pool_swap_total 39
telemt_me_writer_removed_unexpected_total 9421
telemt_me_refill_failed_total 102
telemt_me_writer_restored_same_endpoint_total 9171
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 600
telemt_me_writer_removed_unexpected_minus_restored_total 242
telemt_user_connections_total{user="hello"} 527781
telemt_user_connections_current{user="hello"} 185
telemt_user_octets_from_client{user="hello"} 5800072013 (5.40 GB)
telemt_user_octets_to_client{user="hello"} 172548908760 (160.70 GB)
telemt_user_msgs_from_client{user="hello"} 6384
telemt_user_msgs_to_client{user="hello"} 14733
telemt_user_unique_ips_current{user="hello"} 76
telemt_user_unique_ips_recent_window{user="hello"} 29
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 179135.3 (49h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3315929
telemt_connections_bad_total 32303
telemt_handshake_timeouts_total 221880
telemt_upstream_connect_attempt_total 39792
telemt_upstream_connect_success_total 39771
telemt_upstream_connect_fail_total 21
telemt_upstream_connect_attempts_per_request{bucket="1"} 39792
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20781
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18761
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 222
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 21
telemt_me_keepalive_timeout_total 10340
telemt_me_reconnect_attempts_total 35497
telemt_me_reconnect_success_total 30542
telemt_me_reader_eof_total 32416
telemt_me_idle_close_by_peer_total 32415
telemt_me_route_drop_no_conn_total 1137625
telemt_me_route_drop_channel_closed_total 19
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2754802
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 9026
telemt_desync_full_logged_total 3035
telemt_desync_suppressed_total 5991
telemt_desync_frames_bucket_total{bucket="1_2"} 1519
telemt_desync_frames_bucket_total{bucket="3_10"} 3269
telemt_desync_frames_bucket_total{bucket="gt_10"} 4238
telemt_pool_swap_total 166
telemt_me_writer_removed_unexpected_total 30991
telemt_me_refill_failed_total 149
telemt_me_writer_restored_same_endpoint_total 30501
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 449
telemt_user_connections_total{user="hello"} 2754054
telemt_user_connections_current{user="hello"} 391
telemt_user_octets_from_client{user="hello"} 44752599528 (41.68 GB)
telemt_user_octets_to_client{user="hello"} 974044777133 (907.15 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 136
telemt_user_unique_ips_recent_window{user="hello"} 52
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 179137.9 (49h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2181900
telemt_connections_bad_total 22853
telemt_handshake_timeouts_total 229646
telemt_upstream_connect_attempt_total 55784
telemt_upstream_connect_success_total 53332
telemt_upstream_connect_fail_total 2315
telemt_upstream_connect_attempts_per_request{bucket="1"} 55510
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 31966
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21200
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 166
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2314
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 20351
telemt_me_reconnect_attempts_total 46423
telemt_me_reconnect_success_total 37402
telemt_me_reader_eof_total 40111
telemt_me_idle_close_by_peer_total 40104
telemt_me_route_drop_no_conn_total 760839
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1768832
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
telemt_pool_swap_total 156
telemt_me_writer_removed_unexpected_total 38005
telemt_me_refill_failed_total 274
telemt_me_writer_restored_same_endpoint_total 37378
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 603
telemt_user_connections_total{user="hello"} 1774722
telemt_user_connections_current{user="hello"} 166
telemt_user_octets_from_client{user="hello"} 27343057531 (25.47 GB)
telemt_user_octets_to_client{user="hello"} 661200604026 (615.79 GB)
telemt_user_msgs_from_client{user="hello"} 50957
telemt_user_msgs_to_client{user="hello"} 129867
telemt_user_unique_ips_current{user="hello"} 82
telemt_user_unique_ips_recent_window{user="hello"} 20
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 48571.2 (13h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 656636
telemt_connections_bad_total 7858
telemt_handshake_timeouts_total 7508
telemt_upstream_connect_attempt_total 11410
telemt_upstream_connect_success_total 11064
telemt_upstream_connect_fail_total 346
telemt_upstream_connect_attempts_per_request{bucket="1"} 11410
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5307
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5732
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 346
telemt_me_keepalive_timeout_total 1441
telemt_me_reconnect_attempts_total 38360
telemt_me_reconnect_success_total 8639
telemt_me_reader_eof_total 9723
telemt_me_idle_close_by_peer_total 9722
telemt_me_route_drop_no_conn_total 248957
telemt_me_route_drop_channel_closed_total 13
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 611560
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 3
telemt_me_hardswap_pending_ttl_expired_total 10
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1611
telemt_desync_full_logged_total 507
telemt_desync_suppressed_total 1104
telemt_desync_frames_bucket_total{bucket="1_2"} 489
telemt_desync_frames_bucket_total{bucket="3_10"} 630
telemt_desync_frames_bucket_total{bucket="gt_10"} 492
telemt_pool_swap_total 12
telemt_me_writer_removed_unexpected_total 9649
telemt_me_refill_failed_total 925
telemt_me_writer_restored_same_endpoint_total 8634
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 1010
telemt_user_connections_total{user="hello"} 611459
telemt_user_connections_current{user="hello"} 235
telemt_user_octets_from_client{user="hello"} 9746495420 (9.08 GB)
telemt_user_octets_to_client{user="hello"} 200084903724 (186.34 GB)
telemt_user_unique_ips_current{user="hello"} 87
telemt_user_unique_ips_recent_window{user="hello"} 26
```