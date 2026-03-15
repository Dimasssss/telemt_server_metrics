# Server Metrics 2026-03-15 09:13:41 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.18

telemt_uptime_seconds 39551.5 (10h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 855485
telemt_connections_bad_total 41762
telemt_handshake_timeouts_total 6239
telemt_upstream_connect_attempt_total 7964
telemt_upstream_connect_success_total 7931
telemt_upstream_connect_fail_total 33
telemt_upstream_connect_attempts_per_request{bucket="1"} 7964
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4149
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3767
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 15
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 33
telemt_me_keepalive_timeout_total 8
telemt_me_reconnect_attempts_total 6004
telemt_me_reconnect_success_total 5972
telemt_me_reader_eof_total 6322
telemt_me_idle_close_by_peer_total 6322
telemt_me_route_drop_no_conn_total 279212
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 722695
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2373
telemt_desync_full_logged_total 724
telemt_desync_suppressed_total 1649
telemt_desync_frames_bucket_total{bucket="1_2"} 555
telemt_desync_frames_bucket_total{bucket="3_10"} 876
telemt_desync_frames_bucket_total{bucket="gt_10"} 942
telemt_pool_swap_total 36
telemt_me_writer_removed_unexpected_total 6056
telemt_me_writer_restored_same_endpoint_total 5961
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 296
telemt_me_writer_removed_unexpected_minus_restored_total 84
telemt_user_connections_total{user="hello"} 722681
telemt_user_connections_current{user="hello"} 1913
telemt_user_octets_from_client{user="hello"} 9919819640 (9.24 GB)
telemt_user_octets_to_client{user="hello"} 272017298672 (253.34 GB)
telemt_user_unique_ips_current{user="hello"} 560
telemt_user_unique_ips_recent_window{user="hello"} 258
```

## server2

```
telemt 3.3.18

telemt_uptime_seconds 39552.4 (10h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 336869
telemt_connections_bad_total 18813
telemt_handshake_timeouts_total 13208
telemt_upstream_connect_attempt_total 10545
telemt_upstream_connect_success_total 10493
telemt_upstream_connect_fail_total 52
telemt_upstream_connect_attempts_per_request{bucket="1"} 10545
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5708
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4699
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 25
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 61
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 52
telemt_me_keepalive_timeout_total 15
telemt_me_reconnect_attempts_total 8257
telemt_me_reconnect_success_total 8206
telemt_me_reader_eof_total 8694
telemt_me_idle_close_by_peer_total 8694
telemt_me_route_drop_no_conn_total 85251
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 266933
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 16
telemt_me_endpoint_quarantine_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 973
telemt_desync_full_logged_total 333
telemt_desync_suppressed_total 640
telemt_desync_frames_bucket_total{bucket="1_2"} 305
telemt_desync_frames_bucket_total{bucket="3_10"} 365
telemt_desync_frames_bucket_total{bucket="gt_10"} 303
telemt_pool_swap_total 38
telemt_me_writer_removed_unexpected_total 8275
telemt_me_writer_restored_same_endpoint_total 8198
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 61
telemt_me_writer_removed_unexpected_minus_restored_total 69
telemt_user_connections_total{user="hello"} 267207
telemt_user_connections_current{user="hello"} 715
telemt_user_octets_from_client{user="hello"} 3846881623 (3.58 GB)
telemt_user_octets_to_client{user="hello"} 100457576364 (93.56 GB)
telemt_user_msgs_from_client{user="hello"} 620
telemt_user_msgs_to_client{user="hello"} 1332
telemt_user_unique_ips_current{user="hello"} 225
telemt_user_unique_ips_recent_window{user="hello"} 109
```

## server3

```
telemt 3.3.18

telemt_uptime_seconds 39552.6 (10h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 590515
telemt_connections_bad_total 19448
telemt_handshake_timeouts_total 56639
telemt_upstream_connect_attempt_total 8752
telemt_upstream_connect_success_total 8714
telemt_upstream_connect_fail_total 38
telemt_upstream_connect_attempts_per_request{bucket="1"} 8752
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4564
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4100
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 50
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 38
telemt_me_reconnect_attempts_total 6784
telemt_me_reconnect_success_total 6741
telemt_me_reader_eof_total 7135
telemt_me_idle_close_by_peer_total 7135
telemt_me_route_drop_no_conn_total 171908
telemt_me_route_drop_channel_closed_total 9
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 467999
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 958
telemt_desync_full_logged_total 367
telemt_desync_suppressed_total 591
telemt_desync_frames_bucket_total{bucket="1_2"} 209
telemt_desync_frames_bucket_total{bucket="3_10"} 345
telemt_desync_frames_bucket_total{bucket="gt_10"} 404
telemt_pool_swap_total 39
telemt_me_writer_removed_unexpected_total 6823
telemt_me_writer_restored_same_endpoint_total 6722
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 242
telemt_me_writer_removed_unexpected_minus_restored_total 82
telemt_user_connections_total{user="hello"} 467518
telemt_user_connections_current{user="hello"} 967
telemt_user_octets_from_client{user="hello"} 6981348264 (6.50 GB)
telemt_user_octets_to_client{user="hello"} 189824009136 (176.79 GB)
telemt_user_unique_ips_current{user="hello"} 314
telemt_user_unique_ips_recent_window{user="hello"} 163
```

## server4

```
telemt 3.3.18

telemt_uptime_seconds 39552.2 (10h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 360669
telemt_connections_bad_total 51756
telemt_handshake_timeouts_total 23638
telemt_upstream_connect_attempt_total 12555
telemt_upstream_connect_success_total 12259
telemt_upstream_connect_fail_total 296
telemt_upstream_connect_attempts_per_request{bucket="1"} 12555
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5708
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6548
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 296
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 25418
telemt_me_reconnect_success_total 10293
telemt_me_reader_eof_total 11076
telemt_me_idle_close_by_peer_total 11076
telemt_me_seq_mismatch_total 15
telemt_me_route_drop_no_conn_total 96530
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 268652
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 32
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 637
telemt_desync_full_logged_total 160
telemt_desync_suppressed_total 477
telemt_desync_frames_bucket_total{bucket="1_2"} 149
telemt_desync_frames_bucket_total{bucket="3_10"} 272
telemt_desync_frames_bucket_total{bucket="gt_10"} 216
telemt_pool_swap_total 16
telemt_me_writer_removed_unexpected_total 10854
telemt_me_refill_failed_total 472
telemt_me_writer_restored_same_endpoint_total 10263
telemt_me_writer_restored_fallback_total 30
telemt_me_async_recovery_trigger_total 96
telemt_me_writer_removed_unexpected_minus_restored_total 561
telemt_user_connections_total{user="hello"} 268654
telemt_user_connections_current{user="hello"} 560
telemt_user_octets_from_client{user="hello"} 2541059496 (2.37 GB)
telemt_user_octets_to_client{user="hello"} 86765945500 (80.81 GB)
telemt_user_unique_ips_current{user="hello"} 208
telemt_user_unique_ips_recent_window{user="hello"} 114
```

## server5

```
telemt 3.3.18

telemt_uptime_seconds 39553.0 (10h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 333948
telemt_connections_bad_total 3831
telemt_handshake_timeouts_total 3670
telemt_upstream_connect_attempt_total 8818
telemt_upstream_connect_success_total 8780
telemt_upstream_connect_fail_total 38
telemt_upstream_connect_attempts_per_request{bucket="1"} 8818
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3977
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4798
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 38
telemt_me_reconnect_attempts_total 6852
telemt_me_reconnect_success_total 6820
telemt_me_reader_eof_total 7251
telemt_me_idle_close_by_peer_total 7251
telemt_me_route_drop_no_conn_total 91450
telemt_me_route_drop_channel_closed_total 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 283069
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1129
telemt_desync_full_logged_total 363
telemt_desync_suppressed_total 766
telemt_desync_frames_bucket_total{bucket="1_2"} 329
telemt_desync_frames_bucket_total{bucket="3_10"} 469
telemt_desync_frames_bucket_total{bucket="gt_10"} 331
telemt_pool_swap_total 39
telemt_me_writer_removed_unexpected_total 6888
telemt_me_writer_restored_same_endpoint_total 6812
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 54
telemt_me_writer_removed_unexpected_minus_restored_total 68
telemt_user_connections_total{user="hello"} 283074
telemt_user_connections_current{user="hello"} 774
telemt_user_octets_from_client{user="hello"} 3295082844 (3.07 GB)
telemt_user_octets_to_client{user="hello"} 107031504164 (99.68 GB)
telemt_user_unique_ips_current{user="hello"} 225
telemt_user_unique_ips_recent_window{user="hello"} 119
```