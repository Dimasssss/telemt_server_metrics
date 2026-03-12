# Server Metrics 2026-03-12 15:05:26 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 32806.5 (9h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1176475
telemt_connections_bad_total 20228
telemt_handshake_timeouts_total 12064
telemt_upstream_connect_attempt_total 6513
telemt_upstream_connect_success_total 6477
telemt_upstream_connect_fail_total 36
telemt_upstream_connect_attempts_per_request{bucket="1"} 6513
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3464
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3003
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 36
telemt_me_keepalive_timeout_total 409
telemt_me_reconnect_attempts_total 8700
telemt_me_reconnect_success_total 4796
telemt_me_reader_eof_total 5114
telemt_me_idle_close_by_peer_total 5113
telemt_me_route_drop_no_conn_total 416484
telemt_me_route_drop_channel_closed_total 8
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1106645
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5885
telemt_desync_full_logged_total 1475
telemt_desync_suppressed_total 4410
telemt_desync_frames_bucket_total{bucket="1_2"} 1513
telemt_desync_frames_bucket_total{bucket="3_10"} 2112
telemt_desync_frames_bucket_total{bucket="gt_10"} 2260
telemt_pool_swap_total 22
telemt_me_writer_removed_unexpected_total 4974
telemt_me_refill_failed_total 121
telemt_me_writer_restored_same_endpoint_total 4783
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 178
telemt_user_connections_total{user="hello"} 1106380
telemt_user_connections_current{user="hello"} 1616
telemt_user_octets_from_client{user="hello"} 17489290508 (16.29 GB)
telemt_user_octets_to_client{user="hello"} 323541323460 (301.32 GB)
telemt_user_unique_ips_current{user="hello"} 421
telemt_user_unique_ips_recent_window{user="hello"} 241
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 62427.0 (17h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 535845
telemt_connections_bad_total 6283
telemt_handshake_timeouts_total 26818
telemt_upstream_connect_attempt_total 15065
telemt_upstream_connect_success_total 15058
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 15065
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7466
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7576
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 16
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_keepalive_timeout_total 1178
telemt_me_reconnect_attempts_total 11813
telemt_me_reconnect_success_total 11747
telemt_me_reader_eof_total 12484
telemt_me_idle_close_by_peer_total 12484
telemt_me_route_drop_no_conn_total 156520
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 477540
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1836
telemt_desync_full_logged_total 578
telemt_desync_suppressed_total 1258
telemt_desync_frames_bucket_total{bucket="1_2"} 794
telemt_desync_frames_bucket_total{bucket="3_10"} 593
telemt_desync_frames_bucket_total{bucket="gt_10"} 449
telemt_pool_swap_total 63
telemt_me_writer_removed_unexpected_total 11856
telemt_me_writer_restored_same_endpoint_total 11738
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 109
telemt_user_connections_total{user="hello"} 478039
telemt_user_connections_current{user="hello"} 547
telemt_user_octets_from_client{user="hello"} 7346118903 (6.84 GB)
telemt_user_octets_to_client{user="hello"} 167869433398 (156.34 GB)
telemt_user_msgs_from_client{user="hello"} 353
telemt_user_msgs_to_client{user="hello"} 423
telemt_user_unique_ips_current{user="hello"} 161
telemt_user_unique_ips_recent_window{user="hello"} 99
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 62427.0 (17h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1148037
telemt_connections_bad_total 6071
telemt_handshake_timeouts_total 80976
telemt_upstream_connect_attempt_total 14998
telemt_upstream_connect_success_total 14993
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 14998
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8139
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6792
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 58
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 973
telemt_me_reconnect_attempts_total 12725
telemt_me_reconnect_success_total 11504
telemt_me_reader_eof_total 12137
telemt_me_idle_close_by_peer_total 12137
telemt_me_route_drop_no_conn_total 305035
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 837808
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3478
telemt_desync_full_logged_total 1071
telemt_desync_suppressed_total 2407
telemt_desync_frames_bucket_total{bucket="1_2"} 516
telemt_desync_frames_bucket_total{bucket="3_10"} 1267
telemt_desync_frames_bucket_total{bucket="gt_10"} 1695
telemt_pool_swap_total 59
telemt_me_writer_removed_unexpected_total 11585
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 11463
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 81
telemt_user_connections_total{user="hello"} 837996
telemt_user_connections_current{user="hello"} 1092
telemt_user_octets_from_client{user="hello"} 11075056948 (10.31 GB)
telemt_user_octets_to_client{user="hello"} 263388162009 (245.30 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 292
telemt_user_unique_ips_recent_window{user="hello"} 159
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 62427.5 (17h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 677789
telemt_connections_bad_total 7698
telemt_handshake_timeouts_total 57373
telemt_upstream_connect_attempt_total 16626
telemt_upstream_connect_success_total 16558
telemt_upstream_connect_fail_total 68
telemt_upstream_connect_attempts_per_request{bucket="1"} 16626
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9403
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7142
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 13
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 68
telemt_me_keepalive_timeout_total 1354
telemt_me_reconnect_attempts_total 17289
telemt_me_reconnect_success_total 13428
telemt_me_reader_eof_total 14284
telemt_me_idle_close_by_peer_total 14284
telemt_me_route_drop_no_conn_total 228682
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 579236
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1149
telemt_desync_full_logged_total 398
telemt_desync_suppressed_total 751
telemt_desync_frames_bucket_total{bucket="1_2"} 317
telemt_desync_frames_bucket_total{bucket="3_10"} 465
telemt_desync_frames_bucket_total{bucket="gt_10"} 367
telemt_pool_swap_total 53
telemt_me_writer_removed_unexpected_total 13650
telemt_me_refill_failed_total 119
telemt_me_writer_restored_same_endpoint_total 13407
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 108
telemt_me_writer_removed_unexpected_minus_restored_total 222
telemt_user_connections_total{user="hello"} 578737
telemt_user_connections_current{user="hello"} 723
telemt_user_octets_from_client{user="hello"} 6948853052 (6.47 GB)
telemt_user_octets_to_client{user="hello"} 231345941840 (215.46 GB)
telemt_user_unique_ips_current{user="hello"} 195
telemt_user_unique_ips_recent_window{user="hello"} 129
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 62427.1 (17h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 761978
telemt_connections_bad_total 6274
telemt_handshake_timeouts_total 6114
telemt_upstream_connect_attempt_total 19600
telemt_upstream_connect_success_total 19355
telemt_upstream_connect_fail_total 244
telemt_upstream_connect_attempts_per_request{bucket="1"} 19599
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9831
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9421
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 96
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 244
telemt_me_keepalive_timeout_total 1105
telemt_me_reconnect_attempts_total 23456
telemt_me_reconnect_success_total 16222
telemt_me_reader_eof_total 16989
telemt_me_idle_close_by_peer_total 16989
telemt_me_seq_mismatch_total 27
telemt_me_route_drop_no_conn_total 264719
telemt_me_route_drop_channel_closed_total 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 704305
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 31
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 2834
telemt_desync_full_logged_total 950
telemt_desync_suppressed_total 1884
telemt_desync_frames_bucket_total{bucket="1_2"} 799
telemt_desync_frames_bucket_total{bucket="3_10"} 975
telemt_desync_frames_bucket_total{bucket="gt_10"} 1060
telemt_pool_swap_total 30
telemt_me_writer_removed_unexpected_total 16617
telemt_me_refill_failed_total 224
telemt_me_writer_restored_same_endpoint_total 16188
telemt_me_writer_restored_fallback_total 34
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 395
telemt_user_connections_total{user="hello"} 704205
telemt_user_connections_current{user="hello"} 759
telemt_user_octets_from_client{user="hello"} 8384844700 (7.81 GB)
telemt_user_octets_to_client{user="hello"} 194214150744 (180.88 GB)
telemt_user_unique_ips_current{user="hello"} 220
telemt_user_unique_ips_recent_window{user="hello"} 123
```