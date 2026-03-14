# Server Metrics 2026-03-14 01:28:09 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 156569.8 (43h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4634529
telemt_connections_bad_total 39795
telemt_handshake_timeouts_total 108108
telemt_upstream_connect_attempt_total 33070
telemt_upstream_connect_success_total 32850
telemt_upstream_connect_fail_total 220
telemt_upstream_connect_attempts_per_request{bucket="1"} 33070
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17948
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14757
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 145
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 220
telemt_me_keepalive_timeout_total 6701
telemt_me_reconnect_attempts_total 32864
telemt_me_reconnect_success_total 22729
telemt_me_reader_eof_total 24371
telemt_me_idle_close_by_peer_total 24370
telemt_me_route_drop_no_conn_total 1754631
telemt_me_route_drop_channel_closed_total 24
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4248342
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 16707
telemt_desync_full_logged_total 4504
telemt_desync_suppressed_total 12203
telemt_desync_frames_bucket_total{bucket="1_2"} 4173
telemt_desync_frames_bucket_total{bucket="3_10"} 6379
telemt_desync_frames_bucket_total{bucket="gt_10"} 6155
telemt_pool_swap_total 133
telemt_me_writer_removed_unexpected_total 23371
telemt_me_refill_failed_total 312
telemt_me_writer_restored_same_endpoint_total 22716
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 642
telemt_user_connections_total{user="hello"} 4250199
telemt_user_connections_current{user="hello"} 524
telemt_user_octets_from_client{user="hello"} 62613349612 (58.31 GB)
telemt_user_octets_to_client{user="hello"} 1343244462957 (1.22 TB)
telemt_user_msgs_from_client{user="hello"} 5023
telemt_user_msgs_to_client{user="hello"} 14147
telemt_user_unique_ips_current{user="hello"} 205
telemt_user_unique_ips_recent_window{user="hello"} 61
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 56233.4 (15h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 678359
telemt_connections_bad_total 50946
telemt_handshake_timeouts_total 12966
telemt_upstream_connect_attempt_total 15718
telemt_upstream_connect_success_total 15470
telemt_upstream_connect_fail_total 248
telemt_upstream_connect_attempts_per_request{bucket="1"} 15718
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8686
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6550
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 24
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 210
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 248
telemt_me_keepalive_timeout_total 2051
telemt_me_reconnect_attempts_total 14065
telemt_me_reconnect_success_total 10621
telemt_me_reader_eof_total 11271
telemt_me_idle_close_by_peer_total 11270
telemt_me_route_drop_no_conn_total 230096
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 546691
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 6
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1650
telemt_desync_full_logged_total 448
telemt_desync_suppressed_total 1202
telemt_desync_frames_bucket_total{bucket="1_2"} 351
telemt_desync_frames_bucket_total{bucket="3_10"} 716
telemt_desync_frames_bucket_total{bucket="gt_10"} 583
telemt_pool_swap_total 47
telemt_me_writer_removed_unexpected_total 10877
telemt_me_refill_failed_total 102
telemt_me_writer_restored_same_endpoint_total 10613
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 600
telemt_me_writer_removed_unexpected_minus_restored_total 256
telemt_user_connections_total{user="hello"} 548642
telemt_user_connections_current{user="hello"} 188
telemt_user_octets_from_client{user="hello"} 5926484605 (5.52 GB)
telemt_user_octets_to_client{user="hello"} 177602532040 (165.41 GB)
telemt_user_msgs_from_client{user="hello"} 6384
telemt_user_msgs_to_client{user="hello"} 14733
telemt_user_unique_ips_current{user="hello"} 68
telemt_user_unique_ips_recent_window{user="hello"} 25
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 186190.1 (51h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3354376
telemt_connections_bad_total 34317
telemt_handshake_timeouts_total 222886
telemt_upstream_connect_attempt_total 41801
telemt_upstream_connect_success_total 41780
telemt_upstream_connect_fail_total 21
telemt_upstream_connect_attempts_per_request{bucket="1"} 41801
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21912
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19634
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 227
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 21
telemt_me_keepalive_timeout_total 10404
telemt_me_reconnect_attempts_total 37169
telemt_me_reconnect_success_total 32210
telemt_me_reader_eof_total 34194
telemt_me_idle_close_by_peer_total 34193
telemt_me_route_drop_no_conn_total 1151059
telemt_me_route_drop_channel_closed_total 19
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2789356
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 9170
telemt_desync_full_logged_total 3081
telemt_desync_suppressed_total 6089
telemt_desync_frames_bucket_total{bucket="1_2"} 1545
telemt_desync_frames_bucket_total{bucket="3_10"} 3320
telemt_desync_frames_bucket_total{bucket="gt_10"} 4305
telemt_pool_swap_total 174
telemt_me_writer_removed_unexpected_total 32665
telemt_me_refill_failed_total 149
telemt_me_writer_restored_same_endpoint_total 32169
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 455
telemt_user_connections_total{user="hello"} 2788594
telemt_user_connections_current{user="hello"} 274
telemt_user_octets_from_client{user="hello"} 44981094632 (41.89 GB)
telemt_user_octets_to_client{user="hello"} 994001323065 (925.74 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 113
telemt_user_unique_ips_recent_window{user="hello"} 43
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 186192.8 (51h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2233682
telemt_connections_bad_total 22928
telemt_handshake_timeouts_total 241755
telemt_upstream_connect_attempt_total 58092
telemt_upstream_connect_success_total 55633
telemt_upstream_connect_fail_total 2322
telemt_upstream_connect_attempts_per_request{bucket="1"} 57818
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 33299
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 22168
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 166
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2321
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 20395
telemt_me_reconnect_attempts_total 48384
telemt_me_reconnect_success_total 39356
telemt_me_reader_eof_total 42211
telemt_me_idle_close_by_peer_total 42204
telemt_me_route_drop_no_conn_total 768007
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1789556
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3801
telemt_desync_full_logged_total 1221
telemt_desync_suppressed_total 2580
telemt_desync_frames_bucket_total{bucket="1_2"} 1007
telemt_desync_frames_bucket_total{bucket="3_10"} 1588
telemt_desync_frames_bucket_total{bucket="gt_10"} 1206
telemt_pool_swap_total 163
telemt_me_writer_removed_unexpected_total 39981
telemt_me_refill_failed_total 274
telemt_me_writer_restored_same_endpoint_total 39332
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 625
telemt_user_connections_total{user="hello"} 1795472
telemt_user_connections_current{user="hello"} 145
telemt_user_octets_from_client{user="hello"} 27420903879 (25.54 GB)
telemt_user_octets_to_client{user="hello"} 664424542986 (618.79 GB)
telemt_user_msgs_from_client{user="hello"} 50957
telemt_user_msgs_to_client{user="hello"} 129867
telemt_user_unique_ips_current{user="hello"} 71
telemt_user_unique_ips_recent_window{user="hello"} 19
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 55626.2 (15h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 684626
telemt_connections_bad_total 7887
telemt_handshake_timeouts_total 8626
telemt_upstream_connect_attempt_total 13832
telemt_upstream_connect_success_total 13447
telemt_upstream_connect_fail_total 385
telemt_upstream_connect_attempts_per_request{bucket="1"} 13832
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6471
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6951
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 385
telemt_me_keepalive_timeout_total 1486
telemt_me_reconnect_attempts_total 42826
telemt_me_reconnect_success_total 10666
telemt_me_reader_eof_total 11927
telemt_me_idle_close_by_peer_total 11926
telemt_me_route_drop_no_conn_total 259552
telemt_me_route_drop_channel_closed_total 13
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 637066
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 3
telemt_me_hardswap_pending_ttl_expired_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1640
telemt_desync_full_logged_total 514
telemt_desync_suppressed_total 1126
telemt_desync_frames_bucket_total{bucket="1_2"} 493
telemt_desync_frames_bucket_total{bucket="3_10"} 642
telemt_desync_frames_bucket_total{bucket="gt_10"} 505
telemt_pool_swap_total 16
telemt_me_writer_removed_unexpected_total 11764
telemt_me_refill_failed_total 1001
telemt_me_writer_restored_same_endpoint_total 10661
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 1098
telemt_user_connections_total{user="hello"} 636959
telemt_user_connections_current{user="hello"} 187
telemt_user_octets_from_client{user="hello"} 10573015700 (9.85 GB)
telemt_user_octets_to_client{user="hello"} 208037302416 (193.75 GB)
telemt_user_unique_ips_current{user="hello"} 72
telemt_user_unique_ips_recent_window{user="hello"} 26
```