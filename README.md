# Server Metrics 2026-03-11 01:47:14 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 40809.5 (11h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 821848
telemt_connections_bad_total 9532
telemt_handshake_timeouts_total 11032
telemt_upstream_connect_attempt_total 8900
telemt_upstream_connect_success_total 8891
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 8900
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4454
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4378
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 58
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 487
telemt_me_reconnect_attempts_total 18443
telemt_me_reconnect_success_total 6776
telemt_me_reader_eof_total 7415
telemt_me_idle_close_by_peer_total 7415
telemt_me_route_drop_no_conn_total 334723
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 777189
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3637
telemt_desync_full_logged_total 1023
telemt_desync_suppressed_total 2614
telemt_desync_frames_bucket_total{bucket="1_2"} 1062
telemt_desync_frames_bucket_total{bucket="3_10"} 1358
telemt_desync_frames_bucket_total{bucket="gt_10"} 1217
telemt_pool_swap_total 25
telemt_me_writer_removed_unexpected_total 7196
telemt_me_refill_failed_total 363
telemt_me_writer_restored_same_endpoint_total 6770
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 420
telemt_user_connections_total{user="hello"} 776946
telemt_user_connections_current{user="hello"} 400
telemt_user_octets_from_client{user="hello"} 10652432848 (9.92 GB)
telemt_user_octets_to_client{user="hello"} 235577187748 (219.40 GB)
telemt_user_unique_ips_current{user="hello"} 156
telemt_user_unique_ips_recent_window{user="hello"} 54
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 40866.2 (11h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 352893
telemt_connections_bad_total 2407
telemt_handshake_timeouts_total 17982
telemt_upstream_connect_attempt_total 16199
telemt_upstream_connect_success_total 13313
telemt_upstream_connect_fail_total 2886
telemt_upstream_connect_attempts_per_request{bucket="1"} 16199
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5806
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5266
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 209
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2032
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2886
telemt_me_keepalive_timeout_total 1723
telemt_me_reconnect_attempts_total 9100
telemt_me_reconnect_success_total 8283
telemt_me_reader_eof_total 8753
telemt_me_idle_close_by_peer_total 8751
telemt_me_route_drop_no_conn_total 175159
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 301717
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1787
telemt_desync_full_logged_total 513
telemt_desync_suppressed_total 1274
telemt_desync_frames_bucket_total{bucket="1_2"} 547
telemt_desync_frames_bucket_total{bucket="3_10"} 637
telemt_desync_frames_bucket_total{bucket="gt_10"} 603
telemt_pool_swap_total 33
telemt_me_writer_removed_unexpected_total 8392
telemt_me_refill_failed_total 22
telemt_me_writer_restored_same_endpoint_total 8262
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 86
telemt_me_writer_removed_unexpected_minus_restored_total 109
telemt_user_connections_total{user="hello"} 303986
telemt_user_connections_current{user="hello"} 187
telemt_user_octets_from_client{user="hello"} 2873229178 (2.68 GB)
telemt_user_octets_to_client{user="hello"} 71954976452 (67.01 GB)
telemt_user_msgs_from_client{user="hello"} 7933
telemt_user_msgs_to_client{user="hello"} 11226
telemt_user_unique_ips_current{user="hello"} 71
telemt_user_unique_ips_recent_window{user="hello"} 31
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 40866.0 (11h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 587077
telemt_connections_bad_total 4227
telemt_handshake_timeouts_total 34327
telemt_upstream_connect_attempt_total 11165
telemt_upstream_connect_success_total 11011
telemt_upstream_connect_fail_total 154
telemt_upstream_connect_attempts_per_request{bucket="1"} 11165
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6142
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4799
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 70
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 154
telemt_me_keepalive_timeout_total 521
telemt_me_reconnect_attempts_total 18918
telemt_me_reconnect_success_total 7854
telemt_me_reader_eof_total 8541
telemt_me_idle_close_by_peer_total 8541
telemt_me_route_drop_no_conn_total 200382
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 519834
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1523
telemt_desync_full_logged_total 436
telemt_desync_suppressed_total 1087
telemt_desync_frames_bucket_total{bucket="1_2"} 344
telemt_desync_frames_bucket_total{bucket="3_10"} 523
telemt_desync_frames_bucket_total{bucket="gt_10"} 656
telemt_pool_swap_total 25
telemt_me_writer_removed_unexpected_total 8308
telemt_me_refill_failed_total 343
telemt_me_writer_restored_same_endpoint_total 7843
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 454
telemt_user_connections_total{user="hello"} 520747
telemt_user_connections_current{user="hello"} 256
telemt_user_octets_from_client{user="hello"} 6940991389 (6.46 GB)
telemt_user_octets_to_client{user="hello"} 159308097809 (148.37 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 97
telemt_user_unique_ips_recent_window{user="hello"} 44
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 40866.4 (11h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 436090
telemt_connections_bad_total 38775
telemt_handshake_timeouts_total 41803
telemt_upstream_connect_attempt_total 11846
telemt_upstream_connect_success_total 11846
telemt_upstream_connect_attempts_per_request{bucket="1"} 11846
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6663
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5181
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_timeout_total 425
telemt_me_reconnect_attempts_total 10800
telemt_me_reconnect_success_total 9765
telemt_me_reader_eof_total 10346
telemt_me_idle_close_by_peer_total 10346
telemt_me_seq_mismatch_total 7
telemt_me_route_drop_no_conn_total 131625
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 342012
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 733
telemt_desync_full_logged_total 293
telemt_desync_suppressed_total 440
telemt_desync_frames_bucket_total{bucket="1_2"} 280
telemt_desync_frames_bucket_total{bucket="3_10"} 253
telemt_desync_frames_bucket_total{bucket="gt_10"} 200
telemt_pool_swap_total 34
telemt_me_writer_removed_unexpected_total 9886
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 9747
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 121
telemt_user_connections_total{user="hello"} 341683
telemt_user_connections_current{user="hello"} 175
telemt_user_octets_from_client{user="hello"} 4260999192 (3.97 GB)
telemt_user_octets_to_client{user="hello"} 92524854564 (86.17 GB)
telemt_user_unique_ips_current{user="hello"} 63
telemt_user_unique_ips_recent_window{user="hello"} 28
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 40866.1 (11h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 460475
telemt_connections_bad_total 5338
telemt_handshake_timeouts_total 2966
telemt_upstream_connect_attempt_total 12197
telemt_upstream_connect_success_total 12147
telemt_upstream_connect_fail_total 50
telemt_upstream_connect_attempts_per_request{bucket="1"} 12197
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6274
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5757
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 114
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 50
telemt_me_keepalive_timeout_total 517
telemt_me_reconnect_attempts_total 13799
telemt_me_reconnect_success_total 10029
telemt_me_reader_eof_total 10563
telemt_me_idle_close_by_peer_total 10563
telemt_me_route_drop_no_conn_total 150980
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 421525
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 2296
telemt_desync_full_logged_total 892
telemt_desync_suppressed_total 1404
telemt_desync_frames_bucket_total{bucket="1_2"} 850
telemt_desync_frames_bucket_total{bucket="3_10"} 976
telemt_desync_frames_bucket_total{bucket="gt_10"} 470
telemt_pool_swap_total 22
telemt_me_writer_removed_unexpected_total 10275
telemt_me_refill_failed_total 116
telemt_me_writer_restored_same_endpoint_total 10029
telemt_me_async_recovery_trigger_total 48
telemt_me_writer_removed_unexpected_minus_restored_total 246
telemt_user_connections_total{user="hello"} 421217
telemt_user_connections_current{user="hello"} 236
telemt_user_octets_from_client{user="hello"} 8424336864 (7.85 GB)
telemt_user_octets_to_client{user="hello"} 149817743248 (139.53 GB)
telemt_user_unique_ips_current{user="hello"} 83
telemt_user_unique_ips_recent_window{user="hello"} 27
```