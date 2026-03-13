# Server Metrics 2026-03-13 08:36:48 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 95886.7 (26h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2687395
telemt_connections_bad_total 36278
telemt_handshake_timeouts_total 30363
telemt_upstream_connect_attempt_total 18663
telemt_upstream_connect_success_total 18561
telemt_upstream_connect_fail_total 102
telemt_upstream_connect_attempts_per_request{bucket="1"} 18663
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9603
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8909
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 49
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 102
telemt_me_keepalive_timeout_total 1367
telemt_me_reconnect_attempts_total 22672
telemt_me_reconnect_success_total 13797
telemt_me_reader_eof_total 14862
telemt_me_idle_close_by_peer_total 14861
telemt_me_route_drop_no_conn_total 1001226
telemt_me_route_drop_channel_closed_total 14
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2459598
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 11063
telemt_desync_full_logged_total 2859
telemt_desync_suppressed_total 8204
telemt_desync_frames_bucket_total{bucket="1_2"} 2840
telemt_desync_frames_bucket_total{bucket="3_10"} 4142
telemt_desync_frames_bucket_total{bucket="gt_10"} 4081
telemt_pool_swap_total 81
telemt_me_writer_removed_unexpected_total 14266
telemt_me_refill_failed_total 275
telemt_me_writer_restored_same_endpoint_total 13784
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 469
telemt_user_connections_total{user="hello"} 2459170
telemt_user_connections_current{user="hello"} 1612
telemt_user_octets_from_client{user="hello"} 34638381272 (32.26 GB)
telemt_user_octets_to_client{user="hello"} 816231147540 (760.17 GB)
telemt_user_unique_ips_current{user="hello"} 455
telemt_user_unique_ips_recent_window{user="hello"} 231
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 125507.2 (34h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1094586
telemt_connections_bad_total 13723
telemt_handshake_timeouts_total 88641
telemt_upstream_connect_attempt_total 31307
telemt_upstream_connect_success_total 31276
telemt_upstream_connect_fail_total 31
telemt_upstream_connect_attempts_per_request{bucket="1"} 31307
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16124
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15062
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 90
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 31
telemt_me_keepalive_timeout_total 3633
telemt_me_reconnect_attempts_total 23516
telemt_me_reconnect_success_total 23395
telemt_me_reader_eof_total 24936
telemt_me_idle_close_by_peer_total 24936
telemt_me_route_drop_no_conn_total 337554
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 951488
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4190
telemt_desync_full_logged_total 1279
telemt_desync_suppressed_total 2911
telemt_desync_frames_bucket_total{bucket="1_2"} 1545
telemt_desync_frames_bucket_total{bucket="3_10"} 1372
telemt_desync_frames_bucket_total{bucket="gt_10"} 1273
telemt_pool_swap_total 129
telemt_me_writer_removed_unexpected_total 23625
telemt_me_writer_restored_same_endpoint_total 23386
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 230
telemt_user_connections_total{user="hello"} 953417
telemt_user_connections_current{user="hello"} 630
telemt_user_octets_from_client{user="hello"} 14620393996 (13.62 GB)
telemt_user_octets_to_client{user="hello"} 353609628787 (329.32 GB)
telemt_user_msgs_from_client{user="hello"} 6476
telemt_user_msgs_to_client{user="hello"} 18854
telemt_user_unique_ips_current{user="hello"} 186
telemt_user_unique_ips_recent_window{user="hello"} 98
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 125507.3 (34h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2139716
telemt_connections_bad_total 23674
telemt_handshake_timeouts_total 143165
telemt_upstream_connect_attempt_total 28825
telemt_upstream_connect_success_total 28815
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 28825
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15099
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13600
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 111
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_keepalive_timeout_total 1750
telemt_me_reconnect_attempts_total 23502
telemt_me_reconnect_success_total 22220
telemt_me_reader_eof_total 23540
telemt_me_idle_close_by_peer_total 23539
telemt_me_route_drop_no_conn_total 693025
telemt_me_route_drop_channel_closed_total 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1705466
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5728
telemt_desync_full_logged_total 1807
telemt_desync_suppressed_total 3921
telemt_desync_frames_bucket_total{bucket="1_2"} 940
telemt_desync_frames_bucket_total{bucket="3_10"} 2095
telemt_desync_frames_bucket_total{bucket="gt_10"} 2693
telemt_pool_swap_total 119
telemt_me_writer_removed_unexpected_total 22436
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 22179
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 216
telemt_user_connections_total{user="hello"} 1704922
telemt_user_connections_current{user="hello"} 1122
telemt_user_octets_from_client{user="hello"} 28581157536 (26.62 GB)
telemt_user_octets_to_client{user="hello"} 618748293037 (576.25 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 320
telemt_user_unique_ips_recent_window{user="hello"} 168
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 125507.5 (34h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1360613
telemt_connections_bad_total 14217
telemt_handshake_timeouts_total 83727
telemt_upstream_connect_attempt_total 41871
telemt_upstream_connect_success_total 39570
telemt_upstream_connect_fail_total 2164
telemt_upstream_connect_attempts_per_request{bucket="1"} 41597
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 24130
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15349
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 91
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2163
telemt_me_keepalive_timeout_total 11449
telemt_me_reconnect_attempts_total 36403
telemt_me_reconnect_success_total 27463
telemt_me_reader_eof_total 29577
telemt_me_idle_close_by_peer_total 29570
telemt_me_route_drop_no_conn_total 476962
telemt_me_route_drop_channel_closed_total 3
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1131420
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2190
telemt_desync_full_logged_total 714
telemt_desync_suppressed_total 1476
telemt_desync_frames_bucket_total{bucket="1_2"} 602
telemt_desync_frames_bucket_total{bucket="3_10"} 841
telemt_desync_frames_bucket_total{bucket="gt_10"} 747
telemt_pool_swap_total 108
telemt_me_writer_removed_unexpected_total 27935
telemt_me_refill_failed_total 274
telemt_me_writer_restored_same_endpoint_total 27439
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 472
telemt_user_connections_total{user="hello"} 1136181
telemt_user_connections_current{user="hello"} 635
telemt_user_octets_from_client{user="hello"} 17139119289 (15.96 GB)
telemt_user_octets_to_client{user="hello"} 453371461898 (422.24 GB)
telemt_user_msgs_from_client{user="hello"} 44500
telemt_user_msgs_to_client{user="hello"} 116355
telemt_user_unique_ips_current{user="hello"} 193
telemt_user_unique_ips_recent_window{user="hello"} 99
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 125507.4 (34h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1501972
telemt_connections_bad_total 30732
telemt_handshake_timeouts_total 12432
telemt_upstream_connect_attempt_total 39666
telemt_upstream_connect_success_total 39187
telemt_upstream_connect_fail_total 479
telemt_upstream_connect_attempts_per_request{bucket="1"} 39666
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19878
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19104
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 16
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 189
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 479
telemt_me_keepalive_timeout_total 2145
telemt_me_reconnect_attempts_total 46685
telemt_me_reconnect_success_total 32942
telemt_me_reader_eof_total 34552
telemt_me_idle_close_by_peer_total 34552
telemt_me_seq_mismatch_total 46
telemt_me_route_drop_no_conn_total 550158
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1376346
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 50
telemt_me_hardswap_pending_ttl_expired_total 17
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 4819
telemt_desync_full_logged_total 1726
telemt_desync_suppressed_total 3093
telemt_desync_frames_bucket_total{bucket="1_2"} 1470
telemt_desync_frames_bucket_total{bucket="3_10"} 1557
telemt_desync_frames_bucket_total{bucket="gt_10"} 1792
telemt_pool_swap_total 62
telemt_me_writer_removed_unexpected_total 33734
telemt_me_refill_failed_total 425
telemt_me_writer_restored_same_endpoint_total 32884
telemt_me_writer_restored_fallback_total 58
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 792
telemt_user_connections_total{user="hello"} 1376148
telemt_user_connections_current{user="hello"} 947
telemt_user_octets_from_client{user="hello"} 17566090640 (16.36 GB)
telemt_user_octets_to_client{user="hello"} 478050267572 (445.22 GB)
telemt_user_unique_ips_current{user="hello"} 233
telemt_user_unique_ips_recent_window{user="hello"} 117
```