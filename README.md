# Server Metrics 2026-03-11 18:26:01 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 100735.4 (27h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2554375
telemt_connections_bad_total 48537
telemt_handshake_timeouts_total 56507
telemt_upstream_connect_attempt_total 21263
telemt_upstream_connect_success_total 21251
telemt_upstream_connect_fail_total 12
telemt_upstream_connect_attempts_per_request{bucket="1"} 21263
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10738
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10409
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 103
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 12
telemt_me_keepalive_timeout_total 5294
telemt_me_reconnect_attempts_total 34046
telemt_me_reconnect_success_total 16165
telemt_me_reader_eof_total 17485
telemt_me_idle_close_by_peer_total 17485
telemt_me_route_drop_no_conn_total 954010
telemt_me_route_drop_channel_closed_total 8
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2336498
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 11893
telemt_desync_full_logged_total 3280
telemt_desync_suppressed_total 8613
telemt_desync_frames_bucket_total{bucket="1_2"} 2933
telemt_desync_frames_bucket_total{bucket="3_10"} 4594
telemt_desync_frames_bucket_total{bucket="gt_10"} 4366
telemt_pool_swap_total 72
telemt_me_writer_removed_unexpected_total 16903
telemt_me_refill_failed_total 555
telemt_me_writer_restored_same_endpoint_total 16159
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 738
telemt_user_connections_total{user="hello"} 2334941
telemt_user_connections_current{user="hello"} 1204
telemt_user_octets_from_client{user="hello"} 34832811648 (32.44 GB)
telemt_user_octets_to_client{user="hello"} 661180323540 (615.77 GB)
telemt_user_unique_ips_current{user="hello"} 336
telemt_user_unique_ips_recent_window{user="hello"} 132
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 100792.1 (27h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 956589
telemt_connections_bad_total 16367
telemt_handshake_timeouts_total 85000
telemt_upstream_connect_attempt_total 31296
telemt_upstream_connect_success_total 28329
telemt_upstream_connect_fail_total 2967
telemt_upstream_connect_attempts_per_request{bucket="1"} 31296
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13341
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12733
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 209
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2046
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2967
telemt_me_keepalive_timeout_total 2822
telemt_me_reconnect_attempts_total 22438
telemt_me_reconnect_success_total 20328
telemt_me_reader_eof_total 21515
telemt_me_idle_close_by_peer_total 21512
telemt_me_route_drop_no_conn_total 361320
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 797686
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3130
telemt_desync_full_logged_total 1010
telemt_desync_suppressed_total 2120
telemt_desync_frames_bucket_total{bucket="1_2"} 977
telemt_desync_frames_bucket_total{bucket="3_10"} 1114
telemt_desync_frames_bucket_total{bucket="gt_10"} 1039
telemt_pool_swap_total 81
telemt_me_writer_removed_unexpected_total 20612
telemt_me_refill_failed_total 60
telemt_me_writer_restored_same_endpoint_total 20305
telemt_me_writer_restored_fallback_total 23
telemt_me_async_recovery_trigger_total 86
telemt_me_writer_removed_unexpected_minus_restored_total 284
telemt_user_connections_total{user="hello"} 800148
telemt_user_connections_current{user="hello"} 430
telemt_user_octets_from_client{user="hello"} 9660984722 (9.00 GB)
telemt_user_octets_to_client{user="hello"} 229995791400 (214.20 GB)
telemt_user_msgs_from_client{user="hello"} 7933
telemt_user_msgs_to_client{user="hello"} 11226
telemt_user_unique_ips_current{user="hello"} 130
telemt_user_unique_ips_recent_window{user="hello"} 74
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 100792.0 (27h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1643480
telemt_connections_bad_total 10391
telemt_handshake_timeouts_total 133217
telemt_upstream_connect_attempt_total 26131
telemt_upstream_connect_success_total 25805
telemt_upstream_connect_fail_total 326
telemt_upstream_connect_attempts_per_request{bucket="1"} 26131
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13897
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11776
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 131
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 326
telemt_me_keepalive_timeout_total 1953
telemt_me_reconnect_attempts_total 45661
telemt_me_reconnect_success_total 19654
telemt_me_reader_eof_total 21320
telemt_me_idle_close_by_peer_total 21320
telemt_me_route_drop_no_conn_total 597375
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1437303
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 10
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3930
telemt_desync_full_logged_total 1149
telemt_desync_suppressed_total 2781
telemt_desync_frames_bucket_total{bucket="1_2"} 926
telemt_desync_frames_bucket_total{bucket="3_10"} 1488
telemt_desync_frames_bucket_total{bucket="gt_10"} 1516
telemt_pool_swap_total 55
telemt_me_writer_removed_unexpected_total 20740
telemt_me_refill_failed_total 807
telemt_me_writer_restored_same_endpoint_total 19642
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 1086
telemt_user_connections_total{user="hello"} 1436987
telemt_user_connections_current{user="hello"} 808
telemt_user_octets_from_client{user="hello"} 17863794101 (16.64 GB)
telemt_user_octets_to_client{user="hello"} 437216108309 (407.19 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 244
telemt_user_unique_ips_recent_window{user="hello"} 115
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 100792.3 (27h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1170922
telemt_connections_bad_total 77992
telemt_handshake_timeouts_total 109283
telemt_upstream_connect_attempt_total 27129
telemt_upstream_connect_success_total 27129
telemt_upstream_connect_attempts_per_request{bucket="1"} 27129
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14799
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12324
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 1413
telemt_me_reconnect_attempts_total 26712
telemt_me_reconnect_success_total 22104
telemt_me_reader_eof_total 23479
telemt_me_idle_close_by_peer_total 23478
telemt_me_seq_mismatch_total 23
telemt_me_route_drop_no_conn_total 390037
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 949402
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 34
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1995
telemt_desync_full_logged_total 760
telemt_desync_suppressed_total 1235
telemt_desync_frames_bucket_total{bucket="1_2"} 722
telemt_desync_frames_bucket_total{bucket="3_10"} 685
telemt_desync_frames_bucket_total{bucket="gt_10"} 588
telemt_pool_swap_total 82
telemt_me_writer_removed_unexpected_total 22481
telemt_me_refill_failed_total 141
telemt_me_writer_restored_same_endpoint_total 22071
telemt_me_writer_restored_fallback_total 33
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 377
telemt_user_connections_total{user="hello"} 948665
telemt_user_connections_current{user="hello"} 451
telemt_user_octets_from_client{user="hello"} 11326656140 (10.55 GB)
telemt_user_octets_to_client{user="hello"} 288651583580 (268.83 GB)
telemt_user_unique_ips_current{user="hello"} 141
telemt_user_unique_ips_recent_window{user="hello"} 72
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 5468.3 (1h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 94457
telemt_connections_bad_total 315
telemt_handshake_timeouts_total 565
telemt_upstream_connect_attempt_total 1593
telemt_upstream_connect_success_total 1592
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 1593
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 866
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 713
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 13
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 26
telemt_me_reconnect_attempts_total 1282
telemt_me_reconnect_success_total 1269
telemt_me_reader_eof_total 1279
telemt_me_idle_close_by_peer_total 1279
telemt_me_seq_mismatch_total 1
telemt_me_route_drop_no_conn_total 31872
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 87546
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 184
telemt_desync_full_logged_total 58
telemt_desync_suppressed_total 126
telemt_desync_frames_bucket_total{bucket="1_2"} 41
telemt_desync_frames_bucket_total{bucket="3_10"} 61
telemt_desync_frames_bucket_total{bucket="gt_10"} 82
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 1280
telemt_me_writer_restored_same_endpoint_total 1246
telemt_me_writer_restored_fallback_total 23
telemt_me_async_recovery_trigger_total 256
telemt_me_writer_removed_unexpected_minus_restored_total 11
telemt_user_connections_total{user="hello"} 87533
telemt_user_connections_current{user="hello"} 592
telemt_user_octets_from_client{user="hello"} 6169368200 (5.75 GB)
telemt_user_octets_to_client{user="hello"} 31138375956 (29.00 GB)
telemt_user_unique_ips_current{user="hello"} 178
telemt_user_unique_ips_recent_window{user="hello"} 83
```