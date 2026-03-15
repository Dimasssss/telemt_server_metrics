# Server Metrics 2026-03-15 09:54:33 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.18

telemt_uptime_seconds 42003.5 (11h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 967255
telemt_connections_bad_total 52043
telemt_handshake_timeouts_total 7369
telemt_upstream_connect_attempt_total 8398
telemt_upstream_connect_success_total 8361
telemt_upstream_connect_fail_total 37
telemt_upstream_connect_attempts_per_request{bucket="1"} 8398
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4390
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3953
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 18
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 37
telemt_me_keepalive_timeout_total 8
telemt_me_reconnect_attempts_total 6303
telemt_me_reconnect_success_total 6267
telemt_me_reader_eof_total 6637
telemt_me_idle_close_by_peer_total 6637
telemt_me_route_drop_no_conn_total 318527
telemt_me_route_drop_channel_closed_total 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 816721
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2889
telemt_desync_full_logged_total 844
telemt_desync_suppressed_total 2045
telemt_desync_frames_bucket_total{bucket="1_2"} 674
telemt_desync_frames_bucket_total{bucket="3_10"} 1129
telemt_desync_frames_bucket_total{bucket="gt_10"} 1086
telemt_pool_swap_total 38
telemt_me_writer_removed_unexpected_total 6358
telemt_me_writer_restored_same_endpoint_total 6256
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 296
telemt_me_writer_removed_unexpected_minus_restored_total 91
telemt_user_connections_total{user="hello"} 816735
telemt_user_connections_current{user="hello"} 2090
telemt_user_octets_from_client{user="hello"} 11852591520 (11.04 GB)
telemt_user_octets_to_client{user="hello"} 315646432088 (293.97 GB)
telemt_user_unique_ips_current{user="hello"} 563
telemt_user_unique_ips_recent_window{user="hello"} 260
```

## server2

```
telemt 3.3.18

telemt_uptime_seconds 42004.3 (11h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 381907
telemt_connections_bad_total 21386
telemt_handshake_timeouts_total 15031
telemt_upstream_connect_attempt_total 11183
telemt_upstream_connect_success_total 11125
telemt_upstream_connect_fail_total 58
telemt_upstream_connect_attempts_per_request{bucket="1"} 11183
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6028
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5005
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 27
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 65
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 58
telemt_me_keepalive_timeout_total 15
telemt_me_reconnect_attempts_total 8757
telemt_me_reconnect_success_total 8701
telemt_me_reader_eof_total 9208
telemt_me_idle_close_by_peer_total 9208
telemt_me_route_drop_no_conn_total 97006
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 302134
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 16
telemt_me_endpoint_quarantine_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1074
telemt_desync_full_logged_total 372
telemt_desync_suppressed_total 702
telemt_desync_frames_bucket_total{bucket="1_2"} 353
telemt_desync_frames_bucket_total{bucket="3_10"} 398
telemt_desync_frames_bucket_total{bucket="gt_10"} 323
telemt_pool_swap_total 39
telemt_me_writer_removed_unexpected_total 8781
telemt_me_writer_restored_same_endpoint_total 8693
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 61
telemt_me_writer_removed_unexpected_minus_restored_total 80
telemt_user_connections_total{user="hello"} 302422
telemt_user_connections_current{user="hello"} 744
telemt_user_octets_from_client{user="hello"} 4401676051 (4.10 GB)
telemt_user_octets_to_client{user="hello"} 113650968044 (105.85 GB)
telemt_user_msgs_from_client{user="hello"} 620
telemt_user_msgs_to_client{user="hello"} 1332
telemt_user_unique_ips_current{user="hello"} 223
telemt_user_unique_ips_recent_window{user="hello"} 110
```

## server3

```
telemt 3.3.18

telemt_uptime_seconds 42004.3 (11h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 696011
telemt_connections_bad_total 23365
telemt_handshake_timeouts_total 70618
telemt_upstream_connect_attempt_total 9328
telemt_upstream_connect_success_total 9288
telemt_upstream_connect_fail_total 40
telemt_upstream_connect_attempts_per_request{bucket="1"} 9328
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4852
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4385
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 51
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 40
telemt_me_reconnect_attempts_total 7225
telemt_me_reconnect_success_total 7179
telemt_me_reader_eof_total 7600
telemt_me_idle_close_by_peer_total 7600
telemt_me_route_drop_no_conn_total 200236
telemt_me_route_drop_channel_closed_total 15
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 529347
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1139
telemt_desync_full_logged_total 425
telemt_desync_suppressed_total 714
telemt_desync_frames_bucket_total{bucket="1_2"} 248
telemt_desync_frames_bucket_total{bucket="3_10"} 408
telemt_desync_frames_bucket_total{bucket="gt_10"} 483
telemt_pool_swap_total 41
telemt_me_writer_removed_unexpected_total 7268
telemt_me_writer_restored_same_endpoint_total 7160
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 242
telemt_me_writer_removed_unexpected_minus_restored_total 89
telemt_user_connections_total{user="hello"} 528775
telemt_user_connections_current{user="hello"} 1183
telemt_user_octets_from_client{user="hello"} 7898961068 (7.36 GB)
telemt_user_octets_to_client{user="hello"} 211474672876 (196.95 GB)
telemt_user_unique_ips_current{user="hello"} 340
telemt_user_unique_ips_recent_window{user="hello"} 170
```

## server4

```
telemt 3.3.18

telemt_uptime_seconds 42004.1 (11h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 401855
telemt_connections_bad_total 53668
telemt_handshake_timeouts_total 24608
telemt_upstream_connect_attempt_total 12931
telemt_upstream_connect_success_total 12616
telemt_upstream_connect_fail_total 315
telemt_upstream_connect_attempts_per_request{bucket="1"} 12931
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5934
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6679
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 315
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 29497
telemt_me_reconnect_success_total 10514
telemt_me_reader_eof_total 11421
telemt_me_idle_close_by_peer_total 11421
telemt_me_seq_mismatch_total 16
telemt_me_route_drop_no_conn_total 110438
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 301205
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 33
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 736
telemt_desync_full_logged_total 180
telemt_desync_suppressed_total 556
telemt_desync_frames_bucket_total{bucket="1_2"} 176
telemt_desync_frames_bucket_total{bucket="3_10"} 303
telemt_desync_frames_bucket_total{bucket="gt_10"} 257
telemt_pool_swap_total 16
telemt_me_writer_removed_unexpected_total 11200
telemt_me_refill_failed_total 593
telemt_me_writer_restored_same_endpoint_total 10484
telemt_me_writer_restored_fallback_total 30
telemt_me_async_recovery_trigger_total 96
telemt_me_writer_removed_unexpected_minus_restored_total 686
telemt_user_connections_total{user="hello"} 301116
telemt_user_connections_current{user="hello"} 672
telemt_user_octets_from_client{user="hello"} 3576915216 (3.33 GB)
telemt_user_octets_to_client{user="hello"} 96954808088 (90.30 GB)
telemt_user_unique_ips_current{user="hello"} 212
telemt_user_unique_ips_recent_window{user="hello"} 124
```

## server5

```
telemt 3.3.18

telemt_uptime_seconds 42005.2 (11h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 389759
telemt_connections_bad_total 4273
telemt_handshake_timeouts_total 4887
telemt_upstream_connect_attempt_total 9401
telemt_upstream_connect_success_total 9358
telemt_upstream_connect_fail_total 43
telemt_upstream_connect_attempts_per_request{bucket="1"} 9401
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4253
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5100
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 43
telemt_me_reconnect_attempts_total 7296
telemt_me_reconnect_success_total 7260
telemt_me_reader_eof_total 7717
telemt_me_idle_close_by_peer_total 7717
telemt_me_route_drop_no_conn_total 103288
telemt_me_route_drop_channel_closed_total 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 324393
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1233
telemt_desync_full_logged_total 397
telemt_desync_suppressed_total 836
telemt_desync_frames_bucket_total{bucket="1_2"} 365
telemt_desync_frames_bucket_total{bucket="3_10"} 503
telemt_desync_frames_bucket_total{bucket="gt_10"} 365
telemt_pool_swap_total 40
telemt_me_writer_removed_unexpected_total 7339
telemt_me_writer_restored_same_endpoint_total 7252
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 54
telemt_me_writer_removed_unexpected_minus_restored_total 79
telemt_user_connections_total{user="hello"} 324399
telemt_user_connections_current{user="hello"} 825
telemt_user_octets_from_client{user="hello"} 3985013976 (3.71 GB)
telemt_user_octets_to_client{user="hello"} 119135984980 (110.95 GB)
telemt_user_unique_ips_current{user="hello"} 226
telemt_user_unique_ips_recent_window{user="hello"} 121
```