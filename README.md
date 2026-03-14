# Server Metrics 2026-03-14 20:59:58 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.17

telemt_uptime_seconds 27739.9 (7h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1038763
telemt_connections_bad_total 42345
telemt_handshake_timeouts_total 14688
telemt_upstream_connect_attempt_total 5044
telemt_upstream_connect_success_total 5021
telemt_upstream_connect_fail_total 23
telemt_upstream_connect_attempts_per_request{bucket="1"} 5044
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2495
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2484
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 42
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 23
telemt_me_keepalive_timeout_total 116
telemt_me_reconnect_attempts_total 4409
telemt_me_reconnect_success_total 3601
telemt_me_reader_eof_total 3798
telemt_me_idle_close_by_peer_total 3798
telemt_me_route_drop_no_conn_total 396905
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 924141
telemt_me_writer_pick_total{mode="p2c",result="full"} 12
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 9
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3114
telemt_desync_full_logged_total 891
telemt_desync_suppressed_total 2223
telemt_desync_frames_bucket_total{bucket="1_2"} 735
telemt_desync_frames_bucket_total{bucket="3_10"} 1151
telemt_desync_frames_bucket_total{bucket="gt_10"} 1228
telemt_pool_swap_total 21
telemt_me_writer_removed_unexpected_total 3684
telemt_me_refill_failed_total 24
telemt_me_writer_restored_same_endpoint_total 3592
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 484
telemt_me_writer_removed_unexpected_minus_restored_total 83
telemt_user_connections_total{user="hello"} 924087
telemt_user_connections_current{user="hello"} 1314
telemt_user_octets_from_client{user="hello"} 16420438392 (15.29 GB)
telemt_user_octets_to_client{user="hello"} 311538920852 (290.14 GB)
telemt_user_unique_ips_current{user="hello"} 409
telemt_user_unique_ips_recent_window{user="hello"} 145
```

## server2

```
telemt 3.3.17

telemt_uptime_seconds 27745.0 (7h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 408756
telemt_connections_bad_total 30912
telemt_handshake_timeouts_total 12816
telemt_upstream_connect_attempt_total 5957
telemt_upstream_connect_success_total 5897
telemt_upstream_connect_fail_total 60
telemt_upstream_connect_attempts_per_request{bucket="1"} 5957
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3054
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2729
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 13
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 101
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 60
telemt_me_keepalive_timeout_total 478
telemt_me_reconnect_attempts_total 5276
telemt_me_reconnect_success_total 4479
telemt_me_reader_eof_total 4681
telemt_me_idle_close_by_peer_total 4681
telemt_me_seq_mismatch_total 7
telemt_me_route_drop_no_conn_total 120209
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 341579
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1674
telemt_desync_full_logged_total 442
telemt_desync_suppressed_total 1232
telemt_desync_frames_bucket_total{bucket="1_2"} 695
telemt_desync_frames_bucket_total{bucket="3_10"} 580
telemt_desync_frames_bucket_total{bucket="gt_10"} 399
telemt_pool_swap_total 18
telemt_me_writer_removed_unexpected_total 4596
telemt_me_refill_failed_total 23
telemt_me_writer_restored_same_endpoint_total 4456
telemt_me_writer_restored_fallback_total 23
telemt_me_async_recovery_trigger_total 38
telemt_me_writer_removed_unexpected_minus_restored_total 117
telemt_user_connections_total{user="hello"} 341523
telemt_user_connections_current{user="hello"} 474
telemt_user_octets_from_client{user="hello"} 5087967052 (4.74 GB)
telemt_user_octets_to_client{user="hello"} 118758858132 (110.60 GB)
telemt_user_unique_ips_current{user="hello"} 154
telemt_user_unique_ips_recent_window{user="hello"} 59
```

## server3

```
telemt 3.3.17

telemt_uptime_seconds 27608.0 (7h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 889429
telemt_connections_bad_total 3649
telemt_handshake_timeouts_total 221728
telemt_upstream_connect_attempt_total 5359
telemt_upstream_connect_success_total 5342
telemt_upstream_connect_fail_total 17
telemt_upstream_connect_attempts_per_request{bucket="1"} 5359
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2754
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2574
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 14
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17
telemt_me_keepalive_timeout_total 115
telemt_me_reconnect_attempts_total 7849
telemt_me_reconnect_success_total 3936
telemt_me_reader_eof_total 4218
telemt_me_idle_close_by_peer_total 4218
telemt_me_route_drop_no_conn_total 199021
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 566818
telemt_me_writer_pick_total{mode="p2c",result="full"} 14
telemt_me_writer_pick_total{mode="p2c",result="closed"} 30
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2128
telemt_desync_full_logged_total 816
telemt_desync_suppressed_total 1312
telemt_desync_frames_bucket_total{bucket="1_2"} 314
telemt_desync_frames_bucket_total{bucket="3_10"} 742
telemt_desync_frames_bucket_total{bucket="gt_10"} 1072
telemt_pool_swap_total 23
telemt_me_writer_removed_unexpected_total 4101
telemt_me_refill_failed_total 121
telemt_me_writer_restored_same_endpoint_total 3903
telemt_me_writer_restored_fallback_total 33
telemt_me_async_recovery_trigger_total 1168
telemt_me_writer_removed_unexpected_minus_restored_total 165
telemt_user_connections_total{user="hello"} 566646
telemt_user_connections_current{user="hello"} 714
telemt_user_octets_from_client{user="hello"} 8485038448 (7.90 GB)
telemt_user_octets_to_client{user="hello"} 211173467852 (196.67 GB)
telemt_user_unique_ips_current{user="hello"} 213
telemt_user_unique_ips_recent_window{user="hello"} 93
```

## server4

```
telemt 3.3.17

telemt_uptime_seconds 27462.5 (7h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 472184
telemt_connections_bad_total 99912
telemt_handshake_timeouts_total 54639
telemt_upstream_connect_attempt_total 6333
telemt_upstream_connect_success_total 6332
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 6333
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3193
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3058
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 81
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 214
telemt_me_reconnect_attempts_total 5856
telemt_me_reconnect_success_total 4934
telemt_me_reader_eof_total 5175
telemt_me_idle_close_by_peer_total 5175
telemt_me_seq_mismatch_total 11
telemt_me_route_drop_no_conn_total 108743
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 309618
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 12
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 702
telemt_desync_full_logged_total 244
telemt_desync_suppressed_total 458
telemt_desync_frames_bucket_total{bucket="1_2"} 242
telemt_desync_frames_bucket_total{bucket="3_10"} 231
telemt_desync_frames_bucket_total{bucket="gt_10"} 229
telemt_pool_swap_total 22
telemt_me_writer_removed_unexpected_total 5021
telemt_me_refill_failed_total 28
telemt_me_writer_restored_same_endpoint_total 4922
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 20
telemt_me_writer_removed_unexpected_minus_restored_total 87
telemt_user_connections_total{user="hello"} 309533
telemt_user_connections_current{user="hello"} 374
telemt_user_octets_from_client{user="hello"} 4341617132 (4.04 GB)
telemt_user_octets_to_client{user="hello"} 95190049828 (88.65 GB)
telemt_user_unique_ips_current{user="hello"} 130
telemt_user_unique_ips_recent_window{user="hello"} 58
```

## server5

```
telemt 3.3.17

telemt_uptime_seconds 27758.0 (7h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 395588
telemt_connections_bad_total 1391
telemt_handshake_timeouts_total 3961
telemt_upstream_connect_attempt_total 5882
telemt_upstream_connect_success_total 5767
telemt_upstream_connect_fail_total 115
telemt_upstream_connect_attempts_per_request{bucket="1"} 5882
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2809
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2910
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 48
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 115
telemt_me_keepalive_timeout_total 142
telemt_me_reconnect_attempts_total 5044
telemt_me_reconnect_success_total 4368
telemt_me_reader_eof_total 4611
telemt_me_idle_close_by_peer_total 4611
telemt_me_route_drop_no_conn_total 124826
telemt_me_route_drop_channel_closed_total 23
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 367187
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 970
telemt_desync_full_logged_total 343
telemt_desync_suppressed_total 627
telemt_desync_frames_bucket_total{bucket="1_2"} 322
telemt_desync_frames_bucket_total{bucket="3_10"} 302
telemt_desync_frames_bucket_total{bucket="gt_10"} 346
telemt_pool_swap_total 20
telemt_me_writer_removed_unexpected_total 4469
telemt_me_refill_failed_total 20
telemt_me_writer_restored_same_endpoint_total 4350
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 205
telemt_me_writer_removed_unexpected_minus_restored_total 101
telemt_user_connections_total{user="hello"} 367152
telemt_user_connections_current{user="hello"} 543
telemt_user_octets_from_client{user="hello"} 5885886776 (5.48 GB)
telemt_user_octets_to_client{user="hello"} 153280845764 (142.75 GB)
telemt_user_unique_ips_current{user="hello"} 154
telemt_user_unique_ips_recent_window{user="hello"} 57
```