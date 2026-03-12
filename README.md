# Server Metrics 2026-03-12 16:27:10 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 37709.6 (10h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1361464
telemt_connections_bad_total 20241
telemt_handshake_timeouts_total 13092
telemt_upstream_connect_attempt_total 7573
telemt_upstream_connect_success_total 7533
telemt_upstream_connect_fail_total 40
telemt_upstream_connect_attempts_per_request{bucket="1"} 7573
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3974
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3540
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 19
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 40
telemt_me_keepalive_timeout_total 458
telemt_me_reconnect_attempts_total 9538
telemt_me_reconnect_success_total 5623
telemt_me_reader_eof_total 5982
telemt_me_idle_close_by_peer_total 5981
telemt_me_route_drop_no_conn_total 489822
telemt_me_route_drop_channel_closed_total 9
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1276053
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 6588
telemt_desync_full_logged_total 1648
telemt_desync_suppressed_total 4940
telemt_desync_frames_bucket_total{bucket="1_2"} 1693
telemt_desync_frames_bucket_total{bucket="3_10"} 2384
telemt_desync_frames_bucket_total{bucket="gt_10"} 2511
telemt_pool_swap_total 24
telemt_me_writer_removed_unexpected_total 5822
telemt_me_refill_failed_total 121
telemt_me_writer_restored_same_endpoint_total 5610
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 199
telemt_user_connections_total{user="hello"} 1275728
telemt_user_connections_current{user="hello"} 1470
telemt_user_octets_from_client{user="hello"} 19597689332 (18.25 GB)
telemt_user_octets_to_client{user="hello"} 369031971744 (343.69 GB)
telemt_user_unique_ips_current{user="hello"} 407
telemt_user_unique_ips_recent_window{user="hello"} 205
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 67330.2 (18h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 600610
telemt_connections_bad_total 7885
telemt_handshake_timeouts_total 28267
telemt_upstream_connect_attempt_total 16042
telemt_upstream_connect_success_total 16035
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 16042
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7979
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8040
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 16
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_keepalive_timeout_total 1258
telemt_me_reconnect_attempts_total 12571
telemt_me_reconnect_success_total 12500
telemt_me_reader_eof_total 13288
telemt_me_idle_close_by_peer_total 13288
telemt_me_route_drop_no_conn_total 180169
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 537728
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2128
telemt_desync_full_logged_total 674
telemt_desync_suppressed_total 1454
telemt_desync_frames_bucket_total{bucket="1_2"} 945
telemt_desync_frames_bucket_total{bucket="3_10"} 675
telemt_desync_frames_bucket_total{bucket="gt_10"} 508
telemt_pool_swap_total 67
telemt_me_writer_removed_unexpected_total 12625
telemt_me_writer_restored_same_endpoint_total 12491
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 125
telemt_user_connections_total{user="hello"} 538228
telemt_user_connections_current{user="hello"} 578
telemt_user_octets_from_client{user="hello"} 8304522991 (7.73 GB)
telemt_user_octets_to_client{user="hello"} 189544000750 (176.53 GB)
telemt_user_msgs_from_client{user="hello"} 353
telemt_user_msgs_to_client{user="hello"} 423
telemt_user_unique_ips_current{user="hello"} 177
telemt_user_unique_ips_recent_window{user="hello"} 81
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 67330.1 (18h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1265580
telemt_connections_bad_total 6364
telemt_handshake_timeouts_total 90036
telemt_upstream_connect_attempt_total 16129
telemt_upstream_connect_success_total 16124
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 16129
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8709
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7349
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 62
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 1069
telemt_me_reconnect_attempts_total 13637
telemt_me_reconnect_success_total 12406
telemt_me_reader_eof_total 13083
telemt_me_idle_close_by_peer_total 13082
telemt_me_route_drop_no_conn_total 348470
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 942626
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4007
telemt_desync_full_logged_total 1229
telemt_desync_suppressed_total 2778
telemt_desync_frames_bucket_total{bucket="1_2"} 621
telemt_desync_frames_bucket_total{bucket="3_10"} 1442
telemt_desync_frames_bucket_total{bucket="gt_10"} 1944
telemt_pool_swap_total 62
telemt_me_writer_removed_unexpected_total 12496
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 12365
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 90
telemt_user_connections_total{user="hello"} 942784
telemt_user_connections_current{user="hello"} 973
telemt_user_octets_from_client{user="hello"} 12271130772 (11.43 GB)
telemt_user_octets_to_client{user="hello"} 295900211073 (275.58 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 279
telemt_user_unique_ips_recent_window{user="hello"} 127
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 67330.7 (18h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 757543
telemt_connections_bad_total 7728
telemt_handshake_timeouts_total 60135
telemt_upstream_connect_attempt_total 17668
telemt_upstream_connect_success_total 17598
telemt_upstream_connect_fail_total 70
telemt_upstream_connect_attempts_per_request{bucket="1"} 17668
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9959
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7626
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 13
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 70
telemt_me_keepalive_timeout_total 1499
telemt_me_reconnect_attempts_total 19484
telemt_me_reconnect_success_total 14238
telemt_me_reader_eof_total 15175
telemt_me_idle_close_by_peer_total 15175
telemt_me_route_drop_no_conn_total 258852
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 654176
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1313
telemt_desync_full_logged_total 439
telemt_desync_suppressed_total 874
telemt_desync_frames_bucket_total{bucket="1_2"} 361
telemt_desync_frames_bucket_total{bucket="3_10"} 520
telemt_desync_frames_bucket_total{bucket="gt_10"} 432
telemt_pool_swap_total 56
telemt_me_writer_removed_unexpected_total 14510
telemt_me_refill_failed_total 162
telemt_me_writer_restored_same_endpoint_total 14217
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 108
telemt_me_writer_removed_unexpected_minus_restored_total 272
telemt_user_connections_total{user="hello"} 653626
telemt_user_connections_current{user="hello"} 627
telemt_user_octets_from_client{user="hello"} 8124778756 (7.57 GB)
telemt_user_octets_to_client{user="hello"} 254093463744 (236.64 GB)
telemt_user_unique_ips_current{user="hello"} 181
telemt_user_unique_ips_recent_window{user="hello"} 99
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 67330.3 (18h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 855906
telemt_connections_bad_total 10506
telemt_handshake_timeouts_total 7049
telemt_upstream_connect_attempt_total 21159
telemt_upstream_connect_success_total 20901
telemt_upstream_connect_fail_total 258
telemt_upstream_connect_attempts_per_request{bucket="1"} 21159
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10640
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10149
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 104
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 258
telemt_me_keepalive_timeout_total 1215
telemt_me_reconnect_attempts_total 24779
telemt_me_reconnect_success_total 17536
telemt_me_reader_eof_total 18353
telemt_me_idle_close_by_peer_total 18353
telemt_me_seq_mismatch_total 31
telemt_me_route_drop_no_conn_total 301668
telemt_me_route_drop_channel_closed_total 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 786627
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 35
telemt_me_hardswap_pending_ttl_expired_total 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 3094
telemt_desync_full_logged_total 1046
telemt_desync_suppressed_total 2048
telemt_desync_frames_bucket_total{bucket="1_2"} 854
telemt_desync_frames_bucket_total{bucket="3_10"} 1056
telemt_desync_frames_bucket_total{bucket="gt_10"} 1184
telemt_pool_swap_total 32
telemt_me_writer_removed_unexpected_total 17946
telemt_me_refill_failed_total 224
telemt_me_writer_restored_same_endpoint_total 17496
telemt_me_writer_restored_fallback_total 40
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 410
telemt_user_connections_total{user="hello"} 786521
telemt_user_connections_current{user="hello"} 701
telemt_user_octets_from_client{user="hello"} 9642495400 (8.98 GB)
telemt_user_octets_to_client{user="hello"} 221875100296 (206.64 GB)
telemt_user_unique_ips_current{user="hello"} 214
telemt_user_unique_ips_recent_window{user="hello"} 112
```