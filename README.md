# Server Metrics 2026-03-14 02:03:55 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 158716.4 (44h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4654347
telemt_connections_bad_total 39808
telemt_handshake_timeouts_total 108317
telemt_upstream_connect_attempt_total 33551
telemt_upstream_connect_success_total 33326
telemt_upstream_connect_fail_total 225
telemt_upstream_connect_attempts_per_request{bucket="1"} 33551
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18199
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14982
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 145
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 225
telemt_me_keepalive_timeout_total 6708
telemt_me_reconnect_attempts_total 33211
telemt_me_reconnect_success_total 23073
telemt_me_reader_eof_total 24746
telemt_me_idle_close_by_peer_total 24745
telemt_me_route_drop_no_conn_total 1762324
telemt_me_route_drop_channel_closed_total 24
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4267176
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 16741
telemt_desync_full_logged_total 4512
telemt_desync_suppressed_total 12229
telemt_desync_frames_bucket_total{bucket="1_2"} 4184
telemt_desync_frames_bucket_total{bucket="3_10"} 6391
telemt_desync_frames_bucket_total{bucket="gt_10"} 6166
telemt_pool_swap_total 136
telemt_me_writer_removed_unexpected_total 23722
telemt_me_refill_failed_total 312
telemt_me_writer_restored_same_endpoint_total 23060
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 649
telemt_user_connections_total{user="hello"} 4269033
telemt_user_connections_current{user="hello"} 634
telemt_user_octets_from_client{user="hello"} 62749475116 (58.44 GB)
telemt_user_octets_to_client{user="hello"} 1347909584193 (1.23 TB)
telemt_user_msgs_from_client{user="hello"} 5023
telemt_user_msgs_to_client{user="hello"} 14147
telemt_user_unique_ips_current{user="hello"} 219
telemt_user_unique_ips_recent_window{user="hello"} 71
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 58380.1 (16h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 690624
telemt_connections_bad_total 50961
telemt_handshake_timeouts_total 13082
telemt_upstream_connect_attempt_total 16217
telemt_upstream_connect_success_total 15968
telemt_upstream_connect_fail_total 249
telemt_upstream_connect_attempts_per_request{bucket="1"} 16217
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8919
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6811
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 26
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 212
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 249
telemt_me_keepalive_timeout_total 2056
telemt_me_reconnect_attempts_total 14477
telemt_me_reconnect_success_total 11033
telemt_me_reader_eof_total 11710
telemt_me_idle_close_by_peer_total 11709
telemt_me_route_drop_no_conn_total 232030
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 553050
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 6
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1655
telemt_desync_full_logged_total 451
telemt_desync_suppressed_total 1204
telemt_desync_frames_bucket_total{bucket="1_2"} 354
telemt_desync_frames_bucket_total{bucket="3_10"} 718
telemt_desync_frames_bucket_total{bucket="gt_10"} 583
telemt_pool_swap_total 49
telemt_me_writer_removed_unexpected_total 11295
telemt_me_refill_failed_total 102
telemt_me_writer_restored_same_endpoint_total 11025
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 600
telemt_me_writer_removed_unexpected_minus_restored_total 262
telemt_user_connections_total{user="hello"} 555001
telemt_user_connections_current{user="hello"} 193
telemt_user_octets_from_client{user="hello"} 5954187297 (5.55 GB)
telemt_user_octets_to_client{user="hello"} 178675642952 (166.40 GB)
telemt_user_msgs_from_client{user="hello"} 6384
telemt_user_msgs_to_client{user="hello"} 14733
telemt_user_unique_ips_current{user="hello"} 77
telemt_user_unique_ips_recent_window{user="hello"} 28
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 188337.0 (52h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3366776
telemt_connections_bad_total 34940
telemt_handshake_timeouts_total 223195
telemt_upstream_connect_attempt_total 42390
telemt_upstream_connect_success_total 42369
telemt_upstream_connect_fail_total 21
telemt_upstream_connect_attempts_per_request{bucket="1"} 42390
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 22257
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19875
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 230
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 21
telemt_me_keepalive_timeout_total 10411
telemt_me_reconnect_attempts_total 37628
telemt_me_reconnect_success_total 32667
telemt_me_reader_eof_total 34694
telemt_me_idle_close_by_peer_total 34693
telemt_me_route_drop_no_conn_total 1154722
telemt_me_route_drop_channel_closed_total 19
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2800571
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 9238
telemt_desync_full_logged_total 3102
telemt_desync_suppressed_total 6136
telemt_desync_frames_bucket_total{bucket="1_2"} 1570
telemt_desync_frames_bucket_total{bucket="3_10"} 3346
telemt_desync_frames_bucket_total{bucket="gt_10"} 4322
telemt_pool_swap_total 177
telemt_me_writer_removed_unexpected_total 33128
telemt_me_refill_failed_total 149
telemt_me_writer_restored_same_endpoint_total 32626
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 461
telemt_user_connections_total{user="hello"} 2799805
telemt_user_connections_current{user="hello"} 277
telemt_user_octets_from_client{user="hello"} 45109428460 (42.01 GB)
telemt_user_octets_to_client{user="hello"} 1002580386077 (933.73 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 114
telemt_user_unique_ips_recent_window{user="hello"} 36
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 188339.4 (52h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2246069
telemt_connections_bad_total 22943
telemt_handshake_timeouts_total 244253
telemt_upstream_connect_attempt_total 58981
telemt_upstream_connect_success_total 56521
telemt_upstream_connect_fail_total 2323
telemt_upstream_connect_attempts_per_request{bucket="1"} 58707
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 33783
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 22572
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 166
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2322
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 20411
telemt_me_reconnect_attempts_total 49142
telemt_me_reconnect_success_total 40112
telemt_me_reader_eof_total 43019
telemt_me_idle_close_by_peer_total 43012
telemt_me_route_drop_no_conn_total 770054
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1795060
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3806
telemt_desync_full_logged_total 1223
telemt_desync_suppressed_total 2583
telemt_desync_frames_bucket_total{bucket="1_2"} 1012
telemt_desync_frames_bucket_total{bucket="3_10"} 1588
telemt_desync_frames_bucket_total{bucket="gt_10"} 1206
telemt_pool_swap_total 165
telemt_me_writer_removed_unexpected_total 40740
telemt_me_refill_failed_total 274
telemt_me_writer_restored_same_endpoint_total 40088
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 628
telemt_user_connections_total{user="hello"} 1800980
telemt_user_connections_current{user="hello"} 158
telemt_user_octets_from_client{user="hello"} 27504818031 (25.62 GB)
telemt_user_octets_to_client{user="hello"} 665416096154 (619.72 GB)
telemt_user_msgs_from_client{user="hello"} 50957
telemt_user_msgs_to_client{user="hello"} 129867
telemt_user_unique_ips_current{user="hello"} 73
telemt_user_unique_ips_recent_window{user="hello"} 24
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 57773.0 (16h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 691492
telemt_connections_bad_total 7904
telemt_handshake_timeouts_total 8651
telemt_upstream_connect_attempt_total 14549
telemt_upstream_connect_success_total 14145
telemt_upstream_connect_fail_total 404
telemt_upstream_connect_attempts_per_request{bucket="1"} 14549
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6805
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7315
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 404
telemt_me_keepalive_timeout_total 1497
telemt_me_reconnect_attempts_total 43395
telemt_me_reconnect_success_total 11232
telemt_me_reader_eof_total 12538
telemt_me_idle_close_by_peer_total 12537
telemt_me_route_drop_no_conn_total 262389
telemt_me_route_drop_channel_closed_total 13
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 643715
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 3
telemt_me_hardswap_pending_ttl_expired_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1657
telemt_desync_full_logged_total 519
telemt_desync_suppressed_total 1138
telemt_desync_frames_bucket_total{bucket="1_2"} 498
telemt_desync_frames_bucket_total{bucket="3_10"} 647
telemt_desync_frames_bucket_total{bucket="gt_10"} 512
telemt_pool_swap_total 18
telemt_me_writer_removed_unexpected_total 12336
telemt_me_refill_failed_total 1001
telemt_me_writer_restored_same_endpoint_total 11227
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 1104
telemt_user_connections_total{user="hello"} 643602
telemt_user_connections_current{user="hello"} 221
telemt_user_octets_from_client{user="hello"} 10600569820 (9.87 GB)
telemt_user_octets_to_client{user="hello"} 210109122052 (195.68 GB)
telemt_user_unique_ips_current{user="hello"} 88
telemt_user_unique_ips_recent_window{user="hello"} 32
```