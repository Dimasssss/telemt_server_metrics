# Server Metrics 2026-03-14 12:22:58 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 195858.6 (54h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5681506
telemt_connections_bad_total 60721
telemt_handshake_timeouts_total 125315
telemt_upstream_connect_attempt_total 41108
telemt_upstream_connect_success_total 40845
telemt_upstream_connect_fail_total 263
telemt_upstream_connect_attempts_per_request{bucket="1"} 41108
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 22116
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18569
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 160
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 263
telemt_me_keepalive_timeout_total 7848
telemt_me_reconnect_attempts_total 45142
telemt_me_reconnect_success_total 28765
telemt_me_reader_eof_total 30943
telemt_me_idle_close_by_peer_total 30942
telemt_me_route_drop_no_conn_total 2152685
telemt_me_route_drop_channel_closed_total 31
telemt_me_route_drop_queue_full_total 6
telemt_me_route_drop_queue_full_profile_total{profile="high"} 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5211371
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 20122
telemt_desync_full_logged_total 5504
telemt_desync_suppressed_total 14618
telemt_desync_frames_bucket_total{bucket="1_2"} 4861
telemt_desync_frames_bucket_total{bucket="3_10"} 7657
telemt_desync_frames_bucket_total{bucket="gt_10"} 7604
telemt_pool_swap_total 164
telemt_me_writer_removed_unexpected_total 29693
telemt_me_refill_failed_total 506
telemt_me_writer_restored_same_endpoint_total 28752
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 928
telemt_user_connections_total{user="hello"} 5212944
telemt_user_connections_current{user="hello"} 1757
telemt_user_octets_from_client{user="hello"} 80960718628 (75.40 GB)
telemt_user_octets_to_client{user="hello"} 1658847470505 (1.51 TB)
telemt_user_msgs_from_client{user="hello"} 5023
telemt_user_msgs_to_client{user="hello"} 14147
telemt_user_unique_ips_current{user="hello"} 480
telemt_user_unique_ips_recent_window{user="hello"} 212
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 95522.3 (26h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1100239
telemt_connections_bad_total 58954
telemt_handshake_timeouts_total 25641
telemt_upstream_connect_attempt_total 24597
telemt_upstream_connect_success_total 24290
telemt_upstream_connect_fail_total 307
telemt_upstream_connect_attempts_per_request{bucket="1"} 24597
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13224
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10754
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 48
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 264
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 307
telemt_me_keepalive_timeout_total 2407
telemt_me_reconnect_attempts_total 35426
telemt_me_reconnect_success_total 17480
telemt_me_reader_eof_total 18931
telemt_me_idle_close_by_peer_total 18930
telemt_me_route_drop_no_conn_total 372726
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 907551
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 6
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2523
telemt_desync_full_logged_total 793
telemt_desync_suppressed_total 1730
telemt_desync_frames_bucket_total{bucket="1_2"} 652
telemt_desync_frames_bucket_total{bucket="3_10"} 1049
telemt_desync_frames_bucket_total{bucket="gt_10"} 822
telemt_pool_swap_total 73
telemt_me_writer_removed_unexpected_total 18287
telemt_me_refill_failed_total 554
telemt_me_writer_restored_same_endpoint_total 17472
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 600
telemt_me_writer_removed_unexpected_minus_restored_total 807
telemt_user_connections_total{user="hello"} 909463
telemt_user_connections_current{user="hello"} 662
telemt_user_octets_from_client{user="hello"} 9916014069 (9.24 GB)
telemt_user_octets_to_client{user="hello"} 321409883644 (299.34 GB)
telemt_user_msgs_from_client{user="hello"} 6384
telemt_user_msgs_to_client{user="hello"} 14733
telemt_user_unique_ips_current{user="hello"} 208
telemt_user_unique_ips_recent_window{user="hello"} 98
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 225478.9 (62h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4032037
telemt_connections_bad_total 46493
telemt_handshake_timeouts_total 277990
telemt_upstream_connect_attempt_total 50751
telemt_upstream_connect_success_total 50730
telemt_upstream_connect_fail_total 21
telemt_upstream_connect_attempts_per_request{bucket="1"} 50751
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 26764
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 23700
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 259
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 21
telemt_me_keepalive_timeout_total 11272
telemt_me_reconnect_attempts_total 45181
telemt_me_reconnect_success_total 39179
telemt_me_reader_eof_total 41617
telemt_me_idle_close_by_peer_total 41615
telemt_me_route_drop_no_conn_total 1385027
telemt_me_route_drop_channel_closed_total 22
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3371605
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 10815
telemt_desync_full_logged_total 3651
telemt_desync_suppressed_total 7164
telemt_desync_frames_bucket_total{bucket="1_2"} 1976
telemt_desync_frames_bucket_total{bucket="3_10"} 3903
telemt_desync_frames_bucket_total{bucket="gt_10"} 4936
telemt_pool_swap_total 209
telemt_pool_stale_pick_total 5
telemt_me_writer_removed_unexpected_total 39758
telemt_me_refill_failed_total 180
telemt_me_writer_restored_same_endpoint_total 39138
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 579
telemt_user_connections_total{user="hello"} 3370745
telemt_user_connections_current{user="hello"} 978
telemt_user_octets_from_client{user="hello"} 57633224992 (53.68 GB)
telemt_user_octets_to_client{user="hello"} 1202227964965 (1.09 TB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 280
telemt_user_unique_ips_recent_window{user="hello"} 136
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 225481.6 (62h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2632216
telemt_connections_bad_total 23512
telemt_handshake_timeouts_total 340044
telemt_upstream_connect_attempt_total 69546
telemt_upstream_connect_success_total 67037
telemt_upstream_connect_fail_total 2372
telemt_upstream_connect_attempts_per_request{bucket="1"} 69272
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 39900
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 26971
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 166
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2371
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 20964
telemt_me_reconnect_attempts_total 61563
telemt_me_reconnect_success_total 48780
telemt_me_reader_eof_total 52261
telemt_me_idle_close_by_peer_total 52253
telemt_me_route_drop_no_conn_total 874098
telemt_me_route_drop_channel_closed_total 7
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2057230
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4117
telemt_desync_full_logged_total 1355
telemt_desync_suppressed_total 2762
telemt_desync_frames_bucket_total{bucket="1_2"} 1171
telemt_desync_frames_bucket_total{bucket="3_10"} 1683
telemt_desync_frames_bucket_total{bucket="gt_10"} 1263
telemt_pool_swap_total 193
telemt_me_writer_removed_unexpected_total 49605
telemt_me_refill_failed_total 389
telemt_me_writer_restored_same_endpoint_total 48755
telemt_me_writer_restored_fallback_total 25
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 825
telemt_user_connections_total{user="hello"} 2063689
telemt_user_connections_current{user="hello"} 430
telemt_user_octets_from_client{user="hello"} 30519414747 (28.42 GB)
telemt_user_octets_to_client{user="hello"} 734171814214 (683.75 GB)
telemt_user_msgs_from_client{user="hello"} 50957
telemt_user_msgs_to_client{user="hello"} 129867
telemt_user_unique_ips_current{user="hello"} 129
telemt_user_unique_ips_recent_window{user="hello"} 67
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 94915.2 (26h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1086532
telemt_connections_bad_total 18123
telemt_handshake_timeouts_total 13950
telemt_upstream_connect_attempt_total 22938
telemt_upstream_connect_success_total 22293
telemt_upstream_connect_fail_total 645
telemt_upstream_connect_attempts_per_request{bucket="1"} 22938
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10692
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11575
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 26
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 645
telemt_me_keepalive_timeout_total 1796
telemt_me_reconnect_attempts_total 85344
telemt_me_reconnect_success_total 17554
telemt_me_reader_eof_total 20080
telemt_me_idle_close_by_peer_total 20079
telemt_me_route_drop_no_conn_total 439091
telemt_me_route_drop_channel_closed_total 20
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1006674
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 3
telemt_me_hardswap_pending_ttl_expired_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2701
telemt_desync_full_logged_total 845
telemt_desync_suppressed_total 1856
telemt_desync_frames_bucket_total{bucket="1_2"} 976
telemt_desync_frames_bucket_total{bucket="3_10"} 948
telemt_desync_frames_bucket_total{bucket="gt_10"} 777
telemt_pool_swap_total 24
telemt_me_writer_removed_unexpected_total 19831
telemt_me_refill_failed_total 2113
telemt_me_writer_restored_same_endpoint_total 17549
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 2277
telemt_user_connections_total{user="hello"} 1005873
telemt_user_connections_current{user="hello"} 773
telemt_user_octets_from_client{user="hello"} 17381829376 (16.19 GB)
telemt_user_octets_to_client{user="hello"} 338795833916 (315.53 GB)
telemt_user_unique_ips_current{user="hello"} 204
telemt_user_unique_ips_recent_window{user="hello"} 87
```