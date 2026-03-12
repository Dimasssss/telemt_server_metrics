# Server Metrics 2026-03-12 14:14:23 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 29743.0 (8h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1054539
telemt_connections_bad_total 12076
telemt_handshake_timeouts_total 10857
telemt_upstream_connect_attempt_total 5844
telemt_upstream_connect_success_total 5810
telemt_upstream_connect_fail_total 34
telemt_upstream_connect_attempts_per_request{bucket="1"} 5844
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3091
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2710
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 34
telemt_me_keepalive_timeout_total 393
telemt_me_reconnect_attempts_total 8199
telemt_me_reconnect_success_total 4300
telemt_me_reader_eof_total 4599
telemt_me_idle_close_by_peer_total 4598
telemt_me_route_drop_no_conn_total 373450
telemt_me_route_drop_channel_closed_total 7
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 998150
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5361
telemt_desync_full_logged_total 1349
telemt_desync_suppressed_total 4012
telemt_desync_frames_bucket_total{bucket="1_2"} 1343
telemt_desync_frames_bucket_total{bucket="3_10"} 1947
telemt_desync_frames_bucket_total{bucket="gt_10"} 2071
telemt_pool_swap_total 20
telemt_me_writer_removed_unexpected_total 4473
telemt_me_refill_failed_total 121
telemt_me_writer_restored_same_endpoint_total 4287
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 173
telemt_user_connections_total{user="hello"} 997906
telemt_user_connections_current{user="hello"} 1498
telemt_user_octets_from_client{user="hello"} 16194334220 (15.08 GB)
telemt_user_octets_to_client{user="hello"} 292462286768 (272.38 GB)
telemt_user_unique_ips_current{user="hello"} 401
telemt_user_unique_ips_recent_window{user="hello"} 200
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 59363.5 (16h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 495911
telemt_connections_bad_total 5337
telemt_handshake_timeouts_total 25484
telemt_upstream_connect_attempt_total 14165
telemt_upstream_connect_success_total 14158
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 14165
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6997
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7145
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 16
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_keepalive_timeout_total 1126
telemt_me_reconnect_attempts_total 11092
telemt_me_reconnect_success_total 11031
telemt_me_reader_eof_total 11732
telemt_me_idle_close_by_peer_total 11732
telemt_me_route_drop_no_conn_total 143959
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 440895
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1592
telemt_desync_full_logged_total 504
telemt_desync_suppressed_total 1088
telemt_desync_frames_bucket_total{bucket="1_2"} 669
telemt_desync_frames_bucket_total{bucket="3_10"} 533
telemt_desync_frames_bucket_total{bucket="gt_10"} 390
telemt_pool_swap_total 61
telemt_me_writer_removed_unexpected_total 11133
telemt_me_writer_restored_same_endpoint_total 11022
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 102
telemt_user_connections_total{user="hello"} 441355
telemt_user_connections_current{user="hello"} 519
telemt_user_octets_from_client{user="hello"} 6777329475 (6.31 GB)
telemt_user_octets_to_client{user="hello"} 158140198478 (147.28 GB)
telemt_user_msgs_from_client{user="hello"} 353
telemt_user_msgs_to_client{user="hello"} 423
telemt_user_unique_ips_current{user="hello"} 158
telemt_user_unique_ips_recent_window{user="hello"} 81
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 59363.7 (16h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1075298
telemt_connections_bad_total 5726
telemt_handshake_timeouts_total 78405
telemt_upstream_connect_attempt_total 14171
telemt_upstream_connect_success_total 14166
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 14171
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7705
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6402
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 55
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 931
telemt_me_reconnect_attempts_total 10958
telemt_me_reconnect_success_total 10859
telemt_me_reader_eof_total 11435
telemt_me_idle_close_by_peer_total 11435
telemt_me_route_drop_no_conn_total 279631
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 770395
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3260
telemt_desync_full_logged_total 998
telemt_desync_suppressed_total 2262
telemt_desync_frames_bucket_total{bucket="1_2"} 480
telemt_desync_frames_bucket_total{bucket="3_10"} 1174
telemt_desync_frames_bucket_total{bucket="gt_10"} 1606
telemt_pool_swap_total 58
telemt_me_writer_removed_unexpected_total 10898
telemt_me_refill_failed_total 1
telemt_me_writer_restored_same_endpoint_total 10818
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 39
telemt_user_connections_total{user="hello"} 770590
telemt_user_connections_current{user="hello"} 929
telemt_user_octets_from_client{user="hello"} 10160112128 (9.46 GB)
telemt_user_octets_to_client{user="hello"} 246758946809 (229.81 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 274
telemt_user_unique_ips_recent_window{user="hello"} 133
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 59363.8 (16h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 622244
telemt_connections_bad_total 7686
telemt_handshake_timeouts_total 55436
telemt_upstream_connect_attempt_total 15677
telemt_upstream_connect_success_total 15615
telemt_upstream_connect_fail_total 62
telemt_upstream_connect_attempts_per_request{bucket="1"} 15677
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8859
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6743
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 13
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 62
telemt_me_keepalive_timeout_total 1315
telemt_me_reconnect_attempts_total 13899
telemt_me_reconnect_success_total 12664
telemt_me_reader_eof_total 13433
telemt_me_idle_close_by_peer_total 13433
telemt_me_route_drop_no_conn_total 209900
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 527424
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1080
telemt_desync_full_logged_total 375
telemt_desync_suppressed_total 705
telemt_desync_frames_bucket_total{bucket="1_2"} 301
telemt_desync_frames_bucket_total{bucket="3_10"} 444
telemt_desync_frames_bucket_total{bucket="gt_10"} 335
telemt_pool_swap_total 53
telemt_me_writer_removed_unexpected_total 12799
telemt_me_refill_failed_total 37
telemt_me_writer_restored_same_endpoint_total 12643
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 108
telemt_me_writer_removed_unexpected_minus_restored_total 135
telemt_user_connections_total{user="hello"} 526927
telemt_user_connections_current{user="hello"} 701
telemt_user_octets_from_client{user="hello"} 5794938124 (5.40 GB)
telemt_user_octets_to_client{user="hello"} 213105852648 (198.47 GB)
telemt_user_unique_ips_current{user="hello"} 182
telemt_user_unique_ips_recent_window{user="hello"} 96
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 59363.8 (16h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 704099
telemt_connections_bad_total 3604
telemt_handshake_timeouts_total 5654
telemt_upstream_connect_attempt_total 18607
telemt_upstream_connect_success_total 18381
telemt_upstream_connect_fail_total 226
telemt_upstream_connect_attempts_per_request{bucket="1"} 18607
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9320
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8961
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 93
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 226
telemt_me_keepalive_timeout_total 1053
telemt_me_reconnect_attempts_total 22656
telemt_me_reconnect_success_total 15428
telemt_me_reader_eof_total 16176
telemt_me_idle_close_by_peer_total 16176
telemt_me_seq_mismatch_total 25
telemt_me_route_drop_no_conn_total 242095
telemt_me_route_drop_channel_closed_total 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 653527
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 29
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 2668
telemt_desync_full_logged_total 898
telemt_desync_suppressed_total 1770
telemt_desync_frames_bucket_total{bucket="1_2"} 752
telemt_desync_frames_bucket_total{bucket="3_10"} 926
telemt_desync_frames_bucket_total{bucket="gt_10"} 990
telemt_pool_swap_total 29
telemt_me_writer_removed_unexpected_total 15811
telemt_me_refill_failed_total 224
telemt_me_writer_restored_same_endpoint_total 15397
telemt_me_writer_restored_fallback_total 31
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 383
telemt_user_connections_total{user="hello"} 653429
telemt_user_connections_current{user="hello"} 856
telemt_user_octets_from_client{user="hello"} 7626836164 (7.10 GB)
telemt_user_octets_to_client{user="hello"} 177913239680 (165.69 GB)
telemt_user_unique_ips_current{user="hello"} 229
telemt_user_unique_ips_recent_window{user="hello"} 106
```