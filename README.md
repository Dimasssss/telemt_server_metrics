# Server Metrics 2026-03-15 12:27:49 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.18

telemt_uptime_seconds 51199.3 (14h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1436508
telemt_connections_bad_total 84730
telemt_handshake_timeouts_total 12135
telemt_upstream_connect_attempt_total 10200
telemt_upstream_connect_success_total 10152
telemt_upstream_connect_fail_total 48
telemt_upstream_connect_attempts_per_request{bucket="1"} 10200
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5387
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4732
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 33
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 48
telemt_me_keepalive_timeout_total 13
telemt_me_reconnect_attempts_total 12474
telemt_me_reconnect_success_total 7596
telemt_me_reader_eof_total 8151
telemt_me_idle_close_by_peer_total 8151
telemt_me_route_drop_no_conn_total 480502
telemt_me_route_drop_channel_closed_total 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1204691
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4554
telemt_desync_full_logged_total 1283
telemt_desync_suppressed_total 3271
telemt_desync_frames_bucket_total{bucket="1_2"} 1123
telemt_desync_frames_bucket_total{bucket="3_10"} 1784
telemt_desync_frames_bucket_total{bucket="gt_10"} 1647
telemt_pool_swap_total 40
telemt_me_writer_removed_unexpected_total 7861
telemt_me_refill_failed_total 151
telemt_me_writer_restored_same_endpoint_total 7585
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 296
telemt_me_writer_removed_unexpected_minus_restored_total 265
telemt_user_connections_total{user="hello"} 1204363
telemt_user_connections_current{user="hello"} 2151
telemt_user_octets_from_client{user="hello"} 17071424188 (15.90 GB)
telemt_user_octets_to_client{user="hello"} 482298442612 (449.18 GB)
telemt_user_unique_ips_current{user="hello"} 630
telemt_user_unique_ips_recent_window{user="hello"} 271
```

## server2

```
telemt 3.3.18

telemt_uptime_seconds 51200.3 (14h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 572469
telemt_connections_bad_total 29283
telemt_handshake_timeouts_total 35286
telemt_upstream_connect_attempt_total 13274
telemt_upstream_connect_success_total 13209
telemt_upstream_connect_fail_total 65
telemt_upstream_connect_attempts_per_request{bucket="1"} 13274
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7124
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5968
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 34
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 83
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 65
telemt_me_keepalive_timeout_total 15
telemt_me_reconnect_attempts_total 10397
telemt_me_reconnect_success_total 10324
telemt_me_reader_eof_total 10918
telemt_me_idle_close_by_peer_total 10918
telemt_me_route_drop_no_conn_total 145304
telemt_me_route_drop_channel_closed_total 3
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 444316
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 16
telemt_me_endpoint_quarantine_total 17
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1740
telemt_desync_full_logged_total 608
telemt_desync_suppressed_total 1132
telemt_desync_frames_bucket_total{bucket="1_2"} 653
telemt_desync_frames_bucket_total{bucket="3_10"} 639
telemt_desync_frames_bucket_total{bucket="gt_10"} 448
telemt_pool_swap_total 45
telemt_me_writer_removed_unexpected_total 10438
telemt_me_writer_restored_same_endpoint_total 10312
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 61
telemt_me_writer_removed_unexpected_minus_restored_total 114
telemt_user_connections_total{user="hello"} 444584
telemt_user_connections_current{user="hello"} 708
telemt_user_octets_from_client{user="hello"} 6274631071 (5.84 GB)
telemt_user_octets_to_client{user="hello"} 163957921996 (152.70 GB)
telemt_user_msgs_from_client{user="hello"} 620
telemt_user_msgs_to_client{user="hello"} 1332
telemt_user_unique_ips_current{user="hello"} 211
telemt_user_unique_ips_recent_window{user="hello"} 104
```

## server3

```
telemt 3.3.18

telemt_uptime_seconds 51200.2 (14h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1152313
telemt_connections_bad_total 37505
telemt_handshake_timeouts_total 117072
telemt_upstream_connect_attempt_total 11309
telemt_upstream_connect_success_total 11255
telemt_upstream_connect_fail_total 54
telemt_upstream_connect_attempts_per_request{bucket="1"} 11309
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5813
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5385
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 57
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 54
telemt_me_reconnect_attempts_total 9930
telemt_me_reconnect_success_total 8686
telemt_me_reader_eof_total 9207
telemt_me_idle_close_by_peer_total 9207
telemt_me_route_drop_no_conn_total 351969
telemt_me_route_drop_channel_closed_total 16
telemt_me_route_drop_queue_full_total 6
telemt_me_route_drop_queue_full_profile_total{profile="high"} 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 772840
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1995
telemt_desync_full_logged_total 710
telemt_desync_suppressed_total 1285
telemt_desync_frames_bucket_total{bucket="1_2"} 447
telemt_desync_frames_bucket_total{bucket="3_10"} 741
telemt_desync_frames_bucket_total{bucket="gt_10"} 807
telemt_pool_swap_total 46
telemt_me_writer_removed_unexpected_total 8836
telemt_me_refill_failed_total 37
telemt_me_writer_restored_same_endpoint_total 8667
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 242
telemt_me_writer_removed_unexpected_minus_restored_total 150
telemt_user_connections_total{user="hello"} 769340
telemt_user_connections_current{user="hello"} 1144
telemt_user_octets_from_client{user="hello"} 11317937580 (10.54 GB)
telemt_user_octets_to_client{user="hello"} 289223984204 (269.36 GB)
telemt_user_unique_ips_current{user="hello"} 378
telemt_user_unique_ips_recent_window{user="hello"} 177
```

## server4

```
telemt 3.3.18

telemt_uptime_seconds 51200.1 (14h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 570931
telemt_connections_bad_total 65917
telemt_handshake_timeouts_total 32805
telemt_upstream_connect_attempt_total 14608
telemt_upstream_connect_success_total 14230
telemt_upstream_connect_fail_total 378
telemt_upstream_connect_attempts_per_request{bucket="1"} 14608
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6735
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7492
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 378
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 39770
telemt_me_reconnect_success_total 11676
telemt_me_reader_eof_total 12888
telemt_me_idle_close_by_peer_total 12888
telemt_me_seq_mismatch_total 18
telemt_me_route_drop_no_conn_total 161988
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 426625
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 35
telemt_me_hardswap_pending_ttl_expired_total 9
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1105
telemt_desync_full_logged_total 282
telemt_desync_suppressed_total 823
telemt_desync_frames_bucket_total{bucket="1_2"} 296
telemt_desync_frames_bucket_total{bucket="3_10"} 456
telemt_desync_frames_bucket_total{bucket="gt_10"} 353
telemt_pool_swap_total 17
telemt_me_writer_removed_unexpected_total 12664
telemt_me_refill_failed_total 878
telemt_me_writer_restored_same_endpoint_total 11644
telemt_me_writer_restored_fallback_total 32
telemt_me_async_recovery_trigger_total 96
telemt_me_writer_removed_unexpected_minus_restored_total 988
telemt_user_connections_total{user="hello"} 426496
telemt_user_connections_current{user="hello"} 612
telemt_user_octets_from_client{user="hello"} 7944614196 (7.40 GB)
telemt_user_octets_to_client{user="hello"} 149940933484 (139.64 GB)
telemt_user_unique_ips_current{user="hello"} 215
telemt_user_unique_ips_recent_window{user="hello"} 99
```

## server5

```
telemt 3.3.18

telemt_uptime_seconds 51201.1 (14h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 616188
telemt_connections_bad_total 6978
telemt_handshake_timeouts_total 13127
telemt_upstream_connect_attempt_total 11428
telemt_upstream_connect_success_total 11370
telemt_upstream_connect_fail_total 58
telemt_upstream_connect_attempts_per_request{bucket="1"} 11428
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5242
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6123
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 58
telemt_me_reconnect_attempts_total 8865
telemt_me_reconnect_success_total 8815
telemt_me_reader_eof_total 9349
telemt_me_idle_close_by_peer_total 9349
telemt_me_route_drop_no_conn_total 153779
telemt_me_route_drop_channel_closed_total 20
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 499162
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1956
telemt_desync_full_logged_total 643
telemt_desync_suppressed_total 1313
telemt_desync_frames_bucket_total{bucket="1_2"} 570
telemt_desync_frames_bucket_total{bucket="3_10"} 776
telemt_desync_frames_bucket_total{bucket="gt_10"} 610
telemt_pool_swap_total 46
telemt_me_writer_removed_unexpected_total 8920
telemt_me_writer_restored_same_endpoint_total 8807
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 54
telemt_me_writer_removed_unexpected_minus_restored_total 105
telemt_user_connections_total{user="hello"} 499194
telemt_user_connections_current{user="hello"} 811
telemt_user_octets_from_client{user="hello"} 6485813440 (6.04 GB)
telemt_user_octets_to_client{user="hello"} 179438681068 (167.12 GB)
telemt_user_unique_ips_current{user="hello"} 221
telemt_user_unique_ips_recent_window{user="hello"} 110
```