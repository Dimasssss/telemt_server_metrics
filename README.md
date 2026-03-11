# Server Metrics 2026-03-11 06:31:45 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 57880.0 (16h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1143077
telemt_connections_bad_total 13234
telemt_handshake_timeouts_total 38573
telemt_upstream_connect_attempt_total 12226
telemt_upstream_connect_success_total 12217
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 12226
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6140
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6015
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 61
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 691
telemt_me_reconnect_attempts_total 20949
telemt_me_reconnect_success_total 9266
telemt_me_reader_eof_total 10077
telemt_me_idle_close_by_peer_total 10077
telemt_me_route_drop_no_conn_total 420390
telemt_me_route_drop_channel_closed_total 3
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1027790
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4853
telemt_desync_full_logged_total 1358
telemt_desync_suppressed_total 3495
telemt_desync_frames_bucket_total{bucket="1_2"} 1328
telemt_desync_frames_bucket_total{bucket="3_10"} 1821
telemt_desync_frames_bucket_total{bucket="gt_10"} 1704
telemt_pool_swap_total 44
telemt_me_writer_removed_unexpected_total 9719
telemt_me_refill_failed_total 363
telemt_me_writer_restored_same_endpoint_total 9260
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 453
telemt_user_connections_total{user="hello"} 1027457
telemt_user_connections_current{user="hello"} 1063
telemt_user_octets_from_client{user="hello"} 13604191820 (12.67 GB)
telemt_user_octets_to_client{user="hello"} 302076243468 (281.33 GB)
telemt_user_unique_ips_current{user="hello"} 308
telemt_user_unique_ips_recent_window{user="hello"} 173
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 57936.7 (16h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 439765
telemt_connections_bad_total 5043
telemt_handshake_timeouts_total 21708
telemt_upstream_connect_attempt_total 20926
telemt_upstream_connect_success_total 18015
telemt_upstream_connect_fail_total 2911
telemt_upstream_connect_attempts_per_request{bucket="1"} 20926
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8095
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7677
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 209
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2034
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2911
telemt_me_keepalive_timeout_total 2012
telemt_me_reconnect_attempts_total 12975
telemt_me_reconnect_success_total 12150
telemt_me_reader_eof_total 12844
telemt_me_idle_close_by_peer_total 12842
telemt_me_route_drop_no_conn_total 200107
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 376184
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1935
telemt_desync_full_logged_total 582
telemt_desync_suppressed_total 1353
telemt_desync_frames_bucket_total{bucket="1_2"} 617
telemt_desync_frames_bucket_total{bucket="3_10"} 693
telemt_desync_frames_bucket_total{bucket="gt_10"} 625
telemt_pool_swap_total 48
telemt_me_writer_removed_unexpected_total 12291
telemt_me_refill_failed_total 22
telemt_me_writer_restored_same_endpoint_total 12128
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 86
telemt_me_writer_removed_unexpected_minus_restored_total 141
telemt_user_connections_total{user="hello"} 378454
telemt_user_connections_current{user="hello"} 382
telemt_user_octets_from_client{user="hello"} 3798056882 (3.54 GB)
telemt_user_octets_to_client{user="hello"} 94094756920 (87.63 GB)
telemt_user_msgs_from_client{user="hello"} 7933
telemt_user_msgs_to_client{user="hello"} 11226
telemt_user_unique_ips_current{user="hello"} 122
telemt_user_unique_ips_recent_window{user="hello"} 66
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 57936.6 (16h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 749172
telemt_connections_bad_total 6436
telemt_handshake_timeouts_total 41164
telemt_upstream_connect_attempt_total 15575
telemt_upstream_connect_success_total 15372
telemt_upstream_connect_fail_total 203
telemt_upstream_connect_attempts_per_request{bucket="1"} 15575
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8384
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6902
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 86
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 203
telemt_me_keepalive_timeout_total 695
telemt_me_reconnect_attempts_total 22459
telemt_me_reconnect_success_total 11386
telemt_me_reader_eof_total 12281
telemt_me_idle_close_by_peer_total 12281
telemt_me_route_drop_no_conn_total 253335
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 669614
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1904
telemt_desync_full_logged_total 549
telemt_desync_suppressed_total 1355
telemt_desync_frames_bucket_total{bucket="1_2"} 441
telemt_desync_frames_bucket_total{bucket="3_10"} 690
telemt_desync_frames_bucket_total{bucket="gt_10"} 773
telemt_pool_swap_total 40
telemt_me_writer_removed_unexpected_total 11879
telemt_me_refill_failed_total 343
telemt_me_writer_restored_same_endpoint_total 11375
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 493
telemt_user_connections_total{user="hello"} 670445
telemt_user_connections_current{user="hello"} 534
telemt_user_octets_from_client{user="hello"} 7961875493 (7.42 GB)
telemt_user_octets_to_client{user="hello"} 199243695361 (185.56 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 175
telemt_user_unique_ips_recent_window{user="hello"} 89
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 57936.9 (16h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 570211
telemt_connections_bad_total 54350
telemt_handshake_timeouts_total 58470
telemt_upstream_connect_attempt_total 16499
telemt_upstream_connect_success_total 16499
telemt_upstream_connect_attempts_per_request{bucket="1"} 16499
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9244
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7251
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_me_keepalive_timeout_total 644
telemt_me_reconnect_attempts_total 14632
telemt_me_reconnect_success_total 13586
telemt_me_reader_eof_total 14427
telemt_me_idle_close_by_peer_total 14427
telemt_me_seq_mismatch_total 11
telemt_me_route_drop_no_conn_total 171602
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 441820
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 937
telemt_desync_full_logged_total 390
telemt_desync_suppressed_total 547
telemt_desync_frames_bucket_total{bucket="1_2"} 341
telemt_desync_frames_bucket_total{bucket="3_10"} 348
telemt_desync_frames_bucket_total{bucket="gt_10"} 248
telemt_pool_swap_total 52
telemt_me_writer_removed_unexpected_total 13744
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 13564
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 158
telemt_user_connections_total{user="hello"} 441366
telemt_user_connections_current{user="hello"} 389
telemt_user_octets_from_client{user="hello"} 5313433172 (4.95 GB)
telemt_user_octets_to_client{user="hello"} 121417799220 (113.08 GB)
telemt_user_unique_ips_current{user="hello"} 132
telemt_user_unique_ips_recent_window{user="hello"} 66
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 57936.6 (16h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 596935
telemt_connections_bad_total 5964
telemt_handshake_timeouts_total 4205
telemt_upstream_connect_attempt_total 16481
telemt_upstream_connect_success_total 16413
telemt_upstream_connect_fail_total 68
telemt_upstream_connect_attempts_per_request{bucket="1"} 16481
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8421
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7857
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 133
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 68
telemt_me_keepalive_timeout_total 675
telemt_me_reconnect_attempts_total 17168
telemt_me_reconnect_success_total 13383
telemt_me_reader_eof_total 14140
telemt_me_idle_close_by_peer_total 14140
telemt_me_route_drop_no_conn_total 195905
telemt_me_route_drop_channel_closed_total 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 543069
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 2555
telemt_desync_full_logged_total 989
telemt_desync_suppressed_total 1566
telemt_desync_frames_bucket_total{bucket="1_2"} 917
telemt_desync_frames_bucket_total{bucket="3_10"} 1093
telemt_desync_frames_bucket_total{bucket="gt_10"} 545
telemt_pool_swap_total 39
telemt_me_writer_removed_unexpected_total 13672
telemt_me_refill_failed_total 116
telemt_me_writer_restored_same_endpoint_total 13383
telemt_me_async_recovery_trigger_total 48
telemt_me_writer_removed_unexpected_minus_restored_total 289
telemt_user_connections_total{user="hello"} 542804
telemt_user_connections_current{user="hello"} 631
telemt_user_octets_from_client{user="hello"} 9516047511 (8.86 GB)
telemt_user_octets_to_client{user="hello"} 193746902466 (180.44 GB)
telemt_user_msgs_from_client{user="hello"} 122
telemt_user_msgs_to_client{user="hello"} 215
telemt_user_unique_ips_current{user="hello"} 173
telemt_user_unique_ips_recent_window{user="hello"} 84
```