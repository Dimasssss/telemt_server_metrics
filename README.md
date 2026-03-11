# Server Metrics 2026-03-11 09:04:24 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 67038.8 (18h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1408861
telemt_connections_bad_total 15971
telemt_handshake_timeouts_total 40359
telemt_upstream_connect_attempt_total 14015
telemt_upstream_connect_success_total 14006
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 14015
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7088
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6855
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 62
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 761
telemt_me_reconnect_attempts_total 22301
telemt_me_reconnect_success_total 10614
telemt_me_reader_eof_total 11503
telemt_me_idle_close_by_peer_total 11503
telemt_me_route_drop_no_conn_total 517903
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1278177
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 6285
telemt_desync_full_logged_total 1738
telemt_desync_suppressed_total 4547
telemt_desync_frames_bucket_total{bucket="1_2"} 1654
telemt_desync_frames_bucket_total{bucket="3_10"} 2386
telemt_desync_frames_bucket_total{bucket="gt_10"} 2245
telemt_pool_swap_total 52
telemt_me_writer_removed_unexpected_total 11081
telemt_me_refill_failed_total 363
telemt_me_writer_restored_same_endpoint_total 10608
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 467
telemt_user_connections_total{user="hello"} 1277845
telemt_user_connections_current{user="hello"} 1416
telemt_user_octets_from_client{user="hello"} 16911986508 (15.75 GB)
telemt_user_octets_to_client{user="hello"} 367886547000 (342.62 GB)
telemt_user_unique_ips_current{user="hello"} 372
telemt_user_unique_ips_recent_window{user="hello"} 195
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 67095.6 (18h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 543627
telemt_connections_bad_total 9121
telemt_handshake_timeouts_total 29979
telemt_upstream_connect_attempt_total 22918
telemt_upstream_connect_success_total 19992
telemt_upstream_connect_fail_total 2926
telemt_upstream_connect_attempts_per_request{bucket="1"} 22918
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9090
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8659
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 209
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2034
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2926
telemt_me_keepalive_timeout_total 2077
telemt_me_reconnect_attempts_total 14519
telemt_me_reconnect_success_total 13684
telemt_me_reader_eof_total 14484
telemt_me_idle_close_by_peer_total 14482
telemt_me_route_drop_no_conn_total 228634
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 461090
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2145
telemt_desync_full_logged_total 660
telemt_desync_suppressed_total 1485
telemt_desync_frames_bucket_total{bucket="1_2"} 715
telemt_desync_frames_bucket_total{bucket="3_10"} 772
telemt_desync_frames_bucket_total{bucket="gt_10"} 658
telemt_pool_swap_total 57
telemt_me_writer_removed_unexpected_total 13844
telemt_me_refill_failed_total 22
telemt_me_writer_restored_same_endpoint_total 13662
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 86
telemt_me_writer_removed_unexpected_minus_restored_total 160
telemt_user_connections_total{user="hello"} 463330
telemt_user_connections_current{user="hello"} 516
telemt_user_octets_from_client{user="hello"} 4493213670 (4.18 GB)
telemt_user_octets_to_client{user="hello"} 124135382612 (115.61 GB)
telemt_user_msgs_from_client{user="hello"} 7933
telemt_user_msgs_to_client{user="hello"} 11226
telemt_user_unique_ips_current{user="hello"} 148
telemt_user_unique_ips_recent_window{user="hello"} 76
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 67095.5 (18h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 942063
telemt_connections_bad_total 7259
telemt_handshake_timeouts_total 85656
telemt_upstream_connect_attempt_total 18108
telemt_upstream_connect_success_total 17888
telemt_upstream_connect_fail_total 220
telemt_upstream_connect_attempts_per_request{bucket="1"} 18108
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9751
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8048
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 89
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 220
telemt_me_keepalive_timeout_total 760
telemt_me_reconnect_attempts_total 25814
telemt_me_reconnect_success_total 13453
telemt_me_reader_eof_total 14463
telemt_me_idle_close_by_peer_total 14463
telemt_me_route_drop_no_conn_total 309524
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 811143
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2320
telemt_desync_full_logged_total 688
telemt_desync_suppressed_total 1632
telemt_desync_frames_bucket_total{bucket="1_2"} 563
telemt_desync_frames_bucket_total{bucket="3_10"} 841
telemt_desync_frames_bucket_total{bucket="gt_10"} 916
telemt_pool_swap_total 44
telemt_me_writer_removed_unexpected_total 14008
telemt_me_refill_failed_total 383
telemt_me_writer_restored_same_endpoint_total 13442
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 555
telemt_user_connections_total{user="hello"} 811945
telemt_user_connections_current{user="hello"} 822
telemt_user_octets_from_client{user="hello"} 9623577241 (8.96 GB)
telemt_user_octets_to_client{user="hello"} 245703683973 (228.83 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 231
telemt_user_unique_ips_recent_window{user="hello"} 123
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 67095.9 (18h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 693083
telemt_connections_bad_total 62875
telemt_handshake_timeouts_total 67810
telemt_upstream_connect_attempt_total 18566
telemt_upstream_connect_success_total 18566
telemt_upstream_connect_attempts_per_request{bucket="1"} 18566
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10335
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8227
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_me_keepalive_timeout_total 693
telemt_me_reconnect_attempts_total 16265
telemt_me_reconnect_success_total 15211
telemt_me_reader_eof_total 16150
telemt_me_idle_close_by_peer_total 16149
telemt_me_seq_mismatch_total 12
telemt_me_route_drop_no_conn_total 216184
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 540879
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1243
telemt_desync_full_logged_total 469
telemt_desync_suppressed_total 774
telemt_desync_frames_bucket_total{bucket="1_2"} 415
telemt_desync_frames_bucket_total{bucket="3_10"} 470
telemt_desync_frames_bucket_total{bucket="gt_10"} 358
telemt_pool_swap_total 61
telemt_me_writer_removed_unexpected_total 15391
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 15188
telemt_me_writer_restored_fallback_total 23
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 180
telemt_user_connections_total{user="hello"} 540254
telemt_user_connections_current{user="hello"} 561
telemt_user_octets_from_client{user="hello"} 6333421260 (5.90 GB)
telemt_user_octets_to_client{user="hello"} 152728498244 (142.24 GB)
telemt_user_unique_ips_current{user="hello"} 160
telemt_user_unique_ips_recent_window{user="hello"} 87
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 67095.5 (18h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 733960
telemt_connections_bad_total 5982
telemt_handshake_timeouts_total 6926
telemt_upstream_connect_attempt_total 18335
telemt_upstream_connect_success_total 18261
telemt_upstream_connect_fail_total 74
telemt_upstream_connect_attempts_per_request{bucket="1"} 18335
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9409
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8702
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 148
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 74
telemt_me_keepalive_timeout_total 748
telemt_me_reconnect_attempts_total 18580
telemt_me_reconnect_success_total 14788
telemt_me_reader_eof_total 15635
telemt_me_idle_close_by_peer_total 15635
telemt_me_route_drop_no_conn_total 248782
telemt_me_route_drop_channel_closed_total 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 664739
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 2879
telemt_desync_full_logged_total 1090
telemt_desync_suppressed_total 1789
telemt_desync_frames_bucket_total{bucket="1_2"} 1009
telemt_desync_frames_bucket_total{bucket="3_10"} 1191
telemt_desync_frames_bucket_total{bucket="gt_10"} 679
telemt_pool_swap_total 48
telemt_me_writer_removed_unexpected_total 15094
telemt_me_refill_failed_total 116
telemt_me_writer_restored_same_endpoint_total 14788
telemt_me_async_recovery_trigger_total 48
telemt_me_writer_removed_unexpected_minus_restored_total 306
telemt_user_connections_total{user="hello"} 664427
telemt_user_connections_current{user="hello"} 758
telemt_user_octets_from_client{user="hello"} 10670892667 (9.94 GB)
telemt_user_octets_to_client{user="hello"} 239356991766 (222.92 GB)
telemt_user_msgs_from_client{user="hello"} 122
telemt_user_msgs_to_client{user="hello"} 215
telemt_user_unique_ips_current{user="hello"} 200
telemt_user_unique_ips_recent_window{user="hello"} 108
```