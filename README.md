# Server Metrics 2026-03-14 02:44:49 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 161170.4 (44h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4680024
telemt_connections_bad_total 39822
telemt_handshake_timeouts_total 108507
telemt_upstream_connect_attempt_total 34043
telemt_upstream_connect_success_total 33816
telemt_upstream_connect_fail_total 227
telemt_upstream_connect_attempts_per_request{bucket="1"} 34043
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18457
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15213
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 146
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 227
telemt_me_keepalive_timeout_total 6725
telemt_me_reconnect_attempts_total 33586
telemt_me_reconnect_success_total 23445
telemt_me_reader_eof_total 25144
telemt_me_idle_close_by_peer_total 25143
telemt_me_route_drop_no_conn_total 1779200
telemt_me_route_drop_channel_closed_total 24
telemt_me_route_drop_queue_full_total 6
telemt_me_route_drop_queue_full_profile_total{profile="high"} 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4292103
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 16759
telemt_desync_full_logged_total 4521
telemt_desync_suppressed_total 12238
telemt_desync_frames_bucket_total{bucket="1_2"} 4188
telemt_desync_frames_bucket_total{bucket="3_10"} 6394
telemt_desync_frames_bucket_total{bucket="gt_10"} 6177
telemt_pool_swap_total 138
telemt_me_writer_removed_unexpected_total 24100
telemt_me_refill_failed_total 312
telemt_me_writer_restored_same_endpoint_total 23432
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 655
telemt_user_connections_total{user="hello"} 4293704
telemt_user_connections_current{user="hello"} 606
telemt_user_octets_from_client{user="hello"} 62998280868 (58.67 GB)
telemt_user_octets_to_client{user="hello"} 1356727028205 (1.23 TB)
telemt_user_msgs_from_client{user="hello"} 5023
telemt_user_msgs_to_client{user="hello"} 14147
telemt_user_unique_ips_current{user="hello"} 223
telemt_user_unique_ips_recent_window{user="hello"} 63
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 60833.8 (16h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 699596
telemt_connections_bad_total 50973
telemt_handshake_timeouts_total 13123
telemt_upstream_connect_attempt_total 17007
telemt_upstream_connect_success_total 16755
telemt_upstream_connect_fail_total 252
telemt_upstream_connect_attempts_per_request{bucket="1"} 17007
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9342
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7172
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 29
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 212
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 252
telemt_me_keepalive_timeout_total 2082
telemt_me_reconnect_attempts_total 15133
telemt_me_reconnect_success_total 11687
telemt_me_reader_eof_total 12402
telemt_me_idle_close_by_peer_total 12401
telemt_me_route_drop_no_conn_total 235060
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 560442
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 6
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1685
telemt_desync_full_logged_total 464
telemt_desync_suppressed_total 1221
telemt_desync_frames_bucket_total{bucket="1_2"} 360
telemt_desync_frames_bucket_total{bucket="3_10"} 734
telemt_desync_frames_bucket_total{bucket="gt_10"} 591
telemt_pool_swap_total 51
telemt_me_writer_removed_unexpected_total 11954
telemt_me_refill_failed_total 102
telemt_me_writer_restored_same_endpoint_total 11679
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 600
telemt_me_writer_removed_unexpected_minus_restored_total 267
telemt_user_connections_total{user="hello"} 562400
telemt_user_connections_current{user="hello"} 162
telemt_user_octets_from_client{user="hello"} 5995233349 (5.58 GB)
telemt_user_octets_to_client{user="hello"} 180563647732 (168.16 GB)
telemt_user_msgs_from_client{user="hello"} 6384
telemt_user_msgs_to_client{user="hello"} 14733
telemt_user_unique_ips_current{user="hello"} 76
telemt_user_unique_ips_recent_window{user="hello"} 24
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 190790.6 (52h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3381386
telemt_connections_bad_total 34991
telemt_handshake_timeouts_total 223431
telemt_upstream_connect_attempt_total 42972
telemt_upstream_connect_success_total 42951
telemt_upstream_connect_fail_total 21
telemt_upstream_connect_attempts_per_request{bucket="1"} 42972
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 22562
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20151
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 231
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 21
telemt_me_keepalive_timeout_total 10425
telemt_me_reconnect_attempts_total 38124
telemt_me_reconnect_success_total 33161
telemt_me_reader_eof_total 35213
telemt_me_idle_close_by_peer_total 35212
telemt_me_route_drop_no_conn_total 1158884
telemt_me_route_drop_channel_closed_total 19
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2814495
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 9355
telemt_desync_full_logged_total 3124
telemt_desync_suppressed_total 6231
telemt_desync_frames_bucket_total{bucket="1_2"} 1610
telemt_desync_frames_bucket_total{bucket="3_10"} 3384
telemt_desync_frames_bucket_total{bucket="gt_10"} 4361
telemt_pool_swap_total 179
telemt_me_writer_removed_unexpected_total 33625
telemt_me_refill_failed_total 149
telemt_me_writer_restored_same_endpoint_total 33120
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 464
telemt_user_connections_total{user="hello"} 2813719
telemt_user_connections_current{user="hello"} 380
telemt_user_octets_from_client{user="hello"} 45201067524 (42.10 GB)
telemt_user_octets_to_client{user="hello"} 1005633891913 (936.57 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 144
telemt_user_unique_ips_recent_window{user="hello"} 43
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 190793.2 (52h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2259424
telemt_connections_bad_total 22973
telemt_handshake_timeouts_total 247312
telemt_upstream_connect_attempt_total 59784
telemt_upstream_connect_success_total 57321
telemt_upstream_connect_fail_total 2326
telemt_upstream_connect_attempts_per_request{bucket="1"} 59510
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 34267
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 22888
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 166
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2325
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 20427
telemt_me_reconnect_attempts_total 49853
telemt_me_reconnect_success_total 40820
telemt_me_reader_eof_total 43772
telemt_me_idle_close_by_peer_total 43765
telemt_me_route_drop_no_conn_total 772415
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1802139
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3809
telemt_desync_full_logged_total 1225
telemt_desync_suppressed_total 2584
telemt_desync_frames_bucket_total{bucket="1_2"} 1015
telemt_desync_frames_bucket_total{bucket="3_10"} 1588
telemt_desync_frames_bucket_total{bucket="gt_10"} 1206
telemt_pool_swap_total 167
telemt_me_writer_removed_unexpected_total 41454
telemt_me_refill_failed_total 274
telemt_me_writer_restored_same_endpoint_total 40796
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 634
telemt_user_connections_total{user="hello"} 1808071
telemt_user_connections_current{user="hello"} 184
telemt_user_octets_from_client{user="hello"} 27612050763 (25.72 GB)
telemt_user_octets_to_client{user="hello"} 667058945786 (621.25 GB)
telemt_user_msgs_from_client{user="hello"} 50957
telemt_user_msgs_to_client{user="hello"} 129867
telemt_user_unique_ips_current{user="hello"} 80
telemt_user_unique_ips_recent_window{user="hello"} 25
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 60226.5 (16h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 700198
telemt_connections_bad_total 7911
telemt_handshake_timeouts_total 8665
telemt_upstream_connect_attempt_total 15420
telemt_upstream_connect_success_total 15003
telemt_upstream_connect_fail_total 417
telemt_upstream_connect_attempts_per_request{bucket="1"} 15420
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7219
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7759
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 417
telemt_me_keepalive_timeout_total 1506
telemt_me_reconnect_attempts_total 44166
telemt_me_reconnect_success_total 12003
telemt_me_reader_eof_total 13314
telemt_me_idle_close_by_peer_total 13313
telemt_me_route_drop_no_conn_total 265849
telemt_me_route_drop_channel_closed_total 13
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 652233
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 3
telemt_me_hardswap_pending_ttl_expired_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1698
telemt_desync_full_logged_total 532
telemt_desync_suppressed_total 1166
telemt_desync_frames_bucket_total{bucket="1_2"} 511
telemt_desync_frames_bucket_total{bucket="3_10"} 657
telemt_desync_frames_bucket_total{bucket="gt_10"} 530
telemt_pool_swap_total 18
telemt_me_writer_removed_unexpected_total 13112
telemt_me_refill_failed_total 1001
telemt_me_writer_restored_same_endpoint_total 11998
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 1109
telemt_user_connections_total{user="hello"} 652114
telemt_user_connections_current{user="hello"} 268
telemt_user_octets_from_client{user="hello"} 11926176224 (11.11 GB)
telemt_user_octets_to_client{user="hello"} 212087083228 (197.52 GB)
telemt_user_unique_ips_current{user="hello"} 104
telemt_user_unique_ips_recent_window{user="hello"} 35
```