# Server Metrics 2026-03-14 00:42:08 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 153809.0 (42h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4608382
telemt_connections_bad_total 38418
telemt_handshake_timeouts_total 107879
telemt_upstream_connect_attempt_total 32363
telemt_upstream_connect_success_total 32145
telemt_upstream_connect_fail_total 218
telemt_upstream_connect_attempts_per_request{bucket="1"} 32363
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17596
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14404
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 145
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 218
telemt_me_keepalive_timeout_total 6669
telemt_me_reconnect_attempts_total 32289
telemt_me_reconnect_success_total 22157
telemt_me_reader_eof_total 23763
telemt_me_idle_close_by_peer_total 23762
telemt_me_route_drop_no_conn_total 1745131
telemt_me_route_drop_channel_closed_total 23
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4224779
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 16643
telemt_desync_full_logged_total 4488
telemt_desync_suppressed_total 12155
telemt_desync_frames_bucket_total{bucket="1_2"} 4148
telemt_desync_frames_bucket_total{bucket="3_10"} 6362
telemt_desync_frames_bucket_total{bucket="gt_10"} 6133
telemt_pool_swap_total 131
telemt_me_writer_removed_unexpected_total 22791
telemt_me_refill_failed_total 312
telemt_me_writer_restored_same_endpoint_total 22144
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 634
telemt_user_connections_total{user="hello"} 4226654
telemt_user_connections_current{user="hello"} 569
telemt_user_octets_from_client{user="hello"} 62313404300 (58.03 GB)
telemt_user_octets_to_client{user="hello"} 1335628571881 (1.21 TB)
telemt_user_msgs_from_client{user="hello"} 5023
telemt_user_msgs_to_client{user="hello"} 14147
telemt_user_unique_ips_current{user="hello"} 199
telemt_user_unique_ips_recent_window{user="hello"} 60
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 53472.5 (14h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 652641
telemt_connections_bad_total 48722
telemt_handshake_timeouts_total 12857
telemt_upstream_connect_attempt_total 15032
telemt_upstream_connect_success_total 14787
telemt_upstream_connect_fail_total 245
telemt_upstream_connect_attempts_per_request{bucket="1"} 15032
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8358
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6195
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 24
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 210
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 245
telemt_me_keepalive_timeout_total 1942
telemt_me_reconnect_attempts_total 13512
telemt_me_reconnect_success_total 10070
telemt_me_reader_eof_total 10686
telemt_me_idle_close_by_peer_total 10685
telemt_me_route_drop_no_conn_total 226841
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 537699
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 6
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1645
telemt_desync_full_logged_total 446
telemt_desync_suppressed_total 1199
telemt_desync_frames_bucket_total{bucket="1_2"} 348
telemt_desync_frames_bucket_total{bucket="3_10"} 714
telemt_desync_frames_bucket_total{bucket="gt_10"} 583
telemt_pool_swap_total 44
telemt_me_writer_removed_unexpected_total 10318
telemt_me_refill_failed_total 102
telemt_me_writer_restored_same_endpoint_total 10062
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 600
telemt_me_writer_removed_unexpected_minus_restored_total 248
telemt_user_connections_total{user="hello"} 539650
telemt_user_connections_current{user="hello"} 184
telemt_user_octets_from_client{user="hello"} 5858677501 (5.46 GB)
telemt_user_octets_to_client{user="hello"} 175206820976 (163.17 GB)
telemt_user_msgs_from_client{user="hello"} 6384
telemt_user_msgs_to_client{user="hello"} 14733
telemt_user_unique_ips_current{user="hello"} 79
telemt_user_unique_ips_recent_window{user="hello"} 23
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 183429.2 (50h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3339588
telemt_connections_bad_total 34172
telemt_handshake_timeouts_total 222461
telemt_upstream_connect_attempt_total 41033
telemt_upstream_connect_success_total 41012
telemt_upstream_connect_fail_total 21
telemt_upstream_connect_attempts_per_request{bucket="1"} 41033
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21492
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19289
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 224
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 21
telemt_me_keepalive_timeout_total 10356
telemt_me_reconnect_attempts_total 36530
telemt_me_reconnect_success_total 31574
telemt_me_reader_eof_total 33516
telemt_me_idle_close_by_peer_total 33515
telemt_me_route_drop_no_conn_total 1146115
telemt_me_route_drop_channel_closed_total 19
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2775484
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 9138
telemt_desync_full_logged_total 3069
telemt_desync_suppressed_total 6069
telemt_desync_frames_bucket_total{bucket="1_2"} 1538
telemt_desync_frames_bucket_total{bucket="3_10"} 3311
telemt_desync_frames_bucket_total{bucket="gt_10"} 4289
telemt_pool_swap_total 171
telemt_me_writer_removed_unexpected_total 32029
telemt_me_refill_failed_total 149
telemt_me_writer_restored_same_endpoint_total 31533
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 455
telemt_user_connections_total{user="hello"} 2774722
telemt_user_connections_current{user="hello"} 267
telemt_user_octets_from_client{user="hello"} 44895577664 (41.81 GB)
telemt_user_octets_to_client{user="hello"} 985622851733 (917.93 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 114
telemt_user_unique_ips_recent_window{user="hello"} 42
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 183431.7 (50h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2215241
telemt_connections_bad_total 22915
telemt_handshake_timeouts_total 238290
telemt_upstream_connect_attempt_total 57070
telemt_upstream_connect_success_total 54614
telemt_upstream_connect_fail_total 2319
telemt_upstream_connect_attempts_per_request{bucket="1"} 56796
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 32692
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21756
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 166
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2318
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 20384
telemt_me_reconnect_attempts_total 47496
telemt_me_reconnect_success_total 38470
telemt_me_reader_eof_total 41268
telemt_me_idle_close_by_peer_total 41261
telemt_me_route_drop_no_conn_total 765357
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1781711
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3800
telemt_desync_full_logged_total 1220
telemt_desync_suppressed_total 2580
telemt_desync_frames_bucket_total{bucket="1_2"} 1006
telemt_desync_frames_bucket_total{bucket="3_10"} 1588
telemt_desync_frames_bucket_total{bucket="gt_10"} 1206
telemt_pool_swap_total 161
telemt_me_writer_removed_unexpected_total 39084
telemt_me_refill_failed_total 274
telemt_me_writer_restored_same_endpoint_total 38446
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 614
telemt_user_connections_total{user="hello"} 1787625
telemt_user_connections_current{user="hello"} 138
telemt_user_octets_from_client{user="hello"} 27390373695 (25.51 GB)
telemt_user_octets_to_client{user="hello"} 663260560422 (617.71 GB)
telemt_user_msgs_from_client{user="hello"} 50957
telemt_user_msgs_to_client{user="hello"} 129867
telemt_user_unique_ips_current{user="hello"} 70
telemt_user_unique_ips_recent_window{user="hello"} 24
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 52865.6 (14h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 675610
telemt_connections_bad_total 7870
telemt_handshake_timeouts_total 8605
telemt_upstream_connect_attempt_total 12879
telemt_upstream_connect_success_total 12509
telemt_upstream_connect_fail_total 370
telemt_upstream_connect_attempts_per_request{bucket="1"} 12879
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6066
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6418
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 370
telemt_me_keepalive_timeout_total 1464
telemt_me_reconnect_attempts_total 42018
telemt_me_reconnect_success_total 9861
telemt_me_reader_eof_total 11065
telemt_me_idle_close_by_peer_total 11064
telemt_me_route_drop_no_conn_total 254630
telemt_me_route_drop_channel_closed_total 13
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 628262
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 3
telemt_me_hardswap_pending_ttl_expired_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1638
telemt_desync_full_logged_total 513
telemt_desync_suppressed_total 1125
telemt_desync_frames_bucket_total{bucket="1_2"} 492
telemt_desync_frames_bucket_total{bucket="3_10"} 641
telemt_desync_frames_bucket_total{bucket="gt_10"} 505
telemt_pool_swap_total 14
telemt_me_writer_removed_unexpected_total 10954
telemt_me_refill_failed_total 1001
telemt_me_writer_restored_same_endpoint_total 9856
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 1093
telemt_user_connections_total{user="hello"} 628161
telemt_user_connections_current{user="hello"} 252
telemt_user_octets_from_client{user="hello"} 10535221684 (9.81 GB)
telemt_user_octets_to_client{user="hello"} 205992418236 (191.85 GB)
telemt_user_unique_ips_current{user="hello"} 84
telemt_user_unique_ips_recent_window{user="hello"} 24
```