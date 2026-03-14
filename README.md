# Server Metrics 2026-03-14 00:01:14 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 151354.9 (42h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4587437
telemt_connections_bad_total 38391
telemt_handshake_timeouts_total 107795
telemt_upstream_connect_attempt_total 31842
telemt_upstream_connect_success_total 31625
telemt_upstream_connect_fail_total 217
telemt_upstream_connect_attempts_per_request{bucket="1"} 31842
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17347
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14133
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 145
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 217
telemt_me_keepalive_timeout_total 6656
telemt_me_reconnect_attempts_total 31856
telemt_me_reconnect_success_total 21724
telemt_me_reader_eof_total 23298
telemt_me_idle_close_by_peer_total 23297
telemt_me_route_drop_no_conn_total 1734359
telemt_me_route_drop_channel_closed_total 23
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4204450
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
telemt_pool_swap_total 129
telemt_me_writer_removed_unexpected_total 22354
telemt_me_refill_failed_total 312
telemt_me_writer_restored_same_endpoint_total 21711
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 630
telemt_user_connections_total{user="hello"} 4206338
telemt_user_connections_current{user="hello"} 696
telemt_user_octets_from_client{user="hello"} 62086593020 (57.82 GB)
telemt_user_octets_to_client{user="hello"} 1329441423445 (1.21 TB)
telemt_user_msgs_from_client{user="hello"} 5023
telemt_user_msgs_to_client{user="hello"} 14147
telemt_user_unique_ips_current{user="hello"} 217
telemt_user_unique_ips_recent_window{user="hello"} 78
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 51018.7 (14h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 628392
telemt_connections_bad_total 46731
telemt_handshake_timeouts_total 12760
telemt_upstream_connect_attempt_total 14394
telemt_upstream_connect_success_total 14154
telemt_upstream_connect_fail_total 240
telemt_upstream_connect_attempts_per_request{bucket="1"} 14394
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8053
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5867
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 24
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 210
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 240
telemt_me_keepalive_timeout_total 1927
telemt_me_reconnect_attempts_total 13009
telemt_me_reconnect_success_total 9570
telemt_me_reader_eof_total 10150
telemt_me_idle_close_by_peer_total 10149
telemt_me_route_drop_no_conn_total 223162
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 530575
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
telemt_me_writer_removed_unexpected_total 9815
telemt_me_refill_failed_total 102
telemt_me_writer_restored_same_endpoint_total 9562
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 600
telemt_me_writer_removed_unexpected_minus_restored_total 245
telemt_user_connections_total{user="hello"} 532526
telemt_user_connections_current{user="hello"} 160
telemt_user_octets_from_client{user="hello"} 5828637861 (5.43 GB)
telemt_user_octets_to_client{user="hello"} 173674366392 (161.75 GB)
telemt_user_msgs_from_client{user="hello"} 6384
telemt_user_msgs_to_client{user="hello"} 14733
telemt_user_unique_ips_current{user="hello"} 76
telemt_user_unique_ips_recent_window{user="hello"} 27
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 180975.5 (50h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3325512
telemt_connections_bad_total 32558
telemt_handshake_timeouts_total 222203
telemt_upstream_connect_attempt_total 40343
telemt_upstream_connect_success_total 40322
telemt_upstream_connect_fail_total 21
telemt_upstream_connect_attempts_per_request{bucket="1"} 40343
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21100
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18992
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 223
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 21
telemt_me_keepalive_timeout_total 10345
telemt_me_reconnect_attempts_total 35942
telemt_me_reconnect_success_total 30986
telemt_me_reader_eof_total 32886
telemt_me_idle_close_by_peer_total 32885
telemt_me_route_drop_no_conn_total 1141062
telemt_me_route_drop_channel_closed_total 19
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2763580
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 9050
telemt_desync_full_logged_total 3045
telemt_desync_suppressed_total 6005
telemt_desync_frames_bucket_total{bucket="1_2"} 1523
telemt_desync_frames_bucket_total{bucket="3_10"} 3281
telemt_desync_frames_bucket_total{bucket="gt_10"} 4246
telemt_pool_swap_total 168
telemt_me_writer_removed_unexpected_total 31438
telemt_me_refill_failed_total 149
telemt_me_writer_restored_same_endpoint_total 30945
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 452
telemt_user_connections_total{user="hello"} 2762827
telemt_user_connections_current{user="hello"} 323
telemt_user_octets_from_client{user="hello"} 44796716100 (41.72 GB)
telemt_user_octets_to_client{user="hello"} 979743210197 (912.46 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 121
telemt_user_unique_ips_recent_window{user="hello"} 57
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 180978.2 (50h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2195821
telemt_connections_bad_total 22861
telemt_handshake_timeouts_total 233956
telemt_upstream_connect_attempt_total 56305
telemt_upstream_connect_success_total 53851
telemt_upstream_connect_fail_total 2316
telemt_upstream_connect_attempts_per_request{bucket="1"} 56030
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 32280
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21405
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 166
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2315
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 20353
telemt_me_reconnect_attempts_total 46837
telemt_me_reconnect_success_total 37812
telemt_me_reader_eof_total 40557
telemt_me_idle_close_by_peer_total 40550
telemt_me_route_drop_no_conn_total 762793
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1774422
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3798
telemt_desync_full_logged_total 1218
telemt_desync_suppressed_total 2580
telemt_desync_frames_bucket_total{bucket="1_2"} 1004
telemt_desync_frames_bucket_total{bucket="3_10"} 1588
telemt_desync_frames_bucket_total{bucket="gt_10"} 1206
telemt_pool_swap_total 158
telemt_me_writer_removed_unexpected_total 38422
telemt_me_refill_failed_total 274
telemt_me_writer_restored_same_endpoint_total 37788
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 610
telemt_user_connections_total{user="hello"} 1780317
telemt_user_connections_current{user="hello"} 177
telemt_user_octets_from_client{user="hello"} 27366323459 (25.49 GB)
telemt_user_octets_to_client{user="hello"} 661873651882 (616.42 GB)
telemt_user_msgs_from_client{user="hello"} 50957
telemt_user_msgs_to_client{user="hello"} 129867
telemt_user_unique_ips_current{user="hello"} 83
telemt_user_unique_ips_recent_window{user="hello"} 23
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 50411.4 (14h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 665820
telemt_connections_bad_total 7867
telemt_handshake_timeouts_total 8221
telemt_upstream_connect_attempt_total 12097
telemt_upstream_connect_success_total 11738
telemt_upstream_connect_fail_total 359
telemt_upstream_connect_attempts_per_request{bucket="1"} 12097
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5702
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6011
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 359
telemt_me_keepalive_timeout_total 1452
telemt_me_reconnect_attempts_total 41377
telemt_me_reconnect_success_total 9222
telemt_me_reader_eof_total 10384
telemt_me_idle_close_by_peer_total 10383
telemt_me_route_drop_no_conn_total 251552
telemt_me_route_drop_channel_closed_total 13
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 619618
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
telemt_pool_swap_total 12
telemt_me_writer_removed_unexpected_total 10310
telemt_me_refill_failed_total 1001
telemt_me_writer_restored_same_endpoint_total 9217
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 1088
telemt_user_connections_total{user="hello"} 619517
telemt_user_connections_current{user="hello"} 269
telemt_user_octets_from_client{user="hello"} 9975553400 (9.29 GB)
telemt_user_octets_to_client{user="hello"} 202123200596 (188.24 GB)
telemt_user_unique_ips_current{user="hello"} 89
telemt_user_unique_ips_recent_window{user="hello"} 33
```