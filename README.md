# Server Metrics 2026-03-12 07:26:29 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 5269.7 (1h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 155998
telemt_connections_bad_total 1200
telemt_handshake_timeouts_total 1474
telemt_upstream_connect_attempt_total 1087
telemt_upstream_connect_success_total 1079
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 1087
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 618
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 461
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 8
telemt_me_reconnect_attempts_total 794
telemt_me_reconnect_success_total 790
telemt_me_reader_eof_total 792
telemt_me_idle_close_by_peer_total 792
telemt_me_route_drop_no_conn_total 51831
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 150184
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 749
telemt_desync_full_logged_total 196
telemt_desync_suppressed_total 553
telemt_desync_frames_bucket_total{bucket="1_2"} 170
telemt_desync_frames_bucket_total{bucket="3_10"} 265
telemt_desync_frames_bucket_total{bucket="gt_10"} 314
telemt_pool_swap_total 3
telemt_me_writer_removed_unexpected_total 789
telemt_me_writer_restored_same_endpoint_total 777
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_user_connections_total{user="hello"} 150109
telemt_user_connections_current{user="hello"} 1104
telemt_user_octets_from_client{user="hello"} 2559013668 (2.38 GB)
telemt_user_octets_to_client{user="hello"} 45094035724 (42.00 GB)
telemt_user_unique_ips_current{user="hello"} 354
telemt_user_unique_ips_recent_window{user="hello"} 153
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 34890.2 (9h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 166708
telemt_connections_bad_total 2300
telemt_handshake_timeouts_total 6494
telemt_upstream_connect_attempt_total 9033
telemt_upstream_connect_success_total 9027
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 9032
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4474
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4543
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 216
telemt_me_reconnect_attempts_total 7139
telemt_me_reconnect_success_total 7099
telemt_me_reader_eof_total 7549
telemt_me_idle_close_by_peer_total 7549
telemt_me_route_drop_no_conn_total 47629
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 143817
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 403
telemt_desync_full_logged_total 158
telemt_desync_suppressed_total 245
telemt_desync_frames_bucket_total{bucket="1_2"} 116
telemt_desync_frames_bucket_total{bucket="3_10"} 144
telemt_desync_frames_bucket_total{bucket="gt_10"} 143
telemt_pool_swap_total 37
telemt_me_writer_removed_unexpected_total 7157
telemt_me_writer_restored_same_endpoint_total 7090
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 58
telemt_user_connections_total{user="hello"} 144049
telemt_user_connections_current{user="hello"} 510
telemt_user_octets_from_client{user="hello"} 2268566411 (2.11 GB)
telemt_user_octets_to_client{user="hello"} 59417767290 (55.34 GB)
telemt_user_msgs_from_client{user="hello"} 353
telemt_user_msgs_to_client{user="hello"} 423
telemt_user_unique_ips_current{user="hello"} 135
telemt_user_unique_ips_recent_window{user="hello"} 63
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 34890.0 (9h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 522729
telemt_connections_bad_total 2436
telemt_handshake_timeouts_total 39117
telemt_upstream_connect_attempt_total 9301
telemt_upstream_connect_success_total 9299
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 9301
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5211
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4047
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 37
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_timeout_total 149
telemt_me_reconnect_attempts_total 7265
telemt_me_reconnect_success_total 7197
telemt_me_reader_eof_total 7549
telemt_me_idle_close_by_peer_total 7549
telemt_me_route_drop_no_conn_total 92769
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 272995
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1212
telemt_desync_full_logged_total 377
telemt_desync_suppressed_total 835
telemt_desync_frames_bucket_total{bucket="1_2"} 148
telemt_desync_frames_bucket_total{bucket="3_10"} 434
telemt_desync_frames_bucket_total{bucket="gt_10"} 630
telemt_pool_swap_total 36
telemt_me_writer_removed_unexpected_total 7184
telemt_me_refill_failed_total 1
telemt_me_writer_restored_same_endpoint_total 7156
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_user_connections_total{user="hello"} 273285
telemt_user_connections_current{user="hello"} 765
telemt_user_octets_from_client{user="hello"} 2895455288 (2.70 GB)
telemt_user_octets_to_client{user="hello"} 99309265089 (92.49 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 232
telemt_user_unique_ips_recent_window{user="hello"} 114
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 34890.4 (9h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 236658
telemt_connections_bad_total 1778
telemt_handshake_timeouts_total 14874
telemt_upstream_connect_attempt_total 9798
telemt_upstream_connect_success_total 9758
telemt_upstream_connect_fail_total 40
telemt_upstream_connect_attempts_per_request{bucket="1"} 9798
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5608
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4145
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 40
telemt_me_keepalive_timeout_total 258
telemt_me_reconnect_attempts_total 8045
telemt_me_reconnect_success_total 8016
telemt_me_reader_eof_total 8513
telemt_me_idle_close_by_peer_total 8513
telemt_me_route_drop_no_conn_total 77248
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 194434
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 340
telemt_desync_full_logged_total 129
telemt_desync_suppressed_total 211
telemt_desync_frames_bucket_total{bucket="1_2"} 124
telemt_desync_frames_bucket_total{bucket="3_10"} 124
telemt_desync_frames_bucket_total{bucket="gt_10"} 92
telemt_pool_swap_total 35
telemt_me_writer_removed_unexpected_total 8066
telemt_me_writer_restored_same_endpoint_total 7995
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 108
telemt_me_writer_removed_unexpected_minus_restored_total 50
telemt_user_connections_total{user="hello"} 194301
telemt_user_connections_current{user="hello"} 462
telemt_user_octets_from_client{user="hello"} 2239928932 (2.09 GB)
telemt_user_octets_to_client{user="hello"} 62678042804 (58.37 GB)
telemt_user_unique_ips_current{user="hello"} 146
telemt_user_unique_ips_recent_window{user="hello"} 74
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 34890.2 (9h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 253242
telemt_connections_bad_total 346
telemt_handshake_timeouts_total 1960
telemt_upstream_connect_attempt_total 11735
telemt_upstream_connect_success_total 11594
telemt_upstream_connect_fail_total 141
telemt_upstream_connect_attempts_per_request{bucket="1"} 11735
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6015
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5512
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 62
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 141
telemt_me_keepalive_timeout_total 215
telemt_me_reconnect_attempts_total 11352
telemt_me_reconnect_success_total 9840
telemt_me_reader_eof_total 10251
telemt_me_idle_close_by_peer_total 10251
telemt_me_seq_mismatch_total 15
telemt_me_route_drop_no_conn_total 78850
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 238113
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 956
telemt_desync_full_logged_total 320
telemt_desync_suppressed_total 636
telemt_desync_frames_bucket_total{bucket="1_2"} 226
telemt_desync_frames_bucket_total{bucket="3_10"} 359
telemt_desync_frames_bucket_total{bucket="gt_10"} 371
telemt_pool_swap_total 21
telemt_me_writer_removed_unexpected_total 9979
telemt_me_refill_failed_total 46
telemt_me_writer_restored_same_endpoint_total 9820
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 139
telemt_user_connections_total{user="hello"} 238067
telemt_user_connections_current{user="hello"} 643
telemt_user_octets_from_client{user="hello"} 2297793600 (2.14 GB)
telemt_user_octets_to_client{user="hello"} 56649712616 (52.76 GB)
telemt_user_unique_ips_current{user="hello"} 186
telemt_user_unique_ips_recent_window{user="hello"} 98
```