# Server Metrics 2026-03-11 00:25:58 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 35933.8 (9h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 784978
telemt_connections_bad_total 9521
telemt_handshake_timeouts_total 8983
telemt_upstream_connect_attempt_total 7795
telemt_upstream_connect_success_total 7786
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 7795
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3879
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3849
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 57
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 471
telemt_me_reconnect_attempts_total 17599
telemt_me_reconnect_success_total 5935
telemt_me_reader_eof_total 6508
telemt_me_idle_close_by_peer_total 6508
telemt_me_route_drop_no_conn_total 323365
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 742866
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3554
telemt_desync_full_logged_total 993
telemt_desync_suppressed_total 2561
telemt_desync_frames_bucket_total{bucket="1_2"} 1033
telemt_desync_frames_bucket_total{bucket="3_10"} 1319
telemt_desync_frames_bucket_total{bucket="gt_10"} 1202
telemt_pool_swap_total 19
telemt_me_writer_removed_unexpected_total 6348
telemt_me_refill_failed_total 363
telemt_me_writer_restored_same_endpoint_total 5929
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 413
telemt_user_connections_total{user="hello"} 742652
telemt_user_connections_current{user="hello"} 388
telemt_user_octets_from_client{user="hello"} 10219070724 (9.52 GB)
telemt_user_octets_to_client{user="hello"} 221586680748 (206.37 GB)
telemt_user_unique_ips_current{user="hello"} 145
telemt_user_unique_ips_recent_window{user="hello"} 47
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 35990.5 (9h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 338823
telemt_connections_bad_total 2384
telemt_handshake_timeouts_total 17631
telemt_upstream_connect_attempt_total 14766
telemt_upstream_connect_success_total 11888
telemt_upstream_connect_fail_total 2878
telemt_upstream_connect_attempts_per_request{bucket="1"} 14766
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5121
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4527
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 209
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2031
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2878
telemt_me_keepalive_timeout_total 1705
telemt_me_reconnect_attempts_total 7935
telemt_me_reconnect_success_total 7122
telemt_me_reader_eof_total 7507
telemt_me_idle_close_by_peer_total 7505
telemt_me_route_drop_no_conn_total 171950
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 288308
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1747
telemt_desync_full_logged_total 489
telemt_desync_suppressed_total 1258
telemt_desync_frames_bucket_total{bucket="1_2"} 534
telemt_desync_frames_bucket_total{bucket="3_10"} 618
telemt_desync_frames_bucket_total{bucket="gt_10"} 595
telemt_pool_swap_total 27
telemt_me_writer_removed_unexpected_total 7220
telemt_me_refill_failed_total 22
telemt_me_writer_restored_same_endpoint_total 7101
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 86
telemt_me_writer_removed_unexpected_minus_restored_total 98
telemt_user_connections_total{user="hello"} 290577
telemt_user_connections_current{user="hello"} 150
telemt_user_octets_from_client{user="hello"} 2825596950 (2.63 GB)
telemt_user_octets_to_client{user="hello"} 69946378920 (65.14 GB)
telemt_user_msgs_from_client{user="hello"} 7933
telemt_user_msgs_to_client{user="hello"} 11226
telemt_user_unique_ips_current{user="hello"} 61
telemt_user_unique_ips_recent_window{user="hello"} 29
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 35990.3 (9h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 563276
telemt_connections_bad_total 3875
telemt_handshake_timeouts_total 34055
telemt_upstream_connect_attempt_total 9835
telemt_upstream_connect_success_total 9700
telemt_upstream_connect_fail_total 135
telemt_upstream_connect_attempts_per_request{bucket="1"} 9835
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5475
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4160
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 65
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 135
telemt_me_keepalive_timeout_total 506
telemt_me_reconnect_attempts_total 17867
telemt_me_reconnect_success_total 6807
telemt_me_reader_eof_total 7430
telemt_me_idle_close_by_peer_total 7430
telemt_me_route_drop_no_conn_total 193857
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 496838
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1521
telemt_desync_full_logged_total 434
telemt_desync_suppressed_total 1087
telemt_desync_frames_bucket_total{bucket="1_2"} 343
telemt_desync_frames_bucket_total{bucket="3_10"} 523
telemt_desync_frames_bucket_total{bucket="gt_10"} 655
telemt_pool_swap_total 20
telemt_me_writer_removed_unexpected_total 7248
telemt_me_refill_failed_total 343
telemt_me_writer_restored_same_endpoint_total 6796
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 441
telemt_user_connections_total{user="hello"} 497763
telemt_user_connections_current{user="hello"} 200
telemt_user_octets_from_client{user="hello"} 6810426825 (6.34 GB)
telemt_user_octets_to_client{user="hello"} 153497172697 (142.96 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 92
telemt_user_unique_ips_recent_window{user="hello"} 37
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 35990.6 (9h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 409971
telemt_connections_bad_total 34300
telemt_handshake_timeouts_total 38174
telemt_upstream_connect_attempt_total 10189
telemt_upstream_connect_success_total 10189
telemt_upstream_connect_attempts_per_request{bucket="1"} 10189
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5749
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4439
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 399
telemt_me_reconnect_attempts_total 9401
telemt_me_reconnect_success_total 8370
telemt_me_reader_eof_total 8827
telemt_me_idle_close_by_peer_total 8827
telemt_me_seq_mismatch_total 5
telemt_me_route_drop_no_conn_total 127007
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 324512
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 705
telemt_desync_full_logged_total 286
telemt_desync_suppressed_total 419
telemt_desync_frames_bucket_total{bucket="1_2"} 272
telemt_desync_frames_bucket_total{bucket="3_10"} 247
telemt_desync_frames_bucket_total{bucket="gt_10"} 186
telemt_pool_swap_total 28
telemt_me_writer_removed_unexpected_total 8483
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 8354
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 113
telemt_user_connections_total{user="hello"} 324187
telemt_user_connections_current{user="hello"} 183
telemt_user_octets_from_client{user="hello"} 4175850996 (3.89 GB)
telemt_user_octets_to_client{user="hello"} 90446327960 (84.23 GB)
telemt_user_unique_ips_current{user="hello"} 60
telemt_user_unique_ips_recent_window{user="hello"} 32
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 35990.4 (9h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 433985
telemt_connections_bad_total 4013
telemt_handshake_timeouts_total 2748
telemt_upstream_connect_attempt_total 10872
telemt_upstream_connect_success_total 10829
telemt_upstream_connect_fail_total 43
telemt_upstream_connect_attempts_per_request{bucket="1"} 10872
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5634
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5084
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 109
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 43
telemt_me_keepalive_timeout_total 501
telemt_me_reconnect_attempts_total 12742
telemt_me_reconnect_success_total 8976
telemt_me_reader_eof_total 9434
telemt_me_idle_close_by_peer_total 9434
telemt_me_route_drop_no_conn_total 145708
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 400525
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 2261
telemt_desync_full_logged_total 873
telemt_desync_suppressed_total 1388
telemt_desync_frames_bucket_total{bucket="1_2"} 830
telemt_desync_frames_bucket_total{bucket="3_10"} 970
telemt_desync_frames_bucket_total{bucket="gt_10"} 461
telemt_pool_swap_total 16
telemt_me_writer_removed_unexpected_total 9211
telemt_me_refill_failed_total 116
telemt_me_writer_restored_same_endpoint_total 8976
telemt_me_async_recovery_trigger_total 48
telemt_me_writer_removed_unexpected_minus_restored_total 235
telemt_user_connections_total{user="hello"} 400269
telemt_user_connections_current{user="hello"} 255
telemt_user_octets_from_client{user="hello"} 8333923376 (7.76 GB)
telemt_user_octets_to_client{user="hello"} 145631580556 (135.63 GB)
telemt_user_unique_ips_current{user="hello"} 74
telemt_user_unique_ips_recent_window{user="hello"} 36
```