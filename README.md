# Server Metrics 2026-03-11 16:59:11 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 95524.7 (26h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2391483
telemt_connections_bad_total 42854
telemt_handshake_timeouts_total 54217
telemt_upstream_connect_attempt_total 19991
telemt_upstream_connect_success_total 19979
telemt_upstream_connect_fail_total 12
telemt_upstream_connect_attempts_per_request{bucket="1"} 19991
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10077
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9806
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 95
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 12
telemt_me_keepalive_timeout_total 5076
telemt_me_reconnect_attempts_total 33001
telemt_me_reconnect_success_total 15126
telemt_me_reader_eof_total 16392
telemt_me_idle_close_by_peer_total 16392
telemt_me_route_drop_no_conn_total 888025
telemt_me_route_drop_channel_closed_total 8
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2187713
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 11321
telemt_desync_full_logged_total 3094
telemt_desync_suppressed_total 8227
telemt_desync_frames_bucket_total{bucket="1_2"} 2798
telemt_desync_frames_bucket_total{bucket="3_10"} 4367
telemt_desync_frames_bucket_total{bucket="gt_10"} 4156
telemt_pool_swap_total 69
telemt_me_writer_removed_unexpected_total 15854
telemt_me_refill_failed_total 555
telemt_me_writer_restored_same_endpoint_total 15120
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 728
telemt_user_connections_total{user="hello"} 2186161
telemt_user_connections_current{user="hello"} 1333
telemt_user_octets_from_client{user="hello"} 29378737800 (27.36 GB)
telemt_user_octets_to_client{user="hello"} 616196511396 (573.88 GB)
telemt_user_unique_ips_current{user="hello"} 383
telemt_user_unique_ips_recent_window{user="hello"} 192
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 95581.3 (26h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 898839
telemt_connections_bad_total 15595
telemt_handshake_timeouts_total 76206
telemt_upstream_connect_attempt_total 30196
telemt_upstream_connect_success_total 27236
telemt_upstream_connect_fail_total 2960
telemt_upstream_connect_attempts_per_request{bucket="1"} 30196
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12763
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12224
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 209
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2040
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2960
telemt_me_keepalive_timeout_total 2657
telemt_me_reconnect_attempts_total 21565
telemt_me_reconnect_success_total 19463
telemt_me_reader_eof_total 20593
telemt_me_idle_close_by_peer_total 20590
telemt_me_route_drop_no_conn_total 342785
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 751541
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3026
telemt_desync_full_logged_total 965
telemt_desync_suppressed_total 2061
telemt_desync_frames_bucket_total{bucket="1_2"} 917
telemt_desync_frames_bucket_total{bucket="3_10"} 1089
telemt_desync_frames_bucket_total{bucket="gt_10"} 1020
telemt_pool_swap_total 77
telemt_me_writer_removed_unexpected_total 19739
telemt_me_refill_failed_total 60
telemt_me_writer_restored_same_endpoint_total 19440
telemt_me_writer_restored_fallback_total 23
telemt_me_async_recovery_trigger_total 86
telemt_me_writer_removed_unexpected_minus_restored_total 276
telemt_user_connections_total{user="hello"} 754000
telemt_user_connections_current{user="hello"} 491
telemt_user_octets_from_client{user="hello"} 8658192494 (8.06 GB)
telemt_user_octets_to_client{user="hello"} 213140800908 (198.50 GB)
telemt_user_msgs_from_client{user="hello"} 7933
telemt_user_msgs_to_client{user="hello"} 11226
telemt_user_unique_ips_current{user="hello"} 146
telemt_user_unique_ips_recent_window{user="hello"} 70
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 95581.4 (26h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1533278
telemt_connections_bad_total 8977
telemt_handshake_timeouts_total 126174
telemt_upstream_connect_attempt_total 24682
telemt_upstream_connect_success_total 24364
telemt_upstream_connect_fail_total 318
telemt_upstream_connect_attempts_per_request{bucket="1"} 24682
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13132
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11106
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 126
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 318
telemt_me_keepalive_timeout_total 1755
telemt_me_reconnect_attempts_total 42203
telemt_me_reconnect_success_total 18446
telemt_me_reader_eof_total 20005
telemt_me_idle_close_by_peer_total 20005
telemt_me_route_drop_no_conn_total 559855
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1341078
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 9
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3493
telemt_desync_full_logged_total 1031
telemt_desync_suppressed_total 2462
telemt_desync_frames_bucket_total{bucket="1_2"} 867
telemt_desync_frames_bucket_total{bucket="3_10"} 1319
telemt_desync_frames_bucket_total{bucket="gt_10"} 1307
telemt_pool_swap_total 54
telemt_me_writer_removed_unexpected_total 19440
telemt_me_refill_failed_total 737
telemt_me_writer_restored_same_endpoint_total 18434
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 994
telemt_user_connections_total{user="hello"} 1340780
telemt_user_connections_current{user="hello"} 929
telemt_user_octets_from_client{user="hello"} 16428126253 (15.30 GB)
telemt_user_octets_to_client{user="hello"} 407193950369 (379.23 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 242
telemt_user_unique_ips_recent_window{user="hello"} 132
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 95581.9 (26h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1102432
telemt_connections_bad_total 77987
telemt_handshake_timeouts_total 105434
telemt_upstream_connect_attempt_total 25786
telemt_upstream_connect_success_total 25786
telemt_upstream_connect_attempts_per_request{bucket="1"} 25786
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14097
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11684
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 1166
telemt_me_reconnect_attempts_total 23132
telemt_me_reconnect_success_total 20996
telemt_me_reader_eof_total 22275
telemt_me_idle_close_by_peer_total 22274
telemt_me_seq_mismatch_total 20
telemt_me_route_drop_no_conn_total 362562
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 885807
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 31
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1828
telemt_desync_full_logged_total 706
telemt_desync_suppressed_total 1122
telemt_desync_frames_bucket_total{bucket="1_2"} 656
telemt_desync_frames_bucket_total{bucket="3_10"} 639
telemt_desync_frames_bucket_total{bucket="gt_10"} 533
telemt_pool_swap_total 81
telemt_me_writer_removed_unexpected_total 21285
telemt_me_refill_failed_total 64
telemt_me_writer_restored_same_endpoint_total 20965
telemt_me_writer_restored_fallback_total 31
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 289
telemt_user_connections_total{user="hello"} 885112
telemt_user_connections_current{user="hello"} 495
telemt_user_octets_from_client{user="hello"} 10659323460 (9.93 GB)
telemt_user_octets_to_client{user="hello"} 263390136444 (245.30 GB)
telemt_user_unique_ips_current{user="hello"} 149
telemt_user_unique_ips_recent_window{user="hello"} 82
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 258.2 (0h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4818
telemt_handshake_timeouts_total 28
telemt_upstream_connect_attempt_total 126
telemt_upstream_connect_success_total 126
telemt_upstream_connect_attempts_per_request{bucket="1"} 126
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 82
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 43
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 58
telemt_me_reconnect_success_total 58
telemt_me_reader_eof_total 17
telemt_me_idle_close_by_peer_total 17
telemt_me_route_drop_no_conn_total 1029
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4543
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_desync_total 8
telemt_desync_full_logged_total 3
telemt_desync_suppressed_total 5
telemt_desync_frames_bucket_total{bucket="1_2"} 3
telemt_desync_frames_bucket_total{bucket="3_10"} 2
telemt_desync_frames_bucket_total{bucket="gt_10"} 3
telemt_me_writer_removed_unexpected_total 39
telemt_me_writer_restored_same_endpoint_total 36
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 256
telemt_user_connections_total{user="hello"} 4544
telemt_user_connections_current{user="hello"} 575
telemt_user_octets_from_client{user="hello"} 33857724 (32.29 MB)
telemt_user_octets_to_client{user="hello"} 1125416148 (1.05 GB)
telemt_user_unique_ips_current{user="hello"} 166
telemt_user_unique_ips_recent_window{user="hello"} 87
```