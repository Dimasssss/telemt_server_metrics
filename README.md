# Server Metrics 2026-03-13 01:48:36 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 71396.3 (19h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2045794
telemt_connections_bad_total 26138
telemt_handshake_timeouts_total 21856
telemt_upstream_connect_attempt_total 14166
telemt_upstream_connect_success_total 14086
telemt_upstream_connect_fail_total 80
telemt_upstream_connect_attempts_per_request{bucket="1"} 14166
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7259
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6786
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 41
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 80
telemt_me_keepalive_timeout_total 1252
telemt_me_reconnect_attempts_total 19365
telemt_me_reconnect_success_total 10503
telemt_me_reader_eof_total 11355
telemt_me_idle_close_by_peer_total 11354
telemt_me_route_drop_no_conn_total 797784
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1903561
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8699
telemt_desync_full_logged_total 2263
telemt_desync_suppressed_total 6436
telemt_desync_frames_bucket_total{bucket="1_2"} 2291
telemt_desync_frames_bucket_total{bucket="3_10"} 3138
telemt_desync_frames_bucket_total{bucket="gt_10"} 3270
telemt_pool_swap_total 55
telemt_me_writer_removed_unexpected_total 10930
telemt_me_refill_failed_total 275
telemt_me_writer_restored_same_endpoint_total 10490
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 427
telemt_user_connections_total{user="hello"} 1903019
telemt_user_connections_current{user="hello"} 551
telemt_user_octets_from_client{user="hello"} 27801009944 (25.89 GB)
telemt_user_octets_to_client{user="hello"} 663835578732 (618.25 GB)
telemt_user_unique_ips_current{user="hello"} 201
telemt_user_unique_ips_recent_window{user="hello"} 58
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 101016.8 (28h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 843248
telemt_connections_bad_total 11791
telemt_handshake_timeouts_total 32010
telemt_upstream_connect_attempt_total 25731
telemt_upstream_connect_success_total 25702
telemt_upstream_connect_fail_total 29
telemt_upstream_connect_attempts_per_request{bucket="1"} 25731
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13372
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12241
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 89
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 29
telemt_me_keepalive_timeout_total 3450
telemt_me_reconnect_attempts_total 19113
telemt_me_reconnect_success_total 19008
telemt_me_reader_eof_total 20249
telemt_me_idle_close_by_peer_total 20249
telemt_me_route_drop_no_conn_total 271409
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 764455
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3072
telemt_desync_full_logged_total 965
telemt_desync_suppressed_total 2107
telemt_desync_frames_bucket_total{bucket="1_2"} 1246
telemt_desync_frames_bucket_total{bucket="3_10"} 998
telemt_desync_frames_bucket_total{bucket="gt_10"} 828
telemt_pool_swap_total 103
telemt_me_writer_removed_unexpected_total 19193
telemt_me_writer_restored_same_endpoint_total 18999
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 185
telemt_user_connections_total{user="hello"} 766358
telemt_user_connections_current{user="hello"} 180
telemt_user_octets_from_client{user="hello"} 12288963676 (11.44 GB)
telemt_user_octets_to_client{user="hello"} 290449037123 (270.50 GB)
telemt_user_msgs_from_client{user="hello"} 6476
telemt_user_msgs_to_client{user="hello"} 18854
telemt_user_unique_ips_current{user="hello"} 76
telemt_user_unique_ips_recent_window{user="hello"} 25
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 101016.7 (28h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1749934
telemt_connections_bad_total 8985
telemt_handshake_timeouts_total 116313
telemt_upstream_connect_attempt_total 23571
telemt_upstream_connect_success_total 23561
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 23571
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12443
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11025
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 88
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_keepalive_timeout_total 1593
telemt_me_reconnect_attempts_total 19419
telemt_me_reconnect_success_total 18156
telemt_me_reader_eof_total 19228
telemt_me_idle_close_by_peer_total 19227
telemt_me_route_drop_no_conn_total 572949
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1375431
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4997
telemt_desync_full_logged_total 1533
telemt_desync_suppressed_total 3464
telemt_desync_frames_bucket_total{bucket="1_2"} 798
telemt_desync_frames_bucket_total{bucket="3_10"} 1807
telemt_desync_frames_bucket_total{bucket="gt_10"} 2392
telemt_pool_swap_total 94
telemt_me_writer_removed_unexpected_total 18328
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 18115
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 172
telemt_user_connections_total{user="hello"} 1375026
telemt_user_connections_current{user="hello"} 299
telemt_user_octets_from_client{user="hello"} 20115698836 (18.73 GB)
telemt_user_octets_to_client{user="hello"} 498753992557 (464.50 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 122
telemt_user_unique_ips_recent_window{user="hello"} 42
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 101016.8 (28h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1096389
telemt_connections_bad_total 13106
telemt_handshake_timeouts_total 72565
telemt_upstream_connect_attempt_total 35215
telemt_upstream_connect_success_total 32943
telemt_upstream_connect_fail_total 2135
telemt_upstream_connect_attempts_per_request{bucket="1"} 34941
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20391
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12463
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 89
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2134
telemt_me_keepalive_timeout_total 11277
telemt_me_reconnect_attempts_total 29872
telemt_me_reconnect_success_total 22029
telemt_me_reader_eof_total 23805
telemt_me_idle_close_by_peer_total 23798
telemt_me_route_drop_no_conn_total 387483
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 940046
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1895
telemt_desync_full_logged_total 628
telemt_desync_suppressed_total 1267
telemt_desync_frames_bucket_total{bucket="1_2"} 522
telemt_desync_frames_bucket_total{bucket="3_10"} 743
telemt_desync_frames_bucket_total{bucket="gt_10"} 630
telemt_pool_swap_total 86
telemt_me_writer_removed_unexpected_total 22415
telemt_me_refill_failed_total 241
telemt_me_writer_restored_same_endpoint_total 22007
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 2298
telemt_me_writer_removed_unexpected_minus_restored_total 386
telemt_user_connections_total{user="hello"} 945231
telemt_user_connections_current{user="hello"} 223
telemt_user_octets_from_client{user="hello"} 14483971245 (13.49 GB)
telemt_user_octets_to_client{user="hello"} 370406768986 (344.97 GB)
telemt_user_msgs_from_client{user="hello"} 44500
telemt_user_msgs_to_client{user="hello"} 116355
telemt_user_unique_ips_current{user="hello"} 92
telemt_user_unique_ips_recent_window{user="hello"} 32
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 101016.8 (28h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1208988
telemt_connections_bad_total 12595
telemt_handshake_timeouts_total 9427
telemt_upstream_connect_attempt_total 31269
telemt_upstream_connect_success_total 30879
telemt_upstream_connect_fail_total 389
telemt_upstream_connect_attempts_per_request{bucket="1"} 31268
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15772
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14935
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 13
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 159
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 389
telemt_me_keepalive_timeout_total 1861
telemt_me_reconnect_attempts_total 37035
telemt_me_reconnect_success_total 25826
telemt_me_reader_eof_total 27132
telemt_me_idle_close_by_peer_total 27132
telemt_me_seq_mismatch_total 36
telemt_me_route_drop_no_conn_total 453105
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1117204
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 40
telemt_me_hardswap_pending_ttl_expired_total 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 4171
telemt_desync_full_logged_total 1478
telemt_desync_suppressed_total 2693
telemt_desync_frames_bucket_total{bucket="1_2"} 1250
telemt_desync_frames_bucket_total{bucket="3_10"} 1382
telemt_desync_frames_bucket_total{bucket="gt_10"} 1539
telemt_pool_swap_total 52
telemt_me_writer_removed_unexpected_total 26478
telemt_me_refill_failed_total 347
telemt_me_writer_restored_same_endpoint_total 25779
telemt_me_writer_restored_fallback_total 47
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 652
telemt_user_connections_total{user="hello"} 1117060
telemt_user_connections_current{user="hello"} 314
telemt_user_octets_from_client{user="hello"} 13758399244 (12.81 GB)
telemt_user_octets_to_client{user="hello"} 384345309116 (357.95 GB)
telemt_user_unique_ips_current{user="hello"} 111
telemt_user_unique_ips_recent_window{user="hello"} 42
```