# Server Metrics 2026-03-13 23:56:07 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 151048.3 (41h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4584812
telemt_connections_bad_total 38391
telemt_handshake_timeouts_total 107785
telemt_upstream_connect_attempt_total 31750
telemt_upstream_connect_success_total 31533
telemt_upstream_connect_fail_total 217
telemt_upstream_connect_attempts_per_request{bucket="1"} 31750
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17298
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14090
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 145
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 217
telemt_me_keepalive_timeout_total 6655
telemt_me_reconnect_attempts_total 31810
telemt_me_reconnect_success_total 21679
telemt_me_reader_eof_total 23249
telemt_me_idle_close_by_peer_total 23248
telemt_me_route_drop_no_conn_total 1733272
telemt_me_route_drop_channel_closed_total 23
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4201854
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 16611
telemt_desync_full_logged_total 4474
telemt_desync_suppressed_total 12137
telemt_desync_frames_bucket_total{bucket="1_2"} 4134
telemt_desync_frames_bucket_total{bucket="3_10"} 6355
telemt_desync_frames_bucket_total{bucket="gt_10"} 6122
telemt_pool_swap_total 128
telemt_me_writer_removed_unexpected_total 22308
telemt_me_refill_failed_total 312
telemt_me_writer_restored_same_endpoint_total 21666
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 629
telemt_user_connections_total{user="hello"} 4203776
telemt_user_connections_current{user="hello"} 594
telemt_user_octets_from_client{user="hello"} 62065332516 (57.80 GB)
telemt_user_octets_to_client{user="hello"} 1328584620877 (1.21 TB)
telemt_user_msgs_from_client{user="hello"} 5023
telemt_user_msgs_to_client{user="hello"} 14147
telemt_user_unique_ips_current{user="hello"} 195
telemt_user_unique_ips_recent_window{user="hello"} 61
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 50711.9 (14h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 625461
telemt_connections_bad_total 46491
telemt_handshake_timeouts_total 12750
telemt_upstream_connect_attempt_total 14326
telemt_upstream_connect_success_total 14086
telemt_upstream_connect_fail_total 240
telemt_upstream_connect_attempts_per_request{bucket="1"} 14326
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8026
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5826
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 24
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 210
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 240
telemt_me_keepalive_timeout_total 1927
telemt_me_reconnect_attempts_total 12941
telemt_me_reconnect_success_total 9502
telemt_me_reader_eof_total 10080
telemt_me_idle_close_by_peer_total 10079
telemt_me_route_drop_no_conn_total 222938
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 529777
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
telemt_pool_swap_total 41
telemt_me_writer_removed_unexpected_total 9745
telemt_me_refill_failed_total 102
telemt_me_writer_restored_same_endpoint_total 9494
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 600
telemt_me_writer_removed_unexpected_minus_restored_total 243
telemt_user_connections_total{user="hello"} 531728
telemt_user_connections_current{user="hello"} 205
telemt_user_octets_from_client{user="hello"} 5826874229 (5.43 GB)
telemt_user_octets_to_client{user="hello"} 173595776108 (161.67 GB)
telemt_user_msgs_from_client{user="hello"} 6384
telemt_user_msgs_to_client{user="hello"} 14733
telemt_user_unique_ips_current{user="hello"} 84
telemt_user_unique_ips_recent_window{user="hello"} 18
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 180668.7 (50h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3323534
telemt_connections_bad_total 32325
telemt_handshake_timeouts_total 222194
telemt_upstream_connect_attempt_total 40251
telemt_upstream_connect_success_total 40230
telemt_upstream_connect_fail_total 21
telemt_upstream_connect_attempts_per_request{bucket="1"} 40251
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21049
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18951
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 223
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 21
telemt_me_keepalive_timeout_total 10343
telemt_me_reconnect_attempts_total 35879
telemt_me_reconnect_success_total 30923
telemt_me_reader_eof_total 32821
telemt_me_idle_close_by_peer_total 32820
telemt_me_route_drop_no_conn_total 1140405
telemt_me_route_drop_channel_closed_total 19
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2761886
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 9049
telemt_desync_full_logged_total 3044
telemt_desync_suppressed_total 6005
telemt_desync_frames_bucket_total{bucket="1_2"} 1523
telemt_desync_frames_bucket_total{bucket="3_10"} 3281
telemt_desync_frames_bucket_total{bucket="gt_10"} 4245
telemt_pool_swap_total 168
telemt_me_writer_removed_unexpected_total 31373
telemt_me_refill_failed_total 149
telemt_me_writer_restored_same_endpoint_total 30882
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 450
telemt_user_connections_total{user="hello"} 2761134
telemt_user_connections_current{user="hello"} 293
telemt_user_octets_from_client{user="hello"} 44789702328 (41.71 GB)
telemt_user_octets_to_client{user="hello"} 979089729341 (911.85 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 120
telemt_user_unique_ips_recent_window{user="hello"} 40
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 180671.4 (50h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2193845
telemt_connections_bad_total 22859
telemt_handshake_timeouts_total 233529
telemt_upstream_connect_attempt_total 56226
telemt_upstream_connect_success_total 53773
telemt_upstream_connect_fail_total 2316
telemt_upstream_connect_attempts_per_request{bucket="1"} 55952
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 32232
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21375
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 166
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2315
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 20352
telemt_me_reconnect_attempts_total 46784
telemt_me_reconnect_success_total 37760
telemt_me_reader_eof_total 40504
telemt_me_idle_close_by_peer_total 40497
telemt_me_route_drop_no_conn_total 762513
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1773458
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3796
telemt_desync_full_logged_total 1217
telemt_desync_suppressed_total 2579
telemt_desync_frames_bucket_total{bucket="1_2"} 1003
telemt_desync_frames_bucket_total{bucket="3_10"} 1587
telemt_desync_frames_bucket_total{bucket="gt_10"} 1206
telemt_pool_swap_total 158
telemt_me_writer_removed_unexpected_total 38369
telemt_me_refill_failed_total 274
telemt_me_writer_restored_same_endpoint_total 37736
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 609
telemt_user_connections_total{user="hello"} 1779353
telemt_user_connections_current{user="hello"} 193
telemt_user_octets_from_client{user="hello"} 27360449687 (25.48 GB)
telemt_user_octets_to_client{user="hello"} 661769198034 (616.32 GB)
telemt_user_msgs_from_client{user="hello"} 50957
telemt_user_msgs_to_client{user="hello"} 129867
telemt_user_unique_ips_current{user="hello"} 80
telemt_user_unique_ips_recent_window{user="hello"} 27
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 50104.8 (13h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 664271
telemt_connections_bad_total 7861
telemt_handshake_timeouts_total 8105
telemt_upstream_connect_attempt_total 12018
telemt_upstream_connect_success_total 11659
telemt_upstream_connect_fail_total 359
telemt_upstream_connect_attempts_per_request{bucket="1"} 12018
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5651
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5983
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 359
telemt_me_keepalive_timeout_total 1451
telemt_me_reconnect_attempts_total 41298
telemt_me_reconnect_success_total 9143
telemt_me_reader_eof_total 10305
telemt_me_idle_close_by_peer_total 10304
telemt_me_route_drop_no_conn_total 251212
telemt_me_route_drop_channel_closed_total 13
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 618283
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 3
telemt_me_hardswap_pending_ttl_expired_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1623
telemt_desync_full_logged_total 510
telemt_desync_suppressed_total 1113
telemt_desync_frames_bucket_total{bucket="1_2"} 489
telemt_desync_frames_bucket_total{bucket="3_10"} 636
telemt_desync_frames_bucket_total{bucket="gt_10"} 498
telemt_pool_swap_total 12
telemt_me_writer_removed_unexpected_total 10231
telemt_me_refill_failed_total 1001
telemt_me_writer_restored_same_endpoint_total 9138
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 1088
telemt_user_connections_total{user="hello"} 618182
telemt_user_connections_current{user="hello"} 279
telemt_user_octets_from_client{user="hello"} 9954438832 (9.27 GB)
telemt_user_octets_to_client{user="hello"} 201706893520 (187.85 GB)
telemt_user_unique_ips_current{user="hello"} 92
telemt_user_unique_ips_recent_window{user="hello"} 36
```