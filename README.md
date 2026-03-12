# Server Metrics 2026-03-12 09:39:02 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 13222.0 (3h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 422681
telemt_connections_bad_total 1446
telemt_handshake_timeouts_total 2567
telemt_upstream_connect_attempt_total 2568
telemt_upstream_connect_success_total 2553
telemt_upstream_connect_fail_total 15
telemt_upstream_connect_attempts_per_request{bucket="1"} 2568
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1389
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1161
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 15
telemt_me_keepalive_timeout_total 273
telemt_me_reconnect_attempts_total 1874
telemt_me_reconnect_success_total 1862
telemt_me_reader_eof_total 1928
telemt_me_idle_close_by_peer_total 1928
telemt_me_route_drop_no_conn_total 144324
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 408936
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1919
telemt_desync_full_logged_total 479
telemt_desync_suppressed_total 1440
telemt_desync_frames_bucket_total{bucket="1_2"} 492
telemt_desync_frames_bucket_total{bucket="3_10"} 698
telemt_desync_frames_bucket_total{bucket="gt_10"} 729
telemt_pool_swap_total 10
telemt_me_writer_removed_unexpected_total 1878
telemt_me_writer_restored_same_endpoint_total 1849
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 16
telemt_user_connections_total{user="hello"} 408818
telemt_user_connections_current{user="hello"} 1264
telemt_user_octets_from_client{user="hello"} 6088673068 (5.67 GB)
telemt_user_octets_to_client{user="hello"} 110046676884 (102.49 GB)
telemt_user_unique_ips_current{user="hello"} 355
telemt_user_unique_ips_recent_window{user="hello"} 200
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 42842.5 (11h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 258473
telemt_connections_bad_total 2975
telemt_handshake_timeouts_total 8084
telemt_upstream_connect_attempt_total 10856
telemt_upstream_connect_success_total 10850
telemt_upstream_connect_fail_total 6
telemt_upstream_connect_attempts_per_request{bucket="1"} 10856
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5326
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5509
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 15
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 6
telemt_me_keepalive_timeout_total 657
telemt_me_reconnect_attempts_total 8571
telemt_me_reconnect_success_total 8528
telemt_me_reader_eof_total 9064
telemt_me_idle_close_by_peer_total 9064
telemt_me_route_drop_no_conn_total 74492
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 229429
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 481
telemt_desync_full_logged_total 197
telemt_desync_suppressed_total 284
telemt_desync_frames_bucket_total{bucket="1_2"} 134
telemt_desync_frames_bucket_total{bucket="3_10"} 177
telemt_desync_frames_bucket_total{bucket="gt_10"} 170
telemt_pool_swap_total 45
telemt_me_writer_removed_unexpected_total 8595
telemt_me_writer_restored_same_endpoint_total 8519
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 67
telemt_user_connections_total{user="hello"} 229824
telemt_user_connections_current{user="hello"} 641
telemt_user_octets_from_client{user="hello"} 3279173059 (3.05 GB)
telemt_user_octets_to_client{user="hello"} 87985433770 (81.94 GB)
telemt_user_msgs_from_client{user="hello"} 353
telemt_user_msgs_to_client{user="hello"} 423
telemt_user_unique_ips_current{user="hello"} 155
telemt_user_unique_ips_recent_window{user="hello"} 88
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 42842.4 (11h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 686765
telemt_connections_bad_total 3060
telemt_handshake_timeouts_total 50678
telemt_upstream_connect_attempt_total 10900
telemt_upstream_connect_success_total 10895
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 10900
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6061
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4782
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 48
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 544
telemt_me_reconnect_attempts_total 8472
telemt_me_reconnect_success_total 8400
telemt_me_reader_eof_total 8823
telemt_me_idle_close_by_peer_total 8823
telemt_me_route_drop_no_conn_total 146625
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 421091
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1930
telemt_desync_full_logged_total 581
telemt_desync_suppressed_total 1349
telemt_desync_frames_bucket_total{bucket="1_2"} 249
telemt_desync_frames_bucket_total{bucket="3_10"} 667
telemt_desync_frames_bucket_total{bucket="gt_10"} 1014
telemt_pool_swap_total 43
telemt_me_writer_removed_unexpected_total 8404
telemt_me_refill_failed_total 1
telemt_me_writer_restored_same_endpoint_total 8359
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 4
telemt_user_connections_total{user="hello"} 421353
telemt_user_connections_current{user="hello"} 867
telemt_user_octets_from_client{user="hello"} 5260634144 (4.90 GB)
telemt_user_octets_to_client{user="hello"} 141012743085 (131.33 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 248
telemt_user_unique_ips_recent_window{user="hello"} 135
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 42842.9 (11h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 340830
telemt_connections_bad_total 1829
telemt_handshake_timeouts_total 24552
telemt_upstream_connect_attempt_total 11730
telemt_upstream_connect_success_total 11683
telemt_upstream_connect_fail_total 47
telemt_upstream_connect_attempts_per_request{bucket="1"} 11730
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6661
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5013
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 47
telemt_me_keepalive_timeout_total 813
telemt_me_reconnect_attempts_total 9573
telemt_me_reconnect_success_total 9537
telemt_me_reader_eof_total 10108
telemt_me_idle_close_by_peer_total 10108
telemt_me_route_drop_no_conn_total 115760
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 286735
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 617
telemt_desync_full_logged_total 217
telemt_desync_suppressed_total 400
telemt_desync_frames_bucket_total{bucket="1_2"} 191
telemt_desync_frames_bucket_total{bucket="3_10"} 253
telemt_desync_frames_bucket_total{bucket="gt_10"} 173
telemt_pool_swap_total 41
telemt_me_writer_removed_unexpected_total 9598
telemt_me_writer_restored_same_endpoint_total 9516
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 108
telemt_me_writer_removed_unexpected_minus_restored_total 61
telemt_user_connections_total{user="hello"} 286558
telemt_user_connections_current{user="hello"} 526
telemt_user_octets_from_client{user="hello"} 3531992968 (3.29 GB)
telemt_user_octets_to_client{user="hello"} 112193193868 (104.49 GB)
telemt_user_unique_ips_current{user="hello"} 164
telemt_user_unique_ips_recent_window{user="hello"} 93
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 42842.6 (11h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 382752
telemt_connections_bad_total 400
telemt_handshake_timeouts_total 2830
telemt_upstream_connect_attempt_total 13880
telemt_upstream_connect_success_total 13713
telemt_upstream_connect_fail_total 167
telemt_upstream_connect_attempts_per_request{bucket="1"} 13880
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7067
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6566
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 75
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 167
telemt_me_keepalive_timeout_total 616
telemt_me_reconnect_attempts_total 13081
telemt_me_reconnect_success_total 11563
telemt_me_reader_eof_total 12045
telemt_me_idle_close_by_peer_total 12045
telemt_me_seq_mismatch_total 17
telemt_me_route_drop_no_conn_total 123405
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 361634
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 1537
telemt_desync_full_logged_total 498
telemt_desync_suppressed_total 1039
telemt_desync_frames_bucket_total{bucket="1_2"} 444
telemt_desync_frames_bucket_total{bucket="3_10"} 543
telemt_desync_frames_bucket_total{bucket="gt_10"} 550
telemt_pool_swap_total 25
telemt_me_writer_removed_unexpected_total 11714
telemt_me_refill_failed_total 46
telemt_me_writer_restored_same_endpoint_total 11541
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 151
telemt_user_connections_total{user="hello"} 361567
telemt_user_connections_current{user="hello"} 666
telemt_user_octets_from_client{user="hello"} 3950866184 (3.68 GB)
telemt_user_octets_to_client{user="hello"} 86806383412 (80.84 GB)
telemt_user_unique_ips_current{user="hello"} 183
telemt_user_unique_ips_recent_window{user="hello"} 100
```