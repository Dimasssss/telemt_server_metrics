# Server Metrics 2026-03-11 13:34:53 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 83267.8 (23h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1967600
telemt_connections_bad_total 27776
telemt_handshake_timeouts_total 50564
telemt_upstream_connect_attempt_total 17311
telemt_upstream_connect_success_total 17302
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 17311
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8759
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8471
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 71
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 918
telemt_me_reconnect_attempts_total 25924
telemt_me_reconnect_success_total 13092
telemt_me_reader_eof_total 14145
telemt_me_idle_close_by_peer_total 14145
telemt_me_route_drop_no_conn_total 723594
telemt_me_route_drop_channel_closed_total 7
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1798277
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 9488
telemt_desync_full_logged_total 2567
telemt_desync_suppressed_total 6921
telemt_desync_frames_bucket_total{bucket="1_2"} 2346
telemt_desync_frames_bucket_total{bucket="3_10"} 3664
telemt_desync_frames_bucket_total{bucket="gt_10"} 3478
telemt_pool_swap_total 64
telemt_me_writer_removed_unexpected_total 13632
telemt_me_refill_failed_total 398
telemt_me_writer_restored_same_endpoint_total 13086
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 540
telemt_user_connections_total{user="hello"} 1796790
telemt_user_connections_current{user="hello"} 1717
telemt_user_octets_from_client{user="hello"} 23987337440 (22.34 GB)
telemt_user_octets_to_client{user="hello"} 513197655884 (477.95 GB)
telemt_user_unique_ips_current{user="hello"} 399
telemt_user_unique_ips_recent_window{user="hello"} 211
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 83324.7 (23h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 745836
telemt_connections_bad_total 13033
telemt_handshake_timeouts_total 51092
telemt_upstream_connect_attempt_total 26755
telemt_upstream_connect_success_total 23808
telemt_upstream_connect_fail_total 2947
telemt_upstream_connect_attempts_per_request{bucket="1"} 26755
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10973
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10587
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 209
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2039
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2947
telemt_me_keepalive_timeout_total 2447
telemt_me_reconnect_attempts_total 17547
telemt_me_reconnect_success_total 16682
telemt_me_reader_eof_total 17649
telemt_me_idle_close_by_peer_total 17646
telemt_me_route_drop_no_conn_total 291603
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 629054
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2741
telemt_desync_full_logged_total 868
telemt_desync_suppressed_total 1873
telemt_desync_frames_bucket_total{bucket="1_2"} 858
telemt_desync_frames_bucket_total{bucket="3_10"} 1000
telemt_desync_frames_bucket_total{bucket="gt_10"} 883
telemt_pool_swap_total 69
telemt_me_writer_removed_unexpected_total 16892
telemt_me_refill_failed_total 22
telemt_me_writer_restored_same_endpoint_total 16659
telemt_me_writer_restored_fallback_total 23
telemt_me_async_recovery_trigger_total 86
telemt_me_writer_removed_unexpected_minus_restored_total 210
telemt_user_connections_total{user="hello"} 631541
telemt_user_connections_current{user="hello"} 548
telemt_user_octets_from_client{user="hello"} 6764388982 (6.30 GB)
telemt_user_octets_to_client{user="hello"} 179590327712 (167.26 GB)
telemt_user_msgs_from_client{user="hello"} 7933
telemt_user_msgs_to_client{user="hello"} 11226
telemt_user_unique_ips_current{user="hello"} 153
telemt_user_unique_ips_recent_window{user="hello"} 88
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 83324.6 (23h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1285299
telemt_connections_bad_total 8303
telemt_handshake_timeouts_total 117735
telemt_upstream_connect_attempt_total 22162
telemt_upstream_connect_success_total 21894
telemt_upstream_connect_fail_total 268
telemt_upstream_connect_attempts_per_request{bucket="1"} 22162
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11852
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9937
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 105
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 268
telemt_me_keepalive_timeout_total 900
telemt_me_reconnect_attempts_total 32728
telemt_me_reconnect_success_total 16623
telemt_me_reader_eof_total 17888
telemt_me_idle_close_by_peer_total 17888
telemt_me_route_drop_no_conn_total 445309
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1110804
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2958
telemt_desync_full_logged_total 878
telemt_desync_suppressed_total 2080
telemt_desync_frames_bucket_total{bucket="1_2"} 715
telemt_desync_frames_bucket_total{bucket="3_10"} 1113
telemt_desync_frames_bucket_total{bucket="gt_10"} 1130
telemt_pool_swap_total 52
telemt_me_writer_removed_unexpected_total 17346
telemt_me_refill_failed_total 499
telemt_me_writer_restored_same_endpoint_total 16612
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 723
telemt_user_connections_total{user="hello"} 1111180
telemt_user_connections_current{user="hello"} 784
telemt_user_octets_from_client{user="hello"} 13150681793 (12.25 GB)
telemt_user_octets_to_client{user="hello"} 332615230165 (309.77 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 232
telemt_user_unique_ips_recent_window{user="hello"} 142
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 83324.9 (23h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 926095
telemt_connections_bad_total 77213
telemt_handshake_timeouts_total 87842
telemt_upstream_connect_attempt_total 22677
telemt_upstream_connect_success_total 22677
telemt_upstream_connect_attempts_per_request{bucket="1"} 22677
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12428
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10245
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_me_keepalive_timeout_total 939
telemt_me_reconnect_attempts_total 19582
telemt_me_reconnect_success_total 18513
telemt_me_reader_eof_total 19635
telemt_me_idle_close_by_peer_total 19634
telemt_me_seq_mismatch_total 17
telemt_me_route_drop_no_conn_total 298133
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 735640
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 28
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1578
telemt_desync_full_logged_total 619
telemt_desync_suppressed_total 959
telemt_desync_frames_bucket_total{bucket="1_2"} 567
telemt_desync_frames_bucket_total{bucket="3_10"} 557
telemt_desync_frames_bucket_total{bucket="gt_10"} 454
telemt_pool_swap_total 73
telemt_me_writer_removed_unexpected_total 18740
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 18485
telemt_me_writer_restored_fallback_total 28
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 227
telemt_user_connections_total{user="hello"} 735004
telemt_user_connections_current{user="hello"} 620
telemt_user_octets_from_client{user="hello"} 8530163240 (7.94 GB)
telemt_user_octets_to_client{user="hello"} 213547245316 (198.88 GB)
telemt_user_unique_ips_current{user="hello"} 163
telemt_user_unique_ips_recent_window{user="hello"} 103
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 83324.7 (23h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1010123
telemt_connections_bad_total 6817
telemt_handshake_timeouts_total 9286
telemt_upstream_connect_attempt_total 22733
telemt_upstream_connect_success_total 22635
telemt_upstream_connect_fail_total 98
telemt_upstream_connect_attempts_per_request{bucket="1"} 22733
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11626
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10822
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 183
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 98
telemt_me_keepalive_timeout_total 967
telemt_me_reconnect_attempts_total 22416
telemt_me_reconnect_success_total 18343
telemt_me_reader_eof_total 19356
telemt_me_idle_close_by_peer_total 19356
telemt_me_route_drop_no_conn_total 356749
telemt_me_route_drop_channel_closed_total 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 917310
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 3682
telemt_desync_full_logged_total 1358
telemt_desync_suppressed_total 2324
telemt_desync_frames_bucket_total{bucket="1_2"} 1297
telemt_desync_frames_bucket_total{bucket="3_10"} 1388
telemt_desync_frames_bucket_total{bucket="gt_10"} 997
telemt_pool_swap_total 56
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 18706
telemt_me_refill_failed_total 124
telemt_me_writer_restored_same_endpoint_total 18343
telemt_me_async_recovery_trigger_total 48
telemt_me_writer_removed_unexpected_minus_restored_total 363
telemt_user_connections_total{user="hello"} 917051
telemt_user_connections_current{user="hello"} 747
telemt_user_octets_from_client{user="hello"} 13381397335 (12.46 GB)
telemt_user_octets_to_client{user="hello"} 327678372166 (305.17 GB)
telemt_user_msgs_from_client{user="hello"} 122
telemt_user_msgs_to_client{user="hello"} 215
telemt_user_unique_ips_current{user="hello"} 198
telemt_user_unique_ips_recent_window{user="hello"} 119
```