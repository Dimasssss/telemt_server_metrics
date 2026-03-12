# Server Metrics 2026-03-12 19:10:42 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 47521.7 (13h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1688595
telemt_connections_bad_total 20532
telemt_handshake_timeouts_total 16216
telemt_upstream_connect_attempt_total 9369
telemt_upstream_connect_success_total 9317
telemt_upstream_connect_fail_total 52
telemt_upstream_connect_attempts_per_request{bucket="1"} 9369
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4868
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4418
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 31
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 52
telemt_me_keepalive_timeout_total 571
telemt_me_reconnect_attempts_total 15759
telemt_me_reconnect_success_total 6913
telemt_me_reader_eof_total 7484
telemt_me_idle_close_by_peer_total 7483
telemt_me_route_drop_no_conn_total 660473
telemt_me_route_drop_channel_closed_total 10
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1578236
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7996
telemt_desync_full_logged_total 2039
telemt_desync_suppressed_total 5957
telemt_desync_frames_bucket_total{bucket="1_2"} 2087
telemt_desync_frames_bucket_total{bucket="3_10"} 2882
telemt_desync_frames_bucket_total{bucket="gt_10"} 3027
telemt_pool_swap_total 29
telemt_me_writer_removed_unexpected_total 7286
telemt_me_refill_failed_total 275
telemt_me_writer_restored_same_endpoint_total 6900
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 373
telemt_user_connections_total{user="hello"} 1577728
telemt_user_connections_current{user="hello"} 1383
telemt_user_octets_from_client{user="hello"} 24463081444 (22.78 GB)
telemt_user_octets_to_client{user="hello"} 537325550172 (500.42 GB)
telemt_user_unique_ips_current{user="hello"} 386
telemt_user_unique_ips_recent_window{user="hello"} 202
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 77142.2 (21h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 720666
telemt_connections_bad_total 9472
telemt_handshake_timeouts_total 29821
telemt_upstream_connect_attempt_total 19637
telemt_upstream_connect_success_total 19608
telemt_upstream_connect_fail_total 29
telemt_upstream_connect_attempts_per_request{bucket="1"} 19637
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10385
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9140
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 83
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 29
telemt_me_keepalive_timeout_total 3368
telemt_me_reconnect_attempts_total 14184
telemt_me_reconnect_success_total 14098
telemt_me_reader_eof_total 14988
telemt_me_idle_close_by_peer_total 14988
telemt_me_route_drop_no_conn_total 230739
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 649341
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2846
telemt_desync_full_logged_total 872
telemt_desync_suppressed_total 1974
telemt_desync_frames_bucket_total{bucket="1_2"} 1119
telemt_desync_frames_bucket_total{bucket="3_10"} 932
telemt_desync_frames_bucket_total{bucket="gt_10"} 795
telemt_pool_swap_total 76
telemt_me_writer_removed_unexpected_total 14248
telemt_me_writer_restored_same_endpoint_total 14089
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 150
telemt_user_connections_total{user="hello"} 651217
telemt_user_connections_current{user="hello"} 521
telemt_user_octets_from_client{user="hello"} 11058889236 (10.30 GB)
telemt_user_octets_to_client{user="hello"} 244690606319 (227.89 GB)
telemt_user_msgs_from_client{user="hello"} 6476
telemt_user_msgs_to_client{user="hello"} 18854
telemt_user_unique_ips_current{user="hello"} 150
telemt_user_unique_ips_recent_window{user="hello"} 91
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 77142.1 (21h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1491702
telemt_connections_bad_total 7177
telemt_handshake_timeouts_total 102413
telemt_upstream_connect_attempt_total 18276
telemt_upstream_connect_success_total 18271
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 18276
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9824
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8375
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 67
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 1183
telemt_me_reconnect_attempts_total 15290
telemt_me_reconnect_success_total 14046
telemt_me_reader_eof_total 14813
telemt_me_idle_close_by_peer_total 14812
telemt_me_route_drop_no_conn_total 490967
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1140476
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4736
telemt_desync_full_logged_total 1461
telemt_desync_suppressed_total 3275
telemt_desync_frames_bucket_total{bucket="1_2"} 747
telemt_desync_frames_bucket_total{bucket="3_10"} 1714
telemt_desync_frames_bucket_total{bucket="gt_10"} 2275
telemt_pool_swap_total 68
telemt_me_writer_removed_unexpected_total 14171
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 14005
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 125
telemt_user_connections_total{user="hello"} 1140339
telemt_user_connections_current{user="hello"} 804
telemt_user_octets_from_client{user="hello"} 17919430756 (16.69 GB)
telemt_user_octets_to_client{user="hello"} 420618004757 (391.73 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 240
telemt_user_unique_ips_recent_window{user="hello"} 133
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 77142.6 (21h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 910533
telemt_connections_bad_total 12959
telemt_handshake_timeouts_total 67281
telemt_upstream_connect_attempt_total 19853
telemt_upstream_connect_success_total 19774
telemt_upstream_connect_fail_total 79
telemt_upstream_connect_attempts_per_request{bucket="1"} 19853
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11112
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8649
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 13
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 79
telemt_me_keepalive_timeout_total 1638
telemt_me_reconnect_attempts_total 23640
telemt_me_reconnect_success_total 15915
telemt_me_reader_eof_total 17000
telemt_me_idle_close_by_peer_total 17000
telemt_me_route_drop_no_conn_total 321989
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 787707
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1745
telemt_desync_full_logged_total 584
telemt_desync_suppressed_total 1161
telemt_desync_frames_bucket_total{bucket="1_2"} 490
telemt_desync_frames_bucket_total{bucket="3_10"} 675
telemt_desync_frames_bucket_total{bucket="gt_10"} 580
telemt_pool_swap_total 62
telemt_me_writer_removed_unexpected_total 16285
telemt_me_refill_failed_total 239
telemt_me_writer_restored_same_endpoint_total 15894
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 108
telemt_me_writer_removed_unexpected_minus_restored_total 370
telemt_user_connections_total{user="hello"} 787065
telemt_user_connections_current{user="hello"} 446
telemt_user_octets_from_client{user="hello"} 11661769492 (10.86 GB)
telemt_user_octets_to_client{user="hello"} 323503547464 (301.29 GB)
telemt_user_unique_ips_current{user="hello"} 154
telemt_user_unique_ips_recent_window{user="hello"} 82
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 77142.4 (21h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1021436
telemt_connections_bad_total 11668
telemt_handshake_timeouts_total 8394
telemt_upstream_connect_attempt_total 24091
telemt_upstream_connect_success_total 23800
telemt_upstream_connect_fail_total 291
telemt_upstream_connect_attempts_per_request{bucket="1"} 24091
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12156
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11516
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 120
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 291
telemt_me_keepalive_timeout_total 1392
telemt_me_reconnect_attempts_total 30959
telemt_me_reconnect_success_total 19925
telemt_me_reader_eof_total 20941
telemt_me_idle_close_by_peer_total 20941
telemt_me_seq_mismatch_total 33
telemt_me_route_drop_no_conn_total 381392
telemt_me_route_drop_channel_closed_total 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 936956
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 37
telemt_me_hardswap_pending_ttl_expired_total 10
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 3528
telemt_desync_full_logged_total 1234
telemt_desync_suppressed_total 2294
telemt_desync_frames_bucket_total{bucket="1_2"} 996
telemt_desync_frames_bucket_total{bucket="3_10"} 1178
telemt_desync_frames_bucket_total{bucket="gt_10"} 1354
telemt_pool_swap_total 36
telemt_me_writer_removed_unexpected_total 20493
telemt_me_refill_failed_total 342
telemt_me_writer_restored_same_endpoint_total 19881
telemt_me_writer_restored_fallback_total 44
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 568
telemt_user_connections_total{user="hello"} 936827
telemt_user_connections_current{user="hello"} 672
telemt_user_octets_from_client{user="hello"} 11618822920 (10.82 GB)
telemt_user_octets_to_client{user="hello"} 317277249144 (295.49 GB)
telemt_user_unique_ips_current{user="hello"} 191
telemt_user_unique_ips_recent_window{user="hello"} 97
```