# Server Metrics 2026-03-11 14:25:59 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 86333.0 (23h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2078403
telemt_connections_bad_total 31005
telemt_handshake_timeouts_total 52071
telemt_upstream_connect_attempt_total 18217
telemt_upstream_connect_success_total 18205
telemt_upstream_connect_fail_total 12
telemt_upstream_connect_attempts_per_request{bucket="1"} 18217
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9194
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8921
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 89
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 12
telemt_me_keepalive_timeout_total 4783
telemt_me_reconnect_attempts_total 27715
telemt_me_reconnect_success_total 13849
telemt_me_reader_eof_total 14932
telemt_me_idle_close_by_peer_total 14932
telemt_me_route_drop_no_conn_total 767544
telemt_me_route_drop_channel_closed_total 7
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1900926
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 10017
telemt_desync_full_logged_total 2715
telemt_desync_suppressed_total 7302
telemt_desync_frames_bucket_total{bucket="1_2"} 2492
telemt_desync_frames_bucket_total{bucket="3_10"} 3865
telemt_desync_frames_bucket_total{bucket="gt_10"} 3660
telemt_pool_swap_total 64
telemt_me_writer_removed_unexpected_total 14431
telemt_me_refill_failed_total 430
telemt_me_writer_restored_same_endpoint_total 13843
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 582
telemt_user_connections_total{user="hello"} 1899436
telemt_user_connections_current{user="hello"} 1356
telemt_user_octets_from_client{user="hello"} 25571164228 (23.82 GB)
telemt_user_octets_to_client{user="hello"} 540661050672 (503.53 GB)
telemt_user_unique_ips_current{user="hello"} 364
telemt_user_unique_ips_recent_window{user="hello"} 175
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 86389.9 (23h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 780060
telemt_connections_bad_total 13167
telemt_handshake_timeouts_total 52632
telemt_upstream_connect_attempt_total 27631
telemt_upstream_connect_success_total 24682
telemt_upstream_connect_fail_total 2949
telemt_upstream_connect_attempts_per_request{bucket="1"} 27631
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11413
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11021
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 209
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2039
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2949
telemt_me_keepalive_timeout_total 2522
telemt_me_reconnect_attempts_total 19503
telemt_me_reconnect_success_total 17417
telemt_me_reader_eof_total 18442
telemt_me_idle_close_by_peer_total 18439
telemt_me_route_drop_no_conn_total 305019
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 660859
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2829
telemt_desync_full_logged_total 896
telemt_desync_suppressed_total 1933
telemt_desync_frames_bucket_total{bucket="1_2"} 881
telemt_desync_frames_bucket_total{bucket="3_10"} 1026
telemt_desync_frames_bucket_total{bucket="gt_10"} 922
telemt_pool_swap_total 70
telemt_me_writer_removed_unexpected_total 17672
telemt_me_refill_failed_total 60
telemt_me_writer_restored_same_endpoint_total 17394
telemt_me_writer_restored_fallback_total 23
telemt_me_async_recovery_trigger_total 86
telemt_me_writer_removed_unexpected_minus_restored_total 255
telemt_user_connections_total{user="hello"} 663343
telemt_user_connections_current{user="hello"} 590
telemt_user_octets_from_client{user="hello"} 7035896318 (6.55 GB)
telemt_user_octets_to_client{user="hello"} 187371521240 (174.50 GB)
telemt_user_msgs_from_client{user="hello"} 7933
telemt_user_msgs_to_client{user="hello"} 11226
telemt_user_unique_ips_current{user="hello"} 166
telemt_user_unique_ips_recent_window{user="hello"} 89
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 86389.7 (23h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1349533
telemt_connections_bad_total 8444
telemt_handshake_timeouts_total 121855
telemt_upstream_connect_attempt_total 22936
telemt_upstream_connect_success_total 22664
telemt_upstream_connect_fail_total 272
telemt_upstream_connect_attempts_per_request{bucket="1"} 22936
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12246
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10307
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 111
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 272
telemt_me_keepalive_timeout_total 903
telemt_me_reconnect_attempts_total 33365
telemt_me_reconnect_success_total 17255
telemt_me_reader_eof_total 18549
telemt_me_idle_close_by_peer_total 18549
telemt_me_route_drop_no_conn_total 487535
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1168804
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3139
telemt_desync_full_logged_total 924
telemt_desync_suppressed_total 2215
telemt_desync_frames_bucket_total{bucket="1_2"} 762
telemt_desync_frames_bucket_total{bucket="3_10"} 1190
telemt_desync_frames_bucket_total{bucket="gt_10"} 1187
telemt_pool_swap_total 53
telemt_me_writer_removed_unexpected_total 17989
telemt_me_refill_failed_total 499
telemt_me_writer_restored_same_endpoint_total 17244
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 734
telemt_user_connections_total{user="hello"} 1168601
telemt_user_connections_current{user="hello"} 824
telemt_user_octets_from_client{user="hello"} 14051071373 (13.09 GB)
telemt_user_octets_to_client{user="hello"} 348546628169 (324.61 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 237
telemt_user_unique_ips_recent_window{user="hello"} 141
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 86390.2 (23h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 970592
telemt_connections_bad_total 77421
telemt_handshake_timeouts_total 92761
telemt_upstream_connect_attempt_total 23324
telemt_upstream_connect_success_total 23324
telemt_upstream_connect_attempts_per_request{bucket="1"} 23324
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12761
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10558
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 953
telemt_me_reconnect_attempts_total 20098
telemt_me_reconnect_success_total 19026
telemt_me_reader_eof_total 20177
telemt_me_idle_close_by_peer_total 20176
telemt_me_seq_mismatch_total 17
telemt_me_route_drop_no_conn_total 315277
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 774089
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 28
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1642
telemt_desync_full_logged_total 640
telemt_desync_suppressed_total 1002
telemt_desync_frames_bucket_total{bucket="1_2"} 592
telemt_desync_frames_bucket_total{bucket="3_10"} 575
telemt_desync_frames_bucket_total{bucket="gt_10"} 475
telemt_pool_swap_total 75
telemt_me_writer_removed_unexpected_total 19262
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 18998
telemt_me_writer_restored_fallback_total 28
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 236
telemt_user_connections_total{user="hello"} 773422
telemt_user_connections_current{user="hello"} 594
telemt_user_octets_from_client{user="hello"} 9058974192 (8.44 GB)
telemt_user_octets_to_client{user="hello"} 225068193196 (209.61 GB)
telemt_user_unique_ips_current{user="hello"} 157
telemt_user_unique_ips_recent_window{user="hello"} 92
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 86389.9 (23h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1065773
telemt_connections_bad_total 6936
telemt_handshake_timeouts_total 10344
telemt_upstream_connect_attempt_total 23339
telemt_upstream_connect_success_total 23237
telemt_upstream_connect_fail_total 102
telemt_upstream_connect_attempts_per_request{bucket="1"} 23339
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11892
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11153
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 187
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 102
telemt_me_keepalive_timeout_total 1006
telemt_me_reconnect_attempts_total 22887
telemt_me_reconnect_success_total 18810
telemt_me_reader_eof_total 19840
telemt_me_idle_close_by_peer_total 19840
telemt_me_route_drop_no_conn_total 378162
telemt_me_route_drop_channel_closed_total 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 967887
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 3792
telemt_desync_full_logged_total 1395
telemt_desync_suppressed_total 2397
telemt_desync_frames_bucket_total{bucket="1_2"} 1325
telemt_desync_frames_bucket_total{bucket="3_10"} 1431
telemt_desync_frames_bucket_total{bucket="gt_10"} 1036
telemt_pool_swap_total 58
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 19179
telemt_me_refill_failed_total 124
telemt_me_writer_restored_same_endpoint_total 18810
telemt_me_async_recovery_trigger_total 48
telemt_me_writer_removed_unexpected_minus_restored_total 369
telemt_user_connections_total{user="hello"} 967621
telemt_user_connections_current{user="hello"} 751
telemt_user_octets_from_client{user="hello"} 13931889467 (12.98 GB)
telemt_user_octets_to_client{user="hello"} 340416503174 (317.04 GB)
telemt_user_msgs_from_client{user="hello"} 122
telemt_user_msgs_to_client{user="hello"} 215
telemt_user_unique_ips_current{user="hello"} 195
telemt_user_unique_ips_recent_window{user="hello"} 98
```