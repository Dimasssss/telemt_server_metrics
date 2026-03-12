# Server Metrics 2026-03-12 17:23:21 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 41081.1 (11h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1484545
telemt_connections_bad_total 20278
telemt_handshake_timeouts_total 13969
telemt_upstream_connect_attempt_total 8140
telemt_upstream_connect_success_total 8092
telemt_upstream_connect_fail_total 48
telemt_upstream_connect_attempts_per_request{bucket="1"} 8140
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4253
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3812
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 27
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 48
telemt_me_keepalive_timeout_total 514
telemt_me_reconnect_attempts_total 14845
telemt_me_reconnect_success_total 6002
telemt_me_reader_eof_total 6518
telemt_me_idle_close_by_peer_total 6517
telemt_me_route_drop_no_conn_total 575352
telemt_me_route_drop_channel_closed_total 9
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1391784
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7037
telemt_desync_full_logged_total 1777
telemt_desync_suppressed_total 5260
telemt_desync_frames_bucket_total{bucket="1_2"} 1832
telemt_desync_frames_bucket_total{bucket="3_10"} 2546
telemt_desync_frames_bucket_total{bucket="gt_10"} 2659
telemt_pool_swap_total 24
telemt_me_writer_removed_unexpected_total 6361
telemt_me_refill_failed_total 275
telemt_me_writer_restored_same_endpoint_total 5989
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 359
telemt_user_connections_total{user="hello"} 1391281
telemt_user_connections_current{user="hello"} 1819
telemt_user_octets_from_client{user="hello"} 21346709476 (19.88 GB)
telemt_user_octets_to_client{user="hello"} 426285975512 (397.01 GB)
telemt_user_unique_ips_current{user="hello"} 456
telemt_user_unique_ips_recent_window{user="hello"} 222
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 70701.6 (19h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 646400
telemt_connections_bad_total 8603
telemt_handshake_timeouts_total 28916
telemt_upstream_connect_attempt_total 16823
telemt_upstream_connect_success_total 16816
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 16823
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8397
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8401
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 18
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_keepalive_timeout_total 1351
telemt_me_reconnect_attempts_total 13175
telemt_me_reconnect_success_total 13098
telemt_me_reader_eof_total 13926
telemt_me_idle_close_by_peer_total 13926
telemt_me_route_drop_no_conn_total 200760
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 580696
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2400
telemt_desync_full_logged_total 739
telemt_desync_suppressed_total 1661
telemt_desync_frames_bucket_total{bucket="1_2"} 1020
telemt_desync_frames_bucket_total{bucket="3_10"} 776
telemt_desync_frames_bucket_total{bucket="gt_10"} 604
telemt_pool_swap_total 70
telemt_me_writer_removed_unexpected_total 13231
telemt_me_writer_restored_same_endpoint_total 13089
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 133
telemt_user_connections_total{user="hello"} 581234
telemt_user_connections_current{user="hello"} 637
telemt_user_octets_from_client{user="hello"} 8911281067 (8.30 GB)
telemt_user_octets_to_client{user="hello"} 214492175614 (199.76 GB)
telemt_user_msgs_from_client{user="hello"} 353
telemt_user_msgs_to_client{user="hello"} 423
telemt_user_unique_ips_current{user="hello"} 173
telemt_user_unique_ips_recent_window{user="hello"} 83
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 70701.5 (19h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1349845
telemt_connections_bad_total 6673
telemt_handshake_timeouts_total 96481
telemt_upstream_connect_attempt_total 16872
telemt_upstream_connect_success_total 16867
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 16872
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9075
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7723
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 64
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 1125
telemt_me_reconnect_attempts_total 14202
telemt_me_reconnect_success_total 12965
telemt_me_reader_eof_total 13672
telemt_me_idle_close_by_peer_total 13671
telemt_me_route_drop_no_conn_total 437297
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1017922
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4328
telemt_desync_full_logged_total 1340
telemt_desync_suppressed_total 2988
telemt_desync_frames_bucket_total{bucket="1_2"} 671
telemt_desync_frames_bucket_total{bucket="3_10"} 1571
telemt_desync_frames_bucket_total{bucket="gt_10"} 2086
telemt_pool_swap_total 64
telemt_me_writer_removed_unexpected_total 13068
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 12924
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 103
telemt_user_connections_total{user="hello"} 1017765
telemt_user_connections_current{user="hello"} 1052
telemt_user_octets_from_client{user="hello"} 15188491692 (14.15 GB)
telemt_user_octets_to_client{user="hello"} 348907430829 (324.95 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 276
telemt_user_unique_ips_recent_window{user="hello"} 139
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 70702.0 (19h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 814094
telemt_connections_bad_total 9030
telemt_handshake_timeouts_total 62857
telemt_upstream_connect_attempt_total 18453
telemt_upstream_connect_success_total 18382
telemt_upstream_connect_fail_total 71
telemt_upstream_connect_attempts_per_request{bucket="1"} 18453
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10388
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7981
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 13
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 71
telemt_me_keepalive_timeout_total 1570
telemt_me_reconnect_attempts_total 20090
telemt_me_reconnect_success_total 14837
telemt_me_reader_eof_total 15796
telemt_me_idle_close_by_peer_total 15796
telemt_me_route_drop_no_conn_total 284125
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 705092
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1557
telemt_desync_full_logged_total 520
telemt_desync_suppressed_total 1037
telemt_desync_frames_bucket_total{bucket="1_2"} 429
telemt_desync_frames_bucket_total{bucket="3_10"} 607
telemt_desync_frames_bucket_total{bucket="gt_10"} 521
telemt_pool_swap_total 58
telemt_me_writer_removed_unexpected_total 15115
telemt_me_refill_failed_total 162
telemt_me_writer_restored_same_endpoint_total 14816
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 108
telemt_me_writer_removed_unexpected_minus_restored_total 278
telemt_user_connections_total{user="hello"} 704509
telemt_user_connections_current{user="hello"} 700
telemt_user_octets_from_client{user="hello"} 8692145128 (8.10 GB)
telemt_user_octets_to_client{user="hello"} 282331380964 (262.94 GB)
telemt_user_unique_ips_current{user="hello"} 188
telemt_user_unique_ips_recent_window{user="hello"} 97
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 70701.8 (19h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 918876
telemt_connections_bad_total 11398
telemt_handshake_timeouts_total 7528
telemt_upstream_connect_attempt_total 22557
telemt_upstream_connect_success_total 22287
telemt_upstream_connect_fail_total 270
telemt_upstream_connect_attempts_per_request{bucket="1"} 22557
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11394
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10771
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 114
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 270
telemt_me_keepalive_timeout_total 1290
telemt_me_reconnect_attempts_total 27413
telemt_me_reconnect_success_total 18723
telemt_me_reader_eof_total 19603
telemt_me_idle_close_by_peer_total 19603
telemt_me_seq_mismatch_total 33
telemt_me_route_drop_no_conn_total 336388
telemt_me_route_drop_channel_closed_total 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 843555
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 37
telemt_me_hardswap_pending_ttl_expired_total 9
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 3321
telemt_desync_full_logged_total 1134
telemt_desync_suppressed_total 2187
telemt_desync_frames_bucket_total{bucket="1_2"} 894
telemt_desync_frames_bucket_total{bucket="3_10"} 1138
telemt_desync_frames_bucket_total{bucket="gt_10"} 1289
telemt_pool_swap_total 32
telemt_me_writer_removed_unexpected_total 19197
telemt_me_refill_failed_total 269
telemt_me_writer_restored_same_endpoint_total 18679
telemt_me_writer_restored_fallback_total 44
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 474
telemt_user_connections_total{user="hello"} 843438
telemt_user_connections_current{user="hello"} 855
telemt_user_octets_from_client{user="hello"} 10342153296 (9.63 GB)
telemt_user_octets_to_client{user="hello"} 256916707760 (239.27 GB)
telemt_user_unique_ips_current{user="hello"} 217
telemt_user_unique_ips_recent_window{user="hello"} 119
```