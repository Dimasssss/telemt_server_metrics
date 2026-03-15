# Server Metrics 2026-03-15 06:15:08 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.18

telemt_uptime_seconds 28839.1 (8h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 432327
telemt_connections_bad_total 6540
telemt_handshake_timeouts_total 2259
telemt_upstream_connect_attempt_total 6107
telemt_upstream_connect_success_total 6082
telemt_upstream_connect_fail_total 24
telemt_upstream_connect_attempts_per_request{bucket="1"} 6106
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3212
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2864
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 24
telemt_me_reconnect_attempts_total 4672
telemt_me_reconnect_success_total 4648
telemt_me_reader_eof_total 4903
telemt_me_idle_close_by_peer_total 4903
telemt_me_route_drop_no_conn_total 135291
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 375055
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 938
telemt_desync_full_logged_total 294
telemt_desync_suppressed_total 644
telemt_desync_frames_bucket_total{bucket="1_2"} 206
telemt_desync_frames_bucket_total{bucket="3_10"} 352
telemt_desync_frames_bucket_total{bucket="gt_10"} 380
telemt_pool_swap_total 27
telemt_me_writer_removed_unexpected_total 4699
telemt_me_writer_restored_same_endpoint_total 4637
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 296
telemt_me_writer_removed_unexpected_minus_restored_total 51
telemt_user_connections_total{user="hello"} 375069
telemt_user_connections_current{user="hello"} 1347
telemt_user_octets_from_client{user="hello"} 4300117992 (4.00 GB)
telemt_user_octets_to_client{user="hello"} 136126374364 (126.78 GB)
telemt_user_unique_ips_current{user="hello"} 436
telemt_user_unique_ips_recent_window{user="hello"} 172
```

## server2

```
telemt 3.3.18

telemt_uptime_seconds 28839.7 (8h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 160452
telemt_connections_bad_total 18312
telemt_handshake_timeouts_total 5347
telemt_upstream_connect_attempt_total 8269
telemt_upstream_connect_success_total 8230
telemt_upstream_connect_fail_total 39
telemt_upstream_connect_attempts_per_request{bucket="1"} 8269
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4484
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3686
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 17
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 43
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 39
telemt_me_reconnect_attempts_total 6507
telemt_me_reconnect_success_total 6475
telemt_me_reader_eof_total 6850
telemt_me_idle_close_by_peer_total 6850
telemt_me_route_drop_no_conn_total 38993
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 132127
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 16
telemt_me_endpoint_quarantine_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 377
telemt_desync_full_logged_total 142
telemt_desync_suppressed_total 235
telemt_desync_frames_bucket_total{bucket="1_2"} 108
telemt_desync_frames_bucket_total{bucket="3_10"} 141
telemt_desync_frames_bucket_total{bucket="gt_10"} 128
telemt_pool_swap_total 30
telemt_me_writer_removed_unexpected_total 6495
telemt_me_writer_restored_same_endpoint_total 6467
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 61
telemt_me_writer_removed_unexpected_minus_restored_total 20
telemt_user_connections_total{user="hello"} 132422
telemt_user_connections_current{user="hello"} 562
telemt_user_octets_from_client{user="hello"} 2226828875 (2.07 GB)
telemt_user_octets_to_client{user="hello"} 45551575512 (42.42 GB)
telemt_user_msgs_from_client{user="hello"} 620
telemt_user_msgs_to_client{user="hello"} 1332
telemt_user_unique_ips_current{user="hello"} 171
telemt_user_unique_ips_recent_window{user="hello"} 67
```

## server3

```
telemt 3.3.18

telemt_uptime_seconds 28839.8 (8h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 298002
telemt_connections_bad_total 7620
telemt_handshake_timeouts_total 29829
telemt_upstream_connect_attempt_total 6697
telemt_upstream_connect_success_total 6668
telemt_upstream_connect_fail_total 29
telemt_upstream_connect_attempts_per_request{bucket="1"} 6697
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3560
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3085
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 23
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 29
telemt_me_reconnect_attempts_total 5249
telemt_me_reconnect_success_total 5222
telemt_me_reader_eof_total 5518
telemt_me_idle_close_by_peer_total 5518
telemt_me_route_drop_no_conn_total 75115
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 248461
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 471
telemt_desync_full_logged_total 208
telemt_desync_suppressed_total 263
telemt_desync_frames_bucket_total{bucket="1_2"} 101
telemt_desync_frames_bucket_total{bucket="3_10"} 177
telemt_desync_frames_bucket_total{bucket="gt_10"} 193
telemt_pool_swap_total 29
telemt_me_writer_removed_unexpected_total 5278
telemt_me_writer_restored_same_endpoint_total 5203
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 242
telemt_me_writer_removed_unexpected_minus_restored_total 56
telemt_user_connections_total{user="hello"} 248263
telemt_user_connections_current{user="hello"} 793
telemt_user_octets_from_client{user="hello"} 4007044464 (3.73 GB)
telemt_user_octets_to_client{user="hello"} 103566090672 (96.45 GB)
telemt_user_unique_ips_current{user="hello"} 253
telemt_user_unique_ips_recent_window{user="hello"} 124
```

## server4

```
telemt 3.3.18

telemt_uptime_seconds 28839.7 (8h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 208592
telemt_connections_bad_total 38577
telemt_handshake_timeouts_total 13966
telemt_upstream_connect_attempt_total 9900
telemt_upstream_connect_success_total 9689
telemt_upstream_connect_fail_total 211
telemt_upstream_connect_attempts_per_request{bucket="1"} 9900
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4631
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5055
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 211
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 14242
telemt_me_reconnect_success_total 8250
telemt_me_reader_eof_total 8709
telemt_me_idle_close_by_peer_total 8709
telemt_me_seq_mismatch_total 10
telemt_me_route_drop_no_conn_total 49124
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 151892
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 27
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 243
telemt_desync_full_logged_total 63
telemt_desync_suppressed_total 180
telemt_desync_frames_bucket_total{bucket="1_2"} 71
telemt_desync_frames_bucket_total{bucket="3_10"} 101
telemt_desync_frames_bucket_total{bucket="gt_10"} 71
telemt_pool_swap_total 14
telemt_me_writer_removed_unexpected_total 8507
telemt_me_refill_failed_total 186
telemt_me_writer_restored_same_endpoint_total 8224
telemt_me_writer_restored_fallback_total 26
telemt_me_async_recovery_trigger_total 96
telemt_me_writer_removed_unexpected_minus_restored_total 257
telemt_user_connections_total{user="hello"} 151895
telemt_user_connections_current{user="hello"} 445
telemt_user_octets_from_client{user="hello"} 1318176324 (1.23 GB)
telemt_user_octets_to_client{user="hello"} 54682713292 (50.93 GB)
telemt_user_unique_ips_current{user="hello"} 147
telemt_user_unique_ips_recent_window{user="hello"} 63
```

## server5

```
telemt 3.3.18

telemt_uptime_seconds 28840.4 (8h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 145747
telemt_connections_bad_total 234
telemt_handshake_timeouts_total 1523
telemt_upstream_connect_attempt_total 6505
telemt_upstream_connect_success_total 6478
telemt_upstream_connect_fail_total 27
telemt_upstream_connect_attempts_per_request{bucket="1"} 6505
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2830
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3643
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 27
telemt_me_reconnect_attempts_total 5062
telemt_me_reconnect_success_total 5040
telemt_me_reader_eof_total 5377
telemt_me_idle_close_by_peer_total 5377
telemt_me_route_drop_no_conn_total 41079
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 137539
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 545
telemt_desync_full_logged_total 171
telemt_desync_suppressed_total 374
telemt_desync_frames_bucket_total{bucket="1_2"} 181
telemt_desync_frames_bucket_total{bucket="3_10"} 209
telemt_desync_frames_bucket_total{bucket="gt_10"} 155
telemt_pool_swap_total 31
telemt_me_writer_removed_unexpected_total 5090
telemt_me_writer_restored_same_endpoint_total 5032
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 54
telemt_me_writer_removed_unexpected_minus_restored_total 50
telemt_user_connections_total{user="hello"} 137558
telemt_user_connections_current{user="hello"} 685
telemt_user_octets_from_client{user="hello"} 1314040524 (1.22 GB)
telemt_user_octets_to_client{user="hello"} 47765687328 (44.49 GB)
telemt_user_unique_ips_current{user="hello"} 172
telemt_user_unique_ips_recent_window{user="hello"} 69
```