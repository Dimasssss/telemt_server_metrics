# Server Metrics 2026-03-11 18:20:55 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 100429.0 (27h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2546447
telemt_connections_bad_total 48537
telemt_handshake_timeouts_total 56425
telemt_upstream_connect_attempt_total 21235
telemt_upstream_connect_success_total 21223
telemt_upstream_connect_fail_total 12
telemt_upstream_connect_attempts_per_request{bucket="1"} 21235
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10725
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10394
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 103
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 12
telemt_me_keepalive_timeout_total 5293
telemt_me_reconnect_attempts_total 34018
telemt_me_reconnect_success_total 16137
telemt_me_reader_eof_total 17457
telemt_me_idle_close_by_peer_total 17457
telemt_me_route_drop_no_conn_total 950164
telemt_me_route_drop_channel_closed_total 8
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2329183
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 11853
telemt_desync_full_logged_total 3268
telemt_desync_suppressed_total 8585
telemt_desync_frames_bucket_total{bucket="1_2"} 2925
telemt_desync_frames_bucket_total{bucket="3_10"} 4584
telemt_desync_frames_bucket_total{bucket="gt_10"} 4344
telemt_pool_swap_total 72
telemt_me_writer_removed_unexpected_total 16875
telemt_me_refill_failed_total 555
telemt_me_writer_restored_same_endpoint_total 16131
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 738
telemt_user_connections_total{user="hello"} 2327626
telemt_user_connections_current{user="hello"} 1203
telemt_user_octets_from_client{user="hello"} 34691629496 (32.31 GB)
telemt_user_octets_to_client{user="hello"} 658364196000 (613.15 GB)
telemt_user_unique_ips_current{user="hello"} 343
telemt_user_unique_ips_recent_window{user="hello"} 143
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 100485.8 (27h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 954225
telemt_connections_bad_total 16367
telemt_handshake_timeouts_total 84829
telemt_upstream_connect_attempt_total 31269
telemt_upstream_connect_success_total 28302
telemt_upstream_connect_fail_total 2967
telemt_upstream_connect_attempts_per_request{bucket="1"} 31269
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13332
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12717
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 209
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2044
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2967
telemt_me_keepalive_timeout_total 2814
telemt_me_reconnect_attempts_total 22411
telemt_me_reconnect_success_total 20301
telemt_me_reader_eof_total 21488
telemt_me_idle_close_by_peer_total 21485
telemt_me_route_drop_no_conn_total 360479
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 795547
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3127
telemt_desync_full_logged_total 1008
telemt_desync_suppressed_total 2119
telemt_desync_frames_bucket_total{bucket="1_2"} 975
telemt_desync_frames_bucket_total{bucket="3_10"} 1113
telemt_desync_frames_bucket_total{bucket="gt_10"} 1039
telemt_pool_swap_total 81
telemt_me_writer_removed_unexpected_total 20585
telemt_me_refill_failed_total 60
telemt_me_writer_restored_same_endpoint_total 20278
telemt_me_writer_restored_fallback_total 23
telemt_me_async_recovery_trigger_total 86
telemt_me_writer_removed_unexpected_minus_restored_total 284
telemt_user_connections_total{user="hello"} 798009
telemt_user_connections_current{user="hello"} 450
telemt_user_octets_from_client{user="hello"} 9628823478 (8.97 GB)
telemt_user_octets_to_client{user="hello"} 228822924300 (213.11 GB)
telemt_user_msgs_from_client{user="hello"} 7933
telemt_user_msgs_to_client{user="hello"} 11226
telemt_user_unique_ips_current{user="hello"} 135
telemt_user_unique_ips_recent_window{user="hello"} 69
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 100485.7 (27h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1637866
telemt_connections_bad_total 10391
telemt_handshake_timeouts_total 133183
telemt_upstream_connect_attempt_total 26057
telemt_upstream_connect_success_total 25731
telemt_upstream_connect_fail_total 326
telemt_upstream_connect_attempts_per_request{bucket="1"} 26057
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13854
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11747
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 129
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 326
telemt_me_keepalive_timeout_total 1953
telemt_me_reconnect_attempts_total 45587
telemt_me_reconnect_success_total 19580
telemt_me_reader_eof_total 21243
telemt_me_idle_close_by_peer_total 21243
telemt_me_route_drop_no_conn_total 595474
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1431969
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 10
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3913
telemt_desync_full_logged_total 1144
telemt_desync_suppressed_total 2769
telemt_desync_frames_bucket_total{bucket="1_2"} 923
telemt_desync_frames_bucket_total{bucket="3_10"} 1483
telemt_desync_frames_bucket_total{bucket="gt_10"} 1507
telemt_pool_swap_total 55
telemt_me_writer_removed_unexpected_total 20663
telemt_me_refill_failed_total 807
telemt_me_writer_restored_same_endpoint_total 19568
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 1083
telemt_user_connections_total{user="hello"} 1431653
telemt_user_connections_current{user="hello"} 768
telemt_user_octets_from_client{user="hello"} 17800902401 (16.58 GB)
telemt_user_octets_to_client{user="hello"} 435321494473 (405.42 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 226
telemt_user_unique_ips_recent_window{user="hello"} 110
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 100486.1 (27h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1167214
telemt_connections_bad_total 77992
telemt_handshake_timeouts_total 108971
telemt_upstream_connect_attempt_total 27093
telemt_upstream_connect_success_total 27093
telemt_upstream_connect_attempts_per_request{bucket="1"} 27093
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14784
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12303
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 1413
telemt_me_reconnect_attempts_total 26676
telemt_me_reconnect_success_total 22068
telemt_me_reader_eof_total 23443
telemt_me_idle_close_by_peer_total 23442
telemt_me_seq_mismatch_total 23
telemt_me_route_drop_no_conn_total 388419
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 946056
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 34
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1995
telemt_desync_full_logged_total 760
telemt_desync_suppressed_total 1235
telemt_desync_frames_bucket_total{bucket="1_2"} 722
telemt_desync_frames_bucket_total{bucket="3_10"} 685
telemt_desync_frames_bucket_total{bucket="gt_10"} 588
telemt_pool_swap_total 82
telemt_me_writer_removed_unexpected_total 22445
telemt_me_refill_failed_total 141
telemt_me_writer_restored_same_endpoint_total 22035
telemt_me_writer_restored_fallback_total 33
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 377
telemt_user_connections_total{user="hello"} 945318
telemt_user_connections_current{user="hello"} 562
telemt_user_octets_from_client{user="hello"} 11298576948 (10.52 GB)
telemt_user_octets_to_client{user="hello"} 288037174576 (268.26 GB)
telemt_user_unique_ips_current{user="hello"} 155
telemt_user_unique_ips_recent_window{user="hello"} 90
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 5162.2 (1h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 89946
telemt_connections_bad_total 315
telemt_handshake_timeouts_total 543
telemt_upstream_connect_attempt_total 1513
telemt_upstream_connect_success_total 1512
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 1513
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 830
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 669
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 13
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 26
telemt_me_reconnect_attempts_total 1223
telemt_me_reconnect_success_total 1211
telemt_me_reader_eof_total 1220
telemt_me_idle_close_by_peer_total 1220
telemt_me_seq_mismatch_total 1
telemt_me_route_drop_no_conn_total 30366
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 83620
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 183
telemt_desync_full_logged_total 57
telemt_desync_suppressed_total 126
telemt_desync_frames_bucket_total{bucket="1_2"} 40
telemt_desync_frames_bucket_total{bucket="3_10"} 61
telemt_desync_frames_bucket_total{bucket="gt_10"} 82
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 1220
telemt_me_writer_restored_same_endpoint_total 1188
telemt_me_writer_restored_fallback_total 23
telemt_me_async_recovery_trigger_total 256
telemt_me_writer_removed_unexpected_minus_restored_total 9
telemt_user_connections_total{user="hello"} 83607
telemt_user_connections_current{user="hello"} 664
telemt_user_octets_from_client{user="hello"} 6121080956 (5.70 GB)
telemt_user_octets_to_client{user="hello"} 30091672836 (28.03 GB)
telemt_user_unique_ips_current{user="hello"} 176
telemt_user_unique_ips_recent_window{user="hello"} 87
```