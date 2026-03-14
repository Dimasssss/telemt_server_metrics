# Server Metrics 2026-03-14 03:20:36 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 163317.4 (45h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4704210
telemt_connections_bad_total 39881
telemt_handshake_timeouts_total 108938
telemt_upstream_connect_attempt_total 34533
telemt_upstream_connect_success_total 34304
telemt_upstream_connect_fail_total 229
telemt_upstream_connect_attempts_per_request{bucket="1"} 34533
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18707
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15451
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 146
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 229
telemt_me_keepalive_timeout_total 6732
telemt_me_reconnect_attempts_total 33973
telemt_me_reconnect_success_total 23831
telemt_me_reader_eof_total 25557
telemt_me_idle_close_by_peer_total 25556
telemt_me_route_drop_no_conn_total 1786710
telemt_me_route_drop_channel_closed_total 24
telemt_me_route_drop_queue_full_total 6
telemt_me_route_drop_queue_full_profile_total{profile="high"} 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4315525
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 16777
telemt_desync_full_logged_total 4525
telemt_desync_suppressed_total 12252
telemt_desync_frames_bucket_total{bucket="1_2"} 4193
telemt_desync_frames_bucket_total{bucket="3_10"} 6397
telemt_desync_frames_bucket_total{bucket="gt_10"} 6187
telemt_pool_swap_total 141
telemt_me_writer_removed_unexpected_total 24489
telemt_me_refill_failed_total 312
telemt_me_writer_restored_same_endpoint_total 23818
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 658
telemt_user_connections_total{user="hello"} 4317118
telemt_user_connections_current{user="hello"} 676
telemt_user_octets_from_client{user="hello"} 63186062140 (58.85 GB)
telemt_user_octets_to_client{user="hello"} 1363141386117 (1.24 TB)
telemt_user_msgs_from_client{user="hello"} 5023
telemt_user_msgs_to_client{user="hello"} 14147
telemt_user_unique_ips_current{user="hello"} 232
telemt_user_unique_ips_recent_window{user="hello"} 78
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 62981.1 (17h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 709074
telemt_connections_bad_total 51480
telemt_handshake_timeouts_total 13219
telemt_upstream_connect_attempt_total 17516
telemt_upstream_connect_success_total 17260
telemt_upstream_connect_fail_total 256
telemt_upstream_connect_attempts_per_request{bucket="1"} 17516
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9598
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7421
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 29
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 212
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 256
telemt_me_keepalive_timeout_total 2090
telemt_me_reconnect_attempts_total 15553
telemt_me_reconnect_success_total 12105
telemt_me_reader_eof_total 12847
telemt_me_idle_close_by_peer_total 12846
telemt_me_route_drop_no_conn_total 237447
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 568253
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 6
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1701
telemt_desync_full_logged_total 477
telemt_desync_suppressed_total 1224
telemt_desync_frames_bucket_total{bucket="1_2"} 362
telemt_desync_frames_bucket_total{bucket="3_10"} 745
telemt_desync_frames_bucket_total{bucket="gt_10"} 594
telemt_pool_swap_total 53
telemt_me_writer_removed_unexpected_total 12377
telemt_me_refill_failed_total 102
telemt_me_writer_restored_same_endpoint_total 12097
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 600
telemt_me_writer_removed_unexpected_minus_restored_total 272
telemt_user_connections_total{user="hello"} 570211
telemt_user_connections_current{user="hello"} 267
telemt_user_octets_from_client{user="hello"} 6084074061 (5.67 GB)
telemt_user_octets_to_client{user="hello"} 186892737968 (174.06 GB)
telemt_user_msgs_from_client{user="hello"} 6384
telemt_user_msgs_to_client{user="hello"} 14733
telemt_user_unique_ips_current{user="hello"} 101
telemt_user_unique_ips_recent_window{user="hello"} 43
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 192937.7 (53h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3396341
telemt_connections_bad_total 35687
telemt_handshake_timeouts_total 223709
telemt_upstream_connect_attempt_total 43563
telemt_upstream_connect_success_total 43542
telemt_upstream_connect_fail_total 21
telemt_upstream_connect_attempts_per_request{bucket="1"} 43563
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 22905
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20397
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 233
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 21
telemt_me_keepalive_timeout_total 10428
telemt_me_reconnect_attempts_total 38586
telemt_me_reconnect_success_total 33620
telemt_me_reader_eof_total 35714
telemt_me_idle_close_by_peer_total 35713
telemt_me_route_drop_no_conn_total 1162894
telemt_me_route_drop_channel_closed_total 19
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2828143
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 9366
telemt_desync_full_logged_total 3131
telemt_desync_suppressed_total 6235
telemt_desync_frames_bucket_total{bucket="1_2"} 1614
telemt_desync_frames_bucket_total{bucket="3_10"} 3386
telemt_desync_frames_bucket_total{bucket="gt_10"} 4366
telemt_pool_swap_total 182
telemt_me_writer_removed_unexpected_total 34090
telemt_me_refill_failed_total 149
telemt_me_writer_restored_same_endpoint_total 33579
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 470
telemt_user_connections_total{user="hello"} 2827365
telemt_user_connections_current{user="hello"} 396
telemt_user_octets_from_client{user="hello"} 45298548444 (42.19 GB)
telemt_user_octets_to_client{user="hello"} 1009061259641 (939.76 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 149
telemt_user_unique_ips_recent_window{user="hello"} 57
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 192940.4 (53h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2273732
telemt_connections_bad_total 22996
telemt_handshake_timeouts_total 250160
telemt_upstream_connect_attempt_total 60507
telemt_upstream_connect_success_total 58040
telemt_upstream_connect_fail_total 2330
telemt_upstream_connect_attempts_per_request{bucket="1"} 60233
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 34697
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 23177
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 166
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2329
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 20440
telemt_me_reconnect_attempts_total 50441
telemt_me_reconnect_success_total 41406
telemt_me_reader_eof_total 44413
telemt_me_idle_close_by_peer_total 44406
telemt_me_route_drop_no_conn_total 774869
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1809255
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3817
telemt_desync_full_logged_total 1229
telemt_desync_suppressed_total 2588
telemt_desync_frames_bucket_total{bucket="1_2"} 1018
telemt_desync_frames_bucket_total{bucket="3_10"} 1591
telemt_desync_frames_bucket_total{bucket="gt_10"} 1208
telemt_pool_swap_total 170
telemt_me_writer_removed_unexpected_total 42042
telemt_me_refill_failed_total 274
telemt_me_writer_restored_same_endpoint_total 41382
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 636
telemt_user_connections_total{user="hello"} 1815195
telemt_user_connections_current{user="hello"} 197
telemt_user_octets_from_client{user="hello"} 27650763019 (25.75 GB)
telemt_user_octets_to_client{user="hello"} 669452077358 (623.48 GB)
telemt_user_msgs_from_client{user="hello"} 50957
telemt_user_msgs_to_client{user="hello"} 129867
telemt_user_unique_ips_current{user="hello"} 86
telemt_user_unique_ips_recent_window{user="hello"} 34
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 62374.1 (17h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 708909
telemt_connections_bad_total 7953
telemt_handshake_timeouts_total 8686
telemt_upstream_connect_attempt_total 16229
telemt_upstream_connect_success_total 15791
telemt_upstream_connect_fail_total 438
telemt_upstream_connect_attempts_per_request{bucket="1"} 16229
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7555
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8210
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 26
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 438
telemt_me_keepalive_timeout_total 1520
telemt_me_reconnect_attempts_total 48662
telemt_me_reconnect_success_total 12658
telemt_me_reader_eof_total 14094
telemt_me_idle_close_by_peer_total 14093
telemt_me_route_drop_no_conn_total 269455
telemt_me_route_drop_channel_closed_total 13
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 660706
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 3
telemt_me_hardswap_pending_ttl_expired_total 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1701
telemt_desync_full_logged_total 534
telemt_desync_suppressed_total 1167
telemt_desync_frames_bucket_total{bucket="1_2"} 512
telemt_desync_frames_bucket_total{bucket="3_10"} 658
telemt_desync_frames_bucket_total{bucket="gt_10"} 531
telemt_pool_swap_total 18
telemt_me_writer_removed_unexpected_total 13892
telemt_me_refill_failed_total 1121
telemt_me_writer_restored_same_endpoint_total 12653
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 1234
telemt_user_connections_total{user="hello"} 660584
telemt_user_connections_current{user="hello"} 276
telemt_user_octets_from_client{user="hello"} 12024903656 (11.20 GB)
telemt_user_octets_to_client{user="hello"} 214571705760 (199.84 GB)
telemt_user_unique_ips_current{user="hello"} 104
telemt_user_unique_ips_recent_window{user="hello"} 36
```