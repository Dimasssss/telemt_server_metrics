# Server Metrics 2026-03-11 18:31:07 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 101042.4 (28h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2562285
telemt_connections_bad_total 48538
telemt_handshake_timeouts_total 56556
telemt_upstream_connect_attempt_total 21358
telemt_upstream_connect_success_total 21346
telemt_upstream_connect_fail_total 12
telemt_upstream_connect_attempts_per_request{bucket="1"} 21358
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10788
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10453
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 104
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 12
telemt_me_keepalive_timeout_total 5295
telemt_me_reconnect_attempts_total 34098
telemt_me_reconnect_success_total 16217
telemt_me_reader_eof_total 17545
telemt_me_idle_close_by_peer_total 17545
telemt_me_route_drop_no_conn_total 957510
telemt_me_route_drop_channel_closed_total 9
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2343766
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 11922
telemt_desync_full_logged_total 3288
telemt_desync_suppressed_total 8634
telemt_desync_frames_bucket_total{bucket="1_2"} 2939
telemt_desync_frames_bucket_total{bucket="3_10"} 4604
telemt_desync_frames_bucket_total{bucket="gt_10"} 4379
telemt_pool_swap_total 73
telemt_me_writer_removed_unexpected_total 16955
telemt_me_refill_failed_total 555
telemt_me_writer_restored_same_endpoint_total 16211
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 738
telemt_user_connections_total{user="hello"} 2342209
telemt_user_connections_current{user="hello"} 1262
telemt_user_octets_from_client{user="hello"} 34942357540 (32.54 GB)
telemt_user_octets_to_client{user="hello"} 664028452056 (618.42 GB)
telemt_user_unique_ips_current{user="hello"} 350
telemt_user_unique_ips_recent_window{user="hello"} 165
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 101098.0 (28h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 959134
telemt_connections_bad_total 16370
telemt_handshake_timeouts_total 85187
telemt_upstream_connect_attempt_total 31408
telemt_upstream_connect_success_total 28441
telemt_upstream_connect_fail_total 2967
telemt_upstream_connect_attempts_per_request{bucket="1"} 31408
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13398
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12788
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 209
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2046
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2967
telemt_me_keepalive_timeout_total 2823
telemt_me_reconnect_attempts_total 22506
telemt_me_reconnect_success_total 20396
telemt_me_reader_eof_total 21593
telemt_me_idle_close_by_peer_total 21590
telemt_me_route_drop_no_conn_total 362426
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 799940
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3145
telemt_desync_full_logged_total 1016
telemt_desync_suppressed_total 2129
telemt_desync_frames_bucket_total{bucket="1_2"} 982
telemt_desync_frames_bucket_total{bucket="3_10"} 1120
telemt_desync_frames_bucket_total{bucket="gt_10"} 1043
telemt_pool_swap_total 82
telemt_me_writer_removed_unexpected_total 20681
telemt_me_refill_failed_total 60
telemt_me_writer_restored_same_endpoint_total 20373
telemt_me_writer_restored_fallback_total 23
telemt_me_async_recovery_trigger_total 86
telemt_me_writer_removed_unexpected_minus_restored_total 285
telemt_user_connections_total{user="hello"} 802402
telemt_user_connections_current{user="hello"} 392
telemt_user_octets_from_client{user="hello"} 9712349266 (9.05 GB)
telemt_user_octets_to_client{user="hello"} 230815940152 (214.96 GB)
telemt_user_msgs_from_client{user="hello"} 7933
telemt_user_msgs_to_client{user="hello"} 11226
telemt_user_unique_ips_current{user="hello"} 129
telemt_user_unique_ips_recent_window{user="hello"} 61
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 101098.0 (28h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1649191
telemt_connections_bad_total 10392
telemt_handshake_timeouts_total 133256
telemt_upstream_connect_attempt_total 26267
telemt_upstream_connect_success_total 25939
telemt_upstream_connect_fail_total 328
telemt_upstream_connect_attempts_per_request{bucket="1"} 26267
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13979
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11827
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 132
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 328
telemt_me_keepalive_timeout_total 1954
telemt_me_reconnect_attempts_total 46771
telemt_me_reconnect_success_total 19740
telemt_me_reader_eof_total 21439
telemt_me_idle_close_by_peer_total 21439
telemt_me_route_drop_no_conn_total 599515
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1442760
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 10
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3969
telemt_desync_full_logged_total 1159
telemt_desync_suppressed_total 2810
telemt_desync_frames_bucket_total{bucket="1_2"} 933
telemt_desync_frames_bucket_total{bucket="3_10"} 1507
telemt_desync_frames_bucket_total{bucket="gt_10"} 1529
telemt_pool_swap_total 55
telemt_me_writer_removed_unexpected_total 20859
telemt_me_refill_failed_total 839
telemt_me_writer_restored_same_endpoint_total 19728
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 1119
telemt_user_connections_total{user="hello"} 1442434
telemt_user_connections_current{user="hello"} 802
telemt_user_octets_from_client{user="hello"} 17947610269 (16.72 GB)
telemt_user_octets_to_client{user="hello"} 439675473073 (409.48 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 234
telemt_user_unique_ips_recent_window{user="hello"} 124
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 101098.5 (28h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1174720
telemt_connections_bad_total 78192
telemt_handshake_timeouts_total 109308
telemt_upstream_connect_attempt_total 27245
telemt_upstream_connect_success_total 27245
telemt_upstream_connect_attempts_per_request{bucket="1"} 27245
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14862
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12377
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 1413
telemt_me_reconnect_attempts_total 26785
telemt_me_reconnect_success_total 22175
telemt_me_reader_eof_total 23561
telemt_me_idle_close_by_peer_total 23560
telemt_me_seq_mismatch_total 23
telemt_me_route_drop_no_conn_total 391593
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 952879
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 34
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2001
telemt_desync_full_logged_total 764
telemt_desync_suppressed_total 1237
telemt_desync_frames_bucket_total{bucket="1_2"} 725
telemt_desync_frames_bucket_total{bucket="3_10"} 687
telemt_desync_frames_bucket_total{bucket="gt_10"} 589
telemt_pool_swap_total 83
telemt_me_writer_removed_unexpected_total 22554
telemt_me_refill_failed_total 141
telemt_me_writer_restored_same_endpoint_total 22142
telemt_me_writer_restored_fallback_total 33
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 379
telemt_user_connections_total{user="hello"} 952140
telemt_user_connections_current{user="hello"} 446
telemt_user_octets_from_client{user="hello"} 11350289048 (10.57 GB)
telemt_user_octets_to_client{user="hello"} 289673353756 (269.78 GB)
telemt_user_unique_ips_current{user="hello"} 139
telemt_user_unique_ips_recent_window{user="hello"} 79
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 5774.3 (1h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 98897
telemt_connections_bad_total 315
telemt_handshake_timeouts_total 574
telemt_upstream_connect_attempt_total 1686
telemt_upstream_connect_success_total 1685
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 1686
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 920
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 752
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 13
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 28
telemt_me_reconnect_attempts_total 1353
telemt_me_reconnect_success_total 1337
telemt_me_reader_eof_total 1362
telemt_me_idle_close_by_peer_total 1362
telemt_me_seq_mismatch_total 1
telemt_me_route_drop_no_conn_total 33482
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 91480
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 195
telemt_desync_full_logged_total 62
telemt_desync_suppressed_total 133
telemt_desync_frames_bucket_total{bucket="1_2"} 51
telemt_desync_frames_bucket_total{bucket="3_10"} 61
telemt_desync_frames_bucket_total{bucket="gt_10"} 83
telemt_pool_swap_total 2
telemt_me_writer_removed_unexpected_total 1349
telemt_me_writer_restored_same_endpoint_total 1314
telemt_me_writer_restored_fallback_total 23
telemt_me_async_recovery_trigger_total 256
telemt_me_writer_removed_unexpected_minus_restored_total 12
telemt_user_connections_total{user="hello"} 91464
telemt_user_connections_current{user="hello"} 712
telemt_user_octets_from_client{user="hello"} 6207195180 (5.78 GB)
telemt_user_octets_to_client{user="hello"} 32342296624 (30.12 GB)
telemt_user_unique_ips_current{user="hello"} 193
telemt_user_unique_ips_recent_window{user="hello"} 99
```