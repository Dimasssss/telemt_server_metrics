# Server Metrics 2026-03-12 21:23:24 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 55483.7 (15h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1862519
telemt_connections_bad_total 23751
telemt_handshake_timeouts_total 20436
telemt_upstream_connect_attempt_total 10802
telemt_upstream_connect_success_total 10740
telemt_upstream_connect_fail_total 62
telemt_upstream_connect_attempts_per_request{bucket="1"} 10802
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5584
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5120
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 36
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 62
telemt_me_keepalive_timeout_total 588
telemt_me_reconnect_attempts_total 16795
telemt_me_reconnect_success_total 7943
telemt_me_reader_eof_total 8591
telemt_me_idle_close_by_peer_total 8590
telemt_me_route_drop_no_conn_total 730380
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1735655
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8401
telemt_desync_full_logged_total 2176
telemt_desync_suppressed_total 6225
telemt_desync_frames_bucket_total{bucket="1_2"} 2208
telemt_desync_frames_bucket_total{bucket="3_10"} 3028
telemt_desync_frames_bucket_total{bucket="gt_10"} 3165
telemt_pool_swap_total 38
telemt_me_writer_removed_unexpected_total 8334
telemt_me_refill_failed_total 275
telemt_me_writer_restored_same_endpoint_total 7930
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 391
telemt_user_connections_total{user="hello"} 1735139
telemt_user_connections_current{user="hello"} 958
telemt_user_octets_from_client{user="hello"} 26517908788 (24.70 GB)
telemt_user_octets_to_client{user="hello"} 610475187588 (568.55 GB)
telemt_user_unique_ips_current{user="hello"} 297
telemt_user_unique_ips_recent_window{user="hello"} 101
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 85104.2 (23h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 777537
telemt_connections_bad_total 11661
telemt_handshake_timeouts_total 30974
telemt_upstream_connect_attempt_total 21510
telemt_upstream_connect_success_total 21481
telemt_upstream_connect_fail_total 29
telemt_upstream_connect_attempts_per_request{bucket="1"} 21510
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11342
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10051
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 88
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 29
telemt_me_keepalive_timeout_total 3392
telemt_me_reconnect_attempts_total 15669
telemt_me_reconnect_success_total 15577
telemt_me_reader_eof_total 16567
telemt_me_idle_close_by_peer_total 16567
telemt_me_route_drop_no_conn_total 251649
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 701358
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2976
telemt_desync_full_logged_total 919
telemt_desync_suppressed_total 2057
telemt_desync_frames_bucket_total{bucket="1_2"} 1169
telemt_desync_frames_bucket_total{bucket="3_10"} 980
telemt_desync_frames_bucket_total{bucket="gt_10"} 827
telemt_pool_swap_total 85
telemt_me_writer_removed_unexpected_total 15735
telemt_me_writer_restored_same_endpoint_total 15568
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 158
telemt_user_connections_total{user="hello"} 703235
telemt_user_connections_current{user="hello"} 322
telemt_user_octets_from_client{user="hello"} 11953675060 (11.13 GB)
telemt_user_octets_to_client{user="hello"} 270392387351 (251.82 GB)
telemt_user_msgs_from_client{user="hello"} 6476
telemt_user_msgs_to_client{user="hello"} 18854
telemt_user_unique_ips_current{user="hello"} 103
telemt_user_unique_ips_recent_window{user="hello"} 51
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 85104.2 (23h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1609008
telemt_connections_bad_total 7722
telemt_handshake_timeouts_total 111409
telemt_upstream_connect_attempt_total 19937
telemt_upstream_connect_success_total 19931
telemt_upstream_connect_fail_total 6
telemt_upstream_connect_attempts_per_request{bucket="1"} 19937
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10696
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9160
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 70
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 6
telemt_me_keepalive_timeout_total 1213
telemt_me_reconnect_attempts_total 16563
telemt_me_reconnect_success_total 15316
telemt_me_reader_eof_total 16173
telemt_me_idle_close_by_peer_total 16172
telemt_me_route_drop_no_conn_total 531545
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1245467
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4892
telemt_desync_full_logged_total 1504
telemt_desync_suppressed_total 3388
telemt_desync_frames_bucket_total{bucket="1_2"} 780
telemt_desync_frames_bucket_total{bucket="3_10"} 1767
telemt_desync_frames_bucket_total{bucket="gt_10"} 2345
telemt_pool_swap_total 77
telemt_me_writer_removed_unexpected_total 15459
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 15275
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 143
telemt_user_connections_total{user="hello"} 1245073
telemt_user_connections_current{user="hello"} 530
telemt_user_octets_from_client{user="hello"} 19431142532 (18.10 GB)
telemt_user_octets_to_client{user="hello"} 462103511197 (430.37 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 190
telemt_user_unique_ips_recent_window{user="hello"} 73
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 85104.1 (23h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 990555
telemt_connections_bad_total 12974
telemt_handshake_timeouts_total 71034
telemt_upstream_connect_attempt_total 21694
telemt_upstream_connect_success_total 21606
telemt_upstream_connect_fail_total 88
telemt_upstream_connect_attempts_per_request{bucket="1"} 21694
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12141
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9451
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 14
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 88
telemt_me_keepalive_timeout_total 1678
telemt_me_reconnect_attempts_total 25082
telemt_me_reconnect_success_total 17354
telemt_me_reader_eof_total 18537
telemt_me_idle_close_by_peer_total 18537
telemt_me_route_drop_no_conn_total 354426
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 861914
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1843
telemt_desync_full_logged_total 612
telemt_desync_suppressed_total 1231
telemt_desync_frames_bucket_total{bucket="1_2"} 513
telemt_desync_frames_bucket_total{bucket="3_10"} 715
telemt_desync_frames_bucket_total{bucket="gt_10"} 615
telemt_pool_swap_total 71
telemt_me_writer_removed_unexpected_total 17735
telemt_me_refill_failed_total 239
telemt_me_writer_restored_same_endpoint_total 17333
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 108
telemt_me_writer_removed_unexpected_minus_restored_total 381
telemt_user_connections_total{user="hello"} 861264
telemt_user_connections_current{user="hello"} 326
telemt_user_octets_from_client{user="hello"} 13456341984 (12.53 GB)
telemt_user_octets_to_client{user="hello"} 348036551448 (324.13 GB)
telemt_user_unique_ips_current{user="hello"} 116
telemt_user_unique_ips_recent_window{user="hello"} 51
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 85104.4 (23h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1110155
telemt_connections_bad_total 12513
telemt_handshake_timeouts_total 9034
telemt_upstream_connect_attempt_total 26309
telemt_upstream_connect_success_total 25986
telemt_upstream_connect_fail_total 323
telemt_upstream_connect_attempts_per_request{bucket="1"} 26309
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13303
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12539
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 10
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 134
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 323
telemt_me_keepalive_timeout_total 1430
telemt_me_reconnect_attempts_total 32757
telemt_me_reconnect_success_total 21719
telemt_me_reader_eof_total 22830
telemt_me_idle_close_by_peer_total 22830
telemt_me_seq_mismatch_total 33
telemt_me_route_drop_no_conn_total 416259
telemt_me_route_drop_channel_closed_total 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1020417
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 37
telemt_me_hardswap_pending_ttl_expired_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 3873
telemt_desync_full_logged_total 1348
telemt_desync_suppressed_total 2525
telemt_desync_frames_bucket_total{bucket="1_2"} 1141
telemt_desync_frames_bucket_total{bucket="3_10"} 1276
telemt_desync_frames_bucket_total{bucket="gt_10"} 1456
telemt_pool_swap_total 41
telemt_me_writer_removed_unexpected_total 22313
telemt_me_refill_failed_total 342
telemt_me_writer_restored_same_endpoint_total 21675
telemt_me_writer_restored_fallback_total 44
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 594
telemt_user_connections_total{user="hello"} 1020277
telemt_user_connections_current{user="hello"} 420
telemt_user_octets_from_client{user="hello"} 12702325776 (11.83 GB)
telemt_user_octets_to_client{user="hello"} 360731329220 (335.96 GB)
telemt_user_unique_ips_current{user="hello"} 134
telemt_user_unique_ips_recent_window{user="hello"} 54
```