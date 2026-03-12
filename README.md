# Server Metrics 2026-03-12 10:45:16 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 17196.7 (4h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 571122
telemt_connections_bad_total 1468
telemt_handshake_timeouts_total 3272
telemt_upstream_connect_attempt_total 3323
telemt_upstream_connect_success_total 3301
telemt_upstream_connect_fail_total 22
telemt_upstream_connect_attempts_per_request{bucket="1"} 3323
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1838
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1460
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 22
telemt_me_keepalive_timeout_total 302
telemt_me_reconnect_attempts_total 6277
telemt_me_reconnect_success_total 2390
telemt_me_reader_eof_total 2593
telemt_me_idle_close_by_peer_total 2593
telemt_me_route_drop_no_conn_total 196684
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 549950
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2632
telemt_desync_full_logged_total 661
telemt_desync_suppressed_total 1971
telemt_desync_frames_bucket_total{bucket="1_2"} 669
telemt_desync_frames_bucket_total{bucket="3_10"} 970
telemt_desync_frames_bucket_total{bucket="gt_10"} 993
telemt_pool_swap_total 11
telemt_me_writer_removed_unexpected_total 2535
telemt_me_refill_failed_total 121
telemt_me_writer_restored_same_endpoint_total 2377
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 145
telemt_user_connections_total{user="hello"} 549812
telemt_user_connections_current{user="hello"} 1537
telemt_user_octets_from_client{user="hello"} 10033222852 (9.34 GB)
telemt_user_octets_to_client{user="hello"} 149682799096 (139.40 GB)
telemt_user_unique_ips_current{user="hello"} 401
telemt_user_unique_ips_recent_window{user="hello"} 243
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 46817.4 (13h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 311728
telemt_connections_bad_total 3439
telemt_handshake_timeouts_total 9451
telemt_upstream_connect_attempt_total 11712
telemt_upstream_connect_success_total 11706
telemt_upstream_connect_fail_total 6
telemt_upstream_connect_attempts_per_request{bucket="1"} 11712
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5740
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5951
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 15
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 6
telemt_me_keepalive_timeout_total 676
telemt_me_reconnect_attempts_total 9248
telemt_me_reconnect_success_total 9197
telemt_me_reader_eof_total 9776
telemt_me_idle_close_by_peer_total 9776
telemt_me_route_drop_no_conn_total 90187
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 279503
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 591
telemt_desync_full_logged_total 232
telemt_desync_suppressed_total 359
telemt_desync_frames_bucket_total{bucket="1_2"} 182
telemt_desync_frames_bucket_total{bucket="3_10"} 214
telemt_desync_frames_bucket_total{bucket="gt_10"} 195
telemt_pool_swap_total 48
telemt_me_writer_removed_unexpected_total 9277
telemt_me_writer_restored_same_endpoint_total 9188
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 80
telemt_user_connections_total{user="hello"} 279936
telemt_user_connections_current{user="hello"} 670
telemt_user_octets_from_client{user="hello"} 3886065343 (3.62 GB)
telemt_user_octets_to_client{user="hello"} 101648686854 (94.67 GB)
telemt_user_msgs_from_client{user="hello"} 353
telemt_user_msgs_to_client{user="hello"} 423
telemt_user_unique_ips_current{user="hello"} 175
telemt_user_unique_ips_recent_window{user="hello"} 104
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 46817.3 (13h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 773031
telemt_connections_bad_total 3974
telemt_handshake_timeouts_total 56423
telemt_upstream_connect_attempt_total 11681
telemt_upstream_connect_success_total 11676
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 11681
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6455
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5168
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 49
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 589
telemt_me_reconnect_attempts_total 9080
telemt_me_reconnect_success_total 9003
telemt_me_reader_eof_total 9463
telemt_me_idle_close_by_peer_total 9463
telemt_me_route_drop_no_conn_total 175313
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 498850
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2257
telemt_desync_full_logged_total 665
telemt_desync_suppressed_total 1592
telemt_desync_frames_bucket_total{bucket="1_2"} 295
telemt_desync_frames_bucket_total{bucket="3_10"} 776
telemt_desync_frames_bucket_total{bucket="gt_10"} 1186
telemt_pool_swap_total 46
telemt_me_writer_removed_unexpected_total 9018
telemt_me_refill_failed_total 1
telemt_me_writer_restored_same_endpoint_total 8962
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 15
telemt_user_connections_total{user="hello"} 499103
telemt_user_connections_current{user="hello"} 857
telemt_user_octets_from_client{user="hello"} 5918657480 (5.51 GB)
telemt_user_octets_to_client{user="hello"} 160268720581 (149.26 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 267
telemt_user_unique_ips_recent_window{user="hello"} 160
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 46817.6 (13h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 400264
telemt_connections_bad_total 2480
telemt_handshake_timeouts_total 30791
telemt_upstream_connect_attempt_total 12543
telemt_upstream_connect_success_total 12493
telemt_upstream_connect_fail_total 50
telemt_upstream_connect_attempts_per_request{bucket="1"} 12543
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7090
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5394
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 50
telemt_me_keepalive_timeout_total 845
telemt_me_reconnect_attempts_total 10209
telemt_me_reconnect_success_total 10170
telemt_me_reader_eof_total 10790
telemt_me_idle_close_by_peer_total 10790
telemt_me_route_drop_no_conn_total 134537
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 338154
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 701
telemt_desync_full_logged_total 247
telemt_desync_suppressed_total 454
telemt_desync_frames_bucket_total{bucket="1_2"} 214
telemt_desync_frames_bucket_total{bucket="3_10"} 297
telemt_desync_frames_bucket_total{bucket="gt_10"} 190
telemt_pool_swap_total 45
telemt_me_writer_removed_unexpected_total 10239
telemt_me_writer_restored_same_endpoint_total 10149
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 108
telemt_me_writer_removed_unexpected_minus_restored_total 69
telemt_user_connections_total{user="hello"} 337974
telemt_user_connections_current{user="hello"} 640
telemt_user_octets_from_client{user="hello"} 4026169928 (3.75 GB)
telemt_user_octets_to_client{user="hello"} 130379694944 (121.43 GB)
telemt_user_unique_ips_current{user="hello"} 177
telemt_user_unique_ips_recent_window{user="hello"} 99
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 46817.5 (13h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 452850
telemt_connections_bad_total 475
telemt_handshake_timeouts_total 3352
telemt_upstream_connect_attempt_total 15024
telemt_upstream_connect_success_total 14845
telemt_upstream_connect_fail_total 179
telemt_upstream_connect_attempts_per_request{bucket="1"} 15024
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7678
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7082
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 79
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 179
telemt_me_keepalive_timeout_total 633
telemt_me_reconnect_attempts_total 14038
telemt_me_reconnect_success_total 12514
telemt_me_reader_eof_total 13030
telemt_me_idle_close_by_peer_total 13030
telemt_me_seq_mismatch_total 19
telemt_me_route_drop_no_conn_total 146901
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 426181
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 1784
telemt_desync_full_logged_total 592
telemt_desync_suppressed_total 1192
telemt_desync_frames_bucket_total{bucket="1_2"} 527
telemt_desync_frames_bucket_total{bucket="3_10"} 616
telemt_desync_frames_bucket_total{bucket="gt_10"} 641
telemt_pool_swap_total 26
telemt_me_writer_removed_unexpected_total 12685
telemt_me_refill_failed_total 46
telemt_me_writer_restored_same_endpoint_total 12490
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 171
telemt_user_connections_total{user="hello"} 426103
telemt_user_connections_current{user="hello"} 825
telemt_user_octets_from_client{user="hello"} 4823162120 (4.49 GB)
telemt_user_octets_to_client{user="hello"} 103207047216 (96.12 GB)
telemt_user_unique_ips_current{user="hello"} 201
telemt_user_unique_ips_recent_window{user="hello"} 128
```