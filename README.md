# Server Metrics 2026-03-11 01:32:00 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 39894.9 (11h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 814849
telemt_connections_bad_total 9529
telemt_handshake_timeouts_total 10192
telemt_upstream_connect_attempt_total 8699
telemt_upstream_connect_success_total 8690
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 8699
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4350
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4281
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 58
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 485
telemt_me_reconnect_attempts_total 18287
telemt_me_reconnect_success_total 6620
telemt_me_reader_eof_total 7249
telemt_me_idle_close_by_peer_total 7249
telemt_me_route_drop_no_conn_total 332480
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 771115
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3608
telemt_desync_full_logged_total 1015
telemt_desync_suppressed_total 2593
telemt_desync_frames_bucket_total{bucket="1_2"} 1054
telemt_desync_frames_bucket_total{bucket="3_10"} 1343
telemt_desync_frames_bucket_total{bucket="gt_10"} 1211
telemt_pool_swap_total 24
telemt_me_writer_removed_unexpected_total 7039
telemt_me_refill_failed_total 363
telemt_me_writer_restored_same_endpoint_total 6614
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 419
telemt_user_connections_total{user="hello"} 770875
telemt_user_connections_current{user="hello"} 431
telemt_user_octets_from_client{user="hello"} 10596292956 (9.87 GB)
telemt_user_octets_to_client{user="hello"} 234264485148 (218.18 GB)
telemt_user_unique_ips_current{user="hello"} 166
telemt_user_unique_ips_recent_window{user="hello"} 55
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 39951.8 (11h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 350347
telemt_connections_bad_total 2407
telemt_handshake_timeouts_total 17889
telemt_upstream_connect_attempt_total 15936
telemt_upstream_connect_success_total 13051
telemt_upstream_connect_fail_total 2885
telemt_upstream_connect_attempts_per_request{bucket="1"} 15936
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5690
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5120
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 209
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2032
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2885
telemt_me_keepalive_timeout_total 1717
telemt_me_reconnect_attempts_total 8881
telemt_me_reconnect_success_total 8065
telemt_me_reader_eof_total 8521
telemt_me_idle_close_by_peer_total 8519
telemt_me_route_drop_no_conn_total 174432
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 299326
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1786
telemt_desync_full_logged_total 512
telemt_desync_suppressed_total 1274
telemt_desync_frames_bucket_total{bucket="1_2"} 546
telemt_desync_frames_bucket_total{bucket="3_10"} 637
telemt_desync_frames_bucket_total{bucket="gt_10"} 603
telemt_pool_swap_total 32
telemt_me_writer_removed_unexpected_total 8174
telemt_me_refill_failed_total 22
telemt_me_writer_restored_same_endpoint_total 8044
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 86
telemt_me_writer_removed_unexpected_minus_restored_total 109
telemt_user_connections_total{user="hello"} 301595
telemt_user_connections_current{user="hello"} 169
telemt_user_octets_from_client{user="hello"} 2865190738 (2.67 GB)
telemt_user_octets_to_client{user="hello"} 71442131472 (66.54 GB)
telemt_user_msgs_from_client{user="hello"} 7933
telemt_user_msgs_to_client{user="hello"} 11226
telemt_user_unique_ips_current{user="hello"} 65
telemt_user_unique_ips_recent_window{user="hello"} 21
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 39951.5 (11h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 582585
telemt_connections_bad_total 4181
telemt_handshake_timeouts_total 34271
telemt_upstream_connect_attempt_total 10883
telemt_upstream_connect_success_total 10735
telemt_upstream_connect_fail_total 148
telemt_upstream_connect_attempts_per_request{bucket="1"} 10883
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6012
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4656
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 67
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 148
telemt_me_keepalive_timeout_total 518
telemt_me_reconnect_attempts_total 18685
telemt_me_reconnect_success_total 7622
telemt_me_reader_eof_total 8304
telemt_me_idle_close_by_peer_total 8304
telemt_me_route_drop_no_conn_total 198994
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 515474
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1522
telemt_desync_full_logged_total 435
telemt_desync_suppressed_total 1087
telemt_desync_frames_bucket_total{bucket="1_2"} 344
telemt_desync_frames_bucket_total{bucket="3_10"} 523
telemt_desync_frames_bucket_total{bucket="gt_10"} 655
telemt_pool_swap_total 25
telemt_me_writer_removed_unexpected_total 8071
telemt_me_refill_failed_total 343
telemt_me_writer_restored_same_endpoint_total 7611
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 449
telemt_user_connections_total{user="hello"} 516388
telemt_user_connections_current{user="hello"} 205
telemt_user_octets_from_client{user="hello"} 6923458633 (6.45 GB)
telemt_user_octets_to_client{user="hello"} 157141546633 (146.35 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 89
telemt_user_unique_ips_recent_window{user="hello"} 32
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 39952.0 (11h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 431834
telemt_connections_bad_total 37948
telemt_handshake_timeouts_total 41078
telemt_upstream_connect_attempt_total 11534
telemt_upstream_connect_success_total 11534
telemt_upstream_connect_attempts_per_request{bucket="1"} 11534
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6499
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5033
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_timeout_total 422
telemt_me_reconnect_attempts_total 10531
telemt_me_reconnect_success_total 9496
telemt_me_reader_eof_total 10057
telemt_me_idle_close_by_peer_total 10057
telemt_me_seq_mismatch_total 7
telemt_me_route_drop_no_conn_total 130860
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 339321
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 732
telemt_desync_full_logged_total 292
telemt_desync_suppressed_total 440
telemt_desync_frames_bucket_total{bucket="1_2"} 279
telemt_desync_frames_bucket_total{bucket="3_10"} 253
telemt_desync_frames_bucket_total{bucket="gt_10"} 200
telemt_pool_swap_total 33
telemt_me_writer_removed_unexpected_total 9616
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 9478
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 120
telemt_user_connections_total{user="hello"} 338995
telemt_user_connections_current{user="hello"} 143
telemt_user_octets_from_client{user="hello"} 4245951084 (3.95 GB)
telemt_user_octets_to_client{user="hello"} 92175534300 (85.85 GB)
telemt_user_unique_ips_current{user="hello"} 53
telemt_user_unique_ips_recent_window{user="hello"} 25
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 39951.7 (11h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 455724
telemt_connections_bad_total 5185
telemt_handshake_timeouts_total 2946
telemt_upstream_connect_attempt_total 11958
telemt_upstream_connect_success_total 11908
telemt_upstream_connect_fail_total 50
telemt_upstream_connect_attempts_per_request{bucket="1"} 11958
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6156
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5636
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 114
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 50
telemt_me_keepalive_timeout_total 513
telemt_me_reconnect_attempts_total 13603
telemt_me_reconnect_success_total 9834
telemt_me_reader_eof_total 10354
telemt_me_idle_close_by_peer_total 10354
telemt_me_route_drop_no_conn_total 150195
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 417711
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 2286
telemt_desync_full_logged_total 886
telemt_desync_suppressed_total 1400
telemt_desync_frames_bucket_total{bucket="1_2"} 845
telemt_desync_frames_bucket_total{bucket="3_10"} 973
telemt_desync_frames_bucket_total{bucket="gt_10"} 468
telemt_pool_swap_total 21
telemt_me_writer_removed_unexpected_total 10079
telemt_me_refill_failed_total 116
telemt_me_writer_restored_same_endpoint_total 9834
telemt_me_async_recovery_trigger_total 48
telemt_me_writer_removed_unexpected_minus_restored_total 245
telemt_user_connections_total{user="hello"} 417410
telemt_user_connections_current{user="hello"} 237
telemt_user_octets_from_client{user="hello"} 8402828152 (7.83 GB)
telemt_user_octets_to_client{user="hello"} 148119828588 (137.95 GB)
telemt_user_unique_ips_current{user="hello"} 77
telemt_user_unique_ips_recent_window{user="hello"} 33
```