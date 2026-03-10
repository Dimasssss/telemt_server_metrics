# Server Metrics 2026-03-10 20:57:29 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 23424.7 (6h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 670248
telemt_connections_bad_total 8151
telemt_handshake_timeouts_total 7914
telemt_upstream_connect_attempt_total 4954
telemt_upstream_connect_success_total 4945
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 4954
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2431
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2458
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 55
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 342
telemt_me_reconnect_attempts_total 15365
telemt_me_reconnect_success_total 3712
telemt_me_reader_eof_total 4123
telemt_me_idle_close_by_peer_total 4123
telemt_me_route_drop_no_conn_total 280618
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 632573
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3245
telemt_desync_full_logged_total 887
telemt_desync_suppressed_total 2358
telemt_desync_frames_bucket_total{bucket="1_2"} 912
telemt_desync_frames_bucket_total{bucket="3_10"} 1222
telemt_desync_frames_bucket_total{bucket="gt_10"} 1111
telemt_pool_swap_total 6
telemt_me_writer_removed_unexpected_total 4099
telemt_me_refill_failed_total 363
telemt_me_writer_restored_same_endpoint_total 3706
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 387
telemt_user_connections_total{user="hello"} 632382
telemt_user_connections_current{user="hello"} 822
telemt_user_octets_from_client{user="hello"} 9013953888 (8.39 GB)
telemt_user_octets_to_client{user="hello"} 191646638888 (178.48 GB)
telemt_user_unique_ips_current{user="hello"} 239
telemt_user_unique_ips_recent_window{user="hello"} 104
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 23481.4 (6h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 295083
telemt_connections_bad_total 1828
telemt_handshake_timeouts_total 17162
telemt_upstream_connect_attempt_total 11300
telemt_upstream_connect_success_total 8439
telemt_upstream_connect_fail_total 2861
telemt_upstream_connect_attempts_per_request{bucket="1"} 11300
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3499
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2701
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 209
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2030
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2861
telemt_me_keepalive_timeout_total 1336
telemt_me_reconnect_attempts_total 5074
telemt_me_reconnect_success_total 4272
telemt_me_reader_eof_total 4473
telemt_me_idle_close_by_peer_total 4471
telemt_me_route_drop_no_conn_total 159027
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 247185
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1423
telemt_desync_full_logged_total 385
telemt_desync_suppressed_total 1038
telemt_desync_frames_bucket_total{bucket="1_2"} 449
telemt_desync_frames_bucket_total{bucket="3_10"} 505
telemt_desync_frames_bucket_total{bucket="gt_10"} 469
telemt_pool_swap_total 15
telemt_me_writer_removed_unexpected_total 4352
telemt_me_refill_failed_total 22
telemt_me_writer_restored_same_endpoint_total 4251
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 86
telemt_me_writer_removed_unexpected_minus_restored_total 80
telemt_user_connections_total{user="hello"} 249449
telemt_user_connections_current{user="hello"} 268
telemt_user_octets_from_client{user="hello"} 2546670782 (2.37 GB)
telemt_user_octets_to_client{user="hello"} 58580453108 (54.56 GB)
telemt_user_msgs_from_client{user="hello"} 7933
telemt_user_msgs_to_client{user="hello"} 11226
telemt_user_unique_ips_current{user="hello"} 79
telemt_user_unique_ips_recent_window{user="hello"} 43
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 23481.3 (6h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 478277
telemt_connections_bad_total 2565
telemt_handshake_timeouts_total 33022
telemt_upstream_connect_attempt_total 6805
telemt_upstream_connect_success_total 6705
telemt_upstream_connect_fail_total 100
telemt_upstream_connect_attempts_per_request{bucket="1"} 6805
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3984
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2669
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 52
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 100
telemt_me_keepalive_timeout_total 160
telemt_me_reconnect_attempts_total 14140
telemt_me_reconnect_success_total 4412
telemt_me_reader_eof_total 4839
telemt_me_idle_close_by_peer_total 4839
telemt_me_route_drop_no_conn_total 165825
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 416458
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1372
telemt_desync_full_logged_total 381
telemt_desync_suppressed_total 991
telemt_desync_frames_bucket_total{bucket="1_2"} 311
telemt_desync_frames_bucket_total{bucket="3_10"} 469
telemt_desync_frames_bucket_total{bucket="gt_10"} 592
telemt_pool_swap_total 8
telemt_me_writer_removed_unexpected_total 4791
telemt_me_refill_failed_total 302
telemt_me_writer_restored_same_endpoint_total 4401
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 379
telemt_user_connections_total{user="hello"} 417396
telemt_user_connections_current{user="hello"} 386
telemt_user_octets_from_client{user="hello"} 6039186293 (5.62 GB)
telemt_user_octets_to_client{user="hello"} 132170359473 (123.09 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 141
telemt_user_unique_ips_recent_window{user="hello"} 66
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 23481.9 (6h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 325459
telemt_connections_bad_total 22919
telemt_handshake_timeouts_total 27989
telemt_upstream_connect_attempt_total 6326
telemt_upstream_connect_success_total 6326
telemt_upstream_connect_attempts_per_request{bucket="1"} 6326
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3394
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2931
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 119
telemt_me_reconnect_attempts_total 6109
telemt_me_reconnect_success_total 5091
telemt_me_reader_eof_total 5340
telemt_me_idle_close_by_peer_total 5340
telemt_me_seq_mismatch_total 2
telemt_me_route_drop_no_conn_total 105698
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 262313
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 671
telemt_desync_full_logged_total 275
telemt_desync_suppressed_total 396
telemt_desync_frames_bucket_total{bucket="1_2"} 262
telemt_desync_frames_bucket_total{bucket="3_10"} 238
telemt_desync_frames_bucket_total{bucket="gt_10"} 171
telemt_pool_swap_total 16
telemt_me_writer_removed_unexpected_total 5175
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 5078
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 84
telemt_user_connections_total{user="hello"} 261998
telemt_user_connections_current{user="hello"} 337
telemt_user_octets_from_client{user="hello"} 3881631452 (3.62 GB)
telemt_user_octets_to_client{user="hello"} 81488441712 (75.89 GB)
telemt_user_unique_ips_current{user="hello"} 99
telemt_user_unique_ips_recent_window{user="hello"} 58
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 23481.6 (6h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 344878
telemt_connections_bad_total 1041
telemt_handshake_timeouts_total 2164
telemt_upstream_connect_attempt_total 7325
telemt_upstream_connect_success_total 7296
telemt_upstream_connect_fail_total 29
telemt_upstream_connect_attempts_per_request{bucket="1"} 7325
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3806
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3388
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 100
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 29
telemt_me_keepalive_timeout_total 154
telemt_me_reconnect_attempts_total 9791
telemt_me_reconnect_success_total 6040
telemt_me_reader_eof_total 6323
telemt_me_idle_close_by_peer_total 6323
telemt_me_route_drop_no_conn_total 124361
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 324016
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 1876
telemt_desync_full_logged_total 706
telemt_desync_suppressed_total 1170
telemt_desync_frames_bucket_total{bucket="1_2"} 724
telemt_desync_frames_bucket_total{bucket="3_10"} 784
telemt_desync_frames_bucket_total{bucket="gt_10"} 368
telemt_pool_swap_total 6
telemt_me_writer_removed_unexpected_total 6244
telemt_me_refill_failed_total 116
telemt_me_writer_restored_same_endpoint_total 6040
telemt_me_async_recovery_trigger_total 48
telemt_me_writer_removed_unexpected_minus_restored_total 204
telemt_user_connections_total{user="hello"} 323909
telemt_user_connections_current{user="hello"} 513
telemt_user_octets_from_client{user="hello"} 6191303556 (5.77 GB)
telemt_user_octets_to_client{user="hello"} 110764872952 (103.16 GB)
telemt_user_unique_ips_current{user="hello"} 135
telemt_user_unique_ips_recent_window{user="hello"} 67
```