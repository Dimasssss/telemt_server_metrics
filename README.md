# Server Metrics 2026-03-12 14:50:08 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 31888.6 (8h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1138329
telemt_connections_bad_total 17624
telemt_handshake_timeouts_total 11905
telemt_upstream_connect_attempt_total 6323
telemt_upstream_connect_success_total 6289
telemt_upstream_connect_fail_total 34
telemt_upstream_connect_attempts_per_request{bucket="1"} 6323
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3355
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2924
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 34
telemt_me_keepalive_timeout_total 407
telemt_me_reconnect_attempts_total 8557
telemt_me_reconnect_success_total 4654
telemt_me_reader_eof_total 4971
telemt_me_idle_close_by_peer_total 4970
telemt_me_route_drop_no_conn_total 404226
telemt_me_route_drop_channel_closed_total 8
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1072877
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5743
telemt_desync_full_logged_total 1441
telemt_desync_suppressed_total 4302
telemt_desync_frames_bucket_total{bucket="1_2"} 1466
telemt_desync_frames_bucket_total{bucket="3_10"} 2069
telemt_desync_frames_bucket_total{bucket="gt_10"} 2208
telemt_pool_swap_total 22
telemt_me_writer_removed_unexpected_total 4830
telemt_me_refill_failed_total 121
telemt_me_writer_restored_same_endpoint_total 4641
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 176
telemt_user_connections_total{user="hello"} 1072614
telemt_user_connections_current{user="hello"} 1516
telemt_user_octets_from_client{user="hello"} 16988182984 (15.82 GB)
telemt_user_octets_to_client{user="hello"} 312782721512 (291.30 GB)
telemt_user_unique_ips_current{user="hello"} 412
telemt_user_unique_ips_recent_window{user="hello"} 233
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 61509.2 (17h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 524538
telemt_connections_bad_total 5728
telemt_handshake_timeouts_total 26626
telemt_upstream_connect_attempt_total 14770
telemt_upstream_connect_success_total 14763
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 14770
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7318
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7429
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 16
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_keepalive_timeout_total 1162
telemt_me_reconnect_attempts_total 11561
telemt_me_reconnect_success_total 11496
telemt_me_reader_eof_total 12208
telemt_me_idle_close_by_peer_total 12208
telemt_me_route_drop_no_conn_total 152695
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 467252
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1780
telemt_desync_full_logged_total 563
telemt_desync_suppressed_total 1217
telemt_desync_frames_bucket_total{bucket="1_2"} 757
telemt_desync_frames_bucket_total{bucket="3_10"} 578
telemt_desync_frames_bucket_total{bucket="gt_10"} 445
telemt_pool_swap_total 62
telemt_me_writer_removed_unexpected_total 11602
telemt_me_writer_restored_same_endpoint_total 11487
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 106
telemt_user_connections_total{user="hello"} 467751
telemt_user_connections_current{user="hello"} 543
telemt_user_octets_from_client{user="hello"} 7208840399 (6.71 GB)
telemt_user_octets_to_client{user="hello"} 165273932470 (153.92 GB)
telemt_user_msgs_from_client{user="hello"} 353
telemt_user_msgs_to_client{user="hello"} 423
telemt_user_unique_ips_current{user="hello"} 174
telemt_user_unique_ips_recent_window{user="hello"} 101
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 61509.2 (17h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1124975
telemt_connections_bad_total 6059
telemt_handshake_timeouts_total 80095
telemt_upstream_connect_attempt_total 14802
telemt_upstream_connect_success_total 14797
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 14802
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8038
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6697
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 58
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 972
telemt_me_reconnect_attempts_total 12575
telemt_me_reconnect_success_total 11354
telemt_me_reader_eof_total 11985
telemt_me_idle_close_by_peer_total 11985
telemt_me_route_drop_no_conn_total 296971
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 816183
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3396
telemt_desync_full_logged_total 1043
telemt_desync_suppressed_total 2353
telemt_desync_frames_bucket_total{bucket="1_2"} 505
telemt_desync_frames_bucket_total{bucket="3_10"} 1235
telemt_desync_frames_bucket_total{bucket="gt_10"} 1656
telemt_pool_swap_total 59
telemt_me_writer_removed_unexpected_total 11433
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 11313
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 79
telemt_user_connections_total{user="hello"} 816371
telemt_user_connections_current{user="hello"} 1008
telemt_user_octets_from_client{user="hello"} 10783239132 (10.04 GB)
telemt_user_octets_to_client{user="hello"} 258501220637 (240.75 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 270
telemt_user_unique_ips_recent_window{user="hello"} 138
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 61509.5 (17h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 661879
telemt_connections_bad_total 7694
telemt_handshake_timeouts_total 56898
telemt_upstream_connect_attempt_total 16400
telemt_upstream_connect_success_total 16332
telemt_upstream_connect_fail_total 68
telemt_upstream_connect_attempts_per_request{bucket="1"} 16400
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9264
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7055
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 13
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 68
telemt_me_keepalive_timeout_total 1349
telemt_me_reconnect_attempts_total 15764
telemt_me_reconnect_success_total 13247
telemt_me_reader_eof_total 14060
telemt_me_idle_close_by_peer_total 14060
telemt_me_route_drop_no_conn_total 223198
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 564209
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1130
telemt_desync_full_logged_total 390
telemt_desync_suppressed_total 740
telemt_desync_frames_bucket_total{bucket="1_2"} 313
telemt_desync_frames_bucket_total{bucket="3_10"} 459
telemt_desync_frames_bucket_total{bucket="gt_10"} 358
telemt_pool_swap_total 53
telemt_me_writer_removed_unexpected_total 13426
telemt_me_refill_failed_total 77
telemt_me_writer_restored_same_endpoint_total 13226
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 108
telemt_me_writer_removed_unexpected_minus_restored_total 179
telemt_user_connections_total{user="hello"} 563711
telemt_user_connections_current{user="hello"} 696
telemt_user_octets_from_client{user="hello"} 6812080280 (6.34 GB)
telemt_user_octets_to_client{user="hello"} 226766339540 (211.19 GB)
telemt_user_unique_ips_current{user="hello"} 190
telemt_user_unique_ips_recent_window{user="hello"} 109
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 61509.4 (17h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 744775
telemt_connections_bad_total 5522
telemt_handshake_timeouts_total 5976
telemt_upstream_connect_attempt_total 19231
telemt_upstream_connect_success_total 18997
telemt_upstream_connect_fail_total 234
telemt_upstream_connect_attempts_per_request{bucket="1"} 19231
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9635
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9259
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 96
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 234
telemt_me_keepalive_timeout_total 1076
telemt_me_reconnect_attempts_total 23142
telemt_me_reconnect_success_total 15911
telemt_me_reader_eof_total 16673
telemt_me_idle_close_by_peer_total 16673
telemt_me_seq_mismatch_total 27
telemt_me_route_drop_no_conn_total 257670
telemt_me_route_drop_channel_closed_total 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 688896
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 31
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 2781
telemt_desync_full_logged_total 935
telemt_desync_suppressed_total 1846
telemt_desync_frames_bucket_total{bucket="1_2"} 791
telemt_desync_frames_bucket_total{bucket="3_10"} 962
telemt_desync_frames_bucket_total{bucket="gt_10"} 1028
telemt_pool_swap_total 30
telemt_me_writer_removed_unexpected_total 16301
telemt_me_refill_failed_total 224
telemt_me_writer_restored_same_endpoint_total 15877
telemt_me_writer_restored_fallback_total 34
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 390
telemt_user_connections_total{user="hello"} 688797
telemt_user_connections_current{user="hello"} 760
telemt_user_octets_from_client{user="hello"} 8061752900 (7.51 GB)
telemt_user_octets_to_client{user="hello"} 189714826256 (176.69 GB)
telemt_user_unique_ips_current{user="hello"} 219
telemt_user_unique_ips_recent_window{user="hello"} 114
```