# Server Metrics 2026-03-12 22:24:44 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 59163.7 (16h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1915207
telemt_connections_bad_total 26060
telemt_handshake_timeouts_total 20995
telemt_upstream_connect_attempt_total 11653
telemt_upstream_connect_success_total 11586
telemt_upstream_connect_fail_total 67
telemt_upstream_connect_attempts_per_request{bucket="1"} 11653
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6031
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5518
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 37
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 67
telemt_me_keepalive_timeout_total 600
telemt_me_reconnect_attempts_total 17468
telemt_me_reconnect_success_total 8612
telemt_me_reader_eof_total 9305
telemt_me_idle_close_by_peer_total 9304
telemt_me_route_drop_no_conn_total 748201
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1782161
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8483
telemt_desync_full_logged_total 2209
telemt_desync_suppressed_total 6274
telemt_desync_frames_bucket_total{bucket="1_2"} 2235
telemt_desync_frames_bucket_total{bucket="3_10"} 3055
telemt_desync_frames_bucket_total{bucket="gt_10"} 3193
telemt_pool_swap_total 41
telemt_me_writer_removed_unexpected_total 9011
telemt_me_refill_failed_total 275
telemt_me_writer_restored_same_endpoint_total 8599
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 399
telemt_user_connections_total{user="hello"} 1781634
telemt_user_connections_current{user="hello"} 603
telemt_user_octets_from_client{user="hello"} 26934319204 (25.08 GB)
telemt_user_octets_to_client{user="hello"} 632578550228 (589.13 GB)
telemt_user_unique_ips_current{user="hello"} 224
telemt_user_unique_ips_recent_window{user="hello"} 71
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 88784.2 (24h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 794312
telemt_connections_bad_total 11703
telemt_handshake_timeouts_total 31283
telemt_upstream_connect_attempt_total 22442
telemt_upstream_connect_success_total 22413
telemt_upstream_connect_fail_total 29
telemt_upstream_connect_attempts_per_request{bucket="1"} 22442
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11796
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10528
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 89
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 29
telemt_me_keepalive_timeout_total 3411
telemt_me_reconnect_attempts_total 16427
telemt_me_reconnect_success_total 16332
telemt_me_reader_eof_total 17378
telemt_me_idle_close_by_peer_total 17378
telemt_me_route_drop_no_conn_total 257034
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 717445
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3001
telemt_desync_full_logged_total 933
telemt_desync_suppressed_total 2068
telemt_desync_frames_bucket_total{bucket="1_2"} 1188
telemt_desync_frames_bucket_total{bucket="3_10"} 986
telemt_desync_frames_bucket_total{bucket="gt_10"} 827
telemt_pool_swap_total 89
telemt_me_writer_removed_unexpected_total 16497
telemt_me_writer_restored_same_endpoint_total 16323
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 165
telemt_user_connections_total{user="hello"} 719325
telemt_user_connections_current{user="hello"} 204
telemt_user_octets_from_client{user="hello"} 12065134916 (11.24 GB)
telemt_user_octets_to_client{user="hello"} 279009623863 (259.85 GB)
telemt_user_msgs_from_client{user="hello"} 6476
telemt_user_msgs_to_client{user="hello"} 18854
telemt_user_unique_ips_current{user="hello"} 78
telemt_user_unique_ips_recent_window{user="hello"} 37
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 88784.1 (24h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1651093
telemt_connections_bad_total 7846
telemt_handshake_timeouts_total 113260
telemt_upstream_connect_attempt_total 20704
telemt_upstream_connect_success_total 20698
telemt_upstream_connect_fail_total 6
telemt_upstream_connect_attempts_per_request{bucket="1"} 20704
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11083
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9538
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 72
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 6
telemt_me_keepalive_timeout_total 1219
telemt_me_reconnect_attempts_total 17158
telemt_me_reconnect_success_total 15909
telemt_me_reader_eof_total 16812
telemt_me_idle_close_by_peer_total 16811
telemt_me_route_drop_no_conn_total 543411
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1284814
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4968
telemt_desync_full_logged_total 1524
telemt_desync_suppressed_total 3444
telemt_desync_frames_bucket_total{bucket="1_2"} 790
telemt_desync_frames_bucket_total{bucket="3_10"} 1796
telemt_desync_frames_bucket_total{bucket="gt_10"} 2382
telemt_pool_swap_total 81
telemt_me_writer_removed_unexpected_total 16059
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 15868
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 150
telemt_user_connections_total{user="hello"} 1284420
telemt_user_connections_current{user="hello"} 363
telemt_user_octets_from_client{user="hello"} 19706353160 (18.35 GB)
telemt_user_octets_to_client{user="hello"} 474278471541 (441.71 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 127
telemt_user_unique_ips_recent_window{user="hello"} 58
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 88784.4 (24h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1017410
telemt_connections_bad_total 12998
telemt_handshake_timeouts_total 71380
telemt_upstream_connect_attempt_total 22703
telemt_upstream_connect_success_total 22610
telemt_upstream_connect_fail_total 93
telemt_upstream_connect_attempts_per_request{bucket="1"} 22703
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12714
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9882
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 14
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 93
telemt_me_keepalive_timeout_total 1688
telemt_me_reconnect_attempts_total 25913
telemt_me_reconnect_success_total 18183
telemt_me_reader_eof_total 19423
telemt_me_idle_close_by_peer_total 19423
telemt_me_route_drop_no_conn_total 364032
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 886339
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1852
telemt_desync_full_logged_total 613
telemt_desync_suppressed_total 1239
telemt_desync_frames_bucket_total{bucket="1_2"} 514
telemt_desync_frames_bucket_total{bucket="3_10"} 722
telemt_desync_frames_bucket_total{bucket="gt_10"} 616
telemt_pool_swap_total 75
telemt_me_writer_removed_unexpected_total 18569
telemt_me_refill_failed_total 239
telemt_me_writer_restored_same_endpoint_total 18162
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 108
telemt_me_writer_removed_unexpected_minus_restored_total 386
telemt_user_connections_total{user="hello"} 885685
telemt_user_connections_current{user="hello"} 252
telemt_user_octets_from_client{user="hello"} 14190907724 (13.22 GB)
telemt_user_octets_to_client{user="hello"} 353791749360 (329.49 GB)
telemt_user_unique_ips_current{user="hello"} 91
telemt_user_unique_ips_recent_window{user="hello"} 43
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 88784.2 (24h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1138178
telemt_connections_bad_total 12534
telemt_handshake_timeouts_total 9198
telemt_upstream_connect_attempt_total 27220
telemt_upstream_connect_success_total 26882
telemt_upstream_connect_fail_total 338
telemt_upstream_connect_attempts_per_request{bucket="1"} 27220
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13751
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12980
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 11
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 140
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 338
telemt_me_keepalive_timeout_total 1443
telemt_me_reconnect_attempts_total 33481
telemt_me_reconnect_success_total 22442
telemt_me_reader_eof_total 23598
telemt_me_idle_close_by_peer_total 23598
telemt_me_seq_mismatch_total 33
telemt_me_route_drop_no_conn_total 425994
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1047821
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 37
telemt_me_hardswap_pending_ttl_expired_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 3932
telemt_desync_full_logged_total 1367
telemt_desync_suppressed_total 2565
telemt_desync_frames_bucket_total{bucket="1_2"} 1153
telemt_desync_frames_bucket_total{bucket="3_10"} 1297
telemt_desync_frames_bucket_total{bucket="gt_10"} 1482
telemt_pool_swap_total 44
telemt_me_writer_removed_unexpected_total 23047
telemt_me_refill_failed_total 342
telemt_me_writer_restored_same_endpoint_total 22398
telemt_me_writer_restored_fallback_total 44
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 605
telemt_user_connections_total{user="hello"} 1047680
telemt_user_connections_current{user="hello"} 349
telemt_user_octets_from_client{user="hello"} 12858147472 (11.98 GB)
telemt_user_octets_to_client{user="hello"} 371910217464 (346.37 GB)
telemt_user_unique_ips_current{user="hello"} 107
telemt_user_unique_ips_recent_window{user="hello"} 43
```