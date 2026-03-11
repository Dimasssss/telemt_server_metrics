# Server Metrics 2026-03-11 17:14:30 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 96444.6 (26h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2425224
telemt_connections_bad_total 45332
telemt_handshake_timeouts_total 54439
telemt_upstream_connect_attempt_total 20305
telemt_upstream_connect_success_total 20293
telemt_upstream_connect_fail_total 12
telemt_upstream_connect_attempts_per_request{bucket="1"} 20305
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10236
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9959
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 97
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 12
telemt_me_keepalive_timeout_total 5107
telemt_me_reconnect_attempts_total 33268
telemt_me_reconnect_success_total 15392
telemt_me_reader_eof_total 16669
telemt_me_idle_close_by_peer_total 16669
telemt_me_route_drop_no_conn_total 901688
telemt_me_route_drop_channel_closed_total 8
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2217270
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 11440
telemt_desync_full_logged_total 3139
telemt_desync_suppressed_total 8301
telemt_desync_frames_bucket_total{bucket="1_2"} 2822
telemt_desync_frames_bucket_total{bucket="3_10"} 4416
telemt_desync_frames_bucket_total{bucket="gt_10"} 4202
telemt_pool_swap_total 70
telemt_me_writer_removed_unexpected_total 16122
telemt_me_refill_failed_total 555
telemt_me_writer_restored_same_endpoint_total 15386
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 730
telemt_user_connections_total{user="hello"} 2215717
telemt_user_connections_current{user="hello"} 1390
telemt_user_octets_from_client{user="hello"} 29945625204 (27.89 GB)
telemt_user_octets_to_client{user="hello"} 624784394784 (581.88 GB)
telemt_user_unique_ips_current{user="hello"} 388
telemt_user_unique_ips_recent_window{user="hello"} 226
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 96501.2 (26h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 909508
telemt_connections_bad_total 15973
telemt_handshake_timeouts_total 76615
telemt_upstream_connect_attempt_total 30396
telemt_upstream_connect_success_total 27435
telemt_upstream_connect_fail_total 2961
telemt_upstream_connect_attempts_per_request{bucket="1"} 30396
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12877
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12309
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 209
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2040
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2961
telemt_me_keepalive_timeout_total 2667
telemt_me_reconnect_attempts_total 21719
telemt_me_reconnect_success_total 19616
telemt_me_reader_eof_total 20752
telemt_me_idle_close_by_peer_total 20749
telemt_me_route_drop_no_conn_total 346478
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 761120
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3036
telemt_desync_full_logged_total 967
telemt_desync_suppressed_total 2069
telemt_desync_frames_bucket_total{bucket="1_2"} 920
telemt_desync_frames_bucket_total{bucket="3_10"} 1090
telemt_desync_frames_bucket_total{bucket="gt_10"} 1026
telemt_pool_swap_total 77
telemt_me_writer_removed_unexpected_total 19891
telemt_me_refill_failed_total 60
telemt_me_writer_restored_same_endpoint_total 19593
telemt_me_writer_restored_fallback_total 23
telemt_me_async_recovery_trigger_total 86
telemt_me_writer_removed_unexpected_minus_restored_total 275
telemt_user_connections_total{user="hello"} 763581
telemt_user_connections_current{user="hello"} 569
telemt_user_octets_from_client{user="hello"} 8783320086 (8.18 GB)
telemt_user_octets_to_client{user="hello"} 216122501756 (201.28 GB)
telemt_user_msgs_from_client{user="hello"} 7933
telemt_user_msgs_to_client{user="hello"} 11226
telemt_user_unique_ips_current{user="hello"} 152
telemt_user_unique_ips_recent_window{user="hello"} 91
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 96501.1 (26h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1554095
telemt_connections_bad_total 9123
telemt_handshake_timeouts_total 126405
telemt_upstream_connect_attempt_total 25031
telemt_upstream_connect_success_total 24710
telemt_upstream_connect_fail_total 321
telemt_upstream_connect_attempts_per_request{bucket="1"} 25031
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13286
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11297
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 126
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 321
telemt_me_keepalive_timeout_total 1766
telemt_me_reconnect_attempts_total 43207
telemt_me_reconnect_success_total 18741
telemt_me_reader_eof_total 20330
telemt_me_idle_close_by_peer_total 20330
telemt_me_route_drop_no_conn_total 567028
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1358850
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 9
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3572
telemt_desync_full_logged_total 1049
telemt_desync_suppressed_total 2523
telemt_desync_frames_bucket_total{bucket="1_2"} 874
telemt_desync_frames_bucket_total{bucket="3_10"} 1349
telemt_desync_frames_bucket_total{bucket="gt_10"} 1349
telemt_pool_swap_total 54
telemt_me_writer_removed_unexpected_total 19765
telemt_me_refill_failed_total 759
telemt_me_writer_restored_same_endpoint_total 18729
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 1024
telemt_user_connections_total{user="hello"} 1358544
telemt_user_connections_current{user="hello"} 880
telemt_user_octets_from_client{user="hello"} 16765215353 (15.61 GB)
telemt_user_octets_to_client{user="hello"} 412546491837 (384.21 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 248
telemt_user_unique_ips_recent_window{user="hello"} 149
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 96501.7 (26h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1115006
telemt_connections_bad_total 77987
telemt_handshake_timeouts_total 106114
telemt_upstream_connect_attempt_total 25992
telemt_upstream_connect_success_total 25992
telemt_upstream_connect_attempts_per_request{bucket="1"} 25992
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14192
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11795
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 1186
telemt_me_reconnect_attempts_total 23291
telemt_me_reconnect_success_total 21153
telemt_me_reader_eof_total 22436
telemt_me_idle_close_by_peer_total 22435
telemt_me_seq_mismatch_total 21
telemt_me_route_drop_no_conn_total 368100
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 897565
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 32
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1879
telemt_desync_full_logged_total 716
telemt_desync_suppressed_total 1163
telemt_desync_frames_bucket_total{bucket="1_2"} 672
telemt_desync_frames_bucket_total{bucket="3_10"} 664
telemt_desync_frames_bucket_total{bucket="gt_10"} 543
telemt_pool_swap_total 81
telemt_me_writer_removed_unexpected_total 21447
telemt_me_refill_failed_total 64
telemt_me_writer_restored_same_endpoint_total 21122
telemt_me_writer_restored_fallback_total 31
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 294
telemt_user_connections_total{user="hello"} 896843
telemt_user_connections_current{user="hello"} 546
telemt_user_octets_from_client{user="hello"} 10775655776 (10.04 GB)
telemt_user_octets_to_client{user="hello"} 272105074560 (253.42 GB)
telemt_user_unique_ips_current{user="hello"} 157
telemt_user_unique_ips_recent_window{user="hello"} 95
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 1177.6 (0h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 22925
telemt_handshake_timeouts_total 146
telemt_upstream_connect_attempt_total 288
telemt_upstream_connect_success_total 288
telemt_upstream_connect_attempts_per_request{bucket="1"} 288
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 182
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 102
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 174
telemt_me_reconnect_success_total 173
telemt_me_reader_eof_total 136
telemt_me_idle_close_by_peer_total 136
telemt_me_route_drop_no_conn_total 6748
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 21078
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 44
telemt_desync_full_logged_total 17
telemt_desync_suppressed_total 27
telemt_desync_frames_bucket_total{bucket="1_2"} 14
telemt_desync_frames_bucket_total{bucket="3_10"} 9
telemt_desync_frames_bucket_total{bucket="gt_10"} 21
telemt_me_writer_removed_unexpected_total 159
telemt_me_writer_restored_same_endpoint_total 151
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 256
telemt_user_connections_total{user="hello"} 21079
telemt_user_connections_current{user="hello"} 676
telemt_user_octets_from_client{user="hello"} 174955472 (166.85 MB)
telemt_user_octets_to_client{user="hello"} 5840553508 (5.44 GB)
telemt_user_unique_ips_current{user="hello"} 173
telemt_user_unique_ips_recent_window{user="hello"} 107
```