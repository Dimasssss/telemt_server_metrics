# Server Metrics 2026-03-12 14:45:03 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 31583.0 (8h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1126171
telemt_connections_bad_total 16368
telemt_handshake_timeouts_total 11815
telemt_upstream_connect_attempt_total 6240
telemt_upstream_connect_success_total 6206
telemt_upstream_connect_fail_total 34
telemt_upstream_connect_attempts_per_request{bucket="1"} 6240
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3307
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2889
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 34
telemt_me_keepalive_timeout_total 406
telemt_me_reconnect_attempts_total 8486
telemt_me_reconnect_success_total 4584
telemt_me_reader_eof_total 4889
telemt_me_idle_close_by_peer_total 4888
telemt_me_route_drop_no_conn_total 400463
telemt_me_route_drop_channel_closed_total 8
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1062572
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5717
telemt_desync_full_logged_total 1432
telemt_desync_suppressed_total 4285
telemt_desync_frames_bucket_total{bucket="1_2"} 1461
telemt_desync_frames_bucket_total{bucket="3_10"} 2060
telemt_desync_frames_bucket_total{bucket="gt_10"} 2196
telemt_pool_swap_total 21
telemt_me_writer_removed_unexpected_total 4759
telemt_me_refill_failed_total 121
telemt_me_writer_restored_same_endpoint_total 4571
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 175
telemt_user_connections_total{user="hello"} 1062305
telemt_user_connections_current{user="hello"} 1466
telemt_user_octets_from_client{user="hello"} 16885712656 (15.73 GB)
telemt_user_octets_to_client{user="hello"} 309576324756 (288.32 GB)
telemt_user_unique_ips_current{user="hello"} 408
telemt_user_unique_ips_recent_window{user="hello"} 190
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 61203.6 (17h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 520947
telemt_connections_bad_total 5561
telemt_handshake_timeouts_total 26494
telemt_upstream_connect_attempt_total 14594
telemt_upstream_connect_success_total 14587
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 14594
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7226
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7345
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 16
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_keepalive_timeout_total 1161
telemt_me_reconnect_attempts_total 11430
telemt_me_reconnect_success_total 11366
telemt_me_reader_eof_total 12075
telemt_me_idle_close_by_peer_total 12075
telemt_me_route_drop_no_conn_total 151517
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 464025
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1765
telemt_desync_full_logged_total 555
telemt_desync_suppressed_total 1210
telemt_desync_frames_bucket_total{bucket="1_2"} 751
telemt_desync_frames_bucket_total{bucket="3_10"} 573
telemt_desync_frames_bucket_total{bucket="gt_10"} 441
telemt_pool_swap_total 62
telemt_me_writer_removed_unexpected_total 11469
telemt_me_writer_restored_same_endpoint_total 11357
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 103
telemt_user_connections_total{user="hello"} 464524
telemt_user_connections_current{user="hello"} 558
telemt_user_octets_from_client{user="hello"} 7170002003 (6.68 GB)
telemt_user_octets_to_client{user="hello"} 164710055322 (153.40 GB)
telemt_user_msgs_from_client{user="hello"} 353
telemt_user_msgs_to_client{user="hello"} 423
telemt_user_unique_ips_current{user="hello"} 162
telemt_user_unique_ips_recent_window{user="hello"} 77
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 61203.3 (17h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1118262
telemt_connections_bad_total 6017
telemt_handshake_timeouts_total 79827
telemt_upstream_connect_attempt_total 14692
telemt_upstream_connect_success_total 14687
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 14692
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7975
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6650
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 58
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 970
telemt_me_reconnect_attempts_total 12509
telemt_me_reconnect_success_total 11289
telemt_me_reader_eof_total 11905
telemt_me_idle_close_by_peer_total 11905
telemt_me_route_drop_no_conn_total 294717
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 809915
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3382
telemt_desync_full_logged_total 1037
telemt_desync_suppressed_total 2345
telemt_desync_frames_bucket_total{bucket="1_2"} 503
telemt_desync_frames_bucket_total{bucket="3_10"} 1229
telemt_desync_frames_bucket_total{bucket="gt_10"} 1650
telemt_pool_swap_total 58
telemt_me_writer_removed_unexpected_total 11368
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 11248
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 79
telemt_user_connections_total{user="hello"} 810103
telemt_user_connections_current{user="hello"} 947
telemt_user_octets_from_client{user="hello"} 10706815224 (9.97 GB)
telemt_user_octets_to_client{user="hello"} 257187142645 (239.52 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 261
telemt_user_unique_ips_recent_window{user="hello"} 147
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 61203.9 (17h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 656850
telemt_connections_bad_total 7692
telemt_handshake_timeouts_total 56771
telemt_upstream_connect_attempt_total 16273
telemt_upstream_connect_success_total 16208
telemt_upstream_connect_fail_total 65
telemt_upstream_connect_attempts_per_request{bucket="1"} 16273
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9187
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7008
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 13
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 65
telemt_me_keepalive_timeout_total 1348
telemt_me_reconnect_attempts_total 14404
telemt_me_reconnect_success_total 13167
telemt_me_reader_eof_total 13940
telemt_me_idle_close_by_peer_total 13940
telemt_me_route_drop_no_conn_total 221629
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 559415
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1118
telemt_desync_full_logged_total 385
telemt_desync_suppressed_total 733
telemt_desync_frames_bucket_total{bucket="1_2"} 310
telemt_desync_frames_bucket_total{bucket="3_10"} 457
telemt_desync_frames_bucket_total{bucket="gt_10"} 351
telemt_pool_swap_total 53
telemt_me_writer_removed_unexpected_total 13306
telemt_me_refill_failed_total 37
telemt_me_writer_restored_same_endpoint_total 13146
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 108
telemt_me_writer_removed_unexpected_minus_restored_total 139
telemt_user_connections_total{user="hello"} 558917
telemt_user_connections_current{user="hello"} 665
telemt_user_octets_from_client{user="hello"} 6774182160 (6.31 GB)
telemt_user_octets_to_client{user="hello"} 225281264464 (209.81 GB)
telemt_user_unique_ips_current{user="hello"} 188
telemt_user_unique_ips_recent_window{user="hello"} 110
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 61203.8 (17h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 739415
telemt_connections_bad_total 5272
telemt_handshake_timeouts_total 5914
telemt_upstream_connect_attempt_total 19062
telemt_upstream_connect_success_total 18833
telemt_upstream_connect_fail_total 229
telemt_upstream_connect_attempts_per_request{bucket="1"} 19062
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9540
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9191
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 95
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 229
telemt_me_keepalive_timeout_total 1076
telemt_me_reconnect_attempts_total 23022
telemt_me_reconnect_success_total 15793
telemt_me_reader_eof_total 16553
telemt_me_idle_close_by_peer_total 16553
telemt_me_seq_mismatch_total 27
telemt_me_route_drop_no_conn_total 255446
telemt_me_route_drop_channel_closed_total 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 684170
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 31
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 2759
telemt_desync_full_logged_total 931
telemt_desync_suppressed_total 1828
telemt_desync_frames_bucket_total{bucket="1_2"} 787
telemt_desync_frames_bucket_total{bucket="3_10"} 956
telemt_desync_frames_bucket_total{bucket="gt_10"} 1016
telemt_pool_swap_total 30
telemt_me_writer_removed_unexpected_total 16181
telemt_me_refill_failed_total 224
telemt_me_writer_restored_same_endpoint_total 15759
telemt_me_writer_restored_fallback_total 34
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 388
telemt_user_connections_total{user="hello"} 684070
telemt_user_connections_current{user="hello"} 861
telemt_user_octets_from_client{user="hello"} 7992821452 (7.44 GB)
telemt_user_octets_to_client{user="hello"} 187341795572 (174.48 GB)
telemt_user_unique_ips_current{user="hello"} 233
telemt_user_unique_ips_recent_window{user="hello"} 112
```