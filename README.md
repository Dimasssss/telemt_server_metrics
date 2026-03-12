# Server Metrics 2026-03-12 10:09:35 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 15055.8 (4h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 487733
telemt_connections_bad_total 1461
telemt_handshake_timeouts_total 2778
telemt_upstream_connect_attempt_total 2963
telemt_upstream_connect_success_total 2945
telemt_upstream_connect_fail_total 18
telemt_upstream_connect_attempts_per_request{bucket="1"} 2963
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1620
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1322
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 18
telemt_me_keepalive_timeout_total 282
telemt_me_reconnect_attempts_total 4801
telemt_me_reconnect_success_total 2164
telemt_me_reader_eof_total 2313
telemt_me_idle_close_by_peer_total 2313
telemt_me_route_drop_no_conn_total 168039
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 472211
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2235
telemt_desync_full_logged_total 559
telemt_desync_suppressed_total 1676
telemt_desync_frames_bucket_total{bucket="1_2"} 572
telemt_desync_frames_bucket_total{bucket="3_10"} 824
telemt_desync_frames_bucket_total{bucket="gt_10"} 839
telemt_pool_swap_total 10
telemt_me_writer_removed_unexpected_total 2263
telemt_me_refill_failed_total 82
telemt_me_writer_restored_same_endpoint_total 2151
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 99
telemt_user_connections_total{user="hello"} 472083
telemt_user_connections_current{user="hello"} 1536
telemt_user_octets_from_client{user="hello"} 7707137880 (7.18 GB)
telemt_user_octets_to_client{user="hello"} 128533500988 (119.71 GB)
telemt_user_unique_ips_current{user="hello"} 409
telemt_user_unique_ips_recent_window{user="hello"} 205
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 44676.2 (12h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 282341
telemt_connections_bad_total 3000
telemt_handshake_timeouts_total 8485
telemt_upstream_connect_attempt_total 11295
telemt_upstream_connect_success_total 11289
telemt_upstream_connect_fail_total 6
telemt_upstream_connect_attempts_per_request{bucket="1"} 11295
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5540
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5734
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 15
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 6
telemt_me_keepalive_timeout_total 670
telemt_me_reconnect_attempts_total 8921
telemt_me_reconnect_success_total 8878
telemt_me_reader_eof_total 9426
telemt_me_idle_close_by_peer_total 9426
telemt_me_route_drop_no_conn_total 82161
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 252229
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 523
telemt_desync_full_logged_total 209
telemt_desync_suppressed_total 314
telemt_desync_frames_bucket_total{bucket="1_2"} 143
telemt_desync_frames_bucket_total{bucket="3_10"} 195
telemt_desync_frames_bucket_total{bucket="gt_10"} 185
telemt_pool_swap_total 46
telemt_me_writer_removed_unexpected_total 8947
telemt_me_writer_restored_same_endpoint_total 8869
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 69
telemt_user_connections_total{user="hello"} 252671
telemt_user_connections_current{user="hello"} 596
telemt_user_octets_from_client{user="hello"} 3525692739 (3.28 GB)
telemt_user_octets_to_client{user="hello"} 93922951734 (87.47 GB)
telemt_user_msgs_from_client{user="hello"} 353
telemt_user_msgs_to_client{user="hello"} 423
telemt_user_unique_ips_current{user="hello"} 170
telemt_user_unique_ips_recent_window{user="hello"} 86
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 44676.1 (12h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 725260
telemt_connections_bad_total 3648
telemt_handshake_timeouts_total 53059
telemt_upstream_connect_attempt_total 11309
telemt_upstream_connect_success_total 11304
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 11309
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6279
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4972
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 49
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 582
telemt_me_reconnect_attempts_total 8794
telemt_me_reconnect_success_total 8721
telemt_me_reader_eof_total 9158
telemt_me_idle_close_by_peer_total 9158
telemt_me_route_drop_no_conn_total 160196
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 455945
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2088
telemt_desync_full_logged_total 619
telemt_desync_suppressed_total 1469
telemt_desync_frames_bucket_total{bucket="1_2"} 273
telemt_desync_frames_bucket_total{bucket="3_10"} 719
telemt_desync_frames_bucket_total{bucket="gt_10"} 1096
telemt_pool_swap_total 44
telemt_me_writer_removed_unexpected_total 8730
telemt_me_refill_failed_total 1
telemt_me_writer_restored_same_endpoint_total 8680
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 9
telemt_user_connections_total{user="hello"} 456204
telemt_user_connections_current{user="hello"} 822
telemt_user_octets_from_client{user="hello"} 5456572320 (5.08 GB)
telemt_user_octets_to_client{user="hello"} 149668132077 (139.39 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 257
telemt_user_unique_ips_recent_window{user="hello"} 132
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 44676.4 (12h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 365717
telemt_connections_bad_total 2048
telemt_handshake_timeouts_total 26896
telemt_upstream_connect_attempt_total 12168
telemt_upstream_connect_success_total 12119
telemt_upstream_connect_fail_total 49
telemt_upstream_connect_attempts_per_request{bucket="1"} 12168
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6897
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5213
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 49
telemt_me_keepalive_timeout_total 828
telemt_me_reconnect_attempts_total 9922
telemt_me_reconnect_success_total 9885
telemt_me_reader_eof_total 10487
telemt_me_idle_close_by_peer_total 10487
telemt_me_route_drop_no_conn_total 124882
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 308515
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 671
telemt_desync_full_logged_total 236
telemt_desync_suppressed_total 435
telemt_desync_frames_bucket_total{bucket="1_2"} 206
telemt_desync_frames_bucket_total{bucket="3_10"} 285
telemt_desync_frames_bucket_total{bucket="gt_10"} 180
telemt_pool_swap_total 43
telemt_me_writer_removed_unexpected_total 9950
telemt_me_writer_restored_same_endpoint_total 9864
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 108
telemt_me_writer_removed_unexpected_minus_restored_total 65
telemt_user_connections_total{user="hello"} 308337
telemt_user_connections_current{user="hello"} 556
telemt_user_octets_from_client{user="hello"} 3766401028 (3.51 GB)
telemt_user_octets_to_client{user="hello"} 121270574080 (112.94 GB)
telemt_user_unique_ips_current{user="hello"} 162
telemt_user_unique_ips_recent_window{user="hello"} 103
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 44676.3 (12h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 415183
telemt_connections_bad_total 466
telemt_handshake_timeouts_total 3226
telemt_upstream_connect_attempt_total 14564
telemt_upstream_connect_success_total 14391
telemt_upstream_connect_fail_total 173
telemt_upstream_connect_attempts_per_request{bucket="1"} 14564
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7454
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6854
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 77
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 173
telemt_me_keepalive_timeout_total 624
telemt_me_reconnect_attempts_total 13673
telemt_me_reconnect_success_total 12149
telemt_me_reader_eof_total 12643
telemt_me_idle_close_by_peer_total 12643
telemt_me_seq_mismatch_total 17
telemt_me_route_drop_no_conn_total 134275
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 392247
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 1660
telemt_desync_full_logged_total 543
telemt_desync_suppressed_total 1117
telemt_desync_frames_bucket_total{bucket="1_2"} 488
telemt_desync_frames_bucket_total{bucket="3_10"} 577
telemt_desync_frames_bucket_total{bucket="gt_10"} 595
telemt_pool_swap_total 25
telemt_me_writer_removed_unexpected_total 12314
telemt_me_refill_failed_total 46
telemt_me_writer_restored_same_endpoint_total 12127
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 165
telemt_user_connections_total{user="hello"} 392176
telemt_user_connections_current{user="hello"} 778
telemt_user_octets_from_client{user="hello"} 4352397928 (4.05 GB)
telemt_user_octets_to_client{user="hello"} 94263020344 (87.79 GB)
telemt_user_unique_ips_current{user="hello"} 203
telemt_user_unique_ips_recent_window{user="hello"} 119
```