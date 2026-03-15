# Server Metrics 2026-03-15 16:38:11 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.18

telemt_uptime_seconds 66220.4 (18h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2239212
telemt_connections_bad_total 132363
telemt_handshake_timeouts_total 27752
telemt_upstream_connect_attempt_total 13073
telemt_upstream_connect_success_total 13017
telemt_upstream_connect_fail_total 56
telemt_upstream_connect_attempts_per_request{bucket="1"} 13073
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6763
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6197
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 57
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 56
telemt_me_keepalive_timeout_total 47
telemt_me_reconnect_attempts_total 14591
telemt_me_reconnect_success_total 9695
telemt_me_reader_eof_total 10363
telemt_me_idle_close_by_peer_total 10363
telemt_me_route_drop_no_conn_total 772576
telemt_me_route_drop_channel_closed_total 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1882565
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7345
telemt_desync_full_logged_total 2016
telemt_desync_suppressed_total 5329
telemt_desync_frames_bucket_total{bucket="1_2"} 1777
telemt_desync_frames_bucket_total{bucket="3_10"} 2818
telemt_desync_frames_bucket_total{bucket="gt_10"} 2750
telemt_pool_swap_total 49
telemt_me_writer_removed_unexpected_total 10009
telemt_me_refill_failed_total 151
telemt_me_writer_restored_same_endpoint_total 9684
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 296
telemt_me_writer_removed_unexpected_minus_restored_total 314
telemt_user_connections_total{user="hello"} 1882060
telemt_user_connections_current{user="hello"} 2459
telemt_user_octets_from_client{user="hello"} 27620087712 (25.72 GB)
telemt_user_octets_to_client{user="hello"} 717473920368 (668.20 GB)
telemt_user_unique_ips_current{user="hello"} 690
telemt_user_unique_ips_recent_window{user="hello"} 328
```

## server2

```
telemt 3.3.18

telemt_uptime_seconds 66221.3 (18h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 875701
telemt_connections_bad_total 47337
telemt_handshake_timeouts_total 60765
telemt_upstream_connect_attempt_total 16736
telemt_upstream_connect_success_total 16655
telemt_upstream_connect_fail_total 81
telemt_upstream_connect_attempts_per_request{bucket="1"} 16736
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8881
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7616
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 38
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 120
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 81
telemt_me_keepalive_timeout_total 59
telemt_me_reconnect_attempts_total 14176
telemt_me_reconnect_success_total 12983
telemt_me_reader_eof_total 13729
telemt_me_idle_close_by_peer_total 13729
telemt_me_route_drop_no_conn_total 224416
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 671333
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 16
telemt_me_endpoint_quarantine_total 17
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2110
telemt_desync_full_logged_total 714
telemt_desync_suppressed_total 1396
telemt_desync_frames_bucket_total{bucket="1_2"} 769
telemt_desync_frames_bucket_total{bucket="3_10"} 778
telemt_desync_frames_bucket_total{bucket="gt_10"} 563
telemt_pool_swap_total 53
telemt_me_writer_removed_unexpected_total 13186
telemt_me_refill_failed_total 34
telemt_me_writer_restored_same_endpoint_total 12971
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 61
telemt_me_writer_removed_unexpected_minus_restored_total 203
telemt_user_connections_total{user="hello"} 671576
telemt_user_connections_current{user="hello"} 668
telemt_user_octets_from_client{user="hello"} 9345736571 (8.70 GB)
telemt_user_octets_to_client{user="hello"} 254386756876 (236.92 GB)
telemt_user_msgs_from_client{user="hello"} 620
telemt_user_msgs_to_client{user="hello"} 1332
telemt_user_unique_ips_current{user="hello"} 243
telemt_user_unique_ips_recent_window{user="hello"} 104
```

## server3

```
telemt 3.3.18

telemt_uptime_seconds 66221.2 (18h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1979748
telemt_connections_bad_total 48379
telemt_handshake_timeouts_total 195752
telemt_upstream_connect_attempt_total 14466
telemt_upstream_connect_success_total 14397
telemt_upstream_connect_fail_total 69
telemt_upstream_connect_attempts_per_request{bucket="1"} 14466
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7433
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6895
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 69
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 69
telemt_me_keepalive_timeout_total 45
telemt_me_reconnect_attempts_total 12311
telemt_me_reconnect_success_total 11043
telemt_me_reader_eof_total 11686
telemt_me_idle_close_by_peer_total 11686
telemt_me_route_drop_no_conn_total 510920
telemt_me_route_drop_channel_closed_total 18
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1198008
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3017
telemt_desync_full_logged_total 1093
telemt_desync_suppressed_total 1924
telemt_desync_frames_bucket_total{bucket="1_2"} 694
telemt_desync_frames_bucket_total{bucket="3_10"} 1157
telemt_desync_frames_bucket_total{bucket="gt_10"} 1166
telemt_pool_swap_total 56
telemt_me_writer_removed_unexpected_total 11237
telemt_me_refill_failed_total 37
telemt_me_writer_restored_same_endpoint_total 11024
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 242
telemt_me_writer_removed_unexpected_minus_restored_total 194
telemt_user_connections_total{user="hello"} 1193972
telemt_user_connections_current{user="hello"} 1407
telemt_user_octets_from_client{user="hello"} 17355046144 (16.16 GB)
telemt_user_octets_to_client{user="hello"} 430529037060 (400.96 GB)
telemt_user_unique_ips_current{user="hello"} 425
telemt_user_unique_ips_recent_window{user="hello"} 209
```

## server4

```
telemt 3.3.18

telemt_uptime_seconds 66221.2 (18h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 930864
telemt_connections_bad_total 79480
telemt_handshake_timeouts_total 45827
telemt_upstream_connect_attempt_total 169016
telemt_upstream_connect_success_total 168487
telemt_upstream_connect_fail_total 529
telemt_upstream_connect_attempts_per_request{bucket="1"} 169016
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 155497
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12956
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 34
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 529
telemt_me_keepalive_timeout_total 39
telemt_me_reconnect_attempts_total 55928
telemt_me_reconnect_success_total 13098
telemt_me_reader_eof_total 14793
telemt_me_idle_close_by_peer_total 14793
telemt_me_seq_mismatch_total 26
telemt_me_route_drop_no_conn_total 212990
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 567332
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 43
telemt_me_hardswap_pending_ttl_expired_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1584
telemt_desync_full_logged_total 414
telemt_desync_suppressed_total 1170
telemt_desync_frames_bucket_total{bucket="1_2"} 404
telemt_desync_frames_bucket_total{bucket="3_10"} 628
telemt_desync_frames_bucket_total{bucket="gt_10"} 552
telemt_pool_swap_total 19
telemt_me_writer_removed_unexpected_total 14570
telemt_me_refill_failed_total 1340
telemt_me_writer_restored_same_endpoint_total 13062
telemt_me_writer_restored_fallback_total 36
telemt_me_async_recovery_trigger_total 96
telemt_me_writer_removed_unexpected_minus_restored_total 1472
telemt_user_connections_total{user="hello"} 718956
telemt_user_connections_current{user="hello"} 866
telemt_user_octets_from_client{user="hello"} 13724406250 (12.78 GB)
telemt_user_octets_to_client{user="hello"} 256895832785 (239.25 GB)
telemt_user_msgs_from_client{user="hello"} 3034166
telemt_user_msgs_to_client{user="hello"} 10923814
telemt_user_unique_ips_current{user="hello"} 249
telemt_user_unique_ips_recent_window{user="hello"} 123
```

## server5

```
telemt 3.3.18

telemt_uptime_seconds 66222.5 (18h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 944711
telemt_connections_bad_total 12051
telemt_handshake_timeouts_total 20662
telemt_upstream_connect_attempt_total 14795
telemt_upstream_connect_success_total 14715
telemt_upstream_connect_fail_total 80
telemt_upstream_connect_attempts_per_request{bucket="1"} 14795
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6795
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7906
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 14
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 80
telemt_me_keepalive_timeout_total 86
telemt_me_reconnect_attempts_total 15076
telemt_me_reconnect_success_total 11387
telemt_me_reader_eof_total 12143
telemt_me_idle_close_by_peer_total 12143
telemt_me_route_drop_no_conn_total 235558
telemt_me_route_drop_channel_closed_total 28
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 780543
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2656
telemt_desync_full_logged_total 900
telemt_desync_suppressed_total 1756
telemt_desync_frames_bucket_total{bucket="1_2"} 818
telemt_desync_frames_bucket_total{bucket="3_10"} 1001
telemt_desync_frames_bucket_total{bucket="gt_10"} 837
telemt_pool_swap_total 54
telemt_me_writer_removed_unexpected_total 11637
telemt_me_refill_failed_total 113
telemt_me_writer_restored_same_endpoint_total 11379
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 54
telemt_me_writer_removed_unexpected_minus_restored_total 250
telemt_user_connections_total{user="hello"} 780586
telemt_user_connections_current{user="hello"} 875
telemt_user_octets_from_client{user="hello"} 9590830592 (8.93 GB)
telemt_user_octets_to_client{user="hello"} 278414466664 (259.29 GB)
telemt_user_unique_ips_current{user="hello"} 251
telemt_user_unique_ips_recent_window{user="hello"} 135
```