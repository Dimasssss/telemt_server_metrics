# Server Metrics 2026-03-12 19:05:35 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 47215.0 (13h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1679881
telemt_connections_bad_total 20527
telemt_handshake_timeouts_total 15971
telemt_upstream_connect_attempt_total 9346
telemt_upstream_connect_success_total 9294
telemt_upstream_connect_fail_total 52
telemt_upstream_connect_attempts_per_request{bucket="1"} 9346
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4856
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4407
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 31
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 52
telemt_me_keepalive_timeout_total 571
telemt_me_reconnect_attempts_total 15736
telemt_me_reconnect_success_total 6890
telemt_me_reader_eof_total 7459
telemt_me_idle_close_by_peer_total 7458
telemt_me_route_drop_no_conn_total 656684
telemt_me_route_drop_channel_closed_total 10
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1570379
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7977
telemt_desync_full_logged_total 2029
telemt_desync_suppressed_total 5948
telemt_desync_frames_bucket_total{bucket="1_2"} 2079
telemt_desync_frames_bucket_total{bucket="3_10"} 2879
telemt_desync_frames_bucket_total{bucket="gt_10"} 3019
telemt_pool_swap_total 29
telemt_me_writer_removed_unexpected_total 7261
telemt_me_refill_failed_total 275
telemt_me_writer_restored_same_endpoint_total 6877
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 371
telemt_user_connections_total{user="hello"} 1569864
telemt_user_connections_current{user="hello"} 1436
telemt_user_octets_from_client{user="hello"} 24341800172 (22.67 GB)
telemt_user_octets_to_client{user="hello"} 535357355508 (498.59 GB)
telemt_user_unique_ips_current{user="hello"} 412
telemt_user_unique_ips_recent_window{user="hello"} 184
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 76835.5 (21h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 717585
telemt_connections_bad_total 9472
telemt_handshake_timeouts_total 29753
telemt_upstream_connect_attempt_total 19597
telemt_upstream_connect_success_total 19568
telemt_upstream_connect_fail_total 29
telemt_upstream_connect_attempts_per_request{bucket="1"} 19597
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10365
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9120
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 83
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 29
telemt_me_keepalive_timeout_total 3368
telemt_me_reconnect_attempts_total 14144
telemt_me_reconnect_success_total 14058
telemt_me_reader_eof_total 14948
telemt_me_idle_close_by_peer_total 14948
telemt_me_route_drop_no_conn_total 229393
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 646401
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2837
telemt_desync_full_logged_total 869
telemt_desync_suppressed_total 1968
telemt_desync_frames_bucket_total{bucket="1_2"} 1119
telemt_desync_frames_bucket_total{bucket="3_10"} 927
telemt_desync_frames_bucket_total{bucket="gt_10"} 791
telemt_pool_swap_total 76
telemt_me_writer_removed_unexpected_total 14208
telemt_me_writer_restored_same_endpoint_total 14049
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 150
telemt_user_connections_total{user="hello"} 648277
telemt_user_connections_current{user="hello"} 497
telemt_user_octets_from_client{user="hello"} 10991846544 (10.24 GB)
telemt_user_octets_to_client{user="hello"} 243691984607 (226.96 GB)
telemt_user_msgs_from_client{user="hello"} 6476
telemt_user_msgs_to_client{user="hello"} 18854
telemt_user_unique_ips_current{user="hello"} 147
telemt_user_unique_ips_recent_window{user="hello"} 79
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 76835.4 (21h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1485725
telemt_connections_bad_total 7177
telemt_handshake_timeouts_total 102304
telemt_upstream_connect_attempt_total 18243
telemt_upstream_connect_success_total 18238
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 18243
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9808
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8358
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 67
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 1183
telemt_me_reconnect_attempts_total 15257
telemt_me_reconnect_success_total 14013
telemt_me_reader_eof_total 14780
telemt_me_idle_close_by_peer_total 14779
telemt_me_route_drop_no_conn_total 489254
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1135689
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4729
telemt_desync_full_logged_total 1458
telemt_desync_suppressed_total 3271
telemt_desync_frames_bucket_total{bucket="1_2"} 746
telemt_desync_frames_bucket_total{bucket="3_10"} 1711
telemt_desync_frames_bucket_total{bucket="gt_10"} 2272
telemt_pool_swap_total 68
telemt_me_writer_removed_unexpected_total 14138
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 13972
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 125
telemt_user_connections_total{user="hello"} 1135554
telemt_user_connections_current{user="hello"} 837
telemt_user_octets_from_client{user="hello"} 17836915064 (16.61 GB)
telemt_user_octets_to_client{user="hello"} 417088009013 (388.44 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 245
telemt_user_unique_ips_recent_window{user="hello"} 117
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 76835.9 (21h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 907083
telemt_connections_bad_total 12954
telemt_handshake_timeouts_total 67003
telemt_upstream_connect_attempt_total 19803
telemt_upstream_connect_success_total 19724
telemt_upstream_connect_fail_total 79
telemt_upstream_connect_attempts_per_request{bucket="1"} 19803
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11094
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8617
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 13
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 79
telemt_me_keepalive_timeout_total 1638
telemt_me_reconnect_attempts_total 23590
telemt_me_reconnect_success_total 15865
telemt_me_reader_eof_total 16950
telemt_me_idle_close_by_peer_total 16950
telemt_me_route_drop_no_conn_total 320651
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 784597
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
telemt_me_writer_removed_unexpected_total 16235
telemt_me_refill_failed_total 239
telemt_me_writer_restored_same_endpoint_total 15844
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 108
telemt_me_writer_removed_unexpected_minus_restored_total 370
telemt_user_connections_total{user="hello"} 783955
telemt_user_connections_current{user="hello"} 486
telemt_user_octets_from_client{user="hello"} 11003683400 (10.25 GB)
telemt_user_octets_to_client{user="hello"} 322453387264 (300.31 GB)
telemt_user_unique_ips_current{user="hello"} 163
telemt_user_unique_ips_recent_window{user="hello"} 85
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 76835.8 (21h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1016961
telemt_connections_bad_total 11555
telemt_handshake_timeouts_total 8360
telemt_upstream_connect_attempt_total 24052
telemt_upstream_connect_success_total 23761
telemt_upstream_connect_fail_total 291
telemt_upstream_connect_attempts_per_request{bucket="1"} 24052
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12143
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11491
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 119
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 291
telemt_me_keepalive_timeout_total 1391
telemt_me_reconnect_attempts_total 30920
telemt_me_reconnect_success_total 19886
telemt_me_reader_eof_total 20902
telemt_me_idle_close_by_peer_total 20902
telemt_me_seq_mismatch_total 33
telemt_me_route_drop_no_conn_total 379540
telemt_me_route_drop_channel_closed_total 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 933120
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 37
telemt_me_hardswap_pending_ttl_expired_total 10
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 3511
telemt_desync_full_logged_total 1225
telemt_desync_suppressed_total 2286
telemt_desync_frames_bucket_total{bucket="1_2"} 989
telemt_desync_frames_bucket_total{bucket="3_10"} 1172
telemt_desync_frames_bucket_total{bucket="gt_10"} 1350
telemt_pool_swap_total 36
telemt_me_writer_removed_unexpected_total 20454
telemt_me_refill_failed_total 342
telemt_me_writer_restored_same_endpoint_total 19842
telemt_me_writer_restored_fallback_total 44
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 568
telemt_user_connections_total{user="hello"} 932991
telemt_user_connections_current{user="hello"} 692
telemt_user_octets_from_client{user="hello"} 11566633860 (10.77 GB)
telemt_user_octets_to_client{user="hello"} 315216001496 (293.57 GB)
telemt_user_unique_ips_current{user="hello"} 200
telemt_user_unique_ips_recent_window{user="hello"} 103
```