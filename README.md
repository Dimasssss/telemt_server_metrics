# Server Metrics 2026-03-11 14:15:46 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 85720.1 (23h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2058216
telemt_connections_bad_total 30198
telemt_handshake_timeouts_total 52000
telemt_upstream_connect_attempt_total 18067
telemt_upstream_connect_success_total 18056
telemt_upstream_connect_fail_total 11
telemt_upstream_connect_attempts_per_request{bucket="1"} 18067
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9134
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8836
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 85
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 11
telemt_me_keepalive_timeout_total 4451
telemt_me_reconnect_attempts_total 26989
telemt_me_reconnect_success_total 13702
telemt_me_reader_eof_total 14769
telemt_me_idle_close_by_peer_total 14769
telemt_me_route_drop_no_conn_total 759045
telemt_me_route_drop_channel_closed_total 7
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1882060
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 9904
telemt_desync_full_logged_total 2681
telemt_desync_suppressed_total 7223
telemt_desync_frames_bucket_total{bucket="1_2"} 2456
telemt_desync_frames_bucket_total{bucket="3_10"} 3833
telemt_desync_frames_bucket_total{bucket="gt_10"} 3615
telemt_pool_swap_total 64
telemt_me_writer_removed_unexpected_total 14266
telemt_me_refill_failed_total 412
telemt_me_writer_restored_same_endpoint_total 13696
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 564
telemt_user_connections_total{user="hello"} 1880574
telemt_user_connections_current{user="hello"} 1672
telemt_user_octets_from_client{user="hello"} 25306616048 (23.57 GB)
telemt_user_octets_to_client{user="hello"} 536497403404 (499.65 GB)
telemt_user_unique_ips_current{user="hello"} 419
telemt_user_unique_ips_recent_window{user="hello"} 270
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 85776.9 (23h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 773320
telemt_connections_bad_total 13164
telemt_handshake_timeouts_total 52331
telemt_upstream_connect_attempt_total 27555
telemt_upstream_connect_success_total 24606
telemt_upstream_connect_fail_total 2949
telemt_upstream_connect_attempts_per_request{bucket="1"} 27555
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11380
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10978
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 209
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2039
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2949
telemt_me_keepalive_timeout_total 2522
telemt_me_reconnect_attempts_total 19427
telemt_me_reconnect_success_total 17341
telemt_me_reader_eof_total 18366
telemt_me_idle_close_by_peer_total 18363
telemt_me_route_drop_no_conn_total 302694
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 654632
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2819
telemt_desync_full_logged_total 893
telemt_desync_suppressed_total 1926
telemt_desync_frames_bucket_total{bucket="1_2"} 874
telemt_desync_frames_bucket_total{bucket="3_10"} 1025
telemt_desync_frames_bucket_total{bucket="gt_10"} 920
telemt_pool_swap_total 70
telemt_me_writer_removed_unexpected_total 17596
telemt_me_refill_failed_total 60
telemt_me_writer_restored_same_endpoint_total 17318
telemt_me_writer_restored_fallback_total 23
telemt_me_async_recovery_trigger_total 86
telemt_me_writer_removed_unexpected_minus_restored_total 255
telemt_user_connections_total{user="hello"} 657119
telemt_user_connections_current{user="hello"} 545
telemt_user_octets_from_client{user="hello"} 6984223522 (6.50 GB)
telemt_user_octets_to_client{user="hello"} 185944305732 (173.17 GB)
telemt_user_msgs_from_client{user="hello"} 7933
telemt_user_msgs_to_client{user="hello"} 11226
telemt_user_unique_ips_current{user="hello"} 154
telemt_user_unique_ips_recent_window{user="hello"} 100
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 85776.7 (23h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1339528
telemt_connections_bad_total 8443
telemt_handshake_timeouts_total 121530
telemt_upstream_connect_attempt_total 22858
telemt_upstream_connect_success_total 22586
telemt_upstream_connect_fail_total 272
telemt_upstream_connect_attempts_per_request{bucket="1"} 22858
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12218
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10257
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 111
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 272
telemt_me_keepalive_timeout_total 903
telemt_me_reconnect_attempts_total 33287
telemt_me_reconnect_success_total 17177
telemt_me_reader_eof_total 18469
telemt_me_idle_close_by_peer_total 18469
telemt_me_route_drop_no_conn_total 482929
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1159238
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3103
telemt_desync_full_logged_total 914
telemt_desync_suppressed_total 2189
telemt_desync_frames_bucket_total{bucket="1_2"} 754
telemt_desync_frames_bucket_total{bucket="3_10"} 1178
telemt_desync_frames_bucket_total{bucket="gt_10"} 1171
telemt_pool_swap_total 53
telemt_me_writer_removed_unexpected_total 17909
telemt_me_refill_failed_total 499
telemt_me_writer_restored_same_endpoint_total 17166
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 732
telemt_user_connections_total{user="hello"} 1159041
telemt_user_connections_current{user="hello"} 786
telemt_user_octets_from_client{user="hello"} 13949795193 (12.99 GB)
telemt_user_octets_to_client{user="hello"} 345828335561 (322.08 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 244
telemt_user_unique_ips_recent_window{user="hello"} 164
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 85777.2 (23h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 961210
telemt_connections_bad_total 77288
telemt_handshake_timeouts_total 90689
telemt_upstream_connect_attempt_total 23251
telemt_upstream_connect_success_total 23251
telemt_upstream_connect_attempts_per_request{bucket="1"} 23251
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12726
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10520
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 951
telemt_me_reconnect_attempts_total 20025
telemt_me_reconnect_success_total 18954
telemt_me_reader_eof_total 20103
telemt_me_idle_close_by_peer_total 20102
telemt_me_seq_mismatch_total 17
telemt_me_route_drop_no_conn_total 312075
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 767152
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 28
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1624
telemt_desync_full_logged_total 636
telemt_desync_suppressed_total 988
telemt_desync_frames_bucket_total{bucket="1_2"} 590
telemt_desync_frames_bucket_total{bucket="3_10"} 569
telemt_desync_frames_bucket_total{bucket="gt_10"} 465
telemt_pool_swap_total 75
telemt_me_writer_removed_unexpected_total 19188
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 18926
telemt_me_writer_restored_fallback_total 28
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 234
telemt_user_connections_total{user="hello"} 766495
telemt_user_connections_current{user="hello"} 626
telemt_user_octets_from_client{user="hello"} 9002377096 (8.38 GB)
telemt_user_octets_to_client{user="hello"} 222012872444 (206.77 GB)
telemt_user_unique_ips_current{user="hello"} 171
telemt_user_unique_ips_recent_window{user="hello"} 125
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 85776.9 (23h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1055414
telemt_connections_bad_total 6936
telemt_handshake_timeouts_total 9917
telemt_upstream_connect_attempt_total 23229
telemt_upstream_connect_success_total 23129
telemt_upstream_connect_fail_total 100
telemt_upstream_connect_attempts_per_request{bucket="1"} 23229
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11860
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11079
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 186
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 100
telemt_me_keepalive_timeout_total 989
telemt_me_reconnect_attempts_total 22777
telemt_me_reconnect_success_total 18703
telemt_me_reader_eof_total 19735
telemt_me_idle_close_by_peer_total 19735
telemt_me_route_drop_no_conn_total 374627
telemt_me_route_drop_channel_closed_total 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 958606
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 3781
telemt_desync_full_logged_total 1391
telemt_desync_suppressed_total 2390
telemt_desync_frames_bucket_total{bucket="1_2"} 1323
telemt_desync_frames_bucket_total{bucket="3_10"} 1422
telemt_desync_frames_bucket_total{bucket="gt_10"} 1036
telemt_pool_swap_total 58
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 19071
telemt_me_refill_failed_total 124
telemt_me_writer_restored_same_endpoint_total 18703
telemt_me_async_recovery_trigger_total 48
telemt_me_writer_removed_unexpected_minus_restored_total 368
telemt_user_connections_total{user="hello"} 958342
telemt_user_connections_current{user="hello"} 742
telemt_user_octets_from_client{user="hello"} 13844532183 (12.89 GB)
telemt_user_octets_to_client{user="hello"} 338164418906 (314.94 GB)
telemt_user_msgs_from_client{user="hello"} 122
telemt_user_msgs_to_client{user="hello"} 215
telemt_user_unique_ips_current{user="hello"} 217
telemt_user_unique_ips_recent_window{user="hello"} 149
```