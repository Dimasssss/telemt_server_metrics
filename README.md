# Server Metrics 2026-03-13 10:03:33 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 101092.4 (28h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2911751
telemt_connections_bad_total 36439
telemt_handshake_timeouts_total 52375
telemt_upstream_connect_attempt_total 19980
telemt_upstream_connect_success_total 19871
telemt_upstream_connect_fail_total 109
telemt_upstream_connect_attempts_per_request{bucket="1"} 19980
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10213
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9608
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 50
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 109
telemt_me_keepalive_timeout_total 1422
telemt_me_reconnect_attempts_total 24901
telemt_me_reconnect_success_total 14832
telemt_me_reader_eof_total 15978
telemt_me_idle_close_by_peer_total 15977
telemt_me_route_drop_no_conn_total 1075679
telemt_me_route_drop_channel_closed_total 14
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2654435
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 11579
telemt_desync_full_logged_total 2997
telemt_desync_suppressed_total 8582
telemt_desync_frames_bucket_total{bucket="1_2"} 2977
telemt_desync_frames_bucket_total{bucket="3_10"} 4333
telemt_desync_frames_bucket_total{bucket="gt_10"} 4269
telemt_pool_swap_total 83
telemt_me_writer_removed_unexpected_total 15353
telemt_me_refill_failed_total 312
telemt_me_writer_restored_same_endpoint_total 14819
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 521
telemt_user_connections_total{user="hello"} 2654291
telemt_user_connections_current{user="hello"} 1746
telemt_user_octets_from_client{user="hello"} 36672782936 (34.15 GB)
telemt_user_octets_to_client{user="hello"} 863977246580 (804.64 GB)
telemt_user_unique_ips_current{user="hello"} 444
telemt_user_unique_ips_recent_window{user="hello"} 263
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 130713.1 (36h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1176530
telemt_connections_bad_total 14811
telemt_handshake_timeouts_total 106886
telemt_upstream_connect_attempt_total 32374
telemt_upstream_connect_success_total 32343
telemt_upstream_connect_fail_total 31
telemt_upstream_connect_attempts_per_request{bucket="1"} 32374
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16664
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15589
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 90
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 31
telemt_me_keepalive_timeout_total 3739
telemt_me_reconnect_attempts_total 24323
telemt_me_reconnect_success_total 24197
telemt_me_reader_eof_total 25796
telemt_me_idle_close_by_peer_total 25796
telemt_me_route_drop_no_conn_total 363187
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1012547
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4461
telemt_desync_full_logged_total 1351
telemt_desync_suppressed_total 3110
telemt_desync_frames_bucket_total{bucket="1_2"} 1621
telemt_desync_frames_bucket_total{bucket="3_10"} 1475
telemt_desync_frames_bucket_total{bucket="gt_10"} 1365
telemt_pool_swap_total 135
telemt_me_writer_removed_unexpected_total 24433
telemt_me_writer_restored_same_endpoint_total 24188
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 236
telemt_user_connections_total{user="hello"} 1014482
telemt_user_connections_current{user="hello"} 445
telemt_user_octets_from_client{user="hello"} 15435031680 (14.37 GB)
telemt_user_octets_to_client{user="hello"} 369887494971 (344.48 GB)
telemt_user_msgs_from_client{user="hello"} 6476
telemt_user_msgs_to_client{user="hello"} 18854
telemt_user_unique_ips_current{user="hello"} 137
telemt_user_unique_ips_recent_window{user="hello"} 60
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 130712.5 (36h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2265061
telemt_connections_bad_total 24755
telemt_handshake_timeouts_total 154614
telemt_upstream_connect_attempt_total 29927
telemt_upstream_connect_success_total 29917
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 29927
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15683
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14114
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 115
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_keepalive_timeout_total 1851
telemt_me_reconnect_attempts_total 24336
telemt_me_reconnect_success_total 23048
telemt_me_reader_eof_total 24419
telemt_me_idle_close_by_peer_total 24418
telemt_me_route_drop_no_conn_total 740459
telemt_me_route_drop_channel_closed_total 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1814298
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5990
telemt_desync_full_logged_total 1913
telemt_desync_suppressed_total 4077
telemt_desync_frames_bucket_total{bucket="1_2"} 977
telemt_desync_frames_bucket_total{bucket="3_10"} 2186
telemt_desync_frames_bucket_total{bucket="gt_10"} 2827
telemt_pool_swap_total 123
telemt_me_writer_removed_unexpected_total 23278
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 23007
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 230
telemt_user_connections_total{user="hello"} 1813748
telemt_user_connections_current{user="hello"} 1009
telemt_user_octets_from_client{user="hello"} 31448104116 (29.29 GB)
telemt_user_octets_to_client{user="hello"} 653539983429 (608.66 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 288
telemt_user_unique_ips_recent_window{user="hello"} 168
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 130713.0 (36h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1433871
telemt_connections_bad_total 14236
telemt_handshake_timeouts_total 89294
telemt_upstream_connect_attempt_total 42878
telemt_upstream_connect_success_total 40570
telemt_upstream_connect_fail_total 2171
telemt_upstream_connect_attempts_per_request{bucket="1"} 42604
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 24687
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15792
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 91
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2170
telemt_me_keepalive_timeout_total 11473
telemt_me_reconnect_attempts_total 37144
telemt_me_reconnect_success_total 28197
telemt_me_reader_eof_total 30364
telemt_me_idle_close_by_peer_total 30357
telemt_me_route_drop_no_conn_total 505911
telemt_me_route_drop_channel_closed_total 3
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1197480
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2238
telemt_desync_full_logged_total 740
telemt_desync_suppressed_total 1498
telemt_desync_frames_bucket_total{bucket="1_2"} 619
telemt_desync_frames_bucket_total{bucket="3_10"} 859
telemt_desync_frames_bucket_total{bucket="gt_10"} 760
telemt_pool_swap_total 114
telemt_me_writer_removed_unexpected_total 28681
telemt_me_refill_failed_total 274
telemt_me_writer_restored_same_endpoint_total 28173
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 484
telemt_user_connections_total{user="hello"} 1202234
telemt_user_connections_current{user="hello"} 612
telemt_user_octets_from_client{user="hello"} 18247587657 (16.99 GB)
telemt_user_octets_to_client{user="hello"} 477633265578 (444.83 GB)
telemt_user_msgs_from_client{user="hello"} 44500
telemt_user_msgs_to_client{user="hello"} 116355
telemt_user_unique_ips_current{user="hello"} 178
telemt_user_unique_ips_recent_window{user="hello"} 103
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 130713.2 (36h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1603764
telemt_connections_bad_total 36068
telemt_handshake_timeouts_total 13037
telemt_upstream_connect_attempt_total 41942
telemt_upstream_connect_success_total 41443
telemt_upstream_connect_fail_total 499
telemt_upstream_connect_attempts_per_request{bucket="1"} 41942
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20861
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20368
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 16
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 198
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 499
telemt_me_keepalive_timeout_total 2250
telemt_me_reconnect_attempts_total 52900
telemt_me_reconnect_success_total 34923
telemt_me_reader_eof_total 36702
telemt_me_idle_close_by_peer_total 36702
telemt_me_seq_mismatch_total 48
telemt_me_route_drop_no_conn_total 587031
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1459981
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 52
telemt_me_hardswap_pending_ttl_expired_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 5113
telemt_desync_full_logged_total 1820
telemt_desync_suppressed_total 3293
telemt_desync_frames_bucket_total{bucket="1_2"} 1578
telemt_desync_frames_bucket_total{bucket="3_10"} 1653
telemt_desync_frames_bucket_total{bucket="gt_10"} 1882
telemt_pool_swap_total 63
telemt_me_writer_removed_unexpected_total 35864
telemt_me_refill_failed_total 557
telemt_me_writer_restored_same_endpoint_total 34862
telemt_me_writer_restored_fallback_total 61
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 941
telemt_user_connections_total{user="hello"} 1459780
telemt_user_connections_current{user="hello"} 946
telemt_user_octets_from_client{user="hello"} 18651466140 (17.37 GB)
telemt_user_octets_to_client{user="hello"} 507590629528 (472.73 GB)
telemt_user_unique_ips_current{user="hello"} 223
telemt_user_unique_ips_recent_window{user="hello"} 111
```