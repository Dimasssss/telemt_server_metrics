# Server Metrics 2026-03-12 22:34:56 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 59775.8 (16h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1922066
telemt_connections_bad_total 26062
telemt_handshake_timeouts_total 21048
telemt_upstream_connect_attempt_total 11805
telemt_upstream_connect_success_total 11737
telemt_upstream_connect_fail_total 68
telemt_upstream_connect_attempts_per_request{bucket="1"} 11805
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6117
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5583
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 37
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 68
telemt_me_keepalive_timeout_total 600
telemt_me_reconnect_attempts_total 17576
telemt_me_reconnect_success_total 8720
telemt_me_reader_eof_total 9424
telemt_me_idle_close_by_peer_total 9423
telemt_me_route_drop_no_conn_total 750934
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1788342
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8496
telemt_desync_full_logged_total 2214
telemt_desync_suppressed_total 6282
telemt_desync_frames_bucket_total{bucket="1_2"} 2237
telemt_desync_frames_bucket_total{bucket="3_10"} 3058
telemt_desync_frames_bucket_total{bucket="gt_10"} 3201
telemt_pool_swap_total 42
telemt_me_writer_removed_unexpected_total 9121
telemt_me_refill_failed_total 275
telemt_me_writer_restored_same_endpoint_total 8707
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 401
telemt_user_connections_total{user="hello"} 1787815
telemt_user_connections_current{user="hello"} 625
telemt_user_octets_from_client{user="hello"} 26959298100 (25.11 GB)
telemt_user_octets_to_client{user="hello"} 637023661556 (593.27 GB)
telemt_user_unique_ips_current{user="hello"} 217
telemt_user_unique_ips_recent_window{user="hello"} 77
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 89396.2 (24h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 796394
telemt_connections_bad_total 11706
telemt_handshake_timeouts_total 31315
telemt_upstream_connect_attempt_total 22619
telemt_upstream_connect_success_total 22589
telemt_upstream_connect_fail_total 29
telemt_upstream_connect_attempts_per_request{bucket="1"} 22618
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11878
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10622
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 89
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 29
telemt_me_keepalive_timeout_total 3412
telemt_me_reconnect_attempts_total 16561
telemt_me_reconnect_success_total 16465
telemt_me_reader_eof_total 17527
telemt_me_idle_close_by_peer_total 17527
telemt_me_route_drop_no_conn_total 257682
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 719451
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3001
telemt_desync_full_logged_total 933
telemt_desync_suppressed_total 2068
telemt_desync_frames_bucket_total{bucket="1_2"} 1188
telemt_desync_frames_bucket_total{bucket="3_10"} 986
telemt_desync_frames_bucket_total{bucket="gt_10"} 827
telemt_pool_swap_total 90
telemt_me_writer_removed_unexpected_total 16633
telemt_me_writer_restored_same_endpoint_total 16456
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 168
telemt_user_connections_total{user="hello"} 721331
telemt_user_connections_current{user="hello"} 213
telemt_user_octets_from_client{user="hello"} 12072088464 (11.24 GB)
telemt_user_octets_to_client{user="hello"} 279184667503 (260.01 GB)
telemt_user_msgs_from_client{user="hello"} 6476
telemt_user_msgs_to_client{user="hello"} 18854
telemt_user_unique_ips_current{user="hello"} 78
telemt_user_unique_ips_recent_window{user="hello"} 41
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 89396.0 (24h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1656667
telemt_connections_bad_total 7866
telemt_handshake_timeouts_total 113283
telemt_upstream_connect_attempt_total 20839
telemt_upstream_connect_success_total 20833
telemt_upstream_connect_fail_total 6
telemt_upstream_connect_attempts_per_request{bucket="1"} 20839
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11152
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9604
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 72
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 6
telemt_me_keepalive_timeout_total 1222
telemt_me_reconnect_attempts_total 17250
telemt_me_reconnect_success_total 16000
telemt_me_reader_eof_total 16913
telemt_me_idle_close_by_peer_total 16912
telemt_me_route_drop_no_conn_total 544747
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1290258
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4968
telemt_desync_full_logged_total 1524
telemt_desync_suppressed_total 3444
telemt_desync_frames_bucket_total{bucket="1_2"} 790
telemt_desync_frames_bucket_total{bucket="3_10"} 1796
telemt_desync_frames_bucket_total{bucket="gt_10"} 2382
telemt_pool_swap_total 82
telemt_me_writer_removed_unexpected_total 16152
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 15959
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 152
telemt_user_connections_total{user="hello"} 1289864
telemt_user_connections_current{user="hello"} 373
telemt_user_octets_from_client{user="hello"} 19722270816 (18.37 GB)
telemt_user_octets_to_client{user="hello"} 475720486089 (443.05 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 128
telemt_user_unique_ips_recent_window{user="hello"} 56
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 89396.5 (24h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1020412
telemt_connections_bad_total 13002
telemt_handshake_timeouts_total 71421
telemt_upstream_connect_attempt_total 22897
telemt_upstream_connect_success_total 22804
telemt_upstream_connect_fail_total 93
telemt_upstream_connect_attempts_per_request{bucket="1"} 22897
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12824
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9966
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 14
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 93
telemt_me_keepalive_timeout_total 1691
telemt_me_reconnect_attempts_total 26064
telemt_me_reconnect_success_total 18333
telemt_me_reader_eof_total 19590
telemt_me_idle_close_by_peer_total 19590
telemt_me_route_drop_no_conn_total 365160
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 889252
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1852
telemt_desync_full_logged_total 613
telemt_desync_suppressed_total 1239
telemt_desync_frames_bucket_total{bucket="1_2"} 514
telemt_desync_frames_bucket_total{bucket="3_10"} 722
telemt_desync_frames_bucket_total{bucket="gt_10"} 616
telemt_pool_swap_total 76
telemt_me_writer_removed_unexpected_total 18720
telemt_me_refill_failed_total 239
telemt_me_writer_restored_same_endpoint_total 18312
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 108
telemt_me_writer_removed_unexpected_minus_restored_total 387
telemt_user_connections_total{user="hello"} 888598
telemt_user_connections_current{user="hello"} 255
telemt_user_octets_from_client{user="hello"} 14211245000 (13.24 GB)
telemt_user_octets_to_client{user="hello"} 354559415708 (330.21 GB)
telemt_user_unique_ips_current{user="hello"} 96
telemt_user_unique_ips_recent_window{user="hello"} 39
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 89396.3 (24h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1141422
telemt_connections_bad_total 12536
telemt_handshake_timeouts_total 9205
telemt_upstream_connect_attempt_total 27378
telemt_upstream_connect_success_total 27036
telemt_upstream_connect_fail_total 342
telemt_upstream_connect_attempts_per_request{bucket="1"} 27378
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13827
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13058
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 11
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 140
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 342
telemt_me_keepalive_timeout_total 1445
telemt_me_reconnect_attempts_total 33592
telemt_me_reconnect_success_total 22552
telemt_me_reader_eof_total 23717
telemt_me_idle_close_by_peer_total 23717
telemt_me_seq_mismatch_total 33
telemt_me_route_drop_no_conn_total 426929
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1051030
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 37
telemt_me_hardswap_pending_ttl_expired_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 3937
telemt_desync_full_logged_total 1371
telemt_desync_suppressed_total 2566
telemt_desync_frames_bucket_total{bucket="1_2"} 1155
telemt_desync_frames_bucket_total{bucket="3_10"} 1298
telemt_desync_frames_bucket_total{bucket="gt_10"} 1484
telemt_pool_swap_total 45
telemt_me_writer_removed_unexpected_total 23158
telemt_me_refill_failed_total 342
telemt_me_writer_restored_same_endpoint_total 22508
telemt_me_writer_restored_fallback_total 44
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 606
telemt_user_connections_total{user="hello"} 1050889
telemt_user_connections_current{user="hello"} 267
telemt_user_octets_from_client{user="hello"} 12875452640 (11.99 GB)
telemt_user_octets_to_client{user="hello"} 373404569520 (347.76 GB)
telemt_user_unique_ips_current{user="hello"} 97
telemt_user_unique_ips_recent_window{user="hello"} 35
```