# Server Metrics 2026-03-12 21:18:19 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 55178.7 (15h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1856695
telemt_connections_bad_total 23747
telemt_handshake_timeouts_total 20381
telemt_upstream_connect_attempt_total 10757
telemt_upstream_connect_success_total 10695
telemt_upstream_connect_fail_total 62
telemt_upstream_connect_attempts_per_request{bucket="1"} 10757
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5565
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5094
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 36
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 62
telemt_me_keepalive_timeout_total 587
telemt_me_reconnect_attempts_total 16750
telemt_me_reconnect_success_total 7898
telemt_me_reader_eof_total 8546
telemt_me_idle_close_by_peer_total 8545
telemt_me_route_drop_no_conn_total 728420
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1730220
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8381
telemt_desync_full_logged_total 2168
telemt_desync_suppressed_total 6213
telemt_desync_frames_bucket_total{bucket="1_2"} 2199
telemt_desync_frames_bucket_total{bucket="3_10"} 3023
telemt_desync_frames_bucket_total{bucket="gt_10"} 3159
telemt_pool_swap_total 38
telemt_me_writer_removed_unexpected_total 8289
telemt_me_refill_failed_total 275
telemt_me_writer_restored_same_endpoint_total 7885
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 391
telemt_user_connections_total{user="hello"} 1729704
telemt_user_connections_current{user="hello"} 999
telemt_user_octets_from_client{user="hello"} 26475366200 (24.66 GB)
telemt_user_octets_to_client{user="hello"} 608533489236 (566.74 GB)
telemt_user_unique_ips_current{user="hello"} 298
telemt_user_unique_ips_recent_window{user="hello"} 103
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 84799.1 (23h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 775607
telemt_connections_bad_total 11661
telemt_handshake_timeouts_total 30744
telemt_upstream_connect_attempt_total 21433
telemt_upstream_connect_success_total 21404
telemt_upstream_connect_fail_total 29
telemt_upstream_connect_attempts_per_request{bucket="1"} 21433
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11308
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10008
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 88
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 29
telemt_me_keepalive_timeout_total 3392
telemt_me_reconnect_attempts_total 15592
telemt_me_reconnect_success_total 15500
telemt_me_reader_eof_total 16490
telemt_me_idle_close_by_peer_total 16490
telemt_me_route_drop_no_conn_total 251161
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 699519
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2971
telemt_desync_full_logged_total 917
telemt_desync_suppressed_total 2054
telemt_desync_frames_bucket_total{bucket="1_2"} 1166
telemt_desync_frames_bucket_total{bucket="3_10"} 978
telemt_desync_frames_bucket_total{bucket="gt_10"} 827
telemt_pool_swap_total 85
telemt_me_writer_removed_unexpected_total 15658
telemt_me_writer_restored_same_endpoint_total 15491
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 158
telemt_user_connections_total{user="hello"} 701397
telemt_user_connections_current{user="hello"} 276
telemt_user_octets_from_client{user="hello"} 11914993328 (11.10 GB)
telemt_user_octets_to_client{user="hello"} 269749042247 (251.22 GB)
telemt_user_msgs_from_client{user="hello"} 6476
telemt_user_msgs_to_client{user="hello"} 18854
telemt_user_unique_ips_current{user="hello"} 93
telemt_user_unique_ips_recent_window{user="hello"} 35
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 84799.0 (23h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1604714
telemt_connections_bad_total 7578
telemt_handshake_timeouts_total 111009
telemt_upstream_connect_attempt_total 19883
telemt_upstream_connect_success_total 19877
telemt_upstream_connect_fail_total 6
telemt_upstream_connect_attempts_per_request{bucket="1"} 19883
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10673
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9130
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 69
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 6
telemt_me_keepalive_timeout_total 1211
telemt_me_reconnect_attempts_total 16509
telemt_me_reconnect_success_total 15262
telemt_me_reader_eof_total 16119
telemt_me_idle_close_by_peer_total 16118
telemt_me_route_drop_no_conn_total 530138
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1241760
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4880
telemt_desync_full_logged_total 1500
telemt_desync_suppressed_total 3380
telemt_desync_frames_bucket_total{bucket="1_2"} 775
telemt_desync_frames_bucket_total{bucket="3_10"} 1762
telemt_desync_frames_bucket_total{bucket="gt_10"} 2343
telemt_pool_swap_total 77
telemt_me_writer_removed_unexpected_total 15405
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 15221
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 143
telemt_user_connections_total{user="hello"} 1241367
telemt_user_connections_current{user="hello"} 474
telemt_user_octets_from_client{user="hello"} 19416060912 (18.08 GB)
telemt_user_octets_to_client{user="hello"} 460724668985 (429.08 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 173
telemt_user_unique_ips_recent_window{user="hello"} 68
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 84799.4 (23h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 988154
telemt_connections_bad_total 12974
telemt_handshake_timeouts_total 71015
telemt_upstream_connect_attempt_total 21627
telemt_upstream_connect_success_total 21539
telemt_upstream_connect_fail_total 88
telemt_upstream_connect_attempts_per_request{bucket="1"} 21627
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12099
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9426
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 14
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 88
telemt_me_keepalive_timeout_total 1677
telemt_me_reconnect_attempts_total 25015
telemt_me_reconnect_success_total 17287
telemt_me_reader_eof_total 18468
telemt_me_idle_close_by_peer_total 18468
telemt_me_route_drop_no_conn_total 353260
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 859570
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
telemt_me_writer_removed_unexpected_total 17666
telemt_me_refill_failed_total 239
telemt_me_writer_restored_same_endpoint_total 17266
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 108
telemt_me_writer_removed_unexpected_minus_restored_total 379
telemt_user_connections_total{user="hello"} 858920
telemt_user_connections_current{user="hello"} 312
telemt_user_octets_from_client{user="hello"} 13448300836 (12.52 GB)
telemt_user_octets_to_client{user="hello"} 347528598916 (323.66 GB)
telemt_user_unique_ips_current{user="hello"} 119
telemt_user_unique_ips_recent_window{user="hello"} 63
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 84799.3 (23h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1107658
telemt_connections_bad_total 12513
telemt_handshake_timeouts_total 9028
telemt_upstream_connect_attempt_total 26248
telemt_upstream_connect_success_total 25925
telemt_upstream_connect_fail_total 323
telemt_upstream_connect_attempts_per_request{bucket="1"} 26248
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13272
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12509
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 10
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 134
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 323
telemt_me_keepalive_timeout_total 1429
telemt_me_reconnect_attempts_total 32696
telemt_me_reconnect_success_total 21658
telemt_me_reader_eof_total 22767
telemt_me_idle_close_by_peer_total 22767
telemt_me_seq_mismatch_total 33
telemt_me_route_drop_no_conn_total 415184
telemt_me_route_drop_channel_closed_total 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1017976
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 37
telemt_me_hardswap_pending_ttl_expired_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 3869
telemt_desync_full_logged_total 1347
telemt_desync_suppressed_total 2522
telemt_desync_frames_bucket_total{bucket="1_2"} 1137
telemt_desync_frames_bucket_total{bucket="3_10"} 1276
telemt_desync_frames_bucket_total{bucket="gt_10"} 1456
telemt_pool_swap_total 41
telemt_me_writer_removed_unexpected_total 22250
telemt_me_refill_failed_total 342
telemt_me_writer_restored_same_endpoint_total 21614
telemt_me_writer_restored_fallback_total 44
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 592
telemt_user_connections_total{user="hello"} 1017836
telemt_user_connections_current{user="hello"} 490
telemt_user_octets_from_client{user="hello"} 12641805616 (11.77 GB)
telemt_user_octets_to_client{user="hello"} 359579687016 (334.88 GB)
telemt_user_unique_ips_current{user="hello"} 143
telemt_user_unique_ips_recent_window{user="hello"} 55
```