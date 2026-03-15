# Server Metrics 2026-03-15 12:58:27 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.18

telemt_uptime_seconds 53037.2 (14h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1528248
telemt_connections_bad_total 88328
telemt_handshake_timeouts_total 13488
telemt_upstream_connect_attempt_total 10512
telemt_upstream_connect_success_total 10464
telemt_upstream_connect_fail_total 48
telemt_upstream_connect_attempts_per_request{bucket="1"} 10512
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5526
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4904
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 34
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 48
telemt_me_keepalive_timeout_total 13
telemt_me_reconnect_attempts_total 12698
telemt_me_reconnect_success_total 7816
telemt_me_reader_eof_total 8383
telemt_me_idle_close_by_peer_total 8383
telemt_me_route_drop_no_conn_total 514212
telemt_me_route_drop_channel_closed_total 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1286020
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4817
telemt_desync_full_logged_total 1360
telemt_desync_suppressed_total 3457
telemt_desync_frames_bucket_total{bucket="1_2"} 1202
telemt_desync_frames_bucket_total{bucket="3_10"} 1888
telemt_desync_frames_bucket_total{bucket="gt_10"} 1727
telemt_pool_swap_total 41
telemt_me_writer_removed_unexpected_total 8089
telemt_me_refill_failed_total 151
telemt_me_writer_restored_same_endpoint_total 7805
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 296
telemt_me_writer_removed_unexpected_minus_restored_total 273
telemt_user_connections_total{user="hello"} 1285666
telemt_user_connections_current{user="hello"} 2428
telemt_user_octets_from_client{user="hello"} 18063285468 (16.82 GB)
telemt_user_octets_to_client{user="hello"} 511908970312 (476.75 GB)
telemt_user_unique_ips_current{user="hello"} 662
telemt_user_unique_ips_recent_window{user="hello"} 327
```

## server2

```
telemt 3.3.18

telemt_uptime_seconds 53037.9 (14h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 614080
telemt_connections_bad_total 31292
telemt_handshake_timeouts_total 39282
telemt_upstream_connect_attempt_total 13656
telemt_upstream_connect_success_total 13586
telemt_upstream_connect_fail_total 70
telemt_upstream_connect_attempts_per_request{bucket="1"} 13656
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7333
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6130
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 34
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 89
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 70
telemt_me_keepalive_timeout_total 15
telemt_me_reconnect_attempts_total 10684
telemt_me_reconnect_success_total 10605
telemt_me_reader_eof_total 11217
telemt_me_idle_close_by_peer_total 11217
telemt_me_route_drop_no_conn_total 154506
telemt_me_route_drop_channel_closed_total 3
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 469993
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 16
telemt_me_endpoint_quarantine_total 17
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1840
telemt_desync_full_logged_total 641
telemt_desync_suppressed_total 1199
telemt_desync_frames_bucket_total{bucket="1_2"} 700
telemt_desync_frames_bucket_total{bucket="3_10"} 672
telemt_desync_frames_bucket_total{bucket="gt_10"} 468
telemt_pool_swap_total 46
telemt_me_writer_removed_unexpected_total 10728
telemt_me_writer_restored_same_endpoint_total 10593
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 61
telemt_me_writer_removed_unexpected_minus_restored_total 123
telemt_user_connections_total{user="hello"} 470264
telemt_user_connections_current{user="hello"} 728
telemt_user_octets_from_client{user="hello"} 6600179043 (6.15 GB)
telemt_user_octets_to_client{user="hello"} 174524150520 (162.54 GB)
telemt_user_msgs_from_client{user="hello"} 620
telemt_user_msgs_to_client{user="hello"} 1332
telemt_user_unique_ips_current{user="hello"} 215
telemt_user_unique_ips_recent_window{user="hello"} 103
```

## server3

```
telemt 3.3.18

telemt_uptime_seconds 53037.9 (14h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1244148
telemt_connections_bad_total 40609
telemt_handshake_timeouts_total 127497
telemt_upstream_connect_attempt_total 11682
telemt_upstream_connect_success_total 11626
telemt_upstream_connect_fail_total 56
telemt_upstream_connect_attempts_per_request{bucket="1"} 11682
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5996
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5571
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 59
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 56
telemt_me_reconnect_attempts_total 10212
telemt_me_reconnect_success_total 8966
telemt_me_reader_eof_total 9504
telemt_me_idle_close_by_peer_total 9504
telemt_me_route_drop_no_conn_total 368588
telemt_me_route_drop_channel_closed_total 17
telemt_me_route_drop_queue_full_total 6
telemt_me_route_drop_queue_full_profile_total{profile="high"} 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 822813
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2123
telemt_desync_full_logged_total 773
telemt_desync_suppressed_total 1350
telemt_desync_frames_bucket_total{bucket="1_2"} 483
telemt_desync_frames_bucket_total{bucket="3_10"} 790
telemt_desync_frames_bucket_total{bucket="gt_10"} 850
telemt_pool_swap_total 47
telemt_me_writer_removed_unexpected_total 9120
telemt_me_refill_failed_total 37
telemt_me_writer_restored_same_endpoint_total 8947
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 242
telemt_me_writer_removed_unexpected_minus_restored_total 154
telemt_user_connections_total{user="hello"} 819308
telemt_user_connections_current{user="hello"} 1215
telemt_user_octets_from_client{user="hello"} 12071745640 (11.24 GB)
telemt_user_octets_to_client{user="hello"} 305305453156 (284.34 GB)
telemt_user_unique_ips_current{user="hello"} 379
telemt_user_unique_ips_recent_window{user="hello"} 197
```

## server4

```
telemt 3.3.18

telemt_uptime_seconds 53037.8 (14h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 616763
telemt_connections_bad_total 67329
telemt_handshake_timeouts_total 34212
telemt_upstream_connect_attempt_total 39312
telemt_upstream_connect_success_total 38904
telemt_upstream_connect_fail_total 407
telemt_upstream_connect_attempts_per_request{bucket="1"} 39311
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 30567
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8334
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 407
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 42578
telemt_me_reconnect_success_total 11747
telemt_me_reader_eof_total 13044
telemt_me_idle_close_by_peer_total 13044
telemt_me_seq_mismatch_total 19
telemt_me_route_drop_no_conn_total 165812
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 433572
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 36
telemt_me_hardswap_pending_ttl_expired_total 10
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1144
telemt_desync_full_logged_total 288
telemt_desync_suppressed_total 856
telemt_desync_frames_bucket_total{bucket="1_2"} 307
telemt_desync_frames_bucket_total{bucket="3_10"} 468
telemt_desync_frames_bucket_total{bucket="gt_10"} 369
telemt_pool_swap_total 17
telemt_me_writer_removed_unexpected_total 12821
telemt_me_refill_failed_total 964
telemt_me_writer_restored_same_endpoint_total 11715
telemt_me_writer_restored_fallback_total 32
telemt_me_async_recovery_trigger_total 96
telemt_me_writer_removed_unexpected_minus_restored_total 1074
telemt_user_connections_total{user="hello"} 457949
telemt_user_connections_current{user="hello"} 731
telemt_user_octets_from_client{user="hello"} 8753536089 (8.15 GB)
telemt_user_octets_to_client{user="hello"} 161323699977 (150.24 GB)
telemt_user_msgs_from_client{user="hello"} 426419
telemt_user_msgs_to_client{user="hello"} 1606452
telemt_user_unique_ips_current{user="hello"} 168
telemt_user_unique_ips_recent_window{user="hello"} 128
```

## server5

```
telemt 3.3.18

telemt_uptime_seconds 53038.9 (14h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 655176
telemt_connections_bad_total 8418
telemt_handshake_timeouts_total 13473
telemt_upstream_connect_attempt_total 11817
telemt_upstream_connect_success_total 11755
telemt_upstream_connect_fail_total 62
telemt_upstream_connect_attempts_per_request{bucket="1"} 11817
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5395
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6354
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 62
telemt_me_reconnect_attempts_total 11432
telemt_me_reconnect_success_total 9108
telemt_me_reader_eof_total 9717
telemt_me_idle_close_by_peer_total 9717
telemt_me_route_drop_no_conn_total 163095
telemt_me_route_drop_channel_closed_total 21
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 531753
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2036
telemt_desync_full_logged_total 681
telemt_desync_suppressed_total 1355
telemt_desync_frames_bucket_total{bucket="1_2"} 589
telemt_desync_frames_bucket_total{bucket="3_10"} 814
telemt_desync_frames_bucket_total{bucket="gt_10"} 633
telemt_pool_swap_total 46
telemt_me_writer_removed_unexpected_total 9289
telemt_me_refill_failed_total 71
telemt_me_writer_restored_same_endpoint_total 9100
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 54
telemt_me_writer_removed_unexpected_minus_restored_total 181
telemt_user_connections_total{user="hello"} 531790
telemt_user_connections_current{user="hello"} 895
telemt_user_octets_from_client{user="hello"} 6855322844 (6.38 GB)
telemt_user_octets_to_client{user="hello"} 195869649168 (182.42 GB)
telemt_user_unique_ips_current{user="hello"} 237
telemt_user_unique_ips_recent_window{user="hello"} 109
```