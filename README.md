# Server Metrics 2026-03-15 08:27:43 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.18

telemt_uptime_seconds 36793.4 (10h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 731083
telemt_connections_bad_total 29192
telemt_handshake_timeouts_total 5047
telemt_upstream_connect_attempt_total 7576
telemt_upstream_connect_success_total 7547
telemt_upstream_connect_fail_total 29
telemt_upstream_connect_attempts_per_request{bucket="1"} 7576
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3954
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3579
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 14
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 29
telemt_me_keepalive_timeout_total 8
telemt_me_reconnect_attempts_total 5749
telemt_me_reconnect_success_total 5718
telemt_me_reader_eof_total 6048
telemt_me_idle_close_by_peer_total 6048
telemt_me_route_drop_no_conn_total 235490
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 620018
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1837
telemt_desync_full_logged_total 573
telemt_desync_suppressed_total 1264
telemt_desync_frames_bucket_total{bucket="1_2"} 396
telemt_desync_frames_bucket_total{bucket="3_10"} 671
telemt_desync_frames_bucket_total{bucket="gt_10"} 770
telemt_pool_swap_total 33
telemt_me_writer_removed_unexpected_total 5794
telemt_me_writer_restored_same_endpoint_total 5707
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 296
telemt_me_writer_removed_unexpected_minus_restored_total 76
telemt_user_connections_total{user="hello"} 620018
telemt_user_connections_current{user="hello"} 1952
telemt_user_octets_from_client{user="hello"} 8059699276 (7.51 GB)
telemt_user_octets_to_client{user="hello"} 231596930120 (215.69 GB)
telemt_user_unique_ips_current{user="hello"} 538
telemt_user_unique_ips_recent_window{user="hello"} 268
```

## server2

```
telemt 3.3.18

telemt_uptime_seconds 36794.3 (10h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 286465
telemt_connections_bad_total 18438
telemt_handshake_timeouts_total 11804
telemt_upstream_connect_attempt_total 9922
telemt_upstream_connect_success_total 9873
telemt_upstream_connect_fail_total 49
telemt_upstream_connect_attempts_per_request{bucket="1"} 9922
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5355
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4439
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 23
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 56
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 49
telemt_me_keepalive_timeout_total 15
telemt_me_reconnect_attempts_total 7770
telemt_me_reconnect_success_total 7723
telemt_me_reader_eof_total 8186
telemt_me_idle_close_by_peer_total 8186
telemt_me_route_drop_no_conn_total 71916
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 226123
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 16
telemt_me_endpoint_quarantine_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 840
telemt_desync_full_logged_total 279
telemt_desync_suppressed_total 561
telemt_desync_frames_bucket_total{bucket="1_2"} 241
telemt_desync_frames_bucket_total{bucket="3_10"} 328
telemt_desync_frames_bucket_total{bucket="gt_10"} 271
telemt_pool_swap_total 37
telemt_me_writer_removed_unexpected_total 7779
telemt_me_writer_restored_same_endpoint_total 7715
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 61
telemt_me_writer_removed_unexpected_minus_restored_total 56
telemt_user_connections_total{user="hello"} 226401
telemt_user_connections_current{user="hello"} 735
telemt_user_octets_from_client{user="hello"} 3355973159 (3.13 GB)
telemt_user_octets_to_client{user="hello"} 83706997048 (77.96 GB)
telemt_user_msgs_from_client{user="hello"} 620
telemt_user_msgs_to_client{user="hello"} 1332
telemt_user_unique_ips_current{user="hello"} 224
telemt_user_unique_ips_recent_window{user="hello"} 104
```

## server3

```
telemt 3.3.18

telemt_uptime_seconds 36794.3 (10h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 494238
telemt_connections_bad_total 14823
telemt_handshake_timeouts_total 43956
telemt_upstream_connect_attempt_total 8205
telemt_upstream_connect_success_total 8168
telemt_upstream_connect_fail_total 37
telemt_upstream_connect_attempts_per_request{bucket="1"} 8205
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4310
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3810
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 48
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 37
telemt_me_reconnect_attempts_total 6370
telemt_me_reconnect_success_total 6330
telemt_me_reader_eof_total 6706
telemt_me_idle_close_by_peer_total 6706
telemt_me_route_drop_no_conn_total 133641
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 400126
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 781
telemt_desync_full_logged_total 304
telemt_desync_suppressed_total 477
telemt_desync_frames_bucket_total{bucket="1_2"} 183
telemt_desync_frames_bucket_total{bucket="3_10"} 269
telemt_desync_frames_bucket_total{bucket="gt_10"} 329
telemt_pool_swap_total 37
telemt_me_writer_removed_unexpected_total 6409
telemt_me_writer_restored_same_endpoint_total 6311
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 242
telemt_me_writer_removed_unexpected_minus_restored_total 79
telemt_user_connections_total{user="hello"} 399666
telemt_user_connections_current{user="hello"} 1109
telemt_user_octets_from_client{user="hello"} 5960545072 (5.55 GB)
telemt_user_octets_to_client{user="hello"} 168459770404 (156.89 GB)
telemt_user_unique_ips_current{user="hello"} 313
telemt_user_unique_ips_recent_window{user="hello"} 155
```

## server4

```
telemt 3.3.18

telemt_uptime_seconds 36794.1 (10h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 314542
telemt_connections_bad_total 48032
telemt_handshake_timeouts_total 21550
telemt_upstream_connect_attempt_total 11715
telemt_upstream_connect_success_total 11445
telemt_upstream_connect_fail_total 270
telemt_upstream_connect_attempts_per_request{bucket="1"} 11715
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5374
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6068
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 270
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 22257
telemt_me_reconnect_success_total 9616
telemt_me_reader_eof_total 10314
telemt_me_idle_close_by_peer_total 10314
telemt_me_seq_mismatch_total 13
telemt_me_route_drop_no_conn_total 82712
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 234599
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 30
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 495
telemt_desync_full_logged_total 129
telemt_desync_suppressed_total 366
telemt_desync_frames_bucket_total{bucket="1_2"} 116
telemt_desync_frames_bucket_total{bucket="3_10"} 218
telemt_desync_frames_bucket_total{bucket="gt_10"} 161
telemt_pool_swap_total 16
telemt_me_writer_removed_unexpected_total 10090
telemt_me_refill_failed_total 394
telemt_me_writer_restored_same_endpoint_total 9587
telemt_me_writer_restored_fallback_total 29
telemt_me_async_recovery_trigger_total 96
telemt_me_writer_removed_unexpected_minus_restored_total 474
telemt_user_connections_total{user="hello"} 234611
telemt_user_connections_current{user="hello"} 618
telemt_user_octets_from_client{user="hello"} 2058117060 (1.92 GB)
telemt_user_octets_to_client{user="hello"} 78008821492 (72.65 GB)
telemt_user_unique_ips_current{user="hello"} 204
telemt_user_unique_ips_recent_window{user="hello"} 102
```

## server5

```
telemt 3.3.18

telemt_uptime_seconds 36795.2 (10h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 270454
telemt_connections_bad_total 3627
telemt_handshake_timeouts_total 2699
telemt_upstream_connect_attempt_total 8144
telemt_upstream_connect_success_total 8111
telemt_upstream_connect_fail_total 33
telemt_upstream_connect_attempts_per_request{bucket="1"} 8144
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3639
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4467
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 33
telemt_me_reconnect_attempts_total 6315
telemt_me_reconnect_success_total 6286
telemt_me_reader_eof_total 6696
telemt_me_idle_close_by_peer_total 6696
telemt_me_route_drop_no_conn_total 77460
telemt_me_route_drop_channel_closed_total 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 239765
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 967
telemt_desync_full_logged_total 313
telemt_desync_suppressed_total 654
telemt_desync_frames_bucket_total{bucket="1_2"} 297
telemt_desync_frames_bucket_total{bucket="3_10"} 393
telemt_desync_frames_bucket_total{bucket="gt_10"} 277
telemt_pool_swap_total 38
telemt_me_writer_removed_unexpected_total 6348
telemt_me_writer_restored_same_endpoint_total 6278
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 54
telemt_me_writer_removed_unexpected_minus_restored_total 62
telemt_user_connections_total{user="hello"} 239777
telemt_user_connections_current{user="hello"} 787
telemt_user_octets_from_client{user="hello"} 2569817564 (2.39 GB)
telemt_user_octets_to_client{user="hello"} 94476027116 (87.99 GB)
telemt_user_unique_ips_current{user="hello"} 209
telemt_user_unique_ips_recent_window{user="hello"} 96
```