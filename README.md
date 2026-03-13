# Server Metrics 2026-03-13 01:53:42 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 71701.9 (19h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2049096
telemt_connections_bad_total 26138
telemt_handshake_timeouts_total 21907
telemt_upstream_connect_attempt_total 14206
telemt_upstream_connect_success_total 14126
telemt_upstream_connect_fail_total 80
telemt_upstream_connect_attempts_per_request{bucket="1"} 14206
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7276
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6809
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 41
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 80
telemt_me_keepalive_timeout_total 1253
telemt_me_reconnect_attempts_total 19405
telemt_me_reconnect_success_total 10544
telemt_me_reader_eof_total 11396
telemt_me_idle_close_by_peer_total 11395
telemt_me_route_drop_no_conn_total 799048
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1906468
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8700
telemt_desync_full_logged_total 2264
telemt_desync_suppressed_total 6436
telemt_desync_frames_bucket_total{bucket="1_2"} 2292
telemt_desync_frames_bucket_total{bucket="3_10"} 3138
telemt_desync_frames_bucket_total{bucket="gt_10"} 3270
telemt_pool_swap_total 55
telemt_me_writer_removed_unexpected_total 10971
telemt_me_refill_failed_total 275
telemt_me_writer_restored_same_endpoint_total 10531
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 427
telemt_user_connections_total{user="hello"} 1905925
telemt_user_connections_current{user="hello"} 570
telemt_user_octets_from_client{user="hello"} 27850921500 (25.94 GB)
telemt_user_octets_to_client{user="hello"} 665503240176 (619.80 GB)
telemt_user_unique_ips_current{user="hello"} 207
telemt_user_unique_ips_recent_window{user="hello"} 84
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 101322.5 (28h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 844435
telemt_connections_bad_total 11791
telemt_handshake_timeouts_total 32028
telemt_upstream_connect_attempt_total 25808
telemt_upstream_connect_success_total 25779
telemt_upstream_connect_fail_total 29
telemt_upstream_connect_attempts_per_request{bucket="1"} 25808
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13406
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12284
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 89
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 29
telemt_me_keepalive_timeout_total 3450
telemt_me_reconnect_attempts_total 19190
telemt_me_reconnect_success_total 19084
telemt_me_reader_eof_total 20327
telemt_me_idle_close_by_peer_total 20327
telemt_me_route_drop_no_conn_total 271777
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 765615
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3078
telemt_desync_full_logged_total 967
telemt_desync_suppressed_total 2111
telemt_desync_frames_bucket_total{bucket="1_2"} 1251
telemt_desync_frames_bucket_total{bucket="3_10"} 999
telemt_desync_frames_bucket_total{bucket="gt_10"} 828
telemt_pool_swap_total 103
telemt_me_writer_removed_unexpected_total 19271
telemt_me_writer_restored_same_endpoint_total 19075
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 187
telemt_user_connections_total{user="hello"} 767518
telemt_user_connections_current{user="hello"} 233
telemt_user_octets_from_client{user="hello"} 12292783400 (11.45 GB)
telemt_user_octets_to_client{user="hello"} 290519366723 (270.57 GB)
telemt_user_msgs_from_client{user="hello"} 6476
telemt_user_msgs_to_client{user="hello"} 18854
telemt_user_unique_ips_current{user="hello"} 79
telemt_user_unique_ips_recent_window{user="hello"} 45
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 101322.3 (28h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1752743
telemt_connections_bad_total 9007
telemt_handshake_timeouts_total 116997
telemt_upstream_connect_attempt_total 23641
telemt_upstream_connect_success_total 23631
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 23641
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12468
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11070
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 88
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_keepalive_timeout_total 1594
telemt_me_reconnect_attempts_total 19489
telemt_me_reconnect_success_total 18226
telemt_me_reader_eof_total 19299
telemt_me_idle_close_by_peer_total 19298
telemt_me_route_drop_no_conn_total 573488
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1377674
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
telemt_me_writer_removed_unexpected_total 18399
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 18185
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 173
telemt_user_connections_total{user="hello"} 1377269
telemt_user_connections_current{user="hello"} 324
telemt_user_octets_from_client{user="hello"} 20124758720 (18.74 GB)
telemt_user_octets_to_client{user="hello"} 499097012385 (464.82 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 122
telemt_user_unique_ips_recent_window{user="hello"} 62
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 101322.5 (28h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1097619
telemt_connections_bad_total 13109
telemt_handshake_timeouts_total 72666
telemt_upstream_connect_attempt_total 35370
telemt_upstream_connect_success_total 33098
telemt_upstream_connect_fail_total 2135
telemt_upstream_connect_attempts_per_request{bucket="1"} 35096
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20494
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12515
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 89
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2134
telemt_me_keepalive_timeout_total 11280
telemt_me_reconnect_attempts_total 30027
telemt_me_reconnect_success_total 22184
telemt_me_reader_eof_total 23960
telemt_me_idle_close_by_peer_total 23953
telemt_me_route_drop_no_conn_total 388006
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 941041
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
telemt_me_writer_removed_unexpected_total 22570
telemt_me_refill_failed_total 241
telemt_me_writer_restored_same_endpoint_total 22162
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 2298
telemt_me_writer_removed_unexpected_minus_restored_total 386
telemt_user_connections_total{user="hello"} 946225
telemt_user_connections_current{user="hello"} 238
telemt_user_octets_from_client{user="hello"} 14489148745 (13.49 GB)
telemt_user_octets_to_client{user="hello"} 370648337322 (345.19 GB)
telemt_user_msgs_from_client{user="hello"} 44500
telemt_user_msgs_to_client{user="hello"} 116355
telemt_user_unique_ips_current{user="hello"} 93
telemt_user_unique_ips_recent_window{user="hello"} 40
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 101322.5 (28h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1210803
telemt_connections_bad_total 12596
telemt_handshake_timeouts_total 9443
telemt_upstream_connect_attempt_total 31496
telemt_upstream_connect_success_total 31107
telemt_upstream_connect_fail_total 389
telemt_upstream_connect_attempts_per_request{bucket="1"} 31496
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15891
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15043
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 13
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 160
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 389
telemt_me_keepalive_timeout_total 1866
telemt_me_reconnect_attempts_total 37262
telemt_me_reconnect_success_total 26054
telemt_me_reader_eof_total 27359
telemt_me_idle_close_by_peer_total 27359
telemt_me_seq_mismatch_total 36
telemt_me_route_drop_no_conn_total 453677
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1118943
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 40
telemt_me_hardswap_pending_ttl_expired_total 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 4180
telemt_desync_full_logged_total 1480
telemt_desync_suppressed_total 2700
telemt_desync_frames_bucket_total{bucket="1_2"} 1253
telemt_desync_frames_bucket_total{bucket="3_10"} 1384
telemt_desync_frames_bucket_total{bucket="gt_10"} 1543
telemt_pool_swap_total 52
telemt_me_writer_removed_unexpected_total 26705
telemt_me_refill_failed_total 347
telemt_me_writer_restored_same_endpoint_total 26007
telemt_me_writer_restored_fallback_total 47
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 651
telemt_user_connections_total{user="hello"} 1118799
telemt_user_connections_current{user="hello"} 318
telemt_user_octets_from_client{user="hello"} 13767855424 (12.82 GB)
telemt_user_octets_to_client{user="hello"} 385385104644 (358.92 GB)
telemt_user_unique_ips_current{user="hello"} 117
telemt_user_unique_ips_recent_window{user="hello"} 45
```