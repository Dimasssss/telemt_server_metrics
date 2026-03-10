# Server Metrics 2026-03-10 23:25:01 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 32276.5 (8h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 759534
telemt_connections_bad_total 8946
telemt_handshake_timeouts_total 8484
telemt_upstream_connect_attempt_total 6962
telemt_upstream_connect_success_total 6953
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 6962
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3471
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3425
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 56
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 368
telemt_me_reconnect_attempts_total 16939
telemt_me_reconnect_success_total 5277
telemt_me_reader_eof_total 5803
telemt_me_idle_close_by_peer_total 5803
telemt_me_route_drop_no_conn_total 314587
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 718931
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3493
telemt_desync_full_logged_total 976
telemt_desync_suppressed_total 2517
telemt_desync_frames_bucket_total{bucket="1_2"} 1010
telemt_desync_frames_bucket_total{bucket="3_10"} 1307
telemt_desync_frames_bucket_total{bucket="gt_10"} 1176
telemt_pool_swap_total 15
telemt_me_writer_removed_unexpected_total 5685
telemt_me_refill_failed_total 363
telemt_me_writer_restored_same_endpoint_total 5271
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 408
telemt_user_connections_total{user="hello"} 718722
telemt_user_connections_current{user="hello"} 406
telemt_user_octets_from_client{user="hello"} 10110899548 (9.42 GB)
telemt_user_octets_to_client{user="hello"} 216032652896 (201.20 GB)
telemt_user_unique_ips_current{user="hello"} 149
telemt_user_unique_ips_recent_window{user="hello"} 51
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 32333.2 (8h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 329615
telemt_connections_bad_total 2373
telemt_handshake_timeouts_total 17602
telemt_upstream_connect_attempt_total 13760
telemt_upstream_connect_success_total 10887
telemt_upstream_connect_fail_total 2873
telemt_upstream_connect_attempts_per_request{bucket="1"} 13760
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4632
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4015
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 209
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2031
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2873
telemt_me_keepalive_timeout_total 1388
telemt_me_reconnect_attempts_total 7106
telemt_me_reconnect_success_total 6296
telemt_me_reader_eof_total 6619
telemt_me_idle_close_by_peer_total 6617
telemt_me_route_drop_no_conn_total 169590
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 279394
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1706
telemt_desync_full_logged_total 472
telemt_desync_suppressed_total 1234
telemt_desync_frames_bucket_total{bucket="1_2"} 523
telemt_desync_frames_bucket_total{bucket="3_10"} 603
telemt_desync_frames_bucket_total{bucket="gt_10"} 580
telemt_pool_swap_total 23
telemt_me_writer_removed_unexpected_total 6387
telemt_me_refill_failed_total 22
telemt_me_writer_restored_same_endpoint_total 6275
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 86
telemt_me_writer_removed_unexpected_minus_restored_total 91
telemt_user_connections_total{user="hello"} 281663
telemt_user_connections_current{user="hello"} 135
telemt_user_octets_from_client{user="hello"} 2759695538 (2.57 GB)
telemt_user_octets_to_client{user="hello"} 68431282452 (63.73 GB)
telemt_user_msgs_from_client{user="hello"} 7933
telemt_user_msgs_to_client{user="hello"} 11226
telemt_user_unique_ips_current{user="hello"} 58
telemt_user_unique_ips_recent_window{user="hello"} 25
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 32333.0 (8h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 545372
telemt_connections_bad_total 3510
telemt_handshake_timeouts_total 33948
telemt_upstream_connect_attempt_total 8765
telemt_upstream_connect_success_total 8643
telemt_upstream_connect_fail_total 122
telemt_upstream_connect_attempts_per_request{bucket="1"} 8765
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4941
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3640
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 62
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 122
telemt_me_keepalive_timeout_total 225
telemt_me_reconnect_attempts_total 16984
telemt_me_reconnect_success_total 5927
telemt_me_reader_eof_total 6500
telemt_me_idle_close_by_peer_total 6500
telemt_me_route_drop_no_conn_total 188818
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 479499
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1520
telemt_desync_full_logged_total 433
telemt_desync_suppressed_total 1087
telemt_desync_frames_bucket_total{bucket="1_2"} 342
telemt_desync_frames_bucket_total{bucket="3_10"} 523
telemt_desync_frames_bucket_total{bucket="gt_10"} 655
telemt_pool_swap_total 17
telemt_me_writer_removed_unexpected_total 6363
telemt_me_refill_failed_total 343
telemt_me_writer_restored_same_endpoint_total 5916
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 436
telemt_user_connections_total{user="hello"} 480429
telemt_user_connections_current{user="hello"} 167
telemt_user_octets_from_client{user="hello"} 6726279921 (6.26 GB)
telemt_user_octets_to_client{user="hello"} 151046901733 (140.67 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 86
telemt_user_unique_ips_recent_window{user="hello"} 35
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 32333.5 (8h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 390148
telemt_connections_bad_total 30966
telemt_handshake_timeouts_total 35578
telemt_upstream_connect_attempt_total 8999
telemt_upstream_connect_success_total 8999
telemt_upstream_connect_attempts_per_request{bucket="1"} 8999
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5032
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3966
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 188
telemt_me_reconnect_attempts_total 8383
telemt_me_reconnect_success_total 7356
telemt_me_reader_eof_total 7743
telemt_me_idle_close_by_peer_total 7743
telemt_me_seq_mismatch_total 4
telemt_me_route_drop_no_conn_total 123221
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 310650
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 697
telemt_desync_full_logged_total 282
telemt_desync_suppressed_total 415
telemt_desync_frames_bucket_total{bucket="1_2"} 269
telemt_desync_frames_bucket_total{bucket="3_10"} 245
telemt_desync_frames_bucket_total{bucket="gt_10"} 183
telemt_pool_swap_total 24
telemt_me_writer_removed_unexpected_total 7464
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 7341
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 108
telemt_user_connections_total{user="hello"} 310325
telemt_user_connections_current{user="hello"} 144
telemt_user_octets_from_client{user="hello"} 4089654868 (3.81 GB)
telemt_user_octets_to_client{user="hello"} 88612964744 (82.53 GB)
telemt_user_unique_ips_current{user="hello"} 56
telemt_user_unique_ips_recent_window{user="hello"} 23
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 32333.1 (8h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 412681
telemt_connections_bad_total 3195
telemt_handshake_timeouts_total 2673
telemt_upstream_connect_attempt_total 9884
telemt_upstream_connect_success_total 9845
telemt_upstream_connect_fail_total 39
telemt_upstream_connect_attempts_per_request{bucket="1"} 9884
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5168
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4568
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 107
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 39
telemt_me_keepalive_timeout_total 206
telemt_me_reconnect_attempts_total 11929
telemt_me_reconnect_success_total 8169
telemt_me_reader_eof_total 8569
telemt_me_idle_close_by_peer_total 8569
telemt_me_route_drop_no_conn_total 141165
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 382801
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 2218
telemt_desync_full_logged_total 856
telemt_desync_suppressed_total 1362
telemt_desync_frames_bucket_total{bucket="1_2"} 815
telemt_desync_frames_bucket_total{bucket="3_10"} 954
telemt_desync_frames_bucket_total{bucket="gt_10"} 449
telemt_pool_swap_total 12
telemt_me_writer_removed_unexpected_total 8397
telemt_me_refill_failed_total 116
telemt_me_writer_restored_same_endpoint_total 8169
telemt_me_async_recovery_trigger_total 48
telemt_me_writer_removed_unexpected_minus_restored_total 228
telemt_user_connections_total{user="hello"} 382595
telemt_user_connections_current{user="hello"} 271
telemt_user_octets_from_client{user="hello"} 6491745140 (6.05 GB)
telemt_user_octets_to_client{user="hello"} 141138484760 (131.45 GB)
telemt_user_unique_ips_current{user="hello"} 89
telemt_user_unique_ips_recent_window{user="hello"} 35
```