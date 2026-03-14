# Server Metrics 2026-03-14 02:14:09 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 159329.7 (44h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4660488
telemt_connections_bad_total 39809
telemt_handshake_timeouts_total 108360
telemt_upstream_connect_attempt_total 33645
telemt_upstream_connect_success_total 33420
telemt_upstream_connect_fail_total 225
telemt_upstream_connect_attempts_per_request{bucket="1"} 33645
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18240
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15035
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 145
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 225
telemt_me_keepalive_timeout_total 6712
telemt_me_reconnect_attempts_total 33301
telemt_me_reconnect_success_total 23162
telemt_me_reader_eof_total 24835
telemt_me_idle_close_by_peer_total 24834
telemt_me_route_drop_no_conn_total 1764336
telemt_me_route_drop_channel_closed_total 24
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4273052
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 16753
telemt_desync_full_logged_total 4516
telemt_desync_suppressed_total 12237
telemt_desync_frames_bucket_total{bucket="1_2"} 4185
telemt_desync_frames_bucket_total{bucket="3_10"} 6393
telemt_desync_frames_bucket_total{bucket="gt_10"} 6175
telemt_pool_swap_total 136
telemt_me_writer_removed_unexpected_total 23811
telemt_me_refill_failed_total 312
telemt_me_writer_restored_same_endpoint_total 23149
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 649
telemt_user_connections_total{user="hello"} 4274907
telemt_user_connections_current{user="hello"} 575
telemt_user_octets_from_client{user="hello"} 62811556332 (58.50 GB)
telemt_user_octets_to_client{user="hello"} 1349772139369 (1.23 TB)
telemt_user_msgs_from_client{user="hello"} 5023
telemt_user_msgs_to_client{user="hello"} 14147
telemt_user_unique_ips_current{user="hello"} 196
telemt_user_unique_ips_recent_window{user="hello"} 68
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 58993.4 (16h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 693727
telemt_connections_bad_total 50961
telemt_handshake_timeouts_total 13098
telemt_upstream_connect_attempt_total 16477
telemt_upstream_connect_success_total 16227
telemt_upstream_connect_fail_total 250
telemt_upstream_connect_attempts_per_request{bucket="1"} 16477
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9059
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6930
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 26
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 212
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 250
telemt_me_keepalive_timeout_total 2057
telemt_me_reconnect_attempts_total 14691
telemt_me_reconnect_success_total 11247
telemt_me_reader_eof_total 11925
telemt_me_idle_close_by_peer_total 11924
telemt_me_route_drop_no_conn_total 232749
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 554725
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 6
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1663
telemt_desync_full_logged_total 454
telemt_desync_suppressed_total 1209
telemt_desync_frames_bucket_total{bucket="1_2"} 357
telemt_desync_frames_bucket_total{bucket="3_10"} 719
telemt_desync_frames_bucket_total{bucket="gt_10"} 587
telemt_pool_swap_total 49
telemt_me_writer_removed_unexpected_total 11510
telemt_me_refill_failed_total 102
telemt_me_writer_restored_same_endpoint_total 11239
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 600
telemt_me_writer_removed_unexpected_minus_restored_total 263
telemt_user_connections_total{user="hello"} 556676
telemt_user_connections_current{user="hello"} 175
telemt_user_octets_from_client{user="hello"} 5960254689 (5.55 GB)
telemt_user_octets_to_client{user="hello"} 178917753684 (166.63 GB)
telemt_user_msgs_from_client{user="hello"} 6384
telemt_user_msgs_to_client{user="hello"} 14733
telemt_user_unique_ips_current{user="hello"} 76
telemt_user_unique_ips_recent_window{user="hello"} 30
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 188950.2 (52h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3370152
telemt_connections_bad_total 34947
telemt_handshake_timeouts_total 223260
telemt_upstream_connect_attempt_total 42482
telemt_upstream_connect_success_total 42461
telemt_upstream_connect_fail_total 21
telemt_upstream_connect_attempts_per_request{bucket="1"} 42482
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 22302
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19922
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 230
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 21
telemt_me_keepalive_timeout_total 10414
telemt_me_reconnect_attempts_total 37720
telemt_me_reconnect_success_total 32759
telemt_me_reader_eof_total 34788
telemt_me_idle_close_by_peer_total 34787
telemt_me_route_drop_no_conn_total 1155684
telemt_me_route_drop_channel_closed_total 19
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2803785
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 9277
telemt_desync_full_logged_total 3108
telemt_desync_suppressed_total 6169
telemt_desync_frames_bucket_total{bucket="1_2"} 1583
telemt_desync_frames_bucket_total{bucket="3_10"} 3360
telemt_desync_frames_bucket_total{bucket="gt_10"} 4334
telemt_pool_swap_total 177
telemt_me_writer_removed_unexpected_total 33222
telemt_me_refill_failed_total 149
telemt_me_writer_restored_same_endpoint_total 32718
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 463
telemt_user_connections_total{user="hello"} 2803010
telemt_user_connections_current{user="hello"} 323
telemt_user_octets_from_client{user="hello"} 45127540816 (42.03 GB)
telemt_user_octets_to_client{user="hello"} 1004000355605 (935.05 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 134
telemt_user_unique_ips_recent_window{user="hello"} 44
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 188952.9 (52h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2249347
telemt_connections_bad_total 22948
telemt_handshake_timeouts_total 245115
telemt_upstream_connect_attempt_total 59144
telemt_upstream_connect_success_total 56684
telemt_upstream_connect_fail_total 2323
telemt_upstream_connect_attempts_per_request{bucket="1"} 58870
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 33880
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 22638
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 166
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2322
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 20414
telemt_me_reconnect_attempts_total 49305
telemt_me_reconnect_success_total 40274
telemt_me_reader_eof_total 43183
telemt_me_idle_close_by_peer_total 43176
telemt_me_route_drop_no_conn_total 770504
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1796667
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
telemt_me_writer_removed_unexpected_total 40904
telemt_me_refill_failed_total 274
telemt_me_writer_restored_same_endpoint_total 40250
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 630
telemt_user_connections_total{user="hello"} 1802591
telemt_user_connections_current{user="hello"} 179
telemt_user_octets_from_client{user="hello"} 27574640295 (25.68 GB)
telemt_user_octets_to_client{user="hello"} 665854621610 (620.13 GB)
telemt_user_msgs_from_client{user="hello"} 50957
telemt_user_msgs_to_client{user="hello"} 129867
telemt_user_unique_ips_current{user="hello"} 87
telemt_user_unique_ips_recent_window{user="hello"} 23
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 58386.2 (16h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 693409
telemt_connections_bad_total 7906
telemt_handshake_timeouts_total 8655
telemt_upstream_connect_attempt_total 14667
telemt_upstream_connect_success_total 14263
telemt_upstream_connect_fail_total 404
telemt_upstream_connect_attempts_per_request{bucket="1"} 14667
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6858
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7380
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 404
telemt_me_keepalive_timeout_total 1497
telemt_me_reconnect_attempts_total 43513
telemt_me_reconnect_success_total 11350
telemt_me_reader_eof_total 12658
telemt_me_idle_close_by_peer_total 12657
telemt_me_route_drop_no_conn_total 263223
telemt_me_route_drop_channel_closed_total 13
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 645596
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
telemt_me_writer_removed_unexpected_total 12456
telemt_me_refill_failed_total 1001
telemt_me_writer_restored_same_endpoint_total 11345
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 1106
telemt_user_connections_total{user="hello"} 645483
telemt_user_connections_current{user="hello"} 234
telemt_user_octets_from_client{user="hello"} 10701328764 (9.97 GB)
telemt_user_octets_to_client{user="hello"} 210289916688 (195.85 GB)
telemt_user_unique_ips_current{user="hello"} 84
telemt_user_unique_ips_recent_window{user="hello"} 25
```