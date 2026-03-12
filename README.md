# Server Metrics 2026-03-12 21:28:29 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 55789.3 (15h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1869291
telemt_connections_bad_total 25626
telemt_handshake_timeouts_total 20491
telemt_upstream_connect_attempt_total 10840
telemt_upstream_connect_success_total 10778
telemt_upstream_connect_fail_total 62
telemt_upstream_connect_attempts_per_request{bucket="1"} 10840
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5598
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5144
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 36
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 62
telemt_me_keepalive_timeout_total 589
telemt_me_reconnect_attempts_total 16833
telemt_me_reconnect_success_total 7981
telemt_me_reader_eof_total 8630
telemt_me_idle_close_by_peer_total 8629
telemt_me_route_drop_no_conn_total 731974
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1740206
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8409
telemt_desync_full_logged_total 2178
telemt_desync_suppressed_total 6231
telemt_desync_frames_bucket_total{bucket="1_2"} 2210
telemt_desync_frames_bucket_total{bucket="3_10"} 3030
telemt_desync_frames_bucket_total{bucket="gt_10"} 3169
telemt_pool_swap_total 38
telemt_me_writer_removed_unexpected_total 8373
telemt_me_refill_failed_total 275
telemt_me_writer_restored_same_endpoint_total 7968
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 392
telemt_user_connections_total{user="hello"} 1739690
telemt_user_connections_current{user="hello"} 920
telemt_user_octets_from_client{user="hello"} 26554000912 (24.73 GB)
telemt_user_octets_to_client{user="hello"} 612348393656 (570.29 GB)
telemt_user_unique_ips_current{user="hello"} 285
telemt_user_unique_ips_recent_window{user="hello"} 92
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 85409.9 (23h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 779212
telemt_connections_bad_total 11662
telemt_handshake_timeouts_total 30994
telemt_upstream_connect_attempt_total 21554
telemt_upstream_connect_success_total 21525
telemt_upstream_connect_fail_total 29
telemt_upstream_connect_attempts_per_request{bucket="1"} 21554
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11358
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10079
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 88
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 29
telemt_me_keepalive_timeout_total 3394
telemt_me_reconnect_attempts_total 15713
telemt_me_reconnect_success_total 15621
telemt_me_reader_eof_total 16613
telemt_me_idle_close_by_peer_total 16613
telemt_me_route_drop_no_conn_total 252021
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 702981
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2979
telemt_desync_full_logged_total 922
telemt_desync_suppressed_total 2057
telemt_desync_frames_bucket_total{bucket="1_2"} 1171
telemt_desync_frames_bucket_total{bucket="3_10"} 981
telemt_desync_frames_bucket_total{bucket="gt_10"} 827
telemt_pool_swap_total 85
telemt_me_writer_removed_unexpected_total 15781
telemt_me_writer_restored_same_endpoint_total 15612
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 160
telemt_user_connections_total{user="hello"} 704858
telemt_user_connections_current{user="hello"} 255
telemt_user_octets_from_client{user="hello"} 11965473720 (11.14 GB)
telemt_user_octets_to_client{user="hello"} 270737348163 (252.14 GB)
telemt_user_msgs_from_client{user="hello"} 6476
telemt_user_msgs_to_client{user="hello"} 18854
telemt_user_unique_ips_current{user="hello"} 89
telemt_user_unique_ips_recent_window{user="hello"} 38
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 85409.8 (23h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1613007
telemt_connections_bad_total 7726
telemt_handshake_timeouts_total 111729
telemt_upstream_connect_attempt_total 19977
telemt_upstream_connect_success_total 19971
telemt_upstream_connect_fail_total 6
telemt_upstream_connect_attempts_per_request{bucket="1"} 19977
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10711
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9184
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 71
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 6
telemt_me_keepalive_timeout_total 1213
telemt_me_reconnect_attempts_total 16603
telemt_me_reconnect_success_total 15356
telemt_me_reader_eof_total 16214
telemt_me_idle_close_by_peer_total 16213
telemt_me_route_drop_no_conn_total 533047
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1249060
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4905
telemt_desync_full_logged_total 1507
telemt_desync_suppressed_total 3398
telemt_desync_frames_bucket_total{bucket="1_2"} 782
telemt_desync_frames_bucket_total{bucket="3_10"} 1774
telemt_desync_frames_bucket_total{bucket="gt_10"} 2349
telemt_pool_swap_total 77
telemt_me_writer_removed_unexpected_total 15500
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 15315
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 144
telemt_user_connections_total{user="hello"} 1248666
telemt_user_connections_current{user="hello"} 502
telemt_user_octets_from_client{user="hello"} 19453956192 (18.12 GB)
telemt_user_octets_to_client{user="hello"} 463903685785 (432.04 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 183
telemt_user_unique_ips_recent_window{user="hello"} 78
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 85410.2 (23h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 992915
telemt_connections_bad_total 12977
telemt_handshake_timeouts_total 71060
telemt_upstream_connect_attempt_total 21739
telemt_upstream_connect_success_total 21651
telemt_upstream_connect_fail_total 88
telemt_upstream_connect_attempts_per_request{bucket="1"} 21739
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12168
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9469
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 14
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 88
telemt_me_keepalive_timeout_total 1678
telemt_me_reconnect_attempts_total 25127
telemt_me_reconnect_success_total 17399
telemt_me_reader_eof_total 18582
telemt_me_idle_close_by_peer_total 18582
telemt_me_route_drop_no_conn_total 355390
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 864221
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
telemt_me_writer_removed_unexpected_total 17780
telemt_me_refill_failed_total 239
telemt_me_writer_restored_same_endpoint_total 17378
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 108
telemt_me_writer_removed_unexpected_minus_restored_total 381
telemt_user_connections_total{user="hello"} 863570
telemt_user_connections_current{user="hello"} 324
telemt_user_octets_from_client{user="hello"} 13496837388 (12.57 GB)
telemt_user_octets_to_client{user="hello"} 348676567116 (324.73 GB)
telemt_user_unique_ips_current{user="hello"} 115
telemt_user_unique_ips_recent_window{user="hello"} 44
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 85410.2 (23h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1112486
telemt_connections_bad_total 12515
telemt_handshake_timeouts_total 9042
telemt_upstream_connect_attempt_total 26350
telemt_upstream_connect_success_total 26027
telemt_upstream_connect_fail_total 323
telemt_upstream_connect_attempts_per_request{bucket="1"} 26350
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13318
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12565
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 10
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 134
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 323
telemt_me_keepalive_timeout_total 1431
telemt_me_reconnect_attempts_total 32798
telemt_me_reconnect_success_total 21760
telemt_me_reader_eof_total 22871
telemt_me_idle_close_by_peer_total 22871
telemt_me_seq_mismatch_total 33
telemt_me_route_drop_no_conn_total 417117
telemt_me_route_drop_channel_closed_total 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1022720
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 37
telemt_me_hardswap_pending_ttl_expired_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 3875
telemt_desync_full_logged_total 1349
telemt_desync_suppressed_total 2526
telemt_desync_frames_bucket_total{bucket="1_2"} 1141
telemt_desync_frames_bucket_total{bucket="3_10"} 1277
telemt_desync_frames_bucket_total{bucket="gt_10"} 1457
telemt_pool_swap_total 41
telemt_me_writer_removed_unexpected_total 22354
telemt_me_refill_failed_total 342
telemt_me_writer_restored_same_endpoint_total 21716
telemt_me_writer_restored_fallback_total 44
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 594
telemt_user_connections_total{user="hello"} 1022580
telemt_user_connections_current{user="hello"} 389
telemt_user_octets_from_client{user="hello"} 12710849824 (11.84 GB)
telemt_user_octets_to_client{user="hello"} 361328730564 (336.51 GB)
telemt_user_unique_ips_current{user="hello"} 128
telemt_user_unique_ips_recent_window{user="hello"} 47
```