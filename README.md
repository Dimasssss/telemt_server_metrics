# Server Metrics 2026-03-12 06:35:27 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 2207.9 (0h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 63601
telemt_connections_bad_total 1143
telemt_handshake_timeouts_total 633
telemt_upstream_connect_attempt_total 500
telemt_upstream_connect_success_total 497
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 500
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 334
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 163
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_keepalive_timeout_total 3
telemt_me_reconnect_attempts_total 341
telemt_me_reconnect_success_total 340
telemt_me_reader_eof_total 319
telemt_me_idle_close_by_peer_total 319
telemt_me_route_drop_no_conn_total 20481
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 60455
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 335
telemt_desync_full_logged_total 84
telemt_desync_suppressed_total 251
telemt_desync_frames_bucket_total{bucket="1_2"} 79
telemt_desync_frames_bucket_total{bucket="3_10"} 130
telemt_desync_frames_bucket_total{bucket="gt_10"} 126
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 332
telemt_me_writer_restored_same_endpoint_total 327
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_user_connections_total{user="hello"} 60425
telemt_user_connections_current{user="hello"} 1250
telemt_user_octets_from_client{user="hello"} 1477330216 (1.38 GB)
telemt_user_octets_to_client{user="hello"} 17531330264 (16.33 GB)
telemt_user_unique_ips_current{user="hello"} 336
telemt_user_unique_ips_recent_window{user="hello"} 196
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 31828.6 (8h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 131142
telemt_connections_bad_total 1727
telemt_handshake_timeouts_total 5024
telemt_upstream_connect_attempt_total 8416
telemt_upstream_connect_success_total 8411
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 8416
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4185
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4216
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 208
telemt_me_reconnect_attempts_total 6651
telemt_me_reconnect_success_total 6614
telemt_me_reader_eof_total 7036
telemt_me_idle_close_by_peer_total 7036
telemt_me_route_drop_no_conn_total 38914
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 117132
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 345
telemt_desync_full_logged_total 140
telemt_desync_suppressed_total 205
telemt_desync_frames_bucket_total{bucket="1_2"} 102
telemt_desync_frames_bucket_total{bucket="3_10"} 123
telemt_desync_frames_bucket_total{bucket="gt_10"} 120
telemt_pool_swap_total 34
telemt_me_writer_removed_unexpected_total 6669
telemt_me_writer_restored_same_endpoint_total 6605
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 55
telemt_user_connections_total{user="hello"} 117320
telemt_user_connections_current{user="hello"} 454
telemt_user_octets_from_client{user="hello"} 1774887807 (1.65 GB)
telemt_user_octets_to_client{user="hello"} 50393027134 (46.93 GB)
telemt_user_msgs_from_client{user="hello"} 353
telemt_user_msgs_to_client{user="hello"} 423
telemt_user_unique_ips_current{user="hello"} 128
telemt_user_unique_ips_recent_window{user="hello"} 68
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 31828.4 (8h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 465434
telemt_connections_bad_total 2278
telemt_handshake_timeouts_total 34270
telemt_upstream_connect_attempt_total 8698
telemt_upstream_connect_success_total 8696
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 8698
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4883
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3774
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 35
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_timeout_total 142
telemt_me_reconnect_attempts_total 6791
telemt_me_reconnect_success_total 6726
telemt_me_reader_eof_total 7049
telemt_me_idle_close_by_peer_total 7049
telemt_me_route_drop_no_conn_total 73768
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 221917
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 944
telemt_desync_full_logged_total 304
telemt_desync_suppressed_total 640
telemt_desync_frames_bucket_total{bucket="1_2"} 114
telemt_desync_frames_bucket_total{bucket="3_10"} 354
telemt_desync_frames_bucket_total{bucket="gt_10"} 476
telemt_pool_swap_total 33
telemt_me_writer_removed_unexpected_total 6708
telemt_me_refill_failed_total 1
telemt_me_writer_restored_same_endpoint_total 6685
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_user_connections_total{user="hello"} 222218
telemt_user_connections_current{user="hello"} 652
telemt_user_octets_from_client{user="hello"} 2350752200 (2.19 GB)
telemt_user_octets_to_client{user="hello"} 73652807049 (68.59 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 207
telemt_user_unique_ips_recent_window{user="hello"} 114
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 31828.8 (8h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 199813
telemt_connections_bad_total 1736
telemt_handshake_timeouts_total 12824
telemt_upstream_connect_attempt_total 9158
telemt_upstream_connect_success_total 9119
telemt_upstream_connect_fail_total 39
telemt_upstream_connect_attempts_per_request{bucket="1"} 9158
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5232
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3882
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 39
telemt_me_keepalive_timeout_total 246
telemt_me_reconnect_attempts_total 7535
telemt_me_reconnect_success_total 7507
telemt_me_reader_eof_total 7975
telemt_me_idle_close_by_peer_total 7975
telemt_me_route_drop_no_conn_total 62736
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 162302
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 252
telemt_desync_full_logged_total 87
telemt_desync_suppressed_total 165
telemt_desync_frames_bucket_total{bucket="1_2"} 81
telemt_desync_frames_bucket_total{bucket="3_10"} 99
telemt_desync_frames_bucket_total{bucket="gt_10"} 72
telemt_pool_swap_total 32
telemt_me_writer_removed_unexpected_total 7551
telemt_me_writer_restored_same_endpoint_total 7486
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 108
telemt_me_writer_removed_unexpected_minus_restored_total 44
telemt_user_connections_total{user="hello"} 162166
telemt_user_connections_current{user="hello"} 480
telemt_user_octets_from_client{user="hello"} 1851289408 (1.72 GB)
telemt_user_octets_to_client{user="hello"} 49544955000 (46.14 GB)
telemt_user_unique_ips_current{user="hello"} 147
telemt_user_unique_ips_recent_window{user="hello"} 91
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 31828.6 (8h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 210874
telemt_connections_bad_total 309
telemt_handshake_timeouts_total 1271
telemt_upstream_connect_attempt_total 10910
telemt_upstream_connect_success_total 10785
telemt_upstream_connect_fail_total 125
telemt_upstream_connect_attempts_per_request{bucket="1"} 10910
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5614
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5107
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 59
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 125
telemt_me_keepalive_timeout_total 204
telemt_me_reconnect_attempts_total 10673
telemt_me_reconnect_success_total 9163
telemt_me_reader_eof_total 9552
telemt_me_idle_close_by_peer_total 9552
telemt_me_seq_mismatch_total 14
telemt_me_route_drop_no_conn_total 64746
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 200591
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 778
telemt_desync_full_logged_total 259
telemt_desync_suppressed_total 519
telemt_desync_frames_bucket_total{bucket="1_2"} 188
telemt_desync_frames_bucket_total{bucket="3_10"} 292
telemt_desync_frames_bucket_total{bucket="gt_10"} 298
telemt_pool_swap_total 20
telemt_me_writer_removed_unexpected_total 9294
telemt_me_refill_failed_total 46
telemt_me_writer_restored_same_endpoint_total 9144
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 131
telemt_user_connections_total{user="hello"} 200545
telemt_user_connections_current{user="hello"} 577
telemt_user_octets_from_client{user="hello"} 1766254156 (1.64 GB)
telemt_user_octets_to_client{user="hello"} 46091615980 (42.93 GB)
telemt_user_unique_ips_current{user="hello"} 167
telemt_user_unique_ips_recent_window{user="hello"} 99
```