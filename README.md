# Server Metrics 2026-03-11 01:16:45 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 38980.6 (10h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 807792
telemt_connections_bad_total 9523
telemt_handshake_timeouts_total 9438
telemt_upstream_connect_attempt_total 8499
telemt_upstream_connect_success_total 8490
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 8499
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4241
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4190
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 58
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 482
telemt_me_reconnect_attempts_total 18130
telemt_me_reconnect_success_total 6464
telemt_me_reader_eof_total 7082
telemt_me_idle_close_by_peer_total 7082
telemt_me_route_drop_no_conn_total 330267
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 764929
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3596
telemt_desync_full_logged_total 1011
telemt_desync_suppressed_total 2585
telemt_desync_frames_bucket_total{bucket="1_2"} 1053
telemt_desync_frames_bucket_total{bucket="3_10"} 1339
telemt_desync_frames_bucket_total{bucket="gt_10"} 1204
telemt_pool_swap_total 23
telemt_me_writer_removed_unexpected_total 6882
telemt_me_refill_failed_total 363
telemt_me_writer_restored_same_endpoint_total 6458
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 418
telemt_user_connections_total{user="hello"} 764690
telemt_user_connections_current{user="hello"} 430
telemt_user_octets_from_client{user="hello"} 10569933748 (9.84 GB)
telemt_user_octets_to_client{user="hello"} 232921876180 (216.93 GB)
telemt_user_unique_ips_current{user="hello"} 173
telemt_user_unique_ips_recent_window{user="hello"} 63
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 39037.4 (10h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 347666
telemt_connections_bad_total 2404
telemt_handshake_timeouts_total 17798
telemt_upstream_connect_attempt_total 15697
telemt_upstream_connect_success_total 12812
telemt_upstream_connect_fail_total 2885
telemt_upstream_connect_attempts_per_request{bucket="1"} 15697
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5581
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4991
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 209
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2031
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2885
telemt_me_keepalive_timeout_total 1716
telemt_me_reconnect_attempts_total 8685
telemt_me_reconnect_success_total 7869
telemt_me_reader_eof_total 8312
telemt_me_idle_close_by_peer_total 8310
telemt_me_route_drop_no_conn_total 173940
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 296786
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1777
telemt_desync_full_logged_total 509
telemt_desync_suppressed_total 1268
telemt_desync_frames_bucket_total{bucket="1_2"} 544
telemt_desync_frames_bucket_total{bucket="3_10"} 631
telemt_desync_frames_bucket_total{bucket="gt_10"} 602
telemt_pool_swap_total 31
telemt_me_writer_removed_unexpected_total 7975
telemt_me_refill_failed_total 22
telemt_me_writer_restored_same_endpoint_total 7848
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 86
telemt_me_writer_removed_unexpected_minus_restored_total 106
telemt_user_connections_total{user="hello"} 299055
telemt_user_connections_current{user="hello"} 172
telemt_user_octets_from_client{user="hello"} 2858273946 (2.66 GB)
telemt_user_octets_to_client{user="hello"} 71068838288 (66.19 GB)
telemt_user_msgs_from_client{user="hello"} 7933
telemt_user_msgs_to_client{user="hello"} 11226
telemt_user_unique_ips_current{user="hello"} 62
telemt_user_unique_ips_recent_window{user="hello"} 25
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 39037.1 (10h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 577933
telemt_connections_bad_total 4177
telemt_handshake_timeouts_total 34219
telemt_upstream_connect_attempt_total 10681
telemt_upstream_connect_success_total 10534
telemt_upstream_connect_fail_total 147
telemt_upstream_connect_attempts_per_request{bucket="1"} 10681
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5908
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4560
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 66
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 147
telemt_me_keepalive_timeout_total 514
telemt_me_reconnect_attempts_total 18527
telemt_me_reconnect_success_total 7463
telemt_me_reader_eof_total 8137
telemt_me_idle_close_by_peer_total 8137
telemt_me_route_drop_no_conn_total 197884
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 510912
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1522
telemt_desync_full_logged_total 435
telemt_desync_suppressed_total 1087
telemt_desync_frames_bucket_total{bucket="1_2"} 344
telemt_desync_frames_bucket_total{bucket="3_10"} 523
telemt_desync_frames_bucket_total{bucket="gt_10"} 655
telemt_pool_swap_total 24
telemt_me_writer_removed_unexpected_total 7911
telemt_me_refill_failed_total 343
telemt_me_writer_restored_same_endpoint_total 7452
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 448
telemt_user_connections_total{user="hello"} 511827
telemt_user_connections_current{user="hello"} 184
telemt_user_octets_from_client{user="hello"} 6907916737 (6.43 GB)
telemt_user_octets_to_client{user="hello"} 155854038517 (145.15 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 82
telemt_user_unique_ips_recent_window{user="hello"} 42
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 39037.6 (10h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 426687
telemt_connections_bad_total 37070
telemt_handshake_timeouts_total 40487
telemt_upstream_connect_attempt_total 11229
telemt_upstream_connect_success_total 11229
telemt_upstream_connect_attempts_per_request{bucket="1"} 11229
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6327
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4900
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_timeout_total 417
telemt_me_reconnect_attempts_total 10269
telemt_me_reconnect_success_total 9235
telemt_me_reader_eof_total 9775
telemt_me_idle_close_by_peer_total 9775
telemt_me_seq_mismatch_total 7
telemt_me_route_drop_no_conn_total 129897
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 336065
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 726
telemt_desync_full_logged_total 290
telemt_desync_suppressed_total 436
telemt_desync_frames_bucket_total{bucket="1_2"} 278
telemt_desync_frames_bucket_total{bucket="3_10"} 252
telemt_desync_frames_bucket_total{bucket="gt_10"} 196
telemt_pool_swap_total 32
telemt_me_writer_removed_unexpected_total 9352
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 9217
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 117
telemt_user_connections_total{user="hello"} 335741
telemt_user_connections_current{user="hello"} 177
telemt_user_octets_from_client{user="hello"} 4233212416 (3.94 GB)
telemt_user_octets_to_client{user="hello"} 91659899912 (85.36 GB)
telemt_user_unique_ips_current{user="hello"} 62
telemt_user_unique_ips_recent_window{user="hello"} 31
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 39037.4 (10h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 450702
telemt_connections_bad_total 4951
telemt_handshake_timeouts_total 2904
telemt_upstream_connect_attempt_total 11745
telemt_upstream_connect_success_total 11695
telemt_upstream_connect_fail_total 50
telemt_upstream_connect_attempts_per_request{bucket="1"} 11745
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6056
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5524
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 113
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 50
telemt_me_keepalive_timeout_total 511
telemt_me_reconnect_attempts_total 13433
telemt_me_reconnect_success_total 9665
telemt_me_reader_eof_total 10172
telemt_me_idle_close_by_peer_total 10172
telemt_me_route_drop_no_conn_total 149082
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 413841
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 2280
telemt_desync_full_logged_total 883
telemt_desync_suppressed_total 1397
telemt_desync_frames_bucket_total{bucket="1_2"} 841
telemt_desync_frames_bucket_total{bucket="3_10"} 972
telemt_desync_frames_bucket_total{bucket="gt_10"} 467
telemt_pool_swap_total 20
telemt_me_writer_removed_unexpected_total 9906
telemt_me_refill_failed_total 116
telemt_me_writer_restored_same_endpoint_total 9665
telemt_me_async_recovery_trigger_total 48
telemt_me_writer_removed_unexpected_minus_restored_total 241
telemt_user_connections_total{user="hello"} 413553
telemt_user_connections_current{user="hello"} 241
telemt_user_octets_from_client{user="hello"} 8388915212 (7.81 GB)
telemt_user_octets_to_client{user="hello"} 147721976696 (137.58 GB)
telemt_user_unique_ips_current{user="hello"} 82
telemt_user_unique_ips_recent_window{user="hello"} 34
```